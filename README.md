// This is a simple REST api using RAML and MULE. To run this project you will need Anypoint Studio already installed.

//Installation

1. Import the project into your workspace within Anypoint Studio, and make sure the project settings have jdk 8 set as a JRE system library.
2. Run As -> Mule Application.


//Technical Specification:

I have used http status codes to indicate validation (400), empty results (404), and server errors(500).

The intention is to provide a REST based API interface/gateway for the older soap based web service http://www.webservicex.net/globalweather.asmx?wsdl.

This application has below REST API services:
1st service: Get Cities - This service lists down all the cities
2nd Service: Gets cities by country - This service lists down all the cities in a given country as parameter,
3rd Service: Get Weather - This service gets the weather report of the city in a country taking city and country as parameters.
