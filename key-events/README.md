### keydown

Despite its name, "keydown" fires not only when the key is physically
pushed down. When a key is pressed and held, the event fires again
every time the key repeats.

### keypress

There exists another event, "keypress", which fires right after
"keydown" (and repeated along with "keydown" when the key is held)
but only for keys that produce character input.

The keypress event is fired when a key that produces a character
value is pressed down. Examples of keys that produce a character
value are alphabetic, numeric, and punctuation keys. Examples of
keys that don't produce a character value are modifier keys such
as Alt, Shift, Ctrl, or Meta.

The charCode property in the event object contains a code that can
be interpreted as a Unicode character code. We can use the
String.fromCharCode function to turn this code into an actual
single-character string.


