
# Blinkit-Dashboard

### Dashboard Link : https://app.powerbi.com/groups/me/reports/384d017e-e935-44dc-9e7d-1626c1a36de1/ReportSection

## Problem Statement

This dashboard helps the us to understand blinkit store in different cities. It helps us to know  know how much total sales, and average sales are providing by different store. Through different ratings, we  get to know  improvement area, & thus they can improve their services by identifying these area. It also lets them know the average sales & total no of items  in different tier cities, thus since by using this dashboard we have identified  which items are mostly runs in different stores.

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors.
- Step 5 : For calculating average rating time,average sales, total sales, and total no of items we have calculated the dax formula 
 - Step 6 : Calculated column was created .
for creating new column following DAX expression was written;
      Average sales = AVERAGE('BlinkIT Grocery Data'[Sales]) 
      Average Rating = AVERAGE('BlinkIT Grocery Data'[Rating])
      No of Items = COUNTROWS('BlinkIT Grocery Data')
      Total sales = SUM('BlinkIT Grocery Data'[Sales])
        
Snap of new cards present on dashboard,
[Screenshot 2024-08-12 124328](https://github.com/user-attachments/assets/6ea45234-8e3d-4e37-8e6f-c8a3d555879b)

snap of  full dashboard
![Screenshot 2024-08-12 131722](https://github.com/user-attachments/assets/98d86ae2-1500-4aa7-9342-f4d58c071a35)




