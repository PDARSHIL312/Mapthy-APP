# Mapty

Mapty is a web application designed for tracking workouts, whether it's running or cycling. It utilizes the geolocation feature of modern web browsers to pinpoint the user's location on a map, allowing them to log workouts with specific details like distance, duration, and additional metrics depending on the workout type.

##Video

https://github.com/PDARSHIL312/Mapthy-APP/assets/137078389/25e25af0-3360-47b2-84de-dabe8dec53c5

## Features

### 1. Workout Tracking
- **Running Workouts:** Record your running sessions including distance, duration, pace, and cadence (steps per minute).
- **Cycling Workouts:** Log your cycling activities with details such as distance, duration, speed, and elevation gain.

### 2. Geolocation Integration
- **Map Display:** Utilizes Leaflet.js library to display an interactive map where workouts are logged.
- **Click to Add:** Click on the map to add new workouts, pinpointing the exact location where the workout took place.

### 3. User Interface
- **Form-based Input:** Simple form-based interface to input workout details.
- **Toggle Fields:** Toggle between entering cadence/elevation gain based on the workout type (running/cycling).

### 4. Data Persistence
- **Local Storage:** Stores workout data locally in the browser, ensuring that logged workouts persist even after page reloads.

### 5. Interactive Features
- **Workout Popups:** Clicking on a workout on the sidebar or on the map opens a popup with detailed information about that workout.
- **Move to Workout:** Clicking on a workout in the sidebar or list scrolls and zooms the map to the location of that workout.

### 6. Additional Functionality
- **Responsive Design:** Optimized for various screen sizes, ensuring a consistent user experience across devices.
- **Clear All Data:** Option to clear all logged workouts and reset the application.

## Usage

To use Mapty:
1. Open the application in a web browser.
2. Allow the browser to access your location when prompted to enable geolocation features.
3. Click on the map to add a new workout.
4. Fill out the form with details of your workout (type, distance, duration, and optional cadence or elevation gain).
5. Submit the form to log the workout. It will appear on the map and in the sidebar list.
6. Click on a workout in the sidebar or on the map to view detailed information about that workout.

## Technologies Used

- **JavaScript (ES6+):** Core programming language for the application logic.
- **Leaflet.js:** Open-source JavaScript library for interactive maps.
- **HTML/CSS:** Structuring and styling the web interface.
- **LocalStorage API:** Browser API for storing data locally.

## Credits

- **Author:** [Your Name]
- **Course:** [Course Name or Tutorial Source]

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
