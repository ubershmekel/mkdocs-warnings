## Reproducing an issue with mkdocs

MkDocs promises to check internal links for validity but fails to mention which kind.

In the following output notice only one warning even though there are multiple broken internal links in `index.md`

```
mkdocs-warnings>mkdocs build
INFO    -  Cleaning site directory
INFO    -  Building documentation to directory: mkdocs-warnings\site
WARNING -  The page "index.md" contained a hyperlink to "worksasdf.md" which is not listed in the "pages" configuration.
```

* [See site output](https://ubershmekel.github.io/mkdocs-warnings/site/)
* [See source of links](https://raw.githubusercontent.com/ubershmekel/mkdocs-warnings/gh-pages/docs/index.md)
