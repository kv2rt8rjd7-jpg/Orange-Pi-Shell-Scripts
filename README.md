The files in the Maya and .col directories are needed for the longcount and longglyph shell scripts to work correctly and should be subdirectories of your home directory!!
The shell script files in the Longcount directory should all be placed in a directory that is in your $PATH ... I put them in /usr/games but anywhere in the path will work!!
The main scripts longcount and longglyph call the other scripts in order to execute properly and most of the other scripts should not be used directly except lcrm (Longcount Reverse)!!
The default for the longcount and longglyph will use the system date to calculate either the text or the glyph of the Maya Long Count!!
They also work with paramaters passed as in "longcount 7" which will give the longcount 7 days from the current date and can be a positive or negative number!!
If two paramaters passed it will be the year and the day of the year as in "longglyph 1990 41" which will be the 41st day of the year 1990 being the 10th of February!!
lcrm is used to reverse a longcount date as in "lcrm 13.0.13.6.12" which will give the gregorian date 2026-02-23 ... dates before the First of January 0001 may be out by 1 or 2 days due to the vageries of the date command in different versions of linux!!
These scripts were really for my own use but if anyone else finds some use for them then all good and well ... modify as you please just leave the comments in and add your own!!

Cheers - Rhonda Dyane Brûçé 
http://rhondadyane.ddns.net
