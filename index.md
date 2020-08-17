## About CourseMon

Course Monitor (or CourseMon) is a simple Greasemonkey/Tampermonkey script. 

It checks every few seconds for openings in a course, which you specify. When an opening is found, the script notifies you.

Instructions as to how to use this script are below. 

Disclaimer: this webpage and script were made entirely for educational purposes.

## Instructions for Use

1. Install greasemonkey/tampermonkey
 
2. Copy paste this script into greasemonkey/tampermonkey: <https://github.com/MarshesDuck/Course-Monitor/blob/master/Course%20Monitor.js>
 
3. Change the course subject and number to the course that you would like to monitor- listed under USER SETTINGS in the script
 
4. Run the script on this page: <https://studentservices.uwo.ca/secure/timetables/mastertt/ttindex.cfm>

5. Allow the webpage to show notifications when prompted. 

6. (If your browser has silent notifications)
Make sure that the above website is also given permission to play audio.


## Patch Notes

### Version 1.21 Release

Version 1.2 but with cleaner code.
Redundant code was removed, and the script was reformatted for readability and consistency.  


### Version 1.2 Release

Now has real desktop notifications!


### Version 1.1 Release

It's been fully functional for a while now. The one major change is that I've moved this project and all of its files over to Github, when it was previously a bunch of pastes in pastebin. The pastebin is located here, if you're curious. <https://pastebin.com/u/marshes>

The sound file that the script plays when it detects a course that is not full also went down a number of times, making me change the sound link on the script a few times. Now that the entire project is hosted on Github, this shouldn't be a problem anymore. 

In the future, I'm planning to implement the following:
- Rechecks at random intervals, instead of a set interval.
- Proper desktop notifications (instead of just playing a ping).


