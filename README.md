# CSS Flexbox
-   Flex box works on one dimension
    -   by default that is the horizontal(x-axis) dimension
    -   by default the main axis is read left - right (or if vertical top to bottom)

## Flexbox Properties
    -   Justify Conten - describes how to align content along MAIN axis
    -   Flex-End/Flex-Start refer to the start and the end of main axis

    -   Align-Items - aligns flex cchildren along he CROSS axis
        -Does not access to 
    -   BY DEFAULT ALL Containers is only as tall as the content inside of it
    -   Can only be used if there is enough height of container

    -    Align-Content - If flexbox goes to multiple lines, and has extra space for height of containere, this porperty allow acees to space-around/evenly between  
    -   Flex-Grow - property used on flex child to adjeust width according to ratio. EVERY CHILD HAS TO HAVE IT TO WORK
    -   Flex-Direction allows us to change the main axis of our flex container. (row or column)
        ***This changes the main exis & the cross axis (justify-content, aligh-items, align-content)***
    -   Flex-Wrap - when added to flex congtainert can cause to go to mulitple lines
    -   Flex-Flow - combines flex-Wrap/Direction into one property