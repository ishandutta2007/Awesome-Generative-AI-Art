# Awesome-Generative-AI-Art

## Top Generative AI Art Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Text-to-Image Generation, Local Diffusion Workflows & Self-Hosted Creative Pipelines*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Generative AI Art**. These tools enable creators to generate images from text prompts, edit existing images, train custom styles, and run entire creative pipelines locally—without per-image API costs or cloud dependency.



**Examples** include Midjourney, DALL-E 3, Adobe Firefly, Leonardo.ai, Ideogram, Recraft, NightCafe, Stable Diffusion (SDXL/FLUX), ComfyUI, and Automatic1111 (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom model training, and transparent generation pipelines—ideal for artists who need full control, studios avoiding per-image costs, and researchers exploring diffusion architectures. The open-source landscape is anchored by **ComfyUI** (node-based workflow standard), **Automatic1111** (the classic web UI), **InvokeAI** (professional creative engine), **Fooocus** (Midjourney-like simplicity), and the foundational models **FLUX.1** and **SDXL** that power them.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Midjourney](https://www.midjourney.com/)**  

  The aesthetic ceiling for stylized, painterly, and cinematic output. Accessible via Discord and web interface. Paid plans only (starting ~$10/month), with no free tier. Proprietary model with no local deployment option .



- **[DALL-E 3 (OpenAI)](https://openai.com/dall-e-3)**  

  OpenAI's text-to-image model integrated into ChatGPT. Strong prompt understanding and conversational editing—you can refine images through dialogue. Weaker on typography and text rendering. Requires ChatGPT Plus subscription ($20/month) or API credits .



- **[Adobe Firefly](https://www.adobe.com/products/firefly.html)**  

  The enterprise-safe option: trained exclusively on Adobe Stock and licensed content, with commercial-use indemnification. Integrated directly into Photoshop (Generative Fill, Expand) and Illustrator. Quality competitive on stock-style imagery but lags Midjourney/FLUX on dramatic, stylized work. Included in Creative Cloud subscriptions .



- **[Leonardo.ai](https://leonardo.ai/)**  

  Game asset generation specialist. Curated models (Phoenix, Anime XL, Lightning XL) produce consistent, game-usable output for character sheets, weapon concepts, and environment tiles. Generous free tier (150 credits/day). Paid plans from $12/month with a usable API .



- **[Ideogram](https://ideogram.ai/)**  

  Best-in-class text rendering within images. Ideal for posters, logos, and typography-heavy designs. Paid plans start at ~$7/month. Ranked highly on open-weight leaderboards for text accuracy .



- **[Recraft](https://www.recraft.ai/)**  

  Vector art and brand consistency specialist. Generates SVG output and maintains style coherence across assets—a category of its own for design systems and brand identity work. Starting at $12/month .



- **[NightCafe](https://creator.nightcafe.app/)**  

  Community-first platform running multiple models (FLUX, SDXL, DALL-E 3, Ideogram) under one interface. Daily challenges and social features make it the best on-ramp for beginners. Free daily credits; paid plans from $6/month .



- **[Krea](https://www.krea.ai/)**  

  Real-time generation canvas aggregating FLUX, Stable Diffusion 3.5, Ideogram, and Krea-1. The image updates as you sketch or type—best for iterative exploration where you "know it when you see it." Starting at $10/month .



## Open-Source GitHub Projects



- **[ComfyUI](https://github.com/comfyanonymous/ComfyUI)**  

  The most powerful modular diffusion GUI and backend. Node-based graph interface where you wire together models, samplers, ControlNet, upscalers, and custom nodes into complete workflows. **The de facto standard for advanced users**—nearly every new technique (FLUX, SDXL, video models) gets ComfyUI support first. Supports FLUX.1, SDXL, SD 1.5, and modern video diffusion models. GPL-3.0 licensed. Best for users who want maximum control and reproducible pipelines .



- **[Automatic1111 (Stable Diffusion WebUI)](https://github.com/AUTOMATIC1111/stable-diffusion-webui)**  

  The classic Gradio-based web interface that brought Stable Diffusion to the masses. Simple text-to-image, img2img, inpainting, and extension ecosystem. **Ecosystem is aging**: development has slowed, and many users are migrating to Forge (an optimized fork) or ComfyUI. Best for beginners who want a familiar, straightforward interface without node graphs .



- **[InvokeAI](https://github.com/invoke-ai/InvokeAI)**  

  Professional creative engine with a polished canvas-based interface. Unified canvas for inpainting, outpainting, and regional prompts. Strong model management and a clean workflow. Positioned for artists who want power without ComfyUI's node complexity. Best for professional creative work requiring precise regional control .



- **[Fooocus](https://github.com/lllyasviel/Fooocus)**  

  A rethinking of Stable Diffusion with Midjourney's design philosophy: minimal configuration, good defaults, and focus on prompting. No complex settings—just type and generate. SDXL-based. Best for users who want Midjourney-like simplicity locally without node graphs or endless parameters .



- **[Stable Diffusion WebUI Forge](https://github.com/lllyasviel/stable-diffusion-webui-forge)**  

  An optimized fork of Automatic1111 with improved VRAM management and speed. Often runs on lower-end GPUs where the original struggles. Adds FLUX and modern model support through Forge Neo variants. Best for users who want the A1111 interface with better performance and newer model support .



- **[SwarmUI](https://github.com/mcmonkeyprojects/SwarmUI)**  

  Modular, high-performance web UI for image and video diffusion. Emphasis on making power tools accessible and extensible. Best for users who want a more modern, actively maintained alternative to A1111 with better performance characteristics .



- **[Diffusers (Hugging Face)](https://github.com/huggingface/diffusers)**  

  The official library for diffusion pipelines in PyTorch. State-of-the-art implementations for image, video, and audio generation. Essential for developers building custom pipelines or fine-tuning workflows. Best for Python developers who need programmatic control over diffusion models .



### Foundational Open-Weight Models



- **[FLUX.1](https://github.com/black-forest-labs/flux)**  

  Black Forest Labs' model family—**the photorealism and prompt adherence standard** for open weights. FLUX.1 [dev] offers high quality for complex prompts, text rendering, and detail; [schnell] is the 4-step distilled speed variant. **VRAM requirements**: ~24GB for FP16, ~12GB for FP8, ~8GB for GGUF Q4 (practical floor). Apache 2.0 for [schnell]; [dev] has non-commercial weights but commercial usage via authorized platforms .



- **[Stable Diffusion XL (SDXL)](https://github.com/Stability-AI/generative-models)**  

  The ecosystem workhorse. Massive library of community fine-tunes and LoRAs, broad ControlNet compatibility, and lower VRAM requirements (~8GB FP16). Weak on text rendering but unmatched for style diversity and community tooling. Best for users who want the widest selection of community models and styles .



- **[GLM-Image](https://github.com/zai-org/GLM-Image)**  

  MIT-licensed ~16B parameter model with a dedicated Glyph Encoder for text rendering. Scores 91.16% on CVTG-2K for in-image text accuracy—the best verified benchmark for poster, label, and signage generation. Requires ~12GB VRAM. Smaller ecosystem than SD/FLUX but the most permissive license for text-heavy work .



### Additional Strong Open-Source Options



- **IOPaint / Lama Cleaner** — Open-source inpainting and object removal tools. Best for cleaning up generated images or removing unwanted elements .

- **Real-ESRGAN** — Practical AI upscaler commonly paired with Stable Diffusion outputs. Best for increasing resolution without losing detail .

- **ControlNet** — Spatial conditioning for diffusion models (pose, depth, edges). Essential for precise composition control .

- **kohya_ss / OneTrainer** — Training GUIs for LoRA and DreamBooth. Best for creating custom styles or character consistency .

- **Frameworks for building custom systems**: Use **ComfyUI** as the workflow backbone, **FLUX.1** or **SDXL** as the base model depending on text vs. style needs, **ControlNet** for composition, and **Real-ESRGAN** for upscaling. For programmatic pipelines, use **Diffusers** with **FLUX** or **SDXL** checkpoints. Train custom styles with **kohya_ss**.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- "Open-source" for image models means **open weights**—training data and code are rarely released in full. License terms vary significantly: Apache 2.0 (FLUX schnell, GLM-Image) allows commercial use; FLUX dev weights are non-commercial without platform licensing; SDXL uses CreativeML OpenRAIL .

- Local generation requires adequate GPU VRAM (8GB minimum for quantized models, 12–24GB for full quality) and involves setup time that hosted services eliminate.

- **ArtCraft** (storytold/artcraft) is a creative application suite, not a generative image model—it's a different category from the tools listed here .



---



**Made for digital artists, creative technologists, game developers, and anyone building generative art pipelines without per-image API bills.**  

Let's make generative AI art more open, controllable, and accessible.
