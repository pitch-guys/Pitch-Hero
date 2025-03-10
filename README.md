# Pitch-Hero

## Play Now
Click [here](https://pitch-guys.github.io/pitch-hero/)!

## Project Description
Pitch Hero is a gamified pitch trainer intended to motivate users of all musical levels to improve their relative pitch sense and singing skills. The game is played in   the web browser and involves the user singing different pitches to dodge the incoming obstacles. If the player collides with an obstacle, their final score is displayed   and the game ends. Through practice, the player's pitch skills will improve and they can beat their previous high scores, placing them on the leaderboards for everyone     to see!

## Operational use case
User is able to sing a certain pitch to control Bibby's height and attempt to survive going between the pipe's gaps. Users can see their score displayed in the corner.

## User Manual
### Installing and Running
  Pitch Hero is a browser game thus no additional installation is required. The game can be found and run at the link above where it says "Play Now".
### Playing the Game
  Press START and allow microphone access to start the game. The user can set the minimum and maximum pitch values for the game in their respective boxes. Changing the pitch of your voice will move the trumpet up and down, allowing you to navigate through the pipe gaps safely. The game can be paused (via the pause button) or reset (via the reset button) any time should the user need a break. The user can also change the game difficulty by clicking one of the game difficulty buttons (easy, normal, or hard). When the trumpet hits an obstacle, the game terminates and prompts the user to enter a username to represent their high score.
  
 ### Reporting a bug
  If you find a bug with the application, you can report this bug as an issue in the "Issues" tab on our github repository!
  Please follow the issue template below:
  Title: [relevant name]
  
  Bug description (10 words or less):
  
  Steps to reproduce:
  
  Browser used:

## Developer Manual
### Source Code
  All source code can be found in the /src/ folder.
### Directory Layout
  ├── public/: Public-facing assets for the project<br>
  ├── src/: Project source files; Typescript, CSS, HTML<br>
  |   ├── tests/: Unit test suites<br>
  |   ├── data/: Hardcoded sample data<br>
  |   ├── contexts/: Context objects<br>
  |   ├── libs/: Common objects<br>
  |   └── types/: Common types<br>
  └── reports/: Weekly status reports<br>
### Building 
To contribute to this project, clone the repository.

Then, to build and run the project, run the following commands in the root folder:
```
    npm install
    npm start
```

This will start the React development server, which hosts the web app.
### Releasing the software
  To build and release an updated version of all system components, run the command "npm run deploy". This will build an optimized version of the project and then commit this to the github pages where the application is hosted online.
### Testing and creating tests
  In order to run the test suite for the system, run "npm test" in the terminal, and Jest will automatically run all of the test files which end with test.tsx.
  When creating new tests, if the tests are for the general app, they can be put as a new test inside of test.tsx. Should it need to reference external hardcoded data, the data should be placed in the \_data\_/ folder and exported from there.
  
  Otherwise, if the tests are for a specific implementation, navigate to the \_\_tests\_\_/ folder and create a new folder or add a new test.tsx file.
  e.g. basic-test.tsx
