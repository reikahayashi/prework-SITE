# Pre-work - _Memory Game_

**Light and Sound Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: **Reika Hayashi**

Time spent: **3** hours spent in total

## Required Functionality

The following **required** functionality is complete:

- [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
- [x] "Start" button toggles between "Start" and "Stop" when clicked.
- [x] Game buttons each light up and play a sound when clicked.
- [x] Computer plays back sequence of clues including sound and visual cue for each button
- [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess.
- [x] User wins the game after guessing a complete pattern
- [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

- [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
- [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
- [x] More than 4 functional game buttons
- [ ] Playback speeds up on each turn
- [ ] Computer picks a different pattern each time the game is played
- [ ] Player only loses after 3 mistakes (instead of on the first mistake)
- [ ] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](https://i.imgur.com/1sxT4ZF.gif)
![](https://i.imgur.com/3dRXWhm.gif)
![](https://i.imgur.com/jo24h4x.gif)

<img src='http://i.imgur.com/link/to/your/gif/file.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.

https://www.w3schools.com/cssref/css_colors.asp (to add cool colors)

2) What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)

I had to redo the project twice as the sounds in the JavaScript file would not properly play; it was quite frustrating because I could not figure out
why this was for several hours. I carefully followed the instructions on two occasions and made sure that every line of code was executed properly and
yet it still would not be played. When I looked into the console, it stated that it could not identify the AudioContext library. Then I switched my
browser from Safari to Google Chrome and found that it instantly fixed my problem. Perhaps my Safari preferences/settings were configured to prevent
the library from working. It's silly sometimes how a small change (switching Internet browsers) could make a huge difference. I also added extra buttons
aside from the four main buttons and then I had difficulty playing the sounds again; I am not sure why this was. Aside from these small issues,
I did not encounter major challenges and writing and executing the code was conducted quite smoothly.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)

What are the expectations for an entry-level front-end software engineer?
Are they constantly learning about the latest technologies and gaining new skills that pertain to front-end development?
How do you know whether or not you are "proficient" in these languages and acquire these skill sets?
How do you present yourself as the ideal candidate for a web development job/internship and best demonstrate your qualifications?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)

If I had a few more hours working on this particular project, I would definitely add more functions to further enhance the game.
For instance, I could add a function to speed up or slow down the pace of the patterns being played as well as a function to play
multiple buttons to be played at the same time (forcing the users to memorize more than one at a given time). Perhaps I could also
work on reorganizing the orientation of the buttons so that they are played from different locations and again, making the players
memorize more than before.

## License

    Copyright [Michelel Cheng]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
