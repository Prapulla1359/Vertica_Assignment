# Vertica_Assignment

The Problem Statement:
The test consists of a single page, with a header and a footer and a display area. The header contains some fixed text, a basic radio control, a
clock and some help text. The center display area contains a small panel. This panel can be manually postioned or postioned by the radio
control.

# Feature Requirements (Sorted by priority)

1. The page should have a fixed height position header and fixed height footer. The footer should stay attached to the bottom of the page
and of the defined fixed height regardless of browser resize action. The browser should not display a scrollbar until interior components
become too large.
2. The interior display area should be a fixed height of 400 pixels regardless of browser size. The footer will be allowed to separate from the
display area as the window is resized. See image below.
3. The window in general will contan a floating panel that cannot enter the header or footer area.
4. There should be a clock on the upper right corner of the page in the black header area and it should be up to date. It should be vertically
centered if possible in the header.
5. The header bar will contain a positional control for the floating panel. Radio options for the "Position" should be mutually exclusive and
the selection state should be properly hooked up with the position of the floating block in the middle of the page. Ideally these will be
vertically centered in the header.
6. Whatever the position option is selected, the floating block in the display area.should have text indicating its position. Example "Lower
Right" for option 2, "Center" for option 1.Colors and fonts are up to the candidate but should be easily changed.
7. When the position option is set to "Center", the floating block should be perfectly centered in the browser viewable window, and it should
readjust itself when the browser is resized, but always sticks to the center.
8. When the position option is set to "Lower Right", the floating block should stick to the lower right corner of the page, just above the black
footer area. It should remain in its position even when the window is resized.
9. The grey floating block should be draggable, but ONLY WITHIN THE LIGHT GREAY AREA under the black header, it should not be able
to be dragged outside the the grey containment even in the event of resizing of the browser. Dragging it from the picture above should
snap it back into the area.
10. The floating block should disappear if the user hits the Escape key on the browser and reappears when the Enter key is hit.
11. The candidate should be able to use browser console to log some of the debug information instead of simply using the alert() function
call.



