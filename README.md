# Night Owlish 🌙🦉

A tmTheme, Ace editor, and rstheme adaptation† of [@sdras](https://github.com/sdras/)' [Night Owl VS Code theme](https://github.com/sdras/night-owl-vscode-theme)…

* Theme for [Ace](https://github.com/ajaxorg/ace) editor generated using `.tmtheme` import instructions found [here](https://github.com/ajaxorg/ace/wiki/Importing-.tmtheme-and-.tmlanguage-Files-into-Ace) (plus some manual modifications to [`.css`](https://github.com/batpigandme/night-owlish/blob/master/aceTheme/night_owl.css) file).  

* Theme for [RStudio](https://www.rstudio.com/) IDE generated using the theme importer in [RStudio preview](https://www.rstudio.com/products/rstudio/download/preview/) and [daily](https://dailies.rstudio.com/) builds, with modifications to [`.rstheme`](https://github.com/batpigandme/night-owlish/blob/master/rstheme/night-owlish.rstheme) file.

### Night owlish in RStudio 🌌

![](https://i.imgur.com/KCW7dRa.png)

#### Syntax highlighting in R

![night owlish R syntax highlighting](https://raw.githubusercontent.com/batpigandme/night-owlish/master/img/night-owlish-r-script.png)

#### Syntax highlight in RMarkdown

![night-owlish syntax highlighting in RMarkdown](https://raw.githubusercontent.com/batpigandme/night-owlish/master/img/night-owlish-rmd-screenshot.png)

## Installation notes

If you have an up-to-date daily build, you can directly import the [`.rstheme`](https://github.com/batpigandme/night-owlish/blob/master/rstheme/night-owlish.rstheme) file!

After importing the tmTheme to RStudio, an `.rstheme` file will be generated in:

```
/yourusername/.R/rstudio/themes
└── night-owlish.rstheme 
```

If you use Windows, the `.rstheme` file will be generated in:
```
C:\Users\yourusername\AppData\Roaming\RStudio\themes
└── night-owlish.rstheme 
```

I recommend copying and pasting the [`night-owlish.rstheme`](https://github.com/batpigandme/night-owlish/blob/master/rstheme/night-owlish.rstheme) file over that one, as it has been modified to enable scopes not otherwise imported by the tmTheme.  

🌌 Enjoy

† _Full disclosure: I don't actually use TextMate — this was but a means to an end, as RStudio (which uses Ace) allows you to import tmThemes. If it looks terrible, and you have fixes please submit a PR!_ 🙏
