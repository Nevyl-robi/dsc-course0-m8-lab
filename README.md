# Aviation Accident Analysis
## Business problem:
since the Airplane Insurer needs to know which particular Airplanes models have the lowest rate of destruction and serious passenger injury incase an accident occurs Therefore a reccommendation has to be made based on the size of an Aircraft.Either large or small

## files used:
Aviation_Accidents_cleaning.ipynb for data cleaning
Aviation_Accidents_Data_Analysis.ipynb for making plots and carrying out analysis

## Cleaning of Data:
this is the second step after acquiring our Data from AviationData.csv
Only events that occured  after 1983 was kept.
missing Aircraft categories was added from the common category of the same model and category
An aircraft with 20 or more passengers in any of the accidents was grouped as a large Aircraft otherwise it was classified as small
the total recorded accidents after cleaning is 55,090

## findings after analyzation:
in large Aircrafts model:Mcdonell Douglas,Boeing and Embraer are the best after recording a fraction of 0.05 to 0.11 and a destroy rate of 0.06 to 0.12 with Boeing having the largest samplde of 650 accidents
in small Aircrafts model:Wako Greatlakes and Maule are the best with Maule recording the largest sample of 495 accidents
landing and takeoff contribute to most accidents but are so rare to occur with a maneuvering of approximately 0.52 being the most severe
also engine type is a factor in that Aircrafts with large engines are the safest that is Turbo Fan and Turbo Jet aircraft
[makes_injury.png]
[makes destroyed.png]

## limitation:
Approximately 28% of accidents have no documented phase of flight and 6% engine type and approximately 12 accidents
models such as CESSNA and Beech  have only been grouped as large aircrafts since their models carried  either 20 or more passengers
Aircrafts with approximately 12 accidents provide a week evidence
## recommended models
Boeing 777 and Maule MX-7-235
