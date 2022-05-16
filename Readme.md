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
    1.  Multiplayer HLAPI (required by the Cloud Anchors sample)
    2.  XR Plugin Management (required by Instant Preview, which uses the TrackedPoseDriver)
    
13. Go to File -> Build Setting -> Android -> Switch Platform.
14. In the Android settings tab, configure the following settings, under Other Settings:
    1. Uncheck Auto Graphics API, and remove Vulkan if listed under Graphics APIs.
    2. Check Multithreaded Rendering.
    3. Change package name to com.Example.MarkerlessImplementation.
    4. Set Minimum API Level to Android 7.0 'Nougat' (API Level 24) or higher.
    5. Set the Scripting Backend to IL2CPP.
    6. Select ARM64 under Target Architectures.

15. Connect the required smartphone device.
16. Go to File -> Build Setting -> Build and Run. Save the apk file and wait to install it on your smartphone.
17. Once the installation is complete, you can run the application.

