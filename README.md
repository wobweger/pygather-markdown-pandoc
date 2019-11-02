# pygather-markdown-pandoc

python gather for markdown to simple pandoc

[markdown][mdSyntax] is a great way to document your thoughts and code. 
If small md fragments are supposed to be combined into a single document using
[pandoc](https://pandoc.org/index.html), certain problems may show up:

+ keeping right order
+ images in sub folders
+ references
+ links to files in md are suddenly dead in doc

## background

FIXME

### markdown

markdown or simple md is available in a lot of state-of-the-art platform, a few format instruction allow you to structure 
information into readable look, with any overhead.
it's text rendered into html.

benefits:

+ easy to learn
+ easy to remember
+ lightweight
+ safe, no macros or anything that might invite an attack

some manual found online

+ [cheat](d_man/markdown-cheatsheet-online.pdf)
+ [guide](d_man/markdown-guide.pdf)


### pandoc

[pandoc](https://pandoc.org/index.html) is a flexible document converter. 
see [manual](https://pandoc.org/MANUAL.html)  
It can read and write:

+ markdown
+ html
+ odt
+ docx
+ tex
+ pdf
+ epub
+ and more

[example](d_howto/pandoc_tut.md)

more on github
+ [src][pandoc_github]
+ [wiki][pandoc_wiki]
+ [tricks][pandoc_tricks]

## goal

a python script shall read one md file, analyse it and walk through each md file link. 
all found md files shall be compacted into a new single one.  
all images links shall be copied into a single media folder.  
suggested tree structure shall be flattened out.  
links to other file types, determined by extension, shall be modified to repo links.

## requirements

+ python 3 implementation
+ CLI, command line interface
+ configuration xml
+ project language English
+ coding language English, sort of

## contribute

every contribution is very much appreciated.  
join, discuss, use and share 


[mdSyntax]: https://sourceforge.net/p/scintilla/wiki/markdown_syntax/
[pandoc_github]: https://github.com/jgm/pandoc
[pandoc_wiki]: https://github.com/jgm/pandoc/wiki
[pandoc_tricks]: https://github.com/jgm/pandoc/wiki/Pandoc-Tricks
