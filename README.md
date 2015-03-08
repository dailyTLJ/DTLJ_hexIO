# DTLJ_hexIO

Custom circuit board to connect 16 units of an analog sensor and a LED. Control via a 16-channel Analog Multiplexer and a 16-channel Constant-Current LED driver (+ shifter register). The boards are chainable besides the analog output of the multiplexers. 

v1 has SOIC packages for the two chips, and through-hole packages for all other parts, for easier soldering. 

* 2-layer board
* 3.4 x 2.9 inches
* 35 mil power traces, 20 mil default traces
* 13 mil minimum drill size
* 10 mil clearance btw. traces

<p align="center">
	<img src="https://raw.github.com/dailyTLJ/DTLJ_hexIO/master/dtlj_hexIO.png"/>
</p>

What it looks like assembled

<p align="center">
	<img src="https://raw.github.com/dailyTLJ/DTLJ_hexIO/master/assembled.jpg"/>
</p>


## Things to change in next iteration

* indicator of LED polarity (on power LED, and sensor-module LEDs)
* analog output pin hole too big