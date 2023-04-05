# Kyria

The Kyria is a split keyboard kit by Thomas Baart of [splitkb.com](https://splitkb.com). In this repository you'll find files you can use to make your own Kyria case.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

These files are available for non-commercial use only. You explicitly have permission to make objects with these files for yourself, friends, family and coworkers. If you'd like to sell objects made from these files, please [get in touch](mailto:support@splitkb.com?subject=Aurora%20case%20licensing).

## Which files do I need?

1. Look for the folder of your keyboard, depending on your revision.
2. Decide whether you need kerf (see below: What's kerf?).
3. Pick the files for your keyboard:
    - **A bottom plate**: We have normal plates and puck plates. A normal plate is a fully covered plate, whereas a puck plate is compatible with the splitkb.com [Tenting Puck](https://splitkb.com/products/tenting-puck). It has a circular slot cut out for the puck to sit into. Bottom plates can easily be replaced later, so feel free to get a normal plate if you don't have a puck yet.
    - **A top plate**: We have normal plates, no puck plates and encoder plates. Normal plates have mounting holes, holes for switches, and holes for the puck screws to be mounted through. I recommend getting the normal plates, as the extra holes don't impact functionality and make it easier to add a puck later. The "no puck" plates don't have these extra mounting holes, and the "encoder" plates have wider holes for when you want to use an encoder on a choc-based build. You'll likely want to modify the encoder files before using them, as an encoder hole is larger and won't allow a switch to clip into the plate.
    - **An OLED cover**: Most keyboards will support OLED covers. They protect the microcontroller and display area. Even if you don't use an OLED, I still recommend using a cover, as it'll make the keyboard look more finished. If your keyboard doesn't have a file with "OLED Cover" in its name, then a cover isn't supported.

For rev1 and rev2 boards, a high profile case is available. The case composition and required hardware is a little different there, and is not supported for rev3 for the time being.

All files are symmetrical, meaning you use the same file for both the left and the right side. When ordering parts, make sure you order two of every file you've selected.

The files in this repository are DXF files, which can be opened using a tool like LibreCAD, Adobe Illustrator or other similar CAD or graphic design software packages. You'll be able to send these to a manufacturer to produce cases with for personal use, or modify them using a tool like Fusion 360 to make your own 3D-printable cases.

## What's kerf?

Kerf is the amount of material that's lost in the process of cutting, for example with a laser or water jet. As the cutter moves along the lines in the file, material is removed from either side of the line. Files that account for kerf, add a little bit of material to the edges of all cut lines to compensate for that lost material.

In short, if you're using a laser cutter yourself, you'll want the files with kerf. If you're sending them off to another service, you should ask them whether to include kerf. And if you're 3D printing, you shouldn't need any kerf, or might even need to remove some extra material depending on your printer and calibration.

The files with kerf that we supply are used with our own laser cutter. Third parties might require different settings. We don't supply those files, so you or the third party may have to modify the files to match their process.

## Which thickness do I need?

It depends! Generally:

- For MX switches, 1.5mm is best for the top plate if the material is sturdy enough. For acrylic, go with 3mm.
- For Choc switches, 1.2mm is best for the top plate if the material is sturdy enough. 1.5mm is also fine, and in most cases this makes it compatible with both MX and Choc. For acrylic, go with 3mm and a hand-solderable kit. **Hot swapping 3mm plates makes for a bad experience.**
- For the bottom plate and OLED cover, thickness doesn't matter a lot. We usually go with 3mm for acrylic.

## Which hardware do I need?

The number and lengths of spacers and screws will depend on the keyboard, the switches you use, and the plate thicknesses you choose. You can get all the hardware and some extras when buying an [Aurora Hardware Kit](https://splitkb.com/products/aurora-low-profile-case-hardware-kit).

We also sell various hardware separately:

- [M2 spacers in various lenghts](https://splitkb.com/products/brass-m2-spacers)
- [M2 screws in various lenghts](https://splitkb.com/products/m2-screws)

Generally:

- For MX switches and a metal top plate, go with 8mm spacers.
- For MX switches and an acrylic top plate, go with 6mm spacers.
- For Choc switches and a metal top plate, go with 6mm spacers.
- For Choc switches and an acrylic top plate, go with 4mm spacers.

The OLED cover requires 12mm spacers when using a display, though you might get away with 10mm in some cases. If you don't use a display, you can use 8mm or maybe even 6mm spacers.

## What should I keep in mind?

To prevent disappointment, take care of the following:

- Make sure of some measurements beforehand. For files without kerf, the size of a switch hole will be exactly 14x14mm. For files with kerf, the size of a switch hole will be exactly 13.9x13.9mm.
- Only use plates thicker than 1.6mm with hand solder kits. Hot swapping with thick plates is a bad experience.
- Only use acrylic as a material with plates thicker than 2mm, preferably 3mm. Thin acrylic is fragile and is likely to break during assembly.
- Take care when ordering detoriable materials like copper or brass. They will oxidate over time, which can give a nice patina look when done, but results definitely vary. If you'd like to keep copper or brass nice, take care to wax or coat it, preferably every once in a while.
- When painting or coating plates, some material is added. You might want to enlarge the switch holes to compensate for added thickness paint may add.
