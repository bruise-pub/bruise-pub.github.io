# compiling steps


- pandoc converts content and footer to headerless html

> pandoc content.md sitemap.md -f markdown -t html -o content.html

- that is then pasted into the  body section (much cleaner than web gen)

- sitemap (inc. version)

- index
- campfire
- locality
- poems
- reading
- resources
- tooc







-- issues (including YAML metadata to include title, css and enclose in body tags)


> --css style.css -s -o

links to stylesheet and standalone

example YAML metadata:

> ---
> title: "bruise"
> author: "mateus domingos"
> date: "2021"
> ---


# compiling epubs

i.e.

pandoc -o a-moire.epub title.txt \        
00-title.md \
01-section-1.md \
02-section-2.md \
03-section-3.md \
04-section-4.md \
05-publishers-note.md


