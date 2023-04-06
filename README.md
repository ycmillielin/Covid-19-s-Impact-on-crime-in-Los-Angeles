# Covid-19-s-Impact-on-crime-in-Los-Angeles

The goal was to analyze the following 2 questions:

How did covid-19 impact crime in Los Angeles? What other factors could lead to this impact?
Whether Asians were more likely to become victims after covid-19 in Los Angeles?


# Result

# Installation

| Steps | Jupyter Notebook | Input file | Output file |
| --- | --- | --- | --- |
| 1 | Cleaning_Dataset_1 | Crime_Data_from_2010_to_2019.csv | df.sav |
| 1 |  | Crime_Data_from_2020_to_Present.csv | dataset.csv |
| 2 | Cleaning_Dataset_2 | df.sav | df.sav |
| 2 |  | dataset.csv | dataset.csv |
| 3 | zipcode_finder.ipynb | coords.csv | Coords_w_Zipcodes.csv |
| 4 | zipcode_merge.ipynb | df.sav | dataset_w_Zipcode.csv |
| 4 |  | Coords_w_Zipcodes.csv |  |
