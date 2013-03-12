This is a very simple [TextMate](http://www.macromates.com) Bundle to help with editing [FreeMarker](http://freemarker.org/ FreeMarker) templates.  It provides a (still incomplete) language definition, and some basic snippets, including some for Spring macros.

## Install
### Textmate 2

1. mkdir -p ~/Library/Application\ Support/Avian/Bundles
2. cd ~/Library/Application\ Support/Avian/Bundles
3. git clone git://github.com/briancavalier/textmate-freemarker-bundle.git "Freemarker.tmbundle"

### Textmate 1

1. mkdir -p ~/Library/Application\ Support/TextMate/Bundles
2. cd ~/Library/Application\ Support/TextMate/Bundles
3. git clone git://github.com/briancavalier/textmate-freemarker-bundle.git "Freemarker.tmbundle"
4. osascript -e 'tell app "TextMate" to reload bundles'

## Changelog

### Version 1.2

 * Last version was missing many of the snippets I thought I had included.  Sorry!
 * Including: if, list, assign, local, compress, compress single_line, and macro.

### Version 1.1

 * Added several more snippets for directives: if, else, list, compress, etc.
 * Organized the bundle menu

### Version 1.0

 * Very minimal Language definition that mostly plays well with HTML, but not completely.
 * A few useful snippets for Freemarker tags.
 * One simple HTML template.

## License

Copyright &copy; 2008-2013 Brian Cavalier, MIT License