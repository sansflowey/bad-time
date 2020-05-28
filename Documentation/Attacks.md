# Attacks

## Types ##

### Direction ###
An integer from 0 to 3. 0 is East, each increment is 90 degrees clockwise.

### Speed ###
Pixels per second. Multiply an original Undertale value with 30 (FPS) to get its equivalent.

### Color ###
0 for white, 1 for blue. Other colors (such as orange) may or may not be added in the future

### Time ###
Seconds

### Angle ###
Degrees

### Boolean ###
Just an integer 0 or 1

### Count ###
How many

### Spacing ###
Pixels

<hr />

### BoneH ###
Creates a horizontal bone

* XPosition
* YPosition
* Width
* Direction
* Speed
* Color

### BoneV ###
Creates a vertical bone

* XPosition
* YPosition
* Height
* Direction
* Speed 
* Color

### BoneHRepeat ###
Creates many horizontal bones

* StartX
* StartY
* Width
* Direction
* Speed
* Count
* Spacing

### BoneVRepeat ###
Creates many vertical bones

* StartX
* StartY
* Height
* Direction
* Speed
* Count
* Spacing

### SineBones ###
> Created out of laziness, probably shouldn't use.

Creates a series of bones that leaves a sine-wave gap in between them.

* Count
* Spacing
* Speed
* Height

### BoneStab ###
Wall of bones pops out of the side of the combat zone

* Direction
* Distance
* WarnTime
* StayTime

### GasterBlaster ###
Creates a Gaster Blaster, moves it into position, and fires

* Size
* StartX
* StartY
* EndX
* EndY
* EndAngle
* SpinTime
* BlastTime

### Platform ###
Creates a platform. BooleanReverse make it change direction

* X
* Y
* Width
* Direction
* Speed
* BooleanReverse

### PlatformRepeat ###
Creates many platforms

* StartX
* StartY
* Width
* Direction
* Speed
* Count
* Spacing

### HeartMode ###
Changes the behavior of the heart. 0 is for red, 1 is for blue.

* Mode

### HeartTeleport ###
Instantly moves the heart to a given position

* X
* Y

### HeartMaxFallSpeed ###
Sets the max fall speed. Useful for varying speeds of the slam attack

* MaxSpeed

### SansSlam ###
Slams the heart againist the combat zone

* Direction

### SansSlamDamage ###
Enables/disables slam damage

* BooleanEnabled
