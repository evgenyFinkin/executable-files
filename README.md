# executable-files
A repository For all my builds and executable so you could download tham.

Instructions on how to run a APK on an emulator

1- Run the emulator, and wait until it's completely started.

2- Go to your sdk installation folder then go to platform-tools (you should see an executable called adb.exe)

3- create a new file and call it run.bat, edit the file with notepad and write CMD in it and save it.

4- copy your desired apk to the same folder

5- now open run.bat and write adb install "your_apk_file.apk"

6- wait until the installation is complete

7- voila your apk is installed to your emulator.

Note: to re-install the application if it already existe use adb install -r "your_apk_file.apk"
