# Tileable_Hexagons
 A web tool that generates a tileable grid of hexagons, with the option to represent the pattern mapped to a torus.

There are several options the user can adjust when generating a hexagonal pattern.

- numHexagonsWide: Approximate number of hexagons wide (may be adjusted to fit other properties).
- numHexagonsHigh: Approximate number of hexagons high (may be adjusted to fit other properties).
- radiusMargin: Margin between the hexagons.
- nodeRange: Spatial range in which the nodes of the hexagons may be randomly placed.
- cellVertexRange: Spatial range in which the cell vertices may be randomly placed.
- handleRange: Spatial range in which the Bezier curve handles for each vertex may be randomly placed.
- curveExtent: Spatial extent of the Bezier curves.
- strokeColor: Color of the stroke or outline of each hexagon.
- strokeWidth: Width of the stroke. Stroke/outline can be disabled by setting this to 0.
- fillColor: Most common color names are accepted, as well as rgba() [red, green, blue, alpha].
- wrap: Boolean. Determines if the hexagons at the edges are arranged to fit against the opposite side like puzzle pieces if they were to wrap around.
- scale: The scale of the pattern on the screen.
- torus: Boolean. Determines if pattern will be mapped to a torus. If so, the torus can be spun in 3D using the keyboard.

Future updates could include additional geometries to which the pattern could be mapped (cylinder, sphere, etc).
