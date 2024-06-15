# Dynamic Map Interface with Mapbox GL JS

This repository contains a simple HTML file that demonstrates a dynamic map interface using Mapbox GL JS. The map's appearance, center coordinates, and location can be controlled through URL parameters.

## Features

- **Dynamic Map Styling**: Customize the map style by specifying `mapstyle` parameter in the URL (`streets` for street view, `satellite` for satellite view).
- **Initial Center Coordinates**: Define the initial center of the map using `lat` (latitude) and `lng` (longitude) parameters in the URL.
- **Location Search**: Search for a location dynamically using the `search` parameter in the URL.

## Usage

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/your-repository.git
   cd your-repository


## URL Parameters:

### You can customize the map's appearance by adding parameters to the URL:
#### mapstyle: Specify the map style. Options are streets (default) or satellite.
#### lat: Latitude of the initial center position.
#### lng: Longitude of the initial center position.
#### search: Enter a location to search dynamically.

## Examples:

#### Basic Usage (Default Street Map):
file:///path/to/index.html

#### Satellite Map with Specific Coordinates:
file:///path/to/index.html?mapstyle=satellite&lat=40.7128&lng=-74.0060

#### Search for a Location:
file:///path/to/index.html?search=New%20York%20City

#### Example URL from the provided link:
https://free2510.github.io/map-interface/index.html?mapstyle=streets&lat=40.7128&lng=-74.0060



### Notes:
- Replace `https://github.com/your-username/your-repository.git` with the actual URL of your GitHub repository.
- Provide clear instructions on cloning the repository, customizing the map through URL parameters, and obtaining the necessary Mapbox access token.
- Ensure users understand how to manipulate map appearance and behavior using the provided URL examples (`mapstyle`, `lat`, `lng`, `search`).

This README template provides comprehensive guidance on setting up and using your dynamic map interface project, making it easy for users to get started and customize their map viewing experience. Adjust the content further based on additional features or specific details of your project.

