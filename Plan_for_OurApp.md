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
This apps allow you to keep track of the episodes you have seen from your favorite anime and/or the chapters you have read of your favorite manga by providing you with checklists of all the anime episodes per season and/or all the manga chapters. Furthermore, this app provides a place called 'fandom' where you can post anything you want or see other people's posts related to a specific anime/manga.

### App Evaluation
- **Category:** Personal Logs / Entertainment
- **Mobile:** This app will be primarly developed for smartphones, but could be extended to computers and even TV systems. 
- **Story:** Provides full checklists for users to keep track of the anime episodes or manga chapters they have seen. In addition, allows users to share posts related to a specific anime/manga for other user to see. 
- **Market:** This app isn't limited to a specific audience. Any manga or anime fan is welcome to use it!
- **Habit:** This app's use will vary according to the users tendencies of reading manga or watching anime. Some users like to watch/read daily so they will use it more. Other users, such as those all-caught in the animes or mangas watch/read only when new episodes/chapters come out (could be weekly or monthly). 

- **Scope:** First this app will only focus on helping users track the episodes they have watched or chapters they have read, and provide them a place to share posts related to the anime/manga. Aside from posts, the users can't really interact with one another, so a potential addition could be comments on posts, and even allowing users to send private messages among eachother. 

## Product Spec

### 1. User Stories (Required and Optional)
**Required Must-have Stories**

* Logging screen for users, with option to create a new account
* User should be able to add anime or manga to their home screen using the search screen. 
* User should be able to switch betweeen anime and manga in home screen.
* When user click on an anime from home screen, season options should appear for each season of the anime. 
* When user click on a season, they should see a list of all the episodes and their titles with an option to markoff. 
* When user click on a manga, a check list of all the manga chapters should appear with their title and the option to mark off. 
* In the FANDOM screen, the user should see FANDOM option related to the anime/manga they have on their home screen.
* In the FANDOM screen, the user should be able to scroll through other user posts.
* In the FANDOM screen, the user should be able to make a new post and see it on the thread of posts.
* In the search screen the user should be able to see a list of different anime/manga and have the option to add it to their favorites list.
* In the setting screen the user should be able to log off. 
* User should be able to backtrack between screens.
* User should be able to log off and log in and keep their settings the way they were and their checklists too. 

**Optional Nice-to-have Stories**
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
   * Allows switching between the manga and anime favorites list. 
   * Allows user to click on an anime or manga and pop up new screens for episodes or chapters.

* Home Screen  - click on an anime
  * Provides a list of season for the anime selected
  * After choosing a season provides a list of th episodes from that season for the user to mark off

* Home Screen - click on a manga
  * Provides a list of chapters for the user to markoff.

* Fandom Screen
   * Allows user to select which FANDOM they want to go into.
   * Allows user to see a thread of post from other users for the FANDOM they picked.
   * Allows user to make a post and share it on the FANDOM thread of posts.
    
* Search Screen
   * Allows switching between the manga and anime titles lists. 
   * Allows users to click on an anime, and have the option to add to their favorites list on their home screen. 
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
   * HOME -> ANIME -> SEASONS LIST -> SEASON'S EPISODES CHECKLIST
   * HOME -> MANGA -> MANGA CHAPTERS CHECKLIST
* FANDOM 
   * FANDOM -> SELECTED ANIME/MANGA FANDOM PAGE
   * FANDOM -> SELECTED ANIME/MANGA FANDOM PAGE -> CREATE A POST -> SELECTED ANIME/MANGA FANDOM PAGE

* SEARCH 
   * SEARCH -> ANIME TITLES LIST -> SELECTED ANIME's DESCRIPTION
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
