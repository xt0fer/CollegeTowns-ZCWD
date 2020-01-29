#  CollegeTowns-ZCWD
### College Towns by State

**github.com/xt0fer/CollegeTowns-ZCWD**

This is a data wrangling (data cleaning) activity. It is an intermediate lab.

Create code that Returns a DataFrame of towns and the states they are in from the university_towns.txt list. The format of the DataFrame should be something like: DataFrame( [ ["Michigan", "Ann Arbor"], ["Michigan", "Yipsilanti"] ], columns=["State", "RegionName"]  )

Yes, you are making a frame that has lots of copies of the state names in it.
    
The following cleaning needs to be done:

1. For "State", it removes characters from "[" to the end.

2. For "RegionName", when applicable, it removes every character from " (" to the end.

3. End product should be a dataframe we can ask **"How many college towns in each state?"**

Dataset: 'university_towns.txt'

Source of Dataset: https://en.wikipedia.org/wiki/List_of_college_towns#College_towns_in_the_United_States

analysis.ipynb: Jupiter notebook that imports the raw unstructured dataset, performs cleaning, and structuring of the data

#### Extra Credit

add a column which contains the name(s) of the school in each region `columns=["State", "RegionName", "Schools"]`

source ref: https://github.com/bot13956/unstructured_data_university_towns
