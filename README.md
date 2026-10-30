# YOUNG — Light & Dark for Typora

A quiet pair of themes with soft grayscale colors and the same typography as the YOUNG website: **Adobe Source Han Serif SC ExtraLight** for Chinese, **Courier New** for Latin text. This is not MingLiU.

The website uses a content subset; Typora bundles the full font from the same pinned source and weight (250), so arbitrary Chinese notes remain covered. The CSS family name is `ZYAN Ming Light`. Chinese headings use the same face with font synthesis disabled; the previous subtle text-stroke enhancement is retained.

## Typography previews

![Young Light](screenshots/young-light.png)

![Young Dark](screenshots/young-dark.png)

## Install

1. [Download and unzip](https://github.com/ZiyanLo/young-typora/archive/refs/heads/main.zip).
2. Open **Typora → Preferences → Appearance → Open Theme Folder**.
3. Copy `young-light.css`, `young-dark.css`, and the entire `young-fonts/` folder into it.
4. Restart Typora and select **Young Light** or **Young Dark**.

The font folder is required. Courier New is a system font and is not redistributed. The Latin fallback order matches the website.

## Features

- Matched light (`#dedee0`) and dark (`#232324`) palettes.
- 15px body, 1.5 line height, and 680px writing column.
- Consistent fonts across the editor and sidebar.
- Two-line sidebar summaries and no top separator. Sidebar filenames, folder names, and extensions use regular weight to keep Courier New light.
- White-background print styles.

Developed on macOS. Windows/Linux have not been tested. Native macOS title-bar fonts are outside theme CSS.

## 中文

中文与网站一致：思源宋体简体版 ExtraLight，英文为 Courier New。主题内名 `ZYAN Ming Light`，不是细明体 MingLiU。安装时必须同时复制两个 CSS 与完整 `young-fonts/` 文件夹。保留轻微加粗、深浅配色和侧栏修正。

## Font license

Bundled fonts: SIL OFL 1.1. See `young-fonts/OFL.txt` and `young-fonts/NOTICE.txt` for the source and license.
