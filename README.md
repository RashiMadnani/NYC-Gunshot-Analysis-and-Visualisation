# NYC-Gun-Shooting-Analysis-and-Visualization
Gun violence is a crime that is causing significant worry not only in NYC but also across America. A nonchalant attitude toward such a terrible act affects the physical, emotional, and mental health of society, and the effects extend well beyond the individuals involved in the crime. 


Welcome to New York! Here, the term oh shoot! is used more frequently for a gunshot than a mistake. Gun violence is a crime that is causing significant worry not only in NYC but also across America and even around our campus. A nonchalant attitude toward such a terrible act affects the physical, emotional, and mental health of society, and the effects extend well beyond the individuals involved in the crime. It has an impact on a number of businesses, real estate values, healthcare expenses, and the overall economy, and it poses issues with the licensing rules for firearms. When we learn about such news via UMD notifications, we likewise dread it. Thus, in order to better comprehend the statistics, we chose to analyze gun violence in NYC.

We will be using 2006 to 2021 NYC Gunshot data in order to study and respond to numerous inquiries pertaining to the Societies, Governments, and other businesses that are affected.

With the aid of our analysis, the government can keep track of the trends in gunfire in New York City and take action to reduce, if not stop, the deterioration of quality of life in such areas.

It can benefit real estate companies in the planning of their prospective developments in the NYC region by selecting safer neighborhoods as opposed to those that are more likely to experience gun violence.

This information can be used by the general public and tourists to make informed travel plans in NYC.

This analysis can help first responders better prepare themselves to treat gunshot victims quickly and effectively to save lives in high-gun violence areas.

New York city is made up of five boroughs (Bronx, Brooklyn, Manhattan, Staten Island, and Queens)
US Census information for 2021 shows that the population of New York City was composed of approximately 52% female and 48% male with each borough closely following that same split of male and female residents
Across all five boroughs and New York City as a whole, the three races with the highest populations are White (non-Latino), Hispanic or Latino, and Black. The White(non-Latino) population has the highest concentration across all of the five boroughs.
Over 60% of the population in New York City are between the age of 18 - 64, followed by people under 18 and people aged above 65 account to about ~10% of the population.1
We have graduated from UMD and are working in an NYC based startup- Oh Shoot!. We are a consulting firm that focuses on providing data-backed recommendations for clients. More Americans died of gun-related injuries in recent years compared to other years on record. We currently are working with two institutions that have asked us to analyze a data set on NYPD Shooting Incidents Data.

The data set for analysis is available publically on the NYC OpenData website. Each record represents a shooting incident in NYC and includes information about the event, the location, and time of occurrence. In addition, information related to suspect and victim demographics is also included.

Data Source (dataset and geojson): https://data.cityofnewyork.us/Public-Safety/NYPD-Shooting-Incident-Data-Historic-/833y-fsy8



Individual Column Descriptions:

INCIDENT_KEY: randomly generated Id by the NYPD for each incident. (a shooting incident can have multiple victims involved. Each incident key represents one victim, hence similar incident keys are counted as one incident)
OCCUR_DATE: exact date of the shooting incident.
OCCUR_TIME: the exact time of the shooting incident.
BORO: name of the borough where the shooting incident occurred.
PRECINCT: precinct where the shooting incident occurred.
JURISDICTION_CODE: jurisdiction where the shooting incident occurred. Here,
0: Patrol
1: Transit
2: Housing
3 and above: Non-NYPD jurisdiction
LOCATION_DESC: location of the shooting incident.
STATISTICAL_MURDER_FLAG: shooting resulted in the victim's death which would count as murder.
True: murder
False: an injury not leading to death
PERP_AGE_GROUP: perpetrator's age within a category.
PERP_SEX: perpetrator's gender.
PERP_RACE: perpetrator's race description.
VIC_AGE_GROUP: victim's age within a category.
VIC_SEX: victim's gender.
VIC_RACE: victim's race description.
X_COORD_CD, Y_COORD_CD: midblock X-coordinate and Y-coordinate for New York State Plane Coordinate System, Long Island Zone, NAD 83, units feet (FIPS 3104).
Latitude, Longitude: GPS coordinates where the incident occurred.
Lon_Lat: a combination of latitude and longitude.
Our analysis will help derive valuable answers to the following questions and many more:

What are the trends in shooting incidents over the years in NYC?

Considering that NYPD is interested in our data analysis and wants to determine if there are any areas that experience shootings where the shooter flees after the incident- What are the insights and recommendations that we can provide to determine the same?

Which group of people (as determined by gender, age group, and race) are at a higher risk of being a victim of shooting incidents in NYC?

New York City Council has asked for some recommendations on the basis of spatial facets with high gun violence- What are the socioeconomic factors contributing to high gun violence? In order to curb this problem, what solutions can be recommended?

What recommendations can we provide to ZeroEyes (a firm that delivers A.I. video gun detection real-time solutions) based on NYC Shooting data? What are the possible locations Zero Eyes can target?

Based on previous shooting incidents, what is the expected trend in the number of victims for the following years?
