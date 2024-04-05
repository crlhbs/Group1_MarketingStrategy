## **Welcome to the repository of Group 1 in the ✨ Digital Marketing Strategy ✨ course of 2024.**

In this repository, you will find the code that has been used to investigate and analyze the provided themepark dataset as well as the testing of our hypotheses.

The repository is structured as follows:

#### Jupyter Notebooks
* **Cleaning_EDA**: Includes the main part of data pre-processing as well of the Exploratory data analysis. It was also used to merge the 4 datasets that were given for this work, and created an output dataset ('combined_themepark_dataset.csv') that was then used in the hypotheses testing files 'Testing_H1'-4.
* **Testing_H1,...,H4**: In these notebooks, the level 1 hypotheses were tested. The four files are split up into the different themes of our hypotheses (sentiment, time, emoji, post type).
* **Multi-level_Analysis**: This file includes the multilevel model that has been used to test our level 2 hypotheses. The pymer4 library was utilized here.

#### Datasets (folders, CSV-files)
* **01_original theme park dataset**: This folder includes the 4 datasets that were given at the beginning of this course.
* **02_new dataframes:** This folder includes the 4 dataframes that were exported as the results of the level 1 hypothesis testing files, and inlcudes their new features. These files were stored to be then merged in the 'Multi-level_Analysis' notebook, to create one dataset that includes the new features, for the multi-level testing.
* **combined_themepark_dataset.csv**: This dataset was the result of the Cleaning_EDA notebook and was then used to test the level 1 hypotheses.

#### Datasets (Excel-files)
In addition to the given data, further information was scraped from public online sources.
* **Themepark_Followers.xlsx**: This file contains the number of facebook followers of the analyzed themeparks, serving as out level 2 variable.
* **Timezones.xlsx**: This data was used to find the accurate time of day for every single post in the dataset. More information in 'Testing_H1.ipynb'.

![](https://i.pinimg.com/originals/6a/c1/fa/6ac1faaa1fa28a7a185f3dfda353b5d5.gif)

**Contributors (Team 1):**
Paul Antony,
Carl Hümbs,
Matthijs Snijders,
Otto Tagapere
