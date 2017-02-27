# jQuery-HideShow
This plugin is used to get event when an element gets hidden or visible in DOM.

Don't get confused with `visibility: hidden;`.


`$("#test_hidden").hideShow(function(e, visibility){
    console.log("Element is "+visibility);
})`

*This plugin is keep watching on Element for change in dom visibility*
