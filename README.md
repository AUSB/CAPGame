# CAPGame
Android Application Design Project using Android Studio



This app is a Jeopardy-like game that asks the user questions about countries (the capital of a given country and the country of a given capital-hence the Capss name). It also keeps track of the achieved score.
Once DONE is tapped of Q#9, the game should evaluate and log its answer as before, but then the game should end. The maximum score is therefore 9. 
When the game ends, 

•	The sentence “Game Over!” appears in the question number label.
•	The DONE button becomes disabled.


Also, the app sounds a tone if the answer is correct and a different tone if the answer is wrong. Sound generation is done through the ToneGenerator class. Add an attribute tg of this type to the activity and initialize it in onCreate.
