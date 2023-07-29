# sayho
by 정화중3 권진우
aaaaa
-usb camera connect
dli@dli-desktop:~$ ifconfig  -> stands for "interface configuration"
.....
dli@dli-desktop:~$ ls /dev/video0 -l  -> "ls" is used to list files and directories in a directory.
                                         "/dev/video0" is the path to the device file you want to inspect in this case.
                                         "-l" is used to display the long format listing of the file
.....
dli@dli-desktop:~$ git clone https://github.com/jetsonhacks/USB-Camera.git  ->if your camera is CSI camera, type CSI instead of USB
.....
dli@dli-desktop:~$ ls
.....
dli@dli-desktop:~$ cd USB-Camera  -> change directory(cd) to USB-Camera
dli@dli-desktop:~/USB-Camera$ ls
dli@dli-desktop:~/USB-Camera$ python3 usb-camera-gst.py  -> run python3 on usb-camera-gst the name of the Python script that will be executed
--> now you can see the screen your camera displays
