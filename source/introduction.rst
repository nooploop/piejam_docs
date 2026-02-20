Introduction
============

PieJam is a simple audio mixer for Raspberry Pi. It provides a graphical touch
interface which should be used with the official 7" Raspberry Pi touchscreen.
It needs some external audio interface, most USB based ones should work.

This documentation is work in progress and should give a brief overview of
the functionality.

Features
--------

* Mixing & Routing

  * Dynamic input/output configuration
  * Flexible channel routing
  * Panning, stereo balance, volume
  * Mute and solo

* Effects & Processing

  * Per-channel FX chains
  * Built-in modules: Dual Pan, Filter, Utility
  * Analysis tools: Oscilloscope, Spectrum Analyzer, Tuner
  * LADSPA plugin support

* Control & Automation

  * MIDI CC/Pitchbend parameter control

* Sessions

  * Session recording
  * Session management

Usage Example
-------------

PieJam is quite flexible and can be used in different scenarios. The main goal
is to mix multiple audio sources. The number of audio sources you can mix depends
usually on the number of inputs your audio interface provides.