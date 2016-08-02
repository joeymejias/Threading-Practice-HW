---
title: Threading Practice
type: Homework
duration: "1:00"
creator:
    name: Drew Mahrt
    city: NYC
---

# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Threading Practice

> ***Note:*** _This should be done independently._

## Exercise

When you created Project 2, all of your interaction with the database was done on the main/UI thread. The best practice is to make all interactions with databases (local or remote) asynchronous since there could be delays accessing them. Go through your Project 2 code, and modify it to meet these best practices using `AsyncTask`s.

#### Requirements

- Make all of your Project 2 database calls (reading/writing) asynchronous

**Bonus:**

- If your app included internet access, make that asynchronous too

#### Starter code (if needed)

Use your own Project 2 code.

#### Deliverable

Submit your modified Project 2 app that meets the requirements above. Commit your changes to your existing Project 2 fork, and push that commit to Github, where it will automatically be added to the open pull request you already have for Project 2. If for some reason you don't have an open pull request for Project 2, open a new one.

You do not need to fork or submit a pull request to _this_ repo; just do the required work in your Project 2 repo.
