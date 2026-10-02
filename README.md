# Weather Insights

A full-stack weather insights platform integrating real-time weather
data with analysis and interactive visualizations. The application
provides weather predictions, air quality insights, and interactive
dashboards.

## Live Demo

**Deployed Application:** https://weather-insights-cpsm.onrender.com

## Features

-   Real-time weather information
-   Weather predictions and insights
-   Air quality analysis
-   Interactive dashboards
-   Weather data visualization using Chart.js
-   Location-based weather information
-   Responsive web interface

## Tech Stack

-   **Frontend:** HTML, CSS, JavaScript
-   **Backend:** Flask
-   **API:** OpenWeatherMap API
-   **Visualization:** Chart.js
-   **Deployment:** Render

## Architecture

``` text
User
  ↓
Web Interface
(HTML/CSS/JavaScript)
  ↓
Flask Backend
  ↓
OpenWeatherMap API
  ↓
Weather & Air Quality Data
  ↓
Data Processing
  ↓
Chart.js Visualizations
  ↓
Interactive Dashboard
```

## Setup

### 1. Clone the repository

``` bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
cd Weather-Insights
```

### 2. Create a virtual environment

Windows:

``` bash
python -m venv venv
venv\Scripts\activate
```

macOS/Linux:

``` bash
python -m venv venv
source venv/bin/activate
```

### 3. Install dependencies

``` bash
pip install -r requirements.txt
```

### 4. Configure the API key

Create a `.env` file:

``` env
OPENWEATHER_API_KEY=your_api_key_here
```

Never commit the `.env` file or API key to GitHub.

### 5. Run locally

``` bash
python app.py
```

Open `http://localhost:5000`.

## Application Workflow

``` text
Enter Location
      ↓
Flask Request
      ↓
OpenWeatherMap API
      ↓
Weather + Air Quality Data
      ↓
Data Processing
      ↓
Chart.js Visualization
      ↓
Interactive Dashboard
```

## Deployment

The application is deployed on **Render**.

**Production URL:** https://weather-insights-cpsm.onrender.com

Configure the required environment variable on Render:

``` text
OPENWEATHER_API_KEY
```

## Project Highlights

-   Full-stack Flask application
-   Real-time external API integration
-   Weather and air quality data processing
-   Interactive data visualization
-   Production deployment on Render

## Author

**Anand Kumar Pandey**\
B.Tech Computer Science --- Sitare University
