# CineMatch
Check out [CineMatch](http://cinematch.s3-website-us-east-1.amazonaws.com/) online! Use FireFox for the best experience.

## Project Description

CineMatch is a movie database where users can explore new movies, search movies, and get detailed information about movies. Users will be able to login/register, add movies to a “Favorites” and a “Want to Watch” list, and also be able to search for movies and post/view reviews.

## Technologies Used

* Java 8
* Spring Frameworks(ORM, Aspects, Context, Beans, Core, webMVC, test) 5.2.12 RELEASE
* Hibernate 5.4.10
* PostgreSQL 42.2.18
* Servlet 4.0.1
* JUnit 4.13.1
* Mockito 3.3.3
* Log4j 1.2.17
* Angular - 11.0.6
* Typescript - 4.1.3
* Material - 11.1.0
* Bootstrap - 4.6.0
* HTML5
* CSS3
* Font Awesome
* TMDB API

## Features

User can: 
* login / logout
* Create an account
* Comment on a movie and delete their comment
* Like a movie and view their liked movies
* Add a movie to watch list and view their list
* View list of random movies, tending movies, and movies to explore
* Search a movie by name

## To-do
* Friend List
* Random Movie Filters (Language, rating, genre)
* Profile Pictures
* UI polish
* Trailer playback
* Interface with third party streaming APIs

## Getting Started

### Backend
1. Make sure you have an IDE and JDK installed.
2. Run `git clone https://github.com/2012JavaReston/MovieApp-BackEnd.git`
3. Run the Driver in src/main/java/com/revature 

From there you should be able to ping the endpoints using the FrontEnd for the project.

### Frontend 
1. Have your environment [set-up](https://angular.io/guide/setup-local) for Angular development
2. Run `git clone https://github.com/2012JavaReston/MovieApp-FrontEnd.git`
3. Run `npm install`
4. Run `ng serve --open`

To connect to a local database:
1. In the MovieApp-FrontEnd, navigate to src/app/services/api.service.ts and change the baseUrl variable to your own local instance of the BackEnd server.
    * Example: private baseUrl = 'http://localhost:8080/MovieApp/api/'


## Usage
Landing: `http://localhost:4200/`

<img style='max-width: 650px' src='https://imgur.com/yJ649VL.png' />

Login: `http://localhost:4200/login`

<img style='max-width: 650px' src='https://imgur.com/48XJZeP.png' />

Register: `http://localhost:4200/register` 

<img style='max-width: 650px' src='https://imgur.com/TswRz4E.png' />

Home: `http://localhost:4200/home`

<img style='max-width: 650px' src='https://imgur.com/OH3ZZ8I.png' />

Search: `http://localhost:4200/search/:movie`

<img style='max-width: 650px' src='https://imgur.com/rIGtYa8.png' />

Liked: `http://localhost:4200/liked`

<img style='max-width: 650px' src='https://imgur.com/7QyAQrR.png' />

Movie Info: `http://localhost:4200/movieInfo/:id`

<img style='max-width: 650px' src='https://imgur.com/OCjg0wa.png' />

Profile: `http://localhost:4200/profile/:username`

<img style='max-width: 650px' src='https://imgur.com/8ccyfuz.png' />

Watch List: `http://localhost:4200/watch`

<img style='max-width: 650px' src='https://imgur.com/oZ5DORL.png' />

## Contributors

Brandon Moore, Anthony McKenzie, Andrew Gee, Mohammad Al Lami, Lester Young, Andrew Gee, Jeff Enriquez, Alec Sherlock, Ryan Murray
