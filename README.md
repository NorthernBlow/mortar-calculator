# Squad Mortar Calculator

Squad is a modern military combat simulator which relies heavily on strategy and teamwork.

This is a work in progress for a distance finding tool. The calculator will quickly translate the alphanumerical cordinates provided from the in-game map and produce a rage, angle, and degree of measurement needed to fire artillary pieces accurately.

## The in game map
In the game Squad, there is a very large map divided into sectors. Each sector has a cordinate (such as A1, B4, F9). This would normally be very simple to calculate, however the sector are large blocks that can range between 15,000 and over 100,000 square meters. 
For better accuracy each sector is divided into 9 blocks each with a numerical reference that looks like the number pad on a keyboard. Within each block is a sub block that is divided down in a similar fashion. So The challenge is to feed the calculator a cordinate from the in game map (A153) and translate it into an actual x/y cordinate.

![ScreenShot](https://github.com/Strmiska/mortar-calculator/blob/master/Squad%20Map.jpg?raw=true)

