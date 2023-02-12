# astro-dynamic-import-package-repro

## Setup

```bash
pnpm i
```

## Run

```bash
cd site
pnpm dev
```

## Description

http://localhost:3000/static-import works fine.

http://localhost:3000/dynamic-import won't work because dynamic import of `page-container` fails.
