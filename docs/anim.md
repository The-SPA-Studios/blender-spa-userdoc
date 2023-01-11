
# Quick Start Guide

## Introduction

Blender is a 3D program with a 2D package built-in. Some voices can be heard saying that Blender *looks very complicated*, but it is in fact a very streamlined and simple program even for 2D Animation. At least we are working at making it so.

At SPA we are developing our own studio-specific Blender with a set of UI changes and tools to ease newcomers to it and continue refining its capabilities based on your direct production feedback.
**This document aims to give you the basic knowledge to quickly start Animating with the SPA version of Blender**.

Let's get started.

- - - - - -

## Install and launch Blender SPA

TODO: Write launch instructions for the outside world.


- - - - - -

## Open SPA 2D Animation Template

The first time you launch Blender you will be see the Blender Splash Screen. On the right is a list of recent files, on the left is templates to create a new file from. To get started in the SPA Animation experience select **`SPA 2D Animation`** template.

[![image-1664807871795.png](./images/gallery/2022-10/scaled-1680-/image-1664807871795.png)](./images/gallery/2022-10/image-1664807871795.png)

After launching the template you will see the default SPA Animation workspace. This workspace is opened on a drawing canvas in Draw Mode, you can now begin drawing your first keyframe.

[![image-1657903375268.png](./images/gallery/2022-07/scaled-1680-/image-1657903375268.png)](./images/gallery/2022-07/image-1657903375268.png)

#### Return to the Splash Screen

You can always re-open the Splash Screen by using the **Blender Logo &gt; Splash Screen** in the top right corner of your Blender window. This will re-open the Splash Screen which usually appears when you first launch Blender.

[![image-1658157480319.gif](./images/gallery/2022-07/image-1658157480319.gif)](./images/gallery/2022-07/image-1658157480319.gif)

- - - - - -

## Interface Basics

- **<span style="color: #339966;">Green: Toolbar</span>** This area contains tools like the Draw tool, Eraser tool and the Quick Edit tool.
- **<span style="color: #ffcc00;">Yellow: Drawing Space </span>**This area is your canvas for drawing.
- **<span style="color: #0000ff;">Blue: Timeline/Dope Sheet </span>**The Dopesheet is where animation keyframes can be viewed/moved
- **<span style="color: #ff0000;">Red: Quick Access Panel </span>**The Quick Access panel is where you will find shortcuts for most Animation work

[![image-1657904098763.png](./images/gallery/2022-07/scaled-1680-/image-1657904098763.png)](./images/gallery/2022-07/image-1657904098763.png)

- - - - - -

## Navigation

<p class="callout info">Middle Mouse Action will in the future be set by default for artists launching Blender, temporarily please follow the below procedure to ensure you have the correct navigation settings.</p>

#### <span style="font-weight: 400;">Set your Middle-Mouse Preference right!</span>

<span style="font-weight: 400;">By default the Middle Mouse Button in Blender will Orbit around your object in 3D Space, </span> **which is not desirable for 2D artists.**

<span style="font-weight: 400;">Before you start, Open </span>**Edit&gt;Preferences** <span style="font-weight: 400;">find the </span>**Keymap**<span style="font-weight: 400;"> section from the sidebar of the preferences window. And set </span>**Middle Mouse Action**<span style="font-weight: 400;"> to </span>**Pan**<span style="font-weight: 400;"> as the default *(instead of Orbit).* </span>

[![image-1663764556118.gif](./images/gallery/2022-09/image-1663764556118.gif)](./images/gallery/2022-09/image-1663764556118.gif)

- - - - - -

#### Basic Navigation of your Canvas

<span style="font-weight: 400;">To quickly navigate your scenes, Blender has some handy keyboard shortcuts. These come in the form of </span>**Zoom, Pan,** <span style="font-weight: 400;">and</span> **Rotate Canvas**<span style="font-weight: 400;"> Shortcuts.</span>

<span style="font-weight: 400;">Also do not forget to press the </span>**ESC** <span style="font-weight: 400;">key if you get lost or performed an operation you are not sure about and want to get out of. Or press the camera icon to get back to default view</span>

[![image-1663950702909.gif](./images/gallery/2022-09/image-1663950702909.gif)](./images/gallery/2022-09/image-1663950702909.gif)

1. **Pan:** Move your Pen/Mouse ***Left and Right*** or ***Up and Down*** while Holding Down the **Middle Mouse Button** to pan the Canvas
2. **Zoom:** Move your Pen/Mouse ***Up and Down*** while Holding Down **CTRL + Middle Mouse Button**  to zoom in/out
3. **Rotate Canvas:** Move your Pen/Mouse and Hold Down **SHIFT** + **CTRL + Middle Mouse Button**,
    - Use **CTRL + SHIFT + R** or the Blue Rest Icon in the lower center of your screen to reset your Rotated Canvas
4. **Mirror Canvas:** **SHIFT+ W** to mirror canvas at the current views center. **SHIFT+W** again to reset.

- - - - - -

## Your first strokes

To begin drawing in Blender simply start drawing in the Drawing Space/Canvas area. Use the Dope Sheet to navigate to a new frame and use `I` on your keyboard to insert a keyframe.

[![image-1657909444755.gif](./images/gallery/2022-07/image-1657909444755.gif)](./images/gallery/2022-07/image-1657909444755.gif)


#### **Radius**

The **Radius** of a **Brush** can be controlled in the Header menu. The use pressure button allows for tablet pressure inputs on the **Radius**. You can quickly adjust the **Radius** with “F” on the Keyboard. Under the **Tools&gt;Brush Settings&gt;Radius** menu a custom curve can be set for the strength for more precise control.

[![image-1649075753919.png](./images/gallery/2022-04/scaled-1680-/image-1649075753919.png)](./images/gallery/2022-04/image-1649075753919.png)

#### **Strength**

The **Strength** is how Dark the stroke is, this can also be controlled by pen pressure. To set the **Strength**, edit it in the header menu, under the tools panel or use the keyboard shortcut SHIFT+F. Under the panel **Tools&gt;Brush Settings&gt;Strength** menu a custom curve can be set for the strength for more precise control.

[![image-1649075758465.png](./images/gallery/2022-04/scaled-1680-/image-1649075758465.png)](./images/gallery/2022-04/image-1649075758465.png)

- - - - - -

## Changing Colors

In the Quick Access Panel under the header **Colors** is a menu to select different colors for your drawing. Simply select one of the preset colors and continue drawing in the newly selected color!

[![image-1657909796909.gif](./images/gallery/2022-07/image-1657909796909.gif)](./images/gallery/2022-07/image-1657909796909.gif)

## Erase a Stroke

To remove a stroke with the Eraser tool, select the **Eraser** from the Toolbar on the left. You can now erase strokes, use the **Strength** to adjust how effective your Eraser is. Select the **Stroke** option to quickly erase entire strokes.

[![image-1657909947468.gif](./images/gallery/2022-07/image-1657909947468.gif)](./images/gallery/2022-07/image-1657909947468.gif)


- - - - - -

## Edit a Stroke

To Edit a stroke, find the Quick Select tool on the left Toolbar area. Using the Quick Edit tool users can manipulate strokes. This transform box works similar to transform boxes in other 2D Animation software.

[![image-1657910344557.gif](./images/gallery/2022-07/image-1657910344557.gif)](./images/gallery/2022-07/image-1657910344557.gif)

