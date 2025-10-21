# dynamics365-translation

Auto-translation script for Dynamics 365 forms supporting EN-US, DE (German), and ZH (Chinese) based on URL patterns.

## Usage

Add these script tags to your HTML (in this exact order):

```html
<script src="https://cdn.jsdelivr.net/gh/mylokaye/dynamics365-translation@81d5290c4f37ecfa55db7656ba34c66633119fa0/translations.js"></script>
<script src="https://cdn.jsdelivr.net/gh/mylokaye/dynamics365-translation@81d5290c4f37ecfa55db7656ba34c66633119fa0/translate.js"></script>
```

**Important:** Always use the jsDelivr CDN URLs (`cdn.jsdelivr.net`) as shown above. Do NOT use `raw.githubusercontent.com` URLs, as they serve files with incorrect MIME types and will be blocked by modern browsers.
