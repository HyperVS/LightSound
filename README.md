# Pre-work - *Memory Game*

**LightSound** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Omar Abdelrahman**

Time spent: **2** hours spent in total

Link to project: https://glitch.com/~pool-longhaired-acoustic

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
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [X] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [X] The clue hold time for each clue is reduced to 500ms to allow for a smoother and faster user experience.

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](https://cdn.glitch.com/851d1349-ff15-472c-b785-776ff898a370%2FLightSound.gif?v=1616564529123)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
I actually did not use any outside resources.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
When the computer plays a sound, the button stayed lit up. After some debugging, turns out I wrote 'classlist' instead of 'classList', so that was an easy fix. Other than that, I didn't struggle at all with any parts of this challenge.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
I don't have any questions. I'm excited to learn more.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
I would probably implement additional features such as giving the user a limited amount of time to enter their guess, and possible using chords for the sounds.



## License

    Copyright Omar Abdelrahman

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.