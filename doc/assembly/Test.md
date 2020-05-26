# PrintNC Build Guide

## ─

### Designed by: Mark Hoges

### Written by: Arun Kalahasti


## Introduction

This build guide will walk you through the tools, materials, and process to build your own
PrintNC. The guide is intended to be complete with all the information you will need for the
full build process, but it is NOT built for easy digestion. Please watch a few video guides
before starting your build for a better overview of the process. When doing your build the
guide can be printed and used as a step-by-step checklist to help ensure no critical steps
are missed or done wrong.

## Tools Required

```
❏ Center punch
❏ Hammer
❏ Electric Drill
❏ Metal tap bits
❏ M
❏ M
❏ Allen Key
❏ M
❏ M5 - Ball Nose with long
shaft
❏ Metal cutting drill bits
❏ M
❏ M4.
❏ M
❏ M
❏ M6.
❏ Thread-locking fluid
```
## High Level Build Process Overview:

1. Prepare and assemble X-Axis and Y-Axis frame pieces
2. Mount Y-Axis mechanics
3. Prepare and assemble Z-Axis
4. Prepare X-Axis gantry pieces
5. Mount X-Axis mechanics
6. Install X-Axis gantry and Z-Axis
7. Install waste board


## Important Notes

```
● Never remove the ball screw nuts from the threaded shaft. The mechanism can be
made irreparable if disassembled incorrectly!
● Several steps in the build process requires using a small allen key to pass through a
small hole to tighten bolts. This limits the types of bolts in several places to button
head style, since those use smaller allen keys. Please make sure you’re using the
correct style of bolts where needed. Ball-nose allen keys with long shafts are
required for these sections.
● Some build steps can be done in alternate order to reduce tool changes or to
accommodate the constraints of optional tools like drill presses. Some known
alternatives include:
○ Combine steps 1 and 4: Y Axis Frame - mark corners and middle, then flip
over and mark BF12. All are M6 Threaded.
```

### 1. Y-Axis Frame Prep

```
Summary : Create M6 threaded holes for mounting and one M5 unthreaded at
```
#### the front for cable passthrough.

#### Hardware Needed:

```
❏ Center punch
❏ Drill
❏ M5 Drill bit
❏ M6 Tap bit
❏ Pencil
❏ (2) Y-Axis frame beams
```
#### Printed Parts Needed:

```
❏ Assembly Tool #1 - Y Frame
Marker
❏ Assembly Tool #3 - Y Frame
Mid Marker
❏ Center Line Marker Tool
```
#### When complete, verify:

```
❏ All holes drilled in this step are on the bottom surface of the beams
❏ Each beam should have a center line marked on the top surface.
❏ One end of one Y-axis frame beam should have 5 holes, as shown in Figure
1.4.
❏ The other end of that beam, as well as both ends of all other Y-axis frame
beams should have 4 holes.
❏ All Y-axis frame beams should have 4 holes at the center
❏ All holes except for the center hole in Figure 1.4 should be threaded to
accept an M6 bolt.
```

#### Build Steps:

1. Position Assembly Tool #1 on the top face of one Y-Axis frame beam with the
    number on the printed part facing down and all tabs securely holding position as
    shown in Figure 1.1.
2. Mark all 4 corner holes with a center punch.
3. Mark the center hole with a center punch. The center hole is only used once and
    only on the first beam where a wire will be passed to connect an endstop switch.
4. Repeat steps 1.1-1.2, skipping step 1.3 on the other end of the Y-Axis frame beam
    and both ends of the other beam.
5. Find and mark the center point of the exposed bottom face of each beam.
6. Position Assembly Tool #3 at the middle of the frame beam as shown in Figure 1.2,
    using the hole in the center of the printed tool to align it precisely to the center
    point mark made in the previous step.


7. Mark the 4 holes around the edges with a center punch. Do not mark the center
    hole.
8. Drill all marked points with an M5 bit.
9. Thread all holes made in the previous step except the center hole marked in step
    1.1 with an M6 tap bit. That hole can be tapped, but it’s not necessary.
10.Flip the Y-Axis frame beams so the holes are facing down.
11.Position the Center Line Marker Tool on the top face as shown in Figure 1.3.
12.Place a pencil or other marking tool at the center of the v shaped grove on the
    Center Line Marker Tool and hold it there securely.
13.Run the Center Line Marker Tool down the length of the beam while using the
    marking tool to mark the center. Measure your centerline at several places to
    ensure it is indeed properly centered.
14.Repeat previous 3 steps for the other Y-Axis frame beam.


### 2. X-Axis Frame Prep

```
Summary : Create M6.5 unthreaded holes for mounting
```
#### Hardware Needed:

```
❏ Center punch
❏ Drill
❏ M6.5 Drill bit
❏ (3) X-Axis frame beams
```
#### Printed Parts Needed:

```
❏ Assembly Tool #2 - X Frame Marker
```
#### When complete, verify:

```
❏ One end of one X-Axis frame beam should have 9 holes, as shown in Figure
2.2.
❏ The other end of that beam, as well as both ends of all other X-Axis frame
beams should have 8 holes, as shown in Figure 2.3.
❏ All holes should be 6.5 mm
❏ None of these holes need to be tapped.
```

#### Build Steps:

1. Position Assembly Tool #2 on the top face of one beam with the number facing
    down and all tabs securely holding position as shown in Figure 2.1.
2. Mark all 4 corner holes with a center punch.
3. Mark the center hole with a center punch. The center hole is only used once and
    only on the first beam where a wire will be passed to connect an endstop switch.
4. Repeat steps 2.1 and 2.2 on all ends of the X-Axis frame beams, but do not mark the
    center hole at the other positions.
5. Flip X-axis frame piece so the side surface which was facing down ends up facing up.
6. Repeat steps 1 and 2, but do not mark the center hole at any of the positions.
7. Drill all marked points with an M6.5 bit.


### 3. Frame Assembly

```
Summary : Bolt together the prepared X and Y Axes, aligning the cable pass through
hole.
```
#### Hardware Needed:

```
❏ M4 Allen key
❏ Thread-locking fluid
❏ (24) M6X10mm Button Head Bolt
❏ (2) Prepared Y-Axis frame beams from step 1
❏ (3) Prepared X-Axis frame beams from step 2
```
#### When complete, verify:

```
❏ Your frame is fully squared after assembly.
❏ Each X-Axis beam has 4 bolts on each side attaching it to the Y-Axis beams,
for a total of 8 bolts on each X-Axis beam
❏ A wire can be passed through the spare hole between the 4 bolts circled in
Figure 3.2 and Figure 3.
```

#### Build Steps:

1. Place the prepared Y-Axis frame pieces parallel to each other with the holes facing
    up as shown in Figure 3.1. Please note the location of the Y-Axis frame beam which
    has 5 holes, circled in red.
2. Place the prepared X-Axis frame pieces on top of the Y-Axis frame pieces so that the
    holes align as shown in Figure 3.2. Ensure the X-Axis frame beam which the extra
    hole aligns with the Y-Axis frame beam, as circled in red.


3. Screw M6x10mm bolts into the Y-Axis frame beams to lightly fasten the X-Axis
    beams to the Y-Axis beams as shown in Figures 3.3 and 3.4.
4. Verify your frame is squared. Use the oversized M6.5 holes in the X-Axis to align the
    beams as needed.
5. Apply thread-locking fluid to all bolts
6. Flip the frame right side up so the X-Axis frame beams are on the bottom.


### 4. Y-Axis BF12 Mounting Prep

```
Summary : Create M6 threaded holes
```
#### Hardware Needed:

```
❏ ~6mm diameter marking tool (if used gently an M6 bit and a hammer can be
used or a center punch with a compatible spacer)
❏ M5 Drill bit
❏ M6 Tap bit
❏ Prepared Frame Assembly from step 3
❏ (6) M6x40mm Bolt
```
#### Printed Parts Needed:

```
❏ (2) BF12 Mount
```
#### When complete, verify:

```
❏ Both BF12 Mounts are installed with 3 bolts each
❏ Both BF12 Mounts are oriented correctly as shown in Figure 4.3 (bolts make
a triangle pattern pointing towards the back of the machine)
❏ Neither BF12 Mount is mounted over the cable access hole between the
Y-Axis frame beam and the X-Axis frame beam
```

#### Build Steps:

