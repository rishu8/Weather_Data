## THIS SCRIPT IS WRITTEN TO GENERATE WEATHER DATA
## HOW TO RUN :
## data_generator.py <start date> <end date>
## data_generator.py help 

## Creates data in ./misc folder 
## misc folder contains dimension data and mean climate data
## PLS DONT DELETE

## Run time as of now : 10 minutes for 1M records generated
## Test conducted in Intel(R) Xeon(R) CPU E5-2676 v3 @ 2.40GHz 2GB RAM RHEL Machine

## Use start and end date having a year difference to produce 1M data.

## Output is comma delimited
##  Out put ddl as follows

## DATE TIMESTAMP
## IATA_CD CHAR(3)
## STATION NUMBER SMALLINT
## STATION NAME VARCHAR(50)
## LATITUDE CHAR(10)
## LONGITUDE CHAR(10)
## MAX TEMP FLOAT
## MIN TEMP FLOAT
## CONDITION CHAR (10)
## WIND SPEED FLOAT
## ATMOSPHERIC PRESSURE FLOAT


