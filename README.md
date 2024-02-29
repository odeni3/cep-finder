# CEP-FINDER

![GitHub](https://img.shields.io/github/license/odeni3/Buscar-CEP?style=flat-square)

The Cep Finder program is a Java desktop application developed using WindowBuilder, enabling users to find address information based on a provided ZIP code. It utilizes XML code to access the Republica Virtual service API, fetching data such as city, neighborhood, and state. Additionally, it features data clearing functionalities and provides information about the developer, including links to GitHub and LinkedIn.

## Features

- **Search by ZIP Code:** Users can input a ZIP code in the search field and retrieve information about the corresponding address, including city, neighborhood, and state.
- **Data Clearing:** Functionality to clear input fields and restart the search process.
- **About:** An informative window providing details about the application, including version, author, and links to the service website, as well as the developer's GitHub and LinkedIn profiles.

## Technologies Used

- **Java:** The application is developed in Java, utilizing the Swing library for the graphical interface.
- **WindowBuilder:** The user interface is built using WindowBuilder, a powerful GUI designer tool for Java.
- **DOM4J:** DOM4J library is used for parsing and manipulating XML documents, enabling access to address data from the Republica Virtual service API.

## Getting Started

To run the Buscar CEP program locally, follow these steps:

1. Clone this repository to your local machine.
2. Ensure you have Java Development Kit (JDK) installed on your system.
3. Open the project in your preferred Java IDE that supports WindowBuilder.
4. Build and run the `Cep.java` file to launch the application.
