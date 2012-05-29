RepRap-XYZ
==========

This is a really simple spreadsheet I put together to calculate the X, Y and Z axis firmware values based on printing 2 (or more) test cubes.


How to use
==========

1) Open the included xls file in your favorite spreadsheet program.

2) Download this configuration cube from Thingiverse: http://www.thingiverse.com/download:5839 (You can use another configuration cube, but you will need to update the target values for x, y and z in your spreadsheet.)

3) Enter your initial firmware settings for x, y and z on the first line.

4) Print the calibration cube.

5) Using a set of calipers, measure (only go about half-way down each axis for a more accurate rating) and enter the values you got from the current x, y and z settings.  If you don't have calipers, these ones from Amazon are quite good for the price: http://www.amazon.com/gp/product/B000GSLKIW

6) For any axis that isn't perfect, change the firmware values and enter the new numbers on the second line of the spreadsheet.  The values don't really matter, we are just using them to test the difference.  Then repeat steps 4 and 5.

7) After you have at least two rows of values (you can do more if you like) enter the recommended values from the last line of the spreadsheet into your firmware.

8) Print one more test cube.  It should be really accurate.  If it is off, enter these values you got on the third line of the spreadsheet and add one to the number of results.  Then repeat step 7 and 8.
