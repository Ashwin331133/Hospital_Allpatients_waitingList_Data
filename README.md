# Hospital_Allpatients_waitingList_Data
# Dataset Description

This dataset contains information about patient waiting lists for different types of cases (Day Case, Inpatient, Outpatient) across various specialties. The columns included in this dataset are:

## Columns

1. **Archive_Date**
   - **Type**: Date
   - **Description**: The date when the patient visited hospital.

2. **Specialty_HIPE**
   - **Type**: String
   - **Description**: A code that uniquely identifies the medical specialty.

3. **Specialty_Name**
   - **Type**: String
   - **Description**: The full name of the medical specialty.

4. **Case_Type**
   - **Type**: String
   - **Description**: Specifies the type of medical case. It includes the following categories:
     - **Day Case**: Patients who are admitted for treatment but do not require an overnight stay.
     - **Inpatient**: Patients who are admitted and stay in the hospital overnight or longer.
     - **Outpatient**: Patients who visit the hospital for treatment but are not admitted.

5. **Adult_Child**
   - **Type**: String
   - **Description**: Indicates whether the patient is an adult or a child.

6. **Age_Profile**
   - **Type**: String
   - **Description**: The age group of the patients. Typical values might include:
     - 0-15
     - 16-64
     - 65+

7. **Time_Bands**
   - **Type**: String
   - **Description**: Represents the length of time patients have been on the waiting list. The values include:
     - 0-3 Months
     - 3-6 Months
     - 6-9 Months
     - 9-12 Months
     - 12-15 Months
     - 15-18 Months
     - 18+ Months

8. **Total**
   - **Type**: Integer
   - **Description**: The total number of patients on the waiting list within the specified category.

## Usage

This dataset can be used to analyze and visualize waiting times and the distribution of patients across different specialties and case types. It is particularly useful for healthcare management to understand patient load and manage resources efficiently.
