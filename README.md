# Kerbal-Space-Program-Code
Basic Code for doing Rocket Science calculations, to make Kerbal Space Program much easier to play

This code is meant to make Kerbal Space Program much easier to play by removing the guessing from rocket design.
By running this code in Python, a player can figure out how much delta-V to give their rocket if they want to go to a desired location.
It has a variety of functions in it, but the most important are these: 
- hohmann_transfer_dv(gives the dV needed to change a circular orbit's size)
- orbital_velocity_predictor(gives how much velocity is needed to have a circular orbit at a radius r)
- dv_launch (gives how much dv is needed to get to a certain height, such as above the atmosphere of Kerbin)

At the top of the file are a set of values(height of Kerbin's atmosphere, radius of the Mun's orbit, etc.) and at the very bottom are a set of function commands. Simply find the function you wish to use, uncomment the function and replace the function parameters with whichever values you need, and it will print out the delta-V in the console
This code is meant to be very flexible, so this is part of why all the functions are at the bottom: you can switch any function 'on' or 'off' if you don't want it taking up space in the console, and swap the values inside the functions with anything you want, or you can use the reference values like Mass_Kerbin if you don't want to type out the numbers directly.
- Also, make sure you have numpy and sympy on your python system, if they happen to not have come by default.
