# Daily Seating Reassignment Script

## Introduction

The company has recently moved to a new office at the Gent Zuiderport. The office is an open space with 6 tables, each with 4 seats. As many colleagues are new, the idea was born to change seats every day, helping everyone get to know each other better by working side by side.

This script automates the daily seating reassignment process to ensure that every colleague sits with different people every day.

## Features

- Reads the list of colleagues' names from an Excel file (`output-list.xlsx`).
- Shuffles the list randomly to create new seating arrangements every day.
- Assigns each colleague to a table (there are 6 tables in total).
- Selects a random "leader" for each table, with the leader displayed alongside their group.
- Prints the updated seating arrangement with leaders for each table.

## Requirements

- Python 3.x
- `pandas` library
- `numpy` library
- `openpyxl` library (for reading Excel files)

## Installation

To get started with this script, follow these steps:

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/daily-seating-reassignment.git
