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
- Family categories like `"iPhone"`, `"iPad"`, `"iPod"`, `"Apple Watch"`, and `"TV"` should only be added when the item is clearly part of that product ecosystem.
- Cloud-backed capabilities can span `"Service"` and `"Feature"`.
- Standalone apps that were really fronts for online systems can span `"Software"` and `"Service"`.
- Physical interfaces and built-in hardware capabilities can span `"Feature"` and `"Hardware"`.

`refs` is optional. Use it for launch announcements, support notes, replacement announcements, or other source material for why the product ended.

## Contributing

Contributions should be submitted as GitHub pull requests.

1. Fork the repository on GitHub.
2. Create a branch for your change.
3. Update `products.json` and any related docs.
4. Open a pull request against [`TheDen/killed-by-apple`](https://github.com/TheDen/killed-by-apple).

When adding or changing entries, prefer official Apple references where possible, and leave `refs` empty rather than guessing.
