# Upcoming
- New maps: *ee_morko* and *street*.
- Better skybox in *house*.
- Transition to *street* in *house*.

# 9 January 2017 (Version 1.0.2)
Added one new map: bank, and fixed a lot of the known bugs in Version 1.0.1.

## Known bugs:
- Minitrain in *under* stutters when turning corners.
- Generator sound issue in *house* is not fixed yet - I'm working on it.
- Hacker den sequence in *bank* is unfinished and is not functionally complete yet.
- Couple of lighting artifacts in *bank*.
- There is a flood door in the warehouse in *under* that leads to a wall. This is intentional as the area beyond is unfinished.
- Use highlights are still missing for the sledgehammer in *house*. I'm not sure how to fix this as I've already added hints.

## Changes:
### under
- Added minitrain. THIS IS NOT FUNCTIONALLY COMPLETE YET!
- Fixed any item being able to be used as a fuse (#27)

### house
- Added blinds to toilet window (issue #6)

### menu
- Fixed Morko clipping into the table (#29)

# 14th October 2017 (Version 1.0.1)
## Known bugs:
- Elevator in *under* currently has a bug where it can not go up after it comes down. Will be fixed in 1.0.2.
- Elevator music in *under* is currently not working.
- The "menu" button in the phone menu loads you into the default INFRA main menu, not the custom Remnants one.
- Generator in the mine in *house* has a few bugs which will be fixed in 1.0.2.
- Have NOT added planks to the hole in the mine in *house* yet. This will be added in 1.0.2.

## Changes:
- Added custom main menu. For the "playtest" menu options to show up, you will need to add "-playtest yes" to your INFRA launch options. To do this, right-click on INFRA in your Steam library, click on Properties, click on Set Launch Options and append "-playtest yes" in the box.

### under
- Changed generator puzzle a bit. You now need fuel from the lobby area to start the generator.
- Removed lighting in the blast door area save for a few lights.
- Fixed sprites on the blast door control panel.
- Moved gates on the elevator back a bit so they don't clip the elevator sides.
- All of the sounds on the card readers in the warehouse should now be working properly.
- Added lighting beneath the control area. Also added custom textures to the control panel screens.
- Migrated the alarm panel keypad to my own custom scripted one. There shouldn't be any bugs with this; I've tested it extensively.
- Added camera targets to the asbestos, the water in the flooded hallway, and the emergency stop button.
- Added lip to the ladder that ascends to the laboratory so you can access the door.
- Fixed sounds and rotation on blast doors.
- Added minitrain area, but it is far from complete yet (no lighting, no detail, incomplete logic). Don't include this area in playtesting.

### house
- Made animations for the blast in the office more fluid.
- Made it so that the blast will only occur after you press the button. Added animations to this (may be a little buggy).
- Fixed lighting in the generator/mine area.
- Fixed the door unlocks for most of the locked doors in the house.
- Improved the sauna, and added a kitchen area.
- Removed the attic.

# 1st October 2017 (Version 1.0.0)
Added two maps - under and house.
Please contact CitadelCore for map details.
