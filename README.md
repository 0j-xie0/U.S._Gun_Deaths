# Exploring Gun Deaths in the U.S.
•To explore gun deaths in the U.S. with data from FiveThirtyEight and the CDC  
•To find patterns within victim demographics.

# Installation
•Clone this repo to your computer.  
•OPTIONAL: the original dataset "full_data.csv" can be found [here](https://github.com/fivethirtyeight/guns-data)  
•Install the requirements using pip install -r requirements.txt.  
•Make sure you use Python 3.  
•You may want to install [Jupyter](http://jupyter.org/install) to run the ipynb.

# Usage
•Run the Jupyter Notebook "US.Gun.Deaths.ipynb" either in Jupyter or the IDE of your choice.

# Tasks Performed
### •Removed Headers from List of Lists.
••Extracted first row data and created header row.
### •Calculated Gun Deaths by Year.
••Created dictionary that keeps count of gun deaths in the year column.
### •Explored Gun Deaths by Month & Year.
••Used a list comprehension to create a datetime.datetime object for each row.  
••Queried unique dates to count how many Gun Deaths per month and per year.
### •Explored Gun Deaths by Race & Sex.
••Applied dictionary counting technique to calculate Gun Deaths in race and sex columns.
### •Compared Results to Census Data.
••Read in second dataset from U.S. Census Bureau.
### •Computed Rates of Gun Deaths per Race.
••Cross-referenced Census data and converted raw race counts to a rate of gun deaths per 100000 in each race.
### •Filtered Gun Deaths by Intent.
••Restricted results to gun-related homicides per 100000 in each race.
