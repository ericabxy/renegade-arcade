Controller Theory
=================

A working concept regarding how games and game environments should be controlled.


Linux Gamepad
-------------

The Linux kernel defines a standardized gamepad that reflects modern game console controllers and many legacy controllers. The gamepad layout somewhat resembles the Classic Controller (2006) with renamed buttons and consideration for analog alternatives.

- Four "face" buttons designated North, West, South, and East.
- Four directional "pad" buttons which may be analog or digital.
- Four shoulder "trigger" buttons which may be analog or digital.
- Two "thumb" analog joysticks.
- Three "menu" buttons.
- Force feedback "rumble" feature.

### Steam Controller

#### Axes

0. X (left stick horizontal)
1. Y (left stick vertical)
2. RX (right pad horizontal)
3. RY (right pad vertical)
4. HAT0X (left pad horizontal)
5. HAT0Y (left pad vertical)
6. HAT2X (left trigger)
7. HAT2Y (right trigger)

#### Buttons

0. Thumb (left pad touch)
1. Thumb 2 (right pad touch)
2. South (<span class="joystick-key green">A</span> button)
3. East (<span class="joystick-key red">B</span> button)
4. North (<span class="joystick-key blue">X</span> button)
5. West (<span class="joystick-key yellow">Y</span> button)
6. Trigger Left (left shoulder)
7. Trigger Right (right shoulder)
8. Trigger Left 2 (left trigger)
9. Trigger Right 2 (right trigger)
10. Start (<span class="joystick-key">►</span> button)
11. Select (<span class="joystick-key">◄</span> button)
12. Mode (guide button)
13. Thumb Left (left stick click)
14. Thumb Right (right pad click)
15. Gear Down (right paddle click)
16. Gear Up (left paddle click)
17. Directional Pad Up (left pad click <span class="joystick-key">&#x2BC5;</span>)
18. Directional Pad Down (left pad click <span class="joystick-key">&#x2BC6;</span>)
19. Directional Pad Left (left pad click <span class="joystick-key">&#x2BC7;</span>)
20. Directional Pad Right (left pad click <span class="joystick-key">&#x2BC8;</span>)

### Wiimote System


Mupen64Plus
-----------

The emulator Mupen64Plus defines and standardizes a specific game console controller as well as how to map the controls of various joysticks and a computer keyboard to this standard.

	DPad U = "W"
	DPad L = "A"
	DPad D = "S"
	DPad R = "D"
	Start = "Enter"
	Z Trig = "Z"
	L Trig = "X"
	R Trig = "C"
	A Button = "LShift"
	B Button = "LCtrl"
	C Button U = "I"
	C Button L = "J"
	C Button D = "K"
	C Button R = "L"
	Control Stick = "→", "←", "↓", "↑"


LibRetro Retropad
-----------------

LibRetro defines a standard virtual game controller used to play a variety of emulated and original games. Keyboards and computer joysticks can map to this virtual gamepad in order to play any LibRetro game.


Xboxdrv
-------

Similar to Mupen64, Xboxdrv by Ingo Runke represents game input with an Xbox controller to which many input devices can be mapped and standardized.


Xemu
----

The original Xbox emulator Xemu implements a simple keyboard mapping to the original console's controller inputs.

	DPad U = "↑"
	DPad L = "←"
	DPad D = "↓"
	DPad R = "→"
	Back = ⌫
	Start = ↵
	L Trig = "W"
	R Trig = "O"
	White Button = "1"
	Black Button = "2"
	A Button = "A"
	B Button = "B"
	X Button = "X"
	Y Button = "Y"
	Left Stick = "E", "S", "D", "F"
	Right Stick = "I", "J", "K", "L"

- Left analog stick <span class="keyboard-key">E</span>, <span class="keyboard-key">S</span>, <span class="keyboard-key">D</span>, <span class="keyboard-key">F</span>
- Right analog stick <span class="keyboard-key">I</span>, <span class="keyboard-key">J</span>, <span class="keyboard-key">K</span>, <span class="keyboard-key">L</span>
- Left trigger <span class="keyboard-key">W</span>
- Right trigger <span class="keyboard-key">O</span>
- D pad <span class="keyboard-key">←</span>, <span class="keyboard-key">→</span>, <span class="keyboard-key">↓</span>, <span class="keyboard-key">↑</span>
- A button <span class="keyboard-key">A</span>
- B button <span class="keyboard-key">B</span>
- X button <span class="keyboard-key">X</span>
- Y button <span class="keyboard-key">Y</span>
- White button <span class="keyboard-key">1</span>
- Black button <span class="keyboard-key">2</span>
- Back button <span class="keyboard-key">⌫</span>
- Start button <span class="keyboard-key">↵</span>


Keyboard
--------

There are many considerations for supporting a [gaming keyboard](keyboard.html).

<table class="keyboard">
<tr>
	<td colspan="2">`</td>
	<td colspan="2">1</td>
	<td colspan="2">2</td>
	<td colspan="2">3</td>
	<td colspan="2">4</td>
	<td colspan="2">5</td>
	<td colspan="2">6</td>
	<td colspan="2">7</td>
	<td colspan="2">8</td>
	<td colspan="2">9</td>
	<td colspan="2">0</td>
	<td colspan="2">-</td>
	<td colspan="2">=</td>
	<td colspan="3">⌫</td>
</tr>
<tr>
	<td colspan="3">↹</td>
	<td colspan="2">A</td>
	<td colspan="2">Z</td>
	<td colspan="2">E</td>
	<td colspan="2">R</td>
	<td colspan="2">T</td>
	<td colspan="2">Y</td>
	<td colspan="2">U</td>
	<td colspan="2">I</td>
	<td colspan="2">O</td>
	<td colspan="2">P</td>
	<td colspan="2">[</td>
	<td colspan="2">]</td>
	<td colspan="2">\</td>
</tr>
<tr>
	<td colspan="4">⇪</td>
	<td colspan="2">Q</td>
	<td colspan="2">S</td>
	<td colspan="2">D</td>
	<td colspan="2">F</td>
	<td colspan="2">G</td>
	<td colspan="2">H</td>
	<td colspan="2">J</td>
	<td colspan="2">K</td>
	<td colspan="2">L</td>
	<td colspan="2">;</td>
	<td colspan="2">'</td>
	<td colspan="3">↵</td>
</tr>
<tr>
	<td colspan="5">⇧</td>
	<td colspan="2">W</td>
	<td colspan="2">X</td>
	<td colspan="2">C</td>
	<td colspan="2">V</td>
	<td colspan="2">B</td>
	<td colspan="2">N</td>
	<td colspan="2">M</td>
	<td colspan="2">,</td>
	<td colspan="2">.</td>
	<td colspan="2">/</td>
	<td colspan="4">⇧</td>
</tr>
<tr>
	<td colspan="4">LCtrl</td>
	<td colspan="4">LAlt</td>
	<td colspan="13">Space bar</td>
	<td colspan="4">RAlt</td>
	<td colspan="4">RCtrl</td>
</tr>
</table>

### Mnemonic keys

### Positional keys

WASD


Mouse
-----

Analog/motion control with modifiers. Mouse-only video game test cases:

- Ryzom
- Scorched 3D
- Warzone 2100

#### Relative

1. X Motion
2. Y Motion
3. Z Motion
4. Right X Motion
5. Right Y Motion
6. Right Z Motion
7. <s>Horizontal Wheel</s>
8. Dial Motion
9. <s>Wheel</s>
10. Misc Motion

#### Button

1. Left Button
2. Right Button
3. Middle Button
4. Scroll Up
5. Scroll Down
6. Scroll Left
7. Scroll Right
8. Side Button
9. Extra Button
10. Forward Button
11. Back Button
12. Task Button

### Compressed Button Notation

<table class="keyboard">
<tr>
	<td></td>
	<td></td>
	<td></td>
	<td>ZL</td>
	<td></td>
	<td></td>
	<td></td>
	<td>ZR</td>
	<td></td>
	<td></td>
	<td></td>
</tr>
<tr>
	<td></td>
	<td></td>
	<td></td>
	<td>CL</td>
	<td></td>
	<td></td>
	<td></td>
	<td>CR</td>
	<td></td>
	<td></td>
	<td></td>
</tr>
<tr>
	<td></td>
	<td>DU</td>
	<td></td>
	<td></td>
	<td></td>
	<td>SU</td>
	<td></td>
	<td></td>
	<td></td>
	<td>AU</td>
	<td></td>
</tr>
<tr>
	<td>DL</td>
	<td></td>
	<td>DR</td>
	<td></td>
	<td>SL</td>
	<td></td>
	<td>SR</td>
	<td></td>
	<td>AL</td>
	<td></td>
	<td>AR</td>
</tr>
<tr>
	<td></td>
	<td>DD</td>
	<td></td>
	<td></td>
	<td></td>
	<td></td>
	<td></td>
	<td></td>
	<td></td>
	<td>AD</td>
	<td></td>
</tr>
<tr>
	<td></td>
	<td></td>
	<td></td>
	<td>WL</td>
	<td></td>
	<td></td>
	<td></td>
	<td>WR</td>
	<td></td>
	<td></td>
	<td></td>
</tr>
</table>