*To learn more see [Quick Edit Tool](#quick-edit-tool) doc.*

- - - - - -

## Enable SPA Theme

Dopesheet now has an updated look over vanilla blender to make it easier to read. You must have the **SPA Theme** enabled to do this follow the [Enable SPA Theme page](#enable-spa-theme).

[![image-1664807667681.gif](./images/gallery/2022-10/image-1664807667681.gif)](./images/gallery/2022-10/image-1664807667681.gif)

1. Navigate to **Edit&gt;Preferences**
2. Open the **Theme** tab
3. Select the SPA theme from the **Dropdown**

- - - - - -

## Navigating Between Drawings

There are several ways to switch the active layer, it can be selected from the Drawing Box or the Dope Sheet area, as shown in [Layer Management. ](#layer-management)To jump between layers and grease pencil objects in the viewport we have the shortcuts **CTRL+SHIFT+CLICK** and **ALT+CLICK.**

#### **From the Viewport**

[![image-1664804878597.gif](./images/gallery/2022-10/image-1664804878597.gif)](./images/gallery/2022-10/image-1664804878597.gif)

1. Enabled **Fade Inactive Objects** + **Grease Pencils** from the overlays menu
2. Enabled **Fade Inactive Layers** from the overlays menu
    - Users can adjust the Fade opacity of inactive objects (set to .5 by default)
3. Hover your Mouse/Pen over the stroke of an inactive drawing
4. **Ctrl+Shift** and **Click** to make inactive drawing active
5. **Alt + Click** to make an inactive layer in the current drawing active

#### **From the Dope Sheet**

[![image-1664898293798.gif](./images/gallery/2022-10/image-1664898293798.gif)](./images/gallery/2022-10/image-1664898293798.gif)

1. Ensure you have **Sync Selection [![image-1664804731263.png](./images/gallery/2022-10/scaled-1680-/image-1664804731263.png) ](./images/gallery/2022-10/image-1664804731263.png)**enabled in the Dopesheet header.
2. Select different layers in the Dopesheet the active object will update.

- - - - - -

## Always show Active Drawing in Dope Sheet

In Blender there is a a concept between active and selected. This means it is possible to have a drawing being edit-able but not appear in the Dopesheet. To avoid this issue enable the option **Always Show Active** under the Dopesheet header.

[![image-1664805381739.gif](./images/gallery/2022-10/image-1664805381739.gif)](./images/gallery/2022-10/image-1664805381739.gif)

1. Ensure you are in **Draw Mode**.
2. From the Dopesheet header select the [![image-1664805413055.png](./images/gallery/2022-10/scaled-1680-/image-1664805413055.png)](./images/gallery/2022-10/image-1664805413055.png) icon.
3. Use the [![image-1664805472939.png](./images/gallery/2022-10/scaled-1680-/image-1664805472939.png)](./images/gallery/2022-10/image-1664805472939.png) icon to enable **Always show Active Object**

- - - - - -

## Further Reading

- **Drawing Tools**
    - [Brushes &amp; Materials](#brushes-materials)
    - [Layer Management](#layer-management)
    - [Quick Edit Tool](#quick-edit-tool)
    - [Select Layer from Viewport](#select-layer-from-viewport)
    - [Rotating the Canvas in 2D](#rotating-the-canvas-in-2d)
- **Animation Tools**
    - [Keyframing Drawings](#keyframing-drawings)
    - [Current Keyframe Box](#current-keyframe-box)
    - [Flipping Box](#flipping-box)
    - [Onion Skinning Box](#onion-skinning-box)
- **References**
    - [Shift &amp; Trace Box](#shift-and-trace-box)
    - [Import Image as Reference](#import-image-as-reference)# Start Drawing

The basic tools needed to start drawing in Blender.

# Brushes & Materials

Pens or Brushes in Blender can be selected only when in **Draw Mode**. Pens will always define the shape or style of the stroke and can also sometimes define material or color of the stroke. The same pen can be used with multiple materials/colors.

[![image-1647960996328.gif](./images/gallery/2022-03/image-1647960996328.gif)](./images/gallery/2022-03/image-1647960996328.gif)

1. Pens can be selected from the top left menu. (only when in draw mode)
2. Materials are defined in the **Storyboarding Panel** by Pallet

    - Select a pallet under either [**Material** ](https://docs.blender.org/manual/en/latest/grease_pencil/materials/introduction.html)or [**Vertex Color**](https://docs.blender.org/manual/en/latest/grease_pencil/modes/vertex_paint/introduction.html)
3. <span id="bkmrk-vertex-colors-can-be">**Vertex Colors** can be defined manually, allowing for quick custom color changes and Palette definitions.</span>

# Layer Management

<span id="bkmrk-each-drawing-object--0">Each [**Grease Pencil Object**](https://docs.blender.org/manual/en/latest/grease_pencil/introduction.html) contains its own set of layers. Layers in Blender work very similar to other 2D programs like Harmony. Layers can be ordered top to bottom to create a hagiarchy and easily hidden/locked.</span>

[![image-1647956749034.png](./images/gallery/2022-03/scaled-1680-/image-1647956749034.png)](./images/gallery/2022-03/image-1647956749034.png)

- - ![image](./images/gallery/other/10790c1bf94c5c27e13d82dd706dbc3d.png)Hide Icon
    - ![image](./images/gallery/other/286b0ebd47c928dc687cd68151c97b34.png)Lock Icon
    - ![image](./images/gallery/other/e2872b921a13c214267087a46be45a84.png)Onion Skinning
    - ![image](./images/gallery/other/cf0a23219323dbe826e97d526bce6774.png)Layer Opacity
    - ![image](./images/gallery/other/1898d37cfa4b9c5e5d917c7c69d3edf4.png)Add/Remove Active Layer
    - ![image](./images/gallery/other/61986bd2f6b86fdc86789b574715732d.png)Up/Down Active Layer

# Add New Drawing Objects

To begin drawing in Blender you will need a [**Grease Pencil Object**](https://docs.blender.org/manual/en/latest/grease_pencil/introduction.html). Blender manages different sets of drawings inside of this **Grease Pencil Object**. It contains all data related to drawings including colors and layers. The **Grease Pencil Object** represents a 2D plane that drawings exist on. This object can be transformed and rotated in 3D space depending on the complexity of your scene.

[![image-1647960660899.gif](./images/gallery/2022-03/image-1647960660899.gif)](./images/gallery/2022-03/image-1647960660899.gif)

1. Select the "plus" icon to create a new drawing object
2. A “New Drawing Object” dialogue will open

    1. Name: Enter name based on convention TBD
    2. Location: This gives options to control where the object is in 3D space
        - View Offset: Will place object in 3D relative to the camera’s position
        - 3D Cursor: Will place object in 3D at a fixed point via [3D Cursor](https://docs.blender.org/manual/en/latest/editors/3dview/3d_cursor.html?highlight=3d%20cursor)
    3. View Offset: Set distance of object relative the camera’s position
        - The “Pin to Camera” button See [Pinning Drawings…](#introduction-to-drawing-toolbox#bkmrk-pinning-drawings-to-)
    4. Orient Axis: Restrict orientation to the select axis.
3. The newly created object will appear in the object list

# Switching Between Drawings & Layers

We can use the shortcut **Ctrl+Shift+Click** to jump between objects while selecting them directly in the Viewport or while selecting the object in the list of Objects in the **Drawings Panel**. This feature, in combination with the setting to **Fade in Active Objects** allows us to now clearly ***differentiate*** which object is active and which is inactive and to what level, and jump between them easily.

[![image-1664804636879.gif](./images/gallery/2022-10/image-1664804636879.gif)](./images/gallery/2022-10/image-1664804636879.gif)

1. Ensure you are in **Draw Mode**
2. Ensure you have **Sync Selection [![image-1664804731263.png](./images/gallery/2022-10/scaled-1680-/image-1664804731263.png) ](./images/gallery/2022-10/image-1664804731263.png)**enabled in the dopesheet header.
3. Enabled **Fade Inactive Objects** + **Grease Pencils** from the overlays menu
4. Enabled **Fade Inactive Layers** from the overlays menu
    - Users can adjust the Fade opacity of inactive objects (set to .5 by default)
5. Hover your Mouse/Pen over the stroke of an inactive drawing
6. **Ctrl+Shift** and **Click** to make inactive drawing active
7. **Alt + Click** to make an inactive layer in the current drawing active
8. Notice the Drawing Panel updates which drawing is updated

# Working with Palettes

## Importing Existing Palette

Palettes are predefined groups of materials.

SPA provides a couple of palettes by default and some of these are provided in the Animation and Layout template files.

- - - - - -

## <span style="font-weight: 400;">Create a new Palette</span>

<span style="font-weight: 400;">Palettes are based on existing Grease Pencil Objects. Palette's are defined by materials with a prefix in their name. </span>

<span style="font-weight: 400;">To create a new Palette we simply add a new material with a new prefix. Using a / to separate the palette from the material's name. The palette items are saved inside your Grease Pencil Object!</span>

<span style="font-weight: 400;">For example: </span>`<span style="font-weight: 400;">MyPalette/Color</span>`

[![image-1664377570666.gif](./images/gallery/2022-09/image-1664377570666.gif)](./images/gallery/2022-09/image-1664377570666.gif)

1. <span style="font-weight: 400;">Open the Material's Tab with a Grease Pencil Active</span>
2. <span style="font-weight: 400;">Use the + Button to Add a new Material</span>
3. <span style="font-weight: 400;">Rename your material with palette title `MyPalette` as a prefix followed by `/`</span>
4. <span style="font-weight: 400;">Name your new material now, and set its color</span>
5. <span style="font-weight: 400;">Refresh your palettes to see your new palette in the side panel.</span>

# Mirror the Viewport

Mirroring the Viewport can be done either from the Storyboard side panel or a keyboard shortcut

[![image-1664540863085.gif](./images/gallery/2022-09/image-1664540863085.gif)](./images/gallery/2022-09/image-1664540863085.gif)

1. Move your viewport to the item to be mirrored
2. From the Side Panel select the [![image-1664540613047.png](./images/gallery/2022-09/scaled-1680-/image-1664540613047.png)](./images/gallery/2022-09/image-1664540613047.png) icon\]
3. Or use keyboard shortcut **SHIFT+ W**

<p class="callout info">**Notice:** When viewport is mirrored, the butterfly icon will turn red: [![image-1664540679660.png](./images/gallery/2022-09/scaled-1680-/image-1664540679660.png)](./images/gallery/2022-09/image-1664540679660.png) and the top left will read **Camera Perspective** **(Mirrored)** if text info is enabled in the overlays menu.</p>

# Enable SPA Theme

SPA has a special theme to make it easier to read the Dopesheet. To enable the SPA theme follow these instructions.

[![image-1664807667681.gif](./images/gallery/2022-10/image-1664807667681.gif)](./images/gallery/2022-10/image-1664807667681.gif)

1. Navigate to **Edit&gt;Preferences**
2. Open the **Theme** tab
3. Select the SPA theme from the **Dropdown**

## **What's new in the SPA Theme**

Dopesheet now has an updated look over vanilla blender to make it easier to read.

[![image-1664808011898.png](./images/gallery/2022-10/scaled-1680-/image-1664808011898.png)](./images/gallery/2022-10/image-1664808011898.png)

- <span style="color: #3366ff;">**Active Object**</span> has a Light Blue Highlight on it's row
- **<span style="color: #339966;">Active Layer</span>** has a Light Green Highlight
- <span style="color: #000080;">**Inactive Object**</span> has a Dark Blue Highlight
- <span style="color: #003300;">**Inactive Layer**</span> has a Dark Green Highlight

# Edit Drawings

How to edit your drawings, and navigate between different layers.

# Quick Edit Tool

<span style="font-weight: 400;">Similar to the selection tool in Harmony. The <span style="text-decoration: underline;">**Quick Edit tool**</span> allows you to quickly select and transform any stroke within the **[<span style="text-decoration: underline;">Grease Pencil Object</span>](https://docs.blender.org/manual/en/latest/grease_pencil/introduction.html).** It can be selected from the left Toolbar.</span>

[![image-1649074222291.png](./images/gallery/2022-04/scaled-1680-/image-1649074222291.png)](./images/gallery/2022-04/image-1649074222291.png)

### <span style="font-weight: 400;">Selection &amp; Move</span>

<span style="font-weight: 400;">Use the tool select and move a stroke in a [<span style="text-decoration: underline;">**Grease Pencil Object**</span>](https://docs.blender.org/manual/en/latest/grease_pencil/introduction.html)**.** Keyboard shortcuts allow for a more precise movement. The mouse cursor will display a hand icon when move is available.</span>

[![image-1649426409426.gif](./images/gallery/2022-04/image-1649426409426.gif)](./images/gallery/2022-04/image-1649426409426.gif)

1. <span class="c3">Use the <span style="text-decoration: underline;">**Quick Edit tool** </span>to lasso a selection</span>
2. <span class="c3">Click and Drag with Mouse/Pen on the transform box to move</span>
3. <span class="c3">CTRL+ARROW KEY moves 1px</span>
4. <span class="c3">CTRL+SHIFT+ARROW KEY moves 5px</span>
5. SHIFT+ Selection will add to the section
6. CTRL + Selection will subtract from the selection
7. <span class="c3">Select blank canvas to deselect
    </span>

### Select/Deselect All

<span class="c4">All strokes on the current frame can be selected and deselected with **A** or **Alt+A
[![image-1656516547619.gif](./images/gallery/2022-06/image-1656516547619.gif)](./images/gallery/2022-06/image-1656516547619.gif)**</span>

1. <span class="c4">Use ‘A’ while Quick Edit tool is enabled to select all strokes on the current frame</span>
2. <span class="c4">Use ‘ALT + A’ while Quick Edit tool is enabled to deselect all strokes on the current frame</span>

### <span class="c14 c17">Scaling</span>

<span class="c14 c17"><span style="text-decoration: underline;">**Scale** </span>any selection either freely or while maintaining proportions. Scaling can also be done around the Pivot Point. Scaling is enabled when hovering over any point on the transform box. The mouse cursor will display a four way arrow when scaling is available.</span>

[![image-1649078811408.gif](./images/gallery/2022-04/image-1649078811408.gif)](./images/gallery/2022-04/image-1649078811408.gif)

1. <span class="c3">Select a drawing and select any point to <span style="text-decoration: underline;">**Scale**</span></span>
2. Hold SHIFT<span class="c12"> </span><span class="c3">to Proportionally <span style="text-decoration: underline;">**Scale**</span></span>
3. Hold ALT<span class="c12"> </span><span class="c3">to <span style="text-decoration: underline;">**Scale**</span> around the opposite corner</span>
4. <span class="c3">Hold SHIFT+ALT to <span style="text-decoration: underline;">**Scale** </span>Proportionally around the opposite corner</span>

### <span class="c17 c14">Rotate and adjust Pivot Point</span>

<span class="c17 c14"><span style="text-decoration: underline;">**Rotate** </span>your selection from any corner. Adjust the pivot point for more advanced rotations. <span style="text-decoration: underline;">**Rotation mode**</span> is available when the Mouse Cursor is in a + shape.</span>

[![image-1649078817089.gif](./images/gallery/2022-04/image-1649078817089.gif)](./images/gallery/2022-04/image-1649078817089.gif)

1. <span class="c3">Select Drawing and drag near any corner to rotate.</span>
2. <span class="c3">Adjust pivot point to affect the rotation’s origin.</span>

### <span class="c17 c14">Skewing</span>

<span class="c17 c14"><span style="text-decoration: underline;">**Skewing** </span>a drawing can be done from any side. <span style="text-decoration: underline;">**Skewing mode**</span> is enabled when hovering along the length of the transform box. The mouse cursor will display a bidirectional arrow along the skew axis when available.</span>

[![image-1649078821755.gif](./images/gallery/2022-04/image-1649078821755.gif)](./images/gallery/2022-04/image-1649078821755.gif)

1. <span class="c3">Hover mouse/pen over transform box line</span>
2. <span class="c3">Click and drag to skew</span>
3. Hold <span class="c12">ALT </span><span class="c3">to skew about the pivot point</span>

### <span class="c17 c14">Copy &amp; Paste</span>

<span class="c17 c14">Strokes can quickly be selected for copying to another frame or for duplication using the selection tool. </span>

[![image-1649426493185.gif](./images/gallery/2022-04/image-1649426493185.gif)](./images/gallery/2022-04/image-1649426493185.gif)

1. <span class="c17 c14">Make a selection</span>
2. <span class="c17 c14">Use Ctrl + C to copy</span>
3. <span class="c17 c14">Use Ctrl + V to paste</span>

### <span class="c17 c14">Duplication</span>

[![image-1651246859724.gif](./images/gallery/2022-04/image-1651246859724.gif)](./images/gallery/2022-04/image-1651246859724.gif)

1. <span class="c17 c14">Make a selection</span>
2. <span class="c17 c14">Use SHIFT + D to duplicate</span>
3. <span class="c17 c14">Move the duplication with either the mouse or keyboard shortcuts</span>
4. <span class="c17 c14">Use X to move duplication horizontally </span>
5. <span class="c17 c14">Use Z to move duplication vertically</span>

### <span class="c17 c14">Delete </span>

<span class="c17 c14">Strokes can quickly be deleted either an entire drawing or a portion of the drawing selected</span><span class="c17 c14">.</span>

[![image-1656521209623.gif](./images/gallery/2022-06/image-1656521209623.gif)](./images/gallery/2022-06/image-1656521209623.gif)

1. <span class="c17 c14">Draw a selection</span>
2. <span class="c17 c14">Hit "X" to delete. </span>

### Move Selection to Layer

<span class="c4">Strokes can quickly move to another layer using ‘M’ on your keyboard.
</span>

[![image-1656516606723.gif](./images/gallery/2022-06/image-1656516606723.gif)](./images/gallery/2022-06/image-1656516606723.gif)

1. <span class="c4">Draw a selection</span>
2. <span class="c4">Hit "M” to Move to Layer</span>
3. <span class="c4">Select a destination layer

    </span>

### Flip Strokes

[![image-1660658290622.gif](./images/gallery/2022-08/image-1660658290622.gif)](./images/gallery/2022-08/image-1660658290622.gif)

1. <span class="c4">Draw a selection</span>
2. <span class="c4">Use the Flip buttons in the Top Left header to mirror X/Y</span>
3. <span class="c4">Mirror works on the current keyframe and can be animated across keyframes</span>

# Select Layer from Viewport

<span class="c5">Select Layer from Viewport is a shortcut to quickly change the active layer while drawing.</span>

Select a layer by Alt clicking a stroke in your viewport. Ensure you have “<span class="c3">fade inactive layers” </span>enabled, this will visualize the change in active layer<span class="c3">. </span>ALT+LEFT CLICK over drawings to switch to that drawing’s layer. The newly active layer will now be highlighted in the Drawings toolbox.

[![image-1656518116820.gif](./images/gallery/2022-06/image-1656518116820.gif)](./images/gallery/2022-06/image-1656518116820.gif)

1. Under <span class="c3">Viewport Overlays [![image-1656518129842.png](./images/gallery/2022-06/scaled-1680-/image-1656518129842.png)](./images/gallery/2022-06/image-1656518129842.png) </span>ensure <span class="c3">Fade Layers </span>is enabled.<span class="c13 c3"> </span>
2. <span class="c5">ALT + LEFT CLICK over a stroke to make it’s layer active</span>

# Rotating the Canvas in 2D

To rotate the current view use the Rotate Canvas shortcut. Can be used anywhere in the viewport.

[![image-1651597751103.gif](./images/gallery/2022-05/image-1651597751103.gif)](./images/gallery/2022-05/image-1651597751103.gif)

1. <span class="c17 c14">From either Camera or 3D View</span>
2. <span class="c17 c14">Keyboard Shortcut SHIFT+CTRL+MIDDLE MOUSE BUTTON</span>
3. <span class="c17 c14">The Blue gizmo will help orient your rotation. At the button an reset icon will appear to show rotation is being used.</span>
4. <span class="c17 c14">Use the</span> [![image-1651597805225.png](./images/gallery/2022-05/scaled-1680-/image-1651597805225.png)](./images/gallery/2022-05/image-1651597805225.png) icon to reset the view. Or use shortcut <span class="c17 c14">SHIFT+CTRL+R</span>

# Pegbars

<span style="font-weight: 400;">Pegbars are for offsetting, rotating and scaling individual Grease Pencil Layers. Pegbars are for only transforming layers inside 2D space. The peg bar system will always aligned with a Grease Pencil Object's drawing plane.</span>

- - - - - -

### **Add Pegbar to Grease Pencil Object**

[![image-1660680268625.gif](./images/gallery/2022-08/image-1660680268625.gif)](./images/gallery/2022-08/image-1660680268625.gif)

1. <span style="font-weight: 400;">To create Pegbars select “Create Pegbar” in the Side Panel</span>
2. <span style="font-weight: 400;">A new Pegbar will be created at the center view</span>

- - - - - -

### **Parent Peg to Layer**

[![image-1660680278712.gif](./images/gallery/2022-08/image-1660680278712.gif)](./images/gallery/2022-08/image-1660680278712.gif)

1. <span style="font-weight: 400;">To parent a peg to a layer select the layer in the Drawings Box</span>
2. <span style="font-weight: 400;">Then under </span>**Peg:**<span style="font-weight: 400;"> select the Peg that will be the parent of this layer</span>

- - - - - -

### **Transform Pegs**

[![image-1660680300358.gif](./images/gallery/2022-08/image-1660680300358.gif)](./images/gallery/2022-08/image-1660680300358.gif)

1. <span style="font-weight: 400;">To transform a peg firstly ensure that the desired peg is active in the Pegbars Box</span>
2. <span style="font-weight: 400;">From the Toolbar on the left select the </span>**BLANK**<span style="font-weight: 400;"> icon under the </span>**Shift and Trace**<span style="font-weight: 400;"> icon</span>
3. <span style="font-weight: 400;">A green transform gizmo will appear, used to Scale and Rotate the peg</span>

- - - - - -

### **Keyframe Peg Transforms**

[![image-1660680401012.gif](./images/gallery/2022-08/image-1660680401012.gif)](./images/gallery/2022-08/image-1660680401012.gif)

1. <span style="font-weight: 400;">Transform a peg to begin the keyframe process</span>
2. <span style="font-weight: 400;"><span style="font-weight: 400;">Use the [![image-1660681425419.png](./images/gallery/2022-08/scaled-1680-/image-1660681425419.png) ](./images/gallery/2022-08/image-1660681425419.png)</span></span><span style="font-weight: 400;">button to insert new keyframes</span>
3. <span style="font-weight: 400;">Keyframes will appear in the Dopesheet under Pegbar</span>

- - - - - -

### **Mute Peg Action**

[![image-1660681549741.gif](./images/gallery/2022-08/image-1660681549741.gif)](./images/gallery/2022-08/image-1660681549741.gif)

1. In the Pegbar menu find the desired peg
2. Use the [![image-1660681601802.png](./images/gallery/2022-08/scaled-1680-/image-1660681601802.png)](./images/gallery/2022-08/image-1660681601802.png) button to Mute/Unmute Peg Animation

- - - - - -

### **Hide Peg UI from Viewport**

[![image-1660681771250.gif](./images/gallery/2022-08/image-1660681771250.gif)](./images/gallery/2022-08/image-1660681771250.gif)

1. In the Pegbar menu find the desired peg
2. Use the [![image-1660681723294.png](./images/gallery/2022-08/scaled-1680-/image-1660681723294.png)](./images/gallery/2022-08/image-1660681723294.png) button to Hide/Unhide Peg symbol in Viewport

- - - - - -

### **Add / Remove Pegs**

[![image-1660680316119.gif](./images/gallery/2022-08/image-1660680316119.gif)](./images/gallery/2022-08/image-1660680316119.gif)

<p class="callout warning">Pegs are always created at the object origin. Peg display location cannot be offset yet.</p>

1. <span style="font-weight: 400;">Double Click any Peg’s name in the Pegbars Menu to rename it</span>
2. <span style="font-weight: 400;">Use the PLUS icon to add Pegs and the MINUS icon to remove Pegs</span>
3. <span style="font-weight: 400;">Removing a peg will reset the associated layer back to it’s original position</span>

- - - - - -

### **Reset Peg Transformation**

[![image-1660680408454.gif](./images/gallery/2022-08/image-1660680408454.gif)](./images/gallery/2022-08/image-1660680408454.gif)

1. <span style="font-weight: 400;">To reset Transformation of a peg ensure the Peg is active in the Pegbars menu</span>
2. <span style="font-weight: 400;">Select RESET Transformation in the Top Left of the Window.</span>

- - - - - -

### **Parenting Pegs**

[![image-1660682007733.gif](./images/gallery/2022-08/image-1660682007733.gif)](./images/gallery/2022-08/image-1660682007733.gif)

1. Create a new Peg name it "Parent Peg"
2. Select the Layer Peg that will be it's Child and set the **Parent:** option to the Parent Peg.
3. Transform the Parent Peg (remember use the keyframe button)
4. The the Layer Peg is now the child of the Parent Peg and will inherit all transformations.

# Sculpt Mode

Sculpt Mode in Blender is a way to manipulate strokes after they are already drawn. Sculpt mode can be used to tweak existing drawings, and clone/tweak similar strokes quickly. Sculpt Mode uses many brushes each with a unique characteristics like; Push, Pinch, Twist and more!

<section id="bkmrk-enter-sculpt-mode"><span style="font-size: 2.8275em; font-weight: 400;">Enter Sculpt Mode</span></section>To Enter Sculpt Mode you must have a Grease Pencil Object active. From the top left of your viewport select Sculpt Mode.

[![image-1664217301382.gif](./images/gallery/2022-09/image-1664217301382.gif)](./images/gallery/2022-09/image-1664217301382.gif)

1. Navigate to VIEWPORT header find the **Mode** menu
2. Select **Sculpt Mode**

## Hiding Edit Line Overlays

In Blender each mode has an overlays menu. You can find the overlays menu by looking for the [![image-1664217372209.png](./images/gallery/2022-09/scaled-1680-/image-1664217372209.png)](./images/gallery/2022-09/image-1664217372209.png) symbol.

[![image-1664217488399.gif](./images/gallery/2022-09/image-1664217488399.gif)](./images/gallery/2022-09/image-1664217488399.gif)

1. Navigate to Overlays Menu
2. Disable **Edit Lines**
3. Use the **Vertex Opacity** to fade the edit lines

## Using Sculpt Mode

Sculpt Mode allows for manipulation of Drawing Strokes after they are drawn. Sculpt mode includes brushes to apply tweaks by painting over strokes.

<p class="callout info">**TIP:** Hold down the CTRL key to invert any brush instead of selecting the +/- buttons from the header menu.</p>

#### **Smooth**

Eliminates irregularities in the area of the drawing within the brush’s influence by smoothing the positions of the points.

[![image-1664218577580.gif](./images/gallery/2022-09/image-1664218577580.gif)](./images/gallery/2022-09/image-1664218577580.gif)

- - - - - -

#### **Thickness**

Increase or decrease the points thickness in the area of the drawing within the brush’s influence.

[![image-1664218637586.gif](./images/gallery/2022-09/image-1664218637586.gif)](./images/gallery/2022-09/image-1664218637586.gif)

- - - - - -

#### **Strength**

 Increase or decrease the points transparency (alpha) in the area of the drawing within the brush’s influence.

[![image-1664218606980.gif](./images/gallery/2022-09/image-1664218606980.gif)](./images/gallery/2022-09/image-1664218606980.gif)

####

- - - - - -

#### **Grab**

Grab selects a group of points on mouse-down, and pulls them to follow the mouse. The effect is similar to moving a group of points in Edit Mode with Proportional Editing enabled.[![image-1664218654026.gif](./images/gallery/2022-09/image-1664218654026.gif)](./images/gallery/2022-09/image-1664218654026.gif)

- - - - - -

#### **Push**

Moves points in the direction of the brush stroke.

[![image-1664218681746.gif](./images/gallery/2022-09/image-1664218681746.gif)](./images/gallery/2022-09/image-1664218681746.gif)

- - - - - -

#### **Twist**

Twist the points in counter-clockwise (CCW) or Clockwise (CW) rotation.

[![image-1664218699932.gif](./images/gallery/2022-09/image-1664218699932.gif)](./images/gallery/2022-09/image-1664218699932.gif)

- - - - - -

#### **Pinch**

Pulls points towards the center of the brush. The inverse setting is Inflate, in which points are pushed away from the center of the brush.

[![image-1664218737760.gif](./images/gallery/2022-09/image-1664218737760.gif)](./images/gallery/2022-09/image-1664218737760.gif)

- - - - - -

#### **Clone**

Adds copies of the strokes in the clipboard in the center of the brush. You have to copy the selected strokes you want into the clipboard with <kbd class="kbd compound docutils literal notranslate"><kbd class="kbd docutils literal notranslate">Ctrl</kbd>-<kbd class="kbd docutils literal notranslate">C</kbd></kbd> before using the tool.

[![image-1664218762550.gif](./images/gallery/2022-09/image-1664218762550.gif)](./images/gallery/2022-09/image-1664218762550.gif)

*For More Info on Sculpt Mode see [Blender Doc](https://docs.blender.org/manual/en/latest/grease_pencil/modes/sculpting/index.html)*

# Animate Drawings

Tools to control keyframes for animation and to organize keyframes for Flipping/Onion Skinning,

# Understanding the Dope Sheet

## Differences in Dope Sheet Views

There are several different types of Dope Sheets that can be displayed in Blender. For the purposes of 2D Animation we want to focus on **Dope Sheet, Action Editor &amp; Grease Pencil.**

[![image-1664890319113.png](./images/gallery/2022-10/scaled-1680-/image-1664890319113.png)](./images/gallery/2022-10/image-1664890319113.png)

- **Action Editor:** The action editor is limited to the current active object's animation data. It cannot show multiple objects, it cannot show Grease Pencil data.
- **Grease Pencil:** The Grease Pencil view only shows keyframes for grease pencil objects, can be multiple objects. It cannot show any Object animation data.
- **Dope Sheet:** The Dope Sheet can show all Object animation data, and grease pencil data, and from many objects not just the active one.

- - - - - -

## Sync Layer Selection in the Dope Sheet

Layer selection from the **Drawing Box** in the 3D Viewport can be synchronized with the current layer that is active in the Dope Sheet.

[![image-1664898293798.gif](./images/gallery/2022-10/image-1664898293798.gif)](./images/gallery/2022-10/image-1664898293798.gif)

1. Ensure you have **Sync Selection [![image-1664804731263.png](./images/gallery/2022-10/scaled-1680-/image-1664804731263.png) ](./images/gallery/2022-10/image-1664804731263.png)**enabled in the Dopesheet header.
2. Select different layers in the Dopesheet the active object will update.

## Setting Filters in the Dope Sheet

The Dope Sheet can be customized to show different views on different classes of objects. For example it can show everything but the Camera, or show hidden keyframes or not.

To use Dope Sheet filters ensure you are in the Dope Sheet View.

[![image-1664803598515.png](./images/gallery/2022-10/scaled-1680-/image-1664803598515.png)](./images/gallery/2022-10/image-1664803598515.png)

- **Summary:** Is the header at the Top of the DopeSheet
- **Only Show Selected:** Will only Show the Selected Object
    - **Always Show Active:** Will always Show the Active Object in Dopesheet
- **Show** **Hidden**: Will show objects or data that was hidden
- **Only Show Errors:** Show animation data that has lost it's object
- **Filter by Type:** Enable or Disable different types of objects in the Dope Sheet, (can be useful to only Show Grease Pencils Objects)
- **Sort Data-Blocks**: When disabled the order of the Timeline will match the Order of your Outliner

- - - - - -

## Sync Visible Range

When this setting is enabled, it will ensure that all regions share the same Zoom/Scroll levels. Please note that the Sync Visible Range setting **must be enabled per timeline region.** See below on where to find it.

[![image-1664890289819.gif](./images/gallery/2022-10/image-1664890289819.gif)](./images/gallery/2022-10/image-1664890289819.gif)

1. Open multiple Dope Sheet regions
2. From each Dope Sheet's header select **View&gt;Sync Visible Range**
3. UI should now be synchronized across these Dopesheet

- - - - - -

## Enable Channel Colors

Blender allows users to organize channels using colors. To get started you must enable a setting in your user preferences.

[![image-1664890407422.png](./images/gallery/2022-10/scaled-1680-/image-1664890407422.png)](./images/gallery/2022-10/image-1664890407422.png)

1. Go to **Edit&gt;Preferences**
2. Switch to the **Animation** tab
3. Enable **Channel Group Colors**
4. Under your drawings **Object Data Properties** tab
5. Navigate to **Layers&gt;Display&gt;Custom Channel Color**
6. Changes to this color will be reflected in the Dope Sheet for that layer

- - - - - -

## Dope Sheet Overlays

Dopesheet now has an updated look over vanilla blender to make it easier to read. You must have the **SPA Theme** enabled to do this follow the [Enable SPA Theme page](#enable-spa-theme).
 [![image-1664807134469.png](./images/gallery/2022-10/scaled-1680-/image-1664807134469.png)](./images/gallery/2022-10/image-1664807134469.png)

- <span style="color: #3366ff;">**Active Object**</span> has a Light Blue Highlight on it's row
- **<span style="color: #339966;">Active Layer</span>** has a Light Green Highlight
- <span style="color: #000080;">**Inactive Object**</span> has a Dark Blue Highlight
- <span style="color: #003300;">**Inactive Layer**</span> has a Dark Green Highlight

# Keyframing Drawings

[**Keyframes**](https://docs.blender.org/manual/en/latest/editors/preferences/animation.html?highlight=keyframe#keyframes) are useful for controlling the timing. **Keyframes** can be placed automatically or manually. Using **Keyframes** in [**Draw Mode**](https://docs.blender.org/manual/en/latest/grease_pencil/modes/draw/introduction.html) will allow for the creation of new frames. Using **Keyframes** in [**Object Mode**](https://docs.blender.org/manual/en/latest/editors/3dview/modes.html?highlight=object%20mode#object-modes) will allow for the animation of objects including the camera. This can be used to for example animate a camera in a Master Layout which is often used in combination with _Pinning Drawings to Camera_.

**Manually**

1. Ensure at least one [**Grease Pencil Object**](https://docs.blender.org/manual/en/latest/grease_pencil/introduction.html) is active.
2. Use the Arrow Keys to navigate the **[Grease Pencil Dopesheet](https://docs.blender.org/manual/en/latest/editors/dope_sheet/grease_pencil.html?highlight=grease%20pencil%20dope%20sheet)** to the desired frame
3. Use “I” on Keyboard or select **Grease Pencil &gt; Animation** from the Header menu. (**Object&gt;Animation** to animate Camera/Objects)
    ![image](./images/gallery/other/69b7e169f2c77d77d3c39fa9b811bbdd.png)

**Automatically**

1. To enable [**Auto-Key**](https://docs.blender.org/manual/en/latest/animation/keyframes/editing.html#auto-keyframe) select the [**Timeline**](https://docs.blender.org/manual/en/latest/animation/keyframes/editing.html#auto-keyframe) region.
2. Enable the Circular **Auto Key** button in the center of the **Timeline** region.
3. New blank frames will be inserted automatically on the active layer.

![image](./images/gallery/other/9f036cadd5859aa2b171997b0fe0e09d.gif)

# Current Keyframe Box

## <span class="c14 c15">Change Frame Type</span>

Keyframe types are used to filter drawings in operations like **Onion Skinning** and **Flipping**.
 **Keyframe types includes**:

- [![image-1656528283615.png](./images/gallery/2022-06/scaled-1680-/image-1656528283615.png)](./images/gallery/2022-06/image-1656528283615.png) Normal keyframe (white / yellow diamond),
- [![image-1656528404943.png](./images/gallery/2022-06/scaled-1680-/image-1656528404943.png)](./images/gallery/2022-06/image-1656528404943.png)[ ](./images/gallery/2022-06/image-1656528314746.png)Breakdown (small cyan diamond),
- [![image-1656528314746.png](./images/gallery/2022-06/scaled-1680-/image-1656528314746.png)](./images/gallery/2022-06/image-1656528314746.png) Extreme (big pink diamond), and
- [![image-1656528342030.png](./images/gallery/2022-06/scaled-1680-/image-1656528342030.png)](./images/gallery/2022-06/image-1656528342030.png) Jitter (tiny green diamond).
- [![image-1656528383210.png](./images/gallery/2022-06/scaled-1680-/image-1656528383210.png)](./images/gallery/2022-06/image-1656528383210.png)Moving Hold (dark gray / orange diamond)

To change the current keyframe type select a different keyframe type from the **Current Keyframe** box, status of any active frame will be displayed in this row.

<span class="c14 c15">[![image-1656517759840.gif](./images/gallery/2022-06/image-1656517759840.gif)](./images/gallery/2022-06/image-1656517759840.gif)
</span>

1. Navigate to the desired frame
2. Check the desired layer is active
3. Select a new Keyframe Type from the **Current Keyframe** box**.**

## Change Frame Duration

<span class="c5">To change the length of an active keyframe ensure there is at least one keyframe forward of the </span><span class="c5">(otherwise the frame will be infinite, and its duration will be 0). </span><span class="c5">Once between two keyframes the length of the active frame can be changed, and all other keyframes forward of the play-head on the active layer will shift.</span><span class="c5">[![image-1656517798697.gif](./images/gallery/2022-06/image-1656517798697.gif)](./images/gallery/2022-06/image-1656517798697.gif)</span>

1. <span class="c5">Navigate to the desired frame</span>
2. <span class="c5">Ensure there is a keyframe forward of the play-head</span>
3. <span class="c5">Adjust the duration by entering a number or selecting the handles to move one increment</span>

# Flipping Box

<span class="c14 c15">The **Flipping** menu allows you to rapidly flip through keyframes in the <span class="c24 c12">[**Grease Pencil Object**](https://docs.blender.org/manual/en/latest/grease_pencil/introduction.html). </span><span class="c3">This allows you to quickly filter keyframe types to flip between.
</span></span>

[![image-1657895634020.png](./images/gallery/2022-07/scaled-1680-/image-1657895634020.png)](./images/gallery/2022-07/image-1657895634020.png)

<span class="c14 c15"><span class="c3"> </span></span>

*To change a Keyframe type for the purposes of filtering. Select the keyframe and hit “R” on the keyboard or from the* ***Grease Pencil Dope Sheet*** *header select* ***Key&gt;Keyframe Type.*** *See* [*Blender Manual*](https://docs.blender.org/manual/en/latest/animation/keyframes/introduction.html#keyframe-types) *for more information. Or use [Current Keyframe](#introduction-to-animation-toolbox#bkmrk-current-keyframe) box.*

1. To flip only on the active layer select the ![image](./images/gallery/other/bad66d5cd522da7b42fc9e25f2245b8f.png)<span class="c3">(left) single image symbol.</span>
2. To flip on all active layers select the ![image](./images/gallery/other/958ebb8c88af68ca5ccabe5c901b9f95.png)<span class="c3">(right) multi image symbol.</span>
3. <span class="c3">Use the colorful keyframe symbols to filter which keyframe types to flip between frames.</span>
4. <span class="c3">Click the filter icon </span>[![image-1651246919239.png](./images/gallery/2022-04/scaled-1680-/image-1651246919239.png)](./images/gallery/2022-04/image-1651246919239.png)<span class="c3"> to disable keyframe filtering</span>
5. <span class="c3">Alternatively use Keyboard Shortcuts "," for flip left and "." for flip right. *(comma=left and period=right)*</span>
6. <span class="c3">Enable the </span>[![image-1651247663551.png](./images/gallery/2022-04/scaled-1680-/image-1651247663551.png) ](./images/gallery/2022-04/image-1651247663551.png)to loop the flipping sequence
7. <span class="c30 c24 c31">To consider preview range ensure the </span>![image](./images/gallery/other/9c1055ccbe85b84f9e9215c4cab36550.png)<span class="c3"> is enabled under Flipping.
    </span>

### <span class="c3">Choose Flipping Undo Behavior</span>

<span class="c3">When using Undo by default Blender will include frame changes by default in the undo history. So Ctrl + Z will flip back to the last frame you saw. </span>

[![image-1659549164797.gif](./images/gallery/2022-08/image-1659549164797.gif)](./images/gallery/2022-08/image-1659549164797.gif)

<span class="c3">To disable this behavior enabled **Stick To Frame**  under **Flipping Undo Settings** in the SPA Blender Addon Preferences.</span>

# Onion Skinning Box

<span class="c15 c14">Enable **Onion Skinning** to preview previous and next drawings. This can be filtered in various ways like by Frame, Keyframe, Selection and more. Use these filters to see only the frames you want.</span>

[![image-1656521030588.gif](./images/gallery/2022-06/image-1656521030588.gif)](./images/gallery/2022-06/image-1656521030588.gif)

1. To enable **Onion Skinning** select the ![image](./images/gallery/other/b219db9e4b8102e3b192a9ab5ee7ed84.png)<span class="c3">button.</span>
2. <span class="c3">Adjust opacity of Onion Skins using the **Opacity slider**.</span>
3. <span class="c3">Adjust the range of keyframes to be onion skinned with before/after.</span>
4. <span class="c3">Keyframes Before/After can be filtered out using color/type (similar to Flipping)</span>
5. <span class="c3">Mode to Display in</span>
    1. **Frames** - *<span class="c1">Display every frame</span>*
    2. **Keyframes** - *<span class="c1">Display only keyframes</span>*
    3. **Selected** - *<span class="c1">Display only highlighted keyframes</span>*
    4. **Tagged** - *<span class="c4">TBD</span>*

# References and Review

Tools to for importing references and tracing from drawings.

# Shift and Trace Box

<span class="c15 c14">**Shift and Trace** is used to quickly move a drawing to another part of the screen for tracing in a non destructive way. **Shift and Trace** can be quickly enabled and disabled and is used primarily as a reference.</span>

[![image-1649080061617.gif](./images/gallery/2022-04/image-1649080061617.gif)](./images/gallery/2022-04/image-1649080061617.gif)

1. Make sure the **Shift &amp; Trace Overlay** ![image](./images/gallery/other/809e555e8092356f8aed7c942e3b4d8b.png) is active from the **<span class="c24 c12">Storyboard Panel</span>**<span class="c3">.</span>
2. Select the **Shift &amp; Trace tool** ![image](./images/gallery/other/5fc1071f4e711d103b539bb38146fb67.png)<span class="c3">from the Toolbar on the left.</span>
3. Mode: <span class="c1">Can be set to the Active Layer or any Editable Layer</span>
4. <span class="c24 c12">Use **Current Frame**</span><span class="c3"> allows you to shift the active frame.</span>
5. **<span class="c24 c12">Custom Frame</span>**<span class="c3"> allows a specific frame to be targeted for shifting regardless of the playhead.</span>
6. The **<span class="c24 c12">Shift &amp; Trace</span> tool** uses move, scale, rotate and skew from the [**<span class="c24 c12">Quick Edit Tool</span>**](#introduction-to-animation-toolbox#bkmrk-quick-edit-tool).
7. <span class="c3">The tool is non-destructive, your edits will disappear when the overlay is disabled.</span>
8. To reset all edits or some edits use the **Reset Menu** in the **<span class="c7">Storyboard Panel
    </span>**[![image-1649074727194.png](./images/gallery/2022-04/scaled-1680-/image-1649074727194.png)](./images/gallery/2022-04/image-1649074727194.png)
9. Use CTRL+ARROW KEY to shift frames with the keyboard, similar to Quick Edit shortcuts

### Pinning Shifted Frames![image-1651248570790.gif](./images/gallery/2022-04/image-1651248570790.gif)

Pin your Shift &amp; Trace to a selected frame using the new PIN icon. This means only the pinned frame will display **Shift &amp; Trace**, so you can preview the rest of your animation easier.

# Import Image as Reference

<span class="c0">To import any image as a reference into Blender use the Import Image as Grease Pencil Reference option. This can be done using an image from your clipboard, or from a disk. This allows you to manipulate the reference image externally in any application and import into blender. </span>

<p class="callout info"><span class="c0">Grease Pencil references are first class citizens that use all the same operations including transformations and keyframing.</span></p>

### <span class="c4">Import via Clipboard</span>

To import an image from clipboard take a screenshot using the built in <span class="c10">[Windows Screenshot tools](https://support.microsoft.com/en-us/windows/use-snipping-tool-to-capture-screenshots-00246869-1843-655f-f220-97299b865f6b)</span><span class="c0">, this will automatically copy the screenshot to your clipboard. You can also copy an image layer from photoshop or copy an image from the web.</span>

[![image-1658162916778.gif](./images/gallery/2022-07/image-1658162916778.gif)](./images/gallery/2022-07/image-1658162916778.gif)

1. <span class="c0">Take a screenshot</span>
2. <span class="c0">Open Blender</span>
3. <span class="c0">Ensure you are in Draw Mode</span>
4. <span class="c0">Use CTRL+SHIFT+V to paste the image from clipboard into the active Grease Pencil layer.</span>
5. <span class="c0">Your reference will now be available as a keyframe in the Dope Sheet.</span>

- - - - - -

### <span class="c4">Import Image(s) from disk</span>

To import an image from disk.

[![image-1657896464191.gif](./images/gallery/2022-07/image-1657896464191.gif)](./images/gallery/2022-07/image-1657896464191.gif)

1. <span class="c0">Open Blender</span>
2. <span class="c0">Ensure you are in Draw Mode</span>
3. Use SHIFT+A to Open to Import References
4. <span class="c0">Browse for the Image(s) you want to import</span>
5. Enable <span class="c24">Pack Image(s) </span><span class="c0">to include the image in your .blend file</span>
6. Enable <span class="c24">Create New Layer(s)</span><span class="c0"> to create a layer per image</span>

<p class="callout info"><span class="c30">Layers will inherit Names from the Image file.</span></p>

# Animating with 3D Objects

Working with 3D in the Animation workspace.

# Moving Objects/Cameras

Blender allows for multiple ways to control an object's position in 3D space. [**Blender Object**](https://docs.blender.org/manual/en/latest/scene_layout/object/introduction.html) can be moved multiple times and in combination with [**Keyframing**](https://docs.blender.org/manual/en/latest/editors/preferences/animation.html?highlight=keyframe#keyframes) can be used to animate [**Objects**](https://docs.blender.org/manual/en/latest/scene_layout/object/introduction.html) including the camera.

[![image-1647968451219.gif](./images/gallery/2022-03/image-1647968451219.gif)](./images/gallery/2022-03/image-1647968451219.gif)

1. Switch to [**Object Mode**](https://docs.blender.org/manual/en/latest/editors/3dview/modes.html?highlight=object%20mode#object-modes) using the drawing toolbox.
2. Select the desired object with your mouse
3. From the left toolbar select the **[Move](https://docs.blender.org/manual/en/latest/scene_layout/object/tools/toolbar.html)** gizm<span id="bkmrk-o">o from the [**Toolbar**](https://docs.blender.org/manual/en/latest/interface/window_system/regions.html#toolbar).
    </span>

*Rotate, Scale &amp; Transform tools are also available from the same toolbar.*

# Switching back to Draw Mode

####

[**Draw Mode**](https://docs.blender.org/manual/en/latest/grease_pencil/modes/draw/introduction.html) is where all drawing is done on the [**Grease Pencil Object**](https://docs.blender.org/manual/en/latest/grease_pencil/introduction.html) as defined in the **Creating a New Object** section. Once in **Draw Mode** users can draw, erase, add/remove layers and add/remove keyframes and much more.

[![image-1647960798760.gif](./images/gallery/2022-03/image-1647960798760.gif)](./images/gallery/2022-03/image-1647960798760.gif)
*An active Grease Pencil/Drawing Object is required to enter Draw Mode. Follow the* ***Create New Drawing Object*** *guide to add a new Object.*

1. Entering Draw Mode select an Object
2. Select the enter Draw Mode button
3. The interface will switch into drawing mode.
4. <span id="bkmrk-to-change-the-active">To change the active drawing simply select a new drawing from the same list</span>

<div id="bkmrk-"><div><svg class="svg-icon" data-icon="link" role="presentation" viewbox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"></svg></div></div>

# Pinning Drawings to Camera

When the camera is animated in Blender it is important to manage the location of your [**Grease Pencil Object**](https://docs.blender.org/manual/en/latest/grease_pencil/introduction.html) within the scene.

[![image-1647968779371.gif](./images/gallery/2022-03/image-1647968779371.gif)](./images/gallery/2022-03/image-1647968779371.gif)

1. Select an [O**bject** ](https://docs.blender.org/manual/en/latest/scene_layout/object/introduction.html)from the Object list.
2. Select the “**Pin to Camera**” button
3. The [**Grease Pencil Object**](https://docs.blender.org/manual/en/latest/grease_pencil/introduction.html) will now follow the camera’s animation path.

# Selected and Active Objects

Selection and Active are properties of objects only in Object Mode. To enter drawing mode on a certain object, it must be your active object, it is also possible to have a difference between an active and a selected object. There are many reasons why Blender separates these concepts. For example is Snapping locations from an Active Object to the Selected Object *for more info on snapping see [here](https://docs.blender.org/manual/en/latest/editors/3dview/controls/snapping.html)*. Another example Object Modes like Draw, Edit, Sculpt etc are dependent on your active object not your selected object.

- - - - - -

## Single Active Object

#### **In the Outliner**

The single active object in this example is the Cube.

**[![image-1663944608046.png](./images/gallery/2022-09/scaled-1680-/image-1663944608046.png)](./images/gallery/2022-09/image-1663944608046.png)**

- **Icon:** Active Object will appear with a ***Faint Grey Background around it's icon*** in the outliner.
    - (We know, yes. it's really faint!)

#### **In the 3D Viewport**

The single active object in these examples are first is the Cube, and second is the Camera.

[![image-1663945305419.png](./images/gallery/2022-09/scaled-1680-/image-1663945305419.png)](./images/gallery/2022-09/image-1663945305419.png)

[![image-1663944855009.png](./images/gallery/2022-09/scaled-1680-/image-1663944855009.png)](./images/gallery/2022-09/image-1663944855009.png)

- **Origin Point:** Single Active Object will have it's origin displayed as an **Yellow Dot**

- - - - - -

## Single Active &amp; Selected Object

#### **In the Outliner**

The single active &amp; selected object in this example is the Cube.

#### **[![image-1663945124726.png](./images/gallery/2022-09/scaled-1680-/image-1663945124726.png)](./images/gallery/2022-09/image-1663945124726.png)**

- **Icon:** Active Object will appear with a ***Faint Grey Background around it's icon*** in the outliner.
- **Name:** The name of the Active Object will be ***H****ighlighted in Yellow***
- **Item Row**: The entire Item row in the Outliner is ***Highlighted in Blue***

#### **In the 3D Viewport**

The single active &amp; selected object in this example is the Cube.

[![image-1663944997619.png](./images/gallery/2022-09/scaled-1680-/image-1663944997619.png)](./images/gallery/2022-09/image-1663944997619.png)

- **Origin Point:** Single Active Object will have it's origin displayed as an **Yellow Dot**
- **Outline:** The Object's shape has a **Yellow Outline**

- - - - - -

## Multiple Selected &amp; Single Active Object

#### **In the Outliner**

The Active Object in this example is Cube. The selected Objects in this example are Camera, Light &amp; Cube.

[![image-1663943903453.png](./images/gallery/2022-09/scaled-1680-/image-1663943903453.png)](./images/gallery/2022-09/image-1663943903453.png)

- **Active**
    - **Icon:** Active Object will appear with a ***Faint Grey Background around it's icon*** in the outliner.
    - **Name:** The name of the Active Object will be ***Highlighted in Yellow***
    - **Item Row**: The entire Item row in the Outliner is ***Highlighted in Blue***
- **Selected**
    - **Name:** The name of the Active Object will be ***Highlighted in Orange***
    - **Item Row**: The entire Item row in the Outliner is ***Highlighted in Dark Blue***

#### **In the 3D Viewport**

The Active Object in this example is Cube. The selected Objects in this example are Camera, Light &amp; Cube.

[![image-1663943906460.png](./images/gallery/2022-09/scaled-1680-/image-1663943906460.png)](./images/gallery/2022-09/image-1663943906460.png)

- **Active**
    - **Origin Point:** Single Active Object will have it's origin displayed as an **Yellow Dot**
    - **Outline:** The Object's shape has a **Yellow Outline**
- **Selected**
    - **Origin Point:** Single Active Object will have it's origin displayed as an **Orange Dot**
    - **Outline:** The Object's shape has a **Orange Outline**

- - - - - -

## Clearing Selections

If you have multiple selections made in Blender you can click anywhere in the 3D Viewport to clear the selection, or use the **Alt-A** shortcut shown below.

[![image-1663944292187.gif](./images/gallery/2022-09/image-1663944292187.gif)](./images/gallery/2022-09/image-1663944292187.gif)

Use shortcut **Alt + A**  to clear selections.

<p class="callout info">To learn more about Selection vs Active see the [Blender Documentation](https://docs.blender.org/manual/en/latest/editors/outliner/selecting.html) </p>

# Editing references

## Editing References

With Blender, every artist as access to a full editing package.

### Launch Video Editing Template

[![image-1660676002501.png](./images/gallery/2022-08/scaled-1680-/image-1660676002501.png)](./images/gallery/2022-08/image-1660676002501.png)
To begin simply launch blender via Shotgrid and select the `Video Editing` template from Blender's Splash Screen,

- - - - - -

### <span style="font-weight: 400;">Interface Basics</span>

[![image-1660676107137.png](./images/gallery/2022-08/scaled-1680-/image-1660676107137.png)](./images/gallery/2022-08/image-1660676107137.png)

- <span style="color: #999999;">**<span class="c2">White: File Browser</span>**</span><span class="c11 c13 c3"> </span><span class="c5 c11">This area is where you will find folders from your computer to use as media bins</span>
- <span style="color: #ffcc00;">**<span class="c11 c3 c19">Yellow: Video Canvas </span>**</span><span class="c9 c5">This where the video you are editing will play</span>
- <span class="c11 c3 c13" style="color: #993300;"><span style="color: #ff0000;">**Red: Properties Panel**</span> </span><span class="c9 c5">This area is where you will find render settings like duration, resolution</span>
- <span style="color: #339966;">**<span class="c11 c3 c16">Green: Toolbar</span>**</span><span class="c5 c9"> This area contains tools like the Selection and Cut tools.</span>
- <span class="c11 c3 c20" style="color: #0000ff;">**Blue: Sequencer/Timeline** </span><span class="c9 c5">The Sequencer area is where you can move and organize movie and sounds strips</span>

- - - - - -

### Importing Files as Strips

## [![image-1660676256966.gif](./images/gallery/2022-08/image-1660676256966.gif)](./images/gallery/2022-08/image-1660676256966.gif)

<p class="callout info">Blue Strips contain Videos, while Turquoise Strips contain Audio. Typically movie files will have a Video and an Audio strip.</p>

1. <span class="c4 c5">You can import a file using the file browser area</span>
2. <span class="c4 c5">To begin a folder in the File Browser and navigate to the desired video/audio file.</span>
3. <span class="c4 c5">Drag the desired file into the timeline area</span>
4. *<span class="c6 c5"><span class="c6 c5">Alternatively use shortcut CTRL+A to begin importing</span></span>*

- - - - - -

### Cut a strip

[![image-1660676297776.gif](./images/gallery/2022-08/image-1660676297776.gif)](./images/gallery/2022-08/image-1660676297776.gif)

1. <span class="c4 c5">Select the Blade tool from the Toolbar area</span>
2. <span class="c4 c5">Click on the clip you would like to cut to insert a cut</span>
3. *<span class="c5 c6">Alternatively use Shortcut SHIFT+SPACEBAR , K to open blade tool
    </span>*

- - - - - -

### Delete a Strip

### [![image-1660676381671.gif](./images/gallery/2022-08/image-1660676381671.gif)](./images/gallery/2022-08/image-1660676381671.gif)

1. <span class="c4 c5">Select strip you would like to delete</span>
2. From the sequencer header menu select **<span class="c3">Strip&gt;</span><span class="c4 c3">Delete</span>**
3. *<span class="c6 c5">Alternatively use Shortcut X to delete strips</span>*

- - - - - -

### Move a Strip

[![image-1660676412791.gif](./images/gallery/2022-08/image-1660676412791.gif)](./images/gallery/2022-08/image-1660676412791.gif)

1. <span class="c4 c5">To move a strip select the strip</span>
2. <span class="c4 c5">Hit G on the keyboard and move the mouse or arrow-keys</span>
3. <span class="c4 c5">Press Enter to confirm</span>

- - - - - -

### Moving Strip's Handles

[![image-1660676432426.gif](./images/gallery/2022-08/image-1660676432426.gif)](./images/gallery/2022-08/image-1660676432426.gif)

1. <span class="c4 c5">To move a handle select the handle of a strip (handles are highlighted white)</span>
2. <span class="c4 c5">Hit G on the keyboard and move the mouse or arrow-keys</span>
3. <span class="c4 c5">Press Enter to confirm</span>

- - - - - -

### <span class="c4 c5">Adjust Render Length</span>

[![image-1660748121258.gif](./images/gallery/2022-08/image-1660748121258.gif)](./images/gallery/2022-08/image-1660748121258.gif)

1. In the **Properties Panel** under **Render Properties**
2. Find **Frame Range** and set **Start** &amp; **End** Frames

- - - - - -

### Rendering

### [![image-1660676472881.png](./images/gallery/2022-08/scaled-1680-/image-1660676472881.png)](./images/gallery/2022-08/image-1660676472881.png)

1. <span class="c4 c5">Before rendering name your file using the output properties panel</span>
2. <span class="c4 c5">A `“//”` before the filename means render will save in the folder of current .blend file</span>
3. From the Top Menu of Blender select <span class="c3">**Render**&gt;**Render Animation** to begin rendering.</span>[![image-1660677241976.png](./images/gallery/2022-08/scaled-1680-/image-1660677241976.png)](./images/gallery/2022-08/image-1660677241976.png)# Shotgrid web interface

