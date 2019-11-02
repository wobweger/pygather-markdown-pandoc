# pygather-markdown-pandoc
python gather for markdown to simple pandoc

markdown is a great way to document your thoughts and code. 
If small md fragments are supposed to be combined into a single document using
pandoc, certain problems may show up: 

+ keeping right order
+ images in subfolders 
+ references 
+ links to files in md are suddenly dead in doc

## background

FIXME

## goal

a python script shall read one md file, analyse it and walk through each md file link. 
all found md files shall be compacted into a new single one.  
all images links shall be coopied into a single media folder.  
suggested tree structure shall be flattend out.  
links to other file types, determind by extension, shall be modified to repo links.

## requirements

+ python 3 implementation
+ CLI, command line interface
+ configuration xml
+ project language English
+ coding language English, sort of

## contribute

every contribution is very much appreciated.  
join, discuss, use and share 
