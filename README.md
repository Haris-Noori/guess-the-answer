# Guess The Answer

Guess The Answer is a simple and quick quiz game for users who want to increase their general & IQ knowledge. By playing the game, making the correct & incorrect choices, they will remember and memorize the answers. This website is available globally for anyone from anywhere in the world! 

![Responsice Mockup](https://github.com/Haris-Noori/guess-the-answer/blob/main/assets/img/AmIResponsive.png)

## Features 

Some of the features are existing and there alot more features to come in next release.

### Existing Features

- __Navigation Bar__

  - A full responsive navigation bar, which shows the quiz game logo.

![Nav Bar](https://github.com/Haris-Noori/guess-the-answer/blob/main/assets/img/navbar.png)

- __The Main Game Section__

  - This is the main section of the website where user will interact first.
  - User will read the instructions first, and then select the option that he think is correct

![Main Game Section](https://github.com/Haris-Noori/guess-the-answer/blob/main/assets/img/main_game_section.png)

- __Selecting Option__

  - After Selecting the one option, if the answer is right the selected option will turn intor green, and if it is not then, the selected one will turn red and the other correct option will turn green automatically.

![Right Option](https://github.com/Haris-Noori/guess-the-answer/blob/main/assets/img/right_option.png)

- __Wrong Option & Progress Bar__

  - This is how the wrong option screen look like. 
  - When next button is pressed, the progress bar also change.

![Wrong Option](https://github.com/Haris-Noori/guess-the-answer/blob/main/assets/img/wrong_option.png)

- __The Footer__ 

  - The footer section displays the name of the game, and the company or developer, who made this game website.

![Footer](https://github.com/Haris-Noori/guess-the-answer/blob/main/assets/img/footer.png)

- __Score Section__

  - When all the questions are attempted by the user, this screen will change and it will display the score of the user. 

![Score](https://github.com/Haris-Noori/guess-the-answer/blob/main/assets/img/score.png)

### Features Left to Implement

- We can also Store the last score of user, to show him the improvements,

## Testing 

While working on the project at intial stage, after creating the structure with HTML, when I attached my style file and javascript file. It was not displaying any change, the styles were not working, and no actions were taken place when pressing te buttons. To figure this out, I inspectedmy site on chrome, and I found out that there is no css, and script file are linked.
I changed the path to read files, removed the first 'slash' from the path, and then restart the server, everything worked perfectly.


### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fharis-noori.github.io%2Fguess-the-answer%2F)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fharis-noori.github.io%2Fguess-the-answer%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

### Unfixed Bugs

No unfixed bugs to left.

## Deployment

How this project is deployed on GitHub Pages

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Main Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

  How you can deploy on your environment

  - Go to the repostiry link https://haris-noori.github.io/guess-the-answer/
  - Select the green "Code" dropdown button
  - copy the repo URL and open your system terminal
  - type in your terminal ```git clone <URL>```, and enter
  - then cd into project directory
  - start the server with ```python3 -m http.server```
  - and it will start running on your local IP, e.g, https://127.0.0.1/, try going to this link on your browser

The live link can be found here - https://haris-noori.github.io/guess-the-answer/


## Credits 

I would like to give credits to:
- PixaBay, for the logo image, https://pixabay.com/
- Google FontAwesome icons, for the beautiful icon in the footer, https://fontawesome.com/v4/icons/ 
- Online Convert, for converting the images into favicon, https://www.online-convert.com/

