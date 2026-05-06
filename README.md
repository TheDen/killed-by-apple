# Killed by Apple

A small static site documenting Apple products, services, and features that have been discontinued.

## Editing Content

Add, remove, or update entries in `products.json`. Each item uses this shape:

```json
{
  "name": "Example Product",
  "cat": "Hardware",
  "icon": "🖥️",
  "desc": "Short description.",
  "born": 2000,
  "died": 2005,
  "refs": [
    {
      "label": "Apple announcement",
      "url": "https://example.com"
    }
  ]
}
```

`refs` is optional. Use it for launch announcements, support notes, replacement announcements, or other source material for why the product ended.
