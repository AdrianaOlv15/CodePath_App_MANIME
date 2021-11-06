Original App Design Project - README Template
===

# MANIME

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
This apps allow you to keep track of the chapters you have read of your favorite manga by providing you with checklists of all the manga chapters. Furthermore, this app provides a place called 'fandom' where you can post anything you want or see other people's posts related to a specific manga.

### App Evaluation
- **Category:** Personal Logs / Entertainment
- **Mobile:** This app will be primarly developed for smartphones, but could be extended to computers and even TV systems. 
- **Story:** Provides full checklists for users to keep track of the manga chapters they have seen. In addition, allows users to share posts related to a specific manga for other user to see. 
- **Market:** This app isn't limited to a specific audience. Any manga or anime fan is welcome to use it!
- **Habit:** This app's use will vary according to the users tendencies of reading manga. Some users like to read daily so they will use it more. Other users, such as those all-caught in the manga read only when new chapters come out (could be weekly or monthly). 

- **Scope:** First this app will only focus on helping users track the chapters they have read, and provide them a place to share posts related to the manga. Aside from posts, the users can't really interact with one another, so a potential addition could be comments on posts, and even allowing users to send private messages among eachother. 

## Product Spec

### 1. User Stories (Required and Optional)
**Required Must-have Stories**

* Login Screen
	* User can enter username and a password 
	* User can access their account by clicking ‘log in’ , if the account exist
  * User can create an account by clicking ‘create account’ , if the account does not exist

* Home Screen 
	* Shows the users favorite mangas as buttons
  * User can scroll if there’s multiple mangas in the screen
  * If the user clicks on a manga button, it should bring the ‘Manga Chapters Checklist’ for the selected manga

* Manga Chapters Checklist
	* Shows a full list of all the manga chapters related to the manga selected by the user
	* Each chapter is followed by a check icon that can be pressed by the user + changes!

* Fandom Screen
	* Shows ‘fandom’ buttons related to each of the user favorite mangas (on main screen)
  * User can scroll if there’s multiple ‘fandom’ buttons in the screen
  * If the user clicks on a ‘fandom’ buttons, it should bring the ‘Fandom Feed Screen’ for the selected manga

* Fandom Feed Screen
  * Shows post made by other people on this fandom feed
  * Shows a button for user to make a post
  * Brings a fragment up for user to make a post if button is clicked - user can enter text and image to publish

* Search Screen
	* Should show a list of many manga titles in alphabetical order (they act like buttons)
  * User can scroll if there’s multiple ‘title’ buttons in the screen
  * If the user clicks on a ‘title’ button, it should bring the ‘Manga Overview Screen’ for the selected tile

* Manga Overview Screen
	* Shows a picture of the 1st volume of the selected manga title  
  * Shows the description of the selected manga title
  * Shows a button for the user to add this manga as a favorite  (if they don’t have it)

* Setting Screen
	* Shows the user’s username
	* Shows the user’s profile picture
	* Shows a logout button (if clicked takes you back to the login screen) 

**Optional Nice-to-have Stories**
	* Having the same sections for Search and Main Screen but for anime!
  * Having the 'additional content section' for both anime and manga where user can see check lists for additional content outside the anime and the manga such as movies, ovas, light novels, special chapters. 
  * Allowing the user to change their username and profile picture.
  * Allosing the user to delete anime/manga of their list.
  * Having a wide range of anime and manga options for user to add to their favorites. 
  * Allowing the user to not have to scroll down to the checklist place their left off. 
  * Providing the actual titles of episodes and chapters. 



### 2. Screen Archetypes
* Login Screen
   * Allows user to log into their account
   * Allows user to create a new account

* Home Screen 
   * Allows user to click on a manga and pop up new screen for chapters.

* Home Screen - MANGA click
  * Provides a list of chapters for the user to markoff.

* Fandom Screen
   * Allows user to select which FANDOM they want to go into.
   * Allows user to see a thread of post from other users for the FANDOM they picked.
   * Allows user to make a post and share it on the FANDOM thread of posts.
    
* Search Screen
   * Allows users to click on a manga, and have the option to add to their favorites list on their home screen. 

* Settings Screen
   * Allows the user to log off their account
  

### 3. Navigation
**Tab Navigation** (Tab to Screen)

* HOME
* FANDOM
* SEARCH
* SETTINGS

**Flow Navigation** (Screen to Screen)

* HOME 
   * HOME -> MANGA -> MANGA CHAPTERS CHECKLIST
  
* FANDOM 
   * FANDOM -> SELECTED MANGA FANDOM PAGE
   * FANDOM -> SELECTED MANGA FANDOM PAGE -> CREATE A POST -> SELECTED MANGA FANDOM PAGE

* SEARCH 
   * SEARCH -> MANGA TITLES LIST -> SELECTED MANGAS's DESCRIPTION

* SETTINGS 
   * SETTINGS -> LOG IN SCREEN (if the user chooses to log off)

## Wireframes]
<img src="https://github.com/AdrianaOlv15/CodePath_OurApp/blob/ac72dd7356a723ea88db6a5004146e8ed54a376d/app-wiredframes-1.jpg" width=600>

### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Schema 
[This section will be completed in Unit 9]
### Models
[Add table of models]
### Networking
- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
