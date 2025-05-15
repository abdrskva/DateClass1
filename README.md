# Date Class Project in Java


## Done by
Salima Abdyrasakova
## Group 
COMCEH-23


## Overview
This project implements a custom `Date` class in Java that supports various date-related operations. The goal is to manage date validation, manipulation, comparison, and formatting without using Java's built-in `LocalDate` directly for core logic, to practice custom class design and algorithms.

## Features
- Validate dates including leap year checks.
- Update existing date objects with validation.
- Print dates in a human-readable format.
- Calculate the day of the week for any valid date.
- Compute the difference in days between two `Date` objects.
- Sort a list of `Date` objects using the `Comparable` interface.

## Class Breakdown

### `Date`
A class with the following fields and methods:
- Fields: `int day`, `int month`, `int year`
- `isValidDate()`: checks if the date is correct considering leap years
- `updateDate(int d, int m, int y)`: updates the object if the new date is valid
- `getDayOfWeek()`: returns the weekday of the date
- `calculateDifference(Date otherDate)`: returns number of days between this date and the other
- `printDate()`: prints the date in "Month day, year" format
- Implements `Comparable<Date>` for sorting

### `Main`
A test class to demonstrate:
- Creating valid and invalid dates
- Updating date values
- Displaying weekday names
- Calculating differences
- Sorting date list using `Collections.sort()`
- Handling exceptions

## How to Run

1. Clone the repository or download the files
2. Open the project in IntelliJ IDEA or another IDE
3. Run `Main.java`
4. Output will be printed to the console

## Example Output

May 15, 2025
Day of Week: THURSDAY
Difference: 1961 days
February 29, 2024
Sorted Dates:
January 1, 2020
June 5, 2023
February 29, 2024

## Notes
- Invalid dates are handled with exceptions and printed with messages.
- Leap years are considered for February 29.
- Sorting uses `compareTo()` logic based on year, month, and day.

## Repository Structure

DateClass/
├── src/
│ ├── Date.java
│ └── Main.java
├── .gitignore
└── README.md

<img width="1220" alt="Снимок экрана 2025-05-15 в 17 13 40" src="https://github.com/user-attachments/assets/0bd50fb4-6fec-48a6-b32f-711a6fcea1d0" />

