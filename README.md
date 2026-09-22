# Branding

Logos and marks for **[ONLY FOSS ORG](https://github.com/onlyfossorg)**.

Use these files as-is. Do not redraw or recolor them.

## Logos

Relative paths so this table renders on GitHub. Light marks sit on a dark cell so the white ink is visible.

<table>
  <thead>
    <tr>
      <th>Mark</th>
      <th>Preview</th>
      <th>PNG</th>
      <th>SVG</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Wordmark (light)</td>
      <td bgcolor="#111111" align="center">
        <img src="asset/svg/only-foss-light.svg" alt="ONLY FOSS ORG wordmark light" width="200">
      </td>
      <td><a href="asset/png/only-foss-light.png">PNG</a></td>
      <td><a href="asset/svg/only-foss-light.svg">SVG</a></td>
    </tr>
    <tr>
      <td>Wordmark (dark)</td>
      <td align="center">
        <img src="asset/svg/only-foss-dark.svg" alt="ONLY FOSS ORG wordmark dark" width="200">
      </td>
      <td><a href="asset/png/only-foss-dark.png">PNG</a></td>
      <td><a href="asset/svg/only-foss-dark.svg">SVG</a></td>
    </tr>
    <tr>
      <td>Square icon (green)</td>
      <td align="center">
        <img src="asset/svg/of-1-1-green-s.svg" alt="ONLY FOSS ORG square icon green" width="80">
      </td>
      <td><a href="asset/png/of-1-1-green-s.png">PNG</a></td>
      <td><a href="asset/svg/of-1-1-green-s.svg">SVG</a></td>
    </tr>
    <tr>
      <td>Square icon (black)</td>
      <td align="center">
        <img src="asset/svg/of-1-1-black-s.svg" alt="ONLY FOSS ORG square icon black" width="80">
      </td>
      <td><a href="asset/png/of-1-1-black-s.png">PNG</a></td>
      <td><a href="asset/svg/of-1-1-black-s.svg">SVG</a></td>
    </tr>
    <tr>
      <td>Wordmark 1:1</td>
      <td bgcolor="#111111" align="center">
        <img src="asset/svg/only-foss-1-1.svg" alt="ONLY FOSS ORG 1:1 wordmark" width="120">
      </td>
      <td><a href="asset/png/only-foss-1-1.png">PNG</a></td>
      <td><a href="asset/svg/only-foss-1-1.svg">SVG</a></td>
    </tr>
    <tr>
      <td>Wordmark 1:1 (filled)</td>
      <td align="center">
        <img src="asset/svg/only-foss-fill-1-1.svg" alt="ONLY FOSS ORG filled 1:1 wordmark" width="120">
      </td>
      <td><a href="asset/png/only-foss-fill-1-1.png">PNG</a></td>
      <td><a href="asset/svg/only-foss-fill-1-1.svg">SVG</a></td>
    </tr>
  </tbody>
</table>

Larger square variants: [green](asset/svg/of-1-1-green-b.svg) ([PNG](asset/png/of-1-1-green-b.png)) and [black](asset/svg/of-1-1-black-b.svg) ([PNG](asset/png/of-1-1-black-b.png)).

## Add this to your README.md

Copy a snippet into any project README. Each image is loaded from this repo so you do not need to vendor files. Every mark links to [https://github.com/onlyfossorg](https://github.com/onlyfossorg).

### Square badge

Small green icon for the top of a project README.

```html
<a href="https://github.com/onlyfossorg"><img src="https://raw.githubusercontent.com/onlyfossorg/branding/main/asset/svg/of-1-1-green-s.svg" alt="ONLY FOSS ORG" width="48"></a>
```

Markdown:

```markdown
[![ONLY FOSS ORG](https://raw.githubusercontent.com/onlyfossorg/branding/main/asset/svg/of-1-1-green-s.svg)](https://github.com/onlyfossorg)
```

### Wordmark

Use the **dark** SVG on light pages (GitHub’s default README). Use the **light** SVG (`only-foss-light.svg`) on dark backgrounds.

```html
<a href="https://github.com/onlyfossorg"><img src="https://raw.githubusercontent.com/onlyfossorg/branding/main/asset/svg/only-foss-dark.svg" alt="ONLY FOSS ORG" width="200"></a>
```

### Light / dark wordmark

Same swap as the [org profile](https://github.com/onlyfossorg): light ink on dark GitHub, dark ink on light GitHub.

```html
<a href="https://github.com/onlyfossorg">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/onlyfossorg/branding/main/asset/svg/only-foss-light.svg">
    <img src="https://raw.githubusercontent.com/onlyfossorg/branding/main/asset/svg/only-foss-dark.svg" alt="ONLY FOSS ORG" width="200">
  </picture>
</a>
```

## Banners

Filenames are `onlyfossorg-banner-*` in [asset/banner](asset/banner/). The artwork itself still says VCET FOSS and needs a new export.
