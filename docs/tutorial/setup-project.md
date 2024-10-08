# Setup project
> How to setup a storyboard session

## Storytools + shot management

Storytools add viewport controls and objects management.

To setup the shots, you need a dedicated tool.
You use any alternative you like (ex: Storypencil)  
This tutorial will explain how to work with the *Spa-sequencer* addon in Blender standard

> **Spa-sequencer** has a very complete [documentation](https://the-spa-studios.github.io/blender-spa-userdoc/)  
> The addon is meant to be used with a special SPA build (windows only, and too old to work with storytools, link in spa-documentation homepage).  
> But it can actually be used with Blender standard, at the cost of having to use dual window, one for the sequencer, the other for the viewport.
> In the future, it should be possible to use it in standard blender in single window mode.

## Install

You need Blender software:

Get latest [Blender on download page](https://www.blender.org/download/)  
/!\ Use maximum 4.2, as 4.3+ use the new Grease pencil v3 and ar not compatible with lots of addon for now

> If you want to manage multiple version and easy downloads, check [Blender launcher in resources section](./resources.md#blender-launcher)

Next step is to download, install and enable the addons:

- Get latest [storytools on repository page](https://github.com/Pullusb/storytools) or directly [download latest](https://github.com/Pullusb/storytools/archive/refs/heads/master.zip)
- Get latest [SPArk (spa-sequencer fork) on repository's release page](https://github.com/NickTiny/SPArk-sequencer-addon/releases) (click on latest "spa_sequencer_x_x_x.zip")

In Blender 4.2, you just have to drag and drop the zip file on Blender window.

If it does not work, go to `Edit > Preferences > addons` and uses `install from file`

![install from disk](../images/setup/blender_install_from_disk.png)


## How to use Spa-sequencer in Blender standard


### Setup scenes

We will need at least one extra scene for the sequence part.

Create a new scene and name it `EDIT`, then use the scene selector to reset current window to use `Scene` again (we will use the `EDIT` scene in as dedicated workspace in the next step)

![add new scenes](../images/setup/seq_create_scenes.png)

> You can also create new scenes named with `TEMPLATE_SHOT_` prefix. After setup, new scenes can be created directly in sequencer using those templates.


### Dual window setup

> Note that it's possible to use only one window as explained in this [video by Nick Alberelli](https://youtu.be/pQwSo5sGBeY?si=Cr25klWg8ASRRP_J&t=532)
> But you'll have to jump back and forth between sequencer and drawing view.

To create an additional window, go to the main header menu: `Window > New Main Window`

![Dual windows](../images/setup/seq_dual_window.png)


This new window will be used for the sequencer.  
Remove all the editors to let only a `sequencer editor visible`  
Right-click on limits between editors area > click `Join Areas` > click on the side to remove.

Example using the `Video sequencer` workspace template as base:

![Organise editors](../images/setup/seq_collapse_editors.gif)

Arrange the window at the bottom of your screen so it stay visible below the the previous one.

> Tips: On _Windows 11_, you can use the shortcut `Win + ↑` to stick the first windows at the top, then you can select the other window to go at the bottom, that automatically create a ""window group" in taskbar

On the new "sequencer" window, set the scene selector to `EDIT`

![select edit scene](../images/setup/seq_select_edit_scene.png)

Open the side panel (`N` key with mouse over editor), go to the `SPA.sequencer` tab and point to the `EDIT` scene, then activate `Sync`.
Now this window will control the scenes and shot displayed on the other window.

![Dual window setup](../images/setup/seq_dual_win_desc.png)

Only when the focus is on the bottom window will you play along all the shot

Now the setup is done, and you are ready to create shots !


## Add shots

You can add, duplicate, remove shots in the sequencer `Shots` menu

![Add shot](../images/setup/seq_add_shots.png)


At this point your basically set.

The youtuve video [Demo of The SPA Studios' Sequence Toolset in Blender](https://www.youtube.com/watch?v=pQwSo5sGBeY) by Nick Alberelli explain how use the sequencer.

For more details, you also have the written [Spa-sequencer documentation](https://the-spa-studios.github.io/blender-spa-userdoc/layout/#your-first-shot) (except that you'll have to play with two window instead of one)


## Add Drawing with storytools

Now you are in a shot, and you want to add a new grease pencil object.

> Most editor's sidebar open with `N` key

Use `Storytools > Drawings` in viewport sidebar

![Add Drawing](../images/setup/tool_add_drawing.png)

Enter **Draw mode**, by using _Tab_ or dedicated [bottom bar "pen" button](./story-toolbar.md#set-draw-mode) or by selecting one of the left tools in upper _tool preset_ bar.


Draw things !
