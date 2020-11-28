# GEOCODE-ArchiCAD 0.1 pre-alpha


## HELLO THERE! 

## TL;DR
The aim of this project is converting the file with geocode into the file with extra data about the color of each point.

## WHY
During the work with an ArchiCAD we discovered that it is impossible to use a geocode file which include only 3 data (latitude, longitude and elevation) to generate a point cloud. We need a file with 3 more data which describing a color of an each point.  

We decided to make the app which will solve this problem and allow you to import the geocode file, add 3 extra positions and to export a new file after conversion. Then you will be able do use it in an ArchiCAD to generate a point cloud.


## HOW IT WORKS

### 0.1 pre-alpha version

This very early pre-alpha version already allows you convert the file. To do it, add the file by click "choose the file". Then, wait till the text will appear in the textarea. After that, click "save" button and your converted file will be downloaded to your "downloads" folder. 

#### ISSUES TO FIX
- For now, the downloaded file have *.txt extension, but you can change it very easly.
- The app is crashing during reading larger files, so it is recommend to import smaller files with the maximum 1 milion of geocode lines.  