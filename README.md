# Nordic Nightfall

A dark Omarchy theme inspired by a Nordic winter night: deep blue-black surfaces, muted cold-blue accents, dark-blue focus borders, and an emerald Aurora Borealis above snow-shadowed mountains. Two mountain wallpapers pair fractured rock faces and snow-filled gullies with a dark forest and frozen lake: one has darker snow, while the other retains brighter mountain detail. Two forest wallpapers feature fir, pine, and birch around a warm-lit cabin beside a flowing river and beneath a finely layered green Aurora Borealis. One surrounds the cabin with more trees; the other has an open snowy clearing softly lit by the cabin. Two frozen-lake wallpapers show gently sweeping green auroras above clear dark ice with fine fractures, subtle trapped bubbles, scattered frost, and subdued reflections. One has a low, tree-lined horizon, while the other places the lake in a valley framed by wooded hills.

**Author:** Z1Z0R  
**Repository:** [https://github.com/Z1Z0R/omarchy-nordic-nightfall-theme](https://github.com/Z1Z0R/omarchy-nordic-nightfall-theme)<br>
**Mode:** Dark  
**Tags:** nordic, winter, aurora, blue, dark

## Desktop screenshot

![Nordic Nightfall running on Omarchy](submission-assets/nordic-nightfall.webp)

The 4K source capture is included at `submission-assets/nordic-nightfall-4k.png`.

## Install

Install from GitHub:

```sh
omarchy theme install https://github.com/Z1Z0R/omarchy-nordic-nightfall-theme.git
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

## Wallpapers

![All six Nordic Nightfall wallpapers in a compact collage with two columns and three rows](submission-assets/wallpapers-collage.webp)

## Wallpaper credits

All six included wallpapers were generated and refined specifically for this theme with OpenAI Image Generation; no external source photograph was used. Each is 3840 × 2160, upscaled with Lanczos resampling from a 1672 × 941 generated image (1670 × 942 for the cabin clearing). Refinements were made before upscaling, with no added sharpening during the upscale.

- `backgrounds/001-nordic-winter-shadowed-snow.png` is the darker mountain version, with angular rock faces, snow-filled gullies, a varied shoreline forest, and solid lake ice with thin snow patches and subdued green reflections.
- `backgrounds/002-nordic-winter-aurora-lit-snow.png` retains brighter mountain detail, with fractured rock, naturally settled snow, a dark shoreline forest, and solid ice interrupted by thin matte snow patches.
- `backgrounds/003-nordic-forest-cabin.png` surrounds the warm-lit log cabin with more fir, pine, and birch trees beside a flowing river, with natural branch detail, small ripples around stones, and a green aurora of delicate filaments and translucent folds.
- `backgrounds/004-nordic-forest-cabin-clearing.png` shows an open snowy clearing around the cabin, bordered by fir, pine, and birch beside a flowing river, with soft cabin light on the snow and a finely layered green aurora overhead.
- `backgrounds/005-nordic-frozen-lake-aurora.png` shows a broad frozen lake with a mostly level, tree-lined horizon beneath a low green aurora of delicate filaments and layered folds, reflected softly across clear dark ice with thin fractures, subtle bubbles, and scattered frost.
- `backgrounds/006-nordic-frozen-lake-valley.png` places the lake between rounded wooded hills, with narrow green aurora rays above the distant slopes and soft reflections across dark ice with fine fractures, trapped bubbles, and sparse frost.

Use `omarchy theme bg next` to cycle between the backgrounds after installing the theme.

The palette and included generated wallpapers are provided under the MIT License
in this repository. The adapted Yaru folder icons retain their CC BY-SA 4.0
license; see [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md).

