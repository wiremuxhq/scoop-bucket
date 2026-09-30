# Scoop bucket

```bash
scoop bucket add wiremux https://github.com/wiremuxhq/scoop-bucket
scoop install wiremux
```

`scoop search` does not look in this bucket until it is added.

The manifest here is what `scoop install` uses. The Wiremux release
workflow updates it when `HOMEBREW_TAP_TOKEN` can push this repo.
`checkver` is not how new versions are published.
