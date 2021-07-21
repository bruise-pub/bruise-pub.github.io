# compiling steps


- pandoc converts content and footer to headerless html

> pandoc content.md sitemap.md -f markdown -t html -o content.html

- that is then pasted into the  body section (much cleaner than web gen)

- sitemap (inc. version)

- index
- campfire
- locality
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