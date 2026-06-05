# LARA Project Page

Static project page for:

**LARA: Latent Action Representation Alignment for Vision-Language-Action Models**

## Publish with GitHub Pages

1. Create a GitHub repository, for example `LARA`.
2. Upload these files to the repository root:
   - `index.html`
   - `styles.css`
   - `assets/`
3. In GitHub, open **Settings > Pages**.
4. Set **Source** to `Deploy from a branch`.
5. Select the `main` branch and `/ (root)` folder.
6. Save. The page will be available at:

```text
https://<username>.github.io/LARA/
```

If you instead create a repository named `<username>.github.io`, the page will be available at:

```text
https://<username>.github.io/
```

## Add the Video

The video section at the end of `index.html` is intentionally empty. Search for:

```html
<div class="video-frame">
```

Then paste either a local video:

```html
<video controls playsinline poster="assets/teaser.jpg">
  <source src="assets/lara-video.mp4" type="video/mp4" />
</video>
```

or a hosted embed:

```html
<iframe src="https://www.youtube.com/embed/VIDEO_ID" title="LARA video" allowfullscreen></iframe>
```
