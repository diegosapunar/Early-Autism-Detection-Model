# EARLY AUTISM DETECTION

## Steps 

1. Find Data: 2566 studies founded
2. First Filter: Review studies relevance: 12 studies
3. Second Filter: Find common data schemas (ados exam) between the studies: 9 studies.
4. Pre-proccessing each data set: 
    * Delete columns with more than 25% of NaN values.
    * Remove duplicate columns
    * Parse the columns name (features): All in lower case and removing special characters.
5. Merge the 9 studies.
    * Standardization of the diagnosis format (y values)
    * 