## Bugfix and feature fork for ua's Aegisub scripts  

Manuals for all scripts: https://unanimated.github.io/ts/scripts-manuals.htm  

*Changelog:*  

* **[Snap](http://unanimated.hostfree.pw/ts/scripts-manuals.htm?#snap)** *\[Bugfix\]*: JoinSplitSnap will now snap to the closest keyframe if there are multiple keyframes in range.  
* **[Snap](http://unanimated.hostfree.pw/ts/scripts-manuals.htm?#snap)** *\[Feature\]*: You can now snap the start and the end of a line separately.  
* **[Blur And Glow](http://unanimated.hostfree.pw/ts/scripts-manuals.htm?#blurglow)** *\[Bugfix\]*: BlurAndGlow will no longer return out-of-bounds [selected_lines](https://web.archive.org/http://docs.aegisub.org/3.2/Automation/Lua/Registration/#macro-processing-function) when only add glow is selected.  
* **[NecrosCopy](http://unanimated.hostfree.pw/ts/scripts-manuals.htm?#necroscopy)** *\[Bugfix\]*: clip2frz and clip2fax will now accept subpixel clips thanks to [@petzku](https://github.com/petzku)'s commit [2d3a40](../../commit/2d3a400911c45b90b0a20d388332e4702e302c4f).  
* **[Cycles](http://unanimated.hostfree.pw/ts/scripts-manuals.htm?#cycle)** *\[Feature\]*: Cycles can now be edited inside Aegisub using [aka.config](https://github.com/Akatmks/Akatsumekusa-Aegisub-Scripts).  

*Other information:*

* **[HYDRA](https://unanimated.github.io/ts/scripts-manuals.htm#hydra)** *\[Note\]*: PhosCity has a script called [Edit Tags](https://github.com/PhosCity/Aegisub-Scripts/#edit-tags) that functions more or less similar to HYDRA but it will prefill the tags on the selected line when you open the GUI which is pretty convenient.  
