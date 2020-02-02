# Flix

Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).


## Flix Part 2

### User Stories

#### REQUIRED (10pts)
- [x] (5pts) User can tap a cell to see more details about a particular movie.
- [x] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [ ] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [ ] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthough GIF

<a href="https://gifyu.com/image/qf6Z"><img src="https://s5.gifyu.com/images/Flix2.md.gif" width=250><br>

### Notes
Describe any challenges encountered while building the app.

For part 2, the hardest part was getting the cells to appear correctly formatted in the Collection View grid. For me, the cells weren't appearing like how I laid them out on my storyboard. I fixed the issue after looking up the problem in the discussion and saw to align them using the autoresizing arrows.
---

## Flix Part 1

### User Stories

#### REQUIRED (10pts)
- [x] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [x] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [x] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [ ] (2pt) User can view the app on various device sizes and orientations.
- [ ] (1pt) Run your app on a real device.

### App Walkthough GIF

<a href="https://gifyu.com/image/qglr"><img src="https://s5.gifyu.com/images/Flixddc3bfb6b9860320.md.gif" alt="Flixddc3bfb6b9860320.gif" border="0" /></a>

### Notes
Describe any challenges encountered while building the app.

Since I was using XCode 8, I had the hardest time with the compatibility of AlamofireImage dependency. I ended up having to just upgrade my MacOS and getting XCode 11 to solve everything with that issue. Also, getting Cocoapods to work was hard as well.
