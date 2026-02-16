# css-transform-style

Functional CSS for transform-style

## Filesize

| File | Size |
|------|------|
| `dist/transform-style.css` | 677 bytes |
| `dist/transform-style.min.css` | 501 bytes (158 Gzipped) |

## Install

```sh
npm install css-transform-style
```

## Usage

### Import

```css
@import "css-transform-style";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-transform-style/dist/transform-style.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-transform-style/dist/transform-style.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.ts-p3d` | `transform-style: preserve-3d;` |
| `.ts-flat` | `transform-style: flat;` |
| `.ts-i` | `transform-style: inherit;` |
| `.ts-p3d-s` | `transform-style: preserve-3d;` |
| `.ts-flat-s` | `transform-style: flat;` |
| `.ts-i-s` | `transform-style: inherit;` |
| `.ts-p3d-m` | `transform-style: preserve-3d;` |
| `.ts-flat-m` | `transform-style: flat;` |
| `.ts-i-m` | `transform-style: inherit;` |
| `.ts-p3d-l` | `transform-style: preserve-3d;` |
| `.ts-flat-l` | `transform-style: flat;` |
| `.ts-i-l` | `transform-style: inherit;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.ts-p3d-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/transform-style.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/transform-style.css` — formatted
- `dist/transform-style.min.css` — minified

## License

MIT
