

A note on the API:

- used an API suggested by a classmate
- using a fetch request (for one word filter five letters) 
- grabbing the first object which will be the returm
- this has to be async so the onload can await for the variable to come in
- otherwise winning word could be an object promise and that throws errors
- had errors with two separate onload functions, move guess tag within first onload


Extra Credit: Average guesses

How it works: cookies store total number of lifetime games, total number of lifetime guesses, and current avg (to use for dispalying)
After each game, it adds to the total lifetime and game counts. This makes it easier to update the avg. 
It uses math.floor to round it to the nearest integer.