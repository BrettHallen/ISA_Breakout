# ISA Backplane Boards

## [ISA Penta Backplane](/ISA_Penta)
An attempt at a simple, five-slot ISA board mainly aimed at getting the [Multitech MPF-PC/500 CPU card](https://github.com/BrettHallen/MicroProfessor/tree/main/MPF-PC500) working.<br>

The Multitech card has no documentation (that I've been able to find) and apparently is designed for a "custom" ISA backplane.<br>

## ISA Breakout Board for Logic Analysers
Breakout board to simplify connecting an ISA card to a logic analyser.<br>

![ISA breakout board](/ISA_8bit/ISA_8bit_Logic_Analyser_Breakout_3D.png)

Thus I thought it might be useful to have an ISA backplane with all of the signals broken out to pin headers.<br>

This particular design only provides for +5VDC as that appears to be all that the Multitech CPU card requires - the -5V and ±12V pins are not connected.<br>

![MPF-PC/500 CPU card power](/ISA_8bit/MPF-PC500_power.jpg)

I've also included a 2x31 pin header (2mm pin pitch) to connect to the ISA backplane designed for the Book 8088 computer so that additional cards, like video & storage, might be added.<br>

## ISA Breakout Card for Logic Analysers
Planning to design an ISA card with pin headers for connection to a logic analyser.
