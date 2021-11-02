# VWA-template
A LaTeX template to be used in Austrian High School final projects.

# Requirements
* You will need a biblatex file to be able to cite ressources. It is recommended to use Zotero and the Better-Biblatex-plugin to automatically keep your bibliography up-to-date. 
* **Important**: You need to import the package `etoolbox` in your preamble.
* For easy editing, I recommend Kile, which is also available for Windows, since it handles all Biber & Latex-stuff automatically.
* If that was not obvious yet: Any LaTeX installation, such as TEXLive or MIKTex - whatever suits your needs best.

# How to use
Just import the `template.tex` file into your document where you want
to have your title page. To change different fields of the title page
use commands like `\newcommand{\VWAauthor}{New Author}` before
the `\include` statement.

Possible options are: 
* `\newcommand{\VWAtitel}{Titel}`
* `\newcommand{\VWAauthor}{Author}`
* `\newcommand{\logo}{logo.png}`
* `\newcommand{\klasse}{Klasse}`
* `\newcommand{\jahr}{Jahr}`
* `\newcommand{\vorlagedatum}{tt.mm.jjjj}`
* `\newcommand{\schulinfo}{`

# Citation style
This template uses the Chicago manual of style and uses new commands for analogous/literal citation. New citiation styles could be added with relatively little effort.
