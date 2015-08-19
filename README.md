loop-launchpad-pro
===

Novation Launchpad PRO bindings for
[loop-grid](https://github.com/mmckegg/loop-grid) for using with
[Loop Drop](http://loopjs.com).

This code is heavily derived from the
[Novation Launchpad bindings](https://github.com/loopjs/loop-launchpad)
developed by Matt McKegg, with the buttons correctly mapped for
Novation's Launchpad PRO.

Note - you must put your Launchpad PRO in to "programmer" mode for the
best experience (press setup and the 5th button on the top row).

## Todo

- Support for the Launchpad PRO's velocity sensitive pads
- Support for controller aftertouch
- Support for RGB lights on the PRO.

## Controller Mapping

Trigger sounds using the **main grid** on the Launchpad PRO hardware that
corresponds to the interface grid that you have added chunks to.

### Beat Repeat

The side buttons (marked with right arrows) on the Launchpad enable
**beat repeat** mode as follows:

  - None (free play),
  - 1
  - 2/3
  - 1/2
  - 1/3
  - 1/4
  - 1/6
  - 1/8

When beat repeat is enabled, **hold down** a trigger on the main grid,
and it will be **continuously triggered** at the selected rate to the
project tempo specified. This allows you to play in perfect time with
the tempo.

### Store Loop

By default the last 2 bars of everything you play is being
recorded. The top buttons (1-8) control the current loop. Press
**1**/**Up arrow** to start looping the events you just played.

### Clear / Flatten

When no transformations are currently active (no beat repeat held or
active suppression), **2**/**Down arrow** clears the currently playing
loop, otherwise it locks in the current transform.

### Undo / Redo

Top buttons **3** and **4** (the left and right page buttons) trigger
undo or redo of stored loop on press.

### Beat Hold

Top button **5**/**Session** will loop the currently playing beat at
the rate specified by the Beat Repeat buttons when held down. You can
lock in the loop by pressing the Flatten button (2/down arrow) at the
same time.

### Suppress

Top button **6**/**Note** will suppress all current playback when held
down. You can lock that in by pressing the Flatten button (2/down arrow) at
the same time.

### Select / Move

To select buttons, hold down top button **8**/**user**, and press some
buttons on the grid and release. You can now hold **Suppress** to mute
the selected slots, or hold another button on the grid to move/offset
the loop events.

### Loop Length

Hold `select` (8/user) and press the `undo` (3/left arrow) button to
halve loop length or `redo` (4/right arrow) to double.
