# bus-schedule-
View bus schedules. Choose a bus schedule using the spinner object. 

These are the files for the bus schedule. In this readme I'll go over the files and what you should do with them.
-activity_main.xml: This is the file that contains the spinner that users can use to choose which bus schedule they want to view. I've tested it and the spinner should work properly. This filename may conflict with one of yours - in that case you can just change the filename. 
strings.xml: This file contains the string array called "names" for the spinner. You can just incorporate that array into your own strings.xml (lines 13-20). 
-MainActivity.java: This is the java file that makes the spinner work. You may need to just incorporate this into your own MainActivity.java. The lines that are specifically important for the spinner to work are lines 3, 12, 14-15, 17, 20-21, and 31-69. Here is a short breakdown of the .java file and what's important:
Lines 3, 12, 14-15, 17, 20-21: these are the imports that the spinner uses. 
Line 31: Basically imports the object spinnerX from activity_main.xml.
Lines 33-36: Adds the options for the spinner. For line 34, your strings.xml file should be updated with the names string array. 
Lines 38-69: Makes the spinner work using if-statements. 

There are five different bus schedules for NYIT which I got from this link: https://www3.nyit.edu/files/long_island/LI_InterCampusBusSchedule.pdf
Each bus schedule has its own .xml and .java. I'm not exactly sure if the .java files matter but I'd leave those in your project just to be sure - they should be in the same folder as your other .java files. 

There are also five images, one for each bus schedule, and they are either .png or .jpg. They are named after their bus schedules so it should be obvious which ones are which. These should be stored in your drawable folder. so the .xml files can call to them. 

The content_main.xml file might not be necessary at all.

That should be it. Let me know if you have any questions. 
