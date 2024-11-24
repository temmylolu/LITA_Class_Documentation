# LITA_Class_Documentation
This is where I documented my first project while learning Data Analysis with the incubator Hub

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
#### Number functions in Excel
1. Basic Numeric Functions
  - SUM: Adds a range of numbers.: `=SUM(A1:A10)` sums values from A1 to A10.
  - AVERAGE: Calculates the mean of a range.: `=AVERAGE(A1:A10)` returns the average.
  - MIN and MAX: Finds the minimum or maximum value in a range.: `=MIN(A1:A10) and =MAX(A1:A10)`
  - COUNT: Counts the number of cells with numbers: `=COUNT(A1:A10)` returns the count of numeric cells,
##### EXAMPLE
![Basic Excel functions](https://github.com/user-attachments/assets/7d6b7423-a99a-4698-a4dc-b0424fabf529)

2. Conditional functions
   The Excel functions used in calculating this datasheet are conditional functions: AVERAGEIF, SUMIF, MAXIF, MINIF, and COUNTIF.
   - The calculations are shown in the worksheet
   - 
  ##### EXAMPLE 
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
- In this spreadsheet, PROPER, LOWER, UPPER, TRIM, and PROPER TRIM Function was used in the name extraction
    - `=PROPER(E6)`
    - `=LOWER(E6)`
    - `=UPPER(E6)`
    - `=TRIM(B6)`
    - `=PROPER(TRIM(B6))`
      
![Basic cleaning functions](https://github.com/user-attachments/assets/c789a33c-38df-4c73-9a95-80b10a467953)

----
 2. Text Extraction Functions
- LEFT(text, num_chars): Extracts a specified number of characters from the left side of a string.
- RIGHT(text, num_chars): Extracts a specified number of characters from the right side of a string.
- MID(text, start_num, num_chars): Extracts a specified number of characters from the middle of a string, starting at a given position.
- LEN(text): Returns the length (number of characters) of a text string.
  
 ##### EXAMPLE
 - In this spreadsheet, the LEFT  Function was used in extracting the departmental code 
   `=LEFT(B10,2)`
- The MID Function was used in extracting the purchase date code
   `=MID(B16,3,6)`
- The RIGHT Function was used in extracting the Asset category code
   `=RIGHT(B16,4)`
  
![Text Extration](https://github.com/user-attachments/assets/1da3545b-44c2-4261-865d-c297fb6af12b)

![Text extraction 2](https://github.com/user-attachments/assets/3e81a2b2-290a-4880-9d36-08b2ca16997d)



----
 3. Finding and Replacing Text
- FIND(find_text, within_text, [start_num]): Finds the starting position of one text string within another. Case-sensitive.
- SEARCH(find_text, within_text, [start_num]): Similar to FIND, but case-insensitive.
   REPLACE(old_text, start_num, num_chars, new_text): Replaces part of a text string with a different text string, based on a position and length.
- SUBSTITUTE(text, old_text, new_text, [instance_num]): Replaces occurrences of specific text within a string.
  
  ##### EXAMPLE
  ![Find function](https://github.com/user-attachments/assets/667bfc08-17dd-4cce-8ed5-8bb1665e34d7)

4. Text Concatenation
- & Operator: Joins (concatenates) multiple text strings.
- TEXTJOIN(delimiter, ignore_empty, text1, [text2], ...): Joins multiple text values with a specified delimiter.
- CONCATENATE(text1, [text2], ...): Joins text from different cells or strings. (Note: In newer versions of Excel, CONCATENATE is replaced by CONCAT).

5.  Lookup Functions:
   - VLOOKUP
       - This is the lookup value.
       - It refers to the value you want to find in the first column of the lookup range.
       - The dollar signs ($) indicate an absolute reference, meaning the cell reference won't change when the formula is copied to other cells.
       
##### EXAMPLE
- VLOOKUP practical
   - Calculation for the basic salary `=VLOOKUP($E$9, 'Simple Salary Structure'!$B$8:$I$16, 8, FALSE)`
   - Calculation for the Housing `=VLOOKUP($E$9, 'Simple Salary Structure'!$B$8:$I$16, 3, FALSE)`
   - Calculation for the Transport `=VLOOKUP($E$9, 'Simple Salary Structure'!$B$8:$I$16, 4, FALSE)`
   - Calculation for the Leave `=VLOOKUP($E$9, 'Simple Salary Structure'!$B$8:$I$16, 5, FALSE)`
   - Calculation for the Meal `=VLOOKUP($E$9, 'Simple Salary Structure'!$B$8:$I$16, 6, FALSE)`
   - Calculation for the Utility `=VLOOKUP($E$9, 'Simple Salary Structure'!$B$8:$I$16, 7, FALSE)`
   - Calculation  Gross pay `=VLOOKUP($E$9, 'Simple Salary Structure'!$B$8:$I$16, 8, FALSE)`
       
![Vlookup table](https://github.com/user-attachments/assets/73c9c163-dbd9-45b3-a845-a80b1a030a61)

![Salary structure table](https://github.com/user-attachments/assets/e0d3e929-edae-42c9-bcec-d443c65eedcc)

6. Conditional Text Extraction
- IF: Conditional functions to clean and handle errors.
- LEFT, RIGHT, MID with SEARCH: Combined to extract variable-length text based on specific markers.

 ##### EXAMPLE
 IF Function  `=IF(J2<20,"LOW",IF(J2<=50,"MEDIUM","HIGH"))`
 
![Conditional text extract](https://github.com/user-attachments/assets/d32b26c3-d80f-4cfe-8950-5fa9c95ccff1)

### DATA VISUALIZATION 
#### Pivot Tables
A Pivot Table is used for summarizing, analyzing, and presenting large datasets. It allows you to organize and manipulate data dynamically to extract meaningful insights, such as totals, averages, counts, and comparisons.
 ##### EXAMPLE
 
 ![Data sheet](https://github.com/user-attachments/assets/a8dbeb2e-227f-4228-8ea1-7c9b5d51088d)

- Region by Revenue

![image](https://github.com/user-attachments/assets/bb296fd1-5340-4083-ba18-43affb93ba03)

- Region by unit sold

![image](https://github.com/user-attachments/assets/38c88a4a-fb3b-4012-a713-2adc6ae50ef3)

- Line of Business by unit sold	

![image](https://github.com/user-attachments/assets/ea2461c4-c77f-4df4-ac7c-e39d764b589f)

- Top 10 stores by Revenue	
	
![image](https://github.com/user-attachments/assets/844e1361-e849-4103-9766-f686691e85e7)

- Top 5 Markets by Revenue

![image](https://github.com/user-attachments/assets/846c2a28-e3e1-41b2-80ac-ee8e33ea533f)

- Bottom 5 stores by unit sold

![image](https://github.com/user-attachments/assets/effeeecb-5398-4d42-b7bb-087e3ec89585)

- Region by Average Revenue `=Sheet1!A2:B10+Sheet1!D1:E10+Sheet1!R2:S10`  

![image](https://github.com/user-attachments/assets/057fa8f0-5f2e-4903-ac73-7a42a12c31e6)

- Line of Business by Average unit sold

![image](https://github.com/user-attachments/assets/6375b206-9081-4162-a640-c0be9bedea3e)

- Line of Business by Revenue		

![image](https://github.com/user-attachments/assets/035b0e7d-a10a-4a6c-a45b-da172718c6d2)

- Report of Revenue by month (2014 & 2015)

![image](https://github.com/user-attachments/assets/f0fd4769-c9ba-474a-a2b5-ba0d66c9c434)

#### CHARTS
- Summary for year 2014

![image](https://github.com/user-attachments/assets/28821610-7c45-4972-846e-c998e4ff771d)


![image](https://github.com/user-attachments/assets/8a207848-35c9-4681-aa6c-7ece80ca6a69)

- Summary for year 2015

![image](https://github.com/user-attachments/assets/c92a46d5-d86b-4bd4-9238-4c9a3fcc71be)

![image](https://github.com/user-attachments/assets/b82f5c84-c9cb-42a4-9848-6afbee1b211c)


### SQL (STRUCTURED QUERY LANGUAGE)


---

### **1. Database and Table Creation**
- **Database**: 
  - `CREATE DATABASE LITA_DB` initializes a database named `LITA_DB`.

- **Employee Table**: 
  - `CREATE TABLE Employee` creates a table with employee details like `staffid`, `firstname`, `secondname`, `gender`, etc.
  - Primary key: `staffid`.

- **Salary Table**: 
  - `CREATE TABLE Salary` stores salary details including `department` and `salary` with decimal precision.

- **Payment Table**: 
  - `CREATE TABLE Payment` manages payment details, including `payment_method` with constraints for accepted values.

---

### **2. Data Insertion**
- Multiple `INSERT INTO` statements populate the `Employee`, `Salary`, and `Payment` tables with sample data.

---

### **3. Basic Queries**
- Examples include:
  - **Selection**: `SELECT * FROM Employee` retrieves all employee records.
  - **Aggregation**: Functions like `SUM`, `AVG`, `MAX`, `MIN`, and `COUNT` are used for total salary, average salary, employee count, etc.

---

### **4. Table Modifications**
- **Updating data**:
  - `UPDATE Employee SET secondname = 'Endurance' WHERE staffid = 'AB405'`.
  - Increment salary by 5% using `SET salary = salary * 1.05`.

- **Adding columns**:
  - `ALTER TABLE Employee ADD State_of_Origin varchar(50)`.

---

### **5. Joins**
- **Inner Join**: Combines `Employee` and `Salary` based on matching `staffid`.
- **Outer Joins**: Includes records even if no match exists (e.g., `LEFT JOIN`, `RIGHT JOIN`, `FULL JOIN`).

---

### **6. Unions**
- Combines data from two tables (e.g., `LITA_Store_Lekki` and `LITA_Store_Marina`) while removing duplicates (`UNION`) or retaining duplicates (`UNION ALL`).

---

### **7. Views**
- **Simple Views**:
  - `CREATE VIEW vw_Employee_tbl` simplifies frequent queries by selecting specific columns.
- **Complex Views**:
  - `vw_lita_employee_info` combines data from `Employee`, `Salary`, and `Payment` tables using joins.

---

### **8. Conditional Logic with `CASE`**
- Dynamically assigns categories based on conditions:
  - Example: `CASE` categorizes employees as `Senior Executive`, `Manager`, etc., based on age.

---

### **9. Constraints and Integrity**
- Includes constraints like `CHECK` for valid `Payment_Method` values.
- Ensures data integrity through primary keys, default values, and controlled data types.

---

### **10. Advanced Queries**
- **Filters**:
  - Range (`BETWEEN`), inclusion (`IN`), and exclusion (`NOT IN`).
  - Logical conditions with `AND`/`OR`.
- **Sorting**:
  - Using `ORDER BY` for ascending/descending order.
- **Grouping**:
  - `GROUP BY` organizes data, often used with aggregate functions.

---

### **Summary**
This SQL script demonstrates the end-to-end lifecycle of database management:
- Database creation and initialization.
- Table and data handling with constraints.
- Aggregations, filters, and conditional logic for analysis.
- Efficient organization with views and joins.

Here is the information you provided, formatted as SQL queries: 

---

### **Create a Database**
```sql
CREATE DATABASE LITA_DB;
```

---

### **Create Employee Table**
```sql
CREATE TABLE Employee (
    staffid VARCHAR(10) NOT NULL,
    FirstName VARCHAR(255) NOT NULL,
    SecondName VARCHAR(255),
    Gender VARCHAR(10),
    Date_of_Birth DATE,
    HireDate DATETIME,
    PRIMARY KEY (staffid)
);
```

---

### **Select Query**
```sql
SELECT staffid, firstname FROM Employee;
```

---

### **Drop Table**
```sql
DROP TABLE Employee;
```

---

### **Delete Command**
```sql
DELETE FROM Employee
WHERE staffid = 'ab281';
```

---

### **Truncate Table**
```sql
TRUNCATE TABLE Employee;
```

---

### **Create Table with Identity Column**
```sql
CREATE TABLE PERSON (
    personid INT IDENTITY(1,1) PRIMARY KEY NOT NULL,
    personname VARCHAR(255) NOT NULL,
    age INT
);

INSERT INTO PERSON (personname, age)
VALUES 
('saidu', 45),
('adebanjo', 49),
('olorunda', 33),
('martha', 88),
('sandi', 100),
('jackson', 22),
('okunola', 19),
('esther', 45);

SELECT * FROM PERSON;
```

---

### **Insert Records into Employee Table**
```sql
INSERT INTO Employee (staffid, FirstName, SecondName, Gender, Date_of_Birth, HireDate)
VALUES
('AB200', 'ayomide', 'halleluyah', 'female', '1982-10-09', '2018-07-11'),
('AB405', 'deborah', 'justin', 'female', '1982-10-09', '2018-02-09'),
('AB282', 'wale', 'olanipekun', 'male', '1982-10-09', '2018-02-09'),
('AB278', 'shukurat', 'lasisi', 'female', '1982-10-09', '2018-02-09'),
('AB240', 'johnson', 'mercy', 'female', '1982-10-09', '2019-12-09'),
('AB299', 'ayomide', 'halleluyah', 'female', '1982-10-09', '2018-07-11'),
('AB268', 'deborah', 'justin', 'female', '1982-10-09', '2018-02-09'),
('AB286', 'wale', 'olanipekun', 'male', '1982-10-09', '2018-02-09'),
('AB270', 'shukurat', 'lasisi', 'female', '1982-10-09', '2018-02-09');

SELECT * FROM Employee;
```

---

### **Create Salary Table**
```sql
CREATE TABLE Salary (
    salary_id INT IDENTITY(1,1) NOT NULL,
    Staffid VARCHAR(255),
    firstname VARCHAR(255),
    lastname VARCHAR(255),
    department NVARCHAR(MAX),
    salary DECIMAL(10, 3) -- 10: Precision, 3: Scale
);
```

---

### **Insert Records into Salary Table**
```sql
INSERT INTO Salary (staffid, FirstName, lastname, Department, Salary)
VALUES
('AB401', 'ayan', 'olakun', 'Information Tech.', 45000.45),
('AB212', 'okorie', 'mercy', 'Account', 500000.99999),
('AB223', 'joshua', 'chukwuemeka', 'Human Resources', 100560.9339999),
('AB234', 'sanni', 'ibrahim', 'Sales and Marketing', 845688.99),
('AB254', 'mercy', 'olanipekun', 'Account', 8889.999999),
('AB249', 'johnson', 'mercy', 'Information Tech.', 234000.90909090),
('AB298', 'ayomide', 'halleluyah', 'Logistics', 678000.991999),
('AB260', 'deborah', 'justin', 'Logistics', 900099.00697969);

INSERT INTO Salary (staffid, firstname, lastname, department, salary)
VALUES
('AB200', 'ayomide', 'halleluyah', 'Human Resources', 45699.8585),
('AB405', 'deborah', 'justin', 'Account', 898349.900222),
('AB282', 'wale', 'olanipekun', 'Sales and Marketing', 362636.564848),
('AB278', 'shukurat', 'lasisi', 'Logistics', 100000.464647),
('AB240', 'johnson', 'mercy', 'Information Tech', 3855590.9890093),
('AB299', 'ayomide', 'halleluyah', 'Account', 8585858.9292),
('AB268', 'deborah', 'justin', 'Human Resources', 76767.93939),
('AB281', 'wale', 'olanipekun', 'Information Tech', 873093.2344);
```

---

### **Aggregate Functions**
```sql
SELECT SUM(Salary) AS TOTALSALARY FROM Salary;
SELECT AVG(Salary) AS AVERAGESALARY FROM Salary;
SELECT COUNT(Staffid) AS EmployeeCount FROM Employee;
SELECT COUNT(Staffid) AS NumberOfEmployee FROM Salary;
```

---

### **Update Operations**
1. **Update Salary**:
   ```sql
   UPDATE Salary
   SET salary = 7056999.9994
   WHERE Staffid = 'AB401';
   ```

2. **Update Employee Name**:
   ```sql
   UPDATE Employee
   SET secondname = 'Endurance'
   WHERE staffid = 'AB405';
   ```

3. **Update Department**:
   ```sql
   UPDATE Salary
   SET department = 'Information Tech.'
   WHERE Staffid IN ('AB234', 'AB240');
   ```

---

### **Add a Column**
```sql
ALTER TABLE Employee
ADD State_of_Origin VARCHAR(50);

UPDATE Employee
SET State_of_Origin = 'Ekiti'
WHERE staffid = 'AB268';
```

---
## Example
### **Create Payment Table**
```sql
CREATE TABLE Payment (
    paymentid INT IDENTITY(1,1) PRIMARY KEY,
    Account_No BIGINT NOT NULL,
    staffid VARCHAR(30),
    Bank VARCHAR(255) DEFAULT 'Zenith Bank',
    Payment_Method VARCHAR(50) CHECK (Payment_Method = 'Cash' OR Payment_Method = 'Transfer')
);
```

---

Let me know if you'd like to continue or format specific sections further.

