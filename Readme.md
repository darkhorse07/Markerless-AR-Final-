Below are the steps required for accessing the project Markerless-AR-Final.

1.  Go to https://unity3d.com/get-unity/download, then click to Download Unity Hub.
2.  From your Downloads folder, double-click on the Unity Hub Setup file to begin the installation.
3.  Agree to Unity Terms of Service and follow the instructions to install Unity Hub.

Now that Unity Hub is installed, we need to actually install the version of Unity used in this project along with the code editor, Visual Studio.

4.  In the Installs tab (in Unity Hub) click to Add a new Unity Version.
5.  Select 2020.3.25f1 LTS, then click Next.
6.  On the Add modules screen, select Visual Studio (for Mac or PC). If you already have Visual Studio installed, it will not show up as an option.
7.  Click on Next and accept the necessary terms and conditions.

Now that Unity is installed with the required version, below are the further steps:

8.  Unzip the folder Markerless-AR-Final.
9.  Go to Unity Hub, in the Projects tab (present in the left side), add the project.
10. After the project has been added, double click to open the porject.
11. You need an ARCore supported android device to run this application. Go to https://developers.google.com/ar/devices to check the supported device list.
12. Select Window > Package Manager and install the following packages:
    12.1  Multiplayer HLAPI (required by the Cloud Anchors sample)
    12.2  XR Plugin Management (required by Instant Preview, which uses the TrackedPoseDriver)
13. Go to File -> Build Setting -> Android -> Switch Platform.
14. 












11. For Android:
    11.1  Go to File -> Build Setting -> Android -> Switch Platform.
    11.2  Go to Player Setting -> Player -> Other Settings -> Check Override Default Package Name.
    11.3  Set the package name to com.joebloggs.arudemy.
    11.4  The minimum API level should be set to 22 or higher and the targeted API level to 30.
    11.5  The Scripting Backend should be set to IL2CPP with ARM64 enabled in the Target Architectures.
    
12. For iOS:
    12.1  Go to File -> Build Setting -> iOS -> Switch Platform.
    12.2  Go to Player Setting -> Player -> Other Settings -> Check Override Default Package Name.
    12.3  Set the package name to com.joebloggs.arudemy.
    12.4  The minimum targeted iOS version should be set to 12.0 or higher and a Camera Usage Description as well as a Location Usage Description should be provided.
    12.5  The Architecture should be set to ARM64.
    
13. Connect the required smartphone device (android/ios).
14. Go to File -> Build Setting -> Build and Run. Save the apk file and wait to install it on your smartphone.
15. Once the installation is complete, you can run the application.
16. Print the GrannyMarker.jpg image from the project folder.
17. Open the application and point the camrea to the granny image.

