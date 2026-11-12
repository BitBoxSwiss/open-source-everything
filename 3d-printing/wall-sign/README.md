# Wall sign

The keychain design scaled up into a wall sign as large as a 256 mm build plate allows: 271.5 x 146 mm, with a base 11.2 mm thick and letters raised 4.48 mm.
The key ring's hole is filled, and two keyholes in the back hang it on two nails.
To enhance its presentation at this scale, the sign has chamfered edges: 3 mm on the front edge of the base and 0.6 mm on the top edges of the letters.

<img src="preview.png" alt="The wall sign from the front" width="700">

## Files

- [wall-sign.3mf](wall-sign.3mf): an OrcaSlicer project, ready to print on a Bambu Lab P1S with a 0.4 mm nozzle.
  By the slicer's estimate, it takes about 3 hours 25 minutes and 130 g of filament.
- [wall-sign-base.stl](wall-sign-base.stl) and [wall-sign-letters.stl](wall-sign-letters.stl): the base and the letters, turned 59 degrees as they sit on the plate.

## Printing

The sign prints turned 59 degrees, which lets it use the plate's diagonal; square to the plate it would stop at 248 mm.
Centered on the plate, it stays clear of the P1S's excluded front-left corner and of the line the printer draws along the front edge to prime the nozzle.

The 3MF file uses the stock "0.20mm Standard" process and the Generic PLA profiles, with three changes:

- **No brim.** The automatic brim ran out to the plate's edges and over the priming line.
- **Prime tower off.** All the letter layers sit above all the base layers, so the sign needs only one filament change.
- **Solid infill direction at 14 degrees instead of 45.** With the sign turned on the plate, the stock angle ran the top surfaces' lines nearly upright across the text.
  At 14, the top lines of the base and the letters run parallel, rising at 45 degrees to the text.

Layer height shows mostly on the chamfers.
The base's chamfer steps once per layer, while the chamfer on the letters' top edges shows about four steps at 0.16 mm layers and two at 0.20 mm.

## Hanging

Two nails, level and 101.6 mm (4 in) apart, each 51.9 mm below the top of the sign, the left one 61.3 mm in from the sign's left edge.
Leave the nails standing out about 5 mm; anything from 3.1 to 6.5 mm fits a nail with a 1.5 mm head.
The spacing is centered on the sign's center of mass.

<img src="hanging.png" alt="Where the nails go, seen from the front, with the keyholes in the back outlined" width="600">

<img src="keyholes.jpg" alt="Sliced cutaway of the base, showing the two keyhole pockets for the nails" width="600">
