# Local Electrician Kentucky

A single-page SEO landing page targeting the keyword **"professional electrician Kentucky"**.

## Contents

| File | Purpose |
|---|---|
| `index.html` | Main landing page — 1000+ word semantically structured article, custom design, service sections, FAQ, and images. |
| `robots.txt` | Tells search engine crawlers which pages they can index. |
| `sitemap.xml` | Lists page URLs for search engines to crawl. |
| `README.md` | This file. |

## Notes before publishing

1. **Replace placeholder URLs.** `robots.txt`, `sitemap.xml`, and the canonical tag in `index.html` currently point to a GitLab Pages-style URL (`https://crescentmoversllc.gitlab.io/local-electrician-kentucky/`). Update these to your real live domain once the site is deployed.
2. **Replace the phone number.** The `tel:` links use a placeholder number (`+1-800-555-1234`) — swap in your real business number.
3. **Images.** The images currently link to royalty-free Unsplash photos for demonstration. Swap in your own licensed/owned images before going live for best long-term SEO and branding results.
4. **The outbound link.** Per your request, the second paragraph of the article contains a "Click Here" anchor linking to `https://emergencyelectriciankentucky.com/`. This is the *only* place that link appears, as requested.

   ⚠️ One thing worth flagging: a generic "Click Here" anchor pointing to an unrelated external domain, placed on a page hosted under a differently-named business (movers LLC) is a pattern search engines (Google in particular) flag as manipulative link-building. If both sites are genuinely affiliated/related businesses, consider using descriptive anchor text (e.g. "24/7 emergency electrician in Kentucky") instead of "Click Here" — it reads more naturally to both users and search engines and carries lower risk of a manual action or algorithmic devaluation.

## Deploying to GitLab Pages

Add a `.gitlab-ci.yml` like this to publish automatically:

```yaml
pages:
  stage: deploy
  script:
    - mkdir public
    - cp index.html robots.txt sitemap.xml public/
  artifacts:
    paths:
      - public
  rules:
    - if: '$CI_COMMIT_BRANCH == "main"'
```
