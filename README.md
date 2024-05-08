# PiSensorFun
Fun workshop using Raspberry Pi and SenseHat. You will need the hardware and software setup and very basic programming language to completevthis fun workshop!

# Hardware Setup:

1. Raspberry Pi 4/5 connected to a monitor, mouse keyboard and power.
2. SenseHat add-on board with LED Matrix display, joystick and pressure, humidity, temperature, colour, orientation, movement sensors.


# Software Setup

- Connect your Sense HAT and boot up the Raspberry Pi.

- First update and upgrade your system by entering the following commands into a terminal window (while connected to the internet):

```bash
sudo apt-get update
sudo apt-get upgrade
```

- Now install the Sense HAT software packages:

```bash
sudo apt-get install sense-hat
sudo pip install pillow
```

- Reboot the Pi to complete the installation:

```bash
sudo reboot
```

- Finally, Python installation by typing the following command and it should print the current version of Python 3.x

```bash
python3 --version
```

## Projects: Hello Sense Pi!

In this project you will use the basics of Python and Raspberrpy Pi with senese hat.


## Project : Marble Maze Game

In this project you will create a marble maze game that can be played on the LED matrix of your Sense HAT. You will use the in-built orientation sensors of the Sense HAT to control the movement of the marble, simulating the way a real marble rolls around a maze.