1. Place the BF12 Mount on the Y-Axis frame far from the side which has the cable
    pass through hole as shown in Figure 4.1. The end of the frame with the cable pass
    through hole is marked prohibited in red in the figure. The locations where BF
    Mounts should be marked and placed are circled in green.
2. Ensure the BF12 mount is oriented correctly, as shown in Figure 4.2. The three
    counterbored holes make a triangle pattern pointing towards the back of the
    machine.


3. Mark the three counterbored holes with your marking tool. Ensure the marks are
    adequately centered. If you’re doing this with a drill bit, be careful to hit the bit very
    lightly.
4. Repeat steps 4.2 and 4.3 on the other Y-Axis frame beam where circled in green in
    Figure 4.1.
5. Drill all 6 marked points with an M5 bit.
6. Thread all holes made in the previous step with an M6 tap bit.
7. Install both BF12 Mounts with M6x40mm bolts.


### 5. Y-Axis Linear Rail Prep

### Summary : Create M5 threaded holes

#### Hardware Needed:

```
❏ M4 Allen key
❏ M4.2 Drill bit
❏ M5 Tap bit
❏ ~6mm diameter marking tool (if used gently an M6 drill bit and a hammer
can be used or a center punch with a compatible spacer)
❏ (2) HGR20 Linear Rail
❏ M5x20mm bolts (comes with rail)
```
#### When complete, verify:

```
❏ All M5 holes drilled in this step are properly placed to align to the holes in the
HGR20 rails
❏ All M5 holes for the HGR20 rails are centered on their Y-Axis frame beams
❏ The HGR20 rails have some wiggle room so the final position and alignment
can be adjusted later when mounting the X-Axis gantry
```

#### Build Steps:

1. Double check the center line created in step 1.12. If inaccurate or missing please
    follow steps 1.10-1.13 to (re)create it.
2. Position HGR20 rail against the BF12 Mount as shown in Figure 5.
3. Ensure the HGR20 rail is centered on the Y-Axis frame beam. Use the center line to
    validate.
4. Using the 6mm marking tool, mark the center of the holes in the HGR20 rail which
    are closest and furthest from the BF12 Mount.
5. Repeat previous 3 steps for the other Y-Axis frame beam.
6. Drill the point marked in step 5.4 on both Y-Axis frame beams with an M4.2 bit.
7. Thread the holes made in the previous step with an M5 tap bit.
8. Remount the HGR20 rails and install M5xmm bolts into the holes made in the
    previous step.
9. Using the bolts installed above as soft anchors, mark the remaining mounting holes
    on the HGR20 rail. Ensure the rail maintains centered and positioned correctly
    throughout the entire marking process.
10.Remove the bolts and dismount the HGR20 rail again.
11.Drill the points marked in step 5.9 on both Y-Axis frame beams with an M4.2 bit
12.Thread the holes made in the previous step with an M5 tap bit.
13.Remount the HGR20 rails and loosely install all M5xmm bolts.


### 6. Y-Axis BK12 Mounting Prep

```
Summary : Create M6 threaded holes
```
#### Hardware Needed:

```
❏ ~6mm diameter marking tool (if used gently an M6 drill bit and a hammer
can be used or a center punch with a compatible spacer)
❏ M5 Drill bit
❏ M6 Tap bit
```
#### Printed Parts Needed:

```
❏ (2) BK12 Mount
```
#### When complete, verify:

```
❏ All M6 threaded holes for the BK12 mount are properly placed to align to the
HGR20 rails
```

#### Build Steps:

1. Double check the HGR20 rail is tightly pressed against the BF12 mount so that
    minimum play exists between them.
2. Position BK12 Mount against the HGR20 rail as shown in Figure 6.1.
3. Ensure the mount is positioned correctly. The three counterbored holes should
    form an arrow pointing away from the HGR20 rail as shown in Figure 6.2.


4. Mark the three counterbored holes with your marking tool. Ensure the marks are
    adequately centered. If you’re doing this with a drill bit, be careful to hit the bit very
    lightly.
5. Repeat the previous three steps on the other Y-Axis frame beam.
6. Drill all 6 marked points with an M5 bit.
7. Thread all holes made in the previous step with an M6 tap bit.
8. Set the BK12 mount aside, it will be installed later.


### 7. Y-Axis Roller Beam Prep

