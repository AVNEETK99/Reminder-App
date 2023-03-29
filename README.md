# Reminder-App


## Instructions to run the game

* Open the Github repository where the game code is hosted.

* Click on the green "Code" button and then select "Download ZIP" to download the code as a ZIP file.

* Extract the ZIP file to a folder on your computer.

* Open a command prompt or terminal window and navigate to the folder where you extracted the code.

* Type ```python reminder.py``` and press Enter to start the game.

* Follow the prompts to play the game.

## Functionality of the code

* ```import time```: This line imports the time module, which allows the program to use time-related functions.

* ```print("What shall I remind you about?")```: This line prompts the user to enter a reminder.

* ```text = str(input())```: This line takes the user's input and stores it in the variable text.

* ```print("In how many minutes?")```: This line prompts the user to enter the number of minutes until the reminder should be displayed.

* ```local_time = float(input())```: This line takes the user's input and stores it in the variable local_time as a float.

* ```local_time = local_time * 60```: This line converts the number of minutes entered by the user into seconds, so it can be used with the time.sleep() function.

* ```time.sleep(local_time)```: This line pauses the program for the number of seconds specified by the user.

* ```print(text)```: This line displays the reminder that the user entered after the specified amount of time has passed.
