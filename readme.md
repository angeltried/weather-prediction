# weather prediction

## Acceptance Criteria

GIVEN a weather dashboard with form inputs
WHEN I search for a city
THEN I am presented with current and future conditions for that city and that city is added to the search history
WHEN I view current weather conditions for that city
THEN I am presented with the city name, the date, an icon representation of weather conditions, the temperature, the humidity, and the the wind speed
WHEN I view future weather conditions for that city
THEN I am presented with a 5-day forecast that displays the date, an icon representation of weather conditions, the temperature, the wind speed, and the humidity
WHEN I click on a city in the search history
THEN I am again presented with current and future conditions for that city
### Angels walkthrough

* html
   1. started with boiler then added scripts and linked a style sheet.
   2. made input with button and inside a div bg i have also the weather classes.
   3. erased text referance after java was created.

* css
   1. using tailwind to get items center of the page and responsive.
   2. add bg to body using a url on a style scheet page from website unsplash
   3. add color the middle bg and made trasparent to show back ground.
   4. made button with a icon from ionicons.
   5. gave items flex col also text size and correct spacing.

* java
    1. got an api key from a website current weather.
    2. after waiting an hour gave weather this api key made function to featch the api with city name using .this 
    3. made a display for the weather using the data with quaryselector grabbing the class adding the data names 
    4. have the input a search funtion to feather the weather with its value
    5. event listener click and key up to get resutles both ways.
    6. gave the body sytle to pull a picture of name search from unsplash
    7. load default weather in denver. 
 
####

Make a repository with a unique name.
Made folder in my happy face finder api pop quiz inside folder then git clone ssh of repository using terminal.
Save as readme.md into java pop quiz folder then using vs code create index.html and then folder for assets (styles.css, script.js).
Start working on html and ccs to get position of each section once finish first attemt git push into repo.
Open pop this quiz after all folders saved, git init , git status, add . , git commit -m "comment", git push -u origin main