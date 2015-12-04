# Cosa-CustomBoard

The Cosa-CustomBoard repository is a template for adding custom
boards that use the Cosa Arduino core.

# Install

To use this template you must download and install the [Arduino IDE]
(http://www.arduino.cc/en/Main/Software) (or GCC AVR toolchain) and
[Cosa] (https://github.com/mikaelpatel/Cosa).

Create the directory Cosa-CustomBoard in your sketchbook hardware
directory. Download and unzip the Cosa-CustomBoard-master into your
sketchbook hardware/CustomBoard directory. Rename from
Cosa-CustomBoard-master to avr.

Start the Arduino IDE and the CustomBoard example should be found in
Tools>Board menu.

# Configuration

To add your own board update the following.

1. Rename CustomBoard to your board/product family.
2. Rename variants/VENDOR to the name of your company.
3. Copy the contents of variants/VENDOR/PRODUCT for each board in your
product family.
4. Rename variants/VENDOR/PRODUCT to the name of your board.
5. Modify variants/VENDOR/PRODUCT files; Board.h, Board.hh,
Board.map. The example files are for a breadboard ATmega328P. See the
Cosa/Boards for other examples (and supported AVR MCUs).
6. Modify boards.txt; each board should have properties for the build
in the Arduino IDE. See Cosa boards.txt for further examples.



