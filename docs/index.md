# Welcome to MkDocs

## Testing links warnings during build

[1 working link](works.md)

[2 working link](/works.md)

[3 working link, but it probably should not](/works/)

[4 working link, but it probably should not](/works)

[5 not working link, yes warning because ends with .md](/worksasdf.md)

[6 not working link, no warning](/worksasdf)

[7 not working link, no warning](/worksasdfasdf.qqq)

[8 not working link, no warning](worksasdfasdf)
