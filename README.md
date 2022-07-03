# Giant tying factory

This repo contains the various technical explanations of a machine consisting of 7 KUKA KRC4 robots, the purpose of which is to assemble reinforcing bars for concrete structures. These rebars are then assembled into a latticework, up to 9m by 13m in size.
Places for doors and windows can be drawn into these lattices.

A mesh is configured by the user of the machine via a file with the extension .csv, which contains all the data required for the manufacturing process.

The machine is divided into 4 independent stations:
- The first one allows the deposit of horizontal bars.
- The second allows the deposit of vertical bars.
- The third station allows the bars to be tied and some of them to be cleaned and welded.
- The fourth aims to place the mesh outside, allowing the crane operator to pick it up.
