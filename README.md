# WACCA shield

Plans for the laser-cut metal shield of a home-built WACCA cabinet: the folded
plate that covers the screen and carries the controller ring. The drawing of the
cabinet it was built for comes with it.

These are working documents, not a polished build guide. They are the files I
actually used, published in case they save someone else the measuring.

| Folder | What is in it |
|---|---|
| `Screen Shield/` | Vector plans for the metal shield, ready for laser cutting |
| `Plan/` | Rough cabinet drawing: overall dimensions and the panel cut list |

## Screen shield

![Screen shield, flat pattern](Screen%20Shield/screen%20shield_v2.png)

A single folded aluminium plate: the large central opening is for the screen, and
the ring of small holes around it takes the controller ring.

**Material:** aluminium, raw + PVC film, **2 mm** thick. Going thinner is not
advised, since the plate carries the whole ring: at 2 mm it still flexes slightly
when pressing hard on the bottom buttons. 3 mm would be sturdier but much heavier.

**Cost:** around 150 EUR for the finished metal part, cut and folded, in the EU.

### Dimensions

| Measurement | Value |
|---|---|
| Flat plate | 880 x 1270 mm |
| Inner part, after folding | **800 x 1230 mm** |
| Folds | approx. 40 mm on left, right and top. None at the bottom |
| Fold angles | 90 degrees left and right, 70 degrees at the top |

> **The 800 mm is the number that matters.** After folding the sides, the inner
> width must be exactly 800 mm. If the wooden assembly is wider than that at any
> point, the shield will not sit. On my build the bottom came out at 806 mm and
> the whole frame had to be reworked down to about 801 mm.

See `fold reference.jpg` for the fold directions and
`inner-distance-with-folding.png` for where the inner distance is measured.

### Files

| File | Use |
|---|---|
| `screen shield_v2.dxf` | **Final version, the one sent to the cutter** |
| `screen shield_v2.ai` | Illustrator source |
| `screen shield_v2.svg` | Vector export |
| `screen shield_v2.pdf` | Print / preview |
| `screen shield_v2.png` | Preview, shown above |

## Cabinet

![Cabinet plan](Plan/Plan.png)

The base drawing comes from the official manual. The dimensions, the cut list and
the notes written over it are mine.

Overall: **800 wide x 1730 high x 520 deep** (mm). The screen face is 1230 mm on a
slant, over a 900 mm lower section.

**This build is 80 mm taller than the original**, because I am tall and wanted the
cabinet to match. That is what the `+80` notes on the right of the drawing mean:
total height goes from 1730 to about 1810 mm, and the playfield from 540 to 620 mm.
The cut list below already accounts for it, which is why the sides are 1800 mm and
not 1730. Drop the 80 mm if you want the original height.

Panel cut list, as drawn:

| Size (mm) | Qty | Thickness | Part |
|---|---|---|---|
| 800 x 1800 | 2 | 16 mm | sides |
| 800 x 520 | 1 | 16 mm | main base |
| 768 x 512 | 1 | 12 mm | middle plate, I/O support |
| 768 x 100 | 1 | 16 mm | top |
| 768 x 100 | 1 | 12 mm | connector part (front) |
| 768 x 620 | 1 | 8 mm | back cover, bottom |
| 768 x 300 | 1 | 8 mm | back cover, top |
| 768 x 570 | 1 | 16 mm | screen support |

> **Double check the internal margins before cutting.** The 768 mm parts assume
> 16 mm sides (800 - 2 x 16). Adjust them if your panels differ in thickness.

> **Known issue: the slant angle is slightly off.** By almost nothing, and it goes
> unnoticed on its own. It only showed up when fitting the speakers: the back does
> not line up with them properly. Check the angle against your own speaker mounting
> before cutting the sides.

## License

My own work here is released under **CC BY-SA 4.0**, see [LICENSE](LICENSE): the
shield plans in every format, the cut list, the measurements and the notes. Build
them, modify them, share them; just credit the source and pass the same freedom
on. A share-alike licence rather than a code one, because what is published here
are drawings and measurements, not software.

**One exception:** the base cabinet drawing in `Plan/` is taken from the official
manual. It is not mine to license, and it stays the property of its owner. It is
included because the dimensions written over it are useless without it.

WACCA is a trademark of its respective owner. This is an independent, non
commercial fan build, not affiliated with or endorsed by them.
