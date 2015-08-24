#event-infinite-scroll

This is a Polymer component. This element will fire events when the page is scrolled to the top and bottom.

```html
<event-infinite-scroll
    auto-start
    scroll-offset="500"
    loading-delay="1000"
    on-reach-bottom="{{reachBottom}}"
    on-reach-top="{{reachTop}}">
</event-infinite-scroll>
```

Note: The `params` attribute must be double quoted JSON.

## Properties
###auto-start###
Type: Boolean
Default value: false

Auto start watching the page scroll as soon as the web component is ready

###scroll-offset###
Type: Number
Default value: 300

Set an offset value between the top and the bottom of the page

###loading-delay###
Type: Number
Default value: 0

Can be set to a time value (in millisecond) to delay the actions

## Properties

###reach-bottom###

Fired when the bottom is reached

###reach-top###

Fired when the top is reached

----

See the [component page](http://chadliu23.github.io/event-infinite-scroll) for more information.
