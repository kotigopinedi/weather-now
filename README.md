Weather Now 🌦️
A simple weather application to help users check the current weather conditions for any city quickly. Built with React.js (using Vite) and powered by the Open-Meteo API.

Features
🌍 Search for any city and get real-time weather information.
🌡️ Displays current temperature, wind speed, and weather condition.
❌ Error handling for invalid city names or API issues.
🔄 Clean and intuitive user interface.

Tech Stack
Frontend: React.js (Vite)
API: openweathermap API
Styling: CSS


Getting Started
Follow the steps below to set up the project locally.

1. Clone the Repository

   git clone https://github.com/your-username/weather-now.git
   cd weather-now

2. Install Dependencies
   Ensure you have Node.js installed. Then run:
   
   npm install

3. Start the Application
   
   npm run dev

   The app will be available at the local development server (e.g., http://localhost:5173).


Deployment

The application is live! 🎉

Link: https://github.com/kotigopinedi/weather-now


How It Works

Enter the name of the city in the search bar.
The app fetches the city’s geographical coordinates using the Open-Meteo API.
It retrieves the current weather details and displays them.


Project Structure

weather-now/
│
├── public/                 # Static assets
├── src/
│   ├── components/         # React components
│   │   ├── SearchBar.jsx   # Handles city search
│   │   └── WeatherInfo.jsx # Displays weather details
│   ├── App.jsx             # Main application file
│   ├── App.css             # Application styling
│   └── main.jsx            # React entry point
│
└── README.md               # Project documentation


API Information

OpenWeatherMap API: https://api.openweathermap.org/data/2.5/weather?q=${city}&units=metric&appid=${KEY}

Acknowledgments
Vite
React.js
OpenWeatherMap API

Enjoy using Weather Now! 🌞





