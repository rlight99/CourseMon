## About CourseMon

Course Monitor (or CourseMon) is a simple Greasemonkey/Tampermonkey script. 

It checks every few seconds for openings in a course, which you specify. When an opening is found, the script notifies you.

Instructions as to how to use this script are below. 

Disclaimer: this webpage and script were made entirely for educational purposes.

## Instructions for Use

1. Install greasemonkey/tampermonkey
 
2. Copy paste this script into greasemonkey/tampermonkey: <https://github.com/MarshesDuck/CourseMon/blob/master/Course%20Monitor.js>
 
3. Change the course subject and number to the course that you would like to monitor- listed under USER SETTINGS in the script
 
4. Run the script on this page: <https://studentservices.uwo.ca/secure/timetables/mastertt/ttindex.cfm>

5. Allow the webpage to show notifications when prompted. 

6. (If your browser has silent notifications)
Make sure that the above website is also given permission to play audio.


## Patch Notes

### Version 1.21 Release
Aug 16 2020

Version 1.2 but with cleaner code.
Redundant code was removed, and the script was reformatted for readability and consistency.  


### Version 1.2 Release
Aug 15 2020

Now has real desktop notifications!


### Project moved from Pastebin to Github
Aug 12 2020

It's been fully functional for a while now. The one major change is that I've moved this project and all of its files over to Github, when it was previously a bunch of pastes in pastebin. The pastebin is located here, if you're curious. <https://pastebin.com/u/marshes>


### Version 1.1 Release
Aug 05 2020

Now significantly more usable!
- The part of the script where you enter in course subject and course number is now cleaner and more user friendly.
- @match added onto the top of the script so that it automatically runs on the correct website.
- fixed a spelling error
 
Remaining planned "features" to watch for in the future:
- rechecks at random intervals
- proper desktop notifications (instead of just playing a ping)


### Version 1.0 Release
Aug 02 2020

The script is finally functional.
 
Planned "features" for future updates:
- @match for the western timetables website (was too lazy to put it in already)
- proper desktop notifications (instead of just playing a ping)
- rechecks at random intervals
- more intuitive "user settings"
 

