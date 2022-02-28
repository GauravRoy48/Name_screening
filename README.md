# Name Screening

Scripts that were used to design the Levenshtein based name matching models using phonemes (Double Metaphone).

## Files

1. **1__Name_Screening__Data_Loader.ipynb** - Python notebook to read data source files and (OFAC *(TXT)*, FSF *(CSV)* and BIS Denied Persons *(TXT)* supported)
2. **2__Name_Screening__Data_Analysis.ipynb** - Python notebook to perform analysis on the data to finalize the metrics, thresholds and solutions
3. **3__Name_Screening__Name_Search.ipynb** - Python notebook to run query on the final dataset using the algorithm developed in the previous notebook
4. **random_*_.csv** - CSV files containing randomly generated names of different origin as mentioned in the corresponding file name. Used for artificially increasing the dataset size


## Python Libraries Required

- abydos
- python-Levenshtein
- warnings
- numpy
- pandas
- matplotlib
- seaborn
- datetime
- time
- re
- os

### Versions used

- Python Version: 3.8.5
- Matplotlib Version: 3.3.2

## Data Sources

1. OFAC NS-PLC List : 
https://home.treasury.gov/policy-issues/financial-sanctions/consolidated-sanctions-list/non-sdn-palestinian-legislative-council-ns-plc-list

2. BIS Denied Persons List : 
https://www.bis.doc.gov/index.php/policy-guidance/lists-of-parties-of-concern/denied-persons-list

3. EU FSF List (requires signup using email for list updates) : 
https://eeas.europa.eu/headquarters/headquarters-homepage_en/8442/Consolidated%20list%20of%20sanctions
