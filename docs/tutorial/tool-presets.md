# Tool Presets

> WIP Note : the tool presets are still work in progress and subject to changes

## What are tool presets ?

In storyboard, you only need a handful of tools, with specific use.  
The tool presets are like macros to set Blender tool with specific options in one action.  
Each one is defined through a shortcut and appear as button in the `Tool preset topbar` at the top of the viewport.  

You can hide the topbar in addon preferences (shortcut will stay valid)  
Topbar margin and spreading can be adjusted as well in preferences.

## Default tools presets

> Note: The default tools are subject to changes in future in versions

Default tools presets are associated with keyboard top row number keys and sorted by key order.

`1` : **Sketch Draw** -> draw tool, brush **Pencil**, layer **Sketch**  
`2` : **Line Draw** -> draw tool, brush **Ink Pen**, layer **Line**  
`3` : **Bucket Fill** -> Bucket Fill tool, _no brush_, layer **Color**  
`4` : **Lasso Fill** -> draw tool, Bucket Fill tool, _no brush_, layer **Color**  
`5` : **Eraser Point** -> Eraser tool, brush **Eraser Point**  
`6` : **Eraser Stroke** -> Eraser tool, brush  **Eraser Stroke** 

 <!-- Set Paint mode, (using mode need an ignore function to avoid overwriting shortcuts of other context...)  -->

## Properties of a tool preset

A tool preset can define :

`name`: Name of the tool preset used as identifier
<!-- `mode`: Mode to swap to if specified -->
`layer`: Layer name to swap to, if exists
`material`: Material to swap to, if exists
`tool`: Identifier of the tool to use
`brush`: Name of the brush to use within tool
`icon`: Icon to display
`show`: Display the preset as button in preset bar interface (if hidden, the shortcut remains)<!-- `order`: The order to display on user interface -->

## Preset Management

In addon preferences of storytools go to the `Tool presets` tab

Here you can disable or modify the default tool presets

The panel list all keymaps using the operator ID `storytools.set_draw_tool`, those are registered in keymaps under `Grease Pencil` > `Grease Pencil Stroke paint mode`.

You can add other shortcut directly from the preference. Use existing presets as examples to customize the behavior.
