# Troubleshooting Guide to Common 3D Printing Errors and Problems

If you are suffering from 3D printing issues or want to improve your print quality, this guide is for you. This document aims to cover the majority of problems and their causes in addition to possible solutions to each. The main focus of this guide is FFF (FDM) 3D printers; however, some points are transferable to other additive manufacturing processes.

Know the type of error you are suffering from? Use the table of contents below to skip to where you want.

### Table of Contents
1. [Blocked extruder](#1)
2. [Semi-blocked extruder](#2)
3. [Stripped filament](#3)
4. [Snapped filament](#4)
5. [Extruder too close to surface](#5)
6. [Extruder too far from surface](#6)
7. [Print doesn’t stick to bed](#7)
8. [Supports collapsed](#8)
9. [Shrinkage/Deformation](#9)
10. [Inaccuracy of surfaces](#10)
11. [Bowing at bottom](#11)
12. [Bending edges (Warping)](#12)
13. [Delaminating/Cracking](#13)
14. [Layers not lining up well](#14)
15. [Gaps between infill and wall](#15)
16. [Infill is messy](#16)
17. [Visible infill](#17)
18. [Layers missing](#18)
19. [Leaning of print](#19)
20. [Messy overhangs](#20)
21. [Support surfaces rough](#21)
22. [Non-manifold edges](#22)
23. [Ripples in print](#23)
24. [Diagonal scars on print](#24)
25. [Stringy/droopy artefacts](#25)
26. [Holes and pits in top layer](#26)
27. [Poor dimensional accuracy](#27)
28. [Messy bridges](#28)
29. [Offset between layers](#29)
30. [Early termination](#30)
31. [Detachment from printbed](#31)
32. [Out of filament](#32)

### 1. Blocked extruder <a name="1"></a>

**Problem**

Nothing is printing at all. The desired model has been sliced correctly and the printer has been configured, however, nothing appears out of the nozzle. You have checked to see if the printer has run out of filament, but there is still plastic remaining.
	
**Cause**

There can be multiple causes of a blocked nozzle. However, frequently the most common is a small leftover piece of filament from a previous spool. This annoying piece of old plastic will thwart your attempts to load new filament as it stops the plastic from being pushed through.
	
Another cause can be old carbonised filament - this is filament which has been stuck in your extruder for ages and over time at constant high temperature has carbonised causing an irritating block. If you are lucky this can be spotted early on as the quality of your prints will decrease as the amount of carbonised filament increases.

If you switch plastics a lot, this may be the reason for getting carbonised filament. Going from PLA to ABS or ABS to Nylon sees a reasonable temperature increase. Any remaining plastic of the previous variety at this higher temperature will likely carbonise and possibly burn.
		
**Solution**

One method to fix this problem is to unblock the extruder / nozzle using a needle. First off heat up the nozzle to the required temperature for the filament that is / was loaded, and remove any the filament if still *in situ*. For PLA set the temperature to somewhere in the range of 190C - 220C and for ABS in the range of 230C - 240C. Get hold of a pin which is slightly smaller than the diameter of your nozzle (most nozzles have a diameter of 0.4mm); an airbrush cleaning kit works perfectly. Insert the pin in the hole of the nozzle to unblock.
	
Another method to employ is to push filament through in order to unblock the nozzle. First off heat up the nozzle to the required temperature for the filament that is / was loaded, and remove any the filament if still *in situ*. For PLA set the temperature to somewhere in the range of 190C - 220C and for ABS in the range of 230C - 240C. When hot, try to use another piece of filament to push the old filement out the blocked nozzle. If using a Bowden extruder it is sometimes helpful to remove the feeder tube for this process. Frequently the extra pressure you can exert by hand compared to the extruder unclogs the nozzle, however don't push too hard or you might snap the filament or worse damage your printer.
	
Dismantling your hotend sometimes is the only way to remove a really nasty blockage. Sadly we can't offer instructions on how to do this for every hotend out there. Try looking for instructions or schematics online and record the steps you take whilst dismantling.

### 2. Semi-blocked extruder <a name="2"></a>
### 3. Stripped filament <a name="3"></a>
### 4. Snapped filament <a name="4"></a>

**Problem**

The filament spool still has plastic remaining. With direct drive extruders this problem should be clear, the filament is snapped... it is plain to see. However, if you don't catch this error early enough with direct drives it is a right pain as the extruder will push the snapped filament past your reach and the extruder / hotend setup will have to be dismantled. For a Bowden based setup it is hard to spot the snapped filament as most likely it will be in the feedtube, but nothing will be coming out of the nozzle.
	
**Cause**
	
One of the most common causes of this issue is old or cheap filament. PLA and ABS filaments can last a long time if kept in the correct conditions, however, if stored in incorrect conditions, such as in direct sun light, then they can become more brittle.
	
The diameter of the filament is another issue and this factor can vary from manufacturer to manufacturer and batch to batch. Additionally, if the idler tensioner on the extruder is too tight, the pressure may cause even good quality filament to snap.
	
Sometimes filament can get coiled up and tied in knots and if the extruder continues to pull and tighten these knots it can result in a snap.


**Solution**

First thing to try is to remove the filament in the usual manner.

### 5. Extruder too close to surface <a name="5"></a>
### 6. Extruder too far from surface <a name="6"></a>
### 7. Print doesn’t stick to bed <a name="7"></a>
### 8. Supports collapsed <a name="8"></a>
### 9. Shrinkage/Deformation <a name="9"></a>
### 10. Inaccuracy of surfaces <a name="10"></a>
### 11. Bowing at bottom <a name="11"></a>
### 12. Bending edges (Warping) <a name="12"></a>
### 13. Delaminating/Cracking <a name="13"></a>
### 14. Layers not lining up well <a name="14"></a>
### 15. Gaps between infill and wall <a name="15"></a>
### 16. Infill is messy <a name="16"></a>
### 17. Visible infill <a name="17"></a>
### 18. Layers missing <a name="18"></a>
### 19. Leaning of print <a name="19"></a>
### 20. Messy overhangs <a name="20"></a>
### 21. Support surfaces rough <a name="21"></a>
### 22. Non-manifold edges <a name="22"></a>
### 23. Ripples in print <a name="23"></a>
### 24. Diagonal scars on print <a name="24"></a>
### 25. Stringy/droopy artefacts <a name="25"></a>
### 26. Holes and pits in top layer <a name="26"></a>
### 27. Poor dimensional accuracy <a name="27"></a>
### 28. Messy bridges <a name="28"></a>
### 29. Offset between layers <a name="29"></a>
### 30. Early termination <a name="30"></a>
### 31. Detachment from printbed <a name="31"></a>

### 32. Out of filament <a name="32"></a>

**Problem**

Nothing is printing at all. The desired model has been sliced correctly and the printer has been configured, however, nothing appears out of the nozzle bar the tinyiest bit of oozing plastic. 

Another possibility is that the model is part complete and the extrusion stops all of a sudden but the printer's nozzle continues to wave around in thin air with no plastic being extruded.

**Cause**

A lack of ammunition. On many machines, such as the Original Prusa i3, it is clear to see that the filament spool has run out, however, on some printers this issue is not always immediately obvious as the spool isn't directly visible and is either encased in the printer or hidden around the back.

Some machines feature *smart* filament spools that inform the printer how much material is remaining. This can not always be contained though, as many of us tinker and modify the firmware or work around such failsafes.

Whatever your printer and extruder setup (direct drive or Bowden) you will have to extract some of the remaining filament and feed in some nice fresh plastic.

**Solution**
	
Find the filament spool and check to see if it is empty. If it is, load a new spool, if not you may have another problem. Sometimes the retraction of filament is not always painless. Some tips: 1. ensure the nozzle and hot end are hot, 2. extrude a small amount of plastic to melt the tip of the filament, 3. pull back to retract the filament.