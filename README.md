# Healthcare Expenditure and Related Variables over Time

## About

Join me as we investigate healthcare expenditures as they relate to life expectancy and child mortality in developed countries from 2000 to 2019. The Human Development Index (HDI) is a composite score based on many different demographic statistics, such as education level, per capita income, lifespan, gross national income, etc. Based on the HDI, the top 25 developed countries are:
- Australia
- Austria
- Belgium
- Canada
- Denmark
- Finland
- Germany
- Hong Kong
- Iceland
- Ireland
- Israel
- Japan
- Liechtenstein
- Luxembourg
- Malta
- Netherlands
- New Zealand
- Norway
- Singapore
- Slovenia
- South Korea
- Sweden
- Switzerland
- UK
- USA

Specifically, we will be investigating the following variables and how they correlate with each other:
- GDP
- Life expectancy
- Child mortality
- Total healthcare expenditure
- Out of pocket healthcare expenditure

## Data Source
- [Kaggle - Financing Healthcare](https://www.kaggle.com/datasets/programmerrdai/financing-healthcare?select=share-of-out-of-pocket-expenditure-vs-gdp-per-capita.csv)
- Specific files: child-mortality-vs-health-expenditure.csv, life-expectancy-vs-healthcare-expenditure.csv, and share-of-out-of-pocket-expenditure-vs-gdp-per-capita.csv

## Installation
First, ensure you’ve met the following requirements:
- Python is installed – this project was developed using Python 3.11.4. If you need to install python or update your version, you can do so here: [Python Official Website](https://www.python.org/downloads/)
- Git is installed – you will need Git to clone the repository. If you need to download it, you can do so here: [Git Official Site](https://git-scm.com/downloads)

In order to run this project on your local machine, follow these steps:

**Clone the Repository**

- Navigate to the location you want the repository to be cloned using the ```cd``` command in your terminal, or by opening the location in file explorer and typing cmd into the navigation bar to open your terminal in that location.
- Once you have your terminal open in the desired location, use the following command in your terminal:

```
git clone https://github.com/metrictulip0309/Capstone.git
```

**Navigate to the Cloned Repository**

Use the ```cd``` command to navigate to the directory where the repository was cloned.

**Set Up and Activate Virtual Environment**

Using a virtual environment will isolate the project from your system's Python environment. The following commands will create a virtual environment called 'venv' in your current directory.

Set Up:
For Windows
```
python -m venv venv
```

For macOS or Linux
```
python3 -m venv venv
```

Activation:
For Windows
```
.\venv\Scripts\activate
```

For macOS or Linux
```
source venv/bin/activate
```

**Install Required Packages**

Run the following command to install required packages:
```
pip install -r requirements.txt
```

**You are now set up to run the project!**

To do so, open the Capstone Project.ipynb file.
You can run each cell individually in order or choose to run all cells.

When you finish, type 'deactivate' into your terminal to deactivate the virtual environment.

## Visualizations

Visualizations of this data can be viewed at my [Tableau Public Dashboard](https://public.tableau.com/shared/B6QH4MYSN?:display_count=n&:origin=viz_share_link)

## Summary of Findings

Using Tableau, I looked for correlations in the data. Of note, these correlations are only using data from the above countries. If countries with a lower HDI were examined, these findings may be very different. Additionally, this investigation did not look for any causality only correlation. Based on the correlation coefficient and p-value, the following correlations were observed:
- GDP and child mortality showed a slight negative correlation
- Child mortality and life expectancy showed a negative correlation
- Population and child mortality showed a slight positive correlation
- Health expenditure (% of GDP) showed a very slight positive correlation with life expectancy (p-value indicated statistical significance)
- Health expenditure (% of GDP) also showed slight positive correlations with out-of-pocket expenditure (% of total health expenditure) and population
- Life expectancy showed a slight positive correlation with out-of-pocket expenditure (% of total health expenditure)
- Life expectancy has increased over time while child mortality has decreased, though the increase in life expectancy is greater than the decrease in child mortality
- The percent of GDP that is spent on healthcare and the percent of healthcare expenditure that is paid out-of-pocket have both increased over time, though GDP itself has not

It is unsurprising that life expectancy and child mortality show an inverse correlation due to medical advancements. Additionally, this is correlated with an increase in the percent of GDP spent on healthcare and the percent of healthcare expenditure that is paid out-of-pocket. It is expected that the total dollar amount spent out-of-pocket would increase along with the overall increase in healthcare expenditure, but it is surprising that the percentage of out-of-pocket expenses has also increased. 


## Final Project Requirements

**Category 1**
- Read two data files (CSV).

**Category 2**
- Clean your data and perform a pandas merge, then calculate some new values based on the new data set.

**Category 3**
- Make a Tableau dashboard to display your data.

**Category 4**
- Use a virtual environment and include instructions in your README on how the user should set it up.

**Category 5**
- Annotate your code with markdown cells in Jupyter Notebook, write clear comments, and have a well-written READme.md. 

