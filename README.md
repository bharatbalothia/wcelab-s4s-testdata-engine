# S4S Test Data Generator

Test data generator for Sterling 4 Scarce Supply System

This test data generation uses [LEGO inventory data](https://rebrickable.com/downloads/) to create a realistic inventory test data set.

- It maps original data's part number to test data's part number
- It maps one of the original data's attribute to test data's location id
- It then aggregates by part number and location id to calculate inventory position

## Setup

Refer to "Get Started" section on [pandas-amex-match](https://github.ibm.com/wcelab/pandas-amex-match) project on how to set up the environment for a Jupyter Notebook development environment.


## Where is the code?

[testdata-generator.ipynb](./testdata-generator.ipynb) is the only code. 
[data_source](./data_source) folder contains original test data to be repurposed.

