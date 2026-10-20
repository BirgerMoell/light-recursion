# recursion

A looping, recursive music video. Open the page, press **enter the recursion**, and move your pointer:
the video starts to contain itself, one level per step to the right.

Live: https://recursion.renaissancelabs.eu/

- The loop is seamless: the end dissolves into the start (6 s crossfade), and the sound is a Web Audio buffer that loops sample-exact.
- Visuals: a Droste tunnel of Julia sets with orbit-trap contours, rendered with WebGL shaders (Remotion).
- Page: one recursive function (`room(level, size)`) draws the video inside itself on a canvas. Press the `</>` button to see it.
