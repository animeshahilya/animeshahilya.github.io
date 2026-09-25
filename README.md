# animeshahilya.github.io

Landing pages for my Android apps: https://animeshahilya.github.io/

## Add a new app

1. Copy `_apps/tarang.md` to `_apps/<short-name>.md`. The file name becomes the address, for example `/<short-name>/`.
2. Edit the front matter:
   - `app_name`, `tagline` (the one line shown on the home page), `summary`
   - `version`, `android` (the minimum Android version), and `license` (optional)
   - `releases_repo`: the public repo whose GitHub Releases hold the APK
   - `source_url` and `feedback_url` (both optional)
   - `order`: the app's position on the home page
   - `feature_groups`: headed groups of features
3. Anything in the body, written in Markdown, appears after the install steps.
4. Push. The site rebuilds in about a minute.

When you publish a new release, update `version` in that app's file.
