🌤️ Weather App

A simple and beginner-friendly weather application built with Node.js, Express.js, EJS, and the OpenWeatherMap API. Users can search for any city and view its current weather conditions, including temperature, humidity, and weather description.

📌 Features

🔍 Search weather by city name

🌡️ Display current temperature (°C)

💧 Display humidity

☁️ Show current weather description

❌ Display an error message for invalid city names

🔐 Secure API key management using environment variables


🛠️ Technologies Used

Node.js

Express.js

EJS (Embedded JavaScript Templates)

Axios

dotenv

HTML5

CSS3

OpenWeatherMap API

📂 Project Structure

weather-app-node.js/
│

├── node\_modules/

├── public/

│   └── css/

│       └── style.css

│

├── views/

│   └── index.ejs

│

├── .env

├── app.js

├── package.json

├── package-lock.json

└── README.md

🚀 Getting Started

1\. Clone the Repository

git clone https://github.com/Gelilaaah/weather-app-node.js.git

cd weather-app-node.js

2\. Install Dependencies

npm install

3\. Get an API Key

Create a free account on the OpenWeatherMap website and generate an API key.

4\. Create a .env File

Create a file named .env in the project's root directory.

API\_KEY=YOUR\_API\_KEY

Replace YOUR\_API\_KEY with your actual API key.

5\. Run the Application

node app.js

Or, if you have nodemon installed:

nodemon app.js

6\. Open Your Browser

Visit:
http://localhost:3000

📷 Application Workflow

User enters a city

&#x20;       │
&#x20;       ▼

Form submits request
&#x20;       │
&#x20;       ▼

Express receives POST request
&#x20;       │
&#x20;       ▼

Axios sends request to OpenWeatherMap API
&#x20;       │
&#x20;       ▼

API returns weather data
&#x20;       │
&#x20;       ▼

Express renders the EJS template
&#x20;       │
&#x20;       ▼

Weather information displayed to the user

📖 API Endpoint Used

GET https://api.openweathermap.org/data/2.5/weather

Query Parameters

Parameter	Description

City name

appid	API Key

units	metric


Example:
https://api.openweathermap.org/data/2.5/weather?q=Addis%20Ababa\&appid=YOUR\_API\_KEY\&units=metric

📸 Sample Output


City: Addis Ababa

Temperature: 18°C

Humidity: 64%

Weather: Broken Clouds

⚠️ Error Handling

The application gracefully handles:

- Invalid city names
  
- Empty search submissions
  
- Network errors
  
- API request failures

🎯 Learning Objectives

This project helps beginners understand:

- Setting up an Express server
  
- Creating routes with Express
  
- Handling form submissions
  
- Using Axios to consume REST APIs
  
- Working with asynchronous JavaScript (async/await)
  
- Rendering dynamic pages with EJS

  
- Managing environment variables with dotenv
  
- Organizing a Node.js project


Contributions are welcome!
