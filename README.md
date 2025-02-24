# grandMA3-Chataigne-Module

A Chataigne module to control grandMA3 via OSC

## Purpose

This Chataigne module facilitates the mapping of external sources to grandMA3 via the OSC interface. The faders and buttons of executors as well as directly of sequences can be changed. Of course there is also a function to send commands (cmd) to grandMA3. For all those who only use an onPC node there is the possibility to toggle "blind" and "freeze" and display the status for example on a midi controller.

## Features

The following functions are implemented in the plugin:

- Move Executor Fader
- Push Executor Button
- Move Sequence Fader
- Push Sequence Button
- Move GrandMaster Fader
- Move SpeedMaster Fader
- Turn Encoder
- Set Preview
- Set Blind
- Set Freeze

The range of functions depends on the interface. For the executor faders and buttons, the function is determined by GrandMA3 on the playback page. The sequence faders and buttons can take on any functionality. So it is possible for example to map "Swop", "Speed", "Flash" and "Learn" of a sequence without making a setting in GrandMA3.

## Usage

Activate OSC in grandMA3 in the "In & Out" menu. The OSC input must be activated globally (top right) and an input source must be created. The screenshot shows a simple configuration as an example.

![screenshot](https://github.com/yastefan/grandMA3-Chataigne-Module/blob/main/screenshot.png)
