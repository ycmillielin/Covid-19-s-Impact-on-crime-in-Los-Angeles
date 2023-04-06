# Covid-19-s-Impact-on-crime-in-Los-Angeles

This is a school project with Pratik Khadse, Hsuan-Ting (Tommy) Wu, Nishkarsh Khokhar, and Falak Jain. 

The goal was to analyze the following 2 questions:

1. How did covid-19 impact crime in Los Angeles? What other factors could lead to this impact?
2. Whether Asians were more likely to become victims after covid-19 in Los Angeles?


# Result
[Presentation]( https://github.com/ycmillielin/Covid-19-s-Impact-on-crime-in-Los-Angeles/blob/main/Presentation.pdf)



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
| 5 | Area_zipcode.ipynb | dataset_w_Zipcode.csv | zip_area_max.csv |
| 6 | EDA visualizations.ipynb | df.sav |  |
| 6 |  | dataset.csv |  |
| 7 | add_censes_data_Final.ipynb | population.csv | pop_unemploy_income.csv |
| 7 |  | Unemployment.csv |  |
| 7 |  | Income_new.csv |  |
| 7 |  | dataset_w_Zipcode.csv |  |
| 8 | General regression new.ipynb | dataset_w_Zipcode.csv | regression_new.csv |
| 8 |  | pop_unemploy_income.csv |  |
| 8 |  | zip_area_max.csv |  |
| 9 | Regression_Hypothesis_Final.ipynb | regression_new.csv |  |
