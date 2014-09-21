harmonic-pasteurizer
====================

Audio-based device for measuring temperature for pasteurization applications

We have a design for a temperature sensor that outputs two frequencies:  a reference tone, associated with a reference temperature (72 C in the case of pasteurization), and a measurement tone, associated with a temperature probe to be placed in a heat bath.  As milk in the heat bath reaches the reference temperature, the measurement tone and the reference tone coincide -- indicating to the user that the pasteurization temperature has been achieved, so that the heat bath should then be turned off.

The approximate cost for this device (based on 555 timers, which are ubiquitous and cheap) is < $10.

http://youtu.be/d_dedJYEJbU

<img src="https://github.com/dwblair/harmonic-pasteurizer/blob/master/harmon.png">
