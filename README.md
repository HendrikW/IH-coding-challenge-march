# IH-coding-challenge-march

## Goal

The goal is to create a small **React** application that uses the Wolfram Alpha API ( https://products.wolframalpha.com/api/documentation/ ) to display the path of the sun and the moon for six different cities.

It should take you around 2 hours to complete. 

## Requirements

* it should use Bootstrap and look decent on a mobile device ( don't spend too much time on styling details, just don't force mobile users to pinch-zoom please ;) )
* there should be two different pages/views 
  * one that shows the path of the moon (as an image) for each city in a separate box
  * another page that shows the path of the sun (as an image) for each city in a separate box
* **it should have a detailed README that allows a step-by-step setup of the application on the interviewer's laptop.**

## Notes

* you can choose any six cities that you like.
* any search query you can do via WolframAlpha you can also do via their API. ( e.g. https://www.wolframalpha.com/input/?i=sun+berlin and https://www.wolframalpha.com/input/?i=moon+berlin )
* you can sign up via http://developer.wolframalpha.com/ -> it's free, just type in a name/email and a description for your app etc. (e.g. "testing"). 
* you should use the **JSON** variant of the API (`output=json`)
* it's going to be a completely public page, so no user/login required.
* if you want to use the API from the **frontend** (this is not really supported by WolframAlpha, but might make sense to complete the project without having to write a backend first): use `open -n -a Google\ Chrome --args --disable-web-security --user-data-dir=/tmp/chrome` to open an instance of Chrome that does not care about **CORS**. *DON'T use this for your average web browsing, please, only for this exercise!*

## first Bonus

* allow the user to add more cities.

## second Bonus

* store the cities the user added into a session (so when they close the page and open it later again, the added cities are still there, unless they clear their browser cache)
