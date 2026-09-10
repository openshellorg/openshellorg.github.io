# 2026-09-10 — Host-root Pages publisher

Established `openshellorg/openshellorg.github.io` as the host-root GitHub Pages publisher so crawlers can discover project sitemaps under `openshellorg.github.io`.

Published files:

* `index.html` — brief pointer to [opensh.org](https://opensh.org/) and [docs.opensh.org](https://docs.opensh.org/)
* `robots.txt` — `Allow: /` plus `Sitemap:` lines for the root sitemap index and ProHelp
* `sitemap.xml` — sitemap index listing `https://openshellorg.github.io/prohelp/sitemap.xml`

Custom-domain docs (`docs.opensh.org`) stay outside this host-root policy.
