#Changes for v1

##Style the campgrounds page
* Add a better header/title
* Make campground display in a grid

##Style the Navbar and Form
* Add a navbar to all templates
* Style the new campground form

#Changes for v2

##Add Mongoose
* Install and configure mongoose
* Setup campground model
* Use campground model inside of routes

##Show Page
* Review the RESTful routes we've seen so far
* Add description to campground model
* Show db.collection.drop()
* Add show/route template

#Changes for v3

##Refactor Mongoose Code
* Create a models directory
* Use module.exports
* require everything correctly!

##Add Seeds File
* Add a seeds.js file
* Run the seeds file every time the server starts

##Add the Comment Model
* Make errors go away
* Display comments on campground show page

#Changes for v4

##Comment New/Create
* Add the comment new and create routes
* Add the new comment form

#Changes for v5

##Style Show Page
* Add sidebar to show page
* Display comments nicely

##Finish Styling Show Page
* Add public directory
* Add custom stylesheet

#Changes for v6

##Add User Model
* Install packages needed for auth
* Define User model

##Register
* Config Passport
* Add register routes
* Add register template

##Login
* Add Login routes
* Add Login template

##Logout/Navbar
* Add logout route
* Prevent user from adding comment if not signed in
* Add links to navbar
* Show/hide auth links correctly

##Show/hide links
* Show/hide auth links in navbar correctly

#Changes for v7

##Refactor the routes
* Use Express router to reorganize all routes

#Changes for v8

##Users + Comments
* Associate users and comments
* Save author's name to a comment automatially

#Changes for v9

##Users + Campgrounds
* Prevent an unauthenticated user from creating a campground
* Save username+id to newly created campground

#Changes for v10

##Editing Campgrounds
* Add Method-Override
* Add Edit Route for Campgrounds
* Add link to Edit page
* Add Update route

##Deleting Campgrounds
* Add Destroy route
* Add Delete button

##Authorization
* User can only edit his/her campgrounds
* User can only delete his/her campgrounds
* Hide/Show edit and delete buttons

##Editing Comments
* Add Edit route for comments
* Add Edit button
* Add Update route

##Deleting Comments
* Add Destroy route
* Add Delete button

##Authorization Part 2: Comments
* User can only edit his/her comments
* User can only delete his/her comments
* Hide/show Edit and Delete buttons
* Refactor Middleware

#Changes for v11

##Adding in Flash
* Install and config connect-flash
* Add bootstrap alerts to header