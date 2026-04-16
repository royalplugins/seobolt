<div align="center">

# SEObolt

**SEO rank tracking + AI search visibility, in one platform.**

[SEObolt SaaS](https://seobolt.io) · [Try the dashboard](https://app.seobolt.io/login) · [SEObolt for WordPress](https://royalplugins.com/seobolt/) · [Pricing](https://seobolt.io/pricing) · [Changelog](https://seobolt.io/changelog)

</div>

---

## What is SEObolt?

SEObolt is a rank tracking platform that combines **traditional SEO data** with **AI search visibility**. It pulls rankings and traffic from **Google Search Console** and **Google Analytics 4**, pulls citations from **ChatGPT, Claude, Perplexity, Gemini, and DeepSeek**, and layers four proprietary scoring engines on top so you know what to fix and which changes moved the needle.

- **SEO Score** — 57-test content and technical audit at the URL level
- **Local SEO Score** — 10-point local-business readiness check
- **Schema Score** — 11-factor grade of your structured-data quality
- **GEO Score** — 37-factor Generative Engine Optimization score (peer-reviewed research from Princeton, Georgia Tech, UC Berkeley)

SEObolt ships as three connected surfaces:

1. **[SEObolt SaaS dashboard](https://seobolt.io)** — the main product. Rank tracking, LLM Rankings, GEO Score, GSC/GA4 analytics, competitor comparison, bulk editing, reporting.
2. **[SEObolt for WordPress](https://royalplugins.com/seobolt/)** — a full WP SEO plugin. On-page analysis, schema, sitemaps, redirects, llms.txt editor, and a frontend SEO top bar.
3. **SEObolt Chrome extension** — free, local page auditor. 57-test on-page analysis with zero account required.

This repository contains **free, open-source SEO tools** you can run locally or integrate into your own projects.

---

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

---

## 🖥 SEObolt SaaS Dashboard

The [SEObolt SaaS dashboard](https://seobolt.io) is a centralized platform for SEO teams that want rank tracking, AI search visibility, and on-page optimization in one place. Connects to Google Search Console, Google Analytics 4, and the major LLMs.

### 🤖 AI Search Visibility
- **LLM Rankings** — track how ChatGPT, Claude, Perplexity, Gemini, and DeepSeek cite your brand
- **Prompt-level citations** — see the exact queries that mention (or don't mention) you
- **Competitor AI tracking** — compare your share of AI citations against rivals
- **GEO Score** — 37-factor AI citation optimization score across 6 categories (Content Structure, Evidence & Citations, Technical Accessibility, Authority & E-E-A-T, Content Freshness, Writing Quality)
- **llms.txt generator** — build an llms.txt file from your GSC-indexed pages; copy, regenerate, or download

### 📈 Rank Tracking
- **Daily rank checks** — automated cron with rate limiting per tier
- **30-day sparklines** — trend charts in the keyword list and per-keyword detail page
- **Position history** — full historical chart with period comparisons
- **Top Movers** — winners and losers block on the dashboard
- **CSV export** — full data dump for reporting
- **SerpAPI BYOK** — bring your own SerpAPI key for direct SERP pulls (GSC fallback when no key)

### 🔍 Keyword Research
- **Opportunity finder** — surface keywords with high impressions but low CTR
- **Keyword Lists** — group, tag, and track keyword sets
- **Competitor keyword overlap** — keywords you're both ranking for, in one unified table

### 📊 Analytics
- **Google Search Console** — queries, pages, clicks, impressions, CTR, positions
- **Google Analytics 4** — live dashboard with Traffic Sources, Top Pages, Top Countries
- **Multi-property** — manage Growth, Scale, and Agency-tier properties from one workspace
- **Content decay alerts** — ping when high-traffic pages start losing impressions

### 🧰 Content & On-Page Tools
- **SEO Analysis** — 57-test scoring engine at URL level with category breakdown
- **Content Optimizer** — AI-powered suggestions with **BYOK** (use your own OpenAI, Anthropic, Google, or DeepSeek API key — no per-call platform fees)
- **Bulk Editor** — mass-edit meta titles, descriptions, and canonicals across your site
- **Schema Generator** — 63 schema templates with a visual builder
- **Auto-Linking** — keyword-to-URL rules with bulk apply to existing content
- **SEO Templates** — global title / description / OG patterns with variable substitution

### 🛠 Advanced SEO
- **Robots.txt viewer** with Allow/Disallow rule testing
- **llms.txt generator** built from GSC data
- **Internal linking overview** — orphaned pages, low-link pages, AI-suggested links
- **Social Meta editor** — per-URL Open Graph and Twitter Card overrides with live preview

### 👥 Team Access
- **Seat-based plans** — Growth 1 seat, Scale 3 seats, Agency 10 seats
- **Roles** — Owner, Admin, Editor, Viewer
- **Email invitations** with organization-scoped permissions

### 📑 Reporting
- **White-label PDF reports** — agency-ready exports with custom branding
- **Automated email reports** — weekly or monthly delivery
- **24-month data retention** on the Agency tier

### 🔌 WordPress Integration
- **Plugin sync** — if you run SEObolt for WordPress, the dashboard auto-connects and pulls analyzed page data
- **Push changes** — edit meta titles, descriptions, canonicals, schema in the dashboard and push to any connected WordPress site
- **No plugin required** — the dashboard also works standalone on any site with GSC connected

Plans start at **$29/mo**. AI visibility tracking is included in every tier.

👉 [**Get SEObolt**](https://seobolt.io) · [**Log in**](https://app.seobolt.io/login) · [**Compare plans**](https://seobolt.io/pricing)

---

## ⚡ SEObolt for WordPress

A full WordPress SEO plugin that runs directly on your site. Available in the WordPress admin — no external services required for the core feature set.

### Content Optimization
- **SEO Analysis** — 57-point scoring engine with real-time feedback as you write
- **Focus Keywords** — unlimited focus + secondary keywords per post/page
- **Content AI** — generate SEO titles, meta descriptions, and keyword suggestions (OpenAI & Anthropic)
- **Internal Link Suggestions** — AI-powered recommendations for internal linking
- **Readability Analysis** — content clarity scoring alongside SEO checks

### Schema Markup
- **63 Schema Types** — Article, Product, Recipe, Event, FAQ, HowTo, LocalBusiness, Video, Course, and more
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
- **LLMs.txt Editor** — auto-serves `/llms.txt` dynamically; editable, scored inside GEO Score
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
- **Frontend SEO Top Bar** — live SEO, Schema, and GEO score donuts on every page you own

---

## 🔗 More Free SEO Tools

We maintain additional free tools at [royalplugins.com/tools](https://royalplugins.com/tools):

- [**Schema Validator**](https://royalplugins.com/tools/schema-validator/) — Test your structured data markup
- [**SSL Checker**](https://royalplugins.com/tools/ssl-checker/) — Verify SSL certificate configuration
- [**Site Scanner**](https://royalplugins.com/tools/wordpress-security-scanner/) — Check WordPress sites for common vulnerabilities
- [**Plugin Scanner**](https://royalplugins.com/tools/wordpress-plugin-security-scanner/) — Audit individual WordPress plugins
- [**Meta Tag Checker**](https://royalplugins.com/tools/meta-tag-checker/) — Live fetch and grade any URL's meta tags
- [**HTTP Headers Checker**](https://royalplugins.com/tools/http-headers-checker/) — Inspect server response headers

## 📝 Learn SEO

- [**llms.txt: Control How AI Crawlers Use Your Content**](https://royalplugins.com/blog/llms-txt-ai-crawler-control/)
- [**Perfect SEO Score in WordPress: Page-by-Page Guide**](https://royalplugins.com/blog/wordpress-perfect-seo-score/)
- [**Keyword Rank Tracking in WordPress**](https://royalplugins.com/blog/wordpress-keyword-rank-tracking/)
- [**WooCommerce SEO: The Complete Optimization Guide**](https://royalplugins.com/blog/woocommerce-seo-complete-guide/)
- [**Full blog → royalplugins.com/blog**](https://royalplugins.com/blog/)

## License

Apache 2.0 — see [LICENSE](LICENSE) and [NOTICE](NOTICE) for details.

The source code is free to use, modify, and redistribute. However, **"SEObolt" and "Royal Plugins" are trademarks** and may not be used in derivative product names, marketing, or branding. See the [NOTICE](NOTICE) file for full trademark terms.

---

<div align="center">

**Built by [Royal Plugins](https://royalplugins.com)**

[seobolt.io](https://seobolt.io) · [app.seobolt.io](https://app.seobolt.io) · [royalplugins.com/seobolt](https://royalplugins.com/seobolt/)

</div>
