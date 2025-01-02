
# HelpHub

HelpHub is a platform designed to connect those in need with volunteers who are willing to help. The platform serves as a bridge of interaction, allowing individuals to offer assistance or seek help based on their location and needs.

## Table of Contents
- [Project Description](#project-description)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [How to Run the Project](#how-to-run-the-project)
- [Screenshots](#screenshots)
- [Authors and Acknowledgements](#authors-and-acknowledgements)

## Project Description
HelpHub addresses the lack of a direct connection between those in need and those willing to help. By creating a platform where both volunteers and people in need can register, it enables users to find each other based on their location and specific needs. 

This project was developed during the *Code for All* bootcamp as our final project, with a tight 3-day deadline.

## Features
- **User Registration**: Allows both people in need and volunteers to register on the platform.
- **User Profiles**: Displays user details such as contact information and location.
- **Interactive Cards**: Users can see a list of registered individuals (both volunteers and those in need) in a card view.
- **Search and Filter**: You can search for volunteers based on specific service.

## Technologies Used
- **Backend**: Java, Spring Framework (Spring WebMVC, Spring ORM, Spring TX), Hibernate, MySQL, H2 Database
- **Frontend**: HTML, CSS, JavaScript, Google Maps API
- **Build & Dependency Management**: Maven
- **Server**: Tomcat 8

### Backend Technologies:
- Spring WebMVC (4.3.11.RELEASE)
- Spring ORM (4.3.11.RELEASE)
- Spring TX (4.3.11.RELEASE)
- Hibernate (5.3.6.Final)
- MySQL (8.0.12)
- H2 Database (1.4.196)
- Tomcat Maven Plugin

### Frontend Technologies:
- HTML
- CSS
- JavaScript
- Google Maps API

## How to Run the Project

### Prerequisites:
- Java 8 or higher
- Maven
- MySQL Database
- A new google API key
- VS Code with live server

### Running the Backend:
1. Clone the repository.
2. Navigate to the project folder and open it in your terminal.
3. Run the Maven build command:
   ```bash
   mvn clean install
   ```
4. To run the backend locally, use the following Maven command:
   ```bash
   mvn tomcat7:deploy
   ```
   
### Running the Frontend:
1. Open the frontend folder with VS Code
2. Run index.html with live server plugin
### Configuration:
- Make sure to configure your MySQL database with the proper settings (username, password, etc.), or use the H2 database for development.


## Screenshots

### Homepage
![Homepage Screenshot](Screenshot%20from%202025-01-02%2010-18-41.png)

### Registration Page
![Registration Page Screenshot](Screenshot%20from%202025-01-02%2010-19-26.png)

### Volunteer Profile Cards
![User Profile Cards Screenshot](Screenshot%20from%202025-01-02%2010-18-52.png)

### InNeed Profile Cards
![User Profile Cards Screenshot](Screenshot%20from%202025-01-02%2010-19-09.png)
## Authors and Acknowledgements

This project was developed by:
- **Lucas Takase Sasaki** - Dependency and Plugin Configuration, JavaScript Integration
- **Ana Teresa Fernandes** - Frontend Development (HTML, CSS, JavaScript)
- **Rafael Lopes** - Backend Development
- **Manuel Vieira** - Backend Development

I would like to thank *Code for All*, the *Mastercoders*, our fellow bootcamp colleagues, and everyone who supported us during the development of this project.

Special thanks to the people who helped us refine this idea!
