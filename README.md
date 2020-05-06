# CFI1

TASK 1

1.	Automated Water Motor With Level Indicator
we have used Ultrasonic sensor module which sends the sound waves in the water tank and detects reflection of sound waves that is ECHO. First of all we needs to trigger the ultrasonic sensor module to transmit signal by using Arduino and then wait to receive ECHO. Arduino reads the time between triggering and received ECHO. This sensor module will read the distance between sensor module and water surface, and it will show the distance on LCD screen with message “Water Space in Tank is:”. It means we are here showing empty place of distance or volume for water instead of water level. Because of this functionality we can use this system in any water tank. When empty water level reaches at distance about 30 cm then Arduino turns ON the water pump by driving relay. And now LCD will show “LOW Water Level” “Motor turned ON”, and Relay status LED will start glowing. Now if the empty space reaches at distance about 12 cm arduino turns OFF the relay and LCD will show “Tank is full” “Motor Turned OFF”. Buzzer also beep for some time and relay status LED will turned OFF.

2.	Zoom Meetings Physical Mute Button
Press the button to toggle your mute, or hold the button down to leave the meeting (or end it if you are the host).One great thing about this is that it works even if your Zoom window isn't active.
This device simply emulates a keyboard when you plug it into your computer. We take advantage of the built-in keyboard shortcuts for Zoom:
CTRL+ALT+SHIFT brings focus to the Zoom window
ALT+A toggles the state of mute, if you mute is on it turns it off, and if it's off it turns it on
ALT+Q leaves a meeting or ends it if you are the host.
A short press of the button sends CTRL+ALT+SHIFT followed by ALT+A, while a long press sends CTRL+ALT+SHIFT followed by ALT+Q then ENTER.


3.	Keyboard Cap Micro Watercolor Bots
Involves a  Vibe motor, so attached to the structure made by the ear buds so that the vibration leads ot rotating the buds thus spilling the water colour and creating great to see shapes.
 
4.	Alexa Controlled Bookshelf Lighting
A more of a mechanical based project involving cutting of the wood for the shelves and then adding grooves for the led strip. Then using NodeMCU to connect the strip to Alexa. It also has inbuilt soothing warm-white LED diffused lighting.
Also, connecting Alexa app to Bookshelf is trivial:

Make sure your phone, Echo and ESP32 are all connected to the same WiFi network.
Open the mobile app for Alexa.
Open the hamburger menu on top-left.
Select Add Device.
Set Type Of Device as 'Other'.
It will ask you to discover devices.
It should show 1 found device. Click on 'Setup Device'.
Then it should show 'bookshelf' device should be setup and ready to use.
Say "Alexa, turn on bookshelf". If you have an LED strip connected to ESP32, it should light up.
You can also set the brightness by saying "Alexa, set bookshelf to 50 percent".

5.	IRIS - the Lamp That Knows When You're Around
Manual mode: Usual desk lighting
Smart mode: Automatic detection of the user to turn on / off the light
Smart bed lamp: Automatically lights up your path when you want to go somewhere in the middle of the night
Adaptive brightness: Automatically adjusts brightness based on surrounding light
Daylight awareness: Can turn on smart mode automatically after sunset or when no other light source is around.
This is all achieved using a proximity sensor and controlling it using Arduino.

6.	Simple Raspberry Pi Cooling Fan
Involves connecting a heatsink to the Ras Pi and the using zipties to connect a 5V fan to the heatsink so that the ras pi can be cooled efficiently and get better performance!!

7.	Raspberry Pi Based Weather Station
Nice looking weather forecast for Raspberry Pi Zero and Ili9341 based 2.8 inch TFT. this project how to build a nice looking weather station based on Raspberry Pi Zero W for wall mount with weather forecast and coloured 2.8 inch TFT screen.

https://www.hackster.io/hartmut-wendt/raspberry-pi-based-weather-station-a9a7dd
 
8.	DIY Windows 10 Tablet PC
A project using a touch screen and latte panda to create a tablet and adding all the required components like speaker buttons etc.

https://www.instructables.com/id/DIY-Tablet/
 
9.	Emoji Keyboard
Involves using a numpad and mapping out the keys for emoji’s that are available in Unicode.  ¯\_(ツ)_/¯ 
 
Simple as it sounds! And then sticking the keys with the respective stickers!

10.	GooglePi - Google Assistant on Raspberry Pi
This project involves adding Google Assistant API to Raspberry Pi after setting it up using Python. We can get the Google Assistant easily as it is provided for use by google itself.
https://www.hackster.io/Salmanfarisvp/googlepi-google-assistant-on-raspberry-pi-9f3677

11.	DIY Alarm Bike Lock (Shock Activated)
This project involves using a buzzer and a piezoelectric disk. The piezoelectric disk is such that when given a shock it produces current and hence we use that to run the buzzer for a specific amount of time using a controller.

