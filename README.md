# Day-of-Week-TI-84Plus-CE

### This is a day of week calculate tool for the TI-84+ CE.
### There are two versions, one of them is written in TI-BASIC and therefore also compatible with newer OS versions, the other is written in ICE.

#### why is this different from the standard DayofWk( command?
The standard DayofWk( command calculates all dates using the formula for the Gregorian calendar.
This is for most dates just fine, but if you want to know what day of week it was on a date when they still used the Julian calendar DayofWk( won't give you the correct day.
For that reason I've made this program, where you can set the date your country switched to the Gregorian calendar manually.
The program will then calculate the day of week for any date you give, for your country.

#### How to download the program?
You can download the program via 'releases'

#### How to send the program to your calculator?
You can easily send the program to your calculator using TiLP or TI-connect CE.
Once you've sent it to your calculator there are two possible options to run the program, for the ICE version:
-If the OS of your calculator is 5.5 or higher, then you should run the program via Cesium, or use asmhook.
-If the OS of your calculator is 5.4 or below, you can just run the program via the [prgm] menu.
For the TI-BASIC version:
-Just run the program via the [prgm] menu

#### How do I use this program?
Once you open the program you can press:
-[2nd] to go to the settings
-[enter] to calculate the day of week
-[clear] to exit
-[mode] to see what version you have

###### What are the settings?
There are two different settings:
-On what date your country switched to the Gregorian calendar
-If you want the dates in YYYY-MM-DD, MM-DD-YYYY or DD-MM-YYYY
These settings are all stored in appvars.

Once you press [enter] in the first screen, you'll be asked the year, month and day in the order you selected in the settings.
The default setting is that you see the notation: YYYY/MM/DD.

#### Will the program be 100% correct?
Well, it is very difficult to say if it is correct, but as far as I've tested, all dates were correct, and I did test it thoroughly.

#### How does the program calculate the day of the week?
This program makes use of the Zellers Congruence to calculate the day of the week.
This is are two formulas that can be used to calculate the day of week in the Gregorian and Julian calendar.
If you want to know more, I reccomend reading the wikipedia page about it: https://en.wikipedia.org/wiki/Zeller%27s_congruence


The default setting for the date notation is: YYYY/MM/DD.
The default setting for the calendar switch is: 4 October 1582.

#### IMPORTANT NOTES: 
-If you live in Sweden, the dates that the Swedish calendar was used (from 1700 till 1753) will NOT be correct.
-If your country used another calendar than the Julian before changing to Gregorian, you should input in the settings the first gregorian date
-If your country used another calendar than the Julian before changing to Gregorian, you can ONLY calculate dates from 14 days after the calendar change and later.
-If you live in Turkey, you should input as calendar change 1 Januari 1926, since that's when they also took the current year counting.

-------------------------------------------------------------------------------


If you find any bugs, feel free to contact me via: privacy_dragon@tutanota.com or create a issue
