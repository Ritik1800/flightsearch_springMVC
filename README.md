# flightsearch_springMVC

Extend Assignment #2 to implement a flight search Web Application using Spring, Hibernate technology  that lists matching flights for a traveller who is looking to fly between 2 locations on a given date.

Instead of providing input on console, users will use a web application to input. The web application has to be developed using Spring MVC. Spring and Hibernate integration has to be implemented.

Program should accept 5 input parameters
Departure Location
Arrival Location
Flight Date
Flight Class
Output Preference 

“Flight Class” is a String which has two possible values like ‘E’ and ‘B’. E=Economic and B=Business.
“Output Preference” is a String which suggests whether flight result should be sorted only by fare or by both  fare and flight duration.


Expected Behaviour And Output

Program should be written considering that there could be more csv files and at runtime program should load the files. Please make use of Thread which will look for any new file at particular location after some configurable time and load the provided file
Create a login Page for the application and after successful login Flight Search Screen will be displayed
Search screen should have all input parameters specified in previous slides as Departure Location, Arrival Location, Flight Class, Flight Date, Output Preference
Once Search is triggered after specifying the search parameters, program will display the search results using hibernate
Use Spring MVC and Spring - Hibernate Integration
Spring version 3 or 4 should be used


