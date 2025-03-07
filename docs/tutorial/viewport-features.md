# Viewport features


## Scale figure overlay

To help with real world scale, storytools adds a `Scale Figure` option in GP overlays menu.

![Scale figure overlay](../images/interface/overlay_scale_figure.jpg)

You can see that the default monkey has a pretty big head in real world scale...

The figure will display at active object's origin, orient according to GPencil settings and always stays in world scale.

Figure choice:
- Ruler with customizable size (default to 1.8m)
- human male (1.8m)
- human female (1.65m)
- cat (0.3m)

Clicking on the `layer` icon (next to opacity and xray toggle) will convert the scale figure into a `ScaleFigure` layer into the grease pencil object. This allow to place it somewhere else in the scene, or to include it in render if you need size reference.


## Workspace management

### Reset list

> Work in progress

![quick reset list](../images/interface/wks_reset_button_and_list.jpg)

The pen icon at top right corner is a `quick reset` button.  
It will restore the settings listed in the `Reset list` tab, in addon preferences. Customize behavior to you liking.

### Viewport setup panel

Storytools adds a menu to manage viewport options. Located on top right corner, next to the `quick reset` button 

![Workspace menu](../images/interface/wks_management_menu.jpg)


#### Quick preferences

`Open Storytools Preference` : quick access to preferences window, with "Storytools" entered in the search field


#### View and tool presets

`View Settings Preset` : Store/restore preset of the all the view settings in *current viewport*.
This includes: Overlay settings, Shading mode, hide/select toggles at viewport level...

`Tool Settings Preset` :  Store/restore preset of all the *scene tools options*.  
This includes: Gp placement and orientation, autokey state, color mode (Material Vs attributes), snaping mode...

![view and tool presets](../images/interface/view_and_tool_presets.jpg)

On both of the above, there is a **Default** Preset that reset to factory default.  
This is useful in case where you have a somewhat messed up viewport or tools, you can try to reset using those (or your own presets)

/!\ Careful: restoring the _defaut tool settings_ set the the orientation to `View`. Storytools set it to `Front Axis` at object creation (if you haven't changed it in addon preferences)  

![Default orientation is view](../images/interface/view_after_reset_tool_settings_fun.jpg)

#### Workspace loading

Load one of the two template workspace shipped with storytools, single window or dual window.  
This is explained further in the [Setup Project Section](setup-project.md)

#### Minimap setup

Turn current viewport into a minimap or split current viewport, creating a minimap one on top


<!-- TODO add a minimap section and link to it or list everyting here -->


