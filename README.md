# Mark's Low Rider CNC V3 Build

An archive of files associated with my Low Rider 3 CNC machine build

This build is following the documentation here: [V1 Engineering Low Rider CNC 3](https://docs.v1e.com/lowrider/)

Forum build thread here: [LR3 in Washington - n00b build](https://forum.v1e.com/t/lr3-in-washington-n00b-build)

## As Printed

The [as-printed](./as-printed) directory contains the 3mf files for everything I printed. Files were saved from OrcaSlicer 1.9 which has a different format that is not compatible with earlier versions, but geometry should still load.

## Learnings

* Do not overtighten the bearing bolts in the LR3 core. I cracked my first core print by doing this. However if it had not happened then I would not have the two color core I have now!

* PETG and PLA do not stick to each other.  I found this out with the top piece of [as-printed/kobalt-router-mount.3mf](./as-printed/kobalt-router-mount.3mf) as I only have transparent filament in PETG. Hmmm...support material

* IMPORTANT - while I did not see this noted anywhere the singular YZ plate model provided needs to be mirrored for a second copy.  I have updated the [as-printed](./as-printed/YZ%20Plate%20v1.3mf) model to have two build plates with mirrored parts.

## My build measurements

Work Area: 48" x 24" (1220mm x 610mm)

Overall: 60.75" x 39" (this is the minimum table size from the [LowRider V3 Size Calculator](https://docs.v1e.com/lowrider/calculator/))

## Parts

I am working with standard US electrical conduit with a 23.4mm OD

Required tubing:

- 2 @ 55" for X rails
- 1 @ 39" in (or to match table depth)

Spindle: Kobalt 1.24HP Trim Router

## Modifications

- Captive nuts in gantry braces (@DougJosephdesign8stu) [Printables](https://www.printables.com/model/317381-lowrider-3-cnc-braces-for-gantry-remixed-to-have-n)
- Y-Axis Belt Shields (@DrEnchanted_513663
  ) [Printables](https://www.printables.com/model/685738-lowrider-3-y-axis-belt-shield-and-front-cap) (caps needed to be printed at 101% to fit correctly. Reflected in as-printed)