12.	Fight Coronavirus: Simple Handwash Timer
This project involves using a ultrasonic sensor to detect when your hand gets close to use the soap dispenser and using a controller to turn on a red led and then turn it off after 20 seconds.
 
13.	Add a USB Port to a Lamp
 
Involves adding a usb port of a mobile charger and using the transformer and putting it inside the lamp casing and connecting it to power.

14.	Emergency USB Power Source (3D Printed)
This project involves using a 3D printer to design a outer covering for a small motorcycle or an ATV battery and then connecting it to a usb module to use it as an emergency power source.

15.	Pocket Sized Vacuum Cleaner
Its made from two PVC pipe fittings. A 2 inch PVC coupler & a 1.5 inch to 0.5 inch PVC reducer. The length of the 1.5 inch side of the reducer is taken as 1 cm and the rest is cut off using a hack saw. A 0.5 inch pipe is temporarily inserted to the other end such that it extends to a length of 1cm. This side is kept as bottom and placed inside the 2 inch PVC coupler. Previous 1cm PVC extension helps to raise the reducer in order to provide space for the Nozzle storage option which we would discuss at a later stage. Now, using a drill of appropriate size the dust container and the inside reducer is drilled. Please note that we are drilling to the 1.5 inch side of the reducer. Similarly, 4 holes are drilled in order for bolt insertion and fixing. The remaining air gap inside the section is then sealed by epoxy putty. This finished the dust container.

16.	The Simplest DIY Macro Keypad
It uses only 2 components and no special boards need to be installed for Arduino so it really can't get any easier!

The Arduino Pro Micro supports emulation of HID (Human Interface Devices, aka your keyboard an mouse) so it's perfect for this kind of a project.

We will also be using a 4x4 Keypad because it's cheap, has 16 buttons and is really simple to wire up.
 
17.	Nerf Dart Launcher for the FPV-Rover and FPV-Trike
Involves 3d printing the parts and then connecting it to a controller using the network chip extension on the Arduino.
 
18.	Mobile Controlled crane
modified a toy crane in such a way that it will use 2 servos and an arduino as welll as jumper wires to make it happen.
You will have to use an app known as Arduino Bluetooth controller.

https://www.hackster.io/moadibnasir129/mobile-controlled-crane-8fc114
 
19.	Internet of Dirt: a Texting Plant
This simple project combines a capacitive soil sensor, the WiFi-enabled Adafruit Feather HUZZAH ESP8266 board, Adafruit IO, and IFTTT to set up a system that will text you when your plant's soil gets too dry. It makes a great intermediate-level Arduino project, or a good introduction to Internet of Things-style projects.  
Link: https://www.instructables.com/id/Internet-of-Dirt-a-Texting-Plant/

20.	Etch a Selfie
This project is based to modifying a etch a sketch pad to create selfies on the pad by inputing the picture in the processor and thus the motor etching it. 
 
Link: https://www.instructables.com/id/Etch-a-Selfie/

21.	Laser Spirograph Sound Visualizer (LSSV)
This project is creating a visualizer with the help of lasers and fans to make it look cool and have a nice effect while playing music. 
 
Link: https://www.instructables.com/id/Laser-Spirograph-Sound-Visualizer-LSSV/

22.	Upcycled Alarm Clock Smart Light
In this project I upcycle a completely broken wind-up alarm clock. The clock face is replaced by 12 LEDs, illuminated by an LED strip around the rim of the clock. The 12 LEDs tell the time and the LED strip is programmed to act as an alarm, turning up to full brightness at the set time. Everything is controlled by a Raspberry Pi Zero allowing for countless integration and expansion possibilities such as automatically synchronising the light alarm with your phone alarm or flashing the LEDs when you receive an email.

The project uses relatively cheap or reused components - the only thing I ended up buying was the voltage regulator. Everything else I happened to have lying around such as an off-cut of LED strip. This Instructable will guide you through how I gave a new life to my broken clock and hopefully might inspire you to upcycle something of your own.

https://www.instructables.com/id/Light-Clock-Alarm/

23.	IoT Pet Feeder
In this specific project, we set the feeder to start beeping from time to time. Once the dog comes closer to the device, the PIR sensor recognizes it and the servo is triggered. In addition, we also decided to add the option to control the pet feeder from our mobile phone, using a pre-defined dashboard made with Freeboard.

24.	Velocity Sensitive Cardboard Keyboard
Velocity Sensitive Cardboard Keyboard that works with proximity IR sensors. Depending on whether we play a piano key faster or slower, the musical note will sound more or less hard, respectively.

https://www.instructables.com/id/Velocity-Sensitive-Cardboard-Keyboard/
 
25.	P5 LED Panel With Raspberry Pi
Here we create our own led panel and connect it to a processor to have different patterns. The panel is controlled with a Raspberry Pi Zero, a low-cost microcomputers.
Link: https://www.instructables.com/id/P5-LED-Panel-With-Raspberry-Pi/

