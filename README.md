# LJT-Homepage

Academic homepage for **Junteng Liu**, forked from [Academic Pages](https://github.com/academicpages/academicpages.github.io).

The existing About page contains academic background, research interests, research experience, all six publications, the scholarship, and contact information supplied in memory. The existing Publications page repeats the same publication records. All other template pages and example collections are excluded from the generated site.

No photograph, specific skills, additional profile links, paper URLs, or code repository URLs were supplied in memory, so none were invented. The dates and first-year PhD description are preserved as supplied.

## Build

```sh
bundle install
bundle exec jekyll build --strict_front_matter
```

The Jekyll build workflow validates that only the About and Publications HTML pages are generated and that all six publications appear on both pages.

## GitHub Pages

The project-site configuration uses `https://bench-induction-ai.github.io/LJT-Homepage/`. This is the configured URL, not a claim that deployment has succeeded.

The workflow builds and uploads the site, and deploys it only when GitHub Pages is already enabled. Automatic Pages enablement was blocked by GitHub's workflow-token permissions.

To publish, enable **Settings → Pages → Build and deployment → Source: GitHub Actions**, then run **Actions → Jekyll build → Run workflow**. Future pushes to `master` will also build and deploy when Pages is enabled.
