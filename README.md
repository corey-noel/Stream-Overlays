# Fight Pitt 8 Stream Overlay

A JQuery stream overlay that interfaces with StreamControl, compatible with the Browser sources in both OBS and XSplit. Almost all of the code is contained within js/maincontrol.js. To create a new scene or overlay, all you need to do is make an image background, HTML file and CSS to go with it.

In a script in the HTML file, call the init() function, and then define updateAll() with respective calls to update all IDs that should be refreshed.

Easily extensible, and you don't need to install Flash. :)

### Required Files

> StreamControl.exe (**version 0.4b** - version that supports JSON output)
>
> streamcontrol.json (generated by StreamControl)
>
> players.csv (generated by StreamControl)
