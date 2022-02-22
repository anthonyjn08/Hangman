# **The Hangman's Stage!**
## **Aim of the site**

The aim of the site is to allow users to play a single player python command line version of the Hangman game. There are 3 categories of words for players to choose from on each run through of the game. The player then has 6 guesses to correctly guess the secret word or fail the game.

## **Game Features**
### **Title Screen**

![Title Screen](assets/docs/screenshots/title_screen.jpg)

The title screen welcomes players to the site, explains the rules and asks the player to input "y" to play the game and "n" to exit the game.

### **Theme Choices**

![Themes](assets/docs/screenshots/theme_choices.jpg)

Once the user has input "y" to play the game, they're presented with a list of theme's to choose for the secret word.

### **Game Play Screens***

#### **The secret word**

The secret word is presented to user with a series of underscores which match the length of the secret word.

As the player guesses letters thee letter is appended to a list of used characters which is then printed so the player is aware of letters they have already guessed. If the letter is in the secret word then that letters underscore is replaced by the letter.