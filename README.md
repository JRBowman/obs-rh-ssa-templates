# Setup and Usage 
To setup these templates and resources in OBS, please do the following:
1. Clone GIT repository locally (or fork and clone)
2. In OBS on the top toolbar, select `Scene Collection` -> `Import`
3. Select `obs-rh-ssa-scene-collection.json` from the cloned GIT repo `..\obs-rh-ssa-templates\obs\scenes`
4. Upon `Import`, you'll be requested to "Search for Missing Files" -> Use the `Search` option and select the `..\obs-rh-ssa-templates\resources` folder.
5. Finally, with all resources and templates in place, Configure the `Sources` listed for the `sc-shared-resources` scene to work for your machine (i.e. update `cam-primary` -> `Properties` for your hardware)
6. To configure your `pr-nameplate-0`, please update the HTML source in `\resources\pr-nameplate-0.html`, there are `2` lines in the body to update, Name and Title.
7. Feel free to update any other resources / sources (background image, nameplate html, etc) and please contribute back to the repository!
