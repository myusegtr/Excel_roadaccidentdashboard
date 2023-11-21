## Road accident dashboard

The requirement is to make a dashboard which will give a quick insight about the accidents happen in 2021/2022.

Some of the basic inferences needs to be drawn are:- 

Total No. of casualities
By road,By vehicle type,monthly trend etc.

Steps:-
Apply filter to all the columns. This to easily check for anu null values for all the columns one by one.
Check for primary key column.(Data cleaning part ends here).

(Data processing part)
Now we will try to add a month column to show the monthly trend.(=TEXT(A1, "mmm"))
Do the same for year also.

(Data Analysis & data visualization)

Select any cell ,go to insert then select pivot chart.

Then convert sum of number of casualities based on accident types in percentages.
Then create a pie chart of it.

For dashboard open a new sheet ...go to view & uncheck grid lines. Now go to insert then shapes to add various shape blocks to showcase different scenarios.
Select the block go to shape format select no ouline(check it).

Select any cell in KPI sheet ...go to pivot table analyze & select insert timeline

Now copy paste the pie chart along side the fatal,serious,slight blocks.Then right click and select format chart area ...choose no fill,no border.

Now for analyzing other kpi ...we need to group some categories into one like for vehicle type(like taxi ,car,mini car into one group cars). For that select any cell go to pivot table analyze and select fields,items & sets to select particular items from different labels.

Now do the same percentage calculation for casualities by various vehicle types.

Now to add some pre built icons make sure you are connected to internet, then go to insert then select illustrations or icons directly to add some visual looking icons.(Search for vehicles).

Now for third KPI to showcase monthly trend ...add a new pivot table and in that choose month in rows,year in filters and casualities in values. Create a combined table for monthly trend & then select entire table then insert then choose 2d line.

Insert another pivot table for casualities by road type.To round figure the values in 1000 select the cells & then press ctrl+1 to open format cells dialog box .(0.0,"K")

Now select the table then go to pivot table analyze then choose pivot chart then bar chart .

Insert another pivot table for road surface conditions.
Insert another pivot table for rural & urban.
Insert another pivot table for day & night light.

Now need to connect this timeline(accident) to all the pivot blocks so for that right click on timeline table & click report connections. U can also create a rural & urban slicer just select the table then choose slicer instead of timeline.

Add some icons on the left if possible.

Next tasks need to insert hyperlinks plus data analysis part.

