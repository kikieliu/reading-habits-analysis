# Reading Habits Analysis

## Overview

This project looks at how factors like age, education, and income relate to reading habits.

I used Python, Pandas, and Matplotlib to look at how much people read, which formats they use, and whether those patterns change across different demographic groups.

This is an updated version of a university capstone project that I originally completed with a partner. The original notebook and presentation are included separately, while the main notebook contains my updated individual analysis.

[View the full analysis](reading_habits_analysis.ipynb)

## Tools

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Dataset

The dataset contains 2,832 survey responses about reading habits and demographics. Some of the main fields include age, education, income, number of books read, and whether participants used printed books, e-books, or audiobooks.

Before starting the analysis, I checked for missing values, duplicate records, and inconsistent values. One duplicate was removed, leaving 2,831 records.

The dataset was downloaded from Kaggle and was listed there as coming from Pew Research Center survey data.

[View the dataset on Kaggle](https://www.kaggle.com/datasets/vipulgote4/reading-habit-dataset?resource=download)

## Questions

I focused on a few main questions:

1. How many books do people typically read?
2. Which reading formats are most common?
3. Do people with different education levels read different amounts?
4. Does reading volume change across income groups?
5. Does age affect how much people read or which formats they use?

## Key Findings

- The median participant read 6 books during the previous 12 months. The average was much higher at 16.7 because a smaller group reported reading a large number of books.

- Printed books were by far the most common reading format.

- People with higher education levels generally reported reading more books.

- Reading volume also tended to be higher among higher-income groups, although the pattern was not completely consistent.

- Age did not seem to make a major difference in the number of books people read.

- Age had a clearer connection with format preferences. E-book and audiobook use was more common among some of the middle-age groups and lower among older participants.

Overall, education and income showed clearer differences in reading volume, while age seemed to matter more when looking at reading format.

## Impact

Looking at reading habits across different groups can help show where differences in reading behavior exist.

This kind of information could be useful for libraries, schools, or literacy programs when deciding what types of reading materials to provide or which groups may benefit from more support.

The results do not explain why these differences happen, but they can help point toward areas that may be worth looking into further.

## Limitations

The dataset only includes 2,831 records after cleaning, and some demographic groups are much more represented than others.

There were also some missing or unclear survey responses. In addition, the dataset documentation does not fully explain some of the original coded values.

The results only show patterns in this dataset. They do not prove that factors like education, income, or age directly cause differences in reading habits.

## Project Files

- `reading_habits_analysis.ipynb` — Updated individual analysis
- `reading_habits.csv` — Dataset
- `original-capstone/` — Original group notebook and presentation
