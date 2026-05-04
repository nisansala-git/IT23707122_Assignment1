# Assignment 1 – Transliteration Accuracy Testing

## Student Details

* Name: N.M. Ariyathilake
* Registration Number: IT23707122

---

## Project Description

This project evaluates the accuracy of the Chat Sinhala Transliteration system available at:
https://www.pixelssuite.com/chat-translator

The system is tested using 50 negative test cases where the transliteration fails to correctly convert Singlish input into Sinhala output.

---

## Technologies Used

* Python 3
* Playwright
* OpenPyXL

---

## Setup Instructions

### 1. Install Python

Ensure Python 3.11 or above is installed.

### 2. Install dependencies

Run the following commands in the terminal:

pip install playwright openpyxl
playwright install

---

## How to Run the Automation Script

Use the following command:

python3 IT23707122.py --excel "IT23707122.xlsx" --url "https://www.pixelssuite.com/chat-translator"

---

## Project Structure

* IT23707122.xlsx → Contains test cases and results
* IT23707122.py → Automation script
* README.md → Project instructions
* IT23707122_GitLink.txt → Git repository link

---

## Notes

* The automation script automatically fills the “Actual Output” and “Status” columns in the Excel file.
* The “Singlish Input Types Covered” and “Evidence or Rationale” columns are completed manually.
* All test cases included are negative scenarios as required by the assignment.

---
