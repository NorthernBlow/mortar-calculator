# Squad Mortar Calculator

Squad is a modern military combat simulator which relies heavily on strategy and teamwork.

This is a work in progress for a distance finding tool. The calculator will quickly translate the alphanumerical coordinates provided from the in-game map and produce a range, angle, and degree of measurement needed to fire artillary pieces accurately.

## The in game map
In the game Squad, there is a very large map divided into sectors. Each sector has a coordinate (such as A1, B4, F9). This would normally be very simple to calculate, however the sectors are large blocks that can range between 15,000 and over 100,000 square meters. 
For better accuracy, each sector is divided into 9 blocks. Each block is referenced in game the same way a numerical keypad is arranged. Within each block is another sub block that is divided down in a similar fashion. The challenge is to feed the calculator a coordinate from the in game map (A153 : Sector A1 - SubBlock 5 - MiniBlock 3) and translate it into an actual x/y coordinate.

![ScreenShot](https://github.com/Strmiska/mortar-calculator/blob/master/Squad%20Map.jpg?raw=true)

Here is a visual example of what I am trying to accomplish:

![ScreenShot](https://github.com/Strmiska/mortar-calculator/blob/master/Map%20Reference.png?raw=true)
