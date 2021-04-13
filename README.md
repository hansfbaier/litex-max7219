# litex-max7219
MAX7219 LED matrix demo program for litex
In order to build successfully, your project needs an SPIMaster and you
need do set the following environment variable:

$ export BUILD_DIR=~/path/to/your/project/build/your_board/

The demo project has a command 'max' which starts the MAX7219
LED matrix demo.

My thanks goes to the original autor of the MAX8219
driver code, which I adapted to run on LiteX:

https://github.com/bitbank2/MAX7219

Also many thanks to Florent Kermarrec of the LiteX project,
for the code skeleton of this demo application.
