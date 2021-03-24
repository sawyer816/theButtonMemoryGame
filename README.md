# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **NAME**

Time spent: **#** hours spent in total

Link to project: (insert your link here, should start with https://glitch.com...)

## Required Functionality

The following **required** functionality is complete:

* [ ] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [ ] "Start" button toggles between "Start" and "Stop" when clicked. 
* [ ] Game buttons each light up and play a sound when clicked. 
* [ ] Computer plays back sequence of clues including sound and visual cue for each button
* [ ] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [ ] User wins the game after guessing a complete pattern
* [ ] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- Changed the Shape of Buttons
- Sped up the game, making it more difficult as you advance in the game. 

## Video Walkthrough

Here's a walkthrough of implemented user stories:
Here is the link to the gif.


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

None.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

One challenge I ran into during this project was managing the speed of the buttons. I had to figure out the perfect speed that would enable
the buttons to still show up as they got faster, but challenging enough that it would actually become difficult by the end of the program. 
I first used subtraction, but realized that it would eventually reduce the clueHoldTime to nothing, and so I realized that
division was the best way to speed up the program. Through running my program and changing the division amount of the time, I was able to 
finally find the right speed changes that create a difficult but possible game. 

3. What questions about web development do ykou have after completing your submission? (recommended 100 - 300 words) 

Are there any other languages that are used with web development?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

I would add new features such as levels and difficulty. 
There would be buttons next to the start button that ask for difficulty, and each button is faster.
I would also add different themes, that change the music and change the color of the button depending on what theme you choose. 


## License

    Copyright [YOUR NAME]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.