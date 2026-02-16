
# 🌦️ Python Weather App

A Python-based Weather Application that fetches **real-time weather data** using a public Weather API.
The app displays important weather details such as:

 Temperature
 Humidity
 Wind Speed
 Weather Condition
 City Name

 Description

This project is a simple yet powerful weather application built with Python.
It allows users to enter any city name and retrieve live weather information instantly using an external API.

The goal of this project is to demonstrate:

* Working with APIs in Python
* Handling JSON data
* Making HTTP requests
* Error handling
* Clean and readable output formatting

---

##  Features

* Fetches real-time weather data
* Supports any city worldwide
* Displays temperature in Celsius (or Fahrenheit if configured)
* Shows humidity and wind speed
* Displays weather conditions (Clear, Rainy, Cloudy, etc.)
* Simple and user-friendly interface

---

##  Technologies Used

* Python 3
* `requests` library
* Weather API (e.g., OpenWeatherMap API)

---

##  Installation

1️ Clone the repository:

```bash
git clone https://github.com/your-username/weather-app.git
```

2️ Navigate to the project folder:

```bash
cd weather-app
```

3️ Install required dependencies:

```bash
pip install requests
```

---

##  API Setup

1. Go to a weather API provider (e.g., OpenWeatherMap).
2. Create a free account.
3. Generate your API key.
4. Replace `"YOUR_API_KEY"` in the Python file with your actual API key:

```python
api_key = "YOUR_API_KEY"
```

---

## How to Run

```bash
python weather_app.py
```

Then enter the city name when prompted.

Example:

```
Enter city name: London
```

Output:

```
City: London
Temperature: 18°C
Humidity: 65%
Wind Speed: 5 m/s
Condition: Cloudy
```

---

##  Project Structure

```
weather-app/
│
├── weather_app.py
├── README.md
└── requirements.txt (optional)
```

---

##  Error Handling

* Handles invalid city names
* Handles API request errors
* Displays user-friendly error messages

---

##  Future Improvements

* Add GUI (Tkinter / PyQt)
* Add 5-day forecast
* Add weather icons
* Add unit toggle (°C / °F)
* Deploy as a web app using Flask

---

##  License

This project is open-source and available under the MIT License.

---

##  Author

Your Name
GitHub: [https://github.com/your-username](https://github.com/your-username)

---

If you'd like, I can also:

* Improve this README to look **more professional**
* Add badges (Python version, license, etc.)
* Create a `requirements.txt`
* Help you convert this into a GUI version
* Help you deploy it online 
