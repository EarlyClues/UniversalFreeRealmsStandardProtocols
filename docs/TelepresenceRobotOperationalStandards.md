Telepresence Robot Operational Standards Recommendations
========================================================

Preamble:
---------

*WHEREAS the emerging field of telepresence robotics is still in its infancy…*

&

*WHEREAS a diversity of form factors and functionality exist across telepresence robotics manufacturers and models…*

&

*WHEREAS few or little manufacturer-independent, neutral, interoperable nor “open” standards appear to be widely adopted within the field of telepresence robotics…*

---

**THE FOLLOWING recommendations are hereby set forth this 1416758896 (UTC) regarding Telepresence Robot Operational Standards.**

---

Preliminary Definitions:
------------------------

* “State” is understood as the current status of the telepresence robot unit, the activity of its sensors and output components, and its reception & transmission of remote control data.
* “Functionality” is understood as the physical/technological capabilities or capacities of the telepresence robot unit and its constituent components.
* “Controls” are understood as the mechanism or trigger whereby functionality may be accessed or activated by remote operator, or in some cases by local user, or robot-itself.

---

1. Access To State Data
=======================


State data of telepresence robot should be continuously available to both remote operator (sender), local user (receiver), and to the robot itself.

Recommended Minimum Available State Data:
-----------------------------------------

`State.battery` 
* .percent, .range
* .charging (“docked”)

`State.wifi`
* .percent

`State.localSensor`
* .audio (“can hear”)
* .video (“can see”)

`State.localOutput`
* .video (“what’s being displayed”)
* .audio (“audio monitor”)
* .controls (“action monitor”)

`State.activity`
* .active, inactive (“in use by remote operator,” ie “transmitting”)
* .operatorID (“who is driving”)
* .function (“current function”)

---

2. Discoverable Functionality & Controls
========================================


Available functionality and assigned controls should be accessibly displayed, readily apparent, easily discoverable and/or immediately available on request to both remote operator and local user.

Recommended Minimum Available Functionality:
--------------------------------------------

**Note: Locomotion and camera should be independently controllable.**

`Function.locomotion`
* .forward, .back
* .rotateLeft, .rotateRight
* .stop (“park”)

`Function.height`
* .up, .down

`Function.camera`
* .pan (.left, .right)
* .tilt (.up, .down)
* .zoom
* .lookDown (“second camera”)

`Function.modify.state`
* state.localSensor (“mute”)
* state.localOutput

`Function.endCall`

---

3. Reassignment & Customization of Controls
===========================================

A.) Controls triggering basic functionality should be assigned equally to keyboard shortcuts in addition to on-screen or mouse-action-based controls.

B.) Assignment of controls over all functionality should be easily re-assignable by remote operator, allowing for easy coordination among diverse input devices, operating systems, styles and form factors of remote control terminal.

C.) In certain cases, it may be desirable to allow the robot to control its own functionality (autonomy), and further standards & protocols should be carefully explored and put in place to equitably manage this.

---

4. Respect & Mutuality
======================

A.) Remote operators and local users should treat one another with respect & sympathy, recognizing the unique challenges and differences between ‘ordinary’ localized human-to-human interactions versus those mediated at a distance by a telepresence robot.

B.) Remote operators and local users should also treat with respect & sympathy the telepresence robot-itself, recognizing it as a ‘being’ in its own right—apart from its mere utility—with its own unique state-maintenance needs with which it may at times require assistance & sympathy from human handlers.


Concluding Notes
================

The recommendations set forth in this document are by no means meant to be exhaustive, but rather to give a starting point for further discussion and exploration amongst telepresence robotics stakeholders and interested parties as these technologies become more widespread and commonplace.

We welcome your comments, suggestions, corrections & improvements.
