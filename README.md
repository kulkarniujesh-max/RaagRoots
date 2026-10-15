# RagRoots storefront prototype

A responsive, browser-only storefront prototype for handcrafted Indian musical instruments. The catalog, product options, cart, and demo checkout are sample content; no payment or personal details are collected.

## Open the prototype

From this folder, run:

```powershell
python -m http.server 8000
```

Then open <http://localhost:8000> in a browser. Use **Ctrl+C** in the terminal to stop the local preview.

The cart is saved in the current browser using local storage. Product photos load from their listed image sources; an illustrated fallback appears if a source is unavailable.

