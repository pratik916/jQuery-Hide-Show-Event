# jQuery-HideShow
This plugin is used to get event when an element gets hidden or visible in DOM.

Don't get confused with `visibility: hidden;`.


`$("#test_hidden").hideShow(function(e){
    console.log($(this).is(":visible"));
})`

