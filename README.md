# README for "Food Finder" Project

## Project Overview
"Food Finder" is a web-based application that displays popular restaurants ("matjips") on a map. It allows users to view information about these restaurants and mark them as favorites. The application includes a scraping script to gather data about the restaurants from the web.

### Features
- **Interactive Map:** Displays restaurant locations on a map using the Naver Maps API.
- **Restaurant Information:** Shows details about each restaurant, including its name, address, and category.
- **Like Functionality:** Users can like or unlike restaurants, with this preference reflected in real-time on the map.
- **Data Scraping:** Includes Python scripts to scrape restaurant data from the web and populate the database.
- **Responsive Design:** The application uses Bootstrap for a responsive layout, ensuring compatibility with various devices.

### Technology Stack
- **Frontend:** HTML, CSS, JavaScript, Bootstrap for responsive design.
- **Backend:** Python with Flask for server-side logic.
- **Database:** MongoDB for storing restaurant data and user preferences.
- **Data Scraping:** Python with Selenium and BeautifulSoup for web scraping.
- **Mapping:** Naver Maps API for displaying restaurant locations on a map.

### Setup and Installation
1. **Clone the Repository:** Get the project files from the source repository.
2. **Install Dependencies:** Install necessary Python packages (Flask, pymongo, Selenium, BeautifulSoup) and set up MongoDB.
3. **Configure Database:** Configure MongoDB with appropriate credentials.
4. **Run the Scraping Scripts:** Execute the scraping scripts to populate the database with restaurant data.
5. **Start the Server:** Run `app.py` to start the Flask server.
6. **Access the Application:** Open a web browser and navigate to the specified address (usually `localhost:5000`).

### Usage
- **Viewing Restaurants:** Open the application to view the restaurants displayed on the map.
- **Liking a Restaurant:** Click on a restaurant marker to like or unlike it.
- **Refreshing Data:** Use the provided buttons to refresh the restaurant data or load more information.
