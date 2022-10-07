# Zeniark ReactJS Coding Challenge

## Overview

Your challenge is to create a simple, 10 question, true or false, trivia app in the technology you are familiar with. While the problem you are working on is simple, you should treat this like a real world application. This is a chance to show off your abilities and impress.

**What we are looking for through this challenge:**

- Functionality
- Code Format
- Project Structure
- Scalability
- Maintainability
- Use of industry best practices

## Goals

Implement the screens based on the wireframes below using advanced techniques and industry best practices for your platform. Note that the wireframes may not be complete, so use your best judgment for UI/UX implementation. **Do not use a boilerplate like React Boilerplate for this challenge.** We want to see how you structure your project and what tooling you use from scratch. Create react app is fine to use. Using NextJS is a PLUS! 

## Steps

#### 1. Fork this repo and use web-app folder as code boilerplate to start or you can create a fresh react-app.
#### 2. Data: Feel free to do whatever you prefer in pulling data.
Do either of the ff:
- You can check file under `mock-data/questions.json` and do API data mocking. 
- Or you can have the data under `mock-data/questions.json` and directly code/put it to state/local state.
- Or you can setup nodejs server and do API request (PLUS Points!)

#### 3. UI requirement:
We provide the design for the trivia app. You can check the figma file [here](https://www.figma.com/file/6r4GIfxp3s9VXPq95KK9Gf/Zeniark-Coding-Test?node-id=0%3A1). You don't need to follow exactly the same if you do not have enough time. We want to see your general HTML/CSS skills and how you behavior when converting a design into a real product. `(Logo and background image are located in web-app/src/images)`

### Intro / Home Screen:

![The Intro screen for the app](screenshots/intro-screen.png "The Intro screen for the app")

- Static Text
- LET'S START button navigates to the Quiz screen and starts the Quiz

### Quiz Screen:

![The Quiz screen for the app](screenshots/question-screen.png "The Quiz screen for the app")

- The headline is from question category
- The card element contains the current question
- The next question should appear after the current question is answered True or False
- After all questions have been answered, navigate to the Results Screen

### Results screen:

![The Results screen for the app](screenshots/results-screen.png "The Results screen for the app")

- The Score shows correct and total
- Displays a list of the questions and whether the answer was correct or not
- PLAY AGAIN starts over with new set of random questions and navigates to the Home Screen

## Submission

Please use git for version control and platforms like Github to host the repository. Once you have finished your challenge, send us the repository url. It would be even better if you can have a documentation for how to run your code in our environment.

HAPPY CODING!


~ Chrisl.Zeniark
