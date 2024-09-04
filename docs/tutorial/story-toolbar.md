# Bottom toolbar


## What's in the bar ?

The bottom bar contain some useful actions to move around object and camera.

Most of the actions affect only active object/camera.

Those actions work regardless of the mode you're in, meaning you can move active object without leaving draw mode

Note that some action are always relative to camera view, see details below


## Object actions

### Move

Move active object relative to view
Modifiers:
`X`: lock on X view axis (toggle)
`Y`: lock on Y view axis (toggle)
`Ctrl`: snap on X or Y view axis depending on free movement

### Move forward / backward

Move the object in depth relative to camera

> Note that even if you're in free navigation, it will still on the depth relative to camera

## Camera actions

### Move camera

Move the camera along x/y view axis



## Draw actions


### Set draw mode

If a Grease pencil object is active : Toggle between Draw mode and Object mode

If no Grease pencil active. Set the first on visible in scene as active (trigger creation if no GP object exists)