# schema for captone pokemon card app by Derek Forlini

## Overview
The Pokemon Card App is a web application built using Flask and integrates with the Pokemon TCG API (https://docs.pokemontcg.io/) to allow users to search for Pokemon cards, manage thier collections, and create decks.

## Features
1. Authentication and authorization
   users can register, login, and logout
   Sessions are managed using Flask session management

2. Searcg Pokemon cards
   Users can search for Pokemon cards using various criteria such as name, type, and set

3. Collection managment
   Users can view their collection of pokemon cards
   Cards in the collection are stored in a database linked to user accounts

4. User Interface
   responsive UI with nav bar
   Seperate views for different functionalities (home, Pokemon cards search, collection)  

## Technologies used
1. Backend: Python(flask), SQLalchemy for database managment
2. Frontend: HTML, CSS  
3. API integration: Pokiemon TCG API for fetching card data

### File structure
capstone
|
|-app.py                     
|-extentions.py
|-models.py
|-pokemon_api.py
|
|-static/
    |-style.css
    |-videos/
        |-background
|
|-templates/
    |-base.html
    |-collection.html
    |-login.html
    |-main.html
    |-pokemon_cards.html
    |-register.html
    |-welcome.html        
|
|-utils.py
