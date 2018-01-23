# Thermostat

[Task](#task) | [Approach](#approach) | [Execution](#execution) | [Struggles](#struggles) | [Run the App](#demo) | [Technologies](#technologies)


## <a name="task">Task</a>

This task was completed during week 5 of the Makers Academy course, our first foray into the world of JavaScript. Throughout this week we paired with a different partner each day allowing us to work on our collaboration as well as our coding.

This is the specification that was provided to us:

* Thermostat starts at 20 degrees
* You can increase the temperature with an up function
* You can decrease the temperature with a down function
* The minimum temperature is 10 degrees
* If power saving mode is on, the maximum temperature is 25 degrees
* If power saving mode is off, the maximum temperature is 32 degrees
* Power saving mode is on by default
* You can reset the temperature to 20 with a reset function
* You can ask about the thermostat's current energy usage: < 18 is low-usage, < 25 is medium-usage, anything else is high-usage.
* (In the challenges where we add an interface, low-usage will be indicated with green, medium-usage indicated with black, high-usage indicated with red.)

We chose to use these bullet points as our user stories for the development of the app.

## <a name="approach">Approach</a>

Prior to this week I had never used JavaScript before. I therefore used this week be become familiar with OO design while generating the business logic for the thermostat. This was achieved through test driven developent using Jasmine.

## <a name="execution">Execution</a>


## <a name="struggles">Struggles</a>

* Obtaining icon information from the returned JSON and interpolating it into the subsequent DOM rendering.
* Heroku did not allow http calls to be made after deployment - solved this by making all calls use https.
* If I had more time to work on this project I would like to have made it so that thermostat temperatures were saved in sessions or a database of sorts.

## <a name="demo">Run the App</a>

Thermostat is live [here](https://thermostat-final.herokuapp.com/index.html)

In order to run locally:

* Clone this repository
* Change into the repo directory
* Run `open SpecRunner.html`(Mac) or `xdg-open SpecRunner.html`(Linux) to see all passing tests
* Run `open index.html`(Mac) or `xdg-open index.html`(Linux) to view the thermostat

# <a name="technologies">Technologies</a>

Business logic development was entirely test driven using JavaScript standard syntax and the Jasmine testing framework. JQuery was used to make weather API requests and handle all user interaction.
