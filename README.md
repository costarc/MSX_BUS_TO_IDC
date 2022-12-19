# MSX_BUS_TO_IDC

V1.0

This MSX interface exposes the MSX BUS via an IDC connector.
The IDC pinout layout matches the Altera DE1 Development board.

There is no voltage level conversion, therefore this interface must be used only with MSX FPGA clones
because they already operate at 3.3v level.

Do ont use this interface to connect a real MSX (which operates with a 5V bus) to the Altra DE1.

The pull-ups resistors are optional. They may be installed if you determine that your project requires pull-ups in those lines.
