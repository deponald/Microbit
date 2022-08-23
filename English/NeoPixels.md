# NeoPixel
Neopixels are strings of connected RGB LEDs that can be programmed with the micro:bit to show cool patterns.


## Connecting the NeoPixel hardware to the micro:bit
1. GND wire to micro:bit GND terminal
2. VCC wire to micro:bit 3V terminal
3. IN wite to micro:bit P0 terminal

## Adding NeoPixel library to the code editor
1. Select the +Extensions from the function block category list
2. Enter "neopixel" on the "Search or enter project URL..."  box
3. Choose neopixel
4. Now you have a new function block category "Neopixel"


## Your first Neopixel code
Make code that:
- After pushing switch A: Set the first neopixel to a color (randomly) selected from a pre-configured list
- After pushing switch B: Rotate the neopixel string by one pixel
- After pressing switch A+B: Start or stop auto rotating all neopixel bits with a certain speed
- increase the auto rotating speed when the micro:bit is tilted right
- decrease the auto rotating speed when the micro:bit is tilted left

*HINTS:*
- Configue you neopixel at P0 with 8 LEDs in GRB format
- Use Neopixel function block "Range" to select individual LEDs
- Use the "Strip Show" after a shift or rotate to see the effect
- Use an array for the pre-configured list
- Some hexadecimal values for primary colors:
  - Red: 0xff0000 = 16711680
  - Green: 0x00ff00 = 65280
  - Blue: 0x0000ff = 255
- Also add 0 to the list so you can remove colored LED's with the A + B switches
  