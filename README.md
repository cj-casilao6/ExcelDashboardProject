# Overview
Firstly, get an excel file regarding bike sales. Next is to clean the data so that I could build PivotTables to showcase a relationships between a number of different columns. From there, create a few PivotCharts that would eventually be put together onto a final dashboard which also have Slicers so the user can filter the columns on their desired criteria.

# Raw Excel Data
Below is a sample of the raw excel sheet. (Total rows: 1027)

<img width="975" height="778" alt="image" src="https://github.com/user-attachments/assets/558e93cd-45a6-4736-bae3-add45b7d5bfd" />

# Data Cleaning
**Steps to clean data**:

0) Create a working sheet (duplicate) of original sheet to avoid changes to original data
1) Remove duplicate row(s)
2) Formatting/standardization
   
    EX: Change single letter acronym to full word (M->Married, S->Single, ...)
3) Look for bad data
   Done by using excel filter dropdowns to look for possible values to change
   
4) Replace bad data

   EX: Use age brackets rather than using each response's individual age

Below is a sample of the cleaned excel sheet. (Total rows: 1001)

<img width="1147" height="774" alt="image" src="https://github.com/user-attachments/assets/a9381e07-8ca2-4bd0-8442-ccafc8926485" />

# PivotTables/PivotCharts
Now that we have our desired clean excel sheet. Choose some relation between columns to built PivotTables on.
(Below are examples of the chosen relationships)

## Average income split by gender and whether a bike was purchased:

### PivotTable:

<img width="453" height="80" alt="image" src="https://github.com/user-attachments/assets/e69cd887-48c2-4581-a415-002f27465fc1" />

### PivotChart:

<img width="452" height="374" alt="image" src="https://github.com/user-attachments/assets/b3345603-0ef7-461c-ab43-ad55a8ad8dec" />

## Count of bikes purchased related to commute distance and whether a bike was purchased:

### PivotTable:

<img width="457" height="129" alt="image" src="https://github.com/user-attachments/assets/8628883a-7fb6-44ae-b138-db61c16b7805" />

### PivotChart:

<img width="1017" height="321" alt="image" src="https://github.com/user-attachments/assets/8f614abe-dfbd-4f4c-a8c8-fe4cd6e358ca" />

## Age brackets and whether a bike was purchased:

### PivotTable:

<img width="454" height="98" alt="image" src="https://github.com/user-attachments/assets/725ab2a2-298c-4333-9aa1-4683b49995f8" />

### PivotChart:

<img width="544" height="378" alt="image" src="https://github.com/user-attachments/assets/aca172f0-2228-4195-962b-68f08b87d6f8" />

# Final Dashboard
After making the PivotCharts, combine them into a dashboard on a new sheet. Along with the PivotCharts, add Slicers so the end user is able to select the values within each column to look for specific information which will automatically update the dashboard's PivotCharts.

<img width="1171" height="829" alt="image" src="https://github.com/user-attachments/assets/f7d412f2-3dc1-4322-b876-df9203b79fcc" />


