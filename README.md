# Jeopardy

Tonight we are going to construct a Jeopardy game with multiple choice questions. 

## The basics

Jeopardy is a classic television trivia game show. In the television version, three players compete against eachother to answer questions, each worth a particular monetary value. The player with the most money at the end of the game wins.

There are three rounds in Jeopardy: Jeopardy, Double Jeopardy and Final Jeopardy. Jeopardy and Double are played in the same manner, except that during Double Jeopardy the monetary values for each answered question is double what it was for the Jeopardy round.

The players are shown a board with six categories, each category containing 5 tiers of money values. Here is an example of a board at the beginning of a Jeopardy round:

![Jeopardy board](https://upload.wikimedia.org/wikipedia/commons/thumb/d/d8/Jeopardy_game_board.png/510px-Jeopardy_game_board.png)

A player selects the category and the dollar amount for the category. The harder questions are worth more money. The question is revealed and the player "buzz in" to answer. The contestant who buzzes first gets to answer. If that person correctly answers the question, they win the money and they pick the next category and dollar amount from remaining spaces on the board. If they do not answer correctly, the dollar amount is deducted from their total. If they answer incorrectly or don't answer within a period of time, the other contestants have an opportunity to buzz in and answer. The same scoring, deduction, and turn rotation applies for correct and incorrect answers. If no contestant answers correctly, the original contestant chooses a new category and dollar amount.

The round is played until no remaining spaces are available or there is no time remaining in the round.

There is one Daily Double space hidden in the Jeopardy Round and two in the Double Jeopardy round. If the player selects a space where the Double Jeopardy is hidden, that contestant is the only contestant who will answer. The contestant wagers from a minimum of $5 to a maximum of the player's current score, or the highest clue value available in the round, whichever is greater, after which the question is revealed. The player wins or loses that amount based on whether or not they answer the question correctly. They also will take the next turn.

Final Jeopardy is played much like Daily Double, however each player will wager. Once the wagers are given, the question will be revealed and the players will write their answers secretly. Once time is expired, players reveal their answers and points are added or deducted. The player with the most money after the Final Jeopardy round wins the game.

## The application

Most of the aspects of the actual game can be encorporated into the application. You will need to be able to create a board with questions, answer questions, and score. Depending on the complexity that you want to introduce, you could also encorporate multiple players, but it may be best to start off with a single player option.

There is an included file called trivia-questions.txt where there are some sample questions with multiple choice answers. Part of the challenge is to be able to fill the board with questions, making sure that the harder questions have a higher value and the easier questions have a lower value. You will need to display the questions with the options and check for correct input.

Sample questions were found using [this neat tool](https://opentdb.com/api_config.php)

The implementation is up to you. This is a 3 hour hack night, so start with your MVP, the smallest piece that you can deliver, and add complexity as you go. Good luck!
