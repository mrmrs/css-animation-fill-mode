# css-animation-fill-mode

Functional CSS for animation-fill-mode

## Filesize

| File | Size |
|------|------|
| `dist/animation-fill-mode.css` | 965 bytes |
| `dist/animation-fill-mode.min.css` | 735 bytes (177 Gzipped) |

## Install

```sh
npm install css-animation-fill-mode
```

## Usage

### Import

```css
@import "css-animation-fill-mode";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-animation-fill-mode/dist/animation-fill-mode.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-animation-fill-mode/dist/animation-fill-mode.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.a-fil-non` | `animation-fill-mode: none;` |
| `.a-fil-frw` | `animation-fill-mode: forwards;` |
| `.a-fil-bck` | `animation-fill-mode: backwards;` |
| `.a-fil-bth` | `animation-fill-mode: both;` |
| `.a-fil-non-s` | `animation-fill-mode: none;` |
| `.a-fil-frw-s` | `animation-fill-mode: forwards;` |
| `.a-fil-bck-s` | `animation-fill-mode: backwards;` |
| `.a-fil-bth-s` | `animation-fill-mode: both;` |
| `.a-fil-non-m` | `animation-fill-mode: none;` |
| `.a-fil-frw-m` | `animation-fill-mode: forwards;` |
| `.a-fil-bck-m` | `animation-fill-mode: backwards;` |
| `.a-fil-bth-m` | `animation-fill-mode: both;` |
| `.a-fil-non-l` | `animation-fill-mode: none;` |
| `.a-fil-frw-l` | `animation-fill-mode: forwards;` |
| `.a-fil-bck-l` | `animation-fill-mode: backwards;` |
| `.a-fil-bth-l` | `animation-fill-mode: both;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.a-fil-non-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/animation-fill-mode.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/animation-fill-mode.css` — formatted
- `dist/animation-fill-mode.min.css` — minified

## License

MIT
