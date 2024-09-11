# Bottom toolbar


## What's in the bar ?

The bottom bar contain some useful actions to move around object and camera.

Most of the actions affect only active object/camera.

Those actions work regardless of the mode you're in, meaning you can move active object without leaving draw mode.

Note: Some action are always relative to camera view, see details below

You can collapse the bar or disable it completely in addon preferences

## Object actions

### Move

Move active object perpendicular to view

`X` (toggle) : lock on X view axis  
`Y` (toggle) : lock on Y view axis  
`Ctrl` : Lock on X or Y view axis depending on free movements    
`Shift` : Precision mode  

### Move forward / backward

Move the object in depth relative to camera.  

`Ctrl` : Adjust Scale so object retain same size in camera frame  
`Shift` : Precision mode  
`Alt` : Constraint on horizontal plane  

> Note: even if you're in free navigation, The move is relative to camera

During transform, there is a hint color overlay:

- everything in tinted red is behind object
- everything in tinted blue is in fron of object

The overlay can be customised or disabled in addon preferences

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

### Key transform

Add key on object location, rotation and scale

> Does not affect grease pencil layers frames


## Camera actions

### Move camera

Move the camera along view axis x-y plane (Pan)

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


### Camera control

In Camera view: Toggle "_lock camera to view_" (on active viewport)  
In free view: Go to camera view  

`Ctrl` : Center and resize view to fit camera bounds  
`Shift` : Match view zoom to render resolution  

### Key transform

Add key on active camera location and rotation


## Draw actions

### Lock current view

Lock current viewport orbit navigation.  
when toggled on, the orbit shortcut becomes and additional Pan.  
This way you can't accidentally go out of camera or ensure you stay in the same view axis.

### Set draw mode

If a Grease pencil object is active : Toggle between Draw mode and Object mode.  
If no Grease pencil active. Set the first on visible in scene as active.  
Popup "add GP" if no GP object exists in scene.

> Note that upper tool preset also set draw mode (in default settings)

<!-- `Ctrl` : Add a new object -->