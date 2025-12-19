# ChildPlus to ASQ Data Pipeline

This repository contains a Python-based data pipeline to prepare child-level data from **ChildPlus** and **ASQ** for import into the **ASQ system**.

Technology:
Python(pandas),
Database Management

## Overview

ASQ requires child data to be uploaded using a specific import template.  
To generate this template, the pipeline:

- Extracts required default reports from **ChildPlus** and **ASQ**
- Cleans and standardizes fields across multiple source reports
- Merges data into a single, ASQ-compatible import file
- Ensures data consistency and integrity throughout the process

## Input Data

The pipeline expects a defined set of default reports exported from:
- ChildPlus
- ASQ

> ⚠️ Raw data files are excluded from this repository to protect sensitive information.

## Output

- A single, validated file formatted according to the ASQ child data import template
- Ready for direct upload into ASQ

## Notes

- The pipeline enforces consistent formatting, required fields, and key validations
- All transformation logic is implemented in Python and documented in the script


