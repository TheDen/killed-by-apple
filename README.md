# Killed by Apple

A small static site documenting Apple products, services, and features that have been discontinued.

## Editing Content

Add, remove, or update entries in `products.json`. Each item uses this shape:

```json
{
  "name": "Example Product",
  "cats": ["Hardware"],
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

Use `cats` for one or more categories. Examples:

- Mac hardware should usually include both `"Mac"` and `"Hardware"`.
- Cloud-backed capabilities can span `"Service"` and `"Feature"`.
- Standalone apps that were really fronts for online systems can span `"Software"` and `"Service"`.
- Physical interfaces and built-in hardware capabilities can span `"Feature"` and `"Hardware"`.

`refs` is optional. Use it for launch announcements, support notes, replacement announcements, or other source material for why the product ended.
