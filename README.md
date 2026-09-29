# Movie Watchlist App

A Flutter movie watchlist application created for CW-02.

## Features

- Displays a scrollable list of movies
- Shows local movie poster images
- Displays movie title and cast information
- Allows users to tap a movie to view its details
- Passes a Movie object from the HomeScreen to the DetailsScreen
- Displays the movie poster, title, cast, and synopsis on the DetailsScreen

## Project Structure

- `lib/models/movie.dart` - Movie data model
- `lib/data/movies_data.dart` - Sample movie data
- `lib/screens/home_screen.dart` - Main movie list screen
- `lib/screens/details_screen.dart` - Movie details screen
- `assets/images/` - Local movie poster images

## Movies Included

- Inception
- The Matrix
- Interstellar
- The Dark Knight
- Parasite

## Navigation

The application uses `Navigator.push()` and `MaterialPageRoute` to navigate from the HomeScreen to the DetailsScreen. The selected Movie object is passed to the DetailsScreen.

## Run the App

```bash
flutter pub get
flutter run