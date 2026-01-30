# User-Data-Validation-Text-Analysis-System---Using-Python
This project is a text processing module designed for an online application. It receives raw string inputs from users, cleans and validates the data, and generates a structured summary report.  The system ensures that user information such as name, email, and age is properly formatted, validated, and analyzed before storage.

# Tasks Implemented

1. Data Cleaning:

   Remove extra spaces
   
   Split into name, email, age

   Convert name to Title Case

   Convert email to lowercase


2. Email Validation

   Must contain exactly one '@'

   Must contain at least one '.' after '@'

   Should not start or end with '@'

3. Age Validation

   Convert age to integer

   Check eligibility (>= 18 years)

4. Invalid Record Identification

   Missing name

   Invalid email

   Invalid age

5. Summary Report

   Total records

   Valid users

   Invalid users

   Eligible users

   Underage users

# Constraints
Use only string methods

No regex or external libraries

# Bonus Task
Extract email domains

Count users per domain
6. Output Formatting
