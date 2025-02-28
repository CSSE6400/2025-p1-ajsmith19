[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=18409421)
# CSSE6400 Week 1 Practical

Construction of a simple HTTP server in Python.

Please see the [instructions](https://csse6400.uqcloud.net/practicals/week01.pdf) for more details.

There are [resources](https://www.makeareadme.com) available to help you write a good README file.

## Running the API
To install flask, run:
poetry add flask

If flask needs updating, simply run (this will generate the poetry.lock file):
poetry update flask

To run the API on port 6400, run on a terminal:
poetry run flask --app todo run -p 6400