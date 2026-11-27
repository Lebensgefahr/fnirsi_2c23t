# F2C23T-EN-V2.0.3.bin

## Changes

- Removed the graphical artifact at the top of the oscilloscope display.
- Changed the CH1 waveform color from cyan to yellow.
- Changed the CH1 measurement text color from cyan to yellow.
- Changed the CH1 vertical position marker color from cyan to yellow.

# F2C23T-EN-V2.2.0.bin

## Changes

- Implemented an FPGA-based hardware trigger for both channels, featuring 
  signal pre-trigger history and support for AUTO, NORMAL, SINGLE, RISE, and FALL modes.
  It can capture short single pulses (e.g., 125 ns at a timebase of up to 5 µs which is not possible in stock firmware).
- Fixed a display artifact affecting the MOVE and CURSOR menus when the signal generator is turned off.