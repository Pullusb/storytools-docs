# Bottom toolbar


## What's in the bar ?

The bottom bar contain some useful actions to move around object and camera.

Most of the actions affect only active object/camera.

Those actions work regardless of the mode you're in, meaning you can move active object without leaving draw mode

Note that some action are always relative to camera view, see details below


## Object actions

### Move

Move active object perpendicular to view

Modifiers:  
`X` (toggle): lock on X view axis 
`Y` (toggle): lock on Y view axis
`Ctrl` (during press): Lock on X or Y view axis depending on free movements  
`Shift` (during press): Precision mode

### Move forward / backward

Move the object in depth relative to camera

> Note that even if you're in free navigation, it will still on the depth relative to camera


## Camera actions

### Move camera

Move the camera along view axis x-y plane

Modifiers:  
`X` (toggle): lock on X view axis 
`Y` (toggle): lock on Y view axis
`Ctrl` (during press): Lock on X or Y view axis depending on free movements  
`Shift` (during press): Precision mode


## Draw actions


### Set draw mode

If a Grease pencil object is active : Toggle between Draw mode and Object mode

If no Grease pencil active. Set the first on visible in scene as active (trigger creation if no GP object exists)