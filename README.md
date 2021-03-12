# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Zhongxian(Martin) Zeng**

Time spent: **3** hours spent in total

Link to project: (https://glitch.com/edit/#!/faint-rhinestone-confidence?path=README.md%3A1%3A0)

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [x] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
<img src ="http://g.recordit.co/C1mwQDERqr.gif" >
![http://g.recordit.co/C1mwQDERqr.gif](your-link-here)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[I only follow the website instruction from the pre-work. https://courses.codepath.org/snippets/summer_internship_for_tech_excellence/prework]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[The hardest problem is the play tone part using JavaScript. I don't have experience in JavaScript so I didn't know how the function works. The for loop, i <= progress, is the one
I got confused in the beginning. Based on what I learn from Python and Java, the loop will only run once because i is 0, and the initial progess is 0. But later on, in the guess 
function, the progess++ will make the global progess incremented. Now I know the JavaScript function is connected to the HTML file. Once we clicked different button, the button 
will call the guess function, and the game can keep playing. I didn't call the playClueSequence() function after increment the progess. By following the instruction on the pre work
I can finish the program.]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[I want to know how front end development can be connected to the back end, and how to make my website public to everybody. This web game is interesting, but I am curious how to make
website like Reddit, which can let users leave their comments or have interaction with the web developer. I think a good website is not only with a good-looking layout but also with 
a user-friendly functionality.]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[If I had more time working on this project, I will probably add some additional features. Like others games, I want to add the level so the play can choose what they want. The easy 
level can be like shortter pattern, and the hard level can be a long pattern with shortter gap time between each tones.]



## License

    Copyright [Zhongxian (Martin) Zeng]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
