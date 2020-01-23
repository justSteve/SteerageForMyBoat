# SteerageForMyBoat
Towards a dedicated hydrualic system where digital input at the helm is transposed to the analog output of the system's electric pump.

I operate a houseboat on the Mississippi out of Trempealeau Wisconsin. It's powered by twin 60hp outboards. I'm upgrading the vessel's steering system from the original hydraulics where the helm is connected to the stern by 40' feet of copper tubing. I want to replace that copper run with wires and position a hydraulic pump at each of the outboard's steering cylinder.

The helm would replace the existing pilot wheel (helm pump) with electronic sliders - one for each of the outboards. Think of a soundboard's 'slider' control and turn it horizontal.  When the slider is centered it sets the motors' steerage to be dead ahead. Move the slider to left or right to steer the vessel to port or starboard. Add an other control in the the form of a knob that would control the rate of turn and you've replicated all the features that a conventional helm pump provides.

The output of the helm mounted steerage sliders and rate-of-turn knobs is captured by code running on a Raspberry Pie or Arduino and translated into voltages that are sent to a pair of hydraulic pumps which turn to port or starboard at the given rate of turn (the pump's rpm). 

The vision is an open source, fly by wire steering system that is built with off-the-shelf hardware controlled by code contributed to this repo.
