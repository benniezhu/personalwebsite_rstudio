To Edit the biography edit the following file:

/content/authors/admin/_index.md



The basic files that you want to modify to customize your website are the following:

* config/_default/config.yaml: general website information
* config/_default/params.yaml: website customization
* config/_default/menus.yaml: top bar / menu customization
* content/authors/admin/_index.md: personal information


To add a publication ; in Rstudio

blogdown::hugo_cmd(c('new', 'content/publication/<publication folder name>'))

then in this newly created folder edit the markdown document

# how to comit changes 
hugo in the thing and then cd to personalwebsite/public

git commit -am "blah blah commit message"
