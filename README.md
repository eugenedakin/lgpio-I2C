# lgpio-I2C
This example program communicates with I2C via the lgpio library on Raspberry Pi OS

![](https://github.com/eugenedakin/lgpio-I2C/blob/main/FinalScreenGrab.png)

The MPL3115A2  barometric sensor can measure the barometric pressure and temperature by the I2C (Inter-Integrated-Circuit) to allow many devices to be read and written with through same two-wires that are connected to other devices. This sensor works well with the Raspberry Pi because it works well with the 3.3-volt power supplied by the motherboard. There are two buttons on this project, which the first button is used to calibrate the altitude and the second pushbutton calculates the altitude and reads the pressure and surrounding temperature. The following screen grab shows the output when calibrating the altimeter. 

The lgpio library can be installed Raspberry Pi OS (6 July 2023) and instructions 
are available at http://abyz.me.uk/lg/download.html

Install instructions are:
1) install Raspberry Pi OS (64-bit)
2) Open a terminal and type the following commands:
3) sudo apt install swig python3-dev
4) sudo apt install python3-setuptools
5) sudo apt-get install libunwind8
6) wget https://github.com/joan2937/lg/archive/master.zip
7) unzip master.zip
8) cd lg-master
9) make
10) sudo make install
11) create a Blink example program and copy the program and libraries to the RaspberryPi Desktop
12) give the executable permission to run with something like: 'sudo chmod +x HelloWorldBlink'
13) run the program with something like: 'sudo ./libGPIODinput'

![](https://github.com/eugenedakin/lgpio-I2C/blob/main/I2CBreadboard.png)
