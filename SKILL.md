---
name: competitor-content-breakdown
description: Analyze same-platform competitor/social benchmark merchant accounts and market-validated content patterns for a product, niche, or offer. Use when the user asks for 对标拆解, 竞品账号拆解, 小红书/抖音/Threads/X 等目标平台账号拆解, 爆款内容拆解, market-validated content research, conversion-potential account analysis, reusable hooks, low-quality content traps, or account positioning advice based on product name, price, selling points, target users, target platform, competitors, and traffic destination.
---

# Competitor Content Breakdown

## Purpose

Use this skill to judge what content and account patterns have already been validated by the market for a specific product or niche. The goal is not to list random accounts; the goal is to separate real conversion potential from vanity heat, then extract reusable content logic.

Only use accounts from the user's target platform as benchmark accounts. If the target platform is 小红书, benchmark accounts must be 小红书 accounts; if the target platform is X, benchmark accounts must be X accounts. External websites, other platforms, and search results may be used only as background evidence, not as items in the benchmark account list.

## Required Inputs

Collect or infer these fields before analysis:

- Product name
- Product price
- Selling points
- Target users
- Target platform
- Competitors or similar products
- Desired traffic destination

If more than two fields are missing, ask the user for the missing fields. If only one or two fields are missing, make conservative assumptions and label them.

## Research Rules

- Use current platform evidence whenever possible. Search or browse when data can change, especially for follower counts, recent posts, engagement, product pages, links in bio, offers, or platform trends.
- Restrict benchmark accounts to the target platform provided by the user. If the user gives multiple target platforms, group account lists and content breakdowns by platform; do not mix accounts from other platforms into a platform's benchmark list.
- Define benchmark accounts as merchant or creator accounts on the target platform that resemble the user's account positioning, product, content, or audience. Classify each candidate as one or more of:
  - Product benchmark: similar category, price band, selling point, target user, or purchase scenario.
  - Content benchmark: similar presentation form, content quality, topic style, or production level.
  - Audience benchmark: similar follower size, follower profile, user needs, or comment behavior.
- Search precise keywords first: brand/product words, core effect words, category words, industry words, and competitor words. Then expand to broad keywords: hot-search words, related words, scenario words, pain words, and audience words.
- Find candidates through platform search result account lists, high-performing notes/posts, comment sections, shop result pages, live/shop tabs, or related recommendation flows.
- Apply these hard benchmark-account filters before selecting accounts:
  - Followers must be 1,000+.
  - The account must have posted or updated within the past month.
  - At least 90% of the homepage's visible/recent content must be related to the user's input product, category, or directly adjacent buyer problem.
  - Average likes across the account's recent visible posts must be greater than 100.
  - If any filter cannot be verified because the platform hides data or blocks access, mark that field as "未确认" and use the account only as a secondary candidate unless its other evidence is unusually strong.
- Prefer accounts with visible monetization paths: profile link, lead magnet, consultation, course, paid community, product page, shop, booking page, newsletter, app download, or repeat CTA.
- Do not treat high likes as enough. Check whether the account repeatedly attracts the target user's problem language, purchase intent, questions, saves, shares, comments, DMs, or link-click intent.
- Prefer recently active, growing accounts with good explosive-post interaction, fast topical updates, clear originality, and monetization paths matching the user's goal.
- For ordinary-person reference accounts, prioritize 5k-100k followers. Prioritize 5k-10k or under-10k accounts when the user needs realistic early-stage benchmarks. Avoid accounts below 1k followers unless a post has unusually strong evidence, and avoid accounts above 100k followers when their authority, team, or brand scale makes them hard to imitate.
- When the target platform exposes shops or sales ranking, search core industry keywords, filter accounts with matching fan profile and 5k-100k followers, then sort by sales or shop performance and select the top three strongest accounts as priority benchmarks.
- Avoid accounts whose traffic depends mainly on personal fame, controversy, giveaways, gossip, sexualized attention, platform-native entertainment unrelated to buyer intent, obvious data fraud, low originality, or low-quality repetitive content.
- Compare content against product fit: audience match, pain intensity, buying urgency, price tolerance, trust requirement, and path to conversion.

## Workflow

1. Clarify the offer.
   - Restate the product, price band, target user, core promise, and traffic destination.
   - Identify the likely buying trigger: pain relief, status improvement, income gain, time saving, risk avoidance, identity expression, or convenience.

2. Build benchmark search angles.
   - Search by product category, user pain, desired outcome, competitor names, alternative solutions, and content phrases users would search or comment.
   - Use target-platform searches only when selecting benchmark accounts.
   - For each angle, look for accounts that publish repeatedly about the same buyer problem, not only one viral post.

3. Select benchmark accounts.
   - Choose 5-12 accounts when possible.
   - First exclude accounts that fail the hard filters: under 1,000 followers, no update in the past month, less than 90% product/category relevance on visible homepage content, or average recent likes at or below 100.
   - Mix product benchmarks, content benchmarks, audience benchmarks, direct competitors, adjacent solution accounts, creator-led educators, and small high-efficiency merchant accounts.
   - For each account, record why it qualifies as a benchmark and what conversion signal is visible.
   - If platform shop or sales data is visible, include the top three sales-ranked candidates for the core keyword when they match the user's target user and price band.

4. Break down benchmark content.
   - For each selected account, inspect its recent 10 posts/notes when visible.
   - Identify posts whose interaction is far above that account's baseline, preferably from the past week when enough data exists.
   - Prioritize posts with clear above-baseline performance, strong comment quality, saves/shares signals when visible, obvious sales/lead-capture intent, or comments that reveal new user needs.
   - Capture the content topic, hook, format, emotional trigger, proof element, CTA, audience reaction, and reuse potential.

5. Score signal quality.
   - Market validation: Does repeated content prove the audience cares?
   - Conversion potential: Does the content attract people likely to buy or leave leads?
   - Product fit: Can this pattern sell the user's specific offer at its price?
   - Replicability: Can a new or smaller account reuse the pattern without celebrity status or heavy production?
   - Risk: Is the pattern platform-gimmicky, low-trust, hard to sustain, or misaligned with the user's brand?

6. Synthesize reusable rules.
   - Extract common topic clusters, hook formulas, proof mechanisms, narrative arcs, CTA patterns, and comment triggers.
   - Pull new topic ideas from platform search dropdown terms, search-result related tags/phrases, and high-like comments under benchmark explosive posts.
   - Separate "can copy the structure" from "should not copy the exact style."
   - Convert patterns into templates the user can adapt immediately. When recommending imitation, imitate the title structure, scene angle, layout logic, and high-interaction elements, then replace the benchmark account's proof and offer with the user's differentiated selling point.

## Output Format

Return the answer in Chinese unless the user asks otherwise. Use tables for scan-heavy sections.

### 1. 对标账号列表

Include columns:

- 账号/链接
- 平台
- 对标类型: 商品对标/内容对标/粉丝对标
- 账号定位
- 粉丝量/体量
- 近一月是否更新
- 主页内容相关度是否 >=90%
- 近 visible 内容平均点赞是否 >100
- 赞藏数/互动体量
- 主要产品或变现路径
- 店铺/直播/专栏/私域/广告情况
- 代表内容方向
- 转化潜力判断
- 为什么值得对标
- 风险或不适合照抄之处

### 1A. 账号基础信息与定位拆解

For each priority account, include:

- Account ID, nickname, avatar, profile/homepage, followers, likes/saves/collections when visible.
- Design strengths, weak spots, and learnable cues.
- Account track, niche, user profile, price band, audience needs, user pains, persona labels, language style, interaction style, persona reinforcement methods, monetization goal, whether it takes ads, and partner brand tone when visible.
- Analyze the five background elements when visible: background image, avatar, nickname, verification, and bio.

### 2. 对标内容拆解表

Include columns:

- 账号
- 内容链接/标题
- 内容形式
- 开头钩子
- 讲述结构
- 命中的用户痛点
- 信任或证明元素
- CTA/引流方式
- 互动质量观察
- 可复用点

Also analyze account-level content style:

- Visual system: note/post style, color palette, font choice, cover consistency, image/video quality, style changes, holiday or hot-topic borrowing, learnable points, and warning points.
- Topic selection: high-frequency topics, hot-topic fit, long-tail value, main pain points, solution format, and user-perceived value.
- Content format mix: image/text, video, pure text ratios when visible; best-performing combinations; column/album setup; album themes and fit with user needs; layout logic; placement of core information.
- Video notes/posts: duration, title copy, background music, content structure, and scene.
- Image-text notes/posts: cover, title, body, tags, and comments.

### 2A. 爆款笔记/帖子专项分析

For each explosive note/post, include:

- Title: keywords such as audience, price, number, location, emotion, problem, result; and structure type such as question, quantified number, contrast, pain-point, hot-topic, checklist, or confession.
- Cover: design logic, visual hierarchy, main text, proof element, and whether it matches the title promise.
- Tags and interaction: vertical tags, broad-traffic tags, hot tags, pinned comments, reply strategy, negative-comment handling, and repeated reply scripts when visible.
- Monetization bridge: shop, live, group, private message, platform store, column/course, lead magnet, or direct product link.

### 3. 爆款内容结构总结

Summarize:

- High-frequency topic clusters
- Common opening patterns
- Common proof structures
- Common emotional drivers
- Common comment/save/share triggers
- Which structures fit this product best
- Recent explosive topics from benchmark accounts' latest 10 posts/notes, especially within the past week when visible
- Search dropdown terms, related result words, and high-like comment feedback that can enter the user's topic library

### 4. 可复用的钩子模板

Provide 10-20 templates. Make them specific to the user's product, target user, and platform. Avoid generic hooks such as "你一定要知道..." unless adapted with concrete buyer pain.

### 5. 可避开的低质内容套路

List patterns to avoid and explain why:

- Vanity-traffic topics that do not attract buyers
- Overbroad motivational content
- Pure trend-chasing without product bridge
- Fake scarcity or exaggerated income claims
- Too much education with no conversion path
- Personal diary content without transferable buyer insight
- Content that only works for already-famous creators

### 6. 该产品适合的账号定位建议

Recommend 2-4 positioning directions. For each direction include:

- Positioning sentence
- Best audience segment
- Content pillars
- Trust-building method
- Traffic destination fit
- First 10 content ideas
- Main risk

## Quality Bar

- Name concrete evidence for every "值得对标" claim.
- Distinguish "热度高" from "转化潜力强."
- Prefer fewer, stronger accounts over a long weak list.
- Make final recommendations actionable enough for the user to plan posts.
- When evidence is limited, say so and mark the conclusion as tentative.
