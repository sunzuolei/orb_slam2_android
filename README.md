# orb_slam2_android
Implement ORB SLAM2 on an Android Phone.
## ORB SLAM2
basic ORB SLAM2 project source code is on：https://github.com/raulmur/ORB_SLAM2 <br />
you can also find Related Publications about this project on this page.
## thanks to the reference program
the original refernence program is on: https://github.com/kevinwchn/slamit_ORBSLAM2_on_Android <br />
 make it possible to run after dubugging and at the same time partly changed the UI.
## environment already tested
Compiling environment: android studio 2.2<br />
Test environment: android 7.0<br />
## files needed
this program need two files before running, both camera setting file and vocabulary file.<br />
you can find the vocabulary file from:<br />
https://github.com/raulmur/ORB_SLAM2/tree/master/Vocabulary <br />
setting file can be designed according to:<br />
https://github.com/raulmur/ORB_SLAM2/blob/master/Examples/Monocular/TUM1.yaml<br />

the default path:<br />
setting file: "/storage/emulated/0/SLAM/Calibration/List.yaml"<br />
vocabulary file: "/storage/emulated/0/SLAM/VOC/ORBvoc.txt"<br />

if you want to change the path please swipe left on the main page<br />
## openCV depandence
this release no need to open openCV manager on the phone.<br />
already packed in the apk.


