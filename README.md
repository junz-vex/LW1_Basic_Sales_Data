# LW1_Basic_Sales_Data
Getting Started with Power BI – Loading and Exploring Data

Step 1: Open Power BI Desktop

● Click Start

● Open Microsoft Power BI Desktop

● Wait for the startup screen

<img width="498" height="320" alt="image" src="https://github.com/user-attachments/assets/b3bb63bd-fd93-4a8a-aad3-6700f7698e47" />


Step 2: Load the Dataset

1. Click Home Tab

2. Click Get Data

<img width="1883" height="999" alt="image" src="https://github.com/user-attachments/assets/4fa966b1-4628-4c2e-a662-d3a06c0d2523" />

3. Select Text/CSV
 
<img width="1700" height="942" alt="image" src="https://github.com/user-attachments/assets/6931c3f3-0677-4c92-9372-7a49a642ed73" />


4. Browse and select:

Week1_Basic_Sales_Data.csv

5. Click Load
   
<img width="626" height="472" alt="image" src="https://github.com/user-attachments/assets/90d9fdf6-5a8a-439a-acc9-364f3cf24bc8" />

Step 3: Verify Data in Data View

1. Click the Data View icon (table icon on the left)
   
<img width="580" height="617" alt="image" src="https://github.com/user-attachments/assets/6ae176c6-d341-465d-88c5-7d0d13563476" />  

3. Check:
   
   ○ Are all columns visible? yes
   
   ○ Is “Date” formatted as Date? yes
   
   ○ Is “Sales” formatted as Decimal Number? yes
   

<img width="627" height="376" alt="image" src="https://github.com/user-attachments/assets/f1ae2c51-ce9c-46db-8bdb-4edf3d2ee4d8" />
1. Click the column
   
2. Go to Column Tools
   
3. Change Data Type accordingly:
   
○ Date → Date

○ Sales → Decimal Number

○ Product/Category/Region → Text

<img width="1079" height="989" alt="image" src="https://github.com/user-attachments/assets/17007163-52ca-414b-b00c-9023477c2374" />

PART 2: Exploring the Interface

<img width="377" height="113" alt="image" src="https://github.com/user-attachments/assets/1b542623-b767-4fa1-8ae7-d9a1b70cf096" />

REPORT VIEW
<img width="734" height="656" alt="image" src="https://github.com/user-attachments/assets/4889d152-be21-4e9b-bd7a-7311f745f274" />

DATA VIEW
<img width="188" height="246" alt="image" src="https://github.com/user-attachments/assets/a12fce5c-a992-470d-a9a3-8fbca903c9b2" />

MODEL VIEW
<img width="430" height="301" alt="image" src="https://github.com/user-attachments/assets/e7f61590-3262-45cc-be5d-1bcce332e1c1" />

Switch back to Report View.

PART 3: Creating Auto-Generated Visuals
Step 1: Quick Visualization

1. Drag Sales into canvas
<img width="1919" height="786" alt="image" src="https://github.com/user-attachments/assets/c5481c11-56b3-43f4-9095-d0acc2d9a9ad" />

2. Power BI automatically creates a visual
Question:

● What type of chart was created?

Clustered Column Chart
 

● What does it show?

stacked chart for Sum of sale

Step 2: Create a Sales by Region Chart

1. Click blank canvas

2. Select Clustered Column Chart

<img width="1918" height="769" alt="image" src="https://github.com/user-attachments/assets/e6a4a676-ad95-4c79-b07d-fb34d759e3d0" />

4. Drag:

○ Region → X-axis

○ Sales → Values

*Which region has the highest sale?

answer: West

Step 3: Sales by Category:


1. Insert a Pie Chart
   
2.  Drag:
   
*Category → Legend

*Sales → Values

<img width="949" height="414" alt="image" src="https://github.com/user-attachments/assets/5f712105-db0d-46df-9597-0280863c475c" />

Question:

*Which category dominates?

answer:Electronics

*Is the distribution balanced?

answer:no

Step 4: Sale over time

1.Insert line chart

2.drag

*date- X axis

*sales- Values

