# radio-slipstream

[![Netlify Status](https://api.netlify.com/api/v1/badges/042e0d1a-e887-4c41-9615-f299303943eb/deploy-status)](https://app.netlify.com/sites/happy-hodgkin-93403a/deploys)

homepage for my old campus radio show.

Based on the [Eleventy starter blog template](https://github.com/11ty/eleventy-base-blog), converted from an ages old wordpress site (with like, `<font>` tags n shit). Relying on netlify static site + large file storage/mixcloud to remove all hosting costs for a 15GB archive of audio files 😎.


## commands

```
npx eleventy
```

Or build and host locally for local development
```
npx eleventy --serve
```

Or build automatically when a template changes:
```
npx eleventy --watch
```

Or in debug mode:
```
DEBUG=* npx eleventy
```
