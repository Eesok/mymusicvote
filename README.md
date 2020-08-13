# mymusicvote

## Project Description

A video player app that shows a variety of youtube videos that users can vote/rank. The app will display the videos dynamically based on the rankings of the users. Our main page will be a list of music videos,  but the user will have an option to sort/filter the videos based on various rankings and/or categories. 

### Wireframes

![Wireframe](https://i.imgur.com/djkGImV.jpg)


### MVP User Stories

_**MVP User Stories**_

- _As a user I would like to have the videos displayed on the main page._
- _As a user I would like to be able to cast my vote or ranking on each of the videos._
- _As a user I want to be able to sort/filter the videos according to preference._
- _As a user I would like to be able to play the videos._
- _As a user I would like to be able to share videos I see on the site to my friends._
- _As a user I would like to be able to have a reactive and easy navigation tool on the site._
- _As a user I would like to have a clean/nice user experience that looks aesthetically pleasing._
- _As a user I would like to have a separate page/component to play each video on it’s own._
- _As a user I would like to have a search functionality to find videos I like._


_**Post MVP Stretch Goals**_
- _As a user I would like to be able to have my own profile and login to keep my collection and “liked” videos._
- _As a user I would like to be able to save the videos I like to my own personal collection._
- _As a user I would like to be able to comment on the videos to discuss rankings._
- _As a user I would like to have the video input limited and/or restricted to certain content._

#### OPTIONAL Component Details
| Models | Content | Type
| --- | --- | :---: |
| Video | title: String, url: String, votes{up: Number, down: Number}, genre: String, upvoted: {ref: 'User', type: mongoose.Schema.type.ObjectId} | MVP |
| User | name: String, upvotes: {ref: 'Video', type: mongoose.Schema.type.ObjectId} | Stretch |
