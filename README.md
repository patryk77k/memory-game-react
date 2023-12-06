
# ⭐ Live version link

[Click here!](https://memory-game-bs2i.onrender.com/)

## 💻 Screenshots:
<img src="https://picr.eu/images/2023/12/06/RSslK.png" width="600" />


## 💻 Used Stuff:  
- React
- Java Script

 <i> More Info in package.json</i>

 

## 🚀 Features: 

- Card Shuffling: Cards are shuffled randomly at the start of the game using the shuffleCards() function. This function uses Math.random() to randomize the order of the cards.

- Card Selection: Players can select cards by clicking on them. Two cards can be selected at a time (choiceOne and choiceTwo) using the handleChoice() function.

- Matching Logic: When two cards are selected, the app checks if they match. If the selected cards have the same image (src), they remain flipped. Otherwise, they flip back after a brief pause using setTimeout().

- Turn Counter: The app keeps track of the number of turns taken by the player to complete the game.

- Resetting the Game: Players can reset the game and start a new round by clicking the "New game" button. This button triggers the shuffleCards() function.

- User Interface: The game's user interface displays a title ("Magic Match"), a button to start a new game, a grid layout displaying the cards, and a co unter showing the number of turns taken.
  
## 💻  Install:
  
```
npm i
```

## 💻  Run:
```
npm start
```

