## FAQs:
Q: Which packages should I have in my conda enviroment to be sure everything works?
A: Please check the [requirements.txt](requirements.txt) file.

Q: When trying to run the notebook I get errors related to missing packages. What do I do?
A: Check carefully python's error messages. When a library / package is missing, python will let you know which one it is. Install missing packages via pip (e.g. by typing ```pip install tud-sumo``` for tud-sumo.).

Q: I get weird errors when trying to run / visualize a simulation, something about SUMO_HOME not being set
A: Edit the '.env' file in your project's main folder. Add a line that defines where SUMO_HOME is (e.g.: SUMO_HOME=C:/SUMO/ for Windows (assuming C:/SUMO is your install folder), or SUMO_HOME=/Library/Frameworks/EclipseSUMO.framework/Versions/Current/EclipseSUMO/share/sumo for MacOs). Please note this is computer (and Operating System) dependent, SUMO will define its home folder during installation.

Q: When running Assignment 2, no results are shown and an error message follows the simulation cell, explaining that the 'default' connection is already active.
A: This is common when using SUMO's Graphical User Interface (```forceGUI=True```). Click on 'Restart' (next to Run All, at the top of the window), then run your simulation(s) again. This will remove the issue.

