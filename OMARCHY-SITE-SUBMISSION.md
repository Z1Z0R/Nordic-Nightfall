# Omarchy theme submission notes

## Official Omarchy themes page

The official page is updated through a pull request to `omacom-io/omarchy-site`.
The theme itself should live in its own public GitHub repository so people can install it directly.

1. Create a public repository named `omarchy-nordic-nightfall-theme` under your GitHub account and push this folder to its root.
2. A real 3840 × 2160 DP-2 capture showing the Omarchy desktop, terminal, and Neovim is already included at `submission-assets/nordic-nightfall-4k.png`. Its site-sized 1200 × 675 WebP is `submission-assets/nordic-nightfall.webp`. Review it and use it for the site asset. The screenshot is a real desktop capture, not a mockup.
3. If you take a new screenshot later, convert it to the website asset format and size:

   ```sh
   magick screenshot.png -strip -resize '1200>' -quality 80 nordic-nightfall.webp
   ```

   Put `submission-assets/nordic-nightfall.webp` at `assets/themes/nordic-nightfall.webp` in the site repository. It is 1200 × 675; check it stays under about 100 KB.
4. Add this figure to `themes/index.html` in alphabetical order among the other themes, replacing the GitHub URL if your account handle differs:

   ```html
   <figure class="themes__theme">
     <a href="https://github.com/Z1Z0R/omarchy-nordic-nightfall-theme"
       ><img
         src="/assets/themes/nordic-nightfall.webp"
         alt="Nordic Nightfall theme"
         loading="lazy"
         decoding="async"
     /></a>
     <figcaption>
       <a href="https://github.com/Z1Z0R/omarchy-nordic-nightfall-theme">Nordic Nightfall</a>
     </figcaption>
   </figure>
   ```
5. Open a pull request against `omacom-io/omarchy-site`.

## Omarchy Themes community gallery

The independent community gallery at <https://omarchythemes.dev> accepts a public GitHub repository URL through its “Submit a theme” flow. Its listing is separate from the official `omarchy.org/themes` page.

## Suggested listing copy

**Name:** Nordic Nightfall  
**Author:** Z1Z0R  
**Description:** A cold blue-gray winter palette with a vivid green aurora over Nordic mountains, with both shadowed-snow and brighter aurora-lit wallpaper options.  
**Tags:** nordic, winter, aurora, blue, dark

## Before publishing

- Confirm `Z1Z0R` is the GitHub account handle you want shown in the README and links.
- Push the repository publicly, then test `omarchy theme install <repo-url>` from a clean Omarchy install.
- Capture the real desktop screenshot described above. The included `preview.png` is a wallpaper preview, not a substitute for that screenshot.
