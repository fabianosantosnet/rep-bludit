# Dark Green Code Theme for BLUDIT CMS

> Para detalhes em português [veja aqui no projeto](https://fabianosantosnet.github.io/bluditCMS/).

## Description
Black and green site template with one column, featured content (stick pages), search, static pages (navigation top links), support up to 3 plugins at the bottom page and some configuration in init.php.

Languages: english and portuguese.

Default cover image size 200x100.

Some CSS classes are available to use in your Bludit source code editor: left, right, center, w25, w50, w75, border, bg, opacity and grayscale
Use this code to set two classes in your image ```<img class="center opacity" src="myimage.jpg" alt="some text" />```

Logo image 228x204 (background header color #555555 - use that color when you create your logo to center image).

File init.php
- Set number of sticky pages on home page (variable $NUMBER_STICKY_PAGES_HOME_PAGE )
- Set the name of author (variable $$authorName - meta tag info [default site footer info] )
- Switch between 2 paginator types (bool $IS_PAGINATOR_BY_NUMBERS [default false])
- Allow default image (bool $IS_COVER_IMAGE_FALLBACK_SET [default true / false don't show image]) and set image location ($_DEFAULT_COVER_IMAGE [default image generated from placeholder.com]) 

## Compatible 
- Bludit v3.x

## Author
- @fabianosantosnet

## Credits
- Some parts thanks to:  
   CSS Reset from [HTML5 Boilerplate v7.3.0](https://html5boilerplate.com)  
   Font family fallback from [Vanilla CSS](https://github.com/bradleytaunt/vanilla-css/blob/master/vanilla.css)  
   Web Font from [OnlineWebFonts](https://www.onlinewebfonts.com/)
   
## License
- MIT

## Screenshot
![screenshot-dark-green-code](https://raw.githubusercontent.com/fabianosantosnet/themes-repository/master/items/darkgreencode/screenshot.png)
