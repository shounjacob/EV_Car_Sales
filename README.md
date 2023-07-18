# EV Car Sales Project

## Overview
The main objectives of this project were to:

1. Clean the data using Microsoft Excel.
2. Visualize the data using Tableau.

*NOTE* : This data is about EV sales between January 2012 and September 2019.


## PART 1: Excel

This is what the dataset initially looked like:

![Image Not Available!](https://github.com/shounjacob/EV_Car_Sales/blob/main/Screenshots/1.JPG)

[Access the initial dataset here](https://github.com/shounjacob/EV_Car_Sales/blob/main/Electric%20Car%20Sales%20by%20Model%20in%20USA%20(INITIAL).csv) 

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

[You can view the cleaned dataset here](https://github.com/shounjacob/EV_Car_Sales/blob/main/Electric%20Car%20Sales%20by%20Model%20in%20USA.csv)

*Now, the dataset is ready to visualize in Tableau!*








## PART 2: Tableau

Using the cleaned dataset, I obtained the following insights:

### ELECTRIC VEHICLE MARKET SHARE
![Image Not Available!](https://github.com/shounjacob/EV_Car_Sales/blob/main/Screenshots/TAB%201.JPG)

### TOP 5 LEADING EV MANUFACTURERS
![Image Not Available!](https://github.com/shounjacob/EV_Car_Sales/blob/main/Screenshots/TAB%202.JPG)

### TOP 10 BEST-SELLING EV MODELS
![Image Not Available!](https://github.com/shounjacob/EV_Car_Sales/blob/main/Screenshots/TAB%203.JPG)


[This tableau file can be accessed here](https://public.tableau.com/app/profile/shounjacob1204/viz/EVCarSales_16896319792250/MyStory)
