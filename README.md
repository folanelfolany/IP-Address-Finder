# IP Address Finder
This IP Address Finder app displays your public IP address, approximate location, and internet service provider (ISP) details, along with an interactive map showing your current location.

## Features
* Display IP Address: Shows your current IPv4 address.
* Location Information: Provides details on your approximate city, region, country, and ISP.
* Interactive Map: Centers the map on your location.
## Tech Stack
* React: For the front-end interface.
* IPAPI: API to get IP address and location information.
* Mapbox: For displaying an interactive map.

## Setup Instructions
1. Clone the Repository

```
git clone https://github.com/your-username/ip-address-finder.git
cd ip-address-finder
```
2. Install Dependencies

```
npm install
```
3. Add Mapbox API Key

* In Map.js, replace 'INSERT HERE' with your actual Mapbox API key:
```
const API_KEY = 'YOUR_MAPBOX_API_KEY';
```
4. Run the App

```
npm start
```
5. Open in Browser

Visit `http://localhost:3000` to use the app.
Code Overview
App.js: Handles IP lookup and displays the IP information and Map.
Map.js: Shows an interactive map centered on your location, using the coordinates from IPAPI.