```
Summary : Create 4 M6 threaded holes & 1 M6.5 unthreaded hole on the top
side. Create 4 M6.5 unthreaded holes on the bottom side. Mount HGW20 block to
bottom side.
```
#### Hardware Needed:

```
❏ Center punch
❏ Drill
❏ M6.5 Drill bit
❏ M5 Drill bit
❏ M6 Tap bit
```
#### ❏ (2) Y-Axis roller beams - 70 mm

```
❏ (2) HGW20 Block
❏ (4) M6x20mm Button Head Bolt
❏ (1) M6x12mm Bolt
❏ Thread-locking fluid
❏ (Optional) Pencil
```
#### Printed Parts Needed:

```
❏ Assembly Tool #4 - Y Roller Bottom
❏ Assembly Tool #5 - Y Roller Top
```
#### When complete, verify:

##### ❏


#### Build Steps:

1. (Optional) Mark the side of the bam with an arrow pointing up to ensure you don’t
    lose orientation of the beam. All figures in this section will be marked so for ease of
    interpreting
2. Position Assembly Tool #4 on the bottom face of the Y-Axis frame beam with the
    number on the printed part facing the beam and all tabs securely holding position
    as shown in Figure 7.1.
3. Mark all holes with a center punch.
4. Drill the marked points with an M6.5 drill bit.
5. Position Assembly Tool #5 on the top face of one Y-Axis frame beam with the
    number on the printed part facing the beam and all tabs securely holding position
    as shown in Figure 7.2.


6. Mark all holes with a center punch.
7. Drill the marked center hole with an M6.5 bit.
8. Drill the remaining marked points with an M5 drill bit.
9. Thread all holes made in the previous step except the center hole with an M6 tap
    bit.
10.Apply thread-locking fluid to the M6x20 button head bolts.
11.Mount the HGW20 block to the bottom of the beam using the M6x20mm button
    head bolts as shown in Figure 7.3.
12.Install an M6x12mm bolt into the HGW20 on the side closer to the unthreaded
    center hole on the top surface of the frame beam as shown in Figure 7.4.


### 8. Y-Axis Mechanics Assembly

#### Hardware Needed:

```
❏ Mallet or hammer with a soft
buffer
❏ Assembled and prepared
frame from step 6
❏ (2) Assembled Y-Axis Roller
from previous step
❏ (2) BF12
❏ (2) BK12
❏ (2) Ball screw with attached nut
```
- **NEVER SEPARATE!**
❏ (6) M6x40mm bolt
❏ (12) M5x95mm bolts

#### Printed Parts Needed:

```
❏ (2) BK12 Mount
❏ (2) Ball Screw Face Plate Front
❏ (2) Ball Screw Face Plate Rear
```
#### When complete, verify:

##### ❏


#### Build Steps:

1. Ensure the assembled frame has two BF12 mounts and both HGR20 rails installed.
    The BK12 mount should not be installed as it will block the HGW20 block from being
    installed onto the rails. The frame should look like Figure 8.1.
2. Gently install both of the assembled Y-Axis rollers onto the HGR20 rail as shown in
    Figure 8.2. Their location on the rail does not yet matter.


3. Install both BK12 Mounts onto the tapped holes created in step 6 using M6x40mm
    bolts as shown in Figure 8.3.
4. Insert a ball screw into a BK12 oriented as shown in Figures 8.4, 8.5, and 8.6. You will
    likely need to lubricate the ball screw and the bearing inside the BK12 and gently
    persuade the BK12 on. Be very careful to maintain proper alignment as the low
    tolerances mean any misalignment will cause the parts to jam and become damage.


5. Screw the retainer nut onto the ball screw behind the BK12 as shown in Figure 8.7
    and 8.8. Ensure it is securely tightened against the BK12.
6. Tighten the set screw in the retainer nut so the retainer nut can no longer move.
7. Move the ball screw nut close to the BK12 to minimize future work to accomplish
    the same.
8. Place the Ball Screw Face Plate Front directly behind the ball screw nut as shown in
    Figures 8.9 and 8.10.


9. Pass the empty end of the ball screw through one of the Y-Axis roller beams, the
    result should look like Figure 8.11 and 8.12.
