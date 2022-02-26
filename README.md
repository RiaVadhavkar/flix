# Flix

Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

📝 `NOTE - PASTE PART 2 SNIPPET HERE:` Paste the README template for part 2 of this assignment here at the top. This will show a history of your development process, which users stories you completed and how your app looked and functioned at each step.

---

## Flix Part 1

### User Stories

#### REQUIRED (10pts)
- [x] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [x] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [x] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [ ] (2pt) User can view the app on various device sizes and orientations.
- [x] (1pt) Run your app on a real device.

### App Walkthrough GIF
Simulator: https://submissions.us-east-1.linodeobjects.com/ios_university/CI-rySUH.gif

iPhone: https://i.imgur.com/ht53VUW.gifv

### Notes
Describe any challenges encountered while building the app.

I encountered two errors:
1. This class is not key value coding-compliant for the key tableView
2. Unexpectedly found nil while implicitly unwrapping an Optional value

I fixed them by:
1. Checking the 'Inherit Module From Target' checkbox
2. Remapping the tableView outlet
