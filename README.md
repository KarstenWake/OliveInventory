# OliveInventory
Contains GUI application written in Python and converted to an executable.

Version Notes
* Version 2.0: Fixed bugs where changing values in GUI interface would not reflect in memory/saved files. Added pop-up messages when potential issues arise. 
* Version 2.1: Fixed bug where crash would occur when attempting pressing the import from website button multiple times. 
* Version 2.2: Fixed bug where program crashed if one of the prices in loaded inventory file was empty. Now if it encounters a blank, it will write a zero. Added a feature which prints an error log with a stack trace to a file if there is a crash upon launch of the app. This file can be emailed to make debugging easier. 
