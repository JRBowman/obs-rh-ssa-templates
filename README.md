# Setup and Usage 
To setup these templates and resources in OBS, please do the following:
1. Clone GIT repository locally (or fork and clone)
2. In OBS on the top toolbar, select `Scene Collection` -> `Import`
3. Select `obs-rh-ssa-scene-collection.json` from the cloned GIT repo `..\obs-rh-ssa-templates\src\obs\scenes`
4. Upon `Import`, you'll be requested to "Search for Missing Files" -> Use the `Search` option and select the `..\obs-rh-ssa-templates\src\resources` folder.
5. Finally, with all resources and templates in place, Configure the `Sources` listed for the `sc-shared-resources` and specific scenes to work for your machine (i.e. update `bg-layer-0` -> `Properties` for the background on all scenes... update `cam-primary` in the `sc-primary-0` to use your proper camera device, etc.)
6. To configure your `pr-nameplate-0`, please update the HTML source in `\resources\pr-nameplate-0.html`, there are `2` lines in the body to update, Name and Title.
7. To configure your `off-cam` scene for your Profile Picture, Name, and Title -> update `\resources\rh-frame.html` on `line 19`.
```
# Update with your Profile Picture converted to Base64 as below:
<img class="rh-profile-picture" src='data:image/png;base64,[base 64 image data here]' alt="Profile Picture"/>
...
# Insert your name and title further down in rh-frame.html:
<text class="text" x="312" y="72">Name</text>
<text class="subtext" x="312" y="144">Title</text>
```
8. Feel free to update any other resources / sources (background image, nameplate html, etc) and please contribute back to the repository!
