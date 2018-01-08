
# Times Square ticker

We want to create the software that controls a display that scrolls messages to people. The display shows characters but has a fixed width. By default our ticker has a length of 10 characters.

## Implement a scrolling message

We want to pass a message to the display, if the message fits in the display it should just show it. However if it longer than the display we want it to "scroll" the visible part of the message on the display.

In terms of representing the display it is fine to print what the display shows to `stdout`.

So for example if we were scrolling the message "Hello world!" then our first display would be nine spaces followed by the letter H, namely:

`_________H`

The second step would be eight spaces and the letters "He".

`________He`

The last step in the display would be the exclamation mark and nine spaces:

`!_________`

## Implement an infinite message

Now we have our scroll display we want the message to loop around so that when the end of the message arrives we show the start to the right of it.

We would like the number of spaces between the last and first characters in the message to be configurable.

So if we set the number of spaces to be three then the first looped message will look like this:

`World!___H`