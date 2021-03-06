Team Grimmie Rawwks
=================

Aidan F, Ramy M, and Winton Y's term project for Intro to Computer Science 2.

This is a Web application that gives the user recommendations as to what to wear
based on weather data from the [OpenWeatherMap.com API](http://openweathermap.org/API).

### Development log

#### 2014-05-30
* Aidan wrote a function that retrieves weather data from the OpenWeatherMap.com API.

#### 2014-05-31
* Winton is starting to work on the parsing of the API info to get the info we want.
* Ramy developed the algorithm.

#### 2014-06-03
* Winton and Aidan will work together on parsing of the API info as Ramy will attempt
to fix connection and debug code that opens the file.

#### 2014-06-06
* Aidan has gotten a basic interpreter that informs users how
many layers they should wear based on the temperature in 
their area. Ramy will be helping Aidan with the rest of the 
interpreter.
* Winton is working on designing a register/login functionality
to allow users to save preferences.

#### 2014-06-09
* Aidan fixed a small error in the analysis code, where fields are pulled from the JSON
and copied to another dictionary.
* Aidan found code to change proxy settings, which solved our problem with opening 
HTTP connections.
* Ramy topped off some of the analysis.py code. (Ramy, please elaborate....)

#### 2014-06-11
* we now have a functional website! As in the basic functionality is there, though
there are some bugs and errors we must handle if our users input insufficient or 
incorrect information.
* Winton has also started to work on a register/login feature for users to sign in 
and save cities and preferences. The basic registration and login shell structure
is there.

#### 2014-06-12
* Winton handled errors if a nonexist city/country combination is entered.
* Aidan is working on the html and python code so that users only receive
recommendations based on what they check off.
* Ramy finished randomization of weather messages (i.e. you can get 'It's hot'
or 'Mucho calor!')

#### 2014-06-13
* Aidan finished merging Ramy's changes and adding the code that allows users to select
information to see.

#### 2014-06-14
* Winton created the system to reigster, login, stay logged in, and save preferences. He
never wants to hear the word 'cookie' again.

#### 2014-06-15
* Winton implemented a system to change user's passwords and debugged, A LOT. He also finally 
got to make the website all pretty with backgrounds and CSS!
* Cookies MUST be set to "on" in the browser for login feature to work.
For certain cities, you may simply get ", &lt;Country>". As far as we can tell, this is a fault 
with Open Weather Map, and not our code, since our code simply reads the city and country from
Open Weather Map.
