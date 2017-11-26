## WIP / Notes:

CSS is compiled; there's no SASS source.

- how to make pages work?
- different social things?
- disqus
- google analytics
- github component?

Uses 'tags' for what were 'categories' (in Hexo, categories are hierarchical: so a page with '[cooking, french]' will be understood as belonging to
category cooking, subcategory french cooking).

Social stuff
- supports twitter sharing only, at present

Sidebars
- you can customise the sidebar
- entries to the yaml are displayed in order
- recent: boolean
- featured: boolean, uses tag 'featured'. List is NOT truncated.
- github: string, if set, fetches repos. Can set 'false' or exclude to disable.

What works?
- blockquotes
- code blocks
- images (left / right / center)
- gists
- headings
- pullquotes (left, right [= default])
- jsfiddle embeds
- youtube videos

Still to do
- disqus
- post pagination
- archive pages
- atom.xml
- non-post pages?