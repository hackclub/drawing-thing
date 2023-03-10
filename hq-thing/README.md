# hq-thing

Documenting the various redesigned parts of the prototype at Hack Club HQ.

![drawing-thing-1](https://user-images.githubusercontent.com/72365100/216111031-4d0d3c92-9011-4a9d-b6a0-00293544a068.gif)


## Bill of Materials

### Off-the-shelf parts

| Quantity | Part                           | Link              | Notes                     |
| -------- | ------------------------------ | ----------------- | ------------------------- |
| a bunch  | M5 screws and nuts             | OpenBuilds        |                           |
| a number | M3 screws and nuts             | McMaster-Carr     |                           |
| some     | M2 screws and nuts             | McMaster-Carr     | comes with the Sprig!     |
| yeah     | t-nuts                         | Amazon            | they're cheaper on Amazon |
| some     | 3mm eccentric spacers          | OpenBuilds        | need moar                 |
| tons     | 1mm spacer                     | OpenBuilds        |                           |
| 2        | Nema 17 stepper motor          | Stepperonline.com |                           |
| 1        | micro servo                    | Amazon            | acquired from Generator   |
| some     | v-wheels                       | Amazon            |                           |
| 1        | 250mm 20x20 aluminum extrusion | OpenBuilds        | y-axis                    |
| 1        | 250mm 20x40 aluminum extrusion | OpenBuilds        | x-axis / stationary       |
| 4        | smooth 6mm?? idler pulleys     | Amazon            |                           |
| 1        | timing belt                    | Amazon            |                           |

### Fabricated parts

| Quantity | Part             | File                                                                                                    | Notes                                                                                                                                 |
| -------- | ---------------- | ------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| 2        | Belt clamp clamp | [belt-clamp-clamp.stl](./3d/belt-clamp-clamp.stl)                                                       |                                                                                                                                       |
| 1        | Belt clamp       | [belt-clamp-thick.stl](./3d/belt-clamp-thick.stl)                                                       |                                                                                                                                       |
| 1        | Pen holder       | [pen-holder-pen-part.stl](./3d/pen-holder-pen-part.stl)                                                 | part that holds the pen                                                                                                               |
| 1        | Pen holder       | [pen-holder-vertical-part.stl](./3d/pen-holder-vertical-part.stl)                                       | part attaches to the belt-clamp-thick                                                                                                 |
| 1        | servo arm        | [servo-arm.stl](./3d/servo-arm.stl)                                                                     |                                                                                                                                       |
| 2        | foot             | [feet.stl](./3d/foot.stl)                                                                               | need to redesign. This is the part the steppers are mounted on. I think right now, it's kind of weak and will probably sag over time. |
| 1        | carriage         | [carriage.dxf](./laser/carriage.dxf)                                                                    | laser cut 1/4" acrylic. TODO: check if this is actually the right file                                                                |
| 1        | idler (2 parts)  | [idler-round-thing.stl](./3d/idler-round-thing.stl) and [idler-with-mount.stl](3d/idler-with-mount.stl) | idler that goes on one end of the axis that moves                                                                                     |
