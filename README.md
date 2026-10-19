# 小さな冷凍庫のごはんノート

A three-page Japanese sample website for the BKU affiliate-learning project. It helps people living alone check freezer space and compare frozen-meal delivery costs before ordering.

## Website

GitHub Pages address (available after Pages is enabled):
https://hsushunlailaiphyo-glitch.github.io/affiliation-project/

## Files

- `index.html` — homepage
- `freezer.html` — freezer-space checklist
- `cost.html` — five things to check when comparing costs
- `style.css` — shared responsive styles
- `.nojekyll` — publish the files without Jekyll processing

The original cream-and-green design and Japanese text are preserved. All links are relative, so they work under the repository's GitHub Pages path. No build step or installation is required.

## Publishing

In repository **Settings → Pages**, choose **Deploy from a branch**, select **main** and **/(root)**, then save. Changes to these files on main will be published automatically.

## Current scope

This is a prototype. Affiliate advertising placeholders are inactive; there are no purchase links, forms, accounts, payments, or analytics. The existing `noindex,nofollow` setting is preserved, so public access does not enable Google indexing. GA4 and Search Console remain unconfigured. Comments in each page's head mark future integration points.

