<div align="center">

# SEObolt

**Free, open-source SEO tools — built by the team behind [SEObolt](https://seobolt.io)**

[SEObolt](https://seobolt.io) · [SEObolt WP Plugin](https://royalplugins.com/seobolt/) · [Free SEO Tools](https://royalplugins.com/tools) · [Royal Plugins](https://royalplugins.com)

</div>

---

SEObolt is an SEO platform available as both a **WordPress plugin** and a **standalone SaaS dashboard**. The WordPress plugin handles on-page optimization, schema markup, sitemaps, and crawl control directly inside your site. The SaaS dashboard ([app.seobolt.io](https://seobolt.io)) connects to your WordPress plugin to provide advanced analytics, keyword research, rank tracking, and competitor analysis from one central interface.

This repo contains **free, standalone SEO tools** you can run locally or integrate into your own projects.

## 🛠 Free Tools

### [SERP Preview](tools/serp-preview/)
See exactly how your page appears in Google search results before publishing. Test titles, meta descriptions, and URLs against Google's current display rules.

- Preview desktop and mobile SERP layouts
- Character count validation for titles and descriptions
- Pixel-width truncation check (Google truncates by pixel, not character count)

### [Robots.txt Tester](tools/robots-txt-tester/)
Test your robots.txt crawl rules against any URL and user agent combination. Catch blocking issues before they cost you rankings.

- Parse and validate robots.txt syntax
- Test specific URLs against Allow/Disallow rules
- Check rules for Googlebot, Bingbot, GPTBot, ClaudeBot, and other user agents

### [Meta Tag Analyzer](tools/meta-tag-analyzer/)
Paste any HTML and get a full audit of its meta tags, Open Graph data, and Twitter Card markup. Find what's missing before your competitors do.

- Title, description, canonical, and robots meta tags
- Open Graph tags (og:title, og:description, og:image, etc.)
- Twitter Card validation
- SEO score with pass/warn/fail checklist

## ⚡ SEObolt — WordPress Plugin

These free tools are a taste of what [SEObolt](https://seobolt.io) does inside WordPress. The plugin runs directly on your site and handles everything from content optimization to technical SEO:

### Content Optimization
- **SEO Analysis** — 57-point scoring engine with real-time feedback as you write
- **Focus Keywords** — unlimited focus + secondary keywords per post/page
- **Content AI** — generate SEO titles, meta descriptions, and keyword suggestions (OpenAI & Anthropic)
- **Internal Link Suggestions** — AI-powered recommendations for internal linking
- **Readability Analysis** — content clarity scoring alongside SEO checks

### Schema Markup
- **50+ Schema Types** — Article, Product, Recipe, Event, FAQ, HowTo, LocalBusiness, Video, Course, and more
- **Visual Schema Builder** — build custom JSON-LD without writing code
- **Schema Templates** — pre-built templates library for common use cases
- **Schema Validator** — JSON-LD validation and error checking
- **WooCommerce Product Schema** — price, stock, review markup for product pages

### Technical SEO
- **XML Sitemaps** — post, page, image, video, and news sitemaps with auto-ping to Google/Bing
- **Redirect Manager** — 301, 302, 307, 308 redirects with exact match, prefix, and regex support
- **404 Monitor** — track broken URLs with referrer data and one-click redirect creation
- **Canonical URLs** — automatic generation with manual override per post
- **Robots.txt Editor** — visual editor with rule validation
- **LLMs.txt Editor** — control AI crawler access (ChatGPT, Claude, etc.)
- **Htaccess Editor** — direct .htaccess editing from WordPress admin
- **Breadcrumbs** — navigation breadcrumbs with BreadcrumbList schema
- **Instant Indexing** — Google Indexing API and Bing IndexNow support
- **Broken Links Checker** — cron-based internal link monitoring

### Analytics & Rank Tracking
- **Google Search Console** — one-click OAuth connection with keyword, page, click, impression, and CTR data
- **Google Analytics 4** — built-in GA4 dashboard
- **Keyword Position Tracking** — monitor ranking changes with historical charts
- **Position History** — track keyword movements over time

### Social Media
- **Open Graph Tags** — og:title, og:description, og:image per post
- **Twitter Cards** — card type, title, description, image
- **Social Preview** — visual preview of how posts appear on Facebook and Twitter

### Local SEO & WooCommerce
- **Local SEO** — multiple location support, opening hours, LocalBusiness schema, KML sitemaps
- **WooCommerce SEO** — product schema with rich snippets, price/stock markup, category optimization

### Import, Export & Migration
- **Import from Yoast, Rank Math, AIOSEO, SEOPress** — migrate all your SEO data
- **Export/Backup** — full settings export and restore
- **Bulk CSV Redirect Import** — migrate redirects from any source

### Page Builder Integrations
- Gutenberg, Elementor, Divi, Beaver Builder, WPBakery, Oxygen, Bricks, Avada, and Thrive Architect

### Email Reports & Automation
- **Weekly/Monthly SEO Reports** — automated email delivery with performance summaries
- **Email Deliverability Check** — warns if your host can't send emails reliably

### Admin Tools
- **Role Manager** — control SEO feature access by WordPress role
- **Post List Columns** — SEO score and focus keyword visible in post list
- **Quick Edit** — edit SEO fields without opening the full editor
- **Dashboard Widget** — SEO overview at a glance
- **Setup Wizard** — guided initial configuration

## 🖥 SEObolt — SaaS Dashboard

The [SEObolt SaaS dashboard](https://seobolt.io) connects directly to your WordPress plugin and gives you a centralized analytics platform:

- **SEO Analysis** — site-wide audits beyond individual posts
- **Keyword Research** — discover opportunities and track competition
- **Rank Tracking** — monitor keyword positions across Google
- **Backlink Monitoring** — track your link profile
- **Competitor Comparison** — analyze competitor SEO strategies
- **Content Optimizer** — data-driven content recommendations
- **PDF Reports** — exportable reports for clients or stakeholders
- **Multi-Property Support** — manage multiple sites from one dashboard

The dashboard requires an active SEObolt license (Business tier or higher). Your WordPress plugin syncs data automatically — no manual setup needed.

👉 [**Get SEObolt**](https://seobolt.io) · [**SEObolt WP Plugin**](https://royalplugins.com/seobolt/)

## 🔗 More Free SEO Tools

We maintain additional free tools at [royalplugins.com/tools](https://royalplugins.com/tools):

- [**Schema Validator**](https://royalplugins.com/tools) — Test your structured data markup
- [**SSL Checker**](https://royalplugins.com/tools) — Verify SSL certificate configuration
- [**Security Scanner**](https://royalplugins.com/tools) — Check WordPress sites for common vulnerabilities
- [**Hardening Checklist**](https://royalplugins.com/tools) — Step-by-step WordPress security guide

## 📝 From the Blog

- [I Audited 50 Popular WordPress Plugins. Here's What Scared Me.](https://royalplugins.substack.com/p/i-audited-50-popular-wordpress-plugins)
- [WordPress Security in 2026: The Complete Hardening Guide](https://royalplugins.medium.com/wordpress-security-in-2026-the-complete-hardening-guide-756d4579c7f8)

## License

Apache 2.0 — see [LICENSE](LICENSE) and [NOTICE](NOTICE) for details.

The source code is free to use, modify, and redistribute. However, **"SEObolt" and "Royal Plugins" are trademarks** and may not be used in derivative product names, marketing, or branding. See the [NOTICE](NOTICE) file for full trademark terms.

---

<div align="center">

**Built by [Royal Plugins](https://royalplugins.com) — lightweight, security-first WordPress plugins.**

[seobolt.io](https://seobolt.io)

</div>
