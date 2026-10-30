# Trading Book

A trading-book catalogue and reading-guide website with a focus on quantitative finance and systematic trading.

**Live website:** https://quant-library.netlify.app/

## What's inside

- Static homepage with searchable book catalogue and Telegram inquiries.
- Individual book pages and topic guides under `books/` and `guides/`.
- `assets/`: site styles and scripts; `optimized/`: optimized book images.
- `sitemap.xml` and `robots.txt`: search engine discovery.
- `_headers`: Netlify security and caching headers.

## Local preview

From this directory, run `python -m http.server 8000` and open `http://localhost:8000/`. Netlify-specific headers apply only when served through Netlify (or an equivalent configured server).

## Deployment

The live project is currently deployed manually with Netlify Drop. Upload the website files with `index.html` at the root. A GitHub commit does not automatically deploy unless a Git integration is configured in Netlify.

The catalogue uses manual inquiry and delivery; it is not an automated payment or download system. Book availability, edition, price, distribution rights and image rights should be verified by the site owner.

No license to reuse third-party book covers or other content is granted by this repository.
