# teensy
How to get teensy dev environment working quickly on Linux

# AVR Compiler for Fedora
dnf install avr-gcc-c++

# install libusb 
  ` sudo dnf install libusb-compat-0.1-devel`

# Install arduino 

# dialout group
sudo usermod -a -G dialout $USER

# remove this
 sudo dnf remove brltty   

# download and install udev rules
https://www.pjrc.com/teensy/00-teensy.rules
sudo cp 00-teensy.rules /etc/udev/rules.d/00-teensy.rules

# Download and install teensy gui program 
# wget https://www.pjrc.com/teensy/teensy_linux64.tar.gz
https://www.pjrc.com/teensy/loader.html



