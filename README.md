# COIN_TOSS_SIMULATOR
This is a Python code that creates a GUI application for a coin toss simulation using the customtkinter library. The GUI includes two input fields for the percentage chances of getting heads or tails and two buttons for tossing the coin. It also includes a switch button for toggling between dark and light mode.
Here's a brief overview of the code:
The required modules (tkinter, random, cv2, and customtkinter) are imported.
The decider() function is defined to determine which button is clicked (either toss or toss unbiased) and calls either the toss() or tossunbias() function accordingly.
The toss() function generates a random number between 0 and 1 and displays either heads or tails accordingly.
The tossunbias() function generates two lists with values of all possible outcomes for heads and tails, based on the given percentage chances of getting heads. It then generates a random number between 1 and 100 and determines whether it falls within the range of heads or tails list and displays the outcome accordingly.
The tails() and heads() functions display a video of a coin flip showing either tails or heads respectively.
The switch_event() function is defined to toggle between the dark and light mode.
The code then creates a tkinter window, adds a frame to the window, and adds various GUI elements such as labels, input fields, buttons, and a switch button using the customtkinter library. Finally, the code enters the tkinter main loop to display the GUI and wait for user input.
