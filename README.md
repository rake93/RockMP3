
RockMP3
=======

Android 4.1 Building Audio Player Tutorial...!


People ask me all the time how to develop an Android program that can load up and play music. Sadly, 
there are not a lot of good answers on the internet. The good news is, it's really not all that bad. 
Today we are going to:

    Learn how to implement features of the android.media.MediaPlayer class.
    Load Drawables on the fly from the SD card using the createFromPath() function
    Learn what assets are and how to incorporate these into our program
    Learn how to load media from an SD card
    Write a fully functional Media Player program
    Become a better Java Monkey!

By the end of this tutorial, you will not only have a fully functional simple media player, but you will also have a 
clear understanding of how to incorporate media into your apps. Before going any further, make sure your development 
environment is set up correctly for Android development.



Sending files to Emulator SDCard (For Testing)

To test this app in your android emulator you need to load your emulator with some songs. 
You can send files to emulator sdcard using adb tool which comes with Android SDK.

Navigate to your android SDK folder/platform-tools/ using command line. And using push command you can send files 
to sdcard. (Start your emulator before performing push command)

$platform-tools> adb push "c:\Songs\White Flag.mp3" "/sdcard/"
