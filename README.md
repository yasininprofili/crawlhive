<p align="center"><img src="icon.png" width="96" alt="Crawlhive Chrome extension icon"></p>

# Crawlhive: SEO Audit and Site Crawler for Technical SEO in Chrome

Crawlhive is a free Chrome extension for technical SEO checks. It audits the page you have open and can crawl up to 40 pages of the same site, then reports what is wrong: pages that cannot be indexed, duplicate titles, orphan pages, heading and image problems, missing structured data and hreflang errors.

**[Install from the Chrome Web Store](https://chromewebstore.google.com/detail/hijjkfknggkoajofakeppnbhegdbfjpe?utm_source=github&utm_medium=readme&utm_campaign=crawlhive)** | **[Full guide and FAQ](https://www.addonschrome.com/extensions/crawlhive-seo-audit-site-crawler-technical-seo.html?utm_source=github&utm_medium=readme&utm_campaign=crawlhive)**

This repository is the public home for Crawlhive documentation, release notes and the issue tracker. The extension itself is distributed through the Chrome Web Store.

## What it checks

**On the current page**

- Title, meta description and headings
- Indexability: robots meta, canonical and status
- Images and alt text
- Structured data
- hreflang tags
- Core Web Vitals

**Across the site (crawl of up to 40 pages)**

- Pages that are not indexable
- Duplicate titles
- Orphan pages with no internal links pointing to them

## Export

Save the report as Markdown, JSON or CSV, for a ticket, a client report or your own notes.

## How to use it

1. Install Crawlhive from the [Chrome Web Store](https://chromewebstore.google.com/detail/hijjkfknggkoajofakeppnbhegdbfjpe?utm_source=github&utm_medium=readme&utm_campaign=crawlhive) and sign in with Google.
2. Open the page you want to check and run the page audit.
3. Start a crawl to check up to 40 pages of the site.
4. Export the findings.

The [full guide](https://www.addonschrome.com/extensions/crawlhive-seo-audit-site-crawler-technical-seo.html?utm_source=github&utm_medium=readme&utm_campaign=crawlhive) explains every check.

## A quick post-deploy routine

After a release, run the page audit on the home page and one template of each type, then a crawl. It catches the usual accidents: a leftover noindex, a broken canonical, missing titles.

## What it does not do

Crawlhive is an on-page and technical SEO tool. It does not track rankings and it does not analyse backlinks.

## Pricing

Crawlhive is free.

## Support and feedback

Found a bug or want a feature? [Open an issue](../../issues) in this repository. Please include your Chrome version and the steps that led to the problem.

## Disclaimer

Crawlhive is an independent tool built by Addons Chrome. It reports what it can see from the browser; server logs and search engine data are outside its scope.

---

Built and maintained by [Addons Chrome](https://www.addonschrome.com/?utm_source=github&utm_medium=readme&utm_campaign=crawlhive).
