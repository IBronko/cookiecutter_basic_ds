# Cookiecutter 🍪 for a basic data science project

I was tired of manually seeting up a virtual environment and installing the same basic packages/libraries for each (little) project.
Then I stumbled over this tool called "Cookiecutter" that helps me to automate repetition away... 

## Quick tutorial

💡[Calmcode](https://calmcode.io/cookiecutter/the-problem.html)

## Prerequisites

- Installation of [Python 3](https://www.python.org) on your machine  
- Installation of [cookiecutter](https://cookiecutter.readthedocs.io/en/2.0.2/installation.html) on your machine
- Installation of [pipenv](https://docs.pipenv.org) on your machine (to create virtual environment and install dependencies within ve)

## Steps

1. Navigate to desired folder on your machine and generate your project structure from GitHub project template:<br> 
`$ cookiecutter https://github.com/IBronko/Cookiecutter_Basic_Data_Science.git`

  __OR__: To generate a project from a local cookiecutter template type: `$ cookiecutter .`

2. Adjust Pipfile if necessary (include or exclude packages)

3. Create virtual environment for your project and install requirements of template from included pipfile:<br>
`$ pipenv install`

## Pipenv basics

1. Activate VE: `$ pipenv shell`

2. Deactivate VE: `$ pipenv exit`

3. Commands overview: `$ pipenv -h`

