<h1 align="center">NFL Trivia Game</h1>

This Website is a single webpage built with HTML, CSS and Javascript. It's a niche interest quiz-based game designed for NFL fans as the primary target audience, although anybody can try it. The rules of the game are similar to American football, mainly in that the player has 4 chances to increase their score before it's game-over, and like in a real NFL game, these chances are called downs. When the player gets a question right, the avatar advances 10 yards up the field and 10 points/yards are added to the score/total yardage, and the downs reset to 1st down. This visual representation of a real NFL game being powered by the player's progress in the quiz below creates an immersive user experience.

## Table of Contents
* [User Experience (UX)](#user-experience-ux)
* [Features](#features)
* [Design](#design)
* [Technologies Used](#technologies-used)
* [Testing](#testing)
* [Deployment](#deployment)
* [Credits](#credits)

## User Experience (UX)

-   ### User stories

-   #### A. New User Goals

1. As a new user I can quickly see what the theme of this quiz is from the design so that I can determine whether I will enjoy the content.
2. As a new user I can easily access information regarding the rules of the game so that I understand how to play it.

-   #### B. General User Goals

1. As a user I can play through the game so that I can see my score at the end.
2. As a user I can feel challenged by this game so that it isn't boring.
3. As a user I can replay the game so that I can try and beat my last score.

## Features

### Existing Features

-  #### Quiz area

- The quiz area is the primary user interface on the webpage. The features at the top reflect changes the user makes, but this section is where the user will interact with the game directly by inputting their answers. There are 15 questions in total, although if the player is knowlegeable or lucky, they may win the game with just 10 questions. There are 4 answer buttons which react when hovered over by the user, and will turn green if the correct answer is selected, or red if a wrong answer is selected. The user will have time to see these effects before the next question is loaded.

![quiz-area](/assets/documentation/something.png)

- #### Hero image and title

- The hero image on this webpage is very unique due to the fact that it changes to reflect the player's score throughout the quiz. This helps create an immersive experience and allows the player to visualise how far away they are from winning the game.

![Hero-image](/assets/documentation/something.png)

- #### downs counter

- The Downs counter is a feature which makes the game more challenging. Now if a user fails 4 questions in a row, it will trigger the game-over pop up. However, giving a correct answer will reset the down counter back to 1.

![downs-counter](/assets/documentation/something.png)

- #### total yardage tracker

- The total yardage tracker tracks the user's overall score and displays it as "yardage" at the top of the screen. The score increases by 10 points/yards with every correct answer to further simulate a real NFL game. 

![total-yardage](/assets/documentation/something.png)

- #### time left tracker

- The time left tracker displays the number of questions left before the game ends. This works in a similar way to a game clock. I chose the number of questions to be 15 as that is how many minutes per quarter in an NFL game. This also means the player can win the game even with 5 answers wrong. This feature allows them to keep track of that so they can work out how close they are to winning or losing the game.

![time-left](/assets/documentation/something.png)

- #### start modal and options modal

- This is a key feature for the webpage as the rules of this game are not immediately obvious, especially to users unfamiliar with the structure of NFL games. For this reason I thought it would be vital that the rules are displayed both at the start when the page first loads, and are also available to be checked at any point during the game via the options menu. The options menu also has a restart button so that the player can restart the game at any point, this might be useful if they can see that there is no way for them to win their current game from where they are at.

![modals](/assets/documentation/something.png)

- #### game over modal

- The game over modal loads at the end of the game. This can be triggered for a number of reasons. It will load when the down counter reaches more than 4 downs, when a score of 100 has been reached, or when all the questions have been played, whichever happens first. At the moment, the pop up displays the user's score in yards and invites them to play again with a button, which reloads the page when clicked.

![game-over](/assets/documentation/something.png)

### Future Features

- #### Updated Game-over Modal

- In a future update, the modal should give the user tailored feedback based on their score. For example, a score of 100 could display a "touchdown" image, a score of 0 could display an "oh no" image, while other scores in between offer increasingly positive images and messages.

- #### Sound effects

- Sound effects such as a cheering crowd for correct answers and a worried crowd sound for wrong answers could add more atmosphere to the game in a future update.

- #### Leaderboard

- A leaderboard for players to save scores and compare with other players would greatly improve the game.

- #### Multiplayer

- An option to make the game multiplayer would also be a great improvement for a future update. In this version, players could play with their friends or an online opponent. Instead of the game ending completely after 4 downs, it would just end that player's turn and allow their opponent to play and move their own avatar across the field from the opposite direction.

- #### more questions

- Finally, the number of questions could be increased. They could also be categorised into packs based on difficulty which the player could select and the order could be randomised as well.

## Design

-   ### Images
- The Hero image shows

- the modal images offer feedback based on score

-   ### Colour Scheme
-  The colour scheme was taken from the colours of the NFL logo.

-   ### Typography
- The majority of the font for the website is white in colour, as this improves accessibility with the chosen background colours. Google Fonts were used to import Jaro and Archivo fonts into the project. These were chosen as they are clear and easy to read.

-   ### Wireframes

- #### Game Wireframes

![Game](/assets/documentation/something.png)

- #### modal Wireframes

![modal](/assets/documentation/something.png)


## Technologies Used

### Languages Used

-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
-   [Javascript](https://en.wikipedia.org/wiki/JavaScript)

### Frameworks, Libraries & Programs Used

-   [Google Fonts:](https://fonts.google.com) was used to import the 'Permanent marker' and 'East Sea Dotko' fonts into the style.css file which are used on all pages of the project.
-   [Font Awesome:](https://fontawesome.com) was used to add icons for aesthetic and UX purposes.
-   [Git:](https://git-scm.com) was used for version control by utilising the Gitpod terminal to commit to Git and Push to GitHub.
-   [GitHub:](https://github.com) is used as the respository for the projects code after being pushed from Git.
-   [Canva](https://canva.com/en_gb/) was used for creating the hero image and it's alternates.
-   [Bitmoji](https://www.bitmoji.com/) was used for creating the player image for the hero image.
-   [Balsamiq:](https://balsamiq.com) was used to create the wireframes during the design process.

## Testing

### Validator Testing

- [HTML Validator](https://validator.w3.org)

- results for index.html
![HTML results for Game](/assets/documentation/something.png)

- [CSS Validator](https://jigsaw.w3.org/css-validator/)

- result for style.css
![CSS results for Game](/assets/documentation/something.png)

- [JavaScript Validator](https://jshint.com/)

- result for script.js
![Javascript results for game](/assets/documentation/something.png)


### Browser Compatibility

- Testing has been carried out on the following browsers :
- Chrome
- Firefox
- Edge

### Known Bugs

- Check rules bug

![something](/assets/documentation/something.png)

- Downs suffix bug

![something](/assets/documentation/something.png)

### Responsive design

- testing and editing in progress

![something](/assets/documentation/something.png)


## Deployment

### How The Website Was Deployed

* In the GitHub repository, navigate to the Settings tab, then choose Pages from the left hand menu.

* From the source section drop-down menu, select the Master Branch.

* Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

* Any changes pushed to the master branch will take effect on the live project.

* Live link to the live website can be found [Here](https://frazer-bc.github.io/NFL-Game-Project/).



## Credits

### Code

* [W3Schools](https://www.w3schools.com) used for reference as a learning resource.

* [StackOverflow](https://stackoverflow.com/) used for reference as a learning resource.

* Chat GPT - used for correcting some errors and bug fixes.


### Media

* The icons in the time and score display div were taken from[Font Awesome](https://fontawesome.com/)

* The fonts used were imported from [Google Fonts](https://fonts.google.com/)

* Image of the football field in the hero image came from [Canva](https://canva.com/en_gb/)

### Additional content

* Lindy's Sports Pro Football volume 37, 2023 Preview was used for fact-checking one question.

### Aknowlegements

Thank you to my mentors, Elaine and Mark who helped resolve some technical issues and provided support. 