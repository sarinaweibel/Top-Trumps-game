# Top Trumps Game
### Project Description
The project was created using python and requires importing the packages random and time to work properly. The aim of this project is to recreate the Top Trumps game in a virtual environment. In the end the user will be able to play against the computer and experience the game from a new perspective.

Top Trumps is a card game consisting of a pack of cards belonging to one theme. The theme chosen for this assignment is Harry Potter which means that for each of the 28 characters there is a card explaining their magic, cunning, courage, wisdom, and temper based on numerical data. The goal of the game is to compare the values and to win by having the highest number.

The code structure is divided in several parts. First, you define the categories magic, cunning, courage, wisdom, and temper on the cards while creating a function. By using the open() function you can read the data from a text file which contains all the numerical values to the predefined categories. To be able to play the game properly you have to edit the data as well as create the cards.  Next you need to shuffle the deck and distribute the cards evenly to the two players defined as playerDeck and computerDeck. To run the whole game, you need to implement a while loop which runs as long as both players have cards left. During the game the players are allowed to choose different categories that lead to different outcomes. This is actually the fun part where the players choose their path for the round. If the player does not write one of the given options, the code will not break down but give the user the possibility to rewrite the answer. For the computer to understand whose turn it is you set the playerTurn to True and check with the if-statement if it actually is true in a given situation. As soon as this is the case it is your turn, else it is the computers turn. 

The main challenge was to convert a finished Top Trumps data set from R to Python as well as include it suitably into the game. Instead of defining each card by itself you can just download and import a finished Top Trumps deck with more characters. Do not forget to adapt the code to each deck so that it can work properly. 

To understand how the Top Trumps game is played we will give you a short explanation. In the beginning each player gets a randomized card. If it is your turn you can choose a category and the code will then compare your opponents and your values of the chosen category. The higher number wins and the person owning the winner card gets both cards. Afterwards the winner from the previous round gets to choose the category for the next cards. Players who have lost all their cards are eliminated and the winner is the player who owns the whole deck of cards.

Jan Enderli (18-608-935)

Livia Mühlheim (19-610-419)

Michelle Tijkorte (19-612-852) 

Sarina Weibel (19-613-801)
