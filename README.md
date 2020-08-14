# Cropper compress

Comprime y recorta una imagen.

⚠️ En desarrollo! ⚠️ \
⚠️ In development! ⚠️

## Dependencias

[cropperjs](https://fengyuanchen.github.io/cropperjs/).

```html
<script src="https://unpkg.com/cropperjs@1.5.7/dist/cropper.min.js"></script>
<link
    rel="stylesheet"
    href="https://unpkg.com/cropperjs@1.5.7/dist/cropper.min.css"
/>
```

## Options

#### **compression**

Si va a comprimir la imagen o no.

-   Type: `Boolean`
-   Default: `true`
-   Example: `{ aspectRatio: false }` (No comprimirá la imagen)

#### **clippingType**

Como se mostrará el area de recorte.

-   Type: `String`
-   Default: `square`
-   Example: `{ clippingType: "circle }"`
-   Possible values: `"square", "circle" or "free"`

_Note: `circle` No recorta de forma circular, cuando este recortado se debería mostrar la iamgen circular con css._

⚠️ En desarrollo! ⚠️
⚠️ In development! ⚠️

---

Copyright © 2020 Dalthon.
Released under the MIT License.
