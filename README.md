# sayho
by 정화중3 권진우
aaaaa
-usb camera connect
dli@dli-desktop:~$ ifconfig  -> stands for "interface configuration"인터페이스 구성의 약자, 제슨나노의 ip구성 알려줌
.....
dli@dli-desktop:~$ ls /dev/video0 -l  -> "ls" is used to list files and directories in a directory. 파일과 디렉토리들을 한 디렉토리에 정렬
                                         "/dev/video0" is the path to the device file you want to inspect in this case. 찾을 파일의 위치 구함
                                         "-l" is used to display the long format listing of the file. 파일의 긴 포맷의 나열 보여줌0
.....
dli@dli-desktop:~$ git clone https://github.com/jetsonhacks/USB-Camera.git  ->if your camera is CSI camera, type CSI instead of USB
.....                                                                         카메라 형식에 따라 USB/CSI를 사용함
dli@dli-desktop:~$ ls 정렬
.....
dli@dli-desktop:~$ cd USB-Camera  -> change directory(cd) to USB-Camera 디렉토리를 USB-Camera로 바꿈
dli@dli-desktop:~/USB-Camera$ ls 정렬
dli@dli-desktop:~/USB-Camera$ python3 usb-camera-gst.py  -> run python3 on usb-camera-gst the name of the Python script that will be executed 실행될 파이썬 스크립트를 파이썬3으로 실행
--> now you can see the screen your camera displays 카메라 화면 보임!
