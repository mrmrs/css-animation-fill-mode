# css-animation-fill-mode

Functional CSS for animation-fill-mode

## Filesize

| File | Size |
|------|------|
| `dist/animation-fill-mode.css` | 1032 bytes |
| `dist/animation-fill-mode.min.css` | 802 bytes (180 Gzipped) |

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
| `.a-fill-none` | `animation-fill-mode: none;` |
| `.a-fill-forwards` | `animation-fill-mode: forwards;` |
| `.a-fill-backwards` | `animation-fill-mode: backwards;` |
| `.a-fill-both` | `animation-fill-mode: both;` |
| `.a-fill-none-s` | `animation-fill-mode: none;` |
| `.a-fill-forward-s` | `animation-fill-mode: forwards;` |
| `.a-fill-backwards-s` | `animation-fill-mode: backwards;` |
| `.a-fill-both-s` | `animation-fill-mode: both;` |
| `.a-fill-none-m` | `animation-fill-mode: none;` |
| `.a-fill-forwards-m` | `animation-fill-mode: forwards;` |
| `.a-fill-backwards-m` | `animation-fill-mode: backwards;` |
| `.a-fill-both-m` | `animation-fill-mode: both;` |
| `.a-fill-none-l` | `animation-fill-mode: none;` |
| `.a-fill-forwards-l` | `animation-fill-mode: forwards;` |
| `.a-fill-backwards-l` | `animation-fill-mode: backwards;` |
| `.a-fill-both-l` | `animation-fill-mode: both;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.a-fill-none-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/animation-fill-mode.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/animation-fill-mode.css` — formatted
- `dist/animation-fill-mode.min.css` — minified

## License

MIT
