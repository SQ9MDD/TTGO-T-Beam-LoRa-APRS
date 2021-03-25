## How to binary flash readme...
* Download current version of the esphome-flasher tool
* https://github.com/esphome/esphome-flasher/releases
* Connect your board to your USB port and open ESPHome Flasher.
* If your board is not showing under Serial Port then you likely need to install the drivers for the CP210X serial chip. In Windows you can check by searching “Device Manager” and ensuring the device is shown under “Ports”.
* In ESPHome Flasher, refresh the serial ports and select your board's serial port.
* Browse to the downloaded firmware and select the correct firmware based on the board type.
* Select/Press Flash ESP.
* Once complete, “Done! Flashing is complete!” will be shown.
