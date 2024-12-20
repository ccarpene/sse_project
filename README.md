# sse_project
# Secure Software Engineering
# About The Project

This is how to run my Programming Paradigms project.

## Built With
All the dependencies of our project include:

* [Python 3.12.6](https://www.python.org/)
* [Django 5.1.1](https://www.djangoproject.com/)
* [Bootstrap v5.3](https://getbootstrap.com)

## Getting Started

To set up the project locally, please follow these instructions:

  1. To get started, you can perform a ```git clone``` of this repository on your local machine (see below). 

### Prerequisites

There are no prerequisites required to run the project. No additional software needs to be installed (besides versions of Python, Django, and Bootstrap as mentioned above).

### Installation

To install and run this project, please follow the instructions below:

1. Clone the repo
   ```sh
   git clone https://github.com/ccarpene/sse_project.git
   ```

2. Set your given username and password as your temporary local environment variables. These credentials have been given by Prof. Santos.

	perform ```sh
			export USERN={your username}
			```
		and ```sh
			export PASSW={your password}
			```
   
     Your values of USERNAME and PASSWORD will be used within the code to acquire the API access-token.

3. Go into the src/worndly directory

4. Run python3 manage.py runserver to start the website
