# Analysis of NYC landlord expenses and maintenance spending – Tax Commission TC201 Form — 2021

This repository contains data and analytic code that support the CUNY j-school analysis of landlord spending on rent stabilized units. This analysis was done by Saugat Bolakhe, Liz Rosenberg, Safiyah Riddle, and Rebecca Redelmeier for Lam Thuy Vo's data journalism class.

## Data

This analysis uses rent-data.csv spreadsheets.

The spreadsheets come from the following sources:

- New York City Tax Commission 
  - `rent-data.csv'`: This includes raw data from forms landlords file with the city's Tax Commission whn applying to dispute their tax bills. Not every landlord files this form every year, but many do to request lower tax rates.

Each of the spreadsheets contain, among others, the following columns relevant to the analysis:

- `TOTAL EXPENSES` — Total expenses landlords spent on the buildings, self-reported to tax commission
- `TOTAL INCOME FROM REAL ESTATE` — Total income landlords receive from the building, elf-reported to tax commission 
- `REPAIRS AND MAINT.` - Total landlords spend specifically on repairs and maintance of the building, self-reported to tax commission

## Methodology

The notebook [`analysis.ipynb`](notebooks/analysis.ipynb) performs the following analyses:

##### Part 1: Finds total expenses as a percentage of total income

- Calculates percentage of total income spent on expenses


##### Part 2: Finds repairs and maintance expenses as percent of total expenses

- Calculates percentage of total expense cost spent on repairs

The google sheet ['tax_data_analysis'](https://docs.google.com/spreadsheets/d/1whShVMTuxbVc5Kfbm6SWC2WhLuXR5lIqQ0JRE6zRIvE/edit#gid=965609219) perfroms the following analyses:

##### Filters all building expense data for only buildings that include income from rent stabilized units


## Outputs

The notebooks output this spreadsheet which contains the csv with columns that include total expenses percent of income and total repairs as percent of maintenance: [`output/tax_data_analysis.csv`](output/tax_data_analysis.csv).

## Running the analysis yourself

You can run the analysis yourself. To do so, you'll need the following installed on your computer:

- Python 3
- Pandas

## Licensing

All code in this repository is available under the [MIT License](https://opensource.org/licenses/MIT). The data file in the output/ directory is available under the [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/) (CC BY 4.0) license. All files in the data/ directory are released into the public domain.

## Feedback / Questions?

Contact the team of us at CUNY at rebecca.redelmeier33@journalism.cuny.edu
