# GEOCODE-ArchiCAD 0.1 pre-alpha


## HELLO THERE! 

## TL;DR
The aim of this project is converting the file with a geocode into the file with an extra data about a color of an each point.

## WHY
During the work with an ArchiCAD we discovered that it is impossible to use a geocode file which include only 3 data (latitude, longitude and elevation) to generate a point cloud. We need a file with 3 more data which describing a color of an each point.  

We decided to make the app which will solve this problem and allow you to import the geocode file, add 3 extra positions and to export a new file after conversion. Then you will be able do use it in an ArchiCAD to generate a point cloud.


## HOW IT WORKS

### TRY IT!
Here you can try [the newest version](https://spacehiker.github.io/geocode-archiCAD/).
### 0.1 pre-alpha version

This very early pre-alpha version already allows you convert the file. To do it, add the file by click "choose the file". Then, wait till the text will appear in the textarea. After that, click "save" button and your converted file will be downloaded to your "downloads" folder. 
For now, this version of the app do not have any sophisticated GUI.

#### ISSUES TO FIX
- For now, the downloaded file have *.txt extension, but you can change it very easly.
- The app is crashing during the reading a larger file, so it is recommend to import smaller file with the maximum 1 milion of geocode lines. If your file have much more lines, you can divide it to a smaller parts and convert each separately and afterwards join it together again.

