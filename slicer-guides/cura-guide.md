# Cura Slicer Guide

When you open the Cura software, you will be able to access all of the settings on a side panel. The settings are divided up into numerous sections and categories. If you do not see all the setting categories something might be wrong, but first you can go to the `Preferences: Settings` menu and enable or disable a setting. Below you will find a brief outline of each of the categories taken from the Mastering Cura page on Ultimakers website.

**Machine**—Settings related to the specific printer. You can define the nozzle diameter in the Settings panel. If you have a nozzle with an inner diameter that’s different from one of the default sizes, you can enter the size of your custom nozzle here. This setting will then override the nozzle size that is chosen in the Print Job screen.

**Quality**—Settings that define the (visual) quality of the print. The layer height - one of the most often changed settings - is the thickness of one printed layer (in mm). With a thinner layer height you will usually increase the quality of the print, leading to a smoother surface and more detail visible in the Z-direction (height) of the model. On the other hand, by using thicker layers you can decrease the print time substantially.

**Shell**—Settings related to the outside of the print. Wall Thickness adjusts the thickness of outside walls (on the X/Y axis) of the model. This value divided by the wall line width defines the number of walls and is generally a multiple of the line width. For example: when using a wall line width of 0.35 mm, it will be logical to set the wall thickness to 1.05 mm (3 * 0.35), which means that 3 walls will be printed.
In general, a wall thickness of 2 or 3 times the line width is sufficient. A higher value will create a sturdier model and decreases the chance of leaks, while a lower value can significantly decrease the print time and filament costs. 

**Infill**—Settings related to the inside of the print. Infill density defines the amount of plastic used on the inside of the print. A higher infill density means that there’s more plastic on the inside of your print, leading to a stronger object. An infill density between 10% and 20% will be enough for most objects though.
Instead of filling in the infill density as a percentage, it’s also possible to set the line distance. This determines the distance between each infill line, which has the same effect as changing the fill density.

**Material**—Settings related to Material. Retraction is one property that can be set. At the places in a print where the printer has to do a travel move between two printed parts and you don’t want it to leave the plastic in between the use of retraction is important. This means that the filament is pulled back by the feeder, so that it doesn’t leak from the nozzle during the travel moves. By using retraction, “stringing” (thin threads of plastic in between the printed parts) is prevented, resulting in a much cleaner final model. You have to be careful with flexible materials or models that require a lot of retractions though, as that might lead to grinding of the filament.

**Speed**—Speeds at which the print head moves while printing.  The print speed defines at which speed (in mm/s) the print head moves while printing. Based on this setting, Cura will also calculate how fast the filament must be extruded. A higher print speed will lead to a shorter print time. But keep in mind that increasing the print speed means that you might have to increase the temperature as well, to ensure the plastic is properly melted.
Although you can choose one overall print speed for the complete print, it’s also possible to use different print speeds for specific parts of the print:
>> **Infill speed:** The speed at which the infill material is printed. Since (visual) quality of the infill is not important, you could use a higher speed for the infill. But keep in mind that this might affect the strength of your print.

>> **Wall speed:** The speed at which the walls are printed. You can also set the speed for the outer and inner wall separately. Printing the outer wall a bit slower usually results in a better surface finish.

>> **Top/bottom speed:** The speed at which the top and bottom layers are printed. A lower speed increases the reliability of closure of the top layers, especially on large area prints.

>> **Support speed:** The speed at which support structures are printed. The quality of the support is usually not that important, so a higher value can often be used here.

**Travel**—How the print head behaves while traveling.

**Cooling**—Settings that define how the plastic is cooled. You can enable or disable the print head fans during printing. The print head fans will make sure that the material is properly cooled before the next layer is placed on top of it. Especially on layers with a short layer time and layers with bridges/overhangs, cooling will increase the print quality.

**Support**—Options for support structures. Some models have overhanging parts, which means that parts of the model float mid-air when you would print the model. In this case, you must use a support structure under the model to prevent the plastic from falling down. This can be achieved by enabling support.

**Platform adhesion**—Options for how your model relates to the build plate. Options include Brim, Raft, and Skirt.

**Special modes**—Features that influence printing. These modes include print sequence, surface made, and spiralize outer contour.

**Experimental**—Experimental new features.  