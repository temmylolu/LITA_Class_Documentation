# LITA_Class_Documentation
This is where i documented my first project while learning Data Analysis with the incubator Hub

---
### Project Overview
In this project, we explore data analysis methodologies using Microsoft Excel, SQL, and Power BI. These tools are widely used for data manipulation, query-based insights, and powerful visualizations. The goal of this project is to showcase an end-to-end data analysis workflow that includes data exploration, transformation, and visualization. By the end of the project, we will produce interactive dashboards and reports to present actionable insights for decision-making.

---
### Key Objectives
1. Data Exploration and Transformation with Excel: Use Excel to clean, explore, and summarize the data. This includes using pivot tables, basic functions, and charts to identify initial trends and patterns.

2. Data Querying with SQL: Employ SQL queries to extract meaningful insights from the dataset. SQL allows for efficient data manipulation and aggregation, helping to answer key business questions by breaking down data by categories, dates, regions, and other dimensions.

3. Data Visualization with Power BI: Create interactive dashboards using Power BI to visualize insights discovered in Excel and SQL. The dashboard will allow for real-time interaction, drill-downs, and filtering to uncover trends, performance indicators, and areas of interest.

---
### Tools Used
This project utilizes the following tools and technologies for data analysis and visualization:
- Microsoft Excel: For initial data exploration, pivot tables, and calculations (e.g., average subscription duration, subscription patterns).
- SQL Server: For data storage, querying, and extraction of key insights through SQL queries.
- Power BI: For creating interactive dashboards to visualize customer segments, cancellations, and subscription trends.
- Github for Portfolio Building

---
### Microsoft Excel 
#### Key Topics Covered
1. Excel Basics
   - Navigating the Interface: Understand Excel’s toolbar, navigation, and keyboard shortcuts.
   - Data Entry and Cell Formatting: Learn to input data, adjust cell sizes, apply styles, and use basic data formatting tools.
2. Essential Excel Functions
   - Explore and practice the following categories of Excel functions:
- Mathematical Functions:
   - SUM, AVERAGE, MIN, MAX, and ROUND for basic arithmetic and data aggregation.
- Text Functions:
   - CONCATENATE, UPPER, LOWER, TRIM, and LEFT/RIGHT to manipulate text data.
- Logical Functions:
   - IF, AND, OR, and NOT for conditional logic.
- Lookup Functions:
   - VLOOKUP, HLOOKUP, INDEX, and MATCH for searching and matching data across tables.
- Date and Time Functions:
   - TODAY, NOW, YEAR, MONTH, and DAY for managing date and time values.
- Statistical Functions:
   - COUNT, COUNTA, COUNTIF, SUMIF, and AVERAGEIF for data analysis and counting based on criteria.
3. Data Visualization in Excel
- Creating Charts: Step-by-step guide to creating bar charts, line charts, pie charts, and scatter plots.
- Formatting and Customization: Adjust chart colors, labels, and legends to enhance readability and visual appeal.
- Using Sparklines: Embed small visualizations within cells to show trends and comparisons.
4. Practice Exercises and Real-World Examples
- Each topic is accompanied by exercises and real-world examples (e.g., personal budget sheet, sales report). Users are encouraged to practice with these examples to reinforce their skills.

----
#### Number functions in  ExceL
-Basic Numeric Functions
  - SUM: Adds a range of numbers.: =SUM(A1:A10) sums values from A1 to A10.
  - AVERAGE: Calculates the mean of a range.: =AVERAGE(A1:A10) returns the average.
     MIN and MAX: Finds the minimum or maximum value in a range.: =MIN(A1:A10) and =MAX(A1:A10)
  - COUNT: Counts the number of cells with numbers: =COUNT(A1:A10) returns the count of numeric cells,
##### EXAMPLE
![Basic Excel functions](https://github.com/user-attachments/assets/7d6b7423-a99a-4698-a4dc-b0424fabf529)

- Conditional functions
   - The Excel functions used in calculating for this datasheet is a conditional function: AVERAGEIF, SUMIF, MAXIF, MINIF, COUNTIF.
   - The calculations are shown in the worksheet
  #####  EXAMPLE 
![Basic excel function2](https://github.com/user-attachments/assets/a957c2da-65a9-4c38-9b6e-bde81afb9936)

----
#### Text cleaning in Excel

1. Basic Text Cleaning Functions
- TRIM(text): Removes all extra spaces from a string, except single spaces between words.
- CLEAN(text): Removes all non-printable characters from a text string.
- LOWER(text), UPPER(text), and PROPER(text):
   - LOWER(text): Converts all characters to lowercase.
   - UPPER(text): Converts all characters to uppercase.
   - PROPER(text): Capitalizes the first letter of each word in a text string.
##### EXAMPLE
![Basic cleaning functions](https://github.com/user-attachments/assets/c789a33c-38df-4c73-9a95-80b10a467953)

----
 2. Text Extraction Functions
- LEFT(text, num_chars): Extracts a specified number of characters from the left side of a string.
- RIGHT(text, num_chars): Extracts a specified number of characters from the right side of a string.
- MID(text, start_num, num_chars): Extracts a specified number of characters from the middle of a string, starting at a given position.
- LEN(text): Returns the length (number of characters) of a text string.
 ##### EXAMPLE
 ![Text extraction](https://github.com/user-attachments/assets/1b554027-4166-43f7-a477-93fbe841edb1)

----
 3. Finding and Replacing Text
- FIND(find_text, within_text, [start_num]): Finds the starting position of one text string within another. Case-sensitive.
- SEARCH(find_text, within_text, [start_num]): Similar to FIND, but case-insensitive.
   REPLACE(old_text, start_num, num_chars, new_text): Replaces part of a text string with a different text string, based on a position and length.
- SUBSTITUTE(text, old_text, new_text, [instance_num]): Replaces occurrences of specific text within a string.
  
4. Text Concatenation
- & Operator: Joins (concatenates) multiple text strings.
- TEXTJOIN(delimiter, ignore_empty, text1, [text2], ...): Joins multiple text values with a specified delimiter.
- CONCATENATE(text1, [text2], ...): Joins text from different cells or strings. (Note: In newer versions of Excel, CONCATENATE is replaced by CONCAT).

5. Conditional Text Extraction
- IF: Conditional functions to clean and handle errors.
- LEFT, RIGHT, MID with SEARCH: Use in combination to extract variable-length text based on specific markers.
