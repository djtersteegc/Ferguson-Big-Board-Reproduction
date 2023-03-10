Redraw in Sprint Layout from scans of an unpopulated board, serial number B4088.

Mostly original with the following changes:

- Silkscreen of U52 corrected from a DIP-16 to DIP-14 socket.
- Silkscreen reference Q1 added
- Silkscreen reference Q2 added
- Silkscreen reference R21 added
- Silkscreen reference C142 added
- Added missing vias for the top two memory bank -5V traces
- Pin 14 silkscreen reference on J2 (keyboard connector) corrected to read pin 2
- Jumper JB7 added to switch line character count between 97 and 128.  Strap middle pin to top pin to connect U11 pin 3 to +5V for 128 counts. Strap middle pin to bottom pin to connect U11 pin 3 to U10 pin 2 for 97 counts. *Micro Cornucopia, Number 10, February 1983, page 32*
- Jumper JB8 added to switch between 7 and 8 dot character widths. Strap middle pin to top pin to connect U24 pin 3 to +5V for 7 dots. Strap middle pin to bottom pin to connect U24 pin 3 to GND for 8 dots. *Micro Cornucopia, Number 10, February 1983, page 32*

Like the original board, VPP on the Character Set EPROM (U73, pin 21) is unconnected and needs to be wired to +5V (U73, pin 24) for normal operation.

