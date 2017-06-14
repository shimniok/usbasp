# Introduction

This is an implementation of Fischl's usbasp

USBasp is a USB in-circuit programmer for Atmel AVR controllers consisting
of an ATMega88 or ATMega8 and a few of passive components.

The programmer uses a firmware-only USB driver, no special USB controller
is needed.

## Features

- Works under multiple platforms. Linux, Mac OS X and Windows are tested.
- No special controllers or smd components are needed.
- Programming speed is up to 5kBytes/sec.
- SCK option to support targets with low clock speed (< 1,5MHz).
- Planned: serial interface to target (e.g. for debugging).

# LICENSE

## Electronics

The circuit design is based on Fischl's and is distributed under the terms and conditions of the
MIT license (see ```electronics/LICENSE```)

# LIMITATIONS

## Hardware

This package includes a circuit diagram. This circuit can only be used for
programming 5V target systems. For other systems a level converter is needed.

# FIRMWARE

See http://www.fischl.de/usbasp/ for details on firmware: license, flashing, installation, etc.

Excerpted from Readme.txt, originally:
2011-05-28 Thomas Fischl <tfischl@gmx.de>
http://www.fischl.de
