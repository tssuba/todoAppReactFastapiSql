# Simple To-do App
 
Using React, FastAPI, and SQLite

## Description

* Simple To-do Application
* User can create, update, and delete to-dos and also collectively delete all
* Audit columns present
* Additional Authentication module thanks to the references listed below
* API has CRUD endpoints to GET, UPDATE, DELETE specific, and all /todo/{id} , referred to as leads in the API
* Additionally, I have also hosted the backend on heroku and the frontend on netlify, accessible on the domain https://app.tanmaysuba.com/

## Getting Started

### Dependencies

* React
* FastAPI (pip3 package)
* SQLite
* SQLAlchemy (pip3 package)
* pyjwt (pip3 package)
* passlib[bcrypt] (pip3 package)
* bulma (npm)
* moment (npm)

### Run it Locally

* Backend (while in directory)
```sh
source venv/bin/activate
uvicorn main:app --reload
```
  
* Frontend:
```sh
npm start
```

### References

* Stackoverflow
* SQLAlchemy docs
* Google
* Youtube
* Backend based on https://www.youtube.com/c/rithmics
