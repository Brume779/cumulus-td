# Cumulus Documentation Site

This repository is the public documentation source for Cumulus.

The docs.page site is generated from:

```text
docs.json
docs/
```

The published site is available through docs.page:

```text
https://docs.page/<owner>/<repo>
```

## Validate

From this folder, run:

```sh
npx --yes "@docs.page/cli" check .
```

The checker scans for broken relative links and missing local assets.
