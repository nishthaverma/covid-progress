# Covid-Progress

<H1> Introduction </H1>
I started this project with the intention of learning about creating charts in python about a year ago. Recently, I had to learn how to make prediction models for an assignment, and thought this would be an interesting dataset to build up on! 

<H1> Project Overview </H1>
This project aims to analyze vaccination data and build a prediction model to determine the time required for countries to reach herd immunity (defined as 70% of the population being fully vaccinated). The project uses a Linear Regression model and a Random Forest Regressor to make these predictions.

<H1> About Dataset </H1>
Context
Data is collected daily from Our World in Data GitHub repository for covid-19, merged and uploaded. Country level vaccination data is gathered and assembled in one single file. Then, this data file is merged with locations data file to include vaccination sources information. A second file, with manufacturers information, is included.

<H1> Data </H1>

The data (country vaccinations) contains the following information:

<ul>
<li> Country- this is the country for which the vaccination information is provided;
<li>Country ISO Code - ISO code for the country
<li>Date - date for the data entry; for some of the dates we have only the daily vaccinations, for others, only the (cumulative) total
<li>Total number of vaccinations - this is the absolute number of total immunizations in the country
<li>Total number of people vaccinated - a person, depending on the immunization scheme, will receive one or more (typically 2) vaccines; at a certain moment, the number of vaccination might be larger than the number of people
<li>Total number of people fully vaccinated - this is the number of people that received the entire set of immunization according to the immunization scheme (typically 2); at a certain moment in time, there might be a certain number of people that received one vaccine and another number (smaller) of people that received all vaccines in the scheme
<li>Daily vaccinations (raw) - for a certain data entry, the number of vaccination for that date/country
<li>Daily vaccinations - for a certain data entry, the number of vaccination for that date/country
<li>Total vaccinations per hundred - ratio (in percent) between vaccination number and total population up to the date in the country
<li>Total number of people vaccinated per hundred - ratio (in percent) between population immunized and total population up to the date in the country
<li>Total number of people fully vaccinated per hundred - ratio (in percent) between population fully immunized and total population up to the date in the country
<li>Number of vaccinations per day - number of daily vaccination for that day and country
<li>Daily vaccinations per million - ratio (in ppm) between vaccination number and total population for the current date in the country
Vaccines used in the country - total number of vaccines used in the country (up to date)
<li>Source name - source of the information (national authority, international organization, local organization etc.)
<li>Source website - website of the source of information
