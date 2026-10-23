---
name: geo-optimization-guide
description: Plan, audit and measure GEO/AEO (AI search optimization) for ChatGPT, Google AI Overviews/AI Mode, Bing Copilot, Perplexity and Claude using the 91-action GDdash evidence-graded playbook.
disable-model-invocation: true
---

# GEO optimization playbook (GDdash GEO Guide 2027)

Source: "GEO Guide 2027: How to Improve Visibility in ChatGPT, AI Mode, and AI Search According to 200+ Top Experts and Resources" by John Shehata, GDdash (https://gddash.com/geo-optimization-guide/), published Oct 18, 2026, evidence audit Oct 18, 2026. 91 consolidated recommendations drawn from 250 source records, 1,329 evidence records and 204 distinct resources (Google, Microsoft Bing, OpenAI, Anthropic, Perplexity documentation plus practitioners such as Aleyda Solis, Lily Ray, Kevin Indig, Mike King, Dan Petrovic, Metehan Yeşilyurt and others).

## When to use this skill

Use it whenever the task involves:

- Auditing a site, page or brand for visibility in AI answers (ChatGPT search, Google AI Overviews / AI Mode, Bing Copilot, Perplexity, Claude, Gemini).
- Building a GEO/AEO roadmap, prioritized action list or checklist.
- Reviewing content, technical setup (crawlers, robots.txt, CDN/WAF, rendering, schema, llms.txt) or measurement for AI search.
- Evaluating a GEO tactic, vendor, case study or benchmark claim.
- Designing AI-visibility measurement: prompt panels, citation/mention/recommendation rates, AI referral attribution, ROI.

## Definitions

- **GEO (generative engine optimization):** improving how a website and its organization can be found, understood and accurately represented in AI-generated answers.
- **AEO (answer engine optimization):** overlapping work. **AI search optimization** is the plain-language umbrella for both.
- **ChatGPT optimization:** improving a website's eligibility, relevance and representation in ChatGPT search. It is not prompt writing or model fine-tuning.
- Each platform (Google AI Overviews/AI Mode, Bing Copilot, Perplexity, Claude) has its own controls and retrieval behavior. One platform's advice does not automatically apply to another.
- Being **retrieved, cited, mentioned or recommended** are different outcomes. None guarantees a visit, sale or other commercial result.

## Operating principles (apply to every answer)

1. **Start from the outcome, not the dashboard.** Accurate representation, qualified demand, subscriptions, reader loyalty: rank work by the business goal.
2. **Foundations before speculation.** Access, indexing, accurate facts and genuinely useful content come before formatting tricks, special files or lab tactics.
3. **Platform-specific, not generic.** Name the platform and product the advice applies to; check that operator's current documentation.
4. **Every recommendation is practical, not a guarantee.** Never promise citation, ranking, traffic or revenue lift. Apply advice only to the platforms and circumstances its sources support.
5. **Separate evidence classes.** Label claims as platform documentation, practitioner advice, research finding (with its sampling/lab limits), editorial judgment, or hypothesis. Lab results and observational correlations are not proof of live-platform effects. Multiple articles by one person are not multiple independent endorsements; syndicated repeats are not independent corroboration.
6. **No manipulation.** No fabricated reviews, invented credentials or bylines, hidden instructions, review gating, purchased praise, cosmetic date changes or scaled thin pages.
7. **Recheck live docs.** Crawler names, controls and reporting definitions change. The guide's platform checks date from Oct 13, 2026; verify before implementing.

## Priority scale

- **Do first:** relevant foundations (51 actions).
- **Do next:** worthwhile improvements (20).
- **Situational:** applies only to a specific need (18).
- **Test:** uncertain tactic for a bounded experiment only (2).

Priorities are editorial judgments by GDdash, not ratings from the cited experts.

## Where to start (5-step sequence)

1. **Choose the outcome.** Accurate brand descriptions, better answers to important questions, qualified visits, subscriptions or another meaningful result.
2. **Check access.** Verify indexing, intended search-bot permissions and actual infrastructure responses. Review search access and model-training choices separately.
3. **Fix important facts.** Correct contradictions in product, service and organization information across the website and relevant external profiles.
4. **Improve a small group of important pages.** Add original evidence, clear explanations and decision support to pages that serve real audience needs.
5. **Measure before expanding.** Save a baseline, repeat comparable observations, evaluate against costs and meaningful outcomes.

Starting points by business type (examples, not universal rules): a local business begins with accurate service details and relevant profiles; a software company prioritizes comparisons and product documentation; a publisher prioritizes original reporting and direct audience relationships.

## Platform distinctions

| Platform | Key distinction | Operator docs |
| --- | --- | --- |
| ChatGPT | OAI-SearchBot = search discovery; GPTBot = potential model training; ChatGPT-User = user-triggered fetching. | https://developers.openai.com/api/docs/bots |
| Google AI Overviews / AI Mode | Normal Search eligibility plus documented generative-AI inclusion controls in Search Console (including parent-property inheritance). No special AI files or fixed content chunks required. Google-Extended governs training, separate from Search. | https://developers.google.com/search/docs/fundamentals/ai-optimization-guide , https://support.google.com/webmasters/answer/16908024 |
| Bing / Copilot | Bing-specific crawl and display controls (e.g. section-level data-nosnippet). AI Performance report in Bing Webmaster Tools has its own scope; Bing citation counts and Google impressions are different measures. IndexNow supported. | https://blogs.bing.com/webmaster/2026/2/Introducing-AI-Performance-in-Bing-Webmaster-Tools-Public-Preview/ |
| Perplexity | PerplexityBot = search discovery; Perplexity-User = user-requested fetching. Verify legitimate crawler access via current published IP/verification guidance. | https://docs.perplexity.ai/docs/resources/perplexity-crawlers |
| Claude | Claude-SearchBot = search; ClaudeBot = potential training; Claude-User = user-requested retrieval. | https://support.claude.com/en/articles/8896518 |

For Gemini, Grok or any other interface, identify the specific product and its operator documentation before copying a policy. Google Search controls do not necessarily govern every Gemini experience.

## Tactics that need caution (common myths)

- **Structured data** supports specific documented purposes. Keep it accurate and consistent with visible content; check current eligibility. It does not guarantee an AI citation. FAQ/HowTo rich-result gains should be removed from Google business cases.
- **llms.txt and Markdown copies** need a named consumer and a maintenance owner. Google does not require them for Search AI features. Installation is not success.
- **Clear answers do not require fixed chunks.** No universal 40–60-word answer block or page-length target.
- **Freshness means accurate information.** Update facts when they change; a timestamp change alone adds nothing. No universal weekly refresh cycle is established.
- **A comparison citation is not a recommendation.** An answer can cite your comparison while recommending a competitor. Measure citations, mentions and recommendations separately.
- **Repeated mentions may share one original source.** Trace provenance of syndicated, paid or commonly owned pages before counting corroboration.
- **Lab results require live validation.** Historical GEO benchmarks and custom retrieval experiments do not establish live traffic or revenue effects.
- **Reviews:** invite genuine feedback where review platforms matter; correlations do not prove more reviews cause AI visibility. Never gate or buy reviews.
- **Speed scores:** fix measured usability/fetch problems; no universal speed or timeout threshold for AI citations exists.
- **User-agent allowlisting** alone is not provenance verification; use the provider's official verification methods.

## How to measure GEO progress

Choose a stable core of business-relevant prompts. For every run save: exact wording, date, platform, model or mode, language, location and conversation context. Repeat under comparable conditions. Record failed, empty and unsuccessful runs separately from valid answers that simply do not mention you. There is no universal prompt count or testing frequency; size the sample to goals, resources and observed variability.

| Outcome | Working definition | Does NOT establish |
| --- | --- | --- |
| Citation rate | Valid sampled answers linking to your domain ÷ all valid answers in the defined panel | That the brand was named or recommended |
| Brand mention rate | Valid sampled answers naming your entity ÷ all valid answers in the panel | A link, positive sentiment or a visit |
| Recommendation rate | Valid sampled answers explicitly recommending your offering ÷ valid answers to defined recommendation prompts | A sale or incremental revenue |
| Identifiable AI visits | Visits attributed to a defined AI source within the chosen analytics scope | All AI-influenced discovery or cross-session impact |
| Qualified outcomes | Relevant inquiries, sales, subscriptions or another explicitly defined goal | Causation without an appropriate comparison |

Rules:

- Document denominators and keep them consistent; report collection failures separately.
- Never merge sampled model answers, Search Console impressions, Bing citations and analytics sessions into one count.
- GA4's default channel grouping includes an **AI Assistant** channel, but Google AI Overviews and AI Mode traffic stays in **Organic Search**. Distinguish session, event and first-user scope. (https://support.google.com/analytics/answer/9756891)
- Google Search Console's Search generative-AI report (https://support.google.com/webmasters/answer/16984139) and its Discover counterpart (https://support.google.com/webmasters/answer/16983858) have their own thresholds, Pacific-time dates and availability limits.

## Practical workflow

1. **Choose questions:** topics and prompts that reflect real audience needs (from customer interviews, support, sales, site data; a synthetic prompt list is not demand).
2. **Record a baseline:** starting visibility (by platform/mode/market) and relevant website metrics.
3. **Make focused improvements:** improve selected pages and correct important facts using the action catalog below.
4. **Review results:** repeat comparable checks, compare against a control group, log confounders, and investigate before scaling.

## How to respond when using this skill

- **Audit requests:** walk the "Do first" actions in order of category (Strategy → Technical access → Content facts → Measurement), report findings per action number, and mark each as pass / issue / not applicable / needs data.
- **Roadmaps:** group actions by Do first → Do next → Situational → Test, assign the listed owner, and attach the "Check" metric as the success criterion.
- **Evaluating a tactic or vendor claim:** map it to the nearest action, state its evidence class and limits, and use Action 85 (vet vendor claims) and Action 91 (bounded experiments).
- Always cite the action number(s) and keep the evidence limit: "practical recommendation, not a guaranteed increase in citations or revenue."
- Do not change live settings (Search Console inclusion, robots, snippet controls, training policies) without explicit approval; document current state and propose.

---

# The complete GEO action catalog (91 actions)

Format: **What** (the recommendation) · **Do** (put it into practice) · **Check** (how to validate) · **Why** (priority rationale). Default evidence limit for every action unless stated: *practical recommendation, not a guaranteed increase in citations or revenue; apply only to the platforms and circumstances the sources support.*

## Content (23 actions)

### 1. Publish original research, reporting or tested experience that answers a real need
*Do first · Applies to: Cross-platform practice · Owner: Editorial + research · Key sources: Google Search Central, John Mueller, Aleyda Solis, Lily Ray +23 more*

- **What:** Give readers a useful reason to choose your page over interchangeable summaries. Originality can come from a well-documented test, a meaningful dataset, an interview or a clearer expert explanation.
- **Do:** For a software company, publish a reproducible product test with sample, period and exclusions. For a publisher, add firsthand reporting. For a retailer, document a fair comparison using real product measurements.
- **Check:** Evidence completeness, reader use and qualified outcomes; repeated citation observations are secondary.
- **Why:** Distinctive evidence gives readers a reason to use the page and makes claims independently checkable; citation lift remains uncertain.

### 2. Substantiate important claims with attributable primary evidence
*Do first · Applies to: Cross-platform practice · Owner: Editor + subject specialist · Key sources: Google, Microsoft Bing, Fabrice Canel, Krishna Madhavan +20 more*

- **What:** Make consequential claims checkable. Link to the original data or documentation and explain enough context for readers to understand what the evidence actually establishes.
- **Do:** Check the most consequential claims against primary sources; place scoped dates, methods and source links beside the claims.
- **Check:** Unsupported-claim rate, correction rate and traceable-source coverage.
- **Why:** Unsupported consequential claims create accuracy and trust risks regardless of how an answer engine discovers the page.

### 3. Show real authors, relevant expertise and editorial accountability
*Do first · Applies to: Cross-platform practice · Owner: Editorial operations · Key sources: Aleyda Solis, Lily Ray, Gianluca Fiorelli, Kevin Indig +17 more*

- **What:** Show who is responsible for the content and why their knowledge is relevant. A truthful byline and review process are useful trust signals; invented credentials undermine the entire page.
- **Do:** Verify the real author, role and expertise; explain review responsibility without inventing a byline or credential.
- **Check:** Sampled byline accuracy and editorial-policy compliance; no assumed author-schema citation lift.
- **Why:** Accountable authorship and relevant expertise help readers assess reliability; invented credentials create avoidable harm.

### 4. Make useful answers direct, self-contained and appropriately scoped
*Do first · Applies to: Cross-platform practice · Owner: Editor + content designer · Key sources: Google Search Central, Microsoft Bing, Aleyda Solis, Mike King +26 more*

- **What:** Answer the question before asking readers to work through background material. Keep each answer understandable in context, with necessary qualifications rather than a rigid word limit.
- **Do:** Answer the section question early, identify the relevant entity and preserve necessary caveats; retain deeper detail for readers.
- **Check:** Reader task completion and factual completeness; controlled appearance tests if useful.
- **Why:** A clear, qualified answer improves comprehension without depending on an unverified passage-length formula.

### 5. Use descriptive headings, semantic sections, lists and accessible comparison tables
*Do first · Applies to: Cross-platform practice · Owner: Content design + accessibility · Key sources: Google Search Central, Microsoft Bing, Fabrice Canel, Krishna Madhavan +22 more*

- **What:** Help readers locate the part of the page that solves their problem. Use tables for real comparisons and headings that describe the content beneath them.
- **Do:** Replace vague headings with descriptive ones; use a table only when the same attributes are compared and keep headers accessible.
- **Check:** Navigation/task success, accessibility checks and section comprehension.
- **Why:** Readable structure and accessible comparisons help people use the content and reduce ambiguity for retrievers.

### 6. Make comparisons and ranked lists fair, specific and evidenced
*Do first · Applies to: Cross-platform practice · Owner: Subject specialist + editor · Key sources: Google, Claire Taylor, Mateusz Makosiewicz, Josh Blyskal +2 more*

- **What:** Explain the criteria behind a recommendation. Disclose commercial relationships and avoid declaring your own product the best without evidence that supports the comparison.
- **Do:** State selection criteria, test dates, tradeoffs and conflicts of interest; substantiate each recommendation and offer legitimate alternatives.
- **Check:** Claim accuracy, decision usefulness and qualified engagement; no self-awarded best claims.
- **Why:** Readers need defensible comparison criteria; self-serving rankings and fabricated evaluations create trust and reputation risks.

### 7. Maintain an approved, dated source of truth for brand and product facts
*Do first · Applies to: Cross-platform practice · Owner: Product/brand owner + editorial · Key sources: Aleyda Solis, Kevin Indig, Dan Petrovic, Mateusz Makosiewicz +17 more*

- **What:** Keep a reliable record of names, products, specifications and policies. Consistent owned information gives readers and external writers a dependable place to verify facts.
- **Do:** Create a fact register for company identity, product capabilities, pricing scope and official URLs; assign a fact owner and review trigger.
- **Check:** Factual consistency across owned pages and sampled AI answers; material errors open/closed.
- **Why:** A maintained factual reference reduces contradictions across pages, teams and downstream representations.

### 8. Correct factual contradictions and trace stale claims across important sources
*Do first · Applies to: Cross-platform practice · Owner: Fact owner + editorial/PR · Key sources: Aleyda Solis, Mateusz Makosiewicz, Amanda Natividad, Lily Grozeva +7 more*

- **What:** Trace conflicting claims to their sources. Correct owned material first, then request legitimate third-party corrections where a consequential error remains.
- **Do:** Save an incorrect answer and its citations, identify the earliest source, fix owned facts and prepare evidence-backed correction requests.
- **Check:** Verified error resolution over repeated tests; distinguish stale facts from legitimate unfavorable opinion.
- **Why:** Material factual errors can mislead readers or buyers; traceable corrections address the underlying information problem.

### 9. Refresh material facts when they change and preserve useful evergreen work
*Do first · Applies to: Cross-platform practice · Owner: Editorial + product owner · Key sources: Microsoft Bing, Fabrice Canel, Krishna Madhavan, Meenaz Merchant +22 more*

- **What:** Update information because the facts changed or the explanation needs improvement. Useful older pages do not need replacement simply to obtain a recent timestamp.
- **Do:** Prioritize a high-value page with changed specifications or outdated evidence; update the underlying information before its date.
- **Check:** Stale-fact backlog, reader value and controlled page-cohort outcomes.
- **Why:** Changed facts can make valuable pages misleading; substantive maintenance has clearer value than changing timestamps.

### 10. Keep publication dates, substantive revision dates and change records truthful
*Do first · Applies to: Cross-platform practice · Owner: Editorial operations + CMS · Key sources: Aleyda Solis, Mike King, Kevin Indig, Claire Taylor +8 more*

- **What:** Separate original publication from substantive revision. Explain meaningful changes when readers need that context, and avoid cosmetic date updates.
- **Do:** Keep original publication and genuine revision dates separate; record material changes in a visible or maintained changelog.
- **Check:** Agreement among displayed dates, CMS fields and relevant metadata; no cosmetic-date-only updates.
- **Why:** Truthful dates help readers interpret timeliness and prevent cosmetic freshness from masquerading as new evidence.

### 11. Reject scaled low-value content, fake endorsements and hidden manipulation
*Do first · Applies to: Cross-platform practice · Owner: Editorial lead + compliance · Key sources: Google Search Central, Google, Google Search, Aleyda Solis +12 more*

- **What:** Avoid fabricated reviews, hidden instructions and mass-produced pages that add little value. A short-term visibility result does not justify undermining reader trust.
- **Do:** Review scaled templates and agency proposals for fabricated claims, hidden instructions, fake sentiment, thin duplication and undisclosed promotion.
- **Check:** Policy-risk defects removed and review coverage; retain legitimately useful lists and FAQs.
- **Why:** Fabrication, hidden manipulation and low-value scaling create direct editorial, reputation and platform-policy risks.

### 12. Keep human fact-checking and bounded permissions in AI-assisted workflows
*Do first · Applies to: Cross-platform practice · Owner: Editorial lead + workflow owner · Key sources: Google Search, Kevin Indig, Olivier Martinez, iPullRank +4 more*

- **What:** Have accountable people verify facts and approve consequential edits. Give automation clear limits and keep a record of what changed.
- **Do:** Require accountable human approval for material facts, citations, metadata and sensitive details in an AI-assisted workflow; log changes and permissions.
- **Check:** Review completion, factual error rate, privacy incidents and time saved without quality loss.
- **Why:** Human accountability and bounded permissions reduce factual and operational risks in AI-assisted production.

### 13. Provide timely original reporting and clear update context for news-sensitive needs
*Do first · Applies to: Publishers and news-sensitive content · Owner: Newsroom editor + SEO · Key sources: Louise Linehan / Ahrefs*

- **What:** Establish what happened, when it happened and what is known. Attribute reporting and distinguish a substantive development from a rewritten headline.
- **Do:** For evolving news, publish verified original details promptly, date updates honestly and separate confirmed facts from developing claims.
- **Check:** Reporting accuracy, update latency, reader use and news-surface performance.
- **Why:** For news publishers, verified original information and honest updates directly serve time-sensitive reader needs.

### 14. Explain uncertainty, exceptions and conflicting evidence alongside conclusions
*Do first · Applies to: Cross-platform practice · Owner: Editor + subject specialist · Key sources: Mike King*

- **What:** Explain where a conclusion applies and where it may fail. Readers should be able to distinguish established facts, reasonable interpretations and open questions.
- **Do:** State the population, uncertainty and contrary findings next to a result; distinguish a lab test from a live platform observation.
- **Check:** Misleading-generalization rate and reader comprehension.
- **Why:** Scope and contrary evidence prevent readers from mistaking a narrow result for a general rule.

### 15. Keep commercial specifications, pricing, availability and fit criteria accurate
*Do first · Applies to: Cross-platform practice · Owner: Product/merchant owner · Key sources: Google Search Central, Aleyda Solis, Mateusz Makosiewicz, iPullRank +3 more*

- **What:** Keep decision-critical product details accurate. Readers need current fit criteria, availability, costs and restrictions, not just persuasive positioning.
- **Do:** Reconcile capabilities, limitations, pricing units and availability on public product pages against the approved product record.
- **Check:** Material mismatch rate and buyer task completion; qualified outcomes.
- **Why:** Incorrect product or commercial facts can mislead purchasing decisions and propagate into third-party answers.

### 16. Cover meaningful related questions and explain entity relationships
*Do next · Applies to: Cross-platform practice · Owner: Editorial + SEO · Key sources: Microsoft Bing, Fabrice Canel, Krishna Madhavan, Meenaz Merchant +18 more*

- **What:** Cover the follow-up questions someone needs to make a decision. Explain how concepts relate without publishing a separate thin page for every imagined AI query.
- **Do:** Map reader questions around a core topic. Compare saved answers about your brand and relevant competitors to flag omitted product attributes or use cases. Verify each gap against real audience needs and your approved facts before improving the relevant page and linking its supporting evidence.
- **Check:** Important unanswered questions, reader engagement and repeated topic-level visibility.
- **Why:** Fill demonstrated audience gaps first; additional topic breadth is useful only when it serves a distinct need.

### 17. Match each page to distinct audience intent; consolidate only genuine overlap
*Do next · Applies to: Cross-platform practice · Owner: Editorial + SEO · Key sources: Louise Linehan, Mateusz Makosiewicz, Veruska Anconitano, Nick Lafferty +6 more*

- **What:** Give each page a clear job. Keep genuinely different intents separate and consolidate only where overlap creates confusion or duplicated effort.
- **Do:** Compare two overlapping guides by reader task before merging; preserve unique reporting and useful URLs or redirects.
- **Check:** Task coverage, index/canonical stability, organic outcomes and reader satisfaction.
- **Why:** Consolidation can reduce confusing duplication, but unnecessary merges can remove valuable reporting and useful destinations.

### 18. Localize evidence, examples and language for the intended market
*Do next · Applies to: Cross-platform practice · Owner: Local editor + SEO · Key sources: Aleyda Solis, Montserrat Cano, Edwin Toonen*

- **What:** Match language, units, laws, availability and examples to the audience. A translated paragraph is not always enough to serve a different market.
- **Do:** Use local reader questions, terminology, original sources and relevant examples instead of translating a US-centric page unchanged.
- **Check:** Native-language factual review and market-specific engagement/visibility.
- **Why:** Localization matters when audience needs differ; prioritize markets with demonstrated demand and qualified editorial support.

### 19. Support text with useful images, video, captions, alt text and transcripts
*Do next · Applies to: Cross-platform practice · Owner: Editorial + accessibility · Key sources: Google Search Central, Microsoft Bing, John Mueller, Fabrice Canel +11 more*

- **What:** Use media to demonstrate something text alone cannot convey well. Captions, transcripts and appropriate alternative text also make relevant information easier to access.
- **Do:** Add a useful chart, demonstration or original image with accurate caption and alt text; provide a transcript for important spoken facts.
- **Check:** Accessibility completeness, reader comprehension and asset engagement.
- **Why:** Additional media is worthwhile when it clarifies the task or improves accessibility, not simply because a guide recommends video.

### 20. Adapt valuable material to audience-relevant native formats and video channels
*Do next · Applies to: Cross-platform practice · Owner: Editorial + audience development · Key sources: Aleyda Solis, Lily Ray, Kevin Indig, Lauren Welles Medley +8 more*

- **What:** Adapt an existing useful asset to a channel your audience uses. Preserve the evidence and context rather than distributing the same promotional copy everywhere.
- **Do:** Turn a verified research finding into a useful short video or demonstration for a channel the audience already uses; keep facts and attribution aligned.
- **Check:** Channel-specific engaged audience, qualified referrals and resource cost.
- **Why:** Format adaptation requires audience and channel fit; production cost should be justified before expanding distribution.

### 21. Use descriptive titles, entity names and link labels aligned with the content
*Do next · Applies to: Cross-platform practice · Owner: Editor + SEO · Key sources: Microsoft Bing, Kevin Indig, Mateusz Makosiewicz, Duane Forrester +5 more*

- **What:** Use titles and labels that accurately describe the subject. Make names unambiguous without stuffing keywords or forcing every phrase variation into the page.
- **Do:** Make the title, heading and link text accurately identify the task and entity; remove ambiguity rather than chasing exact-match strings.
- **Check:** Title/content agreement, task success and search performance by comparable intent.
- **Why:** Accurate labels can remove genuine ambiguity, but exact-match wording is not a demonstrated universal citation lever.

### 22. Create task-completing resources and evidence-backed decision support
*Do next · Applies to: Cross-platform practice · Owner: Product/content + subject specialist · Key sources: Aleyda Solis, Mike King, Mateusz Makosiewicz, Leigh McKenzie +2 more*

- **What:** Help the reader finish the task. A worked example, decision tree, calculator or reusable template may contribute more than another overview.
- **Do:** Create an evidence-backed diagnostic, calculator, reference table or implementation guide that completes a real reader task.
- **Check:** Task completion, repeat use, qualified leads/subscriptions and maintenance cost.
- **Why:** Task-completing resources can help qualified audiences, but usefulness and maintenance cost must justify production.

### 23. Include accurate brand context where it genuinely helps the reader
*Situational · Applies to: Cross-platform practice · Owner: Editor + analyst · Key sources: Charlie Marchant*

- **What:** Identify the organization when it helps readers interpret the evidence. Do not insert the brand repeatedly into unrelated explanations to try to force mentions.
- **Do:** Where a cited explanation genuinely describes your business work, add accurate attribution and context; do not repeat brand names mechanically.
- **Check:** Repeated citation/mention overlap with untreated comparison pages; retain null results.
- **Why:** Brand-context changes have limited causal evidence; use a small truthful test only where attribution benefits the reader.

## Technical (26 actions)

### 24. Verify Google Search crawl, index and snippet eligibility for intended pages
*Do first · Applies to: Google Search AI · Owner: Technical SEO + engineering · Key sources: Google Search Central, Google, John Mueller*

- **What:** Confirm that valuable pages meet ordinary Search eligibility requirements before investigating more speculative tactics.
- **Do:** Check selected public pages for successful responses, Googlebot access, indexability and snippet eligibility in authorized diagnostics.
- **Check:** Fetch success and eligible/indexed URL coverage, separately from AI visibility.
- **Why:** A verified crawl, index or snippet blocker can prevent intended Google Search eligibility before content quality is considered.

### 25. Verify OAI-SearchBot access when ChatGPT Search discovery is desired
*Do first · Applies to: ChatGPT · Owner: Technical SEO + security · Key sources: OpenAI*

- **What:** Check the search crawler separately from the training crawler. A website can choose ChatGPT search discovery without making the same choice for model training.
- **Do:** Compare OAI-SearchBot policy and verified request logs with current OpenAI documentation; prepare narrowly scoped fixes if needed.
- **Check:** Verified search-bot fetch success; no citation guarantee.
- **Why:** An unintended OAI-SearchBot block conflicts with a deliberate goal of ChatGPT Search discovery.

### 26. Verify Claude-SearchBot access when Claude search discovery is desired
*Do first · Applies to: Claude · Owner: Technical SEO + security · Key sources: Anthropic*

- **What:** Check Claude search access using the documented agent name. Review the relevant paths and infrastructure rather than assuming every request carrying a Claude label has the same purpose.
- **Do:** Review Claude-SearchBot rules and successful requests independently of ClaudeBot and Claude-User.
- **Check:** Verified fetch success by purpose; no citation guarantee.
- **Why:** An unintended Claude-SearchBot block conflicts with a deliberate goal of Claude search discovery.

### 27. Verify PerplexityBot access when Perplexity discovery is desired
*Do first · Applies to: Perplexity · Owner: Technical SEO + security · Key sources: Perplexity*

- **What:** Check Perplexity search access against its documented crawler and current verification information.
- **Do:** Check PerplexityBot access using current official bot/IP guidance and inspect specific failed requests.
- **Check:** Verified search-bot fetch success; no inclusion guarantee.
- **Why:** An unintended PerplexityBot block conflicts with a deliberate goal of Perplexity discovery.

### 28. Apply purpose-specific crawler policies consistently across hosts
*Do first · Applies to: Cross-platform practice · Owner: Technical SEO + security · Key sources: Anthropic, Gianluca Fiorelli, Conor Baker*

- **What:** Apply the intended policy to the hosts and paths where the content lives. A correct rule on the main domain may not resolve a block on an image or documentation host.
- **Do:** Inventory relevant domains/subdomains and compare purpose-specific crawler rules with the intended policy.
- **Check:** Host coverage and unintended blocks; approved exceptions remain narrow.
- **Why:** Inconsistent host rules can defeat an approved access policy or expose content contrary to that policy.

### 29. Verify crawler provenance and diagnose actual CDN/WAF/HTTP failures
*Do first · Applies to: Cross-platform practice · Owner: Security + engineering + SEO · Key sources: Google Search Central, Google, OpenAI, Anthropic +7 more*

- **What:** Use logs and provider verification to diagnose a real failure. Allowlisting a user-agent string alone is not proof that a request comes from that provider.
- **Do:** Investigate actual bot failures using current official verification methods, status codes and CDN logs; do not trust the user-agent string alone.
- **Check:** Verified request success, false positives, error rates and security impact.
- **Why:** Narrow diagnosis can repair real failures while preserving security controls and avoiding user-agent spoofing mistakes.

### 30. Verify important text is actually retrievable and rendered for each target system
*Do first · Applies to: Cross-platform practice · Owner: Engineering + technical SEO · Key sources: Google Search Central, Microsoft Bing, Aleyda Solis, Lily Ray +14 more*

- **What:** Inspect what the target system actually receives. Choose a rendering approach that reliably exposes important text and links without assuming every platform processes JavaScript identically.
- **Do:** Compare raw and rendered content and actual fetch behavior on representative pages; keep essential claims accessible to the intended consumer.
- **Check:** Key-fact retrieval completeness and rendering/fetch defects by platform.
- **Why:** Content that the intended system cannot retrieve may never enter its answer pipeline; inspect actual behavior before redesign.

### 31. Preserve ordinary technical SEO and repair broken access or page behavior
*Do first · Applies to: Cross-platform practice · Owner: Technical SEO + engineering · Key sources: Microsoft Bing, Gianluca Fiorelli, Kevin Indig, Barry Adams +15 more*

- **What:** Repair broken pages, redirects, resources and navigation before treating weak visibility as an AI-specific problem.
- **Do:** Repair verified crawl, status, broken-page and indexability problems using normal SEO diagnostics before speculative GEO changes.
- **Check:** Eligible useful pages, error backlog and organic outcomes; AI outcomes measured separately.
- **Why:** Ordinary access and page defects have clearer consequences than speculative GEO formatting changes.

### 32. Audit Google Search generative-AI inclusion settings separately from other controls
*Do first · Applies to: Google Search AI · Owner: Publisher leadership + authorized Search Console owner · Key sources: Google Search Central, Google, Marie Haynes*

- **What:** Inspect the current Search Console setting and any parent-property inheritance. Keep this inclusion decision separate from Search indexing and model-training policy.
- **Do:** Record current include/exclude/inherit settings, parent-property relationships and each AI surface; document the decision without changing it here.
- **Check:** Policy-to-setting agreement, propagation interval and relevant AI impressions.
- **Why:** The documented Google control is a substantive inclusion decision with inheritance effects, not a routine SEO toggle.

### 33. Maintain canonical sitemaps and descriptive internal links to useful pages
*Do first · Applies to: Cross-platform practice · Owner: Technical SEO + editorial · Key sources: Google Search Central, Microsoft Bing, Crystal Carter, Duane Forrester +8 more*

- **What:** Help crawlers and readers reach useful pages through stable links and appropriate sitemaps. Prioritize real navigation rather than isolated pages built only for AI prompts.
- **Do:** Keep sitemaps current and canonical; link relevant pages with descriptive labels from useful navigation and related explanations.
- **Check:** Orphan useful URLs, sitemap errors, discovery and reader navigation.
- **Why:** Current canonical discovery paths help engines and people find useful content and reduce contradictory URL signals.

### 34. Keep URLs, canonical signals and destinations stable and internally consistent
*Do first · Applies to: Cross-platform practice · Owner: Technical SEO + engineering · Key sources: Google Search Central, Mateusz Makosiewicz, Dixon Jones*

- **What:** Keep important URLs and canonical signals consistent. An unnecessary migration can create ordinary search and access problems.
- **Do:** Check canonical signals, redirect destinations, internal links and duplicated URL variants on a small template sample. Include broken URLs actually cited in saved AI answers. Diagnose the cause and use a relevant replacement only when one exists; verify the destination after any approved repair.
- **Check:** Canonical consistency, broken destinations and preserved reader/search access.
- **Why:** Contradictory canonical and destination signals can fragment diagnostics and send readers or systems to the wrong page.

### 35. Use accurate structured data only for applicable, currently supported purposes
*Do next · Applies to: Cross-platform practice · Owner: Technical SEO + CMS owner · Key sources: Google Search Central, Google, John Mueller, Microsoft Bing +14 more*

- **What:** Use structured data for an applicable purpose and match it to visible facts. It is not a universal shortcut to citations.
- **Do:** Map only true visible facts to supported schema types and validate implementation; check current feature eligibility first.
- **Check:** Markup validity and fact consistency; supported rich-result outcomes where applicable.
- **Why:** Accurate markup can support documented uses; universal organic citation gains are not established.

### 36. Notify participating engines of meaningful changes through IndexNow
*Do next · Applies to: Bing / Copilot · Owner: CMS/engineering + SEO · Key sources: Microsoft Bing, Fabrice Canel, Krishna Madhavan, Meenaz Merchant +2 more*

- **What:** Notify participating engines when useful pages change. Faster discovery of a revision is not a guarantee of indexing, citation or traffic.
- **Do:** Check whether the CMS already supports IndexNow; notify meaningful additions, changes and removals with correct host scope and response handling.
- **Check:** Accepted notifications, crawl/update latency and indexed outcomes separately.
- **Why:** Change notification can aid participating engines, but eligibility, meaningful updates and existing CMS support determine value.

### 37. Improve page speed, mobile usability and fetch reliability where measured
*Do next · Applies to: Cross-platform practice · Owner: Engineering + UX · Key sources: Google Search Central, John Mueller, Louise Linehan, Conor Baker +4 more*

- **What:** Fix measured performance and usability problems. Do not promise citation gains from a particular speed score.
- **Do:** Measure slow or incomplete responses and intrusive layouts; prioritize failures that prevent actual reading or task completion.
- **Check:** Real-user usability, fetch completion and error rates; avoid unsupported universal timeout thresholds.
- **Why:** Fix measured usability and fetch problems; no universal speed threshold for AI citations is established.

### 38. Set model-training crawler policies independently of search inclusion
*Situational · Applies to: Cross-platform practice · Owner: Publisher/product leadership + legal + engineering · Key sources: Google Search Central, Google, OpenAI, Anthropic*

- **What:** Make an explicit business decision about model-training access. Training permission is a separate choice from allowing a search bot to retrieve a page.
- **Do:** Document the chosen training policy for GPTBot, ClaudeBot and Google-Extended separately from search controls; record owner and scope.
- **Check:** Policy-to-configuration agreement by host and purpose.
- **Why:** Training permission is a business and rights decision that must not be accidentally changed through search-access work.

### 39. Distinguish user-triggered fetching from automatic search crawling
*Situational · Applies to: Cross-platform practice · Owner: Technical SEO + analytics · Key sources: Anthropic*

- **What:** Understand whether a request builds a search index or fetches a page for a user. These requests may follow different documented controls.
- **Do:** Label user-triggered fetch traffic separately from automatic search bots; apply each provider’s documented robots semantics.
- **Check:** Correctly classified request samples and failed-fetch diagnosis.
- **Why:** User-triggered requests need correct interpretation, but investigate them only where they affect the intended experience or policy.

### 40. Control crawl load using documented throttling rather than broad accidental blocking
*Situational · Applies to: Cross-platform practice · Owner: Engineering + security · Key sources: Anthropic*

- **What:** Protect reliability without accidentally denying the systems you want to serve. Use controls documented for the particular crawler.
- **Do:** Where documented and justified by load, propose supported throttling rather than blocking all search access.
- **Check:** Server load, crawl success and response errors before/after.
- **Why:** Throttle only for a demonstrated load problem and documented support; unnecessary restrictions can reduce useful access.

### 41. Defer llms.txt or Markdown unless a documented consumer needs it
*Situational · Applies to: Google Search AI, Specialized · Owner: Technical documentation owner · Key sources: Google Search Central, Gianluca Fiorelli, Duane Forrester, Nicole Wanichko +2 more*

- **What:** Identify a real consuming system before maintaining an extra file or page format. Google does not require llms.txt or Markdown versions for AI Search visibility.
- **Do:** Require a named consumer and maintenance owner before adding llms.txt or Markdown; otherwise keep the work below demonstrated access/content needs.
- **Check:** Consumer requests and task success if piloted; installation is not success.
- **Why:** No universal requirement is established; avoid maintenance cost without a documented consumer and measurable use case.

### 42. Choose Google snippet/display restrictions deliberately and verify recrawling
*Situational · Applies to: Google Search AI · Owner: Publisher policy owner + SEO · Key sources: Google Search Central, Google, John Mueller*

- **What:** Choose snippet and indexing restrictions deliberately. A more restrictive display policy may change how information can appear in supported features.
- **Do:** Inventory Google preview restrictions and intended scope; model their effects and verify recrawl after any separately approved change.
- **Check:** Policy compliance and observed snippet behavior after propagation.
- **Why:** Preview restrictions can change permitted reuse and presentation, so choices need a clear owner and verified scope.

### 43. Apply Bing-specific snippet and page controls at the intended scope
*Situational · Applies to: Bing / Copilot · Owner: Publisher policy owner + technical SEO · Key sources: Microsoft Bing, Cata Milos, Fabrice Canel, Krishna Madhavan*

- **What:** Use Bing documentation for Bing-specific display restrictions. Do not copy a rule from another platform without checking its meaning and scope.
- **Do:** Distinguish a section-level Bing data-nosnippet exclusion from page-wide directives; verify the fetched implementation after approval.
- **Check:** Selected-section/page behavior and Bing recrawl status.
- **Why:** Bing controls have product-specific scope; incorrect directives can suppress more content than intended.

### 44. Evaluate accurate merchant feeds only where the product and participation rules apply
*Situational · Applies to: Ecommerce · Owner: Merchant/product data + engineering · Key sources: Google Search, OpenAI, Aleyda Solis, iPullRank +2 more*

- **What:** Supply accurate product information where a supported merchant program is relevant. Product feeds are conditional commercial interfaces, not requirements for every website.
- **Do:** Determine merchant eligibility and reconcile an authorized product feed with current pricing, availability and canonical product pages.
- **Check:** Feed validation, data freshness and merchant outcomes, separately from organic citations.
- **Why:** Merchant feeds matter only for eligible commerce use cases; they are not a general publisher citation tactic.

### 45. Test relevant browser-agent journeys for usable, accurate task completion
*Situational · Applies to: Browser agents · Owner: Product + accessibility + engineering · Key sources: Google Search Central, Aleyda Solis, Crystal Carter*

- **What:** If browser agents matter to your business, test realistic tasks. Clear labels, accessible controls and truthful information should support successful completion.
- **Do:** Test whether an agent can understand and complete a relevant public task without broken controls, ambiguous facts or inaccessible UI.
- **Check:** Task completion and error rate; no real transaction without approval.
- **Why:** Agent journeys are relevant only where a real audience task exists; exploratory tests should precede major UI investment.

### 46. Pilot maintained machine-readable endpoints only for demonstrated consumer needs
*Situational · Applies to: Specialized · Owner: Developer experience + engineering · Key sources: Mike King, Duane Forrester, Andrea Volpini, Crystal Carter*

- **What:** Create maintained structured endpoints only when a real integration needs them. Confirm ownership, accuracy and update responsibilities before adding another interface.
- **Do:** Offer a versioned public content endpoint only for a real consumer; define ownership, freshness, schema and retirement behavior.
- **Check:** Consumer task success, factual parity, uptime and maintenance cost.
- **Why:** A maintained endpoint adds operational cost; require a real consumer rather than assuming answer engines will use it.

### 47. Verify authorized webmaster-tool ownership before using site diagnostics
*Situational · Applies to: Cross-platform practice · Owner: Authorized site owner + SEO · Key sources: Microsoft Bing*

- **What:** Use properly authorized webmaster accounts and verify property scope. A diagnostic result for the wrong host or path can misdirect the work.
- **Do:** Confirm existing ownership and appropriate access to relevant webmaster diagnostics before planning changes.
- **Check:** Verified property scope and diagnostic availability.
- **Why:** Authorized diagnostic access is a prerequisite for reliable site-specific checks, not a ranking signal.

### 48. Recheck feature deprecations before investing in rich-result markup
*Situational · Applies to: Google Search AI · Owner: Technical SEO · Key sources: Google*

- **What:** Confirm that a feature still exists before investing in its markup. Useful question-and-answer content can remain valuable even if a related rich-result format changes.
- **Do:** Check the current feature changelog before budgeting schema work; remove FAQ/HowTo rich-result gains from Google business cases.
- **Check:** Current feature support documented; useful content retained irrespective of deprecated display.
- **Why:** Deprecated features cannot support a current rich-result business case; check support before allocating implementation effort.

### 49. Validate owned retrieval simulations against labeled and held-out cases
*Test · Applies to: Specialized · Owner: Search/ML engineer + analyst · Key sources: Mike King, Dan Petrovic, Duane Forrester, iPullRank*

- **What:** Use owned simulations as diagnostic tools, not replicas of a closed platform. Validate the simulation against labeled cases before using it to prioritize content.
- **Do:** Create a relevance-labeled query set with held-out cases; compare retrieval variants and validate against actual public-product observations.
- **Check:** Held-out retrieval accuracy, factual quality and mismatch with live observations; no exact platform simulation claim.
- **Why:** Owned simulations can inform tests but cannot substitute for public-product behavior without external validation.

## Measurement & Attribution (23 actions)

### 50. Maintain a documented prompt panel tied to intent, journey and business relevance
*Do first · Applies to: Cross-platform practice · Owner: SEO + audience/product lead · Key sources: Aleyda Solis, Olivier Martinez, Ethan Lazuk, Leigh McKenzie +11 more*

- **What:** Document a manageable prompt panel that represents important reader needs. Keep a stable core for comparisons and add justified variants separately.
- **Do:** Create a manageable panel covering branded accuracy, discovery, comparison and important reader tasks; tag each prompt and why it matters.
- **Check:** Panel coverage, stability and relevance; explicitly label it a selected sample, not usage volume.
- **Why:** An undocumented or biased prompt panel can produce a misleading view of visibility and competitive opportunity.

### 51. Repeat comparable observations and retain prompt, model, mode, time and context
*Do first · Applies to: Cross-platform practice · Owner: Analyst + SEO · Key sources: Aleyda Solis, Lily Ray, Gianluca Fiorelli, Kevin Indig +11 more*

- **What:** Repeat observations under comparable conditions. Save the model, mode, date, market and context so changes are interpretable.
- **Do:** Save repeated outputs with exact prompt, date, product/version, mode, locale and available context; keep failed and absent-brand runs.
- **Check:** Within-prompt variation and confidence intervals where justified; changes exceed ordinary volatility.
- **Why:** Repeated comparable observations distinguish normal output variation from a plausible persistent change.

### 52. Segment results by platform, retrieval mode, market and audience intent
*Do first · Applies to: Cross-platform practice · Owner: Analyst · Key sources: Gianluca Fiorelli, Dan Petrovic, Olivier Martinez, Louise Linehan +9 more*

- **What:** Keep unlike experiences separate. A different platform, language or model mode may select a different source set for the same apparent question.
- **Do:** Compare like-for-like runs separately by product, search-enabled mode, market, intent and time window before considering any aggregate.
- **Check:** Segment completeness and comparable denominators; no average that hides contradictory platform trends.
- **Why:** Mixing platforms, modes or markets can hide different behavior and invalidate before-and-after comparisons.

### 53. Separate eligibility, retrieval, citation, mention, recommendation and business outcomes
*Do first · Applies to: Cross-platform practice · Owner: Analytics + SEO · Key sources: IndexNow, Aleyda Solis, Dan Petrovic, Olivier Martinez +18 more*

- **What:** A page may be retrieved without being cited, or cited without its brand being named. Measure the outcome that fits the decision you are making.
- **Do:** Give separate fields to observable retrieval, linked citation, brand mention, explicit recommendation, accuracy, referral and conversion.
- **Check:** Classification agreement and complete denominator definitions; missing stages remain unknown.
- **Why:** Conflating retrieval, citations, mentions and business outcomes turns a measurement difference into a false success claim.

### 54. Define every visibility metric and denominator, including absent and null results
*Do first · Applies to: Cross-platform practice · Owner: Analytics lead · Key sources: Google, Dan Petrovic, Olivier Martinez, Louise Linehan +6 more*

- **What:** Write down what each metric counts. Include null and absent-brand answers so a favorable denominator does not create a misleading success rate.
- **Do:** Attach a measurement card to each score defining numerator, denominator, sample, weighting, missing cases and aggregation.
- **Check:** Reproducibility from saved observations and sensitivity to reasonable weighting choices.
- **Why:** Missing denominators and exclusions can make the same data appear to support incompatible conclusions.

### 55. Inspect repeated cited sources and competitors before choosing interventions
*Do first · Applies to: Cross-platform practice · Owner: SEO + analyst · Key sources: Aleyda Solis, Kevin Indig, Louise Linehan, Amanda Natividad +8 more*

- **What:** Inspect sources that appear repeatedly for relevant questions. Look for an actual content or corroboration gap before selecting an intervention.
- **Do:** Review repeatedly cited URLs and competitors for relevant prompts; distinguish owned pages, independent evidence and syndicated repeats.
- **Check:** Actionable gaps, source persistence and evidence quality, not raw mention count alone.
- **Why:** Repeated source patterns can identify specific opportunities; one screenshot or a syndicated cluster is weak evidence.

### 56. Audit answer accuracy, entity identity and sentiment against verifiable facts
*Do first · Applies to: Cross-platform practice · Owner: Fact owner + analyst · Key sources: Lily Ray, Barry Adams, Mateusz Makosiewicz, Crystal Carter +15 more*

- **What:** Compare AI descriptions with an approved record of facts. Resolve entity confusion before interpreting sentiment or visibility scores.
- **Do:** Score saved answers against approved facts; distinguish a namesake, factual error, missing fact and subjective criticism. Also record which relevant product features, audiences and topics the answer associates with the brand. Keep observations separated by model and mode; confirm apparent gaps before changing content.
- **Check:** Human-reviewed material-error rate and resolution persistence across repeated runs.
- **Why:** Wrong identities and material inaccuracies can mislead audiences even when the brand receives many mentions.

### 57. Measure identifiable AI referrals, landing pages and qualified engagement
*Do first · Applies to: Cross-platform practice · Owner: Analytics owner · Key sources: Aleyda Solis, Louise Linehan, Despina Gavoyannis, Kevin Lee +4 more*

- **What:** Measure identifiable visits and what people do after landing. Missing referrers and cross-session journeys limit what analytics can attribute.
- **Do:** Report identifiable AI-referral sessions with landing pages and qualified engagement; validate referrer loss and separate bots from humans.
- **Check:** Observed visits and outcomes with collection limits; do not infer all AI influence from referrers.
- **Why:** Identifiable referrals provide observable behavior, while referrer loss and bot traffic require explicit qualification.

### 58. Judge investment using conversions, qualified value and publisher outcomes
*Do first · Applies to: Cross-platform practice · Owner: Business/publisher lead + analytics · Key sources: Google Search Central, John Mueller, Aleyda Solis, Lily Ray +18 more*

- **What:** Tie the investment to relevant value: qualified inquiries, subscriptions, sales or useful readership. More source links alone do not establish a return.
- **Do:** For your business, track qualified trials/leads and retained customers; for news clients, use subscriptions, loyal readers, revenue or mission-specific outcomes.
- **Check:** Incremental value where measurable, plus cost and uncertainty; citations remain an intermediate signal.
- **Why:** Qualified business, reader or mission outcomes are needed to judge whether visibility work is worth continuing.

### 59. Test changes with baselines, comparison groups and documented confounders
*Do first · Applies to: Cross-platform practice · Owner: Analyst + experiment owner · Key sources: Google, Aleyda Solis, Kevin Indig, Olivier Martinez +5 more*

- **What:** Record the baseline, intervention and comparison conditions. Consider seasonality, platform changes and other campaigns before claiming an effect.
- **Do:** Predefine the intervention, stable prompt/page cohorts, baseline, comparison group, outcomes and stopping criteria; log concurrent changes.
- **Check:** Effect estimate with uncertainty, null results, confounders and business relevance.
- **Why:** A comparison and change log reduce the risk of attributing ordinary variation or concurrent work to the intervention.

### 60. Account for effort, tools and shared costs before reporting ROI
*Do first · Applies to: Cross-platform practice · Owner: Finance/business lead + analytics · Key sources: Louise Linehan, Becky Simms, Dr. Peter J. Meyers*

- **What:** Include labor, tools and shared costs in the assessment. A visibility gain may still be an inefficient use of resources.
- **Do:** Include staff time, tools, research and shared-channel costs; report tracked and modeled benefits separately with explicit assumptions.
- **Check:** Comparable cost/value periods and sensitivity range; ad-equivalent exposure is not ROI.
- **Why:** ROI without staff and shared costs can materially overstate the return on GEO work.

### 61. Use Google Search generative-AI reporting with its documented limits
*Do first · Applies to: Google Search AI · Owner: Authorized Search Console owner + analyst · Key sources: Google Search Central, Google, Marie Haynes, Marcus Miller*

- **What:** Read the current Search generative-AI report definitions. Its impressions are not interchangeable with visits, conversions or Bing citation counts.
- **Do:** Use the Search generative-AI impressions report by canonical page and comparable period; document thresholds, Pacific dates and aggregation.
- **Check:** Observed AIO/AI Mode impressions; do not label organic clicks as separately measured AI clicks.
- **Why:** Current first-party Search impression reporting can improve diagnosis if its thresholds and aggregation rules are preserved.

### 62. Use Bing AI Performance metrics with their own scope and denominators
*Do first · Applies to: Bing / Copilot · Owner: Authorized Bing Webmaster Tools owner + analyst · Key sources: Microsoft Bing, Fabrice Canel, Krishna Madhavan, Meenaz Merchant +2 more*

- **What:** Use Bing AI Performance within its documented scope. Define how its citation metrics differ from your other reporting sources.
- **Do:** Review citations, cited pages and grounding-query data; retain the documented Citation Share denominator and selected product coverage.
- **Check:** Comparable Bing-defined metrics; no authority score, complete prompt demand or inferred revenue.
- **Why:** Bing first-party citation reporting provides useful product-specific observations, but its denominator must stay explicit.

### 63. Audit scoring, entity matching and model judgments with human review
*Do first · Applies to: Cross-platform practice · Owner: Analytics/research lead · Key sources: Kevin Indig, Olivier Martinez, Ethan Lazuk, Mateusz Makosiewicz*

- **What:** Validate entity matching, sentiment labels and automated judgments. A mislabeled answer can distort the apparent trend.
- **Do:** Manually review a stratified sample of automated mention/citation labels and model judgments; document disagreement and adjust rules.
- **Check:** Precision/recall or agreement on held-out cases, with ambiguous outcomes retained.
- **Why:** Entity-matching and automated scoring errors can reverse conclusions unless a human-labeled sample is checked.

### 64. Label observed evidence, modeled estimates and causal claims separately
*Do first · Applies to: Cross-platform practice · Owner: Research/analytics lead · Key sources: Microsoft Bing, Krishna Madhavan, Meenaz Merchant, Saral Nigam +15 more*

- **What:** Label observed results, estimates and hypotheses. Explain what the method can support before presenting a forecast as an outcome.
- **Do:** Label each conclusion as documented behavior, observation, experiment or hypothesis; retain sample, uncertainty and alternative explanations.
- **Check:** Unsupported causal claims removed and reproducible metric definitions.
- **Why:** Explicit evidence classes prevent an observation, modeled forecast or practitioner hypothesis from being presented as causal proof.

### 65. Track search exposure, clicks and impressions separately before diagnosing loss
*Do first · Applies to: Cross-platform practice · Owner: Analytics + search lead · Key sources: Barry Adams, Marie Haynes*

- **What:** Compare impressions, clicks and other exposure measures separately. A change in traffic can have several causes that a single citation graph does not reveal.
- **Do:** Inspect clicks, impressions and CTR separately by page, intent and contemporaneous AI exposure; check account concentration and seasonality.
- **Check:** Actual visits/value, denominator shifts and uncertainty; no advertiser benchmark used as a newsroom forecast.
- **Why:** Separating exposure, impressions and clicks reduces the risk of treating changing demand or cohort composition as an AI effect.

### 66. Validate GA4 AI Assistant attribution and any custom channel rules
*Do first · Applies to: Analytics · Owner: Analytics owner · Key sources: Google Analytics Help, Google, Aleyda Solis, Veruska Anconitano +1 more*

- **What:** Check the property’s actual attribution data. The current GA4 AI Assistant channel excludes Google AI Overviews and AI Mode, which belong to Organic Search.
- **Do:** Check the native GA4 AI Assistant channel first; validate known referrers, first-match custom rules and session/event/first-user scopes.
- **Check:** Known-source classification precision, lost-referrer tests and attribution-scope consistency.
- **Why:** Incorrect attribution rules can corrupt the baseline and lead to misallocated effort or misleading performance claims.

### 67. Use observed grounding queries and fan-outs as diagnostic evidence
*Do next · Applies to: Cross-platform practice · Owner: SEO analyst · Key sources: Mike King, Dr. Peter J. Meyers, Metehan Yeşilyurt*

- **What:** Treat generated subqueries as clues about retrieval, not a permanent list of keywords to target with new pages.
- **Do:** Inspect actual exposed grounding queries and fetched URLs where available; map them to reader needs and label simulated fan-outs as predictions.
- **Check:** Trace completeness and useful content hypotheses; never report these as full user-prompt demand.
- **Why:** Observed query traces can inform relevance diagnostics, but inferred fan-outs are uncertain and may not represent all users.

### 68. Use optional self-reported discovery alongside observed analytics
*Do next · Applies to: Cross-platform practice · Owner: Research + CRM/analytics owner · Key sources: Aleyda Solis, Louise Linehan, Crystal Carter*

- **What:** Ask customers how they discovered you when appropriate. Self-reports complement analytics but remain imperfect evidence.
- **Do:** Add an optional discovery question to an approved research process and retain free-text answers alongside observed attribution.
- **Check:** Response rate, recall uncertainty and agreement/disagreement with tracked sources.
- **Why:** Self-report can reveal discovery paths but adds recall and selection biases; use it as complementary evidence.

### 69. Treat brand-search, direct and social changes as corroborating proxies
*Do next · Applies to: Cross-platform practice · Owner: Analytics + brand/audience · Key sources: Aleyda Solis, Louise Linehan, Amanda Natividad, Mateusz Makosiewicz +3 more*

- **What:** Use brand search and direct traffic as contextual signals. They cannot by themselves establish that an AI answer caused the change.
- **Do:** Compare branded search, direct visits and audience engagement with other campaigns and seasonality; present them as supporting signals.
- **Check:** Competing explanations and confidence range, not automatic AI-attributed revenue.
- **Why:** Brand-search and direct-traffic changes can corroborate a hypothesis but have many competing explanations.

### 70. Explain measurement uncertainty to stakeholders with concrete saved examples
*Do next · Applies to: Cross-platform practice · Owner: Analytics/SEO lead · Key sources: Lily Ray, Charlie Marchant, Mark Williams-Cook*

- **What:** Explain uncertainty with saved examples, definitions and meaningful comparisons. Stakeholders need to know what changed and what remains unobservable.
- **Do:** Show stakeholders saved examples of changing answers and explain what the dashboard can and cannot measure before a budget decision.
- **Check:** Shared metric interpretation and decisions that acknowledge uncertainty.
- **Why:** Concrete examples make uncertainty understandable before stakeholders commit budget or interpret a dashboard as ground truth.

### 71. Improve landing-page conversion paths for visitors arriving after AI-assisted discovery
*Do next · Applies to: Cross-platform practice · Owner: Growth / UX, with analytics and the relevant product or subscription owner · Key sources: Veruska Anconitano, Marcus Miller, Crystal Carter*

- **What:** Sites with an appropriate next step after discovery, including SaaS trials or leads, publisher subscriptions or newsletters, bookings, and relevant resource downloads. Use observed landing-page and audience behavior; do not assume all AI visitors are ready to buy.
- **Do:** Use measurable AI referral landing-page data and audience needs to identify pages with a weak next step. Clarify the offer, relevant cost or commitment, expected timing, and what happens next. Add an appropriate and accessible trial, contact, subscription, booking, or other completion path. Test changes against qualified completions and relevant business value, with the limits of referral attribution stated.
- **Check:** A usable next step on selected landing pages, measured qualified completion and business-value outcomes, and an explicit baseline and attribution caveat. Do not treat citation or traffic changes as proof that the conversion changes caused them.
- **Why:** Use observed visitor needs to improve a relevant completion path after discovery. This is a context-dependent business improvement, not a citation-ranking requirement.
- **Evidence limit:** Practical conversion guidance, not a demonstrated citation or ranking lever. Referral data misses some AI-assisted journeys and does not independently establish causation. No source-derived universal conversion lift or assumption that every AI visitor has buying intent. The practical recommendation has medium confidence; no causal GEO or revenue uplift is established.

### 72. Track Discover generative-AI reporting separately from Search reporting
*Situational · Applies to: Discover · Owner: Authorized Search Console owner + analyst · Key sources: Google Search Central, Google Search Console Help*

- **What:** Keep Discover reporting separate from Search reporting. Read the attribution and availability rules for the actual report you use.
- **Do:** Keep Discover generative-AI impressions in a separate view and distinguish source canonical URLs from click destinations.
- **Check:** Comparable visible-source impressions with session/threshold/timezone definitions.
- **Why:** Discover reporting is useful for eligible publisher contexts; its source URLs and impressions differ from Search metrics.

## Brand, Audience & Off-site (10 actions)

### 73. Build direct audience relationships beyond search-platform referrals
*Do first · Applies to: Cross-platform practice · Owner: Audience/business lead · Key sources: Lily Ray, Gianluca Fiorelli, Kevin Indig, Barry Adams +2 more*

- **What:** Build relationships that do not depend entirely on a search interface. Useful newsletters, direct visits and community participation can have independent business value.
- **Do:** Prioritize one direct relationship channel supported by reader demand, such as an email product, subscription or returning-reader program.
- **Check:** Loyal/returning audience, retention, qualified value and channel cost.
- **Why:** Direct audience relationships can support resilience and repeat use without relying entirely on third-party referral behavior.

### 74. Separate independent corroboration from duplicate or syndicated repetition
*Do first · Applies to: Cross-platform practice · Owner: Research/PR analyst · Key sources: Aleyda Solis*

- **What:** Trace coverage to its original reporting and ownership. Repeated publication of one claim is not multiple independent confirmations.
- **Do:** Link republications, syndicated copies and repeated references to the same underlying study before counting support.
- **Check:** Independent-source count versus publication count and traceable alias relationships.
- **Why:** Syndication and repeated references can inflate apparent support without adding independent evidence.

### 75. Respond to valid customer criticism and improve the underlying experience
*Do first · Applies to: Cross-platform practice · Owner: Customer experience + product owner · Key sources: Despina Gavoyannis*

- **What:** Improve the experience behind valid criticism. Accurate independent feedback cannot be solved responsibly by suppressing the criticism or manufacturing praise.
- **Do:** Determine whether criticism is accurate, then address the product/service issue and respond transparently rather than trying to bury it.
- **Check:** Resolved customer issues and verified experience improvement.
- **Why:** Valid criticism signals an underlying customer problem; improving that experience has clearer value than suppressing the criticism.

### 76. Earn relevant independent editorial coverage and genuine expert evaluation
*Do next · Applies to: Cross-platform practice · Owner: PR/editorial + subject experts · Key sources: Google, Aleyda Solis, Gianluca Fiorelli, Kevin Indig +13 more*

- **What:** Earn relevant independent coverage through useful evidence and real expertise. Paid placements and copied syndication are not equivalent to independent editorial validation.
- **Do:** Offer genuine research, demonstrations or independent evaluation to relevant publications already serving the audience; disclose commercial ties.
- **Check:** Relevant independent coverage, factual accuracy and audience/business outcomes; placement is not guaranteed.
- **Why:** Independent coverage can reach relevant audiences, but earned placement and downstream AI effects are uncertain.

### 77. Participate transparently in relevant communities that welcome contributions
*Do next · Applies to: Cross-platform practice · Owner: Community/audience lead + experts · Key sources: Aleyda Solis, Lauren Welles Medley, Despina Gavoyannis, Leigh McKenzie +3 more*

- **What:** Contribute transparently where you have relevant knowledge. Respect community rules and avoid fake identities or manufactured endorsements.
- **Do:** Choose communities that welcome participation, disclose affiliation and answer real questions without covert promotion or manufactured engagement.
- **Check:** Useful responses, community feedback and qualified engagement; observe site rules.
- **Why:** Community participation depends on audience fit and local rules; undisclosed promotion can damage trust.

### 78. Maintain accurate relevant review, directory, marketplace and local profiles
*Do next · Applies to: Cross-platform practice · Owner: Product/local operations + reputation owner · Key sources: Google Search Central, Microsoft Bing, Fabrice Canel, Krishna Madhavan +12 more*

- **What:** Maintain accurate profiles where customers genuinely evaluate your business. Select relevant channels rather than creating listings indiscriminately.
- **Do:** Review only genuine, category-relevant profiles; reconcile names, hours, products and links and prepare responses to authentic reviews.
- **Check:** Profile factual accuracy and qualified outcomes; review volume alone is not causal evidence.
- **Why:** Accurate relevant profiles can help discovery and buyer verification; profile quotas and universal lift are unsupported.

### 79. Report specific factual errors through legitimate correction or feedback routes
*Do next · Applies to: Cross-platform practice · Owner: Fact owner + communications · Key sources: Crystal Carter, Mateusz Makosiewicz, Ethan Lazuk*

- **What:** Use legitimate correction routes for factual errors. Report the specific claim and supporting facts rather than trying to manipulate the answer.
- **Do:** Prepare the exact error, correct fact, source evidence and requested correction for the relevant publisher or platform feedback route.
- **Check:** Correction acceptance and repeated factual accuracy, not removal of legitimate criticism.
- **Why:** An evidence-backed correction can address a specific error, but editorial control belongs to the relevant publisher or platform.

### 80. Invite authentic, recent customer reviews through a transparent, policy-compliant process
*Do next · Applies to: Cross-platform practice · Owner: Customer success / customer experience, with reputation or marketing ownership · Key sources: Wil Reynolds, Nick Haigler*

- **What:** Businesses for which customers use relevant review platforms, especially SaaS and service categories. Select platforms based on actual audience/category relevance; this is not a universal requirement for publishers.
- **Do:** Identify audience-relevant review platforms. Invite genuine customers to give honest feedback after a meaningful experience through a transparent process that follows each platform's rules. Do not gate invitations by expected sentiment or manufacture, purchase, or pressure positive reviews. Track recency, representativeness, and response handling alongside a stable AI narrative/citation panel. Obtain any required approval before sending outreach.
- **Check:** A documented compliant invitation process and more current, authentic customer feedback on relevant platforms; monitor narrative and citation changes without attributing causation from before/after movement alone.
- **Why:** Relevant review platforms benefit from current, genuine customer evidence. Prioritize audience fit and a compliant process; this is not a universal requirement for publishers.
- **Evidence limit:** No guaranteed citation, recommendation, or revenue lift. Platform and category relevance vary. Review activity should represent genuine experience, including negative feedback; improve the underlying customer experience as required. Causal GEO confidence is low. The no-gating, platform-rule and approval safeguards are analyst implementation constraints; the cited sources do not independently prescribe every safeguard.

### 81. Evaluate voluntary Preferred Sources and Discover following for reader loyalty
*Situational · Applies to: Google Search AI, Discover · Owner: Audience development + engineering · Key sources: Duncan Osborn (Google), Layla Amjadi (Google), Google Search Central, Barry Adams*

- **What:** Treat reader preference and following features as audience choices. Eligibility for a badge is not a promised increase in distribution.
- **Do:** Verify domain/subdomain eligibility, then consider an optional reader-selection button or deeplink; evaluate Discover following separately.
- **Check:** Reader uptake where observable and audience outcomes; no guaranteed citation or traffic lift.
- **Why:** Voluntary reader preferences can support audience relationships, but availability and audience interest determine applicability.

### 82. Use encyclopedic or knowledge-base participation only where genuinely eligible
*Situational · Applies to: Specialized · Owner: Qualified editor + communications/legal · Key sources: *

- **What:** Participate in knowledge resources only when eligibility and contribution rules are satisfied. Do not manufacture an encyclopedia entry to create apparent authority.
- **Do:** Assess whether a factual contribution genuinely meets the knowledge platform’s eligibility and conflict-of-interest rules.
- **Check:** Accuracy and policy compliance; do not measure success as guaranteed model inclusion.
- **Why:** Knowledge-base participation has eligibility and conflict-of-interest requirements; promotional listings are not an established citation prerequisite.
- **Evidence limit:** Analyst governance recommendation. The contextual source does not establish eligibility or conflict-of-interest requirements. Verify the chosen platform’s current policies before any contribution; no citation or visibility benefit is established.

## Strategy & Governance (9 actions)

### 83. Set business or publisher goals before choosing AI platforms and priorities
*Do first · Applies to: Cross-platform practice · Owner: Business/publisher lead + SEO · Key sources: Aleyda Solis, Leigh McKenzie, Margarita Loktionova, Josh Blyskal +6 more*

- **What:** Choose the business outcome before choosing the dashboard. A publisher, a software company and a local service provider may need different priorities.
- **Do:** State whether the goal is accurate representation, qualified product demand, subscriptions, reader loyalty or public-service reach; rank opportunities accordingly.
- **Check:** Decision relevance and agreed outcome targets; avoid a universal citation target.
- **Why:** A defined business or publisher objective prevents optimizing visibility that has little audience or commercial value.

### 84. Research actual audience questions, discovery habits and nonlinear journeys
*Do first · Applies to: Cross-platform practice · Owner: Audience research + sales/support/editorial · Key sources: Kevin Indig, Barry Adams, Louise Linehan, Lauren Welles Medley +18 more*

- **What:** Use customer conversations, site data and audience research to find meaningful questions. A synthetic prompt list is not a complete measurement of demand.
- **Do:** Interview relevant readers/customers and frontline staff; use consented material to document real questions, channels and validation steps.
- **Check:** Documented needs, research coverage and agreement between tracked prompts and actual audience language.
- **Why:** Audience evidence identifies relevant needs and channels before content or tracking investments are selected.

### 85. Vet vendor case studies, tools and benchmarks before buying or scaling
*Do first · Applies to: Cross-platform practice · Owner: SEO lead + procurement/analytics · Key sources: Aleyda Solis, iPullRank, Despina Gavoyannis, Conor Baker +4 more*

- **What:** Inspect how a case study defines success. Check sample selection, controls, costs and whether results came from a live platform or a custom laboratory setup.
- **Do:** Ask for exact sample, collection mode, denominators, exclusions, timing, controls and surviving results; distinguish product promotion from proof.
- **Check:** Replicable methodology, fit for the decision and unresolved limitations before purchase.
- **Why:** Opaque samples and promotional claims can lead to costly tools or strategies with no demonstrated relevance.

### 86. Assign cross-functional owners, review cadence and decision-ready reporting
*Do first · Applies to: Cross-platform practice · Owner: Project/business lead · Key sources: Lily Ray, Gianluca Fiorelli, Lauren Welles Medley, iPullRank +11 more*

- **What:** Assign owners for content, engineering, PR and analytics work. A reporting cadence is useful only if it leads to a decision.
- **Do:** Assign one decision owner and named editorial, technical and analytics counterparts; use a short issue log with evidence and next steps.
- **Check:** Resolved high-value issues, review timeliness and outcome-based decisions.
- **Why:** Clear ownership prevents factual, technical and measurement issues from remaining unresolved between teams.

### 87. Revalidate after material content, product or platform changes
*Do first · Applies to: Cross-platform practice · Owner: SEO/analytics + fact owners · Key sources: Microsoft Bing, Cata Milos, Fabrice Canel, Krishna Madhavan +6 more*

- **What:** Recheck important facts and access after meaningful changes. Record changes rather than treating every fluctuation as a content problem.
- **Do:** Maintain a changelog and recheck material sources after platform releases, important page updates or factual corrections.
- **Check:** Unresolved drift, corrected errors and comparable post-change observations.
- **Why:** Platform and product changes can invalidate previous controls or conclusions; revisit material assumptions when conditions change.

### 88. Evaluate publisher participation and partnership choices against an explicit policy
*Situational · Applies to: Publishers · Owner: Publisher leadership + legal/business · Key sources: Marie Haynes, Crystal Carter, Veruska Anconitano*

- **What:** Publishers should weigh licensing and participation against their business model and editorial policy. This is a conditional business choice, not a universal GEO tactic.
- **Do:** Document audience, licensing and economic considerations before any AI participation, exclusion or partnership choice; compare limited approved tests.
- **Check:** Policy clarity and observed business consequences with uncertainty.
- **Why:** Publisher participation choices may affect rights, audience access and economics; they require accountable policy decisions.

### 89. Distinguish paid-ad controls and merchant programs from organic GEO
*Situational · Applies to: Ecommerce, Advertising · Owner: Paid media/merchant owner · Key sources: OpenAI*

- **What:** Separate paid advertising and merchant participation from organic website visibility. Their controls and success measures are different.
- **Do:** Separate ad-specific information controls and commerce participation from organic search eligibility in the project plan.
- **Check:** Correct program scope and advertiser/merchant outcomes.
- **Why:** Advertising and commerce controls should be isolated because their requirements do not establish organic GEO benefits.

### 90. Evaluate relevant native experiences and integrations without assuming web-citation lift
*Situational · Applies to: Specialized · Owner: Product lead + engineering · Key sources: Crystal Carter, Ray Grieselhuber, Dr. Peter J. Meyers*

- **What:** Evaluate native integrations on their own value. A useful app or agent interface does not automatically improve citations to ordinary web pages.
- **Do:** Evaluate a native assistant experience or integration only when a real audience task and support/maintenance model justify it.
- **Check:** Task completion and customer value, measured independently of web citations.
- **Why:** Native experiences need a real task and maintenance case; integration does not inherently improve public web citations.

### 91. Keep uncertain laboratory tactics as bounded experiments rather than production rules
*Test · Applies to: Specialized · Owner: Research/ML + editorial · Key sources: Olivier Martinez, Crystal Carter, Dr. Peter J. Meyers*

- **What:** Keep uncertain tactics in a bounded test with a baseline and a stop condition. Do not sell laboratory findings as established production rules.
- **Do:** Translate a laboratory finding into a safe falsifiable local test with real facts; keep historical models and artificial retrieval conditions explicit.
- **Check:** Held-out outcomes, null results and external-validity limits; no promised real-platform lift.
- **Why:** Artificial-source or historical-model findings need safe local validation before they can justify production changes.

---

## Quick index by priority

- **Do first:** 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 24, 25, 26, 27, 28, 29, 30, 31, 32, 33, 34, 50, 51, 52, 53, 54, 55, 56, 57, 58, 59, 60, 61, 62, 63, 64, 65, 66, 73, 74, 75, 83, 84, 85, 86, 87
- **Do next:** 16, 17, 18, 19, 20, 21, 22, 35, 36, 37, 67, 68, 69, 70, 71, 76, 77, 78, 79, 80
- **Situational:** 23, 38, 39, 40, 41, 42, 43, 44, 45, 46, 47, 48, 72, 81, 82, 88, 89, 90
- **Test:** 49, 91

## Methodology and attribution notes (from the guide)

- Research workbook (Oct 18, 2026): 247 source records + 3-source supplement = 250; 1,329 evidence records; 91 recommendations; 204 distinct linked resources after URL dedup. 182 pages substantively reviewed historically (170 full, 12 partial); 11 clause-level evidence records remain partially verified.
- Evidence roles: platform documentation supports the operator's controls and definitions; practitioner advice supports only its stated component; research findings keep their sampling and lab limits; editorial recommendations are GDdash's interpretation and safeguards; context/counterevidence is not endorsement.
- A reference supports only its stated aspect of a recommendation. Source popularity, repeated publication and sponsored coverage do not establish effectiveness.
- Inclusion does not imply that cited people or organizations endorse the guide, its examples or ratings. Editorial publisher: GDdash.
