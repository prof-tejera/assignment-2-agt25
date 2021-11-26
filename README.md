# [Assignment 2: Functional Timers](https://main.d2i2lla75z6mqo.amplifyapp.com/timers)


# Notes
On the feedback for Assignment 1, you mentioned that Tabata and XY didn't have a round or rest input field. 
- You also stated that my timer was missing a way to show the current action like "run" or "rest". 

I've included screenshots, of my updated timer, to clear any confusion. You'll find that my Assignment 1 phases are the exact same. 

Is it possibly to go back and check the assignment 1 link? I replied to the Github comments, didn't receive an update, so I was confused as to what you were referring to, and what I had to change precisely on this update. Perhaps you forgot to play around with the fields and add a number to each? 

The screenshots below should clear up any confusion. 
For XY, I have: 1) a run input phase, and 2) a round input phase. 
- You can't get to the round input phase without entering a number on the run input phase. 
For Tabata, I have: 1) a run input phase, 2) a round input phase, and 3) a rest input phase. 
- The same procedure follows. 
- Each phase isn't enabled until you click "Next". 
  - The button, also, isn't enabled unless you enter a value for each input phase. 

## Run Phase (as seen on Assignment 1)
<img width="397" alt="run" src="https://user-images.githubusercontent.com/57548500/142510627-0a5cd291-c601-4a59-a74a-2cf0adbe1bab.png">

## Rounds Phase
<img width="415" alt="rounds" src="https://user-images.githubusercontent.com/57548500/142510692-49a83676-a769-4964-9cce-8ce0bf2035bd.png">


## Rest Phase
<img width="414" alt="rest" src="https://user-images.githubusercontent.com/57548500/142510722-6882ff46-e01e-4e15-b33b-eb67d5c384f1.png">
 
 
### PS, I also had the helper run/rest icons set up for assignment 1, along with the "Run" or "Rest" alert below the current time. The timer wasn't functional then, but they were there. 

<img width="94" alt="Screen Shot 2021-11-18 at 5 57 11 PM" src="https://user-images.githubusercontent.com/57548500/142510860-4589df89-11c7-4dc4-a4f9-56cf6cab2ac2.png">

<img width="433" alt="icon-helper-text" src="https://user-images.githubusercontent.com/57548500/142510964-02a3490b-5139-4357-831c-6c17051a0394.png">




# Objective
In this assignment, we will start using the foundation we lay in A1 and make our timers fully functional. Each timer will function as described in A1 and the user flow should be the following:

- User opens the application
- Select a type of timer (Stopwatch, Countdown, XY, TABATA)

- Configure timer based on type (time, rounds, work/rest, etc)

- Run timer. While running, user should be able to:
  - Pause/Resume
  - When paused, user can reset back to initial state
  - Ability to "fast forward" (ends the timer)

- When timer is complete, you can decide how to congratulate the user and allow them to start over or select a different timer

## Deliverable

- Convert all classes components that you have added to functional components. You are welcome to convert all components (including ones added by us), but this is not required.
- Get all timers functional
- Application state should be managed with context. That is, timers should NOT track time, rounds, etc, locally or pass it down to its children
- Make sure that you can switch between timers without breaking the app (e.g. I should not have to refresh in order to run another timer after a run has been completed)
- Update documentation as your components change. 
- Your application must be deployed and the link pasted somewhere in this README -> [Assignment 2: Functional Timers](https://main.d2i2lla75z6mqo.amplifyapp.com/timers)


## Grading Rubric 
- All components you have added are functional components
- All timers are functioning properly 
- Timers can be run one after another and it should not break the application
- Application state is managed with context
- DRY (do not repeat yourself). we should not see the same code copy pasted all over the codebase. 
- Console is free of warnings/errors

## Bonus
For people looking for an additional challenge, we have provided some bonus features that you can implement. These are not required! You can still get a 100% on the assignment without them.
- Before the timer starts, have a 10-second countdown to give user time to prepare (3pt)
- User settings
  - custom number of seconds before the timer starts (1pt)
  - configurable audio notifications (3-2-1-GO, halfway, 1 minute left, last round, beep every minute, etc) (1pt)
- Persisting state so refreshing the page does not clear application state. (2pt) 

## Installing and Running the project

As you have noticed this repository is empty. To begin this assignment you must copy over all of our files from A1 into this repo. I recommend not copying over `node_modules` and instead re-install here. You can then commit and deploy as usual from this repo.


