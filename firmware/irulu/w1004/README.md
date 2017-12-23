irulu/w1004
---------------------------------------------

| Item                      | Description |
|---------------------------|-------------|
| Manufacturer              | iRULU |
| Device                    | Walknbook (W1004) |
| Website                   | https://www.irulu.com/walknbook-laptop-32gb-rom-quad-core-w1004.html |
| Vendor driver (Windows)   | Not found, just copied firmware found in original Windows installation |
| Extracted firmware        | [firmware.fw](firmware.fw) |
| Firmware for gslx680-acpi | [silead_ts.fw](silead_ts.fw) |
| Display resolution        | 1280x800 |
| Touch panel resolution    | The resolution of the touch screen, usually smaller than the display resolution |
| Touch controller          | Not verified. |
| Multitouch support        | Yes (10 touch points). Tested empirirically. |
| Finger tracking           | Yes, if the chip already does finger tracking, No if software finger tracking needs to be enabled in the driver |
| Mirrored horizontally     | Yes, if the touch screen is mirrored along the X axis, i.e. left and right are reversed, otherwise No |
| Mirrored vertically       | Yes, if the touch screen is mirrored along the Y axis, i.e. top and bottom are reversed, otherwise No |
| Axes swapped              | Yes, if the touch screen is rotated by 90 degrees, i.e. moving from left to right results in movement from top to bottom |
| Comments                  | The exact fwtool command line used to generate silead_ts.fw or other relevant information |
