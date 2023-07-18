# EV Car Sales Project

## Overview
In this project, the first step was to clean the dataset I had obtained. Let me walk you through the steps I followed to do so.

This is what the dataset initially looked like:

![Image Not Available!](https://github.com/shounjacob/EV_Car_Sales/blob/main/Screenshots/1.JPG)


### **STEP 1**
The first thing I did was delete the "Logo" column, as it seemed out of place and was not necessary for my analysis.


### **STEP 2**
After that, I fixed the formatting of the dates, as there were many different formats.

![Image Not Available!](https://github.com/shounjacob/EV_Car_Sales/blob/main/Screenshots/2.%20date%20change.JPG)


### **STEP 3**
Upon observing the cell values, I noticed that there was a "â€¬" string in multiple cells, which seemed unnecessary. I removed those next.

![Image Not Available!](https://github.com/shounjacob/EV_Car_Sales/blob/main/Screenshots/3.%20replace%20weird%20text.JPG)


### **STEP 4**
There was also wrong comma formatting for some of the values, so I rectified that before changing the formatting of all the number values to comma style.

![Image Not Available!](https://github.com/shounjacob/EV_Car_Sales/blob/main/Screenshots/4.%20replace%20commas.JPG)


### **STEP 5**
I replaced all the empty cells within the dataset range to 0.


### **STEP 6**
Finally, I created a new column, "Total Sales" with the sum of all the sales for each EV model. 

*Now, the dataset is ready to visualize in Tableau!*