10.Pass the inset face of the Ball Screw Face Plate Rear over the unused side of the ball
    screw and slide it all the way up the screw. Insert the inset side of the printed part
    into the Y-Axis roller beam as shown in Figure 8.13.
11.Attach the ball screw nut to the Y-Axis roller assembly using M5x95mm bolts
    passing the bolts all the way through both printed plates and M5 nuts on the other
    side as shown in Figure 8.14 and 8.15. Only screw these finger tight as they will need
    to be removed again later to install the endstop wire.


12.Finally install a BF12 onto the empty end of the ball screw.
13.Repeat previous 7 steps with other ball screw.
14.Install both BF12s onto their mounts using M6x50mm bolts. These screw directly
into the plastic. **NOTE:** If you used PLA for the printed mounts be careful to screw
the bolts in slowly so as not not cause the plastic to melt around the thread due to
friction. To avoid this, you may wish to pre-thread the printed parts with a tap bit or
by preinstalling an M6 bolt and removing it.
15.Install both BK12s onto their mounts using M6x50mm bolts. These screw directly
into the plastic. **NOTE:** If you used PLA for the printed mounts be careful to screw
the bolts in slowly so as not not cause the plastic to melt around the thread due to
friction. To avoid this, you may wish to pre-thread the printed parts with a tap bit or
by preinstalling an M6 bolt and removing it.
16.Bring the Y-Axis rollers as close as possible to the BK12 end of the rail as shown in
Figure 8.16


### 9. Z-Axis Roller Beam Prep

#### Summary : Create M6 threaded holes and M6.5 unthreaded holes

#### Hardware Needed:

```
❏ Center punch
❏ Drill
❏ M5 Drill bit
❏ M6.5 Drill bit
❏ M6 Tap bit
❏ Pencil
❏ (2) Z-Axis roller beams - 130 mm
❏ Z-Axis Faceplate
❏ (8) M6x15mm Button Head Bolts
❏ ~6.5mm diameter marking tool (if used gently an M6.5 drill bit and a hammer
can be used or a center punch with a compatible spacer)
❏ ~5mm diameter marking tool (if used gently an M5 drill bit and a hammer
can be used or a center punch with a compatible spacer)
❏ (2) HGR20 Linear Rail
❏ M5x20mm bolts (comes with rail)
```
#### Printed Parts Needed:

```
❏ Assembly Tool #7 - X Axis Roller
❏ Assembly Tool #8 - Z Face/Rail Top
❏ Assembly Tool #9 - Z Face/Rail Bottom
❏ Center Line Marker Tool
❏
```
#### When complete, verify:

##### ❏


#### Build Steps:

1. (Optional) Mark the side of each beam uniquely so they do not get mixed up. All
    figures in this section will be marked with a “T” and “B” on the side which will touch
    the faceplate for ease of interpreting.
2. Position the Center Line Marker Tool on the top face as shown in Figure 9.1.
3. Place a pencil or other marking tool at the center of the v shaped grove on the
    Center Line Marker Tool and hold it there securely.
4. Run the Center Line Marker Tool down the length of the beam while using the
    marking tool to mark the center. Measure your centerline at several places to
    ensure it is indeed properly centered.
5. Repeat previous 3 steps for the other Z-Axis roller beam.
6. Find and mark the center point on the lines on each of the faces marked above.
7. Position Assembly Tool #8 on the front face of the top Z-Axis roller beam with the
    number on the printed part facing the beam and all tabs securely holding position
    as shown in Figure 9.2.
8. Mark all three holes with a center punch.
9. Position Assembly Tool #9 on the front face of the bottom Z-Axis roller beam with
    the number on the printed part facing the beam and all tabs securely holding
    position as shown in Figure 9.3.


10.Mark all three holes with a center punch.
11.Drill the marked points on the ends both beams with an M5 drill bit. You should
have created 4 M5 holes in total in this step.
12.Drill the marked points on the inside of both beams with an M6.5 drill bit. You
should have created 2 M6.5 holes in total in this step.
13.Thread the 4 M5 holes created above with an M6 tap bit.
14.Position Assembly Tool #7 on the top or bottom face of a Z-Axis roller beam with the
square hole in the center of the printed part aligned to the center mark made in
step 9.6.
15.Mark the 4 circular holes with a center punch.
16.Repeat previous 2 steps for all top and bottom faces of both Z-Axis roller beams.

