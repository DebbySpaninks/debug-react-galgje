# Steps that i made for debugging this game

- open react devTools
- try game
    after 6 wrong guesses the game ends
- see components and output
    maxGuesses: 5
- see maxGuesses in AppContainer 
    seems ok
- go to App.js and search for maxGuesses
    saw that in function isGameOver the if statement getWrongLetters 
    is bigger then the maxGuesses
- changed it to smaller then and it immediately ends the game
- then changed it to bigger then and equal to and the function ends 
    after 5 wrong letters as it should