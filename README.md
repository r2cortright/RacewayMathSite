# RacewayMathSite

Raceway Math site for communicating with users and supporting release/storefront updates.

## Local preview

If Ruby and Bundler are available:

```bash
bundle install
bundle exec jekyll build
bundle exec jekyll serve
```

## Release notes

See `RELEASE_CHECKLIST.md` for the lightweight site release checklist.

## Hardening notes

- Pull requests now build the Jekyll site before merge.
- The Pages workflow also verifies that core support links remain present.
- Keep site pricing/support language aligned with the app repo and App Store drafts.
