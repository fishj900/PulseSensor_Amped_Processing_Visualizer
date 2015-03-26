![logo](https://avatars0.githubusercontent.com/u/7002937?v=3&s=200)


## PulseSensor Processing Visualizer
Processing code for pulse wave visualization
![Picture](https://github.com/WorldFamousElectronics/PulseSensor_Amped_Processing_Visualizer/blob/master/ScreenShot.png)


## Install Note
1.  "Download ZIP".
2.  Take the folder called 'PulseSensorAmpd_Processing_1dot1' and place it in your
Documents/Processing folder.
3.  UnZip file in the folder. 
4.  Then open or restart Processing to access the code through your Sketch folder.


## Installation
1. Before running this program, install our <a href="https://github.com/WorldFamousElectronics/PulseSensor_Amped_Arduinor"> "Pulse Sensor Arduino Code"</a>
![ScreenShot](https://github.com/WorldFamousElectronics/PulseSensor_Amped_Arduino/blob/master/pics/ScreenCapArduino.png) 


2.  Change Serial settings in Arduino App
Change:
```
// Regards Serial OutPut  -- Set This Up to your needs
static boolean serialVisual = true;   // Set to 'true' by Default. 

```
too:
```
// Regards Serial OutPut  -- Set This Up to your needs
static boolean serialVisual = false;   // Re-set to 'false' to sendDataToSerial instead. : ) 

```

That's it !  Fire up the Mac App, select your USB port, and see it go. 
