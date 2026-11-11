# Small-Business Website Health Checklist

A free, practical checklist for owners and developers who want to spot website problems before paying for a redesign. No signup, paid tools, or analytics access required for the first pass.

**Try the free online preview:** [Website Revenue Leak Audit](https://website-revenue-leak-audit.vercel.app/)
**Read the detailed walkthrough:** [Website health checklist](https://website-revenue-leak-audit.vercel.app/website-health-checklist.html)
**Need help implementing fixes?** [Scoped website fixes and API integrations](https://website-revenue-leak-audit.vercel.app/web-fix-services.html)

The online preview examines source-level signals on **one publicly accessible HTML page**. It is not a full-site crawl, browser performance benchmark, legal compliance certification, guarantee of higher rankings, or guarantee of additional sales. You can do the checks below manually.

## Ten checks worth doing

### 1. Confirm customers can use the main action
On both phone and desktop, actually submit the public contact, appointment, or checkout form using authorized test information. Check the confirmation message, notification, and saved entry. A design can look complete while its form never delivers.

### 2. Read the title and search snippet
Every important page should have a descriptive HTML `<title>` and a useful meta description. These describe the page rather than stuffing keywords. Google may rewrite search snippets, so this is a controllable starting point, not an outcome guarantee.

### 3. Check the mobile experience
Use a real phone: read text without zooming, navigate menus, tap buttons, fill inputs, and check horizontal scrolling. A viewport meta tag is necessary for responsive layout but doesn't prove the site works on phones.

### 4. Verify search indexing, not just a sitemap
Owners can use [Google Search Console](https://search.google.com/search-console/about) to see crawl and indexing reports and inspect priority pages. Make sure a public page isn't unintentionally blocked by `robots.txt`, a `noindex` directive, or a broken canonical. A sitemap is a discovery hint, not an indexing guarantee.

### 5. Follow internal links and redirects
Click the main navigation and important conversion links. Remove broken paths and confusing redirect chains. Ensure users land on the actual content instead of unexpected 404 or login screens.

### 6. Use meaningful headings
Give each page a clear topic and organize subsections with headings in logical order. Headings help people scan content and support accessibility; they are not a substitute for useful information.

### 7. Inspect images
Decorative images can use empty alternative text; meaningful images need suitable descriptions. Large hero images can hurt loading performance, so resize and use modern formats when appropriate. Test appearance on small and slow devices.

### 8. Measure actual performance
[PageSpeed Insights](https://pagespeed.web.dev/) and real-user metrics can help investigate loading and responsiveness. Don't confuse a static HTML check, a lab result, and real visitor Core Web Vitals. Re-test representative pages after each major change.

### 9. Review HTTPS, caching, and security headers
Confirm sensitive pages use HTTPS. Check cache rules so private content isn't stored publicly and static assets can be cached appropriately. Security headers can improve defense in depth but require context-specific configuration, not blanket copy/paste.

### 10. Make it easy to trust and contact you
Check that a real person can find the service description, contact channel, service area when relevant, terms, privacy information, and refund expectations. Claims, testimonials, and ratings should be authentic and verifiable.

## Prioritize findings instead of chasing scores

Copy [the audit worksheet](AUDIT_WORKSHEET.md), then record: exact URL, observed behavior, evidence, business impact, proposed fix, estimated effort, and a repeatable retest. Fix failures that prevent inquiries or purchases first. After that, prioritize indexing mistakes, usability barriers, and measured performance bottlenecks.

For a fuller reference, use the official [Google SEO Starter Guide](https://developers.google.com/search/docs/fundamentals/seo-starter-guide) and [W3C WAI guidance](https://www.w3.org/WAI/). Do not assume passing this checklist means your site conforms to WCAG or any law.

---

Maintained as a public educational resource related to an independent service by Reznik LLC. The links above lead to our own tool and service pages; using them is optional. Prices, scope, and availability are explained on the respective site. This repository contains no customer data, paid audits, accounts, or API keys.