17. **ON BOTH BEAMS ONLY ON THE BOTTOM FACES** drill all four marked points of
    each Z-Axis roller beam with an M6.5 drill bit.
18. **ON THE BOTTOM BEAM ONLY ON THE TOP FACE** drill all four marked points with
    an M6.5 drill bit.
19. **ON THE TOP BEAM ONLY ON THE TOP FACE** drill **ONLY THE TWO POINTS AWAY**
    **FROM THE FACE MARKED** with an identifying letter with an M6.5 drill bit.
20.Drill the remaining two points on the top face with an M5 drill bit.
21.Thread the two holes made in the previous step with an M6 tap bit.
22.Mount the top and bottom roller beams onto the Z-Axis faceplate using 4 M6x15mm
    button head bolts as shown in Figure 9.4.


23.Get the top and bottom roller beams as parallel as possible.
24.Mark the 6 holes circled in Figure 9.4 with a self centering marking tool.
25.Dismount the top and bottom roller beams from the faceplate.
26.Drill the marked points on the ends both beams with an M5 drill bit. You should
have created 4 M5 holes in total in this step.
27.Drill the marked points on the inside of both beams with an M6.5 drill bit. You
should have created 2 M6.5 holes in total in this step.
28.Thread the 4 M5 holes created above with an M6 tap bit.
29.Remount the top and bottom roller beams onto the Z-Axis faceplate using 8
M6x15mm button head bolts.
30.Mount HGR20 rail on the Z-Axis faceplate using M5x20mm bolts as shown in Figure
9.5.


31.Mount the HGW20 block to the inside faces of top and bottom beams using the
M6x20mm button head bolts as shown in Figure 9.6 and 9.7.



### 10. X-Axis Gantry Prep

#### Summary : Create M6 threaded holes and M6.5 unthreaded holes

#### Hardware Needed:

#### ❏ Assembled frame from step 8

#### ❏ Prepared Z-Axis Faceplate from step 9

```
❏ X-Axis gantry beam
❏ Double sided tape
❏ Center punch
❏ ~6mm diameter marking tool (if used gently an M6 bit and a hammer can be
used or a center punch with a compatible spacer)
```
#### Printed Parts Needed:

```
❏ Assembly Tool #6 - X Gantry
❏
```
#### When complete, verify:

##### ❏


#### Build Steps:

1. The X-Axis gantry components need to be testfit in order to find the locations they
    will be affixed. To begin, place the gantry beam on the Y-Axis roller beams in the
    frame completed in step 8.
2. Place one HGR20 rail on the top surface and position a BK12 mount and a BF12
    mount around it. Finally, place a X-Axis motor mount on the beam and reposition all
    components until desired configuration is found. Figure 10.1 shows an example of
    this process with the NEMA 17 dual motor option.
3. Ensure the BF12 mount is oriented correctly, as shown in Figure 10.2. The three
    counterbored holes make a triangle pattern pointing away from the HGR20 rail.


4. Mark the three counterbored holes with your marking tool. Ensure the marks are
    adequately centered. If you’re doing this with a drill bit, be careful to hit the bit very
    lightly.
5. Ensure the BK12 mount is oriented correctly. The three counterbored holes should
    form an arrow pointing away from the HGR20 rail as shown in Figure 10.3.
6. Mark the three counterbored holes with your marking tool. Ensure the marks are
    adequately centered. If you’re doing this with a drill bit, be careful to hit the bit very
    lightly.
7. Ensure the motor mount is oriented correctly. If you are using the dual NEMA 17
    mount it should be oriented as shown in Figure 10.3. If you are using the NEMA 23
    mount it should be oriented as shown in Figure 10.4.


8. Mark the two counterbored holes with your marking tool. Ensure the marks are
    adequately centered. If you’re doing this with a drill bit, be careful to hit the bit very
    lightly.
9. Mark the positions of the BK12 mount and BF12 mount on the gantry where they
    meet the HGR20 rail.
10.Dismount all components and remove the rail from the frame assembly.
11.Drill all points marked above with an M5 bit.
12.Thread all holes made in the previous step with an M6 tap bit.
13.Place Assembly Tool #6 on the Y-Axis roller as shown in Figure 10.5. Ensure all holes
    on the assembly tool align to the holes already existing in the Y-Axis roller beam.
