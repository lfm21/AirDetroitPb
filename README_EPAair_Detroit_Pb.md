##AirDetroitPb
A study on lead levels in the air in Detroit, MI, over the past 35 years.

##Summary
Tetraethyl lead (TEL) was completely phased out of gasoline in 1995; air lead levels have decreased 98% from 1980 to 2014. How has the "Motor City" of Detroit, MI, area experienced a decrease in air lead levels over time? 

##Database Information
The files were downloaded from https://www.epa.gov/outdoor-air-quality-data/download-daily-data and accessed on 2019-04-04. The area is Detroit-Warren-Dearborn in Michigan, USA.

##Data Content
Lead(Pb) in air has been monitored since 1981 in Detroit, though monitoring sites were inconsistently uploaded. Files of generally every fifth year (years 1981, 1985, 1990, 1995, 2000, 2005, 2010, 2015, and 2018) were accessed in order to get a broad view of air Pb quantity and trends. 

Date: month/day/year
Source: AQS (Air Quality System) or AirNow
Site ID: A unique number within the county identifying the site.
POC: “Parameter Occurrence Code” used to distinguish different instruments that measure the same parameter at the same site.
Daily Mean Pb Concentration: numeric value
Daily Max 8-hour Ozone Concentration: numeric value
Units: units for concentration are ug/m3 SC or ug/m3 LC
Daily_AQI_VALUE: contains a "." because there is no air quality index for Pb in air.
Site Name: various sites, generally schools and public parks
DAILY_OBS_COUNT: number of observations per day
PERCENT_COMPLETE
AQS_PARAMETER_CODE
AQS_PARAMETER_DESC
CBSA_CODE: 19820
CBSA_NAME: Detroit-Warren-Dearborn, MI
STATE_CODE: 26
STATE: Michigan (MI)
COUNTY_CODE: 163
COUNTY: All in Wayne County, MI
SITE_LATITUDE
SITE_LONGITUDE
#Naming Conventions/ File Formats
All files were accessed as .csv files, and named EPAair_Pb_Detroit_YEAR.csv.
Files are named according to the following naming convention: `databasename_datatype_details_stage.format`

For more information, please contact Laurie Muzzy (laurie.muzzy@duke.edu)