Introduction
============

PieJam is a simple audio mixer for Raspberry Pi. It provides a graphical touch
interface which should be used with the official 7" Raspberry Pi touchscreen.
It needs some external audio interface, most USB based ones should work.

This documentation is work in progress and should give a brief overview of
the functionality.

Features
--------

* Dynamic configuration of inputs and outputs
* Panning, stereo balance and volume controls
* Mute and solo
* Flexible routing between mixer channels and signal sends
* Fx chain per mixer channel
* Fx modules:

  * Dual Pan
  * Filter
  * Oscilloscope
  * Spectrum Analyzer
  * Tuner
  * Utility

* Support for LADSPA plugins
* Parameter control through MIDI CC
* Session recorder

Usage Example
-------------

PieJam is quite flexible and can be used in different scenarios. The main goal
is to mix multiple audio sources. The number of audio sources you can mix depends
usually on the number of inputs your audio interface provides.