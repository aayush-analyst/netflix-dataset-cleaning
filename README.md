# netflix-dataset-cleaning
Dataset cleaning of Netflix Movies and TV shows

## Data Cleaning and Preprocessing

## Dataset Used:
- Netflix Movies and TV Shows (from Kaggle)

## Tools:
- Microsoft Excel

## Steps Performed:
1. Checked all the columns of 'Netflix Movies and TV Shows' dataset which columns has blanked.
- director,cast,country,date_added columns have blank cells.
- rating column has blank cells as well as some values of other cells were filled. 
  
2.Then filled missing values in 'director', 'cast', and 'country' with '"Unknown"'
- Filled by using IF() function in MS Excel.

3. Standardized 'rating' column, fixed invalid entries
- Filled blank cells by using IF() function as "Unrated".

4. Removed duplicate records
- By using data tab then remove duplicates option in Excel.
 
5. Cleaned column headers: lowercase, no spaces.
   
6. Converted 'date_added' to 'dd-mm-yyyy' format, preserved 'Unknown' where needed.

## Note:
-All columns cleaned using formulas (like 'IF()') were finalized by using Paste Special Values to replace formulas with actual data.

## Output:
- Cleaned and analysis-ready dataset with 8807 records

## Files Included:
- 'netflix_titles_cleaned_final.csv': Final cleaned data
- 'README.md': This summary

