# LimeSDR-LabVIEW-LIB
 LimeSDR LabVIEW Library API
 
 This LimeSDR LabVIEW driver call the LimeSuite.dll APIs, so you must install the LimeSuite first. 
 For this version, I am using PothosSDR-2019.03.24-vc14-x64 which bundle the LimeSuite Driver.
 The driver is calling the LimeSuite from the default folder, "C:\Program Files\PothosSDR\bin\LimeSuite.dll",
 so it's better to install the PothosSDR with default folder.
 
 It's a 64bit Library, so for 32bit system, it would not work.
 
 LabVIEW Version is : LabVIEW 2018 64bit, for older version will update soon.
 
 Some of the vi have not been tested yet, so be careful when using some of those VI.
 
 I have created an LabVIEW FM demodulation example, it's working, but still have some problems in changing the LO frequence online, which mean it can not change the LO frequence after running the example VI. 
 
 Will do more debug and testing soon. 
 
 YongChen 
 2019.11.5
