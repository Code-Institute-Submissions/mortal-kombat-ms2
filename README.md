<h1 align="center">Mortal Kombat</h1>

<h2 align="center"><img src="/documentation/mk-header.jpg"></h2>

# Table of Contents <a name="Home"></a>

1. [Project Introduction](#introduction)
2. [UX](#ux)
3. [Design Choices](#designchoices)
4. [Wireframes](#wireframes)
5. [Features](#features)
6. [Technologies Used](#techused)
7. [Testing](#testing)
8. [Deployment](#deployment)
9. [Credits](#credits)
10. [Acknowledgements](#acknowledgements)
11. [Disclaimer](#disclaimer)

## Project Introduction <a name="introduction"></a>
The Project I have created is a Memory Card Flip game with an added theme of Mortal Kombat.
The premise of this game is simple, find the matching pair of cards to win the game.

As i centered the memory game around a fighting game, I wanted to add my touches to it. By this I mean
a typical card game has a feature that tracks how much flips were made etc. In my project, i added a fight counter
which is tracked via a unmatch or a match. If the user matches cards, they are allocated 3 points.
In a fighting game a round consists of 3 rounds, so scoring 3 rounds wins you the game. I wanted to add this concept to 
my project, so by scoring a pair, you win a fight and have won 3 points.
However, by matching 2 different cards/fighters, you lose the round and lose points which will take you into the negatives.

This feature was important to add for me as I centered the project around a fighting game. So the cards represent the fighters and
the flips represent the fights won counter.

<h2 align="left"><img src="/documentation/mk-fight-win.png"></h2> <h2 align="right"><img src="/documentation/mk-fight-loss.png"></h2>

To view my live project, please click the link below. I hope you have fun playing the game as much as I do.

[View My Live Project Here](https://shazaiib47.github.io/mortal-kombat-ms2/)

## User Experience (UX) <a name="ux"></a>

- ### External User Goals

    - As a User who plays the game, I want to be able to have fun playing the game.
    - As a User who plays the game, I want my effort to be recognised whilst playing.
    - As a User who plays the game, I want the game mechanics to be straightforward to understand.

- ### Site Owner Goals

    - As the site owner of the game, I want to share the same experiences as the visitor and
    have fun playing the game as well.
    - As the site owner of the game, I want to be able to view all the elements of the game on 
    a single page to prevent scrolling.


## Design Choices <a name="designchoices"></a>

- ### Font Selection

    - As my project was centered around the theme of Mortal Kombat, finding the right font was
    imperative for me. As there was no font just as replicated like the font In Mortal Kombat, I 
    had to find a similar one.

        The font I had chosen for the game was [Spectral SC](https://fonts.google.com/specimen/Spectral+SC?query=spec).

    <h2 align="left"><img src="/documentation/mk-font-preview.png"></h2>  
    
    <h2 align="right"><img src="/documentation/mk-text-preview.png"></h2>

    As Shown in the images above, the font comparison is relatively the same in some aspects. This had narrowed down
    my search for a good font and Spectral SC looked like a very ideal font for my game.


- ### Colour Choices

    - As my game was themed around Mortal Kombat, the colour choice in the  game had to represent the colour's
    used in the game for added imersion and to ensure it matched with no contrast.

    - Both the colours used on the card and also the background had matched very well. The background of the front facing
    card had touched quite well with the theme of the game. As I kept the user audience in mind, colour choice was important
    as the creator of the game to ensure there was no distracting elements for the user.

    <h2 align="center"><img src="/documentation/mk-colour-palette.png"></h2>

- ### Cards & Styling

    - In terms of styling the cards I had to think carefully as to how I would want them to be
      so the user has no trouble interacting and it would be clear for them to click with no errors.

    - The cards were styled entirely in CSS with the added image elements, both front and back added
    in the HTML along with sizing and marginal properties applied. Colour theme was taken into consideration 
    here too and I also added a colour background to the cards as well as the images themselves.

    <h2 align="center"><img src="/documentation/mk-headerinput.png"></h2>

    - As shown above, both the front face and back face cards have respective styling towards them. There is also 
    the background behind the front facing cards that reflect the overall theme.

- ### Background Wallpaper

    - The background wallpaper was an important element to also consider as it Had to be relevant to the theme of Mortal
    Kombat, but also not too flashy or distracting for the user so certaine elements are not hidden.

    - The background image for the game was taken directly from the official Fandom Wiki for [Mortal Kombat](https://mortalkombat.fandom.com/wiki/Mortal_Kombat_Wiki).


## Wireframes <a name="wireframes"></a>

-  Wireframes for the game were developed and created in [Balsamiq](https://balsamiq.com).
There are no major contrasts between the wireframes and the final product, but there have been minor added
tweaks such as the overlay instructions added, but all the designs were final.

- Wireframes for the game can be found [here](documentation/wireframes/ms2-mortalkombat.pdf).

## Features

- Interactivity Implemented in game so animations show when a card is flipped.

- Responsive on large devices to ensure the full immersiveness of the game is experienced.

- Fight Counter replaced for Flips for full immersion of the game and to keep track for a competitive edge
to beat your previous record.

- A Back button now implemented for users to return to home page to view instructions. This was added for ease of
accessibility. *Added on 20/10/2020*

### Future Features to Implement.

- A timer to track progress and for the user to have a competitive edge if they wish to beat their previous record.

- Difficulty section which scales from Easy (12 cards), Medium (16 cards), and Hard (24 cards).

- Audio Cues such as music, vocal feedback once a card pair has been matched, and also the iconic Mortal Kombat theme song.

## Technologies Used <a name="techused"></a>

- ### Languages Used

   - [HTML5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
        - Used within the game for the main language to implement text and the structure.
    
    - [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS)
        - Used to style the elements of the game, mainly the cards, text and also added animations
        and transitions.
    
    - [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
        - Javascript used to bring the game together and works as intended.

- ### Frameworks, Programs, and Libraries Used.

    1. [Google Fonts](https://fonts.google.com)
        - Google Fonts Website was used to import the 'Spectral SC' font into the CSS file to be used within
        the game.
    2.  [Git](https://git-scm.com/)
        - Git was used for version control by using the gitpod terminal to commit, add and push changes for my project to Github.
    3.  [GitHub](https://github.com)
        - GitHub was used to store the code from the project after it was pushed via Git.
    4.  [Balsamiq](https://balsamiq.com/)
        - Balsamiq was used to create the wireframes during the design and initial process.
    5.  [HTML Formatter](https://www.freeformatter.com/html-formatter.html)
        - HTML Formatting tool was used to beautify and indent the HTML Code for the game.
    6.  [CSS Formatter](https://www.freeformatter.com/css-beautifier.html)
        - CSS Formatting tool was used to correctly indent and format the CSS within the style.css file.
    7.  [jQuery](https://jquery.com/)
        - jQuery library was used to make HTML and the JS much easier to use and implement via their API.
            This made implementing event handling, animations and manipulating much easier.
    8.  [BootStrap](https://www.bootstrapcdn.com/)
        - BootStrap was used for responsiveness across devices and to ensure minimal margin errors.
    9. [Autoprefixer CSS Online](https://autoprefixer.github.io/)
        - This was used to prefix my CSS that parses it and applies vendor fixes. Used this for the front-face image not showing on iOS Devices.


## Testing <a name="testing"></a>

Three tools were used to validate and test the integrity of my project:

[W3C Validator](https://jigsaw.w3.org/css-validator/#validate_by_input)
- This tool was used to validate and check the integrity of the CSS File.

    Results for the validity of the CSS can be found [here](documentation/css-validator.png)

[W3C Markup Validator](https://validator.w3.org/#validate_by_input)
- This tool was used to validate the integrity of the HTML page for any warnings or errors. There are no errors but warnings
show in regards to better header names, but this does not affect the integrity of the game state.

    Results for the validity of both the HTML's can be found [here](documentation/html-game-validator.png) and [here](documentation/html-index-validator.png)

[JSHint](https://jshint.com/)
- This tool was used to validate and check the Javascript page for any errors shown throughout the game as well
as warnings

    Results for the JavaScript validator can be found [here](documentation/js-code-validator.png)

### Testing User Stories from UX Section

 - "As a User who plays the game, I want to be able to have fun playing the game."
    - The memory game is themed around Mortal Kombat, which is a fighting game and also contains
    a counter as to how many fights the user has won, which adds to the fun as well as the wide array of fighters.

    <h2 align="center"><img src="documentation/mk-fight-counter.png"></h2>

- "As a User who plays the game, I want my effort to be recognised whilst playing."
   - Feedback in a game such as this is important. At the end of the game upon finding all pairs, the user is greeted
    with a message which recognises the user's ability and grants them victory as well as granting the user as a champion
    which in the Mortal Kombat universe is a huge achievement.

    <h2 align="center"><img src="documentation/mk-victory-screen.png"><h2>

- "As a User who plays the game, I want the game mechanics to be straightforward to understand."
    - The game mechanics here are relatively straightforward, the user must click on a card to reveal a fighter, followed 
    by clicking another card to check for a match. If both fighters are matched then the user wins that round.
    - There is also instructions added before the game starts, allowing the user to understand how to play before pressing 
    the button that will take them into the game.

    <h2 align="center"><img src="documentation/mk-instructions.png"></h2>

### Further Testing

- This project was tested through multiple browsers; Chrome, Firefox, Opera and Microsoft Edge for validity.

- The project was viewed on multiple devices, iPhone XS/X/6, Desktop, Laptop, iPad and Huawei P30 Lite.

- Continuous testing of the flip effect to ensure this operated as it was supposed to.
    - I had trouble scripting the flip element for the cards as when clicked to flip, no front-facing image
    would show. After finding relative solutions, the issue was due to grammatical errors which I had discovered later.
    Both the front-face and back-face were stacked onto each other and i had to apply the backface-visibility to visible 
    in order for  the back face to show once flipped.

    - The Flip scripting was an element that had taken me quite some time to get my head around.

- Family members were asked to test the game for me on their phones and their stories can be found below;

### Further Testing (Family Stories)

- "When opening the game on my phone the instructions were brought up first which allowed me to know how to play
the game and the button directed me to the main game" - iPhone XS

- "My feedback was recorded at the end of the game as it informed me I had won and was now the challenger. This had a 
replay effect and had played again to beat my previous score. A good touch" - Amazon Fire Kindle

- "The cards animate and flip as intended and the colour theme matched quite well with no overlapping elements." - Galaxy S7.

- "Couldn't fault anything within the game, very good optimisation for my phone". - Huawei P30 Lite.

### Known Bugs

- Viewing the game on iOS Devices causes a display glitch, where the front-face cards do not show when the user
touches a card to flip. Instead they are greeted with the back face card rotating.
This can be seen below.

<h2 align="center"><img src="documentation/mk-ios-snap-edited.jpg"></h2>

- As you can see above this is what the bug looks like. The front-face image does not show, however after getting into
contact with Tutor Support at CI, they had informed me this bug is common on iOS Devices and is related to the Operating System, and if i was to alter this,
it would affect the whole visibility on Android and Desktop devices.

<h2 align="left"><img src="documentation/tutor-feedback.png"></h2>
<h2 align="right"><img src="documentation/feedback-ci.png"></h2>

- Given the feedback above, as well as some help from my mentor; i decided not to fix this bug, as it could conflict with the project as a whole
and would possibly react differently on other devices and computers etc. My mentor had also stated to leave this untouched and I plan on finding another solution/workaround.

- A change I did make which made a subtle difference was using [Autoprefixer CSS](https://autoprefixer.github.io/) and adding in a -webkit-backface-visibility
property. This is reflected in my CSS.

## Deployment <a name="deployment"></a>

###  Github Pages

This project was deployed to github by following these steps below..

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
4. Under "Source", click the dropdown called "None" and select "Master Branch".
5. The page will automatically refresh.
6. Scroll back down through the page to locate the now published site [link](https://github.com) in the "GitHub Pages" section.
7. You have now deployed the project and this process is completed.


## Credits <a name="credits"></a>

### Code 

- All code content, including HTML, CSS and JavaScript was directly inputted by myself as the developer of the game.

- Inspiration to make a card flip game came from [Scotch IO](https://scotch.io/tutorials/how-to-build-a-memory-matching-game-in-javascript)
who provided the necessary instructions in order for me to understand what was being done and how I should code my game.

- The Flip Effect for the cards was implemented in my game with tips from [W3 Schools](https://www.w3schools.com/howto/howto_css_flip_card.asp)

- The Data Attribute usage came from [W3 Schools](https://www.w3schools.com/tags/att_data-.asp) who helped me implement the Attribute
to store custom data's on HTML elements.

### Content

- Colour properties and additional hex values was added from [Hex Colour Tool](https://www.w3schools.com/colors/colors_picker.asp).

- The shuffle method that I implemented for the cards came from [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random)
who helped implement this method correctly with no errors.

- Content of website was made in pre planning phase by forming Wireframes to project a structure as to how my game should pan out.

### Media

- Images that were used for the front face of the card as well as the backface of the card, were taken directly
from the 'Mortal Kombat 9: Komplete Edition' game that I own respectively on [Steam](https://store.steampowered.com/) and courtesy
of [NetherRealm Studios](https://www.netherrealm.com/games/) for providing me the license to play the game and use its content.

<h2 align="center"><img src="/documentation/mk-steam.png"></h2>

<h2 align="center"><img src="documentation/mk-game-char-select.png"></h2>

- As shown above, there are a wide array of characters available but incorporating them all would have made it difficult for me
in terms of their positioning and layout. A future feature I intend to implement is the difficulty as shown above which incorporates
most additional characters and if provided I can arrange the formatting, then all can be included.

## Acknowledgements <a name="acknowledgements"></a>

- My mentor, Aaron Sinnott. For the continuous help and tips provided to me to ensure I was doing my best. For also providing me with a basic README file to ensure I knew 
  how to structure my own README.

- The Slack community for providing help on JS variable and const formatting and usage.

- [Stack Overflow](https://stackoverflow.com/questions/37361805/memory-game-in-javascript-css) and
[W3 Schools](https://www.w3schools.com/js/js_best_practices.asp) for helping with JS Best practise and further
assistance with JS game development.

- [Mortal Kombat](https://www.mortalkombat.com/) for providing and developing the game series that had a massive impact
on my childhood and also providing the content required for producing the game centered around Mortal Kombat.

- [Code Institute](https://codeinstitute.net/full-stack-software-development-diploma/) for the course material and their inspiration from challenges and mini projects.

- The Tutor Team at CI for assisting me with the iOS bug and providing me with solutions to make it easy for me and to ensure I was doing my best to resolve this issue.

## Disclaimer <a name="disclaimer"></a>

*This game and the content involved was developed for educational purposes.*

