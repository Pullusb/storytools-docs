# Bottom toolbar


## What's in the bar ?

The bottom bar contain some useful actions to move around object and camera.

Most of the actions affect only active object/camera.

Those actions work regardless of the mode you're in, meaning you can move active object without leaving draw mode

Note that some action are always relative to camera view, see details below


## Object actions

### Move

Move active object perpendicular to view

`X` (toggle) : lock on X view axis 
`Y` (toggle) : lock on Y view axis  
`Ctrl` : Lock on X or Y view axis depending on free movements    
`Shift` : Precision mode  

### Move forward / backward

Move the object in depth relative to camera

`Ctrl` : Adjust Scale so object retain same size in camera frame  
`Shift` : Precision mode  
`Alt` : Constraint on horizontal plane  

> Note that even if you're in free navigation, it will still on the depth relative to camera

### Rotate

Rotate object on view axis

`Ctrl` : Snap on 15 degrees angles  
`Shift` : Precision mode  


### Scale

Scale object, drag left<->right

`Shift` : Precision mode


### Align to view


Align object with view

`Ctrl` : Set object Z axis pointing up while aligning  
`Shift` : Bring selected objects in front of camera  

## Camera actions

### Move camera

Move the camera along view axis x-y plane

Modifiers:  
`X` (toggle) : lock on X view axis 
`Y` (toggle) : lock on Y view axis  
`Ctrl` : Lock on X or Y view axis depending on free movements  
`Shift` : Precision mode  

### Rotate

Rotate camera, rotate view in free view

`Ctrl` : Snap on 15 degrees angles  
`Shift` : Precision mode  
`Double click` : Reset rotation


## Draw actions


### Set draw mode

If a Grease pencil object is active : Toggle between Draw mode and Object mode

If no Grease pencil active. Set the first on visible in scene as active (trigger creation if no GP object exists)