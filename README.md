# TorontoRobbery
This repository contains detailed analysis of Robbery dataset to evaluate historical robbery data in the City of Toronto in order to determine if there have been any recent changes to citizen safety in Toronto.

 ## Dataset:
 ### Robbery Dataset:
  - http://data.torontopolice.on.ca/datasets/281a5ad35c60458cb7de41c5ae99d5b5_0.
  ### Additional Dataset
  - Dates & Forward Sortation Area (FSA)
  - Neighbourhood 
  
  ## Data Preparation/Cleaning: 
  - Data set we have choosen was almost clean and most of the records have been failry populated but in order to utilize it efficiantly for our analysis we have reengineered/dropped some attributes from the original dataset.
  - Dataset and Subsets can be found in `Data` directory.
  - Data cleaning proecess is described in `DataCleaning - Final v2.docx`.
  
  ### Tools used for Data Normalization:
  -  SQL and Python
  ###  Subsets:
  - Robbery data 
  - Offences
  - Dates
  - Neighbourhood
  - Premise Types
  - Time of Day
  - Weather  
  
  ## Analysis:
  -  By Type: `TorontoRobbery-Type.ipynb`
  -  By Neighbouthood: `TorontoRobbery_Neighbourhood.ipynb`
  -  By Time/Weather: `TorontoRobbery_Time_Weather.ipynb`
  -  By Division/Reporting:  `Toronto_Robbery_AfterHours.ipynb`
  -  Plotting of Robbery data on Map: `Toronto_Robbery_Map.ipynb`
  
  ## Environment:
  - Language: Python 3
  - IDE: Jupiter Notebook
