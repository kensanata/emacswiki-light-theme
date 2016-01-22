
EmacsWiki Light Theme
=====================

This is an attempt to design a light theme for the
[EmacsWiki](http://emacswiki.org), combining elements from various existing
themes, and some other additions. Suggestions and pull requests are welcome, or
you can file an issue at https://github.com/bburns/emacswiki-light-theme/issues.

Note that the current logo is just a placeholder - other designs or ideas are
welcome!


### Testing ###

To test the theme you can visit [this link](http://www.emacswiki.org/emacs?action=browse;bootstrap=0;id=CSSPreview;css=https://rawgit.com/bburns/emacswiki-light-theme/master/light.css) and use the wiki as normally -
this uses a service provided by http://rawgit.com to serve github files with the
appropriate content headers, though it will change to a more permanent location
later. 

To reset your theme to the default Bootstrap, visit
[this link](http://www.emacswiki.org/emacs?action=browse;id=CSS;bootstrap=1), or
see http://www.emacswiki.org/emacs/CSS/ and choose one of the existing themes.

You can also download the project and open one of the '''test*.htm''' files,
though note that some files may have extra whitespace here and there - this is
just due to globally adding a linefeed after '>' characters to make the HTML
more readable.


### Discussion ###

Some discussion is available on Reddit, for
[version 1](https://www.reddit.com/r/emacs/comments/40u8fx/new_emacswiki_theme/)
and [version 2]().


### Fonts ###

#### Normal Text ####

The font used for normal text is
[EB Garamond by Georg Duffner](http://www.georgduffner.at/ebgaramond/), and
served by [Google Fonts](https://www.google.com/fonts) - it's slightly heavier
weight than the Garamond included with Windows.

> EB Garamond is an open source project to create a revival of Claude Garamont’s
> famous humanist typeface from the mid-16th century. Its design reproduces the
> original design by Claude Garamont: The source for the letterforms is a scan
> of a specimen known as the “Berner specimen”, which, composed in 1592 by
> Conrad Berner, son-in-law of Christian Egenolff and his successor at the
> Egenolff print office, shows Garamont’s roman and Granjon’s italic fonts at
> different sizes. Hence the name of this project: Egenolff-Berner Garamond.

> Why another Garamond? The Garamonds are probably the most copied typefaces in
> the world. There are indeed lots of excellent Garamond fonts, also such that
> try to approach the original in the same way as EB Garamond does. In the world
> of free software, however, only few Garamond-inspired fonts exist, and as far
> as I know, none with the scope of EB Garamond. I know that competition is hard
> in this field, and these fonts won’t be able to stand up to their commercial
> counterparts for quite some time. Nevertheless, it's time for the open source
> community to have a classical Garamond and I promise, I’ll try hard to learn
> and give my best.

> EB Garamond is free software under the terms of the SIL Open Fonts License
> (ofl). That means, you are entitled to do what you want to with these fonts,
> as long as you retain the ofl notice, even if you distribute it in a modified
> form, don’t sell them on their own, and don’t claim they were your work.

#### Italic Text ####

For italic text, one of the built-in serif fonts is used, as EB Garamond lacks
an italic face, and so is computer generated.


### Existing themes ###

There are several alternative themes on the EmacsWiki at
http://emacswiki.org/emacs/CSS - some are included in the `originals` folder.
There is also an image gallery with screenshots of some of the existing themes
at http://imgur.com/a/czk9D.

Some features drawn from other themes:

* Cali+  
 [x] use as a base  
 [x] have section separators but lighter dots  
 [x] headline text in normal font  
 [x] box around table of contents  
 [x] buttons at bottom  
 
* Made in California  
 [x] gray links  
 [x] larger `function references' text (had been too small on my system)  
 
* Planet CSS  
 [x] code block font  
 [x] colored syntax highlighting  
 
* Wikipedia  
 [x] large logo on left  
 [x] try headings with underlines instead of section separators  
 [x] try a vertical sidebar  


### Todo ###

* Some further things to do

 [ ] make new logo  
 [ ] change menu items from "SiteMap" to "Site Map", etc  
 [ ] update the favicon  
 [ ] add links to emacs main page, manuals, twitter, rss, along sidebar  
 [ ] add a back to top link at bottom  
 

### About ###

This CSS has the MIT License. 

