# Crazy Eights

**Introduction**  
This Crazy Eights game is a two-player card game implemented using the Java programming language. This following user manual will guide you through the rules of the game and explains how to play using the graphical user interface (GUI). 

**Game Objective**  
The objective of Crazy Eights is to eliminate all of your cards by playing them onto the discard pile. The player who plays all their cards first wins the game.

**Components**  
The Crazy Eights game consists of the following classes:
- Deck.java: Represents the deck of cards - it contains methods to initialize the deck, shuffle the cards, and draw a card from the deck
- Player.java: Represents a player in the game - it has methods to manage the player's hand, such as adding cards, removing cards, and selecting a card to play
- Card.java: Represents a playing card - it has information about the card's rank, suit, and an image of the card
- CrazyEightsGUI.java: The graphical user interface for the game - it displays the game panel, current player's hand, current card, and provides buttons for drawing and playing cards

**Graphical User Interface**  
The game provides the following graphical user interface elements:
- Current Player Label: Displays the name of the current player
- Current Card Image: Displays the image of the current card
- Draw Button: Click to draw a card from the deck
- Play Button: Click to play the selected card from the current player's hand
- Card Buttons: Represent the cards in the current player's hand (click on a card button to select a card)
- Selected Card Highlight: The selected card button is highlighted with a red glow
- Error Messages: Displayed when an invalid card is played or an error occurs.
- Dialog Box: Used to choose a suit when an "8" card is played.

**Setup**
- Run the Java program "CrazyEightsGUI" using an IDE or command line
- The game window will appear with the title "Crazy Eights" and a dark green background
- The game automatically shuffles the deck, deals seven cards to each player, and selects the first player
- The current player's name is displayed on the left side of the window, and the current card image is shown in the center
- The player's hand is displayed as a row of card buttons at the top of the window

**Gameplay**  
The gameplay follows these steps:
- Player Setup
    - The game starts by shuffling the deck and dealing seven cards to each player
    - The first card from the deck is drawn and placed face-up on the discard pile
    - The suit of the current card becomes the current suit
- Current Player’s Turn
    - The current player's name is displayed in the GUI
    - The current card on the discard pile is shown
    - The player's hand is displayed as a set of card images
    - The player can click on a card in their hand to select it for playing
- Drawing a Card
    - To draw a card, click the "Draw" button
    - A card is drawn from the deck and added to the current player's hand
- Playing a Card
    - To play a card, select a card from the player's hand by clicking on it
    - The selected card will be highlighted
    - Click the "Play" button to play the selected card
    - The card will be removed from the player's hand and placed on the discard pile if it's a valid play
    - If the played card is an “8”, the player will be prompted to choose a new suit for the game
- Valid Card Plays
    - The player can play a card if it matches the current suit or rank
    - If the player plays an 8, it's always a valid play
    - If the player plays a card with the same suit as the current card, it's a valid play
    - If the player plays a card with the same rank as the current card, it's a valid play
- Invalid Card Plays
    - If the player attempts to play an invalid card, a message will be displayed
    - The player must select a valid card to continue the game
- Next Player’s Turn
    - After a card is played, it becomes the new current card
    - The current suit is updated to match the suit of the new current card
    - The turn moves to the next player in a clockwise direction
    - The game continues until a player runs out of cards

**Winning The Game**  
The game ends when one player has no cards left in their hand. The player who plays all their cards first is declared the winner. A message will be displayed in the GUI announcing the winner.

**Exiting The Game**  
You can close the game window to exit the game at any time.

**Additional Notes**  
The game window may need to be resized to display all the player's cards properly. The GUI provides a visual representation of the game, but the actual game logic is implemented in the Java code.

**Tips & Strategies**  
- Pay Attention to the Current Suit: The current suit determines the valid suit for the next player's turn, hence, try to play cards that match the current suit to limit your opponents' options
- Strategic Use of "8" Cards: "8" cards are powerful in Crazy Eights because they can be played at any time and allow you to change the suit, hence, save them for crucial moments or to disrupt your opponents' plans
- Observe Your Opponents: Pay attention to the cards played by your opponents and the cards they draw as this will give you insights into their strategies and help you make better decisions
Plan Ahead: Consider the possible consequences of your plays by thinking a few moves ahead to anticipate how the game might unfold and plan your strategy accordingly
- Keep a Balanced Hand: Try to maintain a balanced hand with cards of different ranks and suits as this will increase your chances of having playable cards during your turns

**Troubleshooting**  
If any errors occur during gameplay, an error message may be displayed. Check the error message for details and try to identify the cause. If necessary, restart the game or consult the game's source code for further debugging.

**Limitations**  
This Crazy Eights game currently supports only two players. The game does not include advanced features such as computer-controlled opponents or additional player support. 

**Feedback & Support**  
For feedback or support regarding the Crazy Eights game, please contact the developer, Kyle Kapoor, or refer to the source code for more information.

**Conclusion**  
The Crazy Eights game provides an exciting and challenging card game experience. Use your strategy and card-playing skills to outsmart your opponents and be the first to eliminate all of your cards. Enjoy playing my game, Crazy Eights!
