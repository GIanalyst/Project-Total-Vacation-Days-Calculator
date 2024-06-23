# Total-Vacation-Days-Calculator

This Oracle PL/SQL script calculates and displays total vacation days for employees based on their category, years of experience, parental status, and special conditions. This tool provides a flexible way to determine vacation entitlements tailored to various roles and circumstances within an organization.

Features
Flexible Input Handling: Supports a wide range of employee categories, from agricultural workers to specialized professionals and military veterans.
Accurate Vacation Calculation: Utilizes predefined rules to compute vacation days based on main entitlements, years of experience, and parental responsibilities.
Error Handling: Ensures data integrity by validating inputs against predefined categories and conditions. Errors are raised for invalid inputs, guiding users to correct their input parameters.
Comprehensive Output: Provides detailed output including main vacation days, additional vacation days based on experience, parenting circumstances, and total vacation days, formatted for easy readability.

Usage
Input Parameters:

Employee Category: Select from a list of predefined categories that best match the employee's role.
Experience Years: Enter the number of years the employee has been with the organization.
Kids Age: If applicable, specify the age of the employee's children.
Kids Count: Indicate the number of children the employee has.
Special Conditions: Choose any relevant special conditions such as being a single parent or having disabled children.
Execution:

Run the provided SQL queries to call the total_vacation_days function with appropriate input values.
Receive a formatted output detailing the employee category, main vacation days, additional vacation days due to experience and parenting, and the total vacation days.
