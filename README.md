# Beatra

**Beatra (beatra.ai) is a creative runtime for AI agents: install one Agent Skill or connect the Beatra MCP server, describe what you want, and your agent generates images, video, music, and speech, and looks up public social data — all billed from one credit balance.**

给你正在用的 AI 智能体加上图片、视频、音乐和配音：装一个 Skill（或接入 Beatra MCP），说清楚想要什么，Beatra 就会帮你生成。国内用户请访问 [beatra.cn](https://www.beatra.cn/zh)。

いつものAIエージェントで、画像・動画・音楽・音声を。スキルを入れるか Beatra MCP を接続して、作りたいものを伝えれば Beatra が生成します。

```bash
npx skills add beatra-ai/ai-media-generator-skill
```

Then ask your agent: *"Turn this product photo into a 5-second clip with a slow push-in."*

> [!NOTE]
> Every skill is free to install; rendering uses Beatra credits. Works with Claude Code, Cursor, Codex, Windsurf, Cline, OpenClaw, and WorkBuddy, plus any MCP client.

### Connect over MCP

| | |
| --- | --- |
| Remote MCP endpoint | `https://mcp.beatra.ai/mcp` (streamable HTTP, Beatra sign-in token) |
| Official MCP Registry | [`ai.beatra/beatra`](https://registry.modelcontextprotocol.io/v0/servers?search=beatra) |
| REST / OpenAPI | [docs.beatra.ai](https://docs.beatra.ai/?utm_source=github&utm_medium=profile&utm_campaign=beatra-ai) |

## Prompt libraries

| [<img src="assets/awesome-qwen-image-3.jpg" alt="Awesome Qwen Image 3.0" width="420">](https://github.com/beatra-ai/awesome-qwen-image-3) | [<img src="assets/awesome-wan-3-video.jpg" alt="Awesome Wan 3.0 Video" width="420">](https://github.com/beatra-ai/awesome-wan-3-video) |
| --- | --- |
| **[Awesome Qwen Image 3.0](https://github.com/beatra-ai/awesome-qwen-image-3)**<br>40 cases · full prompts · CC BY 4.0 | **[Awesome Wan 3.0 Video](https://github.com/beatra-ai/awesome-wan-3-video)**<br>20 cases · full prompts · CC BY 4.0 |

## Skills

### Images (8)

| Skill | What it does |
| --- | --- |
| [ai-media-generator-skill](https://github.com/beatra-ai/ai-media-generator-skill) | Create AI images, videos, music, and voice-over from one Agent Skill. |
| [ai-logo-maker-skill](https://github.com/beatra-ai/ai-logo-maker-skill) | Turn a brand name, industry, or reference image into logo concepts and a scalable brand mark. |
| [ai-poster-maker-skill](https://github.com/beatra-ai/ai-poster-maker-skill) | Turn an event description, a product photo, or brand references into an event poster, promo banner, or social media graphic with clear visual hierarchy, category-matched style, and space kept for text. |
| [ai-image-generator-skill](https://github.com/beatra-ai/ai-image-generator-skill) | Generate, compose, and edit product images, brand visuals, posters, social graphics, illustrations, and photo variations. |
| [photo-to-anime-skill](https://github.com/beatra-ai/photo-to-anime-skill) | Turn a photo into anime, manga, comic, cartoon, watercolor, clay, or 3D character art while the subject stays recognizable, and reuse the same look across a whole set. |
| [ai-headshot-generator-skill](https://github.com/beatra-ai/ai-headshot-generator-skill) | Turn a casual selfie into a professional headshot with a new background, business attire, and studio lighting for resumes, company websites, career profiles, and social media. |
| [ai-image-realism-skill](https://github.com/beatra-ai/ai-image-realism-skill) | Make existing AI portraits, product images, and marketing visuals look more natural by fixing plastic skin, malformed hands and faces, repeated textures, and inconsistent lighting. |
| [ai-storyboard-generator-skill](https://github.com/beatra-ai/ai-storyboard-generator-skill) | Turn a script, scene, or ad brief into a practical shot list and one to four storyboard key-frame images. |

### Video (3)

| Skill | What it does |
| --- | --- |
| [talking-avatar-video-skill](https://github.com/beatra-ai/talking-avatar-video-skill) | Turn one portrait and a short script into a talking avatar video. |
| [ai-video-generator-skill](https://github.com/beatra-ai/ai-video-generator-skill) | Generate, animate, edit, and extend short AI videos for ads, product stories, social posts, b-roll, transitions, and cinematic concepts. |
| [viral-video-remake-skill](https://github.com/beatra-ai/viral-video-remake-skill) | Break a short video that worked into its hook, beats, and call to action, then rebuild that structure around your own subject as a shot list, beat frames, and narration, delivered as one vertical clip or as segmented sources with captions and a timecoded edit list. |

### Music & Voice (7)

| Skill | What it does |
| --- | --- |
| [ai-music-generator-skill](https://github.com/beatra-ai/ai-music-generator-skill) | Turn a theme, lyrics, or reference audio into songs, instrumentals, and soundtracks. |
| [lyrics-to-song-skill](https://github.com/beatra-ai/lyrics-to-song-skill) | Turn full lyrics, a rough draft, or a hook into a structured song with clear sections, style, and vocal direction. |
| [ai-podcast-voiceover-skill](https://github.com/beatra-ai/ai-podcast-voiceover-skill) | Turn an article, notes, or a finished script into a solo podcast episode with a consistent host voice, natural pacing, pronunciation control, and an MP3 you can publish. |
| [ai-voiceover-generator-skill](https://github.com/beatra-ai/ai-voiceover-generator-skill) | Pick or reuse a voice, turn scripts into narration ready for editing, plan ordered long-form or multilingual audio, and create a reusable custom voice. |
| [multilingual-voiceover-skill](https://github.com/beatra-ai/multilingual-voiceover-skill) | Create reviewable voice-over audio for each language from your per-language scripts, with voices cast for each market, pronunciation and timing pilots first, and delivery organized by language and segment. |
| [ai-voice-cloning-skill](https://github.com/beatra-ai/ai-voice-cloning-skill) | Create a reusable personal or brand voice from a clean audio sample, give it a memorable name, and hear it in a short test reading. |
| [ai-audiobook-generator-skill](https://github.com/beatra-ai/ai-audiobook-generator-skill) | Turn a final manuscript or course text into ordered chapter audio with one narrator, a representative sample chapter first, and focused refinements. |

### E-commerce & Social (5)

| Skill | What it does |
| --- | --- |
| [ai-product-photography-skill](https://github.com/beatra-ai/ai-product-photography-skill) | Turn a real product photo into ecommerce studio photos and lifestyle scenes. |
| [ecommerce-product-images-skill](https://github.com/beatra-ai/ecommerce-product-images-skill) | Turn real product photos and confirmed SKU facts into a matching ecommerce image set: a hero image, feature visuals, lifestyle scenes, size views, and in-box images. |
| [wechat-article-cover-skill](https://github.com/beatra-ai/wechat-article-cover-skill) | Turn an article title, topic, or reference image into a WeChat Official Account cover, article hero image, or supporting visual, with space kept for the headline and focused refinement. |
| [xiaohongshu-cover-maker-skill](https://github.com/beatra-ai/xiaohongshu-cover-maker-skill) | Turn a photo or a topic idea into a vertical 3:4 Xiaohongshu cover with a clean background, a bold focal point, and text-safe areas for beauty, food, fashion, and lifestyle notes. |
| [xiaohongshu-copywriter-skill](https://github.com/beatra-ai/xiaohongshu-copywriter-skill) | Turn a product, experience, topic, or audience brief into Xiaohongshu title options, a readable note body, cover text, hashtags, and a natural comment starter. |

Full catalog: [beatra-ai/beatra-skills](https://github.com/beatra-ai/beatra-skills) — every Beatra skill in one repository.

## Models

<details>
<summary>Models (27) — image, video, music, voice, understanding</summary>

**Image** — Qwen Image 2.0 Fast, Qwen Image 3.0, Qwen Image 3.0 Pro, GPT Image 2.5 Flare, GPT Image 2.5 Sunburst, GPT Image 2, Wan Image 2.7 Fast, Qwen Image 2.0 Pro, Wan Image 2.7 Pro, MiniMax Image 01 Live

**Video** — Seedance 2.0 Mini, Wan 2.7, Wan 3.0 Video, MiniMax H3, HappyHorse 1.1, Seedance 2.0 Fast, Seedance 2.0, Wan 3.0 Video Prime, Seedance 2.5, Wan 2.7 Video Edit, HappyHorse 1.0 Video Edit

**Music** — Suno 6, MiniMax Music 3.0

**Voice** — MiniMax Speech 2.8 HD, MiniMax Speech 2.8 Turbo, MiniMax Voice Clone

**Understanding** — MiniMax M3
</details>

## FAQ

**What is Beatra?** A hosted generation service built for AI agents. Agent Skills (SKILL.md) and an OAuth MCP server let Claude Code, Cursor, Codex, and other agents create images, video, music, and speech without leaving the chat.

**Which models does Beatra use?** 27 models across image, video, music, and voice — including Seedance 2.0/2.5, Wan 3.0 Video, Qwen Image 3.0, GPT Image 2, Suno 6, and MiniMax Speech 2.8 (full list above).

**Is it free?** Installing any skill is free and open source (MIT-0). Generation consumes Beatra credits; see [pricing](https://beatra.ai/en/pricing?utm_source=github&utm_medium=profile&utm_campaign=beatra-ai).

**Does it work in mainland China?** Yes — use [www.beatra.cn](https://www.beatra.cn/zh), the WeChat mini program, or install from SkillHub / WorkBuddy.

**Beatra 是什么？** 专为 AI 智能体打造的多媒体生成服务：通过 Agent Skill 或 MCP，让 Claude Code、Cursor、Codex、WorkBuddy 等直接生成图片、视频、音乐和配音。安装免费，生成按积分计费。

## Links

- Website — [beatra.ai](https://beatra.ai/?utm_source=github&utm_medium=profile&utm_campaign=beatra-ai)
- Docs — [docs.beatra.ai](https://docs.beatra.ai/?utm_source=github&utm_medium=profile&utm_campaign=beatra-ai)
- 中国大陆官网 — [www.beatra.cn](https://www.beatra.cn/zh?utm_source=github&utm_medium=profile&utm_campaign=beatra-ai)
- Console — [console.beatra.ai](https://console.beatra.ai)
- MCP — `https://mcp.beatra.ai/mcp` · Registry `ai.beatra/beatra`
- For AI agents — [llms.txt](https://beatra.ai/llms.txt) (index) · [llms-full.txt](https://beatra.ai/llms-full.txt) (every skill in one file)

- WeChat mini program (mainland China) · 国内用户微信扫码使用

<img src="assets/beatra-mini-program-qr.jpg" alt="Beatra WeChat mini program code" width="160">
