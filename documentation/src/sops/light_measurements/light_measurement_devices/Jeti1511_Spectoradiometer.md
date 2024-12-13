# Standard Operating Procedure for Jeti Spectoradiometer 1511

This SOP provides an overview over project specific measurements with the device Jeti Spectoradiometer 1511 for the project ReWoCap. General handling of the device is decribed in another SOP.

| Device      | Jeti, Spectoradiometer 1511                                          |
| ----------- | -------------------------------------------------------------------- |
| Objective   | Describe the measurement with spectoradiometer 1511                  |
| Owner       | [Niloufar Tabandeh](mailto:niloufar.tabandehsaravi@tuebingen.mpg.de) |
| Contributor | [Alexander Hahn](mailto:alexander.hahn@tuebingen.mpg.de)             |
| Version     | 1.0.1.                                                               |
| Last edit   | 12.06.23                                                             |
| Date        | 20.04.23                                                             |

## Start up

Checklist for materials

1.  Jeti spectraval 1511 HiRes; SN: 1510507
2.  Diffusor
3.  Lens Cover
4.  Jeti Software
5.  USB-hub
6.  USB-cable (part of the larger cable unit)
7.  Hard-drive

Start up system

1.  Plug the USB-conncetor-cable into the laptop
2.  Plug the other end of the USB-connector-cable into the Jeti (This activates the device and a green light is visible on the backside of it)

## Pre-measurement procedure

1.  General: Place the entire measurement setup in the desired position
2.  If the Jeti is not included in the set-up yet: Pull up the aluminium handle at the bottom left side of the black box (if you face the box from the rear) and put the light measurement devices in the forward position. Take out the Klein by pulling on the metal handle of its mounting, which loosens the Klein. Now you can put the Jeti in the lower brass mounting and reassemble the Klein. Beforehand, make sure that the Jeti is orientated in the corrected direction (adaptable with the brass screw on the back of the device)
3.  Take the lens cover of the Jeti and carfully put the diffusor. There is only one possible way to put it because of three spikes on the diffusor.
4.  Before plugging in the power cable, attach the magnet of the cable on the small metal plate behind the Jeti.

## Measurement procedure

1.  Open the software. If the Jeti has power and the conncetion between Jeti and Laptop is established, a large green button "Measurement" is shown in the software window. If the connection does not work, it can be helpful to disconnect and then reconnect the cables from the USB-hub and/or the Jeti. Close the software before you disconnect and open it only after reconnecting.
2.  Press the large green button to start the measurement, which takes a few seconds, depending of the intensity of the illuminance.
3.  If the measurement was successful, a spectral diagramm of the lighting conditions is being shown and "#1" appears in the white panel on the middle of the righthand side.

## Data Saving

Export/Access Data

1.  Click on the "#1" (it´s then marked blue) and afterwars click "to Table" underneath the white panel.
2.  Click "File" and then "Export table as Excel File"
3.  Automated saving/renaming
    1.  Save the files in the designated folder that is used by the Python Code to access the data (if you don´t know, which folder it is, you can look it up in the code). Save the data there, according to the following naming description: jeti:time:.xlsx (e.g. jeti0930.xlsx)
    2.  Change the necessary details in header of the Python code and run it to rename, relocate and copy the files.
4.  Manual saving/renaming
    1.  Choose the path for saving the file: Hard-Drive &rarr; rewocap &rarr; data &rarr; raw &rarr; ID (e.g., 1001_20230208) with the name jeti1511_year:month:dayTmeasurementtime (e.g. jeti1511_20230208T0930)
    2.  After saving the table, you delete the measurement by left-clicking on the "#1" and right-clicking "Delete" in the opening window.

## Shut down

1.  Close the Jeti software after making sure everything has been saved.
2.  You can now detache the conncetion cable from the laptop and from the Jeti device, which turns off the device.
