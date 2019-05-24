# Interactive Google Maps Location Finder

An interactive web application that integrates Google Maps JavaScript API to provide location search, geocoding, and map visualization capabilities.

## Features

- Interactive Google Maps integration
- Location search with autocomplete
- Real-time latitude and longitude display
- City name extraction from location
- Draggable marker for precise location selection
- Responsive design

## Project Structure

- `index.php` - Main HTML file containing the map interface
- `javascript.js` - Contains the Google Maps API integration and functionality
- `style.css` - Custom styling for the map interface
- `jquery-min.js` - jQuery library for DOM manipulation
- `bpopup.js` - Popup window functionality
- `api.png` - API-related image asset

## Setup Instructions

1. Clone this repository to your local machine
2. Ensure you have a web server running (Apache, Nginx, etc.)
3. Copy the project files to your web server's directory
4. Open the application in a web browser

## API Requirements

This project requires a Google Maps JavaScript API key. The API key should be added to the script tag in `index.php`. The current API key is for demonstration purposes only and should be replaced with your own API key.

## Usage

1. Enter an address in the search box
2. The map will automatically center on the location
3. The latitude and longitude will be displayed in real-time
4. The city name will be automatically populated
5. You can drag the marker to adjust the location

## Technologies Used

- Google Maps JavaScript API
- HTML5
- CSS3
- JavaScript
- jQuery

## Browser Compatibility

The application is compatible with modern browsers including:
- Chrome
- Firefox
- Safari
- Edge

## Security Note

For production use, please:
1. Replace the demo API key with your own secure API key
2. Implement proper API key restrictions
3. Consider moving sensitive configuration to a server-side file

## Acknowledgments

- Google Maps JavaScript API
- jQuery
- Bootstrap Popup
