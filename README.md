# LL_Hackday
Love Letter Hack Day Repo. University of Edinburgh 2017. Main contacts:
1. [Alastair Heggie](https://www.eng.ed.ac.uk/about/people/mr-alastair-heggie)
2. [James Owers](https://www.inf.ed.ac.uk/people/students/James_Owers.html)


## Rough day outline
Here's a rough plan for the day:

* **08:30 - 09:00** - Breakfast (provided)
* **09:00 - 09:15** - Introduction and explanation of the game
* **09:15 - 09:45** - Team registration and game practice
* **09:45 - 10:30** - Human Tournament (_prize awarded!_)
* **10:30 - 11:00** - _BREAK_
* **11:00 - 13:00** - Work on first solution (probably manual) and submit
* **13:00 - 14:00** - Lunch (provided?)
* **14:00 - 14:15** - Preliminary results announced, feedback given, questions
* **14:15 - 18:00** - Work on final submission and push to repo
* **18:00 - 19:00** - Dinner (Pizza & beers provided!) & Make 1 min presentation
* **19:00 - 19:15** - Best robot announced (_prize awarded!_)
* **19:15 - 19:45** - 1 min presentations (_prize awarded!_ for most innovative)
* **19:45 - 20:30** - Best human vs. best 3 robots (live!)


## Installation
Installation all done using conda. Please download and install miniconda (or anaconda if you want) if you don't have it installed - instructions [here](https://conda.io/docs/install/quick.html)

Once conda is installed, the following code will create a new virtual
environment which you should use throughout the day, and install into it all
required packages:

```{bash}
conda create -n LL_Hackday python=3 numpy
source activate LL_Hackday  # if on windows, drop 'source'
```

Before running any code or installing any more packages, ensure that you
activate the environment (`source activate LL_Hackday` on Unix,
`activate LL_Hackday` on windows).


## Test drive
To check everything is working, try playing the game!

```{bash}
some code that allows user to play baseline solution
```
