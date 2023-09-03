Exploring possible rewrite of [cozy](https://ayco.io/gh/cozy) to use HTMX with Astro

1. `index.astro` contains a form that submits url to an astro page
2. `article.astro` receives GET param containing url
3. `article.astro` fetch and extract article from url
4. `article.astro` renders article content and sends response to `index.astro`
5. `index.astro` swaps outlet div DOM with received response
