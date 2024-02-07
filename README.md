# Weather and Wellness

This repository is for a Weather Health website for MIST 353 at WVU. The purpose of the website is to utilize real time and future weather data to inform users what health conditions may be at risk due to the weather based on a chosen location, and the things they can do to safely prepare themselves for it, as told by health professionals.
<br/>
<br/>
# Status and Page Overview

As of February 6th 2024, the websites current functionality includes a protoype for the Main, Today Report, Future Report, and About Me pages.
<br/>
<br/>

# Current functionality and future enhancements
Information about the current functionality of each page and the plan for it moving forward

## Main Page

The main page is the first page that is opened. This page includes a title, a search bar (not yet in use) for your desired location, and a directory to other pages.

- The main will utilize the search bar to store geolocation data in order to use the weather data for that location in the Today/Future Pages.
<br/>

## Today / Future pages

These pages are currently identical and are comprised of the layout of the page using cards. They have return buttons to the main pages. The today page will return information about today, and the future will return information based on the dates selected for those dates.

- These pages will utilize the results of the search bar on the main page to return the weather for those location(s), and inform you what health conditions will be at risk, and what you can do to prepare yourself.
<br/>

## About Me page

- This page will contain information about how the website works and include a FAQ.
<br/>

# Research Summary

Research was done to find similar websites and repositories to find information and generate ideas for this project, which are all listed below.
<br/>
<br/>
**Website 1: CDC Climate and Health Effects**
Government website about how the climate affects our health
- Utilizes Boostrap alongside table creations
- Uses !important within the CSS to add precedence
- Some code is struck out, possibly indicating code that is no longer relevant
- Includes classes to contain environment data, specifically
<br/>
<br/>
Website 2: Arthritis.org
Website about how the climate effects arthritis

- Utilizes Boostrap for table themselves
- Includes selectors for clearing textboxes and displaying certain colors when the user is inactive
- Combined different photos on the page to create emphasis on those images
<br/>
<br/>
Website 3: AirNow
Website about air quality and its affects

- Utilized data-animation and data-visible tags to create dynamic elements to the page
- Large use of buttons that filter visibility on varous objects
- Adobe imported font via CSS
<br/>
<br/>
Repository 1: weather_app by sharada-marashina
Repository of an app to display weather

- README is organized well with a clearly stated purpose
- Provides a table of contents for each navigation
- Provides a demo
- Emphasis on how to use the app to avoid confusion
<br/>
<br/>
Repository 2: WeatherApp by prabhsingh13
Repository of a weather app with forecasts 

* README starts with a bulleted list of app features
* Tutorial on how to install the app
* Includes important information that the API key must be changed to be used properly

# Citations

Bootstrap, CSS, and Images were utiliized from outside sources.

CSS Utilized from W3 Schools
Search Bar/Input Button That Utilizes a Image to Seach
https://www.w3schools.com/bootstrap/tryit.asp?filename=trybs_form_input_group_btn&stacked=h 
<br/>
<br/>
Lists
https://www.w3schools.com/html/html_lists_ordered.asp

Bootstrap used from Bootswatch
https://bootswatch.com/morph/

Flaticon
A flaticon was used from <a href="https://www.flaticon.com/free-icons/heart" title="heart icons">Heart icons created by pictranoosa - Flaticon</a>
And it was imported using the following tutorial: https://www.youtube.com/watch?v=HtXjhEwf32I

# Generative AI Notice

ChatGPT was used in this website. Its uses were:
* Used to restructure HTML code to be more organized
* Used to gernerate cards for the dividers/content on the Today and Future pages
* Used to generate CSS to animate text and properly align various aspects throughout the website
* Used to aid in formating Return Button's locations
