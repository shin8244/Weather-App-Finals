# WeatherApp: Real-Time Weather Information

## Overview
WeatherApp is an interactive web application designed to provide real-time weather information. By integrating with the OpenWeatherMap API, the application displays current weather details for any city entered by the user. The app also supports real-time updates through WebSocket connections, offering a dynamic and engaging user experience.

## Features
- **Dynamic Content Update**: Utilizes JavaScript to manipulate the DOM and dynamically update content based on user interactions.
- **Web API Integration**: Fetches data from the OpenWeatherMap API to display current weather information.
- **WebSocket Functionality**: Enables real-time updates through WebSocket connections.
- **Responsive Design**: Ensures a seamless experience across different devices and screen sizes.
- **Animated Elements**: Includes animated elements to enhance user engagement.
- **Custom Styling**: Implements a visually appealing design with gradients, custom fonts, and background images.

## Project Structure
The project consists of the following key files and directories:
- **index.html**: Contains the HTML structure of the web application.
- **styles.css**: Includes the CSS styles for the web application.
- **script.js**: Contains the client-side JavaScript code.
- **server.js**: Contains the server-side code using Node.js and WebSocket.
- **README.md**: Provides information about the project.

## Getting Started

### Prerequisites
Ensure you have Node.js and npm installed on your machine.

### Installation
1. Initialize the project:
    ```sh
    npm init -y
    ```
2. Install the necessary dependencies:
    ```sh
    npm install ws express axios
    ```

### Running the Application
1. Download and extract the ZIP file from the repository.
2. Navigate to the project directory:
    ```sh
    cd path/to/project-directory
    ```
3. Start the server:
    ```sh
    node server.js
    ```
4. Open a web browser and go to `http://localhost:8080`.

### Usage
- Enter the name of a city in the search box and click the search button or press the Enter key to see detailed weather information for the city.

## License
This project is licensed under the MIT License.
