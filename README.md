# Rock Tailwind Styles

Shared CSS styles for Favor Care's Rock RMS site, using Tailwind utility classes alongside Bootstrap 3.

## Install

Add to your `<head>`:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/favorcare/rock-tailwind-styles@main/index.css">
```

## Tailwind Scope

Wrap your Tailwind sections with `tw-scope` to neutralize Bootstrap's default overrides (link colors, heading styles, etc.):

```html
<div class="tw-scope tw:bg-fc-dark tw:py-6">
  <div class="tw-container">
    <!-- Tailwind utilities work without Bootstrap interference -->
  </div>
</div>
```

## Container

Use `tw-container` to match Bootstrap 3's responsive container widths (750 / 970 / 1170px):

```html
<div class="tw-container">
  <!-- Aligned with Bootstrap's .container -->
</div>
```
