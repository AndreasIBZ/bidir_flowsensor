# bidirectional volumetric flow sensor

<p>
  <img src="https://github.com/AndreasIBZ/bidir_flowsensor/blob/master/screenshot_flowsensor.JPG" width="200" title="Flowsensor">
  <img src="https://github.com/AndreasIBZ/bidir_flowsensor/blob/master/screenshot_section_flowsensor.JPG" width="200" title="Flowsensor Section">
</p>

## Basic function
A flow through the orifice results in a higher static pressure on the inlet and a lower static pressure on the outlet. The difference is called static pressure drop and can be measured by a differential pressure sensor. The differential pressure is proportional to the flow to the power of 2.  

## Assembly
put a sealing O-Ring or abundance of silicone into the sealing groove of the connector fitting, screw the fitting into the threaded part of the orifice

## Sensitivity
Given an orifice with diameter of 8 mm and flow of air @ 100 l/min and you can expect pressure drops around 1000 Pa (10 mbar, 10 cm H2O), whereas @ 20 l/min you get ~ 40 Pa only. A flow-span of 1:10 will result in a differential pressure span of 1:100 (again the power of 2 relation). 

## Calibration
You will need a adjustable gas flow source (e.g. pressurized air + needle valve) and a accurate reference flow meter. To reduce turbulences the inlet and outlet tubing should be at least 10 times the diameter long and as straight as possible (no bends, ellbows, etc.). To calibrate a flow-span of 1:10 (eg. 6 ... 60 l/min) you will need a sensitive differential pressure sensor that can easily withstand 100 times the pressure at the lowest flow rate. I designed a DIY membrane type differential pressure sensor to meet this requirement - see @AndreasIBZ/pressuresensor

## Limits of this design
if 3D-printed achievable accuracy will vary due to varying surface an geometry quality

## License
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" property="dct:title" rel="dct:type">bidirectional volumetric flow sensor</span> by <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">@Andreas_IBZ (Telegram)</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
