# Steps that i made for debugging this game

- open react devTools
- see components and output
    wordGuessed: true and gameIsOver: true
- see AppContainer and other components, check functions, they seem ok
- check App.js 
    saw quickly that the first function returned true instead of false
- add ! and check application and the winning img was gone