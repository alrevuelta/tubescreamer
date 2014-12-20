# Description

This repository contains the schematics of a Tubescreamer like guitar pedal in EagleCad. This guitar pedal is a classical overdrive very well known among guitar players, specially in blues and rock style. It has several editions and modifications, such as TS-808, TS9 or TS10.

This schematics are based on the TS-808 edition, and the schematics found at gaussmarkov.net website.

<p align="center">
  <img src="TODO">
</p>


# Features

Note that the hardware available at the `hw` folder, has been designed and routed trying to avoid complex wiring. For example, the potentiometers are soldered directly to the PCB, so no wiring is needed for them. Also, the LED can be soldered to the PCB directly without extra wiring. All other connections, such as 3DPDT and in/out TRS jacks, are disposed in an order that tries to avoid wires crossing, making it cleaner that in other designs.

The pedal can be used with a 9v battery or connected to a DC source at the same voltage. Note that the typical low pass filter is included.

<p align="center">
  <img src="TODO">
</p>