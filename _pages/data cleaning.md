---
permalink: /data cleaning/
title: "Data Cleaning for Customer Call List"
---

## Project: Data Cleaning for Customer Call List  
**Goal**: Clean Excel data for analysis.  
**Techniques**: Python Pandas and Numpy Libraries.  
**Results**: A new short database with updated information.

**Duplicate Removal**:  
Before cleaning, I imported the necessary libraries and deleted duplicates and columns that weren't necessary for data analysis.

**Standardization**:  
After dropping any duplicates and/or columns, I standardize the last name, phone numbers, and address formats to maintain consistency across the data set. For the last name, they were stripped to remove any characters that weren't alphabetical. For the phone numbers, the format was changed to just be 10 digits long, removing any characters that weren't necessary, and then formatted to include a dash line where appropriate. For the address, their format was changed to split the original address column into two columns based on the delimiter. I also changed the format of columns, Paying Customer and Do_Not_Contact, from their original strings to simple characters.

**Replacing Null Values**:  
Any null values that were present no the data set were replaced with blank space characters.

**Outcome**:  
Lastly, I dropped any more columns or rows where appropriate. The results were a shorter dataset with an updated customer call list.


[View Code](Data Cleaning.md)


[Return to Python Projects](/python projects/)
