# Import Data using Transform Maps (Spreadsheet)

## Nan Mudhalvan – ServiceNow Project

### Project Title
Import Data using Transform Maps (Spreadsheet)

---
## 1. Project Overview

This project demonstrates how data from a spreadsheet can be imported into ServiceNow using Import Sets and Transform Maps.

The spreadsheet data is first loaded into an Import Set Table. A Transform Map is then used to map the source fields to the corresponding fields in the target ServiceNow table.

After the transformation process, the imported records are checked and validated in the target table.

---

## 2. Objective

The main objectives of this project are:

- To understand data importing in ServiceNow.
- To create an Import Set.
- To create an Import Set Table.
- To create a target ServiceNow table.
- To create and configure a Transform Map.
- To map source fields to target fields.
- To transform spreadsheet data into ServiceNow records.
- To validate the imported records.
- To understand basic ServiceNow data migration.

---

## 3. Project Details

| Item | Details |
|---|---|
| Project Type | ServiceNow Data Import Project |
| Platform | ServiceNow |
| Project Title | Import Data using Transform Maps (Spreadsheet) |
| Program | Nan Mudhalvan |
| Data Source | Spreadsheet |
| Main Features | Import Sets and Transform Maps |
| Target | ServiceNow Table |
| Data Type | Employee Data |

---

## 4. Technologies and Features Used

### ServiceNow

ServiceNow is the main platform used for this project.

### Import Sets

Import Sets are used to import data from an external source such as a spreadsheet into ServiceNow.

### Import Set Table

The Import Set Table temporarily stores the imported source data before the transformation process.

### Transform Maps

Transform Maps define how the fields from the imported data are mapped to the fields in the target ServiceNow table.

### ServiceNow Tables

The target table stores the transformed records.

### Reports

Reports can be used to display and analyze the imported records.

### Dashboards

Dashboards can be used to display multiple reports in one place.

---

## 5. Project Workflow

The overall workflow of the project is:

Spreadsheet
     |
     v
Import Set
     |
     v
Import Set Table
     |
     v
Transform Map
     |
     v
Field Mapping
     |
     v
Data Transformation
     |
     v
Target ServiceNow Table
     |
     v
Data Validation

---

## 6. Spreadsheet Data

A spreadsheet is used as the source of the project data.

The spreadsheet contains structured employee information.

Example fields include:

- Employee ID
- Employee Name
- Department
- Email
- Location
- Job Role

The spreadsheet provides the external data that is imported into ServiceNow.

---

## 7. Target Table

A target table is created in ServiceNow to store the transformed employee records.

Example fields include:

| Field | Description |
|---|---|
| Employee ID | Unique employee identification |
| Employee Name | Name of the employee |
| Department | Employee department |
| Email | Employee email address |
| Location | Employee work location |
| Job Role | Employee role |

---

## 8. Import Set

An Import Set is used to bring the spreadsheet data into ServiceNow.

The imported data is initially stored in an Import Set Table.

The Import Set provides a controlled process for loading external data before it is transformed into the target table.

---

## 9. Import Set Table

The Import Set Table acts as a temporary staging table.

The spreadsheet data is loaded into this table before the transformation process.

The source spreadsheet fields are represented in the Import Set Table.

---

## 10. Transform Map

A Transform Map is created between the Import Set Table and the target table.

The Transform Map determines how source fields are transferred to the corresponding target fields.

Example field mapping:

| Source Field | Target Field |
|---|---|
| Employee ID | Employee ID |
| Employee Name | Employee Name |
| Department | Department |
| Email | Email |
| Location | Location |
| Job Role | Job Role |

---

## 11. Data Transformation

After configuring the Transform Map, the imported data is transformed.

During transformation:

1. ServiceNow reads the imported source records.
2. The Transform Map checks the field mappings.
3. Source values are transferred to the corresponding target fields.
4. Records are created or updated in the target table according to the configured transformation settings.

---

## 12. Data Validation

After transformation, the target table is checked to verify the imported records.

The following points are validated:

- Records are imported successfully.
- Field values are correct.
- Source and target fields are mapped correctly.
- Employee information is displayed correctly.
- The transformed records are available in the target table.

---

## 13. Reports and Dashboards

The imported employee data can be used to create reports.

