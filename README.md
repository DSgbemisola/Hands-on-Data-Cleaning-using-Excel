# Hands on Project on Data Cleaning using Excel

In this project, we delved into data cleaning using Excel.

# Software used in this project

For the hands-on project, we used the free ‘Excel for the web’ version.

# Objectives

The Objectives of this lab are to:

1. Understand how to deal with irrelevant or inaccurate data
2. Remove empty rows and duplicated data
3. Change text case and date formatting
4. Trim whitespaces from data
5. Use Flash Fill and functions to clean data

# Removing Duplicated, Irrelevant or Inaccurate Data

- To remove duplicated, irrelevant and inaccurate Data from our data, the following steps were taken:
  
# Task A: Check spellings

1. Download the file Customer_demographics_and_sales_Lab5.xlsx. Upload and open it using Excel for the web.
   Dataset is available here: https://docs.google.com/spreadsheets/d/1mldaj5VH0treTqeoyTi-YToUiXQ7orNM/edit?usp=sharing&ouid=101032132621933397345&rtpof=true&sd=true
3. Select column L (CREDITCARD_TYPE), then click Review tab, and select Spelling.
4. Click the correct suggestion to change the spelling.

Note: Don’t change ‘jcb’ spelling when doing the spell check. We will need ‘jcb’ for the Exercise 1 Task D.

5. Close the Spelling pane.

![image](https://github.com/user-attachments/assets/5b4fc377-bf27-4179-a4b5-d1965e4b525c)

# Task B: Remove empty rows

1. Press CTRL+HOME, then press CTRL+SHIFT+END to select the whole datasheet.
2. On the Data tab, click Filter.
3. Press CTRL+HOME, click the filter arrow in the CUST_NAME column, and then click Filter.
4. Click the Select All checkbox to deselect all of them. Then select just Blanks, then OK.
5. Select first row, then press CTRL+SHIFT+END to select all rows.
5. Right-click the selected rows and then click Delete Rows.
7. Finally, on the Data tab, click Clear, then click Filter.

![image](https://github.com/user-attachments/assets/00a8251e-abba-44b0-bb34-0d46448b4a4f)

# Task C: Remove duplicate rows

1. Select Column T (ORDER_ID) since ORDER_ID values are unique.
2. On the Home tab, click Conditional Formatting> Highlight Cells Rules> Duplicate Values, and then click OK.
3. Select the whole datasheet (CTRL+SHIFT+END)
4. On the Data tab, click Remove Duplicates.
5. In the Remove Duplicates dialog box, ensure that Select all columns is checked and that My data has headers is also checked, then click OK.
6. In the pop-up box informing you how many duplicate values were found and removed, click OK.

![image](https://github.com/user-attachments/assets/783027dd-bd69-4f00-a387-fe8ea29dfbe4)

# Task D: Use Find & Replace to correct misspelling

1. On the Home tab, click Find & Select.
2. Click Find. In Find what, type jcb, and click Find All.
3. Click Replace.
3. In Replace with, type JCB, click Replace All, and then click the Close icon.
4. On the Home tab, click Conditional Formatting> Clear Rules> Clear Rules from Entire Sheet.

![image](https://github.com/user-attachments/assets/de573122-223d-4801-ad7b-5be977abd810)






