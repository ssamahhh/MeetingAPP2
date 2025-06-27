# Meeting Calculator Script
This script calculates if a user will arrive on time or late to a meeting based on travel time.

## How it works
- Takes user input: name, current time, meeting time, user location, meeting location.
- Uses OpenRouteService to calculate travel time between two locations.
- Uses Geopy to convert locations to coordinates.
- Outputs whether the user is "on time" or "delay" with minutes late
