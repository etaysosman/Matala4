# University Admission Calculator

A web-based form that helps determine eligibility for university admission based on age and academic credentials.

# Live Page

URL: https://etaysosman.github.io/Matala4/

## Overview

This application calculates admission eligibility for Israeli universities based on different combinations of academic achievements including Bagrut (matriculation) scores, Psychometric exam scores, and Mechina (preparatory program) grades.

## Features

- **Age-based eligibility**: Applicants over 30 are automatically eligible for admission to any faculty
- **Dual pathway options**:
  - Bagrut + Psychometric scores
  - Bagrut + Mechina grades
- **Dynamic form validation**: Fields enable/disable based on selected pathway
- **Real-time feedback**: Visual confirmation of admission eligibility

## Files

- `index.html` - Main HTML structure and form layout
- `scripts.js` - JavaScript functionality for form validation and interaction
- `form.css` - Styling for the application

## How to Use

1. Open `index.html` in a web browser
2. Enter your age
3. Select one of the two options:
   - **Bagrut and Psychometric**: Enter both Bagrut and Psychometric grades
   - **Bagrut and Mechina**: Enter both Bagrut and Mechina grades
4. Click the "Validate" button to check eligibility

## Validation Rules

- Bagrut grade is required for all applicants
- Applicants must choose either the Psychometric or Mechina pathway
- Applicants over 30 years old are automatically eligible for any faculty
