# الصدف للإنتاج الفني (Al Sadaf Production) / sadaf.tv

## What is the exact legal/brand name of the company in Arabic and English, and what does "الصدف" refer to as a brand name choice?

### Takeaway
The entity behind sadaf.tv appears, with high but not 100% confidence, to be the same company that Saudi/Gulf media refer to as "الصدف للإنتاج الصوتي والمرئي المحدودة" (Al-Sadaf Audio-Visual Production Company Limited), abbreviated "SMP" on the sadaf.tv site itself. No source explains the meaning/origin of the brand name "الصدف" (coincidence/seashell) — this is an unverified/unanswered point.

### Cited Findings
- The sadaf.tv homepage header shows the brand as "SMP الصدف" (logo alt text "SMP Logo") — [sadaf.tv](https://sadaf.tv)
- The site's only external link (LinkedIn) uses the URL slug `alsadaf-company-for-production`, implying an English name of "Alsadaf Company for Production" — [sadaf.tv](https://sadaf.tv); LinkedIn page itself returned HTTP 403 and could not be directly verified — [LinkedIn](https://www.linkedin.com/company/alsadaf-company-for-production/)
- An Odoo customer-reference page lists a company named "شركة الصدف للانتاج الصوتي والمرئي المحدودة" with the parenthetical "(SMP)" — matching the "SMP" label seen on sadaf.tv — described as a leading Saudi production company founded in 1988, with over 300 projects produced in more than 30 years — [Odoo](https://www.odoo.com/ar/customers/shrk-lsdf-llntj-lswty-wlmryy-lmhdwd-9535360)
- elcinema.com's profile of Hassan Assiri (حسن عسيري) names him director of "الصدف للإنتاج الصوتي والمرئي المحدودة" (Al Sadaf for Audio and Visual Production Ltd.), describing it as part of MBC Group and one of the largest private-sector TV production companies in the Arab world — [elcinema](https://elcinema.com/person/1102207/)
- Marefa (Arabic wiki) describes Hassan Assiri as general manager ("المدير العام") of Al Sadaf — [Marefa via search summary]
- An Argaam news item (title only; full article text could not be retrieved — WebFetch returned empty content) refers to "Sadaf for Audio and Visual Production Co." as a contracting party with "MBC Studios Projects Saudi Arabia Ltd." and states the company is "90% owned by Ara International Holding Co." — [Argaam](https://www.argaam.com/en/article/articledetail/id/1770237) (ownership % claim is from the search-engine summary of this page, not independently confirmed by direct fetch, so treat as lower-confidence)
- The user's framing refers to the company as "الصدف للإنتاج الفني" (Al Sadaf for Artistic Production) — this exact phrase was not found verbatim on sadaf.tv or in any of the sources retrieved; sources instead consistently use "للإنتاج الصوتي والمرئي" (for audio-visual production). This may be a colloquial/alternate rendering of the same brand, but the exact phrase "للإنتاج الفني" is **not verified / غير مؤكد** in any primary or media source found.

### Inferences
- "SMP" on the site header very likely stands for "Sadaf Media Production" or similar, abbreviating the audio-visual production name, but this is an inference, not confirmed by any source.
- sadaf.tv is likely the official/updated web presence of the older, MBC-linked "Al Sadaf for Audio and Visual Production" company (same abbreviation "SMP", same LinkedIn slug), rather than a separate, newer company — but this link is not explicitly stated anywhere; no single source bridges both identities directly by name and confirms they are one and the same legal entity.

### Gaps
- The exact meaning/symbolism of "الصدف" (coincidence or seashell) as a branding choice is not discussed in any source found. **Not verified.**
- No source gives a precise, single authoritative "legal name" matching sadaf.tv's branding (the site itself never states a formal legal/CR name on the pages crawled).
- Could not independently verify the Argaam article's ownership claim (90% owned by Ara International Holding Co.) because WebFetch returned no usable content from that URL; this should be re-verified by a human or another tool before being treated as fact.

## What specific services does it offer?

### Takeaway
sadaf.tv's own site describes its services only in broad, generic terms ("comprehensive/integrated solutions covering all stages of artistic production from planning to execution") with no itemized service list (no explicit mention of music videos, advertising, or event production on the crawled pages). Separate, older sources describe the company (under its audio-visual production name) as a television drama series producer with its own studios and post-production facilities.

### Cited Findings
- sadaf.tv homepage "Our Services" (خدماتنا) section: "We provide comprehensive solutions covering all stages of artistic production from planning to execution" — no specific service types (e.g., music videos, drama, events) are listed in the text — [sadaf.tv](https://sadaf.tv)
- The site has a dedicated `/services` page link in its navigation, but its content was not successfully retrieved in this research pass (only the homepage and `/about` were fetched; `/about` returned content with no body text, and `/services` was not separately fetched) — **gap, see below**
- The Odoo customer profile describes the (likely same) company's capabilities as: audio-visual and television production, post-production including advanced graphics, and in-house television studios of various sizes with high-definition equipment run by engineering/technical staff — [Odoo](https://www.odoo.com/ar/customers/shrk-lsdf-llntj-lswty-wlmryy-lmhdwd-9535360)
- elcinema describes the company (via Hassan Assiri's bio) as one of the largest private-sector companies making Arab TV drama series, and credits it/him with 128+ TV projects over 25 years, mostly television drama series (not music videos) — [elcinema](https://elcinema.com/person/1102207/)
- sadaf.tv also runs/hosts "طريق المواهب" (Talent Road), described on the homepage as "the largest Arab project for discovering actors, actresses, and professionals in cinema and television" — a talent-registration/casting platform, not a production service per se — [sadaf.tv](https://sadaf.tv)
- The homepage also offers an "idea submission" feature for writers/creators to submit project ideas to the company — [sadaf.tv](https://sadaf.tv)

### Inferences
- The company's core, historically documented business is Arabic-language television drama series production (serials/مسلسلات), plus associated studio and post-production services — not primarily music video production.
- No evidence was found that the company specializes in or markets music video production, artist management, or advertising production specifically; these should not be assumed.

### Gaps
- The `/services` subpage content (which likely lists itemized services) was not retrieved in this pass — a follow-up fetch of `https://sadaf.tv/services` is recommended to confirm or rule out music video / advertising / event production as explicit offerings.
- Whether the company offers artist management, event production, or advertising production is **not verified** — no source (official or media) mentions these specifically.

## What is on sadaf.tv — site structure and content summary?

### Takeaway
sadaf.tv is a multi-language (Arabic, English, French, Simplified Chinese) corporate site with four main navigation sections — Home, About (من نحن), Services (الخدمات), and Our Works (أعمالنا) — plus a "Talent Road" talent-registration feature and a contact form; it contains no itemized portfolio, no named clients/artists, and no direct contact details (phone/email/address) in the sections successfully crawled.

### Cited Findings
- Navigation: الرئيسية/Home (`/`), من نحن/About (`/about`), الخدمات/Services (`/services`), أعمالنا/Our Works (`/projects`) — [sadaf.tv](https://sadaf.tv)
- Homepage "Featured Works" (أعمالنا المميزة) section is described as showing "a selection of the latest works," but no actual project titles or client names appear in the crawled content — [sadaf.tv](https://sadaf.tv)
- Homepage "Contact Us" (تواصل معنا) section consists only of a form requesting name, email, subject, mobile number, country, city, and message — no published phone number, email address, or physical address appears on the page — [sadaf.tv](https://sadaf.tv)
- The only social/external link found anywhere on the crawled pages is the footer LinkedIn link: `https://www.linkedin.com/company/alsadaf-company-for-production/` — [sadaf.tv](https://sadaf.tv)
- The site footer shows a copyright notice "© 2026 sadaf.tv" in all four supported languages — [sadaf.tv](https://sadaf.tv)
- A direct fetch of `https://sadaf.tv/about` returned a page with navigation only and no visible About/history body text in the retrieved content — [sadaf.tv/about](https://sadaf.tv/about)
- A fetch of `https://sadaf.tv/ar` (attempting the Arabic-specific path) returned HTTP 404, suggesting the site's language switching does not use that URL pattern (likely uses a different locale-switch mechanism, e.g. a query parameter or client-side toggle) — [sadaf.tv/ar](https://sadaf.tv/ar)

### Inferences
- The site currently appears to be a relatively new or recently redesigned corporate/marketing site (placeholder-style "Featured Works" with no real content, "Register"/"View details" links pointing to `#`), possibly launched or relaunched in 2025-2026, which would explain the lack of populated portfolio and contact content.

### Gaps
- `/services` and `/projects` pages were not individually fetched in this research pass; their content (which may include specific service lists or named projects/clients) is unknown and should be checked in a follow-up.
- No explicit founding date, history, or key-people names appear anywhere on the crawled sadaf.tv pages themselves — this information, where it exists, comes only from third-party sources (elcinema, Odoo, Argaam), not from the company's own site content retrieved so far.

## What notable artists, songs, or TV productions has it produced or been credited for? Is Hassan Asiri (حسن عسيري) among them?

### Takeaway
Hassan Assiri (حسن عسيري) is not merely an artist the company "worked with" — multiple independent sources identify him as the director/general manager of Al Sadaf's audio-visual production company, i.e., a key executive, not just a contracted artist. The company (under Hassan Assiri's leadership) is credited with numerous Arabic TV drama series, but no music videos or songs were found attributed to it.

### Cited Findings
- elcinema.com identifies Hassan Assiri as director of "الصدف للإنتاج الصوتي والمرئي المحدودة," part of MBC Group, overseeing 128+ TV projects over 25 years, with 133 producer credits and 69 acting credits — [elcinema](https://elcinema.com/person/1102207/)
- Marefa (Arabic encyclopedia, via search summary) describes him as an actor/producer and general manager of the company, born February 23, 1967 (elcinema's fetched page instead states February 14, 1967, born in Al-Kharj — birth date/place details conflict between sources) — [Marefa](https://www.marefa.org/%D8%AD%D8%B3%D9%86_%D8%B9%D8%B3%D9%8A%D8%B1%D9%8A); [elcinema](https://elcinema.com/person/1102207/)
- Notable series credited to him/the company per elcinema: recent (2025–2026) — سندس ج3, بنات عمير, وننسى اللي كان, الست موناليزا, المحامية; earlier popular titles — سليم ودستة حريم, محسن الهزاني أمير الحب والحرب, عندما يكتمل القمر, سوق الدماء, أنا وهو; also عندما يزهر الخريف (parts 1–2), أسوار (part 2 as producer, part 1 as actor), الملك فاروق (supervising role), كلام الناس (parts 1–3, producer) — [elcinema](https://elcinema.com/person/1102207/)
- Alraimedia (via search result title) describes him as "الفنان والمنتج السعودي" (the Saudi artist and producer) who discussed career milestones on the program "مسرح الحياة," and reportedly said the company's studio was designed by professional Egyptian set designers — [Alraimedia](https://www.alraimedia.com/article/1759346/فنون/منوعات/حسن-عسيري-المعاهد-الفنية-توازي-كليات-الطب-في-مخرجاتها) (content summarized from search snippet; full article not directly fetched, so detail should be treated as moderate-confidence)
- Awards credited to his/the company's productions: gold award for عندما يزهر الخريف at the Arab Festival, Tunisia (2015); multiple gold/silver awards for الملك فاروق at the Cairo TV Festival (2008) plus a gold directing award at the Gulf festival in Bahrain (2008); gold award for أسوار at the Bahrain TV Festival (2007), with a 15-minute excerpt screened at the Emmy festival in New York (2007); gold award for الساكنات في قلوبنا at the Jordan Arab Media Festival (2012) — [elcinema](https://elcinema.com/person/1102207/)
- Frequent collaborators listed on his elcinema profile: Omar Al-Dini (عمر الديني), Riyadh Ahmed (رياض أحمد), Firas Sharbatati (فراس شرباتي), Hussam Mohammed Al-Hamad (حسام محمد الحمد), Walid Al-Hashim (وليد الهشيم) — [elcinema](https://elcinema.com/person/1102207/)
- A separate web search also surfaced that series titled "سواق وشغالة وأكثر" (named Best Gulf Comedy Series in Sayidaty magazine's Ramadan 2014 poll) and "ثانوية النسيم" (a controversial drama) were produced via Hassan Assiri's company, per an AI-generated search summary — this could not be independently verified by direct source fetch, so treat as **lower-confidence / needs verification**.

### Inferences
- Al Sadaf's demonstrated track record is almost entirely Arabic-language television drama series (مسلسلات), not music videos. No evidence links the company to music video production for any singer/artist, including Hassan Asiri himself (who appears to be a producer/executive and actor, not a singer).
- The user's question seems to assume Hassan Asiri might be a *client/artist* the company "worked with" for a music video — the research instead shows he is the company's *own director/general manager*, which is an important distinction for the brand profile.

### Gaps
- No music videos, songs, or music-industry productions/artists are attributed to the company in any source found. **Not verified** — if the user has reason to believe the company does music videos, this was not corroborated.
- sadaf.tv's own "Our Works" (/projects) page was not successfully fetched with real content (it showed only placeholder text), so it's unconfirmed whether the current sadaf.tv brand lists any of the above series as its own portfolio.

## What are its official social media account links/handles?

### Takeaway
The only official social media presence found, across both the live sadaf.tv site and web searches, is a LinkedIn company page; no Instagram, X/Twitter, YouTube, Snapchat, or TikTok accounts could be found or confirmed for sadaf.tv or Al Sadaf production company.

### Cited Findings
- sadaf.tv's footer links only to LinkedIn: `https://www.linkedin.com/company/alsadaf-company-for-production/` — [sadaf.tv](https://sadaf.tv)
- A direct WebFetch attempt on the LinkedIn URL returned HTTP 403 Forbidden, so the LinkedIn page's content (follower count, description, HQ, founding date as listed on LinkedIn) could not be verified directly — [LinkedIn](https://www.linkedin.com/company/alsadaf-company-for-production/)
- A targeted web search for "sadaf.tv instagram twitter" returned no results connecting that domain to any Instagram/Twitter/X account — all results were unrelated individuals also named "Sadaf" — [search results, no usable source]
- A targeted Arabic search for "الصدف للإنتاج" + YouTube/Instagram/channel terms returned no relevant results — [search results, no usable source]

### Inferences
- Given the site's generally sparse/placeholder state (no portfolio, no contact details), it is plausible the company either has no active public social media beyond LinkedIn, or its accounts use a name/handle not easily discoverable via these search queries (e.g., a handle unrelated to "sadaf" or "الصدف" in text).

### Gaps
- Instagram, X/Twitter, YouTube, Snapchat, and TikTok presence: **not found / not verified**. This should be explicitly flagged as unconfirmed rather than assumed absent, since a direct site crawl of `/about`, `/services`, and `/projects` subpages (which might contain additional social links) was not completed in this pass.
- LinkedIn page's actual content (employee count, HQ city listed, description) could not be verified due to a 403 error blocking direct access.

## Where is it headquartered, and is there any public business registration info?

### Takeaway
No source found states a specific city/address for the company's headquarters, though all sources agree it is a Saudi company; no commercial registration (CR) number or similar public registry identifier was found in any source.

### Cited Findings
- Multiple sources describe the company generically as "a leading Saudi production company" / "one of the MBC Group companies" without specifying a city — [Odoo](https://www.odoo.com/ar/customers/shrk-lsdf-llntj-lswty-wlmryy-lmhdwd-9535360); [elcinema](https://elcinema.com/person/1102207/)
- A web search specifically for the company's headquarters (Riyadh/Jeddah) returned no matching result; it surfaced only unrelated companies (e.g., SADAFCO dairy company in Jeddah, Sadara Studio in Riyadh) that are NOT the same entity — [search results, no usable source]
- A search summary referenced an Argaam article stating the company (as "Sadaf for Audio and Visual Production Co.") signed a SAR 52.9 million production-services contract with "MBC Studios Projects Saudi Arabia Ltd." (a wholly owned MBC Group subsidiary) around November 18, 2024, and that the company is reportedly 90% owned by "Ara International Holding Co." — this is from a search-engine-generated summary of the Argaam page; direct WebFetch of the article returned no usable text, so this claim is **moderate-confidence, not independently confirmed** — [Argaam](https://www.argaam.com/en/article/articledetail/id/1770237)
- No commercial registration (CR) number, Ministry of Commerce listing, or Chamber of Commerce record was found for this company in any source retrieved.

### Inferences
- Given its description as an MBC Group-linked company and the contract with an MBC subsidiary, the company's operations are likely tied to Saudi Arabia's broadcast/media production hubs (commonly Riyadh or Jeddah for MBC-affiliated studios), but this is inference only, not a stated fact.

### Gaps
- Exact HQ city/address: **not verified**.
- Commercial registration number / official Ministry of Commerce or Chamber of Commerce listing: **not found**.
- The Argaam ownership claim (90% owned by Ara International Holding Co.) needs independent re-verification — the full article text could not be retrieved in this research pass.

## What keywords/phrases would naturally describe this company for AI-answer/search purposes?

### Takeaway
Based on verified source material, the company is best described with TV-drama-production and Saudi-media-industry keywords; music-video-specific or event-production keywords are not supported by any source found and should not be used without a caveat.

### Cited Findings / Supported Keywords
- "شركة إنتاج تلفزيوني سعودية" (Saudi television production company) — supported by elcinema and Odoo descriptions — [elcinema](https://elcinema.com/person/1102207/); [Odoo](https://www.odoo.com/ar/customers/shrk-lsdf-llntj-lswty-wlmryy-lmhdwd-9535360)
- "شركة الصدف للإنتاج الصوتي والمرئي" (Al Sadaf Audio-Visual Production Company) — the name consistently used across third-party sources — [elcinema](https://elcinema.com/person/1102207/)
- "منتجة مسلسلات درامية عربية" (producer of Arabic drama series) — supported by the extensive filmography tied to Hassan Assiri/the company — [elcinema](https://elcinema.com/person/1102207/)
- "جزء من مجموعة MBC" / "MBC Group-affiliated production company" — [elcinema](https://elcinema.com/person/1102207/); Argaam summary
- "طريق المواهب" (Talent Road) — a talent-discovery/casting platform operated via sadaf.tv — [sadaf.tv](https://sadaf.tv)
- "SMP الصدف" — the brand's own self-label as shown on sadaf.tv — [sadaf.tv](https://sadaf.tv)

### Keywords NOT supported by evidence found (should not be used without caveat)
- "منتج فيديوهات كليبات" / "music video production company" — **not verified**; no source ties the company to music video production.
- Any specific city name (e.g., "شركة إنتاج فني في الرياض") — **not verified**; headquarters city is unconfirmed.
- "وكالة إدارة فنانين" (artist management agency) — **not verified**; no source describes this as a service.

### Inferences
- For AI-answer-engine optimization purposes, accurate descriptive phrases should emphasize "Saudi/Arab television drama production," "MBC Group-linked production house," and "Talent Road / طريق المواهب casting platform," while explicitly avoiding unverified claims about music videos, events, or advertising production.

### Gaps
- No official SEO/meta-description text from sadaf.tv itself (e.g., `<meta name="description">`) was captured in this research pass; a follow-up technical crawl (viewing page source/meta tags) would help confirm the company's own self-description for search engines.
