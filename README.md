# Guess_Where

### Introduction

This project aims to put into practice our knowledge in dynamic web pages. The aim was to use the
Leaflet free JavaScript library, used for mapping.


The goal is simple: get the best score, and this by locating as precisely as possible the places displayed on a
planisphere.


Once our choice is validated, the result is displayed and a description of the place appears. The user then has the choice to continue the game
or display on the map the route (between the place he has located and its correct location).


At the end of a game consisting of five questions, the score is displayed and the game offers the player the opportunity to replay. The score is calculated based on the accuracy with which the user will have located the places. Beyond a thousand kilometers no point is awarded, while one hundred and fifty points are earned if the choice is within a five kilometer radius of the location in question.


The ability to quit the game and return to the home page is always available, via the cross located at the top right.

### Project structure

* public: contains the elements necessary for the correct functioning of the front (css, js, resources, ...)
* utils: has a data.php file which contains the necessary back-end data (name, description, location, ...)
* views: contains the views of the application

### Quick Start

1. go to your command prompt
2. cd [WHERE IS THE PROJECT]
3. use the command : php -S 0.0.0.0:{PORT} -t public/
4. go to browser and type localhost:{PORT}
