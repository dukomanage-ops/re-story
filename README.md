# re-story

Image and report hosting for the daily real estate news Instagram Stories on **@sandor_realtor**.

Every file pushed here gets a public link that Instagram scheduling tools can pull from.

## Folder layout

```
stories/
  2026-10-22/
    01.png        ← first story slide
    02.png
    ...
reports/
  2026-10-22.pdf  ← daily report sent to people who comment "report"
brand/
  ...             ← logos and reusable brand assets
```

- **stories/** — one folder per weekday, named by date (`YYYY-MM-DD`), slides numbered in posting order.
- **reports/** — one file per day, named by date.
- **brand/** — assets that don't change day to day.

## Public link format

Any file here can be opened publicly at:

```
https://raw.githubusercontent.com/dukomanage-ops/re-story/main/<path to file>
```

Example — slide 1 for October 22, 2026:

```
https://raw.githubusercontent.com/dukomanage-ops/re-story/main/stories/2026-10-22/01.png
```

## Note

This repo is **public**, so anyone with a link can see the files. Only put content here that's meant for Instagram — no client details or private documents.
