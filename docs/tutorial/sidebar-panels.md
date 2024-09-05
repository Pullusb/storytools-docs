# Sidebar Panels


## Quick access

The sidebar contains all you need to manage your cameras and grease pencil objects

## Camera management

Passepartout and opacity is exposed in panel header

In a storyboard context they will probably be only one per shot.  
But having multiple allow testing alternative movements  
Clicking on camera icon or name will make it active.  

### Camera lens

The `lens` display can be disabled in subpanel.  

A bunch of classic lens shortcut are provided in subpanel.

### Track to constraint on object

In some cases, it's more easy to handle the direction of the camera using a target in 3D space.  
The `Add Track-to Constraint` create an empty object with camera contrained to look at it.

> if an empty object is already selected it will be used as target

The constraint can be managed or removed in the same subpanel

### GP Toolbox Draw cam switch

If the addon GP toolbox is enabled, a shortcut to the `Draw camera` switch appears in lateral menu buttons.  
This feature allow rotating in camera view without affecting camera.  
More on `GP toolbox` and the `Draw cam` in the [resources section](./resources.md#gp-toolbox)

## Grease Pencil Objects

The Grease Pencil objects are listed here

Clicking on a GP in list will make it active regardless of previous mode.  
If a GP was selected previously the mode will be transfered.  

The grid display overlay representing the drawing plane is exposed in panel header

### GP lateral menu

`+` button, pop-up a menu to add new GP

`Chain` button parent/unparent object to active camera (not a dynamic parent!)


The submenu expose informations to display in the list:

- `Show linked data` (Disabled by default) : Show when two GP use the same datablock
- `Show parents` : Display a chain if object is parented
- `In Front toggle` : Expose `In Front` object property, override depth order to show object in front of other


## Materials

The same material list as in propertie panel, exposed in sidebar to be able to work without properties panel

### Layer-material Synchronisation

This feature allow to link selected material with active layer.  
when active, returning on this layer later will select the same material.  
This is individual per object but can be unified, usefull when ultiple objects use same layer names and materials.


## Native Brushes - Color - Palette

The native Brushes, color and palette panels are exposed here for convenience when working with custom brushes or using vertex color instead of material.

## Tool

Some extra tools that can proves handy

### Align view


`Align view to Object` : Set free view in front of object drawing plane

`Opposite View` : Turn the free view by 180° to watch opposite side


### Store / Restore settings

`View Settings Presets` : Popup a panel to save or restore View settings

These are all the settings related to view configuration and overlays.

`Tool Settings Preset` : Popup a panel to save or restore Tool settings

These are all the settings related to active tools: brush, thickness, opacity...


Both settings can be restored to blender default by clicking on `Default`


## Tools

Extra _tools_ panel is added if addon `Grease Pencil Tools` is enabled.
For more info on the addon go to the [resources section](./resources.md#grease-pencil-tools)
