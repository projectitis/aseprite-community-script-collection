# Aseprite community scripts collection

The is a collection of scripts from the Aseprite community, originally collected by [@JJHagger](https://community.aseprite.org/u/JJHaggar/summary) from the [Aseprite forums](https://community.aseprite.org/c/scripts/13).

Aseprite is working on an official database of scripts and extensions (including a store). In the meantime, this is the unofficial home of this collection.

If you have a script that you'd like to contribute, complete the form to [submit a script](https://github.com/projectitis/aseprite-community-script-collection/issues/new?assignees=projectitis&labels=&projects=&template=submit-a-script.md&title=%5BScript%5D+My+script+name).

- [How to install a script](#how-to-install-a-script)
- [How to create a scrip](#how-to-create-a-script)
- [Scripts collection](#scripts-collection)
- [Submit a script](https://github.com/projectitis/aseprite-community-script-collection/issues/new?assignees=projectitis&labels=&projects=&template=submit-a-script.md&title=%5BScript%5D+My+script+name)

## How to install a script

1. Download the script (scripts are files with .lua extension, so if you download them as a .zip file you will need to uncompress them)
2. Open the user script folder 1.1k
    
    ![Open the scripts folder](/images/screenshot-scripts-folder.png)

3. Copy the script in that folder (if you want you can also create folders there for organisation)
4. Restart Aseprite
5. Then you will be able to access to that script from the File > Scripts > YourScriptName menu option
6. You can also create a Keyboard Shortcut for each script that you want from the Edit > Keyboard Shortcuts menu (type “script” in the search box to find them easily)

    ![Keyboard shortcuts](/images/screenshot-shortcuts.png)

## How to create a script

1. You should know how to program a little bit, or at least don’t be scared of trying :)
2. Learn a bit about Lua:  
    2.1 [all you need to know about Lua](https://www.lua.org/pil/contents.html).  
    2.2 [online tester for normal Lua code](https://www.lua.org/demo.html).
3. Aseprite scripting API:  
    3.1 [on GitHub](https://github.com/aseprite/api)  
    3.2 [on Aseprite.org](https://www.aseprite.org/api/)
4. Get help from a (free) LLM (they can teach you and also help you fix bugs):  
    4.1 [Anthropic’s Claude](https://claude.ai/chats)  
    4.2 [Google’s Gemini](https://gemini.google.com/app)  
    4.3 [OpenAi’s ChatGPT](https://chat.openai.com/)  
    4.4 Local (Open Source) models using [Ollama](https://ollama.com/)

## Scripts collection

[Touch Toolbar helper](https://community.aseprite.org/t/touch-toolbar-helper/2169) by [dacap](https://community.aseprite.org/u/dacap) ([Link to file](https://gist.githubusercontent.com/dacap/e470b917c343af38e84b81cb642b85d3/raw/f83d6b1f64a6fea5923ef52d1c6268a18b41ab1c/Touch%2520Toolbar.lua))
A simple example script that shows how to create a dialog with buttons on it.

`example`

---

[Slice](https://community.aseprite.org/t/aseprite-slice-script/3130) by [molingyu](https://community.aseprite.org/u/molingyu) ([GitHub](https://github.com/molingyu/AsepriteScript))
Slice a sprite by cell size or by count. Similar to the slice tool in the Unity sprite editor.

`sprite sheet`

---

[Displacement](https://community.aseprite.org/t/script-displacement/3438) by [heidi](https://community.aseprite.org/u/heidi) ([GitHub](https://github.com/Heidi-Potato/scripts-for-asesprite))
A script for tile randomization that randomly moves about pixels as per given probabilities.

`tile`

---

[Timer script](https://community.aseprite.org/t/script-timer-script/2594) by [goustkor](https://community.aseprite.org/u/goustkor) ([GitHub](https://github.com/goustkor/Aseprite-Scripts))
A counter to time how long it took to create a sprite.

---

**Multi Color Replacer** by [goustkor](https://community.aseprite.org/u/goustkor) ([GitHub](https://github.com/goustkor/Aseprite-Scripts))
Select multiple color replacements (**from** and **to**) and perform them all at once.

`palette`

---

[Pixel Stats](https://community.aseprite.org/t/pixel-stats-check-the-total-amount-of-colored-pixels-you-used-in-your-art/1897) by [haloflooder](https://community.aseprite.org/u/haloflooder) ([GitHub](https://github.com/haloflooder/Aseprite-Scripts/releases))
Calculates and summarizes the total number of pixels for each color (including %).

`metrics`

---

[NxPA Studio](https://thkaspar.itch.io/nxpa) by [Kacper Woźniak aka thkaspar](https://thkaspar.itch.io) ([Demo (on twitter)](https://twitter.com/thkasparrr/status/1058795230382747649))
This is a powerful script suite that consists of:

- **Scale**: a script that allows for upscaling pixel art without introducing new colors using a variety of algorithms: Nearest Neighbor, Eagle, Scale2x and a custom algorithm named Hawk.  
- **Tween**: a script for effortless animation inbetweening based on position.  
- **Note**: a to-do list app inside [Aseprite](https://dacap.itch.io/aseprite). 

`transform` `tween`

---

**Various Aseprite scripts** by [Chris Anselmo aka christopherwk210](https://github.com/christopherwk210) ([GitHub](https://github.com/christopherwk210/aseprite-scripts))

- **image/color-overlay.lua**: Overwrites all non-transparent pixels in the current layer with any given color/opacity. Can be applied to the current layer or to a new layer.  
- **image/stroke.lua**: Outlines all non-transparent pixels in the current layer with any color and width. Can be applied to the current layer or to a new layer.  
- **timeline/add-frame-background.lua**: Adds a new frame to the timeline, copying cels from every layer but the active one. Useful when working on animations with a background.  
- **misc/midi.lua**: Generates a piece of music based on the colors in the current cel image, and outputs the result into a midi file ([midi demo](https://twitter.com/tophtacular/status/1060201985184432130))

`outline` `audio`

---

**Generate normal map** by Rucho/るっちょ‏ @ruccho\_vector ([Demo (twitter)](https://twitter.com/ruccho_vector/status/1103488054604386305), [for one frame](https://gist.github.com/ruccho/efa1139ddd6da6d4d22def161209d2e7), [for all frames](https://gist.github.com/ruccho/2d1eb4aea3dfa55690c2ddc4419172ff))
Generates a normal map automatically from one frame or from all frames of selected layers.

`normal map`

---

**Parallax tool** by [Hazel Quantock aka TekF](https://github.com/TekF) ([Demo (twitter)](https://twitter.com/TekF/status/1145372742264512513), [GitHub](https://github.com/TekF/Aseprite-Scripts))
Shows controls to move layers in the editor to give a parallax effect. By default each layer moves twice as fast as the one below, but this can be customized.

`parallax`

---

**Isometric Box Generator** by [Kamil ‏@darkwark](https://twitter.com/darkwark) ([Demo (twitter)](https://twitter.com/darkwark/status/1061343439957229568), [GitHub](https://github.com/darkwark/isobox-for-aseprite), [itch.io](https://darkwark.itch.io/isobox-for-aseprite))
Generate isometric boxes at custom sizes, either filled or wireframe. Select colors for each of the sides, set a highlight and stroke color and corner style (2px and 3px).

`isometric`

---

**C64 helper scripts** by [Viza74](https://github.com/Viza74) ([GitHub](https://github.com/Viza74/c64helperscriptsforaseprite))
A collections of scripts, including:

- Various checks to ensure the sprite meets C64 multicolor rules
- Various checks to ensure the sprite meets C64 hires rules
- Importing and exporting Koala format

`c64` `export` `import`

---

**Color, Hue and Shade Scripts** by [aquova](https://github.com/aquova) ([GitHub](https://github.com/aquova/aseprite-scripts))

- **Color Compliment**: Asks for a single color and returns the HSV color compliment according to the color wheel.  
- **Hue Generator**: Asks for two colors and the number of intermediate colors you wish to generate. The script will then give a window with a range of colors between the two that were given.  
- **Shade Generator**: Will give a range of shades brighter and darker than the color that is given, ranging from black up to white.

`color`

---

**Antialias and Outline** by [rikfuzz](https://github.com/rikfuzz) ([GitHub](https://github.com/rikfuzz/aseprite-scripts))

- **Antialias**: Antialiases inside the foreground colour anywhere it touches the background colour ([Link to file](https://github.com/rikfuzz/aseprite-scripts/blob/master/antialias.lua))
- **Outline**: Outlines current layer with 1px of fg colour ([Link to file](https://github.com/rikfuzz/aseprite-scripts/blob/master/outline.lua))

`antialias` `outline`

---

**Various scripts** by [Cotu41](https://github.com/Cotu41) ([GitHub](https://github.com/Cotu41/AsepriteScripts))

- **Fill non-transparent**: Fills all the non-transparent pixels in a layer with the current foreground color ([Link to file](https://github.com/Cotu41/AsepriteScripts/blob/master/fillNonTransparent.lua))
- **Moving scanlines**: Scanline effect ([Link to file](https://github.com/Cotu41/AsepriteScripts/blob/master/movingScanLines.lua))

---

**Various scripts** by [alexpennells](https://github.com/alexpennells) ([GitHub](https://github.com/alexpennells/AsepriteScripts))

- **Image border**: Creates a new layer with a 1 pixel wide border around the current image for all frames ([Link to file](https://github.com/alexpennells/AsepriteScripts/blob/master/Image%20Border.lua))
- **Layer border**: Creates a new layer with a 1 pixel wide border around the current image for all frames ([GitHub](https://github.com/alexpennells/AsepriteScripts/blob/master/Layer%20Border.lua))
- **Group border**: Creates a new layer with a 1 pixel wide border around the current image for all frames ([GitHub](https://github.com/alexpennells/AsepriteScripts/blob/master/Group%20Border.lua))
- **Save all frames**: Exports all frames as images, grouped by tag ([GitHub](https://github.com/alexpennells/AsepriteScripts/blob/master/Export%20All%20Frames.lua))

`outline` `export`

---

**APNG reader/decoder** by [kettek](https://github.com/kettek) ([GitHub](https://github.com/kettek/aseprite-scripts))
Not currently working. APNG reader and writer

`import` `export`

---

**Isometric Guidelines** by [oscb](https://github.com/oscb) ([GitHub](https://github.com/oscb/aseprites-scripts))
Generates isometric guidelines and adds them to a new layer

`isometric` `guide`

---

**Mask layer-like extensions** by [masakazu-k](https://github.com/masakazu-k) ([GitHub](https://github.com/masakazu-k/aseprite-scripts))
Adds the mask layer-like functionality to Aseprite. Use the MergedCopy function to cut out the mask area specified in the mask layer.

`mask`

---

**aseprite-xcolor** by [steven-kraft](https://github.com/steven-kraft) ([GitHub](https://github.com/steven-kraft/aseprite-xcolor))
An external color picking script for Aseprite using [xcolor](https://github.com/Soft/xcolor) by Soft. Allows you to pick colors from outside of the Aseprite application. Currently only tested on Linux.

`color`

---

**Aseprite-Export-Tags** by [StarJackal57](https://github.com/StarJackal57) ([GitHub](https://github.com/StarJackal57/Aseprite-Export-Tags))
Exports the tags of the active Aseprite sprite and exports as a horizontal png strip. The file is labeled with the proper suffix to make import into Game Maker projects much simpler.

`export`

---

**PixeLips** by [BoThompson](https://github.com/BoThompson) ([GitHub](https://github.com/BoThompson/pixeLips))
An Aseprite Script Plugin to support Papagayo files to animate Lipsyncing

`animation`

---

[Color Shading](https://community.aseprite.org/t/script-more-color-shading-options/3668) by [domjohn](https://community.aseprite.org/u/domjohn) ([GitHub](https://github.com/dominickjohn/aseprite/))
An Aseprite Script to open a dialog with relevant color shades.

`color`

---

[Export sprite’s layers as individual images](https://community.aseprite.org/t/script-linux-export-sprites-layers-as-individual-images/3679) by [Gaspi](https://community.aseprite.org/u/gaspi/summary) ([Github](https://github.com/PKGaspi/AsepriteScripts))
Scripts to export layers or slices on a sprite as individual png images with their own name and on a specific folder.

`export`

---

**Listing and removing all slices** by [Jonathan Smårs (jsmars on twitter)](https://twitter.com/jsmars/status/1193812885853671429) ([GitHub](https://github.com/jsmars/DevTools))
Creates a list of all the slices in your document and allows you to delete them (even corrupt slices that do not show up in the view)

---

**Screen color picker for Windows** by [endlesstravel](https://community.aseprite.org/u/endlesstravel) ([Project](https://gitee.com/endlesstravel/Aseprite-Sprite-Win-ColorPicker), [Download](https://gitee.com/endlesstravel/Aseprite-Sprite-Win-ColorPicker/releases))
Needs .Net 4.6.1+. Escape to exit, mouse click to pick color (change bg, change fg, add color to palette).

`palette`

---

**1-Point Perspective Helper** by [GunTurtle (itch.io)](https://gunturtle.itch.io/) ([itch.io](https://itch.io/queue/c/565204/aseprite?game_id=445017))
A lua script for Aseprite that quickly generates single point perspective.

`perspective` `guide`

---

**Export to PSD** by [Tsukina\_7mochi (twitter)](https://twitter.com/Tsukina_7mochi) ([GitHub](https://github.com/Tsukina-7mochi/aseprite-scripts))
This script is used to export to Photoshop’s .psd format from Aseprite If you have problems opening the exported PSD, you can try using [this revision of the script file](https://raw.githubusercontent.com/Tsukina-7mochi/aseprite-scripts/c19e025246955b8008773d54759821667cb1727f/psd/Export%20as%20PSD.lua) (right click on the link and choose “save link as”).

`export`

---

**Cycling keyboard shortcut** by [Gasparoken](https://community.aseprite.org/u/Gasparoken)
You can associate a keyboard shortcut to a script, and you can also make that script cycle between tools, brushes, etc. [How to create a cycling keyboard shortcut](https://community.aseprite.org/t/how-to-create-a-cycling-keyboard-shortcut/4732)

---

**Export Tags to Gif** by [ThunderFD](https://github.com/ThunderFD) ([GitHub](https://github.com/ThunderFD/Thunders-Aseprite-Scripts))
It exports all tags as individual gifs

`export`

---

**Bulk rename Tags** by [Arkogelul](https://community.aseprite.org/u/Arkogelul), [dacap](https://community.aseprite.org/u/dacap), [JJHaggar](https://community.aseprite.org/u/jjhaggar) ([Link to file](https://github.com/jjhaggar/Aseprite-Add-on-Collections/tree/master/scripts/bulk-rename-tags))
This script can find & replace strings, and add prefixes or suffixes for tags in ase files.

---

**Note**: I've been reformatting this list, and have got to here so far. The scripts below just haven't been put into this nicer format yet, but are all still available. Just harder to read.


*   [Change the palette of several sprites](https://community.aseprite.org/t/change-the-palette-of-several-sprites/4299) (by [dacap](https://community.aseprite.org/u/dacap)): _(_**Before using these scripts create a backup of your sprites**_)_.
*   [Copy Merged Scaled](https://community.aseprite.org/t/script-copy-merged-scaled/4849) (by [YellowAfterlife](https://community.aseprite.org/u/YellowAfterlife)): Copy a merged version of the sprite layers, and also scale it up so that you can paste it wherever to show it to people
*   [Rotation tweening](https://community.aseprite.org/t/rotation-tweening-on-aseprite-lua-script/4982) (by [Gasparoken](https://community.aseprite.org/u/Gasparoken)): [Youtube video](https://www.youtube.com/watch?v=hDwW-9_sIzo), Script [here](https://gasparoken.itch.io/aseprite-rotation-script).
*   Mark cels based on frame duration, or manually (by [libroumque](https://twitter.com/librorumque/status/1179466036392931330)): Original [tweet](https://twitter.com/librorumque/status/1179466036392931330), view it [on github](https://gist.github.com/dotbread/26ad91dd92a67f8ab7ef0d80eb5fd4f6) or [download the script](https://gist.github.com/dotbread/26ad91dd92a67f8ab7ef0d80eb5fd4f6/raw/a4867dcc20530f9146d32028d482ce57c14058a3/Highlight%2520Cels.lua). **UPDATE**: GitHub Link’s dead, but script was rescued thanks to [V972](https://community.aseprite.org/u/V972) [here](https://community.aseprite.org/t/aseprite-scripts-collection/3599/58) - link to Google Drive [here](https://drive.google.com/file/d/1RNyY_SheXV2daMTp0LOn1OhgS_AYVXJv/view).
*   Record (by [sprngr](https://community.aseprite.org/u/sprngr)): Is a suite of LUA scripts for taking incremental snapshots of your sprite for the purpose of making a time lapse/progress gif. Links: [itchio](https://sprngr.itch.io/aseprite-record) and [github](https://github.com/sprngr/aseprite-record).
*   [Aseprite Mega Drive Digitizer](http://gendev.spritesmind.net/forum/viewtopic.php?t=3112) (by themrcul): Gets art directly and immediately from Aseprite to the Mega Drive (to be exact, to a Mega Everdrive X7 connected via USB) . Links: [MegaDriveDraw Release 1.zip](http://gendev.spritesmind.net/forum/download/file.php?id=354) and [MegaDriveDraw Release 2.zip](http://gendev.spritesmind.net/forum/download/file.php?id=355).
*   [Center the current selection on the sprite](https://community.aseprite.org/t/centralization-tool/5474/2) (by [tuxpup](https://community.aseprite.org/u/tuxpup)): It takes the current selection and centers it on the current canvas. Link to repo: [~tuxpup/asesprite-script-center-selection - "Center Selection" script for asesprite - sourcehut git](https://git.sr.ht/~tuxpup/asesprite-script-center-selection)
*   [Reduce the bit-depth of the palette](https://community.aseprite.org/t/aseprite-scripts-collection/3599/26) (by [sandor](https://community.aseprite.org/u/sandor)): It reduces the bit-depth of the palette colors. Link to repo: [aseprite-scripts/Reduce palette bit-depth.lua at master · sandord/aseprite-scripts · GitHub](https://github.com/sandord/aseprite-scripts/blob/master/Reduce%20palette%20bit-depth.lua)
*   [Import tags from exported JSON](https://community.aseprite.org/t/aseprite-scripts-collection/3599/27) (by [jest](https://community.aseprite.org/u/jest)): It Imports existing tags from the exported JSON. That’s useful so you don’t have to re-tag every animation for similar sprites. [Link to repo](https://github.com/jestarray/aseprite-scripts/blob/master/Import_Existing_Tags.lua)
*   [EGA dithering script](https://community.aseprite.org/t/ega-dithering-script/5405) (by [Dan\_Beeston](https://community.aseprite.org/u/Dan_Beeston)): This script sets your image to a blended EGA palette then dithers it to the original EGA palette. [Youtube Video](https://www.youtube.com/watch?v=9VAwc5yeiSQ) - Download link: [https://invisiblespiders.com/egaify.zip](https://invisiblespiders.com/egaify.zip)
*   [Export to GameBoy format](https://community.aseprite.org/t/script-gameboy-export/5266) (by [boombuler](https://community.aseprite.org/u/boombuler)): It exports the current sprite to gameboy assembly. Link to repo: [GitHub - boombuler/aseprite-gbexport: a gameboy sprite export script for aseprite](https://github.com/boombuler/aseprite-gbexport)
*   [Path Animator](https://community.aseprite.org/t/aseprite-scripts-collection/3599/37) (by [Gasparoken](https://community.aseprite.org/u/Gasparoken)): A tool for animating an image (multi-layer allowed) according a desired path - Repository [here](https://github.com/Gasparoken/asepriteScripts/tree/master/PathAnimator).
*   [Merge All tags](https://community.aseprite.org/t/aseprite-scripts-collection/3599/40) (by [jest](https://community.aseprite.org/u/jest)): It will just combine all your open tabs into 1 spritesheet… [Link to repo](https://github.com/jestarray/aseprite-scripts/blob/master/jest_merge_all_tabs.lua)
*   [non-empty cels counter](https://community.aseprite.org/t/aseprite-scripts-collection/3599/45) (by [Unknow0059](https://community.aseprite.org/u/Unknow0059)): It displays the total number of non-empty cels from visible layers. Or, in naive terms, the total frame count.
*   [Perlin Noise Generation](https://community.aseprite.org/t/aseprite-scripts-collection/3599/46) (by [Ondrej\_Pokorny](https://community.aseprite.org/u/Ondrej_Pokorny)): It generates perlin noise, that can be used for water/clouds textures. Scritp for generation of normal maps is in repository as well - [link to repo](https://github.com/Ondra09/AseWave)
*   [Aseprite Scripts](https://community.aseprite.org/t/aseprite-scripts-collection/3599/47) by [David\_Barker](https://community.aseprite.org/u/David_Barker)  
    **Ghost Images :** Animation effect similar to onion skinning. The script will generate a new layer containing a number of ‘Ghosts’ of previous frames.  
    **Layer Transition :** Generates a new layer with a simple transition effect between two existing layers.  
    **Load Palette From CSV :** Load a palette from a CSV file with red, green, blue, alpha columns.  
    **Save Palette To CSV :** Save current palette To CSV file with red, green, blue, alpha columns.  
    **Selected Pixel Count :** Counts the number of pixels in an arbitrary shaped selection.  
    Github repo [https://github.com/davebarkeruk/Aseprite\_LUA\_Scripts](https://github.com/davebarkeruk/Aseprite_LUA_Scripts)
*   [MSX image file import v1.0](https://community.aseprite.org/t/extension-msx-image-file-import/8655/2) (by [NataliaPC](https://community.aseprite.org/u/NataliaPC)): It imports MSX image files. - [Github repo](https://github.com/nataliapc/aseprite_msx/releases/tag/v1.0)
*   [PalRowMax](https://community.aseprite.org/t/aseprite-scripts-collection/3599/50)(by [BraidAcer](https://community.aseprite.org/u/BraidAcer)): It scans an indexed color image and tell you if you’ve used more than X palette colours in a single pixel height horizontal line - link to [drive](https://drive.google.com/file/d/13sJzyBVmaX0Lu0auqGOP2AZoyEQoBcqA/view).
*   [Simple Color Range Multi-Select Noodle – SCRMSN](https://community.aseprite.org/t/aseprite-scripts-collection/3599/55) (by [J19](https://community.aseprite.org/u/J19)): It lets you select colors continuously instead of one-by-one like you had to do with the built-in tool: select-> color range. [Available (for free) on itch.io](https://j-19.itch.io/scrmsn).
*   **UPDATE**: GitHub Link’s dead, but script was rescued thanks to [V972](https://community.aseprite.org/u/V972) [here](https://community.aseprite.org/t/aseprite-scripts-collection/3599/58) - link to Google Drive [here](https://drive.google.com/file/d/1RNyY_SheXV2daMTp0LOn1OhgS_AYVXJv/view).
*   [Noise](https://community.aseprite.org/t/aseprite-scripts-collection/3599/59) (by [shemake](https://community.aseprite.org/u/shemake)): By default, it will create a new layer and scatter it with single pixel dots in your current foreground color. You can control the density with the first script option (higher numbers = LOWER density). Even better, if you want to create noise using a brush, all you have to do is choose the “Use current brush” checkbox and the script will apply the brush anywhere it would have created a speck of noise. - [link to github](https://shemake.dev/tech/viewing/Aseprite_makeNoise)
*   [Find Orphan](https://community.aseprite.org/t/aseprite-scripts-collection/3599/60) (by [shemake](https://community.aseprite.org/u/shemake)): It will find orphan pixels. - [link to github](https://shemake.dev/tech/viewing/Aseprite_findOrphans)
*   [Import Images from a folder Into New Layers](https://community.aseprite.org/t/aseprite-scripts-collection/3599/61) (by [JJHaggar](https://community.aseprite.org/u/JJHaggar), me XD): It imports images from a folder into new layers. [Link to repo](https://bitbucket.org/jjhaggar/aseprite-scripts/src/master/import_images_as_layers/)
*   [Auto Mirror](https://community.aseprite.org/t/aseprite-scripts-collection/3599/65) (by [semplar](https://community.aseprite.org/u/semplar)): UIt helps with seamless tiles of any shape, like isometric ones. [Link to repo](https://github.com/semplar2007/aseprite-scripts/blob/main/AutoMirror.lua)
*   [Asesprite-TF-Atlas-Editor](https://community.aseprite.org/t/aseprite-scripts-collection/3599/66) (by [CoolModder](https://community.aseprite.org/u/CoolModder)): Script for editing XML atlases for Towerfall - [Link to repo](https://github.com/CoolModder/Asesprite-TF-Atlas-Editior/tree/main)
*   [Memo](https://community.aseprite.org/t/aseprite-scripts-collection/3599/67) (by [CoolModder](https://community.aseprite.org/u/CoolModder)): Script for viewing txt, xml, and json files. Editing not supported - [Link to repo](https://github.com/CoolModder/Memo)
*   [Aseprite Export Tooling](https://community.aseprite.org/t/aseprite-scripts-collection/3599/69) (by [emscape](https://community.aseprite.org/u/emscape)): Extension for exporting spritesheets / frames + layers as seperate images - [Link to file (for free) on Patreon](https://www.patreon.com/posts/aseprite-export-96589806).
*   [Paint Drip](https://community.aseprite.org/t/aseprite-scripts-collection/3599/73) (by [emscape](https://community.aseprite.org/u/emscape)): script to create a Paint Drip animation - [Link to file (for free) on Patreon](https://www.patreon.com/posts/98988171).
*   [Emphasise layers](https://community.aseprite.org/t/aseprite-scripts-collection/3599/74) (by [emscape](https://community.aseprite.org/u/emscape)): script to emphasise your working layer within aseprite. With this you can finally see well what you’re doing when working with complex sprites - [Link to file (for free) on Patreon](https://www.patreon.com/posts/aseprite-layers-99381205)
*   [Isometric Tiles](https://community.aseprite.org/t/aseprite-scripts-collection/3599/75) (by [motero2k](https://community.aseprite.org/u/motero2k)): a script for isometric “tiled mode”. It clones the selection to see how the texture fits - [Link to file](https://github.com/motero2k/aseprite-scripts)
*   [Palettize: Better control when applying a palette](https://community.aseprite.org/t/script-palettize-better-control-when-applying-a-palette/21823) (by [Projectitis](https://community.aseprite.org/u/Projectitis)): Load a palette and preview your image with that palette. Adjust HSV sliders for each color channel until you are happy with the mapping before applying it - [Link to repo](https://github.com/projectitis/aseprite-script-palettize)

---

[DNS Exporter](https://community.aseprite.org/t/doom-style-sprite-exporter/21240) by [TheSartremaster](https://community.aseprite.org/u/thesartremaster/summary) ([GitHub](https://github.com/jvornhagen/DoomStyleSpriteExporterForAseprite))
This script allows automatically exporting of Aseprite files following the DOOM naming conventions. E.g. An image with 3 frames will be exported as POSSA0, POSSB0, POSSC0. Allows setting the sprite angles, mirroring, custom export range and starting letter.

`export`
