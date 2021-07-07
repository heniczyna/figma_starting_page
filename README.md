# [The Figma 2021 Crash Course by Example](https://www.youtube.com/watch?v=Gu1so3pz4bA)

This is first attempt to work with [Figma](https://www.figma.com/), tool for designing user interface.
* create your [Figma](https://www.figma.com/) account and login
* useful link [UI Goodies](http://www.uigoodies.com/)
  * background used [UI Goodies](http://www.uigoodies.com/) -> Patterns and backgrounds -> Subtle Patterns which leads to [this site](https://www.toptal.com/designers/subtlepatterns/?ref=uigoodies.com) -> [Greek Vase Pattern](https://www.toptal.com/designers/subtlepatterns/greek-vase-pattern/)
  * hero image -> in the tutorial it has been downloaded [Storefront Illustration](https://lukaszadam.com/illustrations?ref=uigoodies.com), however seems something has changed and there is no option to download this particular illustration (tutorial shows that it is possible to download this as zip file with `svg` file), there is only button saying `Download FREE Right Here` which redirects to [here](https://lukaszadam.gumroad.com/l/pBPJg) and requires some email address
    * when `svg` file has been unzipped, then he just drag-and-dropped from Desktop to Figma canvas and it appears as `Asset` 
* Figma plugins installed: Iconify, Lorem ipsum, Unsplash
* import ***1_design.fig*** to your account and explore the project, therefore:
  * download ***1_design.fig*** to your local disc drive,
  * after logging-in to Figma you will see **Import** icon in the upper right corner of the page, so hit it and choose the downloaded ***1_design.fig***,
  * that's all, should work straight away
* no local copy of the repo

First/landing page of the design:
![example_ui_design_1](https://raw.githubusercontent.com/heniczyna/figma_starting_page/main/example_ui_design.PNG)

Seems that relative links also work:
![example_ui_design_2](/example_ui_design.PNG)

# Useful functions of Figma
* Drag (resize) the frame (when you have large frame and want to tailor it to image inside the frame, useful when exporting and do not want to keep additional spaces around the image, I found it useful when playing aroung creating some logos, and when exporting I wanted to have only this logo without any margins on the top/bottom/left/right), so there are two interesting ways to do that:
  * manually: just change the size of the frame as you wish, just in the same way as you would do with rectangle, however keep `Ctrl` pressed to change frame size only, not the size of the image inside the frame [info](https://help.figma.com/hc/en-us/articles/360041539473-Frames-in-Figma#Drag_the_frame)
  * automatically: use button on the right hand side with four arrows pointing to the center (you can find it near to X, Y, width, height properties), it adjust frame to fit the content of the frame, or just hit this link [info](https://help.figma.com/hc/en-us/articles/360041539473-Frames-in-Figma#Resize_to_Fit) to see how this button looks like
  * I found that when image is rotated, then automatic resizing of the frame does not work in the way as I wish, therefore you should use manual resizing (automatic resizing takes the most outside corners of the rotated image and based on that resizes the frame, so when exporting there is too much additional space)
* Export image: just select the object you want to export on the left hand side (the pane with `Layers`, `Assets` and list of all object you have in your design) and go to right hand side and look for `Export` function, there is also `Preview` before exporting
* Select multiple objects: with `Shift`
* `Create component` function: when you create component, you have it visible in `Assets` tab (on the left hand side), the component is re-usable item, when you place few instances/copies of the component, and change something in `master` component (remember, in `master`, not in copies), then changes are visible in all copies of his `master` component (from tutorials I can see this is useful for example when you have few texts, and afterwards you want to change the color of all these texts, or useful when creating the buttons which should look like in similar way)
  * `master` component is marked as four diamonds, when copy of `master` component is marked as single diamond 
  * you can change something in copy of the `master` component (for example change line color from black to red), and when you change the same line in `master` component then your copy remains not changed! you can select you copy and then right click and hit `Reset all overrides` to have exactly the same copy of `master` component again
  * there is also useful view on the right hand side when copy of `master` components is selected which informs what is the `master` component for this copy
* Autoflow plugin (`Plugins` -> `Browse Plugins in Community` -> search for `Autoflow` -> `Install`)
  * this is for automatic drawing arrows between frames to create flowcharts
  * when you want to use this plugin after installation just hit `Plugins` -> `Autoflow`
