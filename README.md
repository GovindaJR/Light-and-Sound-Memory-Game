# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Govinda Ramrattan

Time spent: 3 hours spent in total

Link to project: (https://glitch.com/edit/#!/test-for-internship?path=README.md%3A11%3A25)

## Required Functionality

The following **required** functionality is complete:

* [X] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [X] "Start" button toggles between "Start" and "Stop" when clicked. 
* [X] Game buttons each light up and play a sound when clicked. 
* [X] Computer plays back sequence of clues including sound and visual cue for each button
* [X] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [X] User wins the game after guessing a complete pattern
* [X] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [X] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [X] Buttons use a pitch (frequency) other than the ones in the tutorial
* [X] More than 4 functional game buttons
* [X] Playback speeds up on each turn
* [X] Computer picks a different pattern each time the game is played
* [X] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
http://g.recordit.co/obJqFeEAIv.gif


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
https://developer.mozilla.org/en-US/docs/web/javascript/reference/global_objects/math/random
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array
https://www.rapidtables.com/web/css/css-color.html


2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
A majority of the difficulties I faced in the submission came from iimplementing the optional features for the project. 

This project was the first time I have used CSS, HTML, and JavaScript all on one project. I've had experience using HTML and CSS in my own time but I've never used them in conjunction together with JavaScript. In fact, this was my first experience with JavaScript. By reading the instructions and explanations for certain lines of code and for certain functions on the Pre-work steps, I was able to gain an understanding about the interactions between HTML and CSS with JavaScript. For instance, learning that you could call  JavaScript functions from HTML, such as from clicking a button. While these came as challenges in understanding the code, actually coding these parts were not as difficult. 
In terms actually completing the project, my main difficulty came with implementing the optional features. Specifically, my issues arose as I started the second optional feature, "Speed it up". Figuring out where exactly to modify the playClueSequence function to update clueHoldTime and how to actually update it were not clear at first. However, with some thinking and trial and error, I was able to figure it out. I realized when it came to updating, that rather than slowing it down by a flat number, I would lower the time in between sequences by a certain percentage, while setting a floor for the time, so the sequences would not play impossibly fast. I also had to reset clueHoldTime every time whenever the game would start again. 
Creating a function to randomize the pattern served some issues. I was unfamiliar with how to randomize an array in JavaScript. I had to consult the JavaScript documentation to find functions that would help in both learning how to randomize given a max and min number, and how to use those functions with an array. Eventually, looking at the example code snippets in the documentation I was able to figure out a way to implement the feature, 

Overall, I would say that the challenges served as a great learning experience to make me a better programmer. 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

Web Development seems to be quite a large field, with an extensive amount of frameworks and technologies/tools that contribute to the field. Those are some things that I would just like to learn more about that. What frameworks/technologies are used most in industry? What are the proper steps that go into the web development cycle? What are API's and how are they related to web development?  I am also interested in the field job-wise. What does web development look like in a professional setting? Is the job market mostly in demand for back-end, front-end or full-stack developers, or is it mostly even?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had more time to work on the project, I would first try to complete the two optional features that I was not able to complete. Those were, adding new images and sounds the the program, and adding a ticking clock for the player during their guesses. The features appear difficult enough to be quite challenging for me, while at the same time seem pretty exciting to implement. The features feel like they would greatly enhance the user experience while allowing me to grow from the struggle. Additionally, I would look for more ways to enhance the HTML of the program. 




## License

    Copyright Govinda Ramrattan

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.