# Responsive Rendering for Phone, Tablet, and Desktop

### jsDelivr Link

```html
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/gh/dev-bhatia/cdn@main/responsiveRender/responsiveRender.css"
/>
```

### Use (Singal Device Rendering)

```html
<!-- RENDER ON PHONES ONLY -->
<div class="phone">...</div>

<!-- RENDER ON TABLETS ONLY -->
<div class="tablet">...</div>

<!-- RENDER ON DESKTOPS ONLY -->
<div class="desktop">...</div>
```

### Use (Multiple Device Rendering)

```html
<!-- RENDER ON CERTAIN SCREENS -->
<!-- Specify screens types to render on -->

<!-- RENDER ON PHONES & TABLETS ONLY -->
<div class="phone tablet">...</div>

<!-- RENDER ON TABLETS & DESKTOPS ONLY -->
<div class="tablet desktop">...</div>

<!-- RENDER ON ALL SCREENS -->
<!-- Don't need to specify anything -->
<div class="">...</div>
```
