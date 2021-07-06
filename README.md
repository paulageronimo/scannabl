Original App Design Project - scannbl
===

# scannbl

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
Scannbl helps find the nearest, and/or best priced item you are searching for right at your fingertips. With a simple barcode scan, several stores near you with the item on stock appear

### App Evaluation
[Evaluation of your app across the following attributes]
- **Category:** Shopping
- **Mobile:** primarily mobile, but web version allows to view saved items/locations; push notificaitons, uses mobile phone camera to scan barcode, location 
- **Story:** Users can find and compare prices on items by scanning its barcode; they could bookmark items/locations into lists, either private or public
- **Market:** Tourists, chefs, couponers, the dietary restricted, frugal living, anyone who would like to locate the nearest or best priced item of interest
- **Habit:** Users can track the prices of their saved items, encouraging them to create a profile and keep an eye out to find the best buy
- **Scope:** mid to narrow scoped due to its main purpose to serve and provide the prices by location

## Product Specs

### 1. User Stories

**Required Must-have Stories**

* Scan item
* View cheapest price
* View locations where item is available
* User profiles (logging in, account creation)
* Lists/bookmarks page
* Product reviews, crowdsourcing alternatives (?)
* Settings: default location, radius, *store preferences*

**Optional Nice-to-have Stories**

* Crowdsourcing to verify prices
* Search for similar/alternative items
* List/bookmarks can be private or public
* Niche pages (Italian cooks/recipe items in the Bronx, Mexican tourists in Sydney, Australia, Kosher food items in Boise, Idaho)

### 2. Screen Archetypes

* Create account 
   * User can create an account through email/phone#/appleID
* Log in
   * logging in via the way they created the account
* Location
    * It will ask the user to provide their location (or A location)
* Search
   * Scan barcode with the camera, this will search through products using the unique barcode
   * Search results will pop up listing the prices (Sort: location, price)
* Map View
   * Pin-points of the stores by color (orange: general locations; green: cheapest price in n mile radius; maroon: nearest location where the product is; gold: nearest happens to be the cheapest priced)
* Stream
   * User can scroll and pinch through the map to view locations
   * User can scroll through the list of automatically sorted by distance of the several marked items
   * Once in detailed view of the item at the location, they can view alternate items found based on product keywords
* Creation
   * Create lists/bookmarks page of items/locations saved


### 3. Navigation

**Tab Navigation** (Tab to Screen)

* search
* compare
* profile/bookmarks

**Flow Navigation** (Screen to Screen)

* Create a Profile Screen
    * => Home
* Log in Screen
    * => Home
* Location Preferences
    * Pop-up to allow location tracking
    * Either if the user allows or not, they have the option to manually input their location
    * => Home
* Search (home)
   * Start to scan... *or upload a scannbl (pun intended) picture*
   * => Map View / Stream
* Map View
    * 📍 pins on maps
    * Scroll up to view the stream, click on the pins to view stream
    * => stream
* Stream
    * View items, more info on the item
    * => Details
    * => Add to Bookmarks/Lists
    * => Profile
* Creation (Bookmarsk Lists)
    * View saved items
    * => Profile

## Wireframes
- [QUICK STREAM SKETCH](https://imgur.com/a/Sv4rqTc)
![og-sketch](https://user-images.githubusercontent.com/41409758/124549678-81424380-ddfd-11eb-9103-d63517d6d7a5.jpeg)
-[QUICK SAVED ITEMS SKETCH](https://i.imgur.com/cf17ekM.jpeg)

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
