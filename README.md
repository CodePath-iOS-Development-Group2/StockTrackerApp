# StockTracker 

Original App Design Project - README Template
===

# StockTracker App

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
[Description of your app]

An iOS mobile app that allows users to track their favorite stocks. 

StockTracker makes it easy to follow your foavorite stocks. View quotes and daily performance in a customizable watchlist, and tap any ticker to see an interactive chart and key details about perormance. StockTracker also includes business news from top publications around the world.


# Features


*Watchlist*

• Customize your watchlist with stocks, indexes, mutual funds, ETFs, currencies, and more.

• View price quotes and tap to toggle between price change, percentage change, and market capitalization.

• Color-coded sparklines let you easily track stock performance throughout the day.


*Charts and details*

• Tap any ticker in your watchlist to see price charts for day, week, month, and multi-month periods.

• Touch the chart with one finger to see the price at a specific date or time, or touch with two fingers to view price change over time.

• View key details including after-hours price, trading volume, EPS, and more.


*Business News*

• Read Top Stories selected by Apple News editors for the latest news driving the market.*

• Read and watch stories about the companies you follow, from a select group of top-rated business publications, selected using the same machine learning as Apple News.*

• Apple News+ subscribers see Apple News+ stories right in StockTracker.*


### App Evaluation
[Evaluation of your app across the following attributes]
- **Category:** Travel
- **Mobile:** Mobile is the primary point of access to information when traveling.
- **Story:** Flight tracking allows travelers to track theirs and others' flights in a stress-free way. 
- **Market:**  Any travelers and those dropping them off / picking them up to know whether a flight has landed or is on schedule.
- **Habit:** Frequent travelers share their whereabouts with their friends and family. 
- **Scope:** Flight tracking allows travelers and those responsible for picking them up and dropping them off accordingly to know the  status of the respective flights in order to schedule their commute.  

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**
  
* User does not need to login and can continue as guest 
* User can view their flight information by searching flight number in the search bar. 
* User can share their flight status. 
* User can find nearby resturants in their landed destination. 
* User can find nearby hotels in their landed destination. 

**Optional Nice-to-have Stories**

* User can create a new account 
* User can login 
* User can see the weather of departing and arrival locations. 
* User can see the type of aircraft for the specific flight. 
* User can see the time zone of their arrival location. 
* User can see where their seats are located on the aircraft. 
* User can track flight live in a 3D globe map. 
* User can find things to do in their arrival location. 
* User can make transportation and hotel reservation. 
* User can know when their hotel room / Airbnb is ready.   

### 2. Screen Archetypes


* MyFlight Screen
   * User can search their flight information by searching flight number (User can expand information about flight details)
   * User can see all the optional stories (weather, aircraft type, time zone change, seating, live view of the aircraft on a 3D globe map)  

 
* Resturants Nearby
   * User can find nearby resturants in their landed destination.
   

* Resturants Nearby Expanded Details Screen
   * User can call, request directions, view reviews, and menu of resturants. 
   * User can make reservations the resturants , if appicable. (Optional)

* Hotels Nearby
   * User can find hotels in their landed destination. 

* Hotels Nearby Expanded Details Screen
   * User can call, visit site, request directions, and make reservations at the hotels. 
   * User can be notified when their hotel room / Airbnb is ready. (Optional)


### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Home Feed (MyFlight)
* Resturants Nearby
* Hotels Nearby

**Flow Navigation** (Screen to Screen)

* Home Feed (MyFlight)
* Resturants Nearby
* Hotels Nearby

## Wireframes
[Add picture of your hand sketched wireframes in this section]



<img src= "https://imgur.com/F65fYID.gif" width=600>




## Schema 
[This section will be completed in Unit 9]
### Models
Post

<img src= "https://imgur.com/cXdhmKw.gif" width=600>





### Networking
- [Add list of network requests by screen ]

<img src= "https://imgur.com/UtS3bup.gif" width=600>

- (READ/GET) Fetch posts for a user's nearby restaurants.
- (READ/GET) Fetch posts for a user's nearby hotels.
- (READ/GET) Fetch flight information for user.

### Sprint Planning

https://github.com/CodePath-iOS-Development-Group2/FlightTrackingApp/projects?type=beta

- [x] Sprint Plan in place using GitHub project management flow.
    - [x] GitHub Project created (1pt)
    - [x] GitHub Milestones created (1pt)
    - [x] GitHub Issues created from user stories (2pts)
    - [x] Issues added to project and assigned to specific team members (1pt)
- [x] Updated status of issues in Project board (2pts)
- [x] Sprint planned for next week (Issues created, assigned & added to project board) (3pts)
- [x] Completed user stories checked-off in README (2pts)
- [x] Gifs created to show build progress and added to README (3pts)

<img src="https://media.giphy.com/media/1VAcxgWY1pklqZKzrQ/giphy.gif" width=550><br>
<img src="https://media.giphy.com/media/hlFG7fFu7QpHOI8mSX/giphy.gif" width=550><br>

