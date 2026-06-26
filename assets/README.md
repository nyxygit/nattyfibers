# Assets Directory

Place logo and image files here.

## Expected files

| File | Purpose |
|------|---------|
| `logo.png` | Site logo, displayed in the navigation header |
| `favicon.ico` | Browser tab icon |

## Logo guidelines

- Format: PNG with transparency
- Dimensions: 32×32px minimum, 200×40px recommended for header
- Style: Minimal, line-art or solid icon that works on dark (`#3E4A3E`) background

## Usage

Once `logo.png` is placed here, update the `.nav-logo` span in each HTML file:

```html
<!-- Replace the emoji span with: -->
<img src="../assets/logo.png" alt="NattyFibers" height="32">
```
