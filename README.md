# EYROVE

**AI image prompt wall, prompt reverse tools and a local MCP server for image generation.**

EYROVE has three parts that share one account, one credit balance and one record of generations: a prompt inspiration wall, a toolkit for turning any image into a prompt, and an MCP server that lets coding agents generate images with the same account.

![EYROVE inspiration wall](app_inspiration.png)

## 1. Prompt inspiration wall (eyrove.com/app)

A visual feed of finished work instead of an empty generator. Filter by image model — GPT Image, Gemini, Midjourney, Seedream, Grok, Flux — or by use case, from e-commerce hero shots and product pages to marketing assets, beauty, exhibition backdrops, product scenes and social covers. Search by text or by image.

Open any work and a detail panel shows the image, its model, aspect ratio, creator and source. Full prompt text needs a free account; once signed in, three buttons turn a reference into output: create in the same style, generate again, or copy the prompt.

## 2. Prompt reverse toolkit

**Browser extension — Eyrove Prompt.** Hover, right-click or box-select an image on any page, then analyse it, extract colour and pose references, or send it straight into EYROVE. Images that carry generation metadata get their original prompt and model back for 0 credits; a full eight-dimension analysis (subject, composition, style, light and colour, material, pose, layout, constraints) costs 65 credits and returns an editable prompt. The Pro build is on the Chrome Web Store; PROMPT LITE is an open-source BYOK build (https://github.com/geslie1/eyrove-prompt-lite).

**SkillHub (eyrove.com/app?workspace=skills).** Six tools in one place: prompt reverse, high-resolution upscale and restoration, product retouching across seven materials, portrait retouching that keeps identity and skin texture, plus two tools that run locally and never upload the image — batch compression and exact resize. Local tools are free.

## 3. MCP server (eyrove.com/app?workspace=mcp)

`eyrove-image-mcp` v0.2.1 is a local Node.js package (Node 22+) that connects EYROVE to Codex, Claude Code or Cursor with eight tools: account and points, model capabilities, image upload, quotes, generation and editing, task lookup, waiting for images, and downloading originals. It uses the user's own account key with an optional spending limit, so the agent spends points rather than the developer.

## Links

- Product: https://eyrove.com
- Inspiration wall: https://eyrove.com/app
- SkillHub tools: https://eyrove.com/app?workspace=skills
- MCP server: https://eyrove.com/app?workspace=mcp
- Browser extension: https://eyrove.com/zh-cn/eyrove-prompt
- Free generator (no account): https://eyrove.com/en/free-ai-image-generator
- Open-source BYOK extension: https://github.com/geslie1/eyrove-prompt-lite
- Guides: https://eyrove.com/en/guides

## Details

| | |
|---|---|
| Category | AI image generation · AI prompt library · MCP server |
| Models | GPT Image, Gemini, Midjourney, Seedream, Grok, Flux |
| Languages | 7 |
| Pricing | Free tier; credits per action; paid plans add points and concurrency |
| Contact | support@eyrove.com |

## What it looks like

![Detail panel with prompt, model and actions](app_prompt_detail.png)

## License

This repository holds the product showcase, not the application source. The BYOK browser extension is open source under its own license in the repository linked above.
