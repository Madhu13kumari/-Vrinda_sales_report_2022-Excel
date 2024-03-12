# -Vrinda_sales_report_2022-Excel
Downloaded dataset & open in excel.
Data cleaning
Cross checked data that is there any duplicate or null value while using filter one by one.
In Gender column data were not consistent it was ex: - men, m, women, w.
Used filter selected data one by one replaced all M with men and all W with women.
In Qty column also data was not consistent it was ex: -1, 2 ,3 ,4 ,5, one, two.
Replaced one with 1 and two with 2.
Data processing
To show relation between age and group created new column with name of Age group.
Formula =if(E2>=50, “Senior”, if(E2>=30, “Adult”, “Teenager”))
Double click to fill values in all columns.
Copied all age group column data and paste as value.
Inserted month column with help of date column.
Formula =text(g2, “mmm”)
Double click to fill values in all columns.
Data Analysis
Created pivot table.
(if data will be change in future so you just need click on pivot chart than click on pivot chat analyze click on refresh all in will update) 
Question 1
Sales and orders in one chart
In values 
Sum of amount
Count of order id 
In row
Month
Went into design in grand total and off for row and column.
Selected all data and created combo chart and added secondary axis.
Right clicked in chart and clicked on hide all field buttons on chart.
Added chart title renamed as orders vs sales, resized.
Removed gridlines and double click on values went into format axis, went into format code removed General and wrote formula = 0.00,, “m”.
Created new sheet renamed Vrinda sales report 2022.
Created heading with name of Vrinda sales report 2020 marge column resized bold font colour change and background colour change.
Pasted the column chart in Vrinda sales report 2022 sheet.
Question 2
Men vs women
Went into Vrinda store data sheet created pivot table.
In row
Gender
In value
Amount
Went into design in grand total and off for row and column.
Selected all data and went into pivot chart created pie chart.
Right clicked in chart and clicked on hide all field buttons on chart.
Added chart title renamed as, sale: men vs women, converted value into percentage resized.
Added data labels with data callout and did formatting.
Pasted the pie chart in Vrinda sales report 2022 sheet.
Question 3
Order status
In row 
Status
In values
Count of order 
Went into design in grand total and off for row and column.
Selected all data and went into pivot chart created pie chart.
Right clicked in chart and clicked on hide all field buttons on chart.
Added chart title renamed as orders vs status, converted value into percentage resized.
Added data labels with data callout and did formatting.
Pasted the pie chart in Vrinda sales report 2022 sheet.
Question 4
TOP 3 STATE
In row 
Ship-states
In values
Sum of amount
Went into design in grand total and off for row and column.
Selected all data and created bar chart.
Right clicked in chart and clicked on hide all field buttons on chart.
Added chart title renamed as top: 3 states, resized.
Added data labels did formatting.
Removed gridlines and double clicked on values went into format axis, went into format code removed general and wrote formula = 0.00,, “m”.
Pasted the bar chart in Vrinda sales report 2022 sheet.
Question 5
Men vs women
Went into Vrinda store data sheet created pivot table.
In row
Age group
In value
Order id
Column
Gender
Went into design in grand total and off for row and column.
Right click on data click on show value as % of grand total.
Selected all data and went into pivot chart created column chart.
Right clicked in chart and clicked on hide all field buttons on chart.
Added chart title renamed as, orders: age vs gender, resized.
Added data labels with data callout and did formatting.
Pasted the column chart in Vrinda sales report 2022 sheet.
Question 6
Orders vs channel
In row 
Channel
In values
Count of order id
Went into design in grand total and off for row and column.
Right click on data click on show value as % of grand total.
Selected all data and went into pivot chart created pie chart.
Right clicked in chart and clicked on hide all field buttons on chart.
Added chart title renamed as orders: channel.
Added data labels with data callout and did formatting.
Pasted the pie chart in Vrinda sales report 2022 sheet.
Changed background colour and remove gridlines.

(You can only get the option of slicer when you have created pivot chats.)
Now went to Vrinda sales report 2022 sheet and clicked on any chat went to pivot data analyze went into slicer option selected month channel and category, added slicer.
Right clicked on any slicer and went into report connections selected all sheet and clicked ok.
Did the same with another 2 slicers.
