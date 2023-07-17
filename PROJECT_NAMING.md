# HW project naming

Hardware (mainly electronics) projects are named according to the scheme **RBxxyy-ProjectName**

where 
- **xx** is a two-digit category/platform prefix
- **yy** is a two-digit counter within a category

## HW Categories

- _xx = 32_: Electronics with an ESP32 MCU
- _xx = 03_: Electronics for the Pololu 3pi robot
- _xx = 01_: Electronics with a different MCU
- _xx = 00_: Electronics without an MCU

When adding a new HW project make sure to use a unique xxyy number.

Consider adding a new category when working with a new "platform".

# SW project naming

Software projects (libraries, firmwares, ...) can use the same RBxxyy prefix as the hardware they are targeting
or ignore this naming if they are not tied to a specific hardware.
