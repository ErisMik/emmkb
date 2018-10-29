# EEMKB

An ultra-thin mechanical keyboard

## Background

I wanted a keyboard that met all the requirements below. I couldn't find one, so I decided to make one myself!

* As thin and portable as possible, no thicker than my laptop (Dell XPS 13 9360, approx. 1.2cm)
* Mechanical keyboard switches
* 60/65 % layout
	* Full size modifier keys
	* Independent arrow keys
	* Has Home, End, Page Up and Page Down keys
	* ISO/ANSI based layout (ie. Non-ortholinear)

## Design

I found a keyboard layout from OLKB keyboards, unfortunately since they now focus on ortholinear keyboards, they no longer sell this layout. Luckily however, they do provide the .dxf drawings! They are a bit hidden so the original designs are included in this repository.

At the time I did not have access to a CNC or Laser Cutter, so building it out of wood or aluminum was not an option. It had to be 3D printed, which was still good since the plastic could be made light, however it limited how thin I could make the case.

The original designs were for Cherry MX type switches. In order to meet my thickness requirements, I decided to use the `Choc` switches from Chinese manufacturer Kaihua/Kailh Electronics.

Controller is a Teensy 3.2. This micro-controller was chosen since it is extremely thin, simple to wire up to the switches and compatible with the popular [QMK Firmware](https://github.com/qmk/qmk_firmware)

My design:
* 3D printed: PLA, 2-pieces for printing on small print bed
* Switch holes should be for `Choc` switches

## Construction

[Excellent construction guide](https://deskthority.net/workshop-f7/brownfox-step-by-step-t6050.html)

Parts List:
* 120+ Kailh `Choc` switches, any type
* 120+ 1N4148 Diodes
* Teensy 3.2
* Top plate
* Bottom Plate
* Lots of wire

*Pictures coming soon*

## Software

*Coming Soon*