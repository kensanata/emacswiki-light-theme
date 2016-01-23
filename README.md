
EmacsWiki Light Theme
=====================

This is an attempt to design a light theme for the
[EmacsWiki](http://emacswiki.org), combining elements from various existing
themes, and some other additions. Suggestions and pull requests are welcome, or
you can file an issue at https://github.com/bburns/emacswiki-light-theme/issues.

Note that the current logo is just a placeholder - other designs or ideas are
welcome!


### Screenshots ###

Version 2:  
![Version 2]()

Version 1:  
![Version 1](http://i.imgur.com/NCjDpe3.png)


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

The font used is Garamond - it's a bit on the light side, but most other serif
fonts tried seemed to be too heavy.


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

