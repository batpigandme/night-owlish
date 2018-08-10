## Notes on `.rstheme` installation*

To install custom themes in RStudio, you must have the [daily build](https://dailies.rstudio.com/) installed. 

With the daily build, you can import the [tmTheme file](https://github.com/batpigandme/night-owlish/blob/master/tmTheme/night-owlish.tmTheme) by going to `Preferences >> Appearance >> Add` (see gif, below).

![Importing custom themes in RStudio](https://i.imgur.com/0801DLK.gif)

However, I've added several improvements specific to the Ace and rstheme formats. In order to modify the imported rstheme file, you'll need to go to: **`/Users/<you>/.R/rstudio/themes`**.† 

There, you'll find the imported theme as `night-owlish.rstheme`. You can either copy and paste the contents, or the [`night-owlish.rstheme`](https://github.com/batpigandme/night-owlish/blob/master/rstheme/night-owlish.rstheme) file itself (the one in this repo) to enable the super-special-just-for-RStudio-beautified version. 💅 

**_Last updated: 2018-08-10_**

---
\* Unofficial guide, YMMV.

† I only know how to do this on a Mac. Sorry! 😬
