Dom's TextMate Bundle
===================

Mostly frontend snippets for TextMate

Installation
---------------
    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git@github.com:domchristie/tmbundle.git DomChristie.tmbundle

Reload your bundles, and you're done!

Usage
---------
### Lucida font-stack

Nice Lucida font-stack:

    "Lucida Grande", Verdana, Tahoma, Ubuntu, sans-serif

Tab trigger: `lucida`

### jQuery document ready

Shorthand jQuery document ready function.

    $(function(){
      
    });

Tab trigger: `$`

### Console log

Logs selected text in javascript console (or creates empty log function).

    window.console && console.log();

Key equivalent: `ctrl + shift + L`

### CSS comment banner

Makes selected text into CSS comment banner (or creates an empty one).

    /*
    -----------------------------------------------
    Banner
    -----------------------------------------------*/

Key equivalent: `ctrl + shift + /`
