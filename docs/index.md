# Welcome to MkDocs

For full documentation visit [mkdocs.org](http://mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs help` - Print this help message.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

## Testing links warnings during build

[1 working link](works.md)

[2 working link](/works.md)

[3 working link, but it probably should not](/works/)

[4 working link, but it probably should not](/works)

[5 not working link, yes warning because ends with .md](/worksasdf.md)

[6 not working link, no warning](/worksasdf)

[7 not working link, no warning](/worksasdfasdf.qqq)

[8 not working link, no warning](worksasdfasdf)
