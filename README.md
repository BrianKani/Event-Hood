# Event Management Application

## Overview
The Event Management Application is a web-based system designed to manage events, registrations, and user profiles. It allows users to create, search, register for, and manage events conveniently.

## Features
- **Event Creation:** Users can create new events by providing details such as event name, description, date, time, and location.
- **Event Registration:** Users can register for events they are interested in attending.
- **User Authentication:** Authentication system to ensure secure access to the application.
- **User Profile:** Users can manage their profiles, update personal information, and view their registered events.
- **Search Functionality:** Users can search for events based on various criteria such as event name, date, or location.
- **Event Details:** Detailed information about each event, including description, date, time, location, and attendees.

## Technologies Used
- Java
- Servlets and JSP (JavaServer Pages)
- Maven for project management and build automation
- Apache Tomcat or GlassFish as the application server

## Setup Instructions
1. ** Load the project to NetBeans and go to "CLEAN AND BUILD" if the build is successful then WAR file will be created in the 'dist folder'
2. Copy the 'event.war' file created and paste it in the 'Webapps' folder in your apache tomcat installation folder. 
3. start your apache tomcat server with cmd and run startup.bat (note: run cmd within the bin folder of apache tomcat) 
4. Go to your browser and navigate to localhost8080 (or the listening port for your tomcat server) https://localhost8080/Event
## Contributors


