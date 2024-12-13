# Standard Operating Procedure for Klein Colorimeter

This SOP provides an overview over project specific measurements with the device Klein Colorimeter K-10A for the project ReWoCap. General handling of the device is decribed in another SOP.

| Device      | Klein, Instruments Corporation, K-10A                                |
| ----------- | -------------------------------------------------------------------- |
| Owner       | [Niloufar Tabandeh](mailto:niloufar.tabandehsaravi@tuebingen.mpg.de) |
| Contributor | [Alexander Hahn](mailto:alexander.hahn@tuebingen.mpg.de)             |
| Version     | 1.0.1.                                                               |
| Last edit   | 12.06.23                                                             |
| Date        | 20.04.23                                                             |

## Start up

Checklist for materials

1.  Klein Colorimeter, SN: U006957
1.  USB-connector-cable
1.  Laptop
1.  USB-hub
1.  Hard-drive
1.  Klein Software (Chromasurf)

Start up system

1.  Connect the cable to the Laptop via USB. The device starts up automatically.

## Pre-Measurement procedure

1.  General: Place the entire measurement setup in the desired position
1.  Make sure the Klein is properly mounted in the upper brass mounting in the black box
1.  Postion the light measurement devices on the rail so that the cable of Klein is not squashed against the back of the black box

## Measurement procedure

_Since this measurement usually takes the longest, you should start with this measurement first._

1.  Open the software. If the conncetion between Klein and laptop is established, click "Connection to" in the horizontal upper panel, to find out whether the device is recognized by the software. If the connection does not work, click "Connect Colorimeter" and select "DEMO: K-10".
2.  Should you want to reactivate the connection to the device from the offline mode, you can do so by pressing CLTR + I. In order for this to work successfully, the device must be connected to the software when first opening it.
3.  Click "Tools" in the upper panel and in the following "Logging tool".
4.  In the newly opened window, two modulators control the duration and sample rate of the measurement. Choose "60 sec." measurement duration and "fast" sampling rate.
5.  Click the "start"-button in the right of the window to start the measurement.

## Data Saving

Export Data

1. After the measurement has finished (60 sec.) click the "save"-button on the right of the window.
2. Automated renaming/saving 1. CSV: Save the data in the designated folder that is used by the Python Code (if you don´t know, which folder it is, you can look it up in the code). Save all the files there, according to the following naming description: klein:time:.csv (e.g. klein0930.csv) 2. Once the data is saved delete the data set in the window. Click "clear data" and continue with pressing "ok" in the opened window. 3. Enter the necessary details for automated naming in the header of the Python Code and let the code run to copy, relocate and rename the files.
3. Manual saving 1. Choose the path where you want to store the data: Hard-Drive &rarr; rewocap &rarr; data &rarr; raw &rarr; ID (e.g., 1001_20230208) with the name kleink10a_year:month:dayTmeasurementtime (e.g. kleink10a_20230208T0930) 2. Once the data is saved delete the data set in the window. Click "clear data" and continue with pressing "ok" in the opened window.

## Shut down

1.  Close the Klein software after making sure everything has been saved.
2.  You can now detache the conncetion cable from the laptop, which turns off the device.

---
