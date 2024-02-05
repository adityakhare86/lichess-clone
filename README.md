# README

It is a single-page web-app, using React.js and Ruby on Rails.

![Evanschess Overview Demo](demos/evanschess.gif)

## Current Functionality Highlights

* Hand-rolled User Authentication using BCrypt
* Single Page Application, using React
* The illusion and convenience of multiple pages using React-Router
* Asynchronous HTTP requests using jQuery's Ajax
* Users can challenge other Users or the Computer
* The chess match board is rotated depending on which side if you are white or black
* Hard AI uses a tree of all possible game outcomes to play a flawless game
* Leave current game at anytime and come back later to replay the game; every submitted move is saved to the db
* Users can undo previously made moves
* Spectators can currently only visit the game by its link, but once there they can spectate the game live and will not be able to interact with the board in any way to affect the match
* Users can open any previous game, to view the ending state of the game, and will eventually be able to scroll over the board see the game progression
* Users can post on the forums to discuss their thoughts or review their chess games, will be eventually able to directly post   a chess game to the forum
* A queuing system using redis so that users can look for games against each other
* The ability to directly challenge other users to games by using the "challenge a friend" form
* Users can edit only their posts if they wish to
* Users can read blog posts on the website via the the all index or by year and fetch more using infinite scrolling
* Users can search for other users in the nav search bar, which will bring the user to a profile page
* Users can search the forums for forum posts that have an author, title, or comment which contains that keyword
* Posts, comments, and blogs are all paginated so that the user is not overwhelmed with data