14.Place a piece of double sided tape on the assembly tool.
15.Place the X-Axis gantry beam back in position it aligns with the Y-Axis roller beams.
    The double sided tape should stick to the gantry beam and hold the position of the
    assembly tool.
16.Gently lift the gantry and assembly tool so their relative positions do not shift.
17.Mark the 5 holes with a center punch.
18.Repeat previous 5 steps on the other Y-Axis roller and unmarked end of the X-Axis
    gantry beam.
19.Drill all marked points with an M6.5 bit.


### 11.X-Axis Gantry HGR20 Mount

#### Summary : Create M6 threaded holes and M6.5 unthreaded holes

#### Hardware Needed:

```
❏ X-Axis gantry beam
❏ (2) HRG20 rail
❏ Center punch
❏ ~6mm diameter marking tool (if used gently an M6 drill bit and a hammer
can be used or a center punch with a compatible spacer)
```
#### Printed Parts Needed:

```
❏ Center Line Marker Tool
❏
```
#### When complete, verify:

##### ❏


#### Build Steps:

1. Position the Center Line Marker Tool on the top face of the gantry beam of as
    shown in Figure 11.1.
2. Place a pencil or other marking tool at the center of the v shaped groove on the
    Center Line Marker Tool and hold it there securely.
3. Run the Center Line Marker Tool down the length of the beam while using the
    marking tool to mark the center. Measure your centerline at several places to
    ensure it is indeed properly centered.
4. Flip the beam over and repeat previous 3 steps for the underside of the gantry
    beam.
5. Position HGR20 rail on the top face within the marks made in step 10.9.
6. Ensure the HGR20 rail is centered on the X-Axis gantry beam. Use the center line to
    validate.
7. Using the 6mm marking tool, mark the center of the first and last holes in the
    HGR20 rail.
8. Flip the beam over and repeat the last 2 steps for the underside of the gantry beam.
9. Drill the points marked in the last two steps on both sides of the gantry beam with
    an M4.2 bit.
10.Thread the holes made in the previous step with an M5 tap bit.
11.Remount the HGR20 rails and install M5xmm bolts into the holes made in the
    previous step.
12.Using the bolts installed above as soft anchors, mark the remaining mounting holes
    on the HGR20 rail. Ensure the rail maintains centered and positioned correctly
    throughout the entire marking process.
13.Remove the bolts and dismount the HGR20 rail again.
14.Drill the points marked in step 11.12 on both sides of the gantry beam with an M4.2
    bit
15.Thread the holes made in the previous step with an M5 tap bit.
16.Remount the HGR20 rails and loosely install all M5xmm bolts.


### 12.X-Axis Gantry Assembly

#### Summary : Create M6 threaded holes and M6.5 unthreaded holes

#### Hardware Needed:

```
❏ Prepared Z-Axis Faceplate from step 9
❏ Prepared X-Axis gantry beam with HGR20 rails mounted from step 16
❏ Assembled frame from step 8
```
#### Printed Parts Needed:

```
❏ Center Line Marker Tool
❏
```
#### When complete, verify:

##### ❏


#### Build Steps:

1. Place the X-Axis gantry beam with the HGR20 rail attached onto the Y-Axis roller
    beams on the frame.
2. The HGR20 rail should be lightly attached to the X-Axis gantry so that it can be
    wiggled without much force.
3. Slide the assembled Z-Axis onto the X-Axis gantry HGR20 rail as shown in Figure
    12.1.
4. Slide the Z-Axis assembly back and forth across the X-Axis rails to self align. You may
    need to readjust the bolts holding the HGW blocks on the Z-Axis.
5. Tighten the bolts on the X-Axis gantry HGR20 rail as you side the Z-Axis assembly
    back and forth. When all the bolts on the HGR20 are tightened the Z-Axis should be
    able to smoothly slide along the X-Axis gantry.
6. Attach the X-Axis gantry to the Y-Axis rollers as shown in Figure 12.2 using
    M6x10mm button head bolts on both ends. You will need to put a long allen key
    through the M6 threaded holes created for mounting the BK12, BF12, and X-Axis
    motor to access the bolts.


