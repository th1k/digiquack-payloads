# Setup Digispark

### Prerequirements

* Arduino: https://www.arduino.cc/en/software
* Windows / Linux / Mac  (Windows preferred)
* Digispark ATtiny85

### Configuration - IDE

1. Download arduino software from the official website and install it
2. Open arduino and go to File -> Preferences -> Additional Boards Manager URLs: (put the digispark package script inside that)
    > http://digistump.com/package_digistump_index.json
3. Close the IDE and reopen it
4. Go to Tools -> Board: "###" -> Boards Manager... -> Type (Contributed) -> Digistump AVR Boards -> Install
5. Go to Tools -> Board: "###" -> Digistump AVR Boards -> Digispark (Default -16.5mhz)


### Driver Installation - Windows 10

1. Download driver package from (https://github.com/digistump/DigistumpArduino/releases) | Digistump.Drivers.zip
2. Extract and install the file named DPinst64.exe for win64bit or DPinst.exe for win32bit
3. Go to Device Manager in windows and plug the digispark inside the usb port.
4. In Deivce Manager go to View -> Show hidden devices
5. Find the unknow device driver (on Other devices or Ports (COM))
6. Right click on the blur driver icon -> Update Drivers -> Browse my computer... -> Check on Includes subfolders (✓) -> Browse to the Digistump driver folder -> Ok

### Coding

1. Before upload any code into the board please make sure you have choose the right board model
2. Write a sample code and click on Upload (Upload script first before plug the usb in).
3. Plug the Digispark inside the USB port to upload the script.
4. Done, now you can test in real world.
