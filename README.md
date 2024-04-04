<h1>Ampsight - A configurable load for testing headphone amplifiers</h1>

<h2> Scope </h2>

Ampsight is a configurable load for testing the power output of headphone amplifiers. 

<h2> Key goals </h2>

The design goals are:

* Simplicity - not even power supply is necessary
* Ease of design, maintenance and configuration - no microcontrolers or firmware
* Instrumentation is external - bring your own measurement device
* Non inductive - good resistance performance accross frequencies
* Stable over temperature - can be used with more intense loads

<h2> Thoery of operation </h2>

Board uses a resistor bank configurable by a switching element. On current REV1 this is achieved by a 7 position DIP switch, which connects several Caddock resistors in parallel. This way many resistance values are achievable. 

After connected, the resistors are routed to input connectors that interface with the amplifier to be meausred. Today two types of inputs are available: 6.35mm (1/4 inch) jack and 4.4mm Pentaconn jack

The way to operate is - using a sound source, you program a 1khz tone to be played by the amplifier. Select a desired resistance value on ampsight, measure it using a multimeter. Connect the amplifier to ampsight and using a multimeter or osciloscope, take the alternate RMS voltage and use it in conjunction with resistance to calculate the power provided by the amplifier.

<h2> Resistance values </h2>

As of REV1 the resistance values are

* 3x 30R
* 2x 75R
* 2x 330R

<h3> Resistance combination possibilities and known headphone impedances </h3>

Coming soon. 

