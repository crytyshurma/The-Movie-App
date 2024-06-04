# The Movie App
The app displays 20 most popular movies of the current time. It fetches data from the website *www.themoviedb.org*

## Introduction
TheMoviesApp is an Android application that displays a list of the most 20 popular movies along with their ratings and images. **The app fetches JSON data from *The Movie Database (TMDB)*.

## Features
-Fetches popular movies from *TMDB* in JSON format using an **API key**.
-Converts **JSON to POJO**.
-Uses **retrofit** for **asynchronous call**.
-Displays movie titles and their ratings along with thier images.
-Uses **live data** and **swipe to refresh** to update changes.
-Uses **data binding** for **MVVM architecture**.
-Uses **RecyclerView** for efficient display of movie lists.

## Known Issues
Website Downtime: Currently, ***TMDB's website is down***, causing the app to display a blank white screen. The Logcat shows an error: No adapter attached because the adapter cannot retrieve data from the website.

## Future Improvement: 
Implementing local caching or a fallback mechanism when the API is unreachable would improve user experience.

## Contributing
***Contributions are welcome! Please fork this repository and submit pull requests.***
