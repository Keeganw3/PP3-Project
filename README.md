# Daily Planner
## Project Description
<p> Daily Planner is a command line application to help you plan out what you would like to do in a day no matter what that may be!

The user can input all the activities they would like to do and the application will give them back to the user in a list for them to do as they please.
</p>

# Features
## Existing Features
## Main Menu
* The user is told what the program is and how to use it. This leads to the main menu where the user is given all the options for what they can do with the daily planner in a straightforward and easy to read format. 
* The first 4 options are suggestions for their schedule and option 6 lets the user make their own option. The user can leave the program whenever they're on the menu by clicking 7.
screenshot()

* The user will always be shown their current list everytime a value has been added to them. 

* The user is asked to enter a number from 1-7. If they use a number outside of this range an error is displayed which asks the user pick a number within this range and returns them to the main menu. (add extra enter?)
screenshot()

## User created options
* The user can make their own options to be added into their list plans for the day. The user can do this as many times as they want and the input can be as long as they desire to give full flexibility to the user.
* The user can exit this prompt by typing 'exit' if they came in here by mistake. This will not affect the user's list and they will be returned to the main menu.


## Header
* This tells the user the name of the quiz.

![Screenshot](/assets/screenshots/header-screenshot.png)


## Question Container
* This section shows the questions being asked to the user.

![Screenshot](/assets/screenshots/question-container-screenshot.png)

## Game Area
* This area is for the placement of the answers. 
* The user can select an answer to the question being asked in the question container.

![Screenshot](/assets/screenshots/game-area-screenshot.png)

# Future Features to be added 
## Results page
* This would open a new page that would tell the user what their score was and the amount of money they won.
## Animated header
* This would flash at the user to how the game show Who Wants To Be a Millionaire Logo did.
## Randomised Questions
* This would've made it so different questions are asked on each attempt. This would be limited to 3 attempts.
## Halting Progress
* The user would have to restart from the beginning when they got a question wrong. This would've made the game more difficult to play through.

# Technologies Used
## Languages Used
* Python

## Programs Used
* lucid.app: used to create the flowchart for this project.
screenshot()(detail?)
* Git: used for creating the code for this project and sending it to GitHub.
* GitHub: a repository for the code after being made in Git.
* Heroku: used to deploy the application and hosts a page for the code.

# Testing
## Validator Testing
### Python Testing
* No errors or warnings were found through the PEP8 online validator.
![Screenshot](/assets/screenshots/pep8_validator_screenshot.jpg)

## Manual Testing
I tested the media queries by manually adjusting the screen size from roughly 500-1000px to make sure the correct changes were taking place above or below each specific screen size.

For media queries 768px, 500px and below the text across the website is shrunk in order to maintain a clear structure on smaller screens and the logo was slightly adjusted. Media queries weren't needed at sizes larger than this.

## Known Bugs
When creating an option to be used the code will ask you for it twice. This doesn't happen if exit is used the first time the user is asked but if it is used when prompted the second time it will add this to the list. Using exit the first time won't add it to the list. I couldn't figure out why this problem happened.

# Deployment
For all of the below steps you must head to Github.
* Log into Github
* Load up the required repository.
* Go to Settings and scroll down to Github pages (this will open up a new webpage).
* Click on the dropdown menu called "None" and then select "Master Branch".
* A second dropdown menu should appear that says "/root" and a button that says Save.
* Click Save and now the link for the website has been made.

# Acknowledgements

## Credits
* My mentor Brian Macharia who supported me and provided me with both feedback, examples and solutions to problems I faced while creating this project.
* Code institute for the classes, sources and tutors that they provided me.