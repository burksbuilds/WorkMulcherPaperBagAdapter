# Worx Mulcher Paper Bag Adapter

![Photo with Mulcher](Images/Assembly%20With%20Mulcher.jpg)

This assembly is designed to adapt a standard brown paper lawn bag to the [Worx WG430 Electric Leaf Mulcher](https://www.worx.com/electric-leaf-mulcher-wg430.html).
The provided mulcher stand is good for connecting black plastic lawn bags but is too wide to accomodate standard (12x16x34 inch) [brown paper lawn bags](https://www.lowes.com/pd/Lowe-s-5-Count-30-Gallons-Brown-Tan-Outdoor-Paper-Lawn-and-Leaf-Trash-Bag/5013024901).
This design elevates the mulcher to accomodate the increased height of the paper bags and provides a bag-mounting feature small enough to accomodate the paper bags without needing to stretch them.

## Design

![Render](Images/Assembly%20Render.png)

The adapter assemby is made from four identical quarter-circle 3D-printed parts bolted together to form a solid ring.
The ring is supported by four lengths of 1/2" EMT conduit, connected with thumb screws and captured nuts.
There are two mounting points for optional toggle clamps on each quarter which can be used to secure the bag to the ring.

![Zoom Render](Images/Plastic%20Assembly%20Zoom.png)

The underside of the ring has a circular channel for the paper bag to fit in to, along with conical lead-ins to help guide the bag into the slot.

The design was developed in Solidworks 2024 and all custom parametric files are available in this repository. Reference models for hardware were taken from the McMaster-Carr website (see the [gitignore](.gitignore) or open the [assembly](Lawn%20Bag%20Adapter.SLDASM) in Solidworks for a list of McMaster parts used in the assembly model)

> Detailed design notes are available on the [Burks Builds Blog](https://burksbuilds.com/other/work-mulcher-paper-bag-adapter/)

## 3D Print

![Part In Printer](Images/Printed%20Part.jpg)

The plastic quadrant is designed to print either upside down or rightside up without any supports. 
The largest bridge is approximately 1/2 inch long.
The original design was printed on a Bambu P1S with 0.4mm nozzle and default settings (see [print settings file](Adapter%20Quadrant.3mf)).
The print takes about 8.5 hours and consumes approximately 370g of PLA.
The [model](Adapter%20Quadrant.STL) is just under 250mm x 250mm, so a large 3D printer is required.

## Assembly

![Quadrant Assembly](Images/Assembled%20Quadrant.jpg)

Toggle clamps can be mounted to the flats on either side of the part using #6 sheet metal screws (1/2" long).
There is a slot in the center to capture a 1/4"-20 hex nut which is used to thread in the thumb screw that retains the conduit leg.

![Ring Assembly](Images/Ring%20Assembly.jpg)

There is an alignment feature to help guide the four quadrants together.
The hexagonal relief on the left side of each quadrant (when viewed from the outside) is designed to capture an M6 hex nut.
The hexagonal relief on the right side of ach quadrant is designed to accomodate an M6 washer and cap screw.

![Full Assembly](Images/Assembled%20Legs.jpg)

The legs are made from 37 inch long sections of 1/2" EMT conduit (nominal OD of ~0.7 inches), but longer or shorter legs may be more desirable.
The legs should be inserted all the way into the plastic until they bottom out so that the thumb screw merely retains the conduit and does not support any of the weight of the mulcher.

## Bill of Materials

|Item   |Qty    |Cost   | Notes |
|--     |--     |--     |--     |
|Adapter Quadrant   |4  |$20    |1.48kg of PLA
|Legs               |4  |$10    |37" of [1/2" EMT conduit](https://www.lowes.com/pd/Common-1-2-in-Actual-50-In-Metallic-Emt-10-ft-Conduit/3129551) per leg
|Connecting Screws  |8  |$5     |[M6 Cap Srew, 40mm](https://www.lowes.com/pd/Hillman-6mm-1-x-40mm-Phillips-Drive-Machine-Screws-5-Count/999994860)
|Connecting Nuts    |8  |$2     |[M6 Hex Nut](https://www.lowes.com/pd/Hillman-6mm-x-1-Zinc-Plated-Steel-Hex-Nut-10-Count/999995432)
|Leg Nuts           |4  |$1     |[1/4-20 Hex Nut](https://www.lowes.com/pd/Hillman-1-4-in-x-20-Zinc-Plated-Steel-Hex-Nut/3058547)
|Leg Thumb Screws   |4  |$2     |[1/4-20 Thumb Screw x 3/4 Long](https://www.lowes.com/pd/Hillman-1-4-in-20-x-3-4-in-Thumbscrew-Drive-Machine-Screws-2-Count/3012563)
|Optional Clamps    |4  |$7     |[201A Clamp](https://www.amazon.com/dp/B00S9D0Z46)
|Clamp Screws       |16 |$2     |[#6 x 1/2" Sheet Metal Screw](https://www.lowes.com/pd/Hillman-6-x-1-2-in-Phillips-Drive-Sheet-Metal-Screws-20-Count/3035786)
|**TOTAL**          |   |**$49**




