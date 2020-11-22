# Overview

I have a [Creality CR-6 SE][cr6] which I backed on [kickstarter][kcr6] and which has mostly been good for me, unlike people who have had parts of the printer catch fire or otherwise fail.

If you use Windows, I have no advice for you at all.

# PrusaSlicer

This github repo has my settings for PrusaSlicer 2.2.0 (and maybe later, when I upgrade).

If you use a Mac, you can copy some or all of my settings from here to your ```~/Library/Applications Support/PrusaSlicer``` directory, and unless you have a ```.ini``` file named exactly as mine, they should all co-exist safely.

# General Notes

I based all my settings for the CR-6 on the Ender 3, and because it's a pain in the ass to modify all the generic builtins, I just left the printer model in my printer description as 'Ender 3' so that all the generics line up.

I don't use Cura anymore, so don't ask.

I don't use Slic3r, so don't ask.

# Nylon Trimmer Line


* I've been printing with Nylon Trimmer Line, in particular [MaxPower 333665][ntl] from Amazon. It was $22 USD for a 1.4Kg spool last time I checked, or $16/Kg USD.
* [Nylon][ntl] **ABSOLUTELY POSITIVELY** needs to spend at least 16 hours in a dehydrator at 75C
* It's too big to fit into a [SunLu Dehydrator][sunlu] box so I put it in a generic [food dehydrator][presto].  I could respool it onto smaller spools that fit in the SunLu, but I don't have any empty spools yet. I haven't tried using this [spool][ulfs].
* generally my settings are 
  * Bed 105C
  * Nozzle 250C
  * Fan off
  * Filament Type = Nylon
  * 50mm/s print speed

# CR-6 SE Modifications

Does anyone run a *stock* printer?  I don't think so.

**BOUGHT:**

* This [replacement power switch][rps] from Amazon
* This [Capricorn pfte bowden][bowden] kit from Amazon
* This [Creality all-metal extruder][amex] kit from Amazon
* Some [stainless steel nozzles][ssn] from Amazon
* This [SunLu Dehydrator][sunlu] box from Amazon for PLA and PETG. Has adjustable temperature.
* This [Presto food dehydrator][presto] from Amazon for NYLON. It does not have a temp control (always 75C) so it is a little too hot for PLA.
* Several [simple timers][timer] to shut off the printer and dehydrator

**MADE:** 

* This [filament guide and wire harness][fgcg] from Thingiverse, which replaced this [filament guide][fg] I originally printed.
* This [hot-end wire-harness][cgbt] from Thingiverse, which replaced this [hot-end cable guide][hecg] I originally printed.
* This [X-Axis wire harness clip][xawhc] from Thingiverse
* This [left tool-box][lsd] from Thingiverse
* This [v-slot covers][vsc] from Thingiverse
* A fistful of these [filament clips][fc] which work surprisingly well, but are prone to go flying, and then the cat shoves them under furniture.
* Parts of this [TUSH spool holder][tush1], and this [the Tush++ remix][tush2], both from Thingiverse. These fit inside the [food dehydrator][presto] with the nylon spool so I can keep the [nylon][ntl] dry during very long prints.
* This [nozzle insert][ndi], which in turn fits in this [drawer insert][di] from Thingiverse

[cr6]: https://www.creality.com/goods-detail/cr-6-se-3d-printer
[kcr6]: https://www.kickstarter.com/projects/3dprintmill/creality-cr-6-se-leveling-free-diy-3d-printer-kit
[ntl]: https://www.amazon.com/gp/product/B003VPAEL6
[bowden]: https://www.amazon.com/gp/product/B082LPB9XD/
[amex]:https://www.amazon.com/gp/product/B07J44QW8B/
[ssn]: https://www.amazon.com/gp/product/B08MVWM43F/
[sunlu]: https://www.amazon.com/gp/product/B08C9RZPMN/
[presto]: https://www.amazon.com/gp/product/B008H2OELY/
[timer]: https://www.amazon.com/gp/product/B01KKOJ42U/
[rps]:https://www.amazon.com/gp/product/B081VD1NNT/
[tush1]: https://www.thingiverse.com/thing:2521463
[tush2]:https://www.thingiverse.com/thing:2451368
[cgbt]: https://www.thingiverse.com/thing:4653730
[lsd]: https://www.thingiverse.com/thing:4656033
[ndi]: https://www.thingiverse.com/thing:4656201
[di]:https://www.thingiverse.com/thing:4612526
[vsc]:https://www.thingiverse.com/thing:3379068
[fgcg]: https://www.thingiverse.com/thing:4632727
[hecg]:https://www.thingiverse.com/thing:4606951
[xawhc]:https://www.thingiverse.com/thing:4598182
[fg]:https://www.thingiverse.com/thing:4594094
[fc]:https://www.thingiverse.com/thing:1194027
[ulfs]:https://www.thingiverse.com/thing:1986210