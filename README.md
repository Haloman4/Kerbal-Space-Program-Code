# Kerbal-Space-Program-Code-A-
Basic Code for doing Rocket Science calculations, to make Kerbal Space Program much easier to play

This code is meant to make Kerbal Space Program much easier to play by removing the guessing from rocket design.
By running this code in Python, a player can figure out how much delta-V to give their rocket if they want to go to a desired location.
It has a variety of functions in it, but the most important are these: 
- hohmann_transfer_dv(gives the dV needed to change a circular orbit's size)
- orbital_velocity_predictor(gives how much velocity is needed to have a circular orbit at a radius r)
- dv_launch (gives how much dv is needed to get to a certain height, such as above the atmosphere of Kerbin)

The code can be intimidating, but the usage is fairly easy. At the top of the file are a set of values(height of Kerbin's atmosphere, radius of the Mun's orbit, etc.) and at the very bottom are a set of function commands. Simply find the function you wish to use, uncomment the function and replace the function parameters with whichever values you need, and it will print out the delta-V in the console
And, you can add any functions or variables you want(which is recommended since the code didn't have everything). Add Jool's orbital radius, or the apoapsis of a space station, or create a function for how to escape the Kerbol System entirely-it is up to you.
