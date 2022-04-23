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

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](https://i.imgur.com/PxBt4Bs.gif)

![](https://i.imgur.com/lvgnezv.gif)

![](https://i.imgur.com/0Yiz3xZ.gif)

![](https://i.imgur.com/wNry8rA.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

I used Stackoverflow, w3 school and googled images for some guidance on completing the optional features

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)
 
After following all the instructions I found myself not moving forward from the 3rd click and getting the “you lost” alert, I started console logging and double-checking the code with the instructions and starter code moving functions around checking the CSS file, going back to the HTML file, and finally the script.js until I figured out the context. resume() was the issue. After I removed the resume line it all started to come together as planned. Also, after writing my guess() function ended up referencing the code path code as I found myself comparing and noticing mine might have gotten a little sloppy after implementing it.

Another challenge was time, to complete the optional instructions I needed to allocate more time which unfortunately I did not have. The email invite was sent to me around 24 hours before the deadline and splitting the time from my 9 to 5 work and the code path prework. It brought me the greatest challenge. The “speed it up” timer, the ticking timer, and giving the player 3 strikes were not completed. I managed to add 2 more buttons, a random sequence using Math. random and searched for 6 different images to spruce it up a little. Adding the gif video took me a while and the video recording pushed me out of my comfort zone, knowing that I might be judged based on what I said in the recording made me overthink it.


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

I’m eager to learn more about JavaScript, CSS, HTML, and other data structures like databases, Python, React, DOM manipulation, object-oriented programming, and creating flow charts to better understand the code. Adding the sound was a new thing for me. My question would be more about how can I increase my knowledge base and get better at coding? How can I figure out what path to take? for instance, researching other free coding webinar I find myself seeing more than one way to complete a task, like the Axios and fetch approach, how can I better manage a flow chart, and knowing best practices, the speed of runtime with O notation, which programming language should I focus more on? 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

I completed 3 out of 6 optional instructions. I would start there and move on to aesthetics, making the page contrast more with the colors, adding templates, playing with the grid perhaps comparing the size of the box with the images, mostly CSS stuff. 
Add a box for the name, add scores and keep track of the highest score. This project reminded me of other code game I wrote, it was about a memory game. Where boxes were added to the grid vertically and horizontally with 2 pairs of gifs at random locations inside the boxes and you had to uncover the matching gif. Another feature would be the sound, I wonder if I have had more time to research more sounds what would that be like?




## Interview Recording URL Link

[My 5-minute Interview Recording]https://www.loom.com/share/4c610acdea4047e7bacd934b9fc95ca0


## License

    Copyright Eduardo King

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
