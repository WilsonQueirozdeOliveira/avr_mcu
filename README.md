# avr_mcu

## Dependencies

### windows install
    usbipd-win 2.3.0

### windows comands
    usbipd wsl list

    usbipd wsl attach --busid "busid"

    usbipd wsl detach --busid "busid"

### wsl install
    sudo apt install linux-tools-5.4.0-77-generic hwdata

    sudo update-alternatives --install /usr/local/bin/usbip usbip /usr/lib/linux-tools/5.4.0-77-generic/usbip 20

    sudo apt-get install avr-libc binutils-avr gcc-avr avrdude

### wsl comands

    lsusb

    sudo avrdude -c usbasp -p m328P -vvv 

### src/blink

    sudo make "for usb permition"