<img width="448" height="349" alt="image" src="https://github.com/user-attachments/assets/ab03c4c9-57d7-48e4-b171-1016ce2e354a" />


Question:

*Is there growth?

answer:no

*Any noticeable trends?

answer:The chart shows a sharp, linear decline in sales from approximately 0.2M in 2024 to nearly zero in 2025.

PART 4: Basic Data Insight Interpretation

Students must now interpret visuals.

Question:

● Which region contributes most revenue?

answer: west region

● Which product category performs best?

answer:Electronics

● Are sales consistent across dates?

answer:No, sales are not consistent across dates because the data for 2025 is currently limited to the month of January, causing a misleadingly sharp drop compared to the full year of 2024.

● What business recommendation can you suggest?

answer:recommendation is to adjust the report to compare Year-to-Date (YTD) performance (e.g., January 2024 vs. January 2025) to avoid the "cliff effect" caused by comparing a full year of historical data against an incomplete current year.

Part A – Technical Questions
●What are the five columns in the dataset?

Answer:The columns are Date, Region, Product, Sales, and Quantity.

●What data type is assigned to the "Sales" column?

Answer:In Power BI, it is assigned as a Decimal Number (or Currency).

●Which Power BI view allows you to see raw data?

Answer:The Table view (formerly Data view).

●What chart type is best for showing trends over time?

Answer:A Line chart.

●What aggregation is automatically applied to Sales?

Answer:The Sum aggregation.

Part B – Analytical Questions
●Which region has the highest total sales?

Answer:Based on the dataset, North consistently shows the highest sales volume.

●Which category has the lowest performance?

Answer:The South region and the Accessories product category show the lowest performance metrics.

●Are sales increasing, decreasing, or stable?

Answer:Sales appear to be decreasing sharply on the year-over-year chart; however, this is a "false" trend because 2025 only contains January data while 2024 contains a full year.

●If you were a manager, which region would you prioritize?

Answer:I would prioritize the South region to investigate why its performance lags significantly behind the North and West.

●Provide one actionable recommendation based on the data.

Answer:Implement Year-to-Date (YTD) tracking: Since comparing a full year (2024) to a partial year (2025) creates a misleading downward trend, the business should use YTD comparisons to accurately measure growth.

ENHANCEMENT SECTION

Advanced Exploration

Students must perform the following:

Task 1: Add a Card Visualization

1. Insert Card

2. Drag Sales

3. Format:

○ Increase font size

○ Change title to “Total Sales”

<img width="296" height="239" alt="image" src="https://github.com/user-attachments/assets/48dc888d-b851-4a8b-b009-297fb4b4e8a0" />

Question:

● What is the total sales amount?

Answer:220k

Task 2: Add Slicer

1. Insert Slicer

2. Drag Region

3. Test filtering

<img width="1353" height="744" alt="image" src="https://github.com/user-attachments/assets/cff0d410-efd1-4d1f-b5af-f270f48c9d76" />

Question:

● What happens to other visuals when you click a region?

answer:When you click a region, the other visuals are cross-filtered or cross-highlighted to display data exclusively for that selection, which is important in BI because it allows users to isolate specific segments for more granular analysis.

● Why is filtering important in BI?

answer:Filtering is important in BI because it allows users to isolate specific data subsets, such as a single region or product, to uncover granular insights and ensure accurate comparisons that would otherwise be obscured by high-level totals.

Task 3: Sort Sales

1. Click Region Chart

2. Click three dots (...)

3. Sort by Sales Descending

<img width="678" height="297" alt="image" src="https://github.com/user-attachments/assets/7737bf53-128f-4d7d-b962-e33adc6d530f" />


Question:
● Does sorting improve readability?

Answer:Sorting improves readability by organizing data into a logical sequence, such as chronological or numerical order, which allows users to quickly identify high or low performers and recognize patterns without scanning every row.

● Why?

answer:
Sorting improves readability because it organizes data into a logical sequence such as chronological or numerical order—allowing the eye to immediately identify peak performers, outliers, and patterns without manually scanning every row.


Task 4: Identify Outliers

● Which region is significantly higher or lower?

● What might explain that difference?



   









