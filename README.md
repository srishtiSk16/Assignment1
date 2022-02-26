# Flix
Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).


## Flix Part 1

### User Stories
A user story is a way to capture requirements for an app from an end-user perspective. It is a common practice in app development and helps to simplify the way requirements are specified.

#### REQUIRED (10pts)
- [ x] (10pts) User can view a list of movies (title, poster image, and overview) currently playing in theaters from the Movie Database API.

#### BONUS
- [ ] (2pts) Views should be responsive for both landscape/portrait mode.
   - [x ] (1pt) In portrait mode, the poster image, title, and movie overview is shown.
   - [ x] (1pt) In landscape mode, the rotated alternate layout should use the backdrop image instead and show the title and movie overview to the right of it.

- [ x] (2pts) Display a nice default [placeholder graphic](https://guides.codepath.org/android/Displaying-Images-with-the-Glide-Library#advanced-usage) for each image during loading
- [ x] (2pts) Improved the user interface by experimenting with styling and coloring.
- [x ] (2pts) For popular movies (i.e. a movie voted for more than 5 stars), the full backdrop image is displayed. Otherwise, a poster image, the movie title, and overview is listed. Use Heterogenous RecyclerViews and use different ViewHolder layout files for popular movies and less popular ones.

### App Walkthough GIF

<img src="https://github.com/srishtiSk16/Assignment1/blob/main/app/src/main/res/drawable-v24/walkthrough2%20gif.gif" width=250><br>

### Notes
Great Experience, Had some issues connecting with the API, but fixed it!!

### Open-source libraries used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Androids
