RMarkdown reports
================

*work in progress*

How to create static or dynamic reports for your home assignments, using
R markdown.

R Markdown provides an authoring framework for data science. You can use
a single R Markdown file to both.

Generate high quality reports that can be shared with an audience. R
Markdown documents are fully reproducible and support dozens of static
and dynamic output formats.

# R markdown

First install pandoc (<https://pandoc.org/installing.html>)

The library `rmarkdown` already comes with RStudio. If you neet to
install it:

``` r
install.packages("rmarkdown")
```

## Usefull resources

-   [**A great quick
    tutorial**](https://towardsdatascience.com/getting-started-in-r-markdown-2d3de636bde3)
-   [R Markdown
    Cheatsheet](https://github.com/rstudio/cheatsheets/raw/master/rmarkdown-2.0.pdf)
-   [R Markdown: The Definitive
    Guide](https://bookdown.org/yihui/rmarkdown/)

### Make your outputs live

To make your outputs online at your IST server.

#### VPN check

First, you have to make sure that your computer is trusted to be
connected to IST servers.  
Please [follow the
insctructions](https://si.tecnico.ulisboa.pt/en/servicos/redes-e-conetividade/vpn/),
by choosing your Operating System.

You only need to do this once per computer.

#### Using SFTP

SFTP is a Secure FTP connection.  
Donwload FileZilla at:
<https://filezilla-project.org/download.php?type=client>

-   CTRL + S (site manager)
-   new site (name “fenix”)
-   SFTP
-   server: sigma.ist.utl.pt
-   port: *leave blank*
-   user: ist1XXXXX
-   Connect, save password, always trust this key

Upload your outputs under **web** / tdm
