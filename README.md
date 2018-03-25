# android-ws
Android workspace

====> MyToDos
https://www.raywenderlich.com/165824/introduction-android-activities-kotlin --> Thanks!

--> Error: When try to install the signed apk on Note 4
android studio apk there was a problem parsing the package
--> Solution:
build.gradle, 
minSdkVersion 23 --> from 26 to 23 because Note 4, Android version is 6.0.1, which API level is 23
targetSdkVersion 23

