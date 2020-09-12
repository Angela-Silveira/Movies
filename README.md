# Movies
The purpose of this analysis is to clean and consolidate large amounts of data related to movies to allow for the information to be used for further analysis during a hackathon.

Wikipedia data is utilized for general information (titles, budgets/box office revnue, actors, etc.) that needed to be streamlined to filter out only movies (versus TV shows), consolidate columns (Directed by/Director) and eliminate repetitive information (Alternate Titles). Formatting of some data (budget, box office) was cleaned using regular expressions so the result is left in a consistent format despite how the data was entered.

Kaggle data provided similar information, which allowed the information to fill in gaps in the Wikipedia data (or the opposite) to combine to form a more complete dataset. 

These two data sets combined with the viewer ratings data to create databases that will allow the hackathon group to extract useful findings related to highly-rated content.
