# Armandle
A wordle clone that supports secret messages (multiple words separated by a space) instead of just one word.

The game is live at https://www.gamearmani.com/armandle.

One can set the secret message and the number of guesses the user has to guess it by modifying
these two lines at the top of the javascript:

```
const secretMessage = "arjun".toUpperCase();
const NUMBER_OF_GUESSES = 6;
```

For example,
```
const secretMessage = "happy birthday himani".toUpperCase();
const NUMBER_OF_GUESSES = 8;
```

Leave the `toUpperCase` after the secret message. 

Enjoy!