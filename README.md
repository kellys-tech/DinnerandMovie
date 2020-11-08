# D&M (Dinner and a Movie)
### Pages: https://kellys-tech.github.io/DinnerandMovie/movies.html
### GitHubRepo: https://github.com/kellys-tech/DinnerandMovie


*Welcome to Dinner and a Movie (D&M). Planning a date? Evening with friends? Last minute plans? Home alone? A person can utilize this app to generate a list of movies to watch and/or meals to make at home.

## MVP
### Movies
* User selects movie genre(s) in checkboxes
* User clicks button to generate list of movies
* Movies are displayed in cards on the movie page

### Meals
* User clicks button for meal type to generate a list of related recipes
* Recipes are listed in cards
* User can click on link in card to go to an external site for the full recipe

## Dinner and a Movie created using:
* HTML - to create the content of the dashboard. 
* CSS - for styling
* Materialize - additional styling and formatting
* JQuery - create interactions for the user
* APIs:
    * The Movie Database - to get movie info
    * Edamam - get recipe info
* Google fonts - to get fonts 

## Features
### Movies
* Movie suggestions
   * Movie genres are listed as checkboxes for the user to choose from
   * User will click one or more checkboxes and click the generate button to get a list of movies for that genre
   * Suggested movies will be displayed in cards.
        * Each card contains the movie name, poster image and a description.

### Meals
* Meal suggestions
    * Meal types are listed as buttons for the user to click on
    * User will click a button and a list of meals will be generated based on their meal type
    * User can only choose one meal type at a time
        * If user clicks another meal type, the current list of meals will be removed from the screen and a list from the new meal type will be displayed
    * A card will be displayed for each meal with the meal name and a link to the full recipe
    * When a user clicks a link they will be taken to an external site in a new tab that will display the recipe details

### Future Versions for updates and enhancements
* Add new APIs/Features
    * Music, Sports, Recreation, I Feel Lucky (randomly generated)
    * Add additional filtering options
    * View More (display more results)

* Styling
    * Add help text
    * Updated aesthetic
    * Create home page
    * Meet accessibility standards


### Screenshots

![Movies Search](assets/MoviesSearch.png)
![Movies Generated](assets/MoviesGenerated.png)
![Recipes Search](assets/RecipesSearch.png)
![Recipes Generated](assets/RecipesGenerated.png)
![Mobile Movies Search](assets/MobileMoviesSearch.png)
![Mobile Movies Generated](assets/MobileMoviesGenerated.png)
![Mobile Recipes Search](assets/MobileRecipesSearch.png)
![Mobile Recipes Generated](assets/MobileRecipesGenerated.png)
![Mobile Menu](assets/MobileMenu.png)
![Recipes New Tab](assets/RecipesNewTab.png)


