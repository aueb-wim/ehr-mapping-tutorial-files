In this repo we store some mock data with information about patients and their visits in a hospital. This data is used in the [Data Factory User Guide](https://mip.ebrains.eu/documentation/User%20Manuals/6).
## EHR_Exams1.csv
Clinical data containing measurements and diagnosis variables.
## EHR_Patient_Family_history.csv
Basic demographics and other data related to the patients.
## cde_metadata.csv
The metadata descriptions of the Common Data Elements for Dementia.
## hospital_metadata.csv
The metadata descriptions of the hospital local data model, meaning for the variables in EHR_Exams1.csv and EHR_Patient_Family_history.csv.
## mapping-tasks
- map.xml : The mapping task configuration for the data capture step
- mapHarmonize.xml : The mapping task configuration for the data harmonization step
