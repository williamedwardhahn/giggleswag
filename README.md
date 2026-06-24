# 😜 GiggleSwag

> Wearable joy. Seriously fun swag.

The official landing site for **GiggleSwag** — a new brand making apparel and
accessories with way too much personality. Tees, totes, mugs & stickers.

🔗 **Live site:** https://williamedwardhahn.github.io/giggleswag/

## Stack

A single, dependency-free static site — built to drop straight onto GitHub Pages.

- `index.html` — markup & a little vanilla JS (sticker parallax + signup placeholder)
- `styles.css` — all styling (sticker-pop aesthetic, Unbounded + Hanken Grotesk)

No build step. Open `index.html` locally or serve the folder:

```bash
python3 -m http.server 8000   # then visit http://localhost:8000
```

## Roadmap

- [x] Brand landing page
- [ ] **Printify storefront** — wire up the made-to-order product catalog
- [ ] Real email capture for the giggle list
- [ ] Drop 001 launch 🎉

## Adding Printify (next step)

The product cards in the **Shop** section and the footer note are placeholders.
When the Printify store is ready we'll either embed the Printify Pop-Up store /
buy buttons or swap the cards for links to the storefront. The markup is already
structured (`.card` blocks under `#shop`) to make that swap easy.
