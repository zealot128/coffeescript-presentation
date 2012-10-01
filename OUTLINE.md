# Intro

* WAT


## Syntax

* von Python: Indentation > Braces
* functions
* von Ruby: parents optional, alles hat return value
* String Interpolation/Multi line strings
* Javascript strict/Patterns:
  * Local Variable
  * == -> ===
  * Module Pattern
  * Classes

Erwaehnen:
* everything is an expression: if/else/while
* Chained comparisons
* existential

## JQuery & Co.


$('a.special').click ->
  element = $(this)
  $.ajax
    url: element.attr("href")
    data:
      id: element.data("id")
    complete: (resp) ->
      console.log "Completed"


## Tooling

Spielen: http://coffeescript.org/extras/coffee-script.js

Node.js/NPM: npm install -g coffee-script


Syntax:
* vim, eclipse, sublime, netbeans ...

Building:
* coffee hat eingebauten watcher
* Rails: Default seit 3.1
* Sinatra, Django, Drupal, Symfony2 ...

## Downsides

* Debugging: Zeilennummern matchen nicht mit Fehlermeldung
* -> Source Maps in spaeteren Browsern

http://ryanflorence.com/2011/case-against-coffeescript/

## Who uses it

https://tech.dropbox.com/?p=361
blockquote In the process of converting, we shaved off more than 5000 lines of code, a 21% reduction. Granted, many of those lines looked like this:

      });
          });
            }
            }



## Resources

http://coffeescript.org/

http://coffeescriptcookbook.com

Credits: https://github.com/bodil
