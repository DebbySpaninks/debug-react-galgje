# Steps that i made for debugging this game

- open react devTools
- try game
    the wrong input letters can be guessed more than once
- see components and output
    guessedLetter: adds the same wrong input letter
- go to AppContainer
    look for guessedLetter
- saw no compare for wrong letters
- add compare for guessedLetters and currentChosenLetter 
- check if the adjustment works