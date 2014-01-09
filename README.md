scrollThis
==========

A simple jQuery plugin for wrapping an element in a scrollable box with buttons and scroll wheel functionality.
Here's An Example!
```javascript
// Using ScrollThis with the default options
$(".thingToMakeScroll").scrollThis();

// Using ScrollThis and specifing options
$(".withOptions").scrollThis({              
       scrollNum: 1,                        // number of items to scroll (any multiple, could be 0.5!)
       hoverScrollNum:1,                    // number of items to scroll on hover over button
       hoverScrollDelay:200,                // delay between scrolls during hover
       hoverStartDelay:1000,                // time to hover over button before scrolling
       cssSelectors:{                       // a collection of CSS classes that will be applied to new elements
               wrapper:"container",           // wrapper class
               buttons:"btn",                 // button class
               upBtn:"up",                    // up button class
               downBtn:"down"                 // down button class
       }
});
```

<!--
@description Wraps a thing in a div, puts a div before and after said thing.
@description Makes the thing scroll via the buttons or scroll wheel.

@version 0.0.8
@author Ryan Bogle
@license Attribution 3.0 Unported (CC BY 3.0)
@license http://creativecommons.org/licenses/by/3.0/legalcode

@requires jQuery

@class scrollThis
@memberOf jQuery.fn

@example
// Using ScrollThis with the default options
$(".thingToMakeScroll").scrollThis();

// Using ScrollThis and specifing options
$(".withOptions").scrollThis({              
       scrollNum: 1,                        // number of items to scroll (any multiple, could be 0.5!)
       hoverScrollNum:1,                    // number of items to scroll on hover over button
       hoverScrollDelay:200,                // delay between scrolls during hover
       hoverStartDelay:1000,                // time to hover over button before scrolling
       cssSelectors:{                       // a collection of CSS classes that will be applied to new elements
               wrapper:"container",           // wrapper class
               buttons:"btn",                 // button class
               upBtn:"up",                    // up button class
               downBtn:"down"                 // down button class
       }
});
-->


