# Kickstarting with Excel
Exercising different techniques on Excel to create charts that show information in relation to launch dates and funding goals

## Overview of the Project
### With the methods that have been taught through module 1, the purpose of this project was to use what we have learned to create two analyses on Excel using the previous dataset 'Kickstarter" to help create visualizations. The two analyses that are created are to help show Louise the different campaigns and how the campaigns are related to their launch date and and funding goals.
## Analysis and Challenge 
### Analysis of Outcomes Based on Launch Date
- When creating the analysis and visualization for "Outcomes Based on Launch Date", what I did first was pull up the Kickstarter dataset and extract the year from the column: date created conversion. I copied the column: dates created conversion by clicking on the letter column, then clicking on the button CTRL + C to copy the whole column. Afterwards, I used the YEAR() function to extract the year from the M/D/Y. Continuing on, I created a pivot table and filtered the table by dragging the appropriate pivot table fields to its correct spots. Lastly, I clicked on pivot Chart and made sure to choose line chart to create a visualization showing what theater campaigns were successful, canceled, and failed.  
- YEAR() function link: [https://support.microsoft.com/en-us/office/year-function-c64f017a-1354-490d-981f-578e8ec8d3b9?ui=en-us&rs=en-us&ad=us]
- (![extracting year from date created conversion column](https://user-images.githubusercontent.com/101531875/160308282-61661fef-9ac8-4eff-9b90-2e280b254bdd.png)
### Analysis of Outcome Based on Goals
- For the Analysis of Outcome Based on Goals, percentages were needed to be shown to see the overall success rate, failed rate, and canceled rate for plays only. This Analysis required more work and skills to create the visualization. First, I created a new sheet in the Kickstarter datasheet, and created new column titles that were listed in the challenge, along with fill in the 'Goals' column with the appropriate dollar- ranges. Using a new function: COUNTIFS(); that function was used in the columns: Number Successful, Number Failed, and Number Canceled. The COUNTIFS fucntion aplies a specific criteria to cells across multiple ranges and counts how many times that criteria is met. After finding the amount of succcessful, failed,and canceled plays within its specific dollar-range, next was finding the sum of total projects. To find the sum, I had to use the SUM() function. After that, was finding the percentage of successful, failed, and canceled projects; to do that I divided the number of successful/failed/canceled by the total project to get a percentage. After finishing up the sheet, I created a line chart by selecting the entire new sheet and click insert chart. I then deleted the columns that were not needed and only kept the percentage of successful, failed, and canceled, along with the goals column. To finish the analysis up, I added a chart title to the line chart and changed some colors of the line within the chart tomake the visualization easier to read.
 ### Challenges and Difficulties Encountered
- When creating both of the analyses, I did come across from difficulties that I was able to overcome with the help of going over my previous work and asking for help. 

- In the beginning of creating an analysis for "Outcomes Based on Launch Date" I had trouble with extracting the year from the column date created conversion, because when I first copied the date created conversin column into the new row "Years" it gave me 1/1/1970 and then when I used the YEAR() function to extract, it gave me a date of 7/7/1905 and I knew that was wrong. I tried many ways to fix it, such as changing the column frmo general to short date, long date and time, but it did not work. After a while of not being able to figure it out I reached out an instructor for help, and with the help of the instructor, i was able to extract the year from the date created conversion column. To extract the year from the date created conversion column:
-     1) I clicked on the first cell listed in the column "date created conversion"
-     2) I clicked on the formula bar and changed the currect formula that was listed to the M/D/Y that was shown in the cell I selected
-     3)![year column extract](https://user-images.githubusercontent.com/101531875/160310612-a49c2f12-12cc-4ffe-bfdf-2f2a63953e60.png)
-     4) after changing the formula to the M/D/Y shown in its specific cell, the YEAR() function worked and was able to extract the year from the date created conversion column

- Throughout doing the analyses, evrything went through smoothly. Th only other difficuly I came across, was when it was time to double check the columns in the new sheet "Outcome Based on Goals" for the Anaylsis "Outcome Based on Launch Goals Chart". It was diificult because I had to make sure I used the right greater than/less than signs when plugging into the COUNTIFS() function, along with use the right formula when findnig the percentages. Being precise was important because it could have nessed up the line chart that was created at the end.
## Results
- After creating the Analysis for "Theater Outcomes by Launch Date", two conclusions I can make is
-   1) The most successful month to launch is in May, because May shows in both Pivot table and line chart that it has the most successful number of theater launches.
-   2) By looking at the line chart that I created, theater is not as popular as plays because the amount of canceled theater launches is higher than the amount of plays that wre canceled.
-  Based on the Outcomes Based on Goals, the plays that cost less had higher successful percentage, compared to the plays that costed more. I came to that conclusion, because in the line chart that was craeted for the percentages of successful, failed, and canceled; the highest peak for successful plays were when the plays costed from a range of less than 1000 to 4999. 
-  Some limitations on the kickstarter dataset is when inputting the wrong number into a cell, it can ruin the entire spreadsheet. Another limitation is, if you do not save the dataset then you can lose your work.
-  With both analyses, some tables/ charts that could have also been created are pie charts. Pie charts are a great visualization because it is color coordinated and shows the part-whole relationship. It is especially great when showing percentages, because it shows visually how much of a percent something is by the amount of color that is shaded in within the pie chart. 
-   For the Theater Outcome by Launch Date Chart, another chart that would have been good is a clustered column chart. That would be another great option because it can compare the multiple series next to each other; such as successful, failed, and canceled in the month of January, and so on.