7. Install the BF12 mount onto the tapped holes using M6x40mm bolts.
8. Install the BK12 mount onto the tapped holes using M6x40mm bolts.
9. Insert a ball screw into a BK12 oriented as shown in Figures 12.3, 12.4, and 12.5. You
    will likely need to lubricate the ball screw and the bearing inside the BK12 and gently
    persuade the BK12 on. Be very careful to maintain proper alignment as the low
    tolerances mean any misalignment will cause the parts to jam and become damage.


10.Screw the retainer nut onto the ball screw behind the BK12 as shown in Figure 12.6
and 12.7. Ensure it is securely tightened against the BK12.
11.Tighten the set screw in the retainer nut so the retainer nut can no longer move.
12.Place the Ball Screw Face Plate Front directly behind the ball screw nut as shown in
Figures 12.8 and 12.9.


13.Pass the empty end of the ball screw through the top X-Axis roller beam, the result
should look like Figure 12.10 and 12.11.
14.Pass the inset face of the Ball Screw Face Plate Rear over the unused side of the ball
screw and slide it all the way up the screw. Insert the inset side of the printed part
into the X-Axis roller beam as shown in Figure 12.12.
15.Attach the ball screw nut to the X-Axis roller assembly using M5 threaded rod,
passing the bolts all the way through both printed plates. Attach M5 nuts both ends
of the threaded rod as shown in Figure 12.13 and 12.14. Only screw these nuts
finger tight as they will need to be removed again.


16.Finally install a BF12 onto the empty end of the ball screw. Your assembly should
look like Figure 12.15.


### 13.Z-Axis Motor Mount

#### Summary : Create M6 threaded holes and M6.5 unthreaded holes

#### Hardware Needed:

```
❏ Prepared frame from step 12
❏ 608 bearing
❏ Motor-to-T8 coupler
❏ (4) M3x10mm (NEMA 17 version only)
❏ (4) M5x20mm (NEMA 23 version only)
```
#### Printed Parts Needed:

```
❏ Z-Axis NEMA mount
❏ Bearing washer (NEMA 23 version only)
❏
```
#### When complete, verify:

##### ❏


#### Build Steps:

1. Insert the 608 bearing into the Z-Axis NEMA mount as shown in Figure 13.1.
2. _NEMA 23 only_ - Add the 3d printed washer to allow the bearing to support and rotate
    with the motor coupler.
3. Place the coupler over the 608 bearing as shown in Figure 13.3. Ensure the coupler
    is oriented to accept the motor shaft on the top and the Z-Axis threaded rod below.


4. Place NEMA motor on mount and ensure the shaft seats into the coupler.
5. Tighten the set screw on the motor end of the coupler to affix it to the motor shaft.
6. Insert motor mounting screws. For the NEMA 17 version these will be M3x10mm
    bolts inserted into the motor through the holes on the bottom of the printed part.
    These are marked in Figure 13.4. For the NEMA 23 version these will be M5x20mm
    bolts inserted through the motor into the 3d printed motor mount from above as
    shown in Figure 13.5
7. Install the assembled mount onto the Z-Axis assembly. Ensure the HGR20 rail fully
    seats into the slots on the underside of the mount.


8. Secure the mount to the Z-Axis assembly with two M6x30mm bolts as shown in
    Figure 13.7.


### 14.Z-Axis Mechanics Assembly

#### Summary : Create M6 threaded holes and M6.5 unthreaded holes

#### Hardware Needed:

```
❏ Prepared frame from step 13
❏ T8 threaded rod
❏ T8 nut
❏ Lighter or Blowtorch
❏ (2) HGW20 Block
❏ (4) M2x30mm bolts
```
#### Printed Parts Needed:

```
❏ T8 Riser
❏
```
#### When complete, verify:

##### ❏


#### Build Steps:

1. Heat the T8 nut with the lighter or blowtorch and press fit it into the printed T8 riser.
2. Secure the T8 nut in place with 4 M2x30mm bolts.
3. Install the T8 threaded rod into the Z-Axis coupler and tighten the set screw to
    secure it.
4. Align the two HGW20 blocks on either side of the assembled T8 riser as shown in
    Figure 14.1.
5. Slide the assembled T8 riser and HGW20 blocks onto the Z-Axis HGR20 rails from
    below as shown in Figure 14.2.


