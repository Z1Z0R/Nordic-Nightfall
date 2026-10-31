# Nordic Nightfall

A dark Omarchy theme inspired by a Nordic winter night: deep blue-black surfaces, muted cold-blue accents, dark-blue focus borders, and an emerald aurora above snow-shadowed mountains.

**Author:** Z1Z0R  
**Repository:** [https://github.com/Z1Z0R/Nordic-Nightfall](https://github.com/Z1Z0R/Nordic-Nightfall)  
**Mode:** Dark  
**Tags:** nordic, winter, aurora, blue, dark

## Desktop screenshot

![Nordic Nightfall running on Omarchy](submission-assets/nordic-nightfall.webp)

The 4K source capture is included at `submission-assets/nordic-nightfall-4k.png`.

## Install

Install from GitHub:

```sh
omarchy theme install https://github.com/Z1Z0R/Nordic-Nightfall.git
```

The theme uses a custom, darker blue variant of the Yaru folder icons and applies
its GTK colors only while Nordic Nightfall is active. Install the appearance
hook, then apply the theme:

```sh
omarchy hook install theme-set ~/.config/omarchy/themes/nordic-nightfall/hooks/50-nordic-nightfall-appearance
omarchy theme set nordic-nightfall
```

The hook installs the icon overlay and applies Files-only GTK styles when this
theme is selected, then restores the GTK stylesheets that were in place before
installation when you switch to another theme. Close and reopen Files after
switching themes so it reloads the active GTK styles.

## Wallpaper credits

All four included wallpapers were generated specifically for this theme with OpenAI Image Generation; no external source photograph was used. Each is 3840 × 2160, upscaled from a 1672 × 941 generated image with Lanczos resampling.

- `backgrounds/001-nordic-winter-shadowed-snow.png` is the darker, cooler night-snow version.
- `backgrounds/002-nordic-winter-aurora-lit-snow.png` has brighter aurora-lit slopes.
- `backgrounds/003-nordic-forest-cabin.png` shows a snow-covered Nordic forest, cabin, and river beneath a broad aurora.
- `backgrounds/004-nordic-forest-cabin-clearing.png` frames the cabin with fir, pine, and birch trees around an open clearing.

Use `omarchy theme bg next` to cycle between the backgrounds after installing the theme.

The palette and included generated wallpapers are provided under the MIT License
in this repository. The adapted Yaru folder icons retain their CC BY-SA 4.0
license; see [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md).
