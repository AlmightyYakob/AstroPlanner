# AstroPlanner-api
Code by Jake Nesbitt

A project to predict the quality of the night-time sky conditions for astrophotography using weather forecasts and lunar phases.

This project will alert a user when conditions are right for photographing the stars.
This mean the sky is clear and clouds are absent and the moon isn't interfering either.

The code will take data from multiple sources and display to the user if both the above conditions are true.


Credentials are supplied in `credentials.py`, with a variable named`DARK_SKY_SECRET`.

The python virtual environment is managed by pipenv. To create the virtual environment, run `pipenv install`.
To activate it, run `pipenv shell`.

## APIs used
* [DarkSky](https://darksky.net)
* [Sunrise Sunset](https://sunrise-sunset.org)
