# Import Data using Transform Maps (Spreadsheet)

## Nan Mudhalvan – ServiceNow Project

### Project Title
Import Data using Transform Maps (Spreadsheet)

---

## 📌 Project Overview

This project demonstrates how data from a spreadsheet can be imported into ServiceNow using Import Sets and Transform Maps.

The spreadsheet data is loaded into an Import Set Table. A Transform Map is then used to map the source fields to the corresponding fields in the target ServiceNow table.

After transformation, the records are validated in the target table.

---

## 🎯 Objectives

- To understand data importing in ServiceNow.
- To create an Import Set.
- To create an Import Set Table.
- To create a target ServiceNow table.
- To create and configure a Transform Map.
- To map source fields to target fields.
- To transform spreadsheet data into ServiceNow records.
- To validate imported records.
- To understand ServiceNow data migration.

---

## 🛠️ Technologies and Features

| Feature | Purpose |
|---|---|
| ServiceNow | Main platform |
| Import Sets | Import spreadsheet data |
| Import Set Table | Temporarily store imported data |
| Transform Maps | Map and transform data |
| Field Mapping | Connect source and target fields |
| ServiceNow Tables | Store final records |
| Reports | Analyze imported data |
| Dashboards | Display information |

---

## 📋 Project Details

| Item | Details |
|---|---|
| Program | Nan Mudhalvan |
| Project Title | Import Data using Transform Maps (Spreadsheet) |
| Platform | ServiceNow |
| Data Source | Spreadsheet |
| Target | ServiceNow Table |
| Main Features | Import Sets and Transform Maps |
| Data Type | Employee Data |

---

## 🔄 Project Workflow

Spreadsheet

↓

Import Set

↓

Import Set Table

↓

Transform Map

↓

Field Mapping

↓

Data Transformation

↓

Target ServiceNow Table

↓

Data Validation

---

## 📊 Source Spreadsheet

The spreadsheet is used as the external data source.

Example fields:

- Employee ID
- Employee Name
- Department
- Email
- Location
- Job Role

---

## 🗃️ Target Table

The target ServiceNow table stores the transformed records.

Example fields:

| Field | Description |
|---|---|
| Employee ID | Unique employee identification |
| Employee Name | Name of employee |
| Department | Employee department |
| Email | Employee email |
| Location | Employee work location |
| Job Role | Employee role |

---

## 📥 Import Set

The Import Set is used to bring spreadsheet data into ServiceNow.

The imported data is initially stored in an Import Set Table before transformation.

---

## 🗂️ Import Set Table

The Import Set Table acts as a temporary staging table.

The spreadsheet data is loaded into this table before the transformation process.

---

## 🔄 Transform Map

A Transform Map connects the Import Set Table with the target table.

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

## ⚙️ Data Transformation

During transformation:

1. ServiceNow reads the imported records.
2. The Transform Map checks the field mappings.
3. Source values are transferred to target fields.
4. The transformation is executed.
5. Records are created or updated in the target table.
6. The resulting records are verified.

---

## ✅ Data Validation

The following items are checked:

- Records are imported successfully.
- Field values are correct.
- Source and target mappings are correct.
- Employee information is displayed correctly.
- Transformed records are available in the target table.

---

## 📊 Reports and Dashboards

The imported data can be used to create reports such as:

- Employees by Department
- Employees by Location
- Employee Count
- Employees by Job Role

A dashboard can display multiple reports in one interface.

---

## 🏗️ Project Architecture

Spreadsheet

↓

Import Set

↓

Import Set Table

↓

Transform Map

↓

Field Mapping

↓

Data Transformation

↓

Target ServiceNow Table

↓

Reports / Dashboard

---

## 🧪 Testing

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

Expected Result: Records should be created or updated in the target table.

Result: Verified after transformation.

### Test Case 4 – Data Validation

Input: Transformed records

Expected Result: Target records should contain the correct values.

Result: Verified in the target table.

---

## 🌟 Advantages

- Reduces manual data entry.
- Makes bulk data import easier.
- Saves time during data migration.
- Provides structured field mapping.
- Makes data validation easier.
- Supports reporting.
- Supports dashboard creation.
- Provides practical ServiceNow experience.

---

## 💡 Applications

This process can be used for:

- Employee data migration
- User information migration
- Department data migration
- Asset information migration
- Customer data migration
- Bulk record creation
- Spreadsheet-to-ServiceNow migration

---

## 🧠 Skills Learned

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

## 📸 Project Screenshots

The following screenshots can be added to the `screenshots` folder:

1. Spreadsheet
2. Import Set
3. Import Set Table
4. Transform Map
5. Field Mapping
6. Transform Result
7. Target Table
8. Imported Records
9. Reports
10. Dashboard

Only screenshots of completed features should be included.

---

## 📁 Project Structure

Import-Data-using-Transform-Maps-Spreadsheet/

├── README.md

├── ServiceNow_Project.xml

└── screenshots/

    ├── spreadsheet.png

    ├── import_set.png

    ├── import_set_table.png

    ├── transform_map.png

    ├── field_mapping.png

    ├── transform_result.png

    ├── target_table.png

    ├── imported_records.png

    ├── reports.png

    └── dashboard.png

---

## 🏆 Project Outcome

The project demonstrates the process of importing spreadsheet data into ServiceNow using Import Sets and Transform Maps.

The data is imported, mapped, transformed, stored in the target table, and validated.

---

## 🎓 Nan Mudhalvan Project

Program: Nan Mudhalvan

Project Title: Import Data using Transform Maps (Spreadsheet)

Platform: ServiceNow

Project Type: Data Import and Transformation

---

## 📌 Conclusion

The Import Data using Transform Maps (Spreadsheet) project demonstrates how external spreadsheet data can be imported and transformed in ServiceNow.

Using Import Sets and Transform Maps, the project provides a structured process for loading source data, mapping fields, transforming records, and validating the final information in the target table.

This project provides practical experience in ServiceNow data import, transformation, field mapping, data validation, and reporting.
