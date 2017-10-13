Pressing a mouse button also causes a number of events to fire. 

The
"`mousedown`" and "`mouseup`" events are similar to "`keydown`" and "`keyup`"
and fire when the button is pressed and released. 

These will happen
on the DOM nodes that are immediately below the mouse pointer when
the event occurs.

After the "`mouseup`" event, a "`click`" event fires on the most specific
node that contained both the press and the release of the button.

For example, if I press down the mouse button on one paragraph and
then move the pointer to another paragraph and release the button,
the "`click`" event will happen on the element that contains both
those paragraphs.

If two clicks happen close together, a "`dblclick`" (double-click)
event also fires, after the second click event.

To get precise information about the place where a mouse event
happened, you can look at its `pageX` and `pageY` properties, which
contain the event’s coordinates (in pixels) relative to the top-left
corner of the document.

