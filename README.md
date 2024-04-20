# guess-my-number 
Initialization:
It starts by initializing three variables:
number: A random number between 1 and 20 (inclusive) that the player needs to guess.
score: The initial score set to 20, representing the number of attempts the player has.
highscore: The highest score achieved by the player.
Display Message Function:
There's a function displayMessage defined to change the text content of an element with the class .message. This function is used to display various messages to the player throughout the game.
Event Listeners:
Two event listeners are set up:
One for the "Check" button: When clicked, it compares the input guess with the randomly generated number.
One for the "Again" button: When clicked, it resets the game to its initial state.
Checking the Guess:
When the player clicks the "Check" button, it first retrieves the value of the guess entered by the player.
It checks if the guess is empty. If so, it displays a message prompting the player to enter a number.
If the guess matches the number, the player wins:
Displays a winning message.
Updates the background color, enlarges the number display, and updates the highscore if the current score is higher.
If the guess is higher than the number, it reduces the score and displays a message indicating the guess was too high.
If the guess is lower than the number, it reduces the score and displays a message indicating the guess was too low.
Resetting the Game:
When the player clicks the "Again" button, it resets the game:
Resets the score to 20.
Generates a new random number.
Resets the message, score display, and guess input field.
Resets background color and number display size.
