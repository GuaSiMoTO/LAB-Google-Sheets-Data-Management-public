# LAB-Google-Sheets-Data-Management
![](https://user-images.githubusercontent.com/970858/63474771-d6734700-c469-11e9-83bb-9429da563909.png)

## Introduction

> ***Note:*** _This can be a pair programming activity or done independently._

This lab will guide you through a practical case study to understand and apply fundamental concepts of Google Sheets, including spreadsheet navigation, data entry, formatting, and basic formulas. You will manage data for a small team in an imaginary company.

## Initial Setup

#### Fork The Repository And Download The Spreadsheet
1. Go to GitHub and click the `fork button` to create a copy of this repository in your personal account.
2. Download `Data_Management_LAB.xlsx` file.
3. Access your `Google Drive` account and upload the `Data_Management_LAB.xlsx` file.
4. Open the file in Google Sheets and complete the iterations below.

#### Iteration 1: Data Validation

You will see that the first worksheet contains information about the company's projects for 2024, but the cells currently lack data validation. In this iteration, you will create a table to organize project data and ensure it is correctly formatted.

![image](https://github.com/rebootacademy-labs/LAB-Data-Management/assets/114155101/1cbbfae8-dde9-4d05-9d52-a596e9a3fc90)


1. Add data validation:
   - ID: Whole number
   - Project Name: Text length
   - Manager: Text length
   - Budget: Number
   - Start Date: Date
   - End Date: Date
   - Status: List
2. Don't forget to display the Budget field in € and ensure that the cents are visible.
3. Now check that invalid data are not allowed in each column.
--- 

#### Iteration 2: Data Visualization

As you can see, there are two additional worksheets: Staff - Contact Info and Staff - Attendance Tracker. In this iteration, we will learn to manage and structure data to facilitate its visualization using the techniques covered in class.

1. The most basic way to improve data visualization is through styling. Apply basic styling to the worksheet.
2. Reference the Email and Phone Number fields from Staff - Contact Info in Staff - Attendance Tracker.
3. Sort the workers by department, and within each department, sort the workers alphabetically.
4. Group the data by months. Verify that the information expands when clicking on the + and collapses when clicking on the -.
5. Group the Email and Phone Number columns to quickly consult them only when necessary. Verify that the information expands when clicking on the + and collapses when clicking on the -.
6. Freeze the first row to keep it visible while scrolling horizontally.
7. Hide the months from January to August.
8. Apply filtering to the entire table to display attendance based on departments.

---

## Iteration 3: Sharing Workbook

To submit this LAB:

1. Share the workbook with your instructor.
2. Upload the file to our forked repository.
3. Don't forget to add the `share link` in your pull request!

-  Share link: <your link>
---

## Bonus 1

Enhance the styling of your attendance tracker table by implementing data validation and conditional formatting. 

1. Try to convert the attendance cells into a dropdown list with four possible values: OK, Late, MISS-Excused, and MISS-Unexcused.
2. Then, apply conditional formatting to change the cell color based on the selected value.

---

## Bonus 2

Although the Staff - Attendance Tracker worksheet allows us to record employee attendance, it is not very effective for tracking or quickly identifying repeated absences. By enhancing the worksheet with advanced styling and creating an additional summary sheet, we can improve its functionality and make it easier to spot patterns and issues.

1. Create a new worksheet and set up it to calculate the totals using formulas.
2. Apply conditional formatting to highlight if:
   -  2 or more unexcused absences are detected.
   -  3 or more late entries are detected.

---

