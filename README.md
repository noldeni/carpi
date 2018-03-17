# carpi
Scripts and documentation for my carpi

# pidashcam
In the directory pidashcam are the files from the blog under http://pidashcam.blogspot.de/

Extract from the blog(http://pidashcam.blogspot.de/2013/09/install.html):
  audio.sh         - Uses arecord to save audio recordings to the audio directory
  dashcam.sh       - The main startup script. Mounts USB device, rotates logs, disk cleanup etc.
  flash            - C program to flash LEDs as required (GPIO #, count, delay, finish on/off)
  global.rc        - Resource file for all the global variables
  gps_logger       - C program to manage the GPS (via gpsd)
  home.sh          - Program to transfer files from the Pi to another computer before shutdown
  motion_camera.sh - Runs motion to record video when a USB camera is connected
  picam.py         - Pi camera recording using the picamera package
  pico.sh          - A script to make use of the optional UPS PIco module
  pivid.sh         - Pi camera recording using the raspivid command
  pwr_butt         - Monitors (GPIO 5 by default) for a button press to shutdown or reboot


