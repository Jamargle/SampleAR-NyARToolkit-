# SampleAR1
Sample Augmented Reality application for Android with NyArtoolkit (from ARToolkit).
I took sample project from [this tutorial](http://emiliusvgs.com/2014/07/19/tutorial-nyartoolkit-realidad-aumentada-android/) of Emilio Vegas and I have fixed some issues produced during import process on Eclipse. It isn't the last version of NyARToolkit but this is for showing a fast and easy example.

For using this app:
* Download the [apk file](https://github.com/Jamargle/SampleAR1/blob/master/NyARToolkit_Android_v3.0.0-1os2.1/bin/SampleAR1.apk)
* Allow installation of non-Market apps in Settings > Security
* Put this file into your Android device
* Search SampleAR1.apk in your device and install it
* Launch SampleAR1 and focus your device to [markers](https://github.com/Jamargle/SampleAR1/blob/master/NyARToolkit_Android_v3.0.0-1os2.1/res/raw/multi.pdf)


For modifing SampleAR1 or doing something with it follow these steps:
* Download the project from [here](https://github.com/Jamargle/SampleAR1/archive/master.zip). Note that SampleAR1 uses an old version of NyARToolkit. Other versions are [here](http://nyatla.jp/nyartoolkit/wp/?page_id=729)
* Unzip and go to File > import on Eclipse. Import the project.
* This project uses support-v7-appcompat. For adding it to the project, Right click on project name > Properties > Android > Go to Library section > Add support-v7-appcompat as a Library
* You can add your code to src/jp.androidgroup.nyartoolkit/NyARToolkitAndroidActivity.java. This class is AR activity that handles AR tasks.

##AR Markers
You will find the markers [here](https://github.com/Jamargle/SampleAR1/blob/master/NyARToolkit_Android_v3.0.0-1os2.1/res/raw/multi.pdf) and in res/raw/multi.pdf folder in the project.
In the code, they are used in "initScene" function and in "initializeGLSurfaceView"

For more details of this process, go to [original tutorial](http://emiliusvgs.com/2014/07/19/tutorial-nyartoolkit-realidad-aumentada-android/)

Thanks to Emilio Vegas and Neogeek tutorial and Ryu Iizuka.

[See NyARToolkit original documentation](https://github.com/nyatla/NyARToolkit/blob/master/README.EN.md)

[See NyARToolkit author site](http://nyatla.jp/nyartoolkit/wp/?page_id=729) and stay tuned about last releases of NyARToolkit
