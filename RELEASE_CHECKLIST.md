# Raceway Math Site Release Checklist

## Content alignment
- Confirm the App Store link points to the live production listing
- Confirm the site describes Raceway Math as free to download
- Confirm optional tip jar language matches the app and App Store copy
- Confirm support email and issue links are still correct
- Re-read the privacy policy after any app privacy change

## Validation
- GitHub Pages workflow passes on the release PR
- Local `bundle exec jekyll build` passes when Ruby/Bundler is available
- Screenshot and any future images render correctly on the live site

## Release follow-up
- Review the live GitHub Pages deployment after merge
- Check for broken links from the homepage and privacy policy
- Make sure site copy stays in sync with App Store release notes
