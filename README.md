# Student Data Preview Tool

A lightweight Python script using **pandas** to interactively load an Excel dataset (`Cleaned_Student_Data.xlsx` or `Raw_Student_Data.xlsx`) and display the first `n` rows in the console.

## Overview

This script provides a quick command-line / notebook prompt to inspect student records—such as `Student ID`, `Student Name`, `Age`, `Department`, `Attendance (%)`, `Exam Marks`, `City`, and `Gender`—before running deeper analysis or visualizations.

## Prerequisites

Make sure you have Python installed along with the following dependencies:

- [pandas](https://pandas.pydata.org/)
- [openpyxl](https://openpyxl.pydata.org/) (required by pandas for reading `.xlsx` files)

Install them via `pip`:

```bash
pip install pandas openpyxl