Possible reports include:

- Employees by Department
- Employees by Location
- Employee Count
- Employees by Job Role

A dashboard can be used to display multiple reports together.

---

## 14. Project Architecture

External Spreadsheet
        |
        v
    Import Set
        |
        v
 Import Set Table
        |
        v
  Transform Map
        |
        v
  Field Mapping
        |
        v
Data Transformation
        |
        v
Target ServiceNow Table
        |
        v
 Reports / Dashboard

---

## 15. Implementation Steps

The project is implemented using the following steps:

1. Prepare the spreadsheet.
2. Create the target ServiceNow table.
3. Create or configure the Import Set.
4. Import the spreadsheet data.
5. Verify the Import Set Table.
6. Create the Transform Map.
7. Configure source and target field mappings.
8. Run the transformation.
9. Check the transformed records.
10. Validate the target table.
11. Create reports if required.
12. Create a dashboard if required.
13. Verify the final project result.

---

## 16. Testing

The project is tested at different stages.

### Test Case 1 – Spreadsheet Import

Input: Employee spreadsheet

Expected Result: Data should be loaded into the Import Set Table.

Result: Verified after import.

### Test Case 2 – Transform Map

Input: Imported records

Expected Result: Source fields should map correctly to target fields.

Result: Verified after field mapping.

### Test Case 3 – Data Transformation

Input: Import Set records

Expected Result: Records should be created or updated in the target table according to the configured Transform Map.

Result: Verified after transformation.

### Test Case 4 – Data Validation

Input: Transformed records

Expected Result: Target records should contain the correct values.

Result: Verified in the target table.

---

## 17. Advantages

- Reduces manual data entry.
- Makes bulk data import easier.
- Saves time during data migration.
- Provides structured data mapping.
- Reduces manual data entry errors.
- Allows source and target fields to be mapped.
- Makes imported data easier to validate.
- Supports reporting and dashboard creation.

---

## 18. Applications

The Import Set and Transform Map process can be used for:

- Employee data migration.
- Customer data migration.
- Department information migration.
- Asset information migration.
- User information migration.
- Bulk record creation.
- Spreadsheet-to-ServiceNow data migration.

---

## 19. Project Outcome

The project demonstrates the process of importing spreadsheet data into ServiceNow using Import Sets and Transform Maps.

The data is loaded into an Import Set Table, mapped using a Transform Map, transformed into the target table, and validated.

The project provides practical experience with ServiceNow data import and transformation features.

---

## 20. Skills Learned

Through this project, the following skills were practiced:

- ServiceNow navigation
- Import Sets
- Import Set Tables
- Transform Maps
- Field Mapping
- Data Transformation
- Data Validation
- ServiceNow Tables
- Reports
- Dashboards
- Basic data migration concepts

---

## 21. Project Screenshots

Screenshots of the project implementation can be stored in the screenshots folder.

Recommended screenshots include:

1. Spreadsheet data
2. Import Set
3. Import Set Table
4. Transform Map
5. Field Mapping
6. Transform Result
7. Target Table
8. Imported Records
9. Reports
10. Dashboard

Only screenshots of the features actually completed in the ServiceNow project should be included.

---

## 22. Project Files

The GitHub repository can contain the following files:

Import-Data-using-Transform-Maps-Spreadsheet/
|
|-- README.md
|
|-- ServiceNow_Project.xml
|
|-- screenshots/
    |-- spreadsheet.png
    |-- import_set.png
    |-- import_set_table.png
    |-- transform_map.png
    |-- field_mapping.png
    |-- transform_result.png
    |-- target_table.png
    |-- imported_records.png
    |-- reports.png
    |-- dashboard.png

---

## 23. Conclusion

The Import Data using Transform Maps (Spreadsheet) project demonstrates how external spreadsheet data can be imported and transformed in ServiceNow.

Using Import Sets and Transform Maps, the project provides a structured process for loading source data, mapping fields, transforming records, and validating the final information in the target table.

This project provides practical experience in ServiceNow data import, transformation, field mapping, data validation, and reporting.

---

## Nan Mudhalvan Project

Program: Nan Mudhalvan

Project Title: Import Data using Transform Maps (Spreadsheet)

Platform: ServiceNow

Project Type: Data Import and Transformation
