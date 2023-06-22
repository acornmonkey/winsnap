# xwinsnap
Window-snapping for X11
## Key bindings
* Meta+Left: xwinsnap left
* Meta+Right: xwinsnap right
* Meta+Up: wmctrl -r :ACTIVE -b add,maximized_vert,maximized_horz
* Meta+Down: xmetadown
## Dependencies
* X11
* bash
* wmctrl
* xdotool
* xprop (xmetadown only)
* grep (xmetadown only)
