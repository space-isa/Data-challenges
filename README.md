# Data-challenges
Working through problems on Kaggle.

---
## Table of Contents 
1. [About](#about) 
2. [Getting Started](#getting-started)
3. [Requirements](#requirements)
4. [How to use?](#how-to-use) 
6. [Tests](#tests)
9. [Author](#author)

---

## About 

This repo will house some of the data challenges I've worked through using datasets found on the site kaggle.com. As an asipring data engineer, my primary focus is on data loading, extraction, cleaning, and transformation (usually according to the "tasks" that accompanied the datasets, and sometimes using multiple external datasets). While there are more powerful tools (e.g., Pandas) that would be better suited to solving data challenges on the job, these challenges will be implemented using only Python standard libraries.

When working as part of any team, it's important for each person to have at least some understanding of the big picture--the same is true for data engineers working as part of a larger data team, which would include data scientists and anylists. To this end, cleaned and transformed datasets will be used to create dashboards using Tableau Public.     

## Getting Started

### Basic project structure:
```
   project/
      |
      |- docs/
      |   |_ README.txt
      |
      |- src/
      |   |- input/
      |   |    |_ input.csv
      |   |- output/
      |   |    |_ output.csv
      |   |_ code/
      |   |    |- project.py
      |   |    |_ run.sh
      |
      |- tests/
      |   |- test_input.csv
      |   |_ test_project.py
      |  
      |_ run.sh
 ```     

### Where to view data visualizations
ADD LINKS

## Requirements
This code was developed and tested using Python 3.8.6.

No additional installations are required, as this project uses only standard Python libraries. 

---

## How to use? 

Each project contains a shell script `run.sh` containing the following commands (a generalized example): 

   ```shell
   chmod +x ./src/project.py
   python3.8 ./src/project.py input.csv output.csv
   ```
In your terminal, change to the `project` directory and run the shell script: 

   ```shell
   $ bash run.sh
   ```
--- 

## Tests 

### Unit testing 
Tests were conducted using Python's built-in `unittest` module. Tests are found in the `test/` subdirectory for each project.

To run tests:
   1. In your terminal, change directories from `project` to the input directory in the test suite of interest. For example, if you wanted to run the test script `test_project.py`: 
      ```shell
      $ cd /path/to/tests/
      ```
   2. In your terminal run, 
      ```shell
      $ python3.8 -m test_project
      ```
   3. A an example output of a successful run for this script: 
      ```bash
      -------------------------------------------------
      Ran 5 tests in 0.003s
      OK
      ```

## Author 
Isabel J. Rodriguez 
