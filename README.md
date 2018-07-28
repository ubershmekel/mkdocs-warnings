## Reproducing an issue with mkdocs

MkDocs promises to check internal links for validity but fails to mention which kind.

```
mkdocs-warnings>mkdocs build
INFO    -  Cleaning site directory
INFO    -  Building documentation to directory: mkdocs-warnings\site
WARNING -  The page "index.md" contained a hyperlink to "worksasdf.md" which is not listed in the "pages" configuration.
```

Notice only one warning even though there are multiple broken internal links in `index.md`

