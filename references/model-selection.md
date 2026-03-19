# Model Selection Guide

> Which AI model for which job. Choose based on the artifact type, not convenience.

## Quick Reference

| Need | Primary | Alternative | Notes |
|------|---------|------------|-------|
| **Product stills** | Nano Banana Pro (Gemini 3 Pro) | GPT Image 1.5 | Best for photorealistic product shots |
| **Hero images** | Nano Banana Pro | Grok Imagine | Wide aspect ratios, atmospheric |
| **Icons/Small graphics** | Nano Banana Pro | GPT Image 1.5 | 1:1 aspect, transparent bg |
| **Video/Animation** | Kling 3 | Veo 3 | For motion sequences |
| **Start/End keyframes** | Stitch | — | Frame interpolation between two images |
| **Product rotations** | Leonardo Product Spin Video | — | 360° sequences, extract frames |
| **Style matching** | Leonardo Style Transfer | — | Apply site identity to any image |
| **Scene placement** | Leonardo Product In Scene | — | Lifestyle product photography |
| **Relighting** | Leonardo Custom Relight | — | Match lighting across frames |
| **Background swap** | Leonardo Background Change | — | Context-match section backgrounds |
| **Canvas expansion** | Leonardo Instant Outpaint | — | Fill wider containers |
| **Scroll sequence** | Nano Banana Pro (keyframes) + ffmpeg | Kling 3 → frame extract | See scroll-engine.md |

## Nano Banana Pro (Primary for Stills)

```bash
# Basic generation
uv run {baseDir}/scripts/generate_image.py \
  --prompt "your description" \
  --filename "output.png" \
  --resolution 2K

# Specific aspect ratio
uv run {baseDir}/scripts/generate_image.py \
  --prompt "hero banner" \
  --filename "hero.png" \
  --resolution 2K \
  --aspect-ratio 16:9

# Edit existing image
uv run {baseDir}/scripts/generate_image.py \
  --prompt "make the background darker, add gold rim lighting" \
  --filename "hero-v2.png" \
  -i hero.png \
  --resolution 2K
```

**Supported Resolutions:** 1K (default), 2K, 4K
**Supported Aspect Ratios:** 1:1, 2:3, 3:2, 3:4, 4:3, 4:5, 5:4, 9:16, 16:9, 21:9

## Leonardo AI Blueprints

Access at [app.leonardo.ai](https://app.leonardo.ai/) → Blueprints section.

**Best for Iron Canvas:**
1. **Product Studio Photoshoot** — consistent studio angles
2. **Product Spin Video** — 360° rotation → frame extraction
3. **Style Transfer** — apply site DNA to any image
4. **Custom Relight** — lighting consistency across frame sets

## Frame Extraction (ffmpeg)

```bash
# From video → WebP frames
ffmpeg -i product_spin.mp4 -vf "fps=24,scale=1920:1080" frames/frame_%04d.webp

# From video → PNG frames (higher quality, larger files)
ffmpeg -i product_spin.mp4 -vf "fps=30" frames/frame_%04d.png

# Reduce frame count (every other frame)
ffmpeg -i input.mp4 -vf "fps=12,scale=1920:1080" frames/frame_%04d.webp

# Mobile-optimized (half resolution)
ffmpeg -i input.mp4 -vf "fps=24,scale=960:540" mobile/frame_%04d.webp
```
