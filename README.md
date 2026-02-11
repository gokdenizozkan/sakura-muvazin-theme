# Muvazin.css

**Muvazin** (meaning *balanced* or *equivalent*) is a high-contrast, strictly accessible theme
for [sakura.css](https://github.com/oxalorg/sakura).

It is built on the **Okabe Ito** color palette, designed specifically to be distinct for all forms of color blindness (
Protanopia, Deuteranopia, and Tritanopia). Muvazin favors explicitness, minimizing cognitive load.

## The Design Philosophy

1. **The Canvas (Ink & Paper):** Text is strictly **Black** (`#000000`) on **White** (`#FFFFFF`). Readability is
   prioritized.
2. **The Lead (Teal):** Used for action and navigation. It guides the user forward.
3. **The Support (Gold):** Used for structure and decoration. It frames the content.
4. **The Focus (Vermilion):** Used for certain state changes (e.g. focus, active input).

## Installation

Sakura is a semantic CSS library. It requires no class names, as it targets standard HTML tags directly.

1. Download `muvazin.css`.
2. Link `sakura.css` first, followed by `muvazin.css` (the theme).

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" href="https://unpkg.com/sakura.css/css/sakura.css" type="text/css">
    <link rel="stylesheet" href="muvazin.css" type="text/css">
</head>
<body>
<h1>Hello, World</h1>
<p>This page is now accessibly styled.</p>
</body>
</html>

```

## The Palette

Muvazin exposes its logic via semantic CSS variables. You can override these if necessary, but they are tuned for
maximum WCAG AA compliance.

| Role          | Semantic Variable               | Color Name      | Hex       |
|---------------|---------------------------------|-----------------|-----------|
| **Action**    | `--theme-color-action-primary`  | Okabe Teal      | `#009E73` |
| **Structure** | `--theme-color-decoration-line` | Okabe Gold      | `#E69F00` |
| **Focus**     | `--theme-color-action-focus`    | Okabe Vermilion | `#D55E00` |
| **Reading**   | `--theme-color-text-reading`    | Black           | `#000000` |
| **Canvas**    | `--theme-color-canvas`          | White           | `#FFFFFF` |

## Browser Support

Muvazin relies on **CSS Variables**. It supports all modern browsers (Chrome, Firefox, Safari, Edge). It does not
support Internet Explorer.

## License

Unlicense. You are free to do anything with this theme without any conditions. Use, modify, and distribute this theme
freely. See further details on the [LICENSE](LICENSE) file.