# Automating Data Import and Relationship Mapping Using ServiceNow

## Project Overview

This project demonstrates how to automate employee data import into ServiceNow using Import Sets and Transform Maps, and how to use Dot Walking to access related data efficiently.

---

## Tools & Technologies

* ServiceNow
* Google Sheets
* CSV/XLSX Data Files

---

## Implementation Steps

### 1. Data Preparation

* Created employee dataset with:

  * Name
  * Email
  * Department
  * Manager
  * Phone Number

### 2. Import Set Creation

* Loaded data into ServiceNow
* Created staging table: `import_employee`

### 3. Transform Map

* Mapped:

  * Source: `import_employee`
  * Target: `sys_user`
* Used Auto Map & Mapping Assist

### 4. Data Transformation

* Executed transform
* Verified records in `sys_user`

### 5. Dot Walking Implementation

* Used fields:

  * Assigned to.department
  * Assigned to.email
  * Assigned to.manager

---

## Results

* Automated data import process
* Reduced manual errors
* Improved data accessibility using dot walking

---

## Project Abstract

 [Download Abstract](./Naan_Mudhalvan_Abstract.pdf)

---

## Author

* Saran.V
