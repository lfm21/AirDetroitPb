##AirDetroitPb
A study on lead levels in the air in Detroit, MI, over the past 35 years.

##Summary
In addition to dramatically decreased airborne lead concentrations, another indicator of
progress in the reduction of airborne lead in the environment is the drop in children's
blood lead levels over time. Since the late 1970s, average blood lead concentration for
children aged 1 to 5 have dropped significantly, from about 15 micrograms per deciliter
(µg/dL) to less than 1 µg/dL. 
On September 16, 2016, EPA announced its decision to retain, without revision, the
national ambient air quality standards (NAAQS) for lead of 0.15 ug/m3, in terms of a 3-
month average concentration.

Tetraethyl lead (TEL) was completely phased out of gasoline in 1995; air lead levels have decreased 98% from 1980 to 2014. How has the "Motor City" of Detroit, MI, area experienced a decrease in air lead levels over time? 

##Database Information
The files were downloaded from https://www.epa.gov/outdoor-air-quality-data/download-daily-data and accessed on 2019-04-04. The area is Detroit-Warren-Dearborn in Michigan, USA.

##Data Content
Lead(Pb) in air has been monitored every 12 days, since 1981 in Detroit-Dearborn-Warren area; there is a gap in data collection in the early 2000s.
.csv files were downloaded for every year available, which was 1981 until 2018. 

Date: month/day/year
Source: AQS (Air Quality System) or AirNow
Site ID: A unique number within the county identifying the site.
POC: “Parameter Occurrence Code” used to distinguish different instruments that measure the same parameter at the same site.
Daily Mean Pb Concentration: numeric value
Daily Max 8-hour Ozone Concentration: numeric value
Units: units for concentration are ug/m3 SC or ug/m3 LC (to the best of my knowledge, this refer to SC = standard conditions of 25 degrees C, and LC = local condiditons). LC is used from 1981 until 2010; SC is used after 2010.
Daily_AQI_VALUE: all columns contain a period "." because there is no air quality index standard for Pb in air.
Site Name: various sites, generally schools and public parks
DAILY_OBS_COUNT: number of observations per day = 1
PERCENT_COMPLETE: 100%
AQS_PARAMETER_CODE: varies
AQS_PARAMETER_DESC: Lead (TSP) STP
CBSA_CODE: 19820
CBSA_NAME: Detroit-Warren-Dearborn, MI
STATE_CODE: 26
STATE: Michigan (MI)
COUNTY_CODE: 163
COUNTY: All in Wayne County, MI
SITE_LATITUDE: varies
SITE_LONGITUDE: varies
#Naming Conventions/ File Formats
All files were accessed as .csv files, and named EPAair_Pb_Detroit_YEAR.csv.
Files are named according to the following naming convention: `databasename_datatype_details_stage.format`

For more information, please contact Laurie Muzzy (laurie.muzzy@duke.edu)