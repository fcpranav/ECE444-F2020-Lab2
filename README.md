# ECE444-F2020-Lab2
Lab 2 of ECE444 at University of Toronto

My name is Pranav Patel and this repo is a clone of https://github.com/miguelgrinberg/flasky.

## Activity 1

![Image of Activity 1](/static/images/ECE444-Lab-2-Activity-1.png)

## Activity 2

![Image of Activity 2](/static/images/ECE444-Lab-2-Activity-2.png)

## Activity 3

Briefly summarize what are the Flask context globals.

Flask context globals are variables view functions automatically have access to when handling requests. Flask has four context globals: current_app, g, request and session. current_app is a reference to the application that is handling the current request. g is an object whose scope is the lifecycle of a single request. You can use this object to store temporary state for a request being handled. request provides information on the current request being handled. This includes HTTP request type, body, etc. session is a reference to the current user's session. You can use a session to persist information about a user across multiple requests. The session might include user authentication information.
