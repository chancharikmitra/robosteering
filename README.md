# Robotic Steering - Project Website

This repository contains the project website for **"Mechanistic Finetuning of Vision-Language-Action Models via Few-Shot Demonstrations"**.

🌐 **Live site:** [https://yourusername.github.io/robotic-steering/](https://yourusername.github.io/robotic-steering/)

---

## 📁 Repository Structure

```
robotic-steering/
├── index.html              # Main website (single-page)
├── README.md               # This file
└── media/                  # All images, videos, and assets
    ├── favicon.svg         # Browser tab icon (SVG)
    ├── favicon-16.png      # Browser tab icon (16x16) - ADD THIS
    ├── favicon-32.png      # Browser tab icon (32x32) - ADD THIS
    ├── apple-touch-icon.png # iOS icon (180x180) - ADD THIS
    ├── approach-figure.png # Method diagram
    ├── result-1.png        # Results figure 1 - ADD THIS
    ├── result-2.png        # Results figure 2 - ADD THIS
    ├── result-3.png        # Results figure 3 - ADD THIS
    ├── intro-video.mp4     # Introduction video - ADD THIS
    ├── demo1-zeroshot.mp4  # Demo 1: Zero-shot - ADD THIS
    ├── demo1-lora.mp4      # Demo 1: LoRA - ADD THIS
    ├── demo1-ours.mp4      # Demo 1: Ours - ADD THIS
    ├── demo2-lora.mp4      # Demo 2: LoRA - ADD THIS
    ├── demo2-ours.mp4      # Demo 2: Ours - ADD THIS
    ├── demo3-zeroshot.mp4  # Demo 3: Zero-shot - ADD THIS
    ├── demo3-lora.mp4      # Demo 3: LoRA - ADD THIS
    └── demo3-ours.mp4      # Demo 3: Ours - ADD THIS
```

---

## 🚀 Deployment on GitHub Pages

1. Create a new repository on GitHub
2. Upload all files maintaining the folder structure above
3. Go to **Settings** → **Pages**
4. Under "Source", select **Deploy from a branch**
5. Choose `main` branch and `/ (root)` folder
6. Click **Save**
7. Your site will be live in ~1 minute at `https://yourusername.github.io/repo-name/`

---

## ✏️ Customization Guide

### Update Authors

In `index.html`, find the `<div class="authors">` section and update:

```html
<div class="author">
    <span class="author-name">Your Name</span>
    <span class="author-affiliation">Your University</span>
</div>
```

### Add Videos

Replace the video placeholders with actual `<video>` tags. Find sections like:

```html
<div class="demo-video-wrapper">
    <div class="video-placeholder-text">...</div>
</div>
```

Replace with:

```html
<div class="demo-video-wrapper">
    <video autoplay loop muted playsinline>
        <source src="media/demo1-ours.mp4" type="video/mp4">
    </video>
</div>
```

### Add Result Figures

Find the result card placeholders:

```html
<div class="result-image">
    Result Figure 1 Placeholder
</div>
```

Replace with:

```html
<div class="result-image">
    <img src="media/result-1.png" alt="Task Performance Comparison" style="width:100%; height:100%; object-fit:cover;">
</div>
```

### Update Links

Update the paper, code, and dataset buttons in the hero section:

```html
<a href="https://arxiv.org/abs/XXXX.XXXXX" class="btn btn-primary">Paper</a>
<a href="https://github.com/yourusername/robotic-steering-code" class="btn btn-secondary">Code</a>
```

### Update Citation

Find the BibTeX block and update with your actual citation:

```bibtex
@article{roboticsteering2025,
  title={Mechanistic Finetuning of Vision-Language-Action Models 
         via Few-Shot Demonstrations},
  author={LastName, FirstName and ...},
  journal={arXiv preprint arXiv:XXXX.XXXXX},
  year={2025}
}
```

---

## 🎨 Theme Customization

The website includes 6 built-in color themes accessible via the theme switcher (top-right corner):

| Theme | Background | Accent |
|-------|------------|--------|
| Emerald Night (default) | `#0a0a0b` | `#10b981` |
| Light Academic | `#ffffff` | `#059669` |
| Ocean Depth | `#0a0f1a` | `#3b82f6` |
| Warm Amber | `#0f0a07` | `#f59e0b` |
| Violet Research | `#0a0a12` | `#8b5cf6` |
| Cyan Circuit | `#050a0a` | `#06b6d4` |

To set a default theme, add this to the `<html>` tag:

```html
<html lang="en" data-theme="light-green">
```

To remove the theme switcher for production, delete the `<div class="theme-switcher">` block and its associated CSS/JS.

---

## 📋 Media Checklist

Before publishing, ensure you have:

- [ ] Favicon PNGs (16x16, 32x32, 180x180)
- [ ] Introduction video
- [ ] 8 demo videos (3 + 2 + 3 for each comparison section)
- [ ] 3 result figures
- [ ] Updated author information
- [ ] Updated paper/code/dataset links
- [ ] Updated BibTeX citation

---

## 📝 Video Recommendations

For best performance and compatibility:

- **Format:** MP4 (H.264 codec) or WebM
- **Resolution:** 720p or 1080p
- **Aspect ratio:** 4:3 (matches the video card layout)
- **Length:** Keep demos short (5-15 seconds) for quick loading
- **Compression:** Use tools like HandBrake to reduce file size

---

## 📄 License

This website template is provided for academic use. Please update with your own license as appropriate.
