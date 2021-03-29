# Steps that i made for debugging this game

- open react devTools
- see components and output
    the clickfunction is working without input
- see AppContainer and other components
    in AppContainer was missing an if statement to check if currentChosenLetter is bigger then 0
- add the if statement and the game is not accepting click without input 