---
title: "Modify the buffer size of the Wire library"
---

The Wire library is used to communicate with I2C/TWI devices. Being able to change/modify it’s buffer size is very useful for I2C/TWI device communication.

To locate the `Wire.h` library in the Arduino installation path and modify its buffer size, take the steps outlined below:

1. Close the Arduino IDE if open.

2. Find the file `Wire.h`:

   * **Windows:** `C:\Program Files (x86)\Arduino\hardware\arduino\avr\libraries\Wire\src\Wire.h`
   * **macOS:** `~/Library/Arduino15/hardware/arduino/avr/libraries/Wire/src/Wire.h`
   * **Linux:** `~/sketchbook/hardware/arduino/avr/libraries/Wire/src/Wire.h`

3. Opem the file `Wire.h` with a text editor.

   ![wire header file location](img/wire.h_header_file.png)

4. Locate the line `#define BUFFER_LENGTH 32` and change the number `32` to the desired value.

5. Save the changes made and close the text editor.

6. Restart the IDE.
