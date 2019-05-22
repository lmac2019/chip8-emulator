# **Product Document** - CMPT 276 Team 3
_<font size = "3">
   Members: Nichol Yip, Jeremy Lee, Mac Liu, Eric Wong, Tanvir Khan
</font>_

### __Meeting Schedule__
<br>    Team members are expected to show up to weekly meetings scheduled on Mondays at 10:30 AM for an hour, before class and 12:30 - 1:30 after class on Monday, Wednesday, and Friday. Also our group will have an online meeting on Saturday night at 8:30PM - 9:30PM using Discord and Teletype atom.

### __Communication Tool/Techniques__

<br>    Communication tools utilized outside of school would consist of Facebook Messenger, Discord and Teletype atom. Most of the planning documents and presentation materials(PowerPoint) will be completed in the form of Google Docs and Google Slides for ease of access.

### __Details of Software Methodology (UPDATED)__
<br>    Members were originally expected to follow an incremental development model while working on the project, where the project will be divided into larger releases. Early releases would consist of the core properties of Chip-8, with later releases containing various add-ons(the games, the application). Gradually, this developed into a form of an agile development method. Smaller, iterative sub-releases would be pushed to Google Drive, identified by a number and change description. We followed an Extreme Programming process, in which we had multiple short development cycles, updated small release. We adopted pair programming in our meetings, where we would face to face to break into teams of two to work on tasks together. We had also had collective ownership, in which if someone saw something that needed to be improved, they had the agency to do so.

### __Testing and Quality Assurance Tools__

<br>    Tools we will use for testing and assuring the quality would consist of JavaScript Sandbox, a manual code in a separate JavaScript file(Build up with each release). As well as the chrome inspect function to test for any small bugs.

### __Main Implementation Language/ Software Repository__

<br>   Main implementation language would be JavaScript and code will be stored using Google Drive during coding stages while the Final update of the code will be stored in GitHub.

### __Detailed Use Cases For Next Release ( UPDATED )__

<br> N/A

### __Work Breakdown (UPDATED)__

| Name   | Release 1 Tasks (Final)|
| ------ | --------------- |
| Nichol | Updates to Product Document |
| Jeremy | Automated Testing/Opcode |
| Mac    | Automated Testing/Rom loader/Opcode/Output pixels |
| Eric   | Opcode |
| Tanvir | N/A |
| all    | Debug  |

| Name   | Release 2 Tasks(Final) |
| ------ | --------------- |
| Nichol |  Updates to Product Document / Visualizer / Keyboard|
| Jeremy |  Front-end interface / Sound & Delay Timer |
| Mac    | Animation /Keyboard /Sound & Delay Timer|
| Eric   | Visualizer |
| Tanvir | N/A |
| all    | Debug|

| Name   | Release 3 Tasks(Final) |
| ------ | --------------- |
| Nichol | Updates to Product document  / Game 1 JavaScript Prototype|
| Jeremy | Chip 8 Tool / Game 1 (random generation) |
| Mac    | Chip 8 Tool / Game 1 (random generation) / Game 1(animation)|
| Eric   | Game 1(starting screen & ending screen & score)  |
| Tanvir | N/A |
| all    | Debug|

| Name   | Release 4 Tasks(Final)|
| ------ | --------------- |
| Nichol | Game 2 Design  / Game 2 Sprites / Release 4 PowerPoint presentation / Product document|
| Jeremy | Game 2 mechanics / Release 4 script / Product document / Product document|
| Mac    | Game 2 Design / Game 2 mechanics  / Release 4 script/ Product document|
| Eric   | Game 2 Design / Game 2 mechanics / Release 4 script / Product document / Game 2 Starting Screen & ending screen & score|
| Tanvir | N/A |
| all    | Debug|

**NOTE:** All group members are expected to work on the debugging process of the code together.

### __Completed Tasks ( UPDATED )__
<br> - CHIP 8 Core
<br> - CHIP 8 Functions
<br> - Canvas Display
<br> - Rom loader(UPDATED)
<br> - Automated Testing
<br> - Visualizer
<br> - Keyboard
<br> - Animation
<br> - Game 1 Worm
<br> - Chip-8 Tool Sprite Editor
<br> - Game 2 Unicorn (NEW)

### __Future Schedules__

| Date  | Tasks Expected to Finish  |
| ----  | ------------------------  |
| Jan 13 - Jan 14 | Chip 8 Constructor and Initializer |
| Jan 14 - Jan 21 | Opcode |
| Jan 14 - 17 | Product Document |
| **Jan 18** | **Product Document Due** |
| Jan 18 - Jan 21 | Powerpoint |
| **Jan 21** | **Powerpoint Due** |
| Jan 21 | presentation rehearsal|
| Jan 25 | Release 0 Presentation |
| Jan 22 - Jan 28 | Automated testing |
| Jan 22 - Jan 28 | Display |
| Jan 22 - Jan 28 | Visualizer |
| Jan 29 - Jan 30 | Link Work Together |
| Jan 31 - Feb 6 | Debugging |
| Jan 31 - Feb 6 | Product Document Update |
| **Feb 6** | **Release 1 Due** |
| Feb 7 - Feb 13 | Hex Keyboard |
| Feb 7 - Feb 13 | Timers |
| Feb 7 - Feb 13 | Sound |
| Feb 7 - Feb 13 | Finish Application |
| Feb 7 - Feb 13 | Game 1 Design Concept |
| Feb 7 - Feb 13 | Running Display |
| Feb 7 - Feb 13 | Finish Visualizer |
| Feb 14 - Feb 19 | Part of The Game Done ( Animation/Title Screen ) |
| Feb 20 - Feb 21 | Link work together |
| Feb 22 - Feb 25 | Debugging |
| Feb 26 - Feb 27 | Update Product Document |
| **Feb 27** | **Release 2 Due** |
| Feb 28 - Mar 7 | Finish Game 1 |
| Feb 28 - Mar 7 | Start Game 2 With Application |
| Feb 28 - Mar 7 | Finish Chip 8 Tool |
| Mar 8 - Mar 9 | Link Work together |
| Mar 10 - Mar 12 | Debugging |
| Mar 10 - Mar 12  | Update Product Document |
| **Mar 13** | **Release 3 Due** |
| Mar 14 - Mar 23 | Finish Game 2 |
| Mar 14 - Mar 25 | Release 4 Presentation Slides Finished |
| Mar 26 | Rehearsal |
| Mar 27 - Mar 28 | Product Document Update |
| Mar 29 - Apr 5  | Debugging |
| Apr 1 | Release 4 Presentation |
| Apr 5 | Finish All Code and Debugging Stages |
| **Apr 8** | **Release 4 Due** |

### __Release 1 Discussions__
<ul style = "font-size : 17.5px;">
  <li> Visualizer completion pushed to release 2 - visualizer is just a log of the first 1000 operations of the program loaded into memory</li>
  <li> Screen completion (animations) for the programs and games done by release 2 - using window.requestAnimationFrame object - need more in depth research</li>
  <li> Currently with the load function, it is possible to load anything. We want to make it only possible to run the rom files in a specified folder so it wont give any errors
  <li> One of the problems that was encountered was that one of our team members did not do any of the work associated with release one. Because of this, some progress was pushed back to later releases, making the development process frustrating to work on with the remaining team members. On top of that, it was very difficult to contact him, as he does not read any forms of communication that we have been using as a group. Attendance to meetings has been sparse (he have not come to the past 6 meetings). As a temporary solution, the group has decided to split up the code amongst the four remaining members. </li>
</ul>

### __Release 2 Discussions__
<ul style = "font-size : 17.5px;">
  <li> Chip 8 tool has been moved to release 3 </li>
  <li> We encountered a problem to test two of our opcodes which is FX0A and CXNN. This is because, those opcodes were only able to be tested while the program is running. Thus, we have decided to not include it in our automatic testing.
  <li>
  As an ongoing problem, our team member continues to refuse to communicate with us. One of our team members sent him a private message, letting him know that the TA has been notified and that he should really start putting in his share. However, he has ignored that private message, even when he has seen the group chat. This has become increasingly frustrating for us, as none of the work done in this and the previous release has come from him. He has not attended any meetings at all for release 2, and when we have asked him to come in the group chat, he has seen the messages, but not responded to it. The duties of coding this project has been continued to be split amongst the four remaining members. The rest of the team members find this incredibly unfair, and by the next release we will have contacted both the TA and Teacher.</li>
</ul>

### __Release 3 Discussions__

<ul style = "font-size : 17.5px;">
  <li>We encountered a problem making the sprite editor. We were planning to use a one dimensional array to have an efficient runtime, but we soon encountered problems of converting the coordinates to unique array entries in the index. We realized that the runtime is going to be similar to using a two dimensional array, instead using the x and y positions to create a unique ID for each location.</li>
  <li>Game 2 design moved to release 4</li>
  <li>Changed game 1 from Snake(OLD) to Worm(NEW)(Original)</li>
  <li>We encountered problems while trying to make Snake as our game 1, especially with the chip8 register and memory length. The problem with Snake for chip8 is that the game slows down after a few points due to the chip8 memory space and register getting filled up as the snake gets longer(Queue). We decided to scrap the idea of Snake, using some of the concepts and animation to make our own original game, Worm. We used the animation for the fixed length of 2 pixels as the worm body animation and we used the generating food function to generate food for the worm. We then added obstacles for the worm(randomly generated rocks created by Sprite Editor). However, we soon found the randomly generated rocks to be a problem because the rocks can spawn on food and on the worm. If it spawns on the worm, it causes instant death to the player. If it spawns on the food, then it would cover the food, making the game unplayable. The amount of increasing bugs made the game harder to code through. One of the solutions was to use a grid system to avoid rocks randomly generating in the wrong places(Where the player and food is located). However, this solution proved vastly complicated for us, and the game was boring to play, as there were too few rocks spaced far apart. It was also very difficult to distinguish where the food went if it was beside a rock. So as a solution for all of the above, we had decided to use an "invincible frame" for the worm and have the food blink rapidly to indicate its position. When the rock is spawned on top of the worm, the worm doesn't die immediately, and the player has few seconds to respond. This meant that we could spawn more rocks without the consequence of instant death. Because of increasing the amount of rocks randomly spawned, there was an issue in which a path to the food could not be found. The solution was to create a  reset terrain button(R) for the player, at the cost of subtracting one from the score so the player wont spam the reset for easy points.</li>
  <li>
  As an ongoing problem, one of our teammates refuses to work with us. We have been communicating and inviting him to the meetings, but he still does not attend meetings or online calls. According to him, he has a lower body injury has prevented him from working on the project with us. We feel that this needs to be solved by a TA or through professor intervention. In conclusion, he should not be given the same grade as the rest of the team members.</li>
</ul>

### __Release 4 Discussions (NEW)__
<ul style = "font-size : 17.5px;">
  <li> We've encountered problems where we have trouble optimizing the code for game 2 unicorn. When coding on OCTO, we've realized their Chip-8 emulator is a lot more optimized compared to ours which slows down the overall game play when playing in the emulator we have created. As a solution we've optimized the code by rewriting some functions and removing if...begin...end loops because it requires more instructions than a plain if...then.
  <li>
  As an ongoing problem, one of our teammates refuses to work with us. We have been communicating and inviting him to the meetings, but he still does not attend meetings or online calls. According to him, he has an lower body injury has prevented him from working on the project with us. We feel that this needs to be solved by a TA or through professor intervention. In conclusion, he should not be given the same grade as the rest of the team members.</li>  

<h2>FINAL RELEASE INSTRUCTIONS<h2>

  <h2>Running Code(UPDATED):</h2>
  <ul style = "font-size : 17.5px;">
  <li>For the display and interface, open <strong>load.html</strong></li>
  <ul>
  <li>Features a 640x320 monochrome display, a memory/stack visualizer, an opcode visualizer, and a speed indicator</li>
  <ul>
  <li><strong>Forward/Backward</strong> - traverses forward and backward through the opcode and memory/stack
  </ul>
  <li>Features several buttons with different functions:
  <ul>
  <li><strong>Increase Speed</strong> - increases speed by 0.2</li>
  <li><strong>Decrease Speed</strong> - decreases speed by 0.2</li>
  <li><strong>Pause/Unpause</strong> - pause/unpause toggle for game</li>
  <li><strong>Choose Roms</strong> - opens file reader (Roms are located in Team 3 Release 4/roms)(After select game choose a preferable speed)</li>
  <li><strong>Game One Load</strong> - opens game Worm
  <li><strong>Game Two Load</strong> - opens game Unicorn
  <li><strong>Automatic Testing</strong> - opens an Automatic Testing page in a separate tab</li>
  <li><strong>Sprite Editor</strong> - opens the Chip-8 tool in a separate tab</li>
  </ul>
  <li>Optimal in 100% window size</li>
  </ul>



  <li>Key map:</li>
  <table>
  <tr>
  <th colspan = "4">Keypad</th> <th colspan = "4"> Keyboard </th>
  </tr>

  <tr>
  <td>1</td> <td>2</td> <td>3</td> <td>C</td>
  <td>1</td> <td>2</td> <td>3</td> <td>4</td>
  </tr>

  <tr>
  <td>4</td> <td>5</td> <td>6</td> <td>D</td>
  <td>Q</td> <td>W</td> <td>E</td> <td>R</td>
  </tr>

  <tr>
  <td>7</td> <td>8</td> <td>9</td> <td>E</td>
  <td>A</td> <td>S</td> <td>D</td> <td>F</td>
  </tr>

  <tr>
  <td>A</td> <td>0</td> <td>B</td> <td>F</td>
  <td>Z</td> <td>X</td> <td>C</td> <td>V</td>
  </tr>
  </table>
  </ul>

  <h2>Automated Testing:</h2>
  <ul style = "font-size : 17.5px;">
  <li> In each testing case the opcode number/property and the testing result is displayed in bold font</li>
  <li> Details for each test are directly under the bolded title and are indented</li>
  </ul>

  <h2>Details:</h2>
  <p style = "font-size : 17.5px;"> Each test will give an output at the end of the line, displaying whether the test operation performed was a success. The way the opcodes were tested was through using sample data stored in various variables, using a check Boolean to determine success or failure. The results are then printed with a green check or a red cross mark. For DXYN (The Screen Opcode), we have provided a sample display with one sprite (0) printed on it to show that the display function does work (best viewed with 100% screen size). All missing opcodes have been included to the tests except for FX0A and CXNN. For FX0A it requires a live keyboard input and for CXNN we are still working on how to test a randomizer.</p>

  <h2>Sprite Editor:</h2>
  <ul style = "font-size : 17.5px;">
  <li> Added a 8x16 Sprite Editor for the creation of sprites in Chip-8</li>
  <li> User can left-click on canvas to draw  on the canvas, right-click on canvas to erase</li>
  <li> Buttons on the left hand side consist of:
  <ul>
  <li>Clear - clears the Screen</li>
  <li>Up - shifts all pixels up by 1 increment</li>
  <li>Down - shifts all pixels down by 1 increment</li>
  <li>Left - shifts all pixels left by 1 increment</li>
  <li>Right - shifts all pixels right by 1 increment</li>
  </ul>
  <li> Live Hex output - sprite to hex converter</li>
  </ul>



  <h2>Game 1 - Worm :</h2>
  <ul style = "font-size : 17.5px;">
  <li><strong>A randomly generated terrain explorer game: you play as a tiny worm to find food in a harsh environment.</strong></li>
  <li>click the "GAME 1 LOAD" button to load up Worm</li>
  <li>Created Game 1(original game) : a random generating terrain explorer </li>
  <li>Sprite Editor was used to draw rocks and letters for the ending screen
  <li> The goal of the game is to get a high score by eating as much food(blinking pixel) as possible, while avoiding rocks</li>
  <li>Worm has a special ability to reset the terrain(by pressing R) so it can move freely, but 1 point is deducted from the overall score.</li>
  <li> player is shown as a 2x1 pixel object</li>
  <li>Controls: WASD to move in four directions, R to reset(this deducts 1 point) terrain, 1 to restart the game from the game over screen</li>
  <li> The worm cannot go directly backwards</li>
  </ul>

  <h2>Game 2 - Unicorn(NEW) :</h2>
  <ul style = "font-size : 17.5px;">
  <li><strong>Unicorn is a simple infinite runner game where you have to dodge incoming objects</strong></li>
  <li>click the "GAME 2 LOAD" button to load up Unicorn -automatically changes speed to 32 (default playing speed)</li>
  <li>Created Game 2(inspired by the Google dinosaur game and flappy bird) </li>
  <li>Sprite Editor used to draw cactus, pipes, and the starting/ending screen sprites for our game
  <li>The goal of the game is to get a high score by dodging obstacles</li>
  <li>The Unicorn has to dodge every object while moving forward to reach the second level(flying)</li>
  <li>When the unicorn scores enough points by dodging obstacles(20 points), it will reach the flying phase, where the unicorn will be flying and the game will be more challenging by introducing pipes and obstacles from various places</li>
  <li>Controls: First Phase: W to jump. Second phase(Fly): press W continuously to fly and hover </li>

  </ul>


### __Post Project Mortem (NEW)__
<ul style = "font-size : 17.5px;">
**What worked well in this project, and what didn’t?**
<ul style = "font-size : 17.5px;">
GitHub didn't really work/was not really convenient for us from our extreme programming method, so we used Google Drive as a temporary backup and save point for our incremental small releases. Furthermore, we were initially using JavaScript sandbox to test our code but switched over to programming modules into our main code body, and using the <code>console.log</code> command to test for bugs, output and variable results in the Chrome inspect function. Initially our plan for JavaScript sandbox was to test modules, but we found that this method affected logical cohesiveness. To fix that, we decided to code our modules directly into the code body, so that it would easier to comprehend the effect of that part on the rest of our project.

<ul style = "font-size : 17.5px;">
**What would you have done differently knowing what you know now?**
<ul style = "font-size : 17.5px;">
If we were to do this again, we would focus more on fully understanding the properties of Chip-8 so that we won’t be confused when developing the core.

<ul style = "font-size : 17.5px;">
**What was the biggest unexpected challenge?**
<ul style = "font-size : 17.5px;">
The biggest unexpected challenge would have to be that one of our teammates had medical issues, and as a result of that, they missed out on the development and planning of the whole project. We attempted to communicate with him over various platforms, but it was clear that he would not respond. A solution was to shift parts of our initial schedule, and because we planned for a high BUS factor, we did not have to restructure the complete timeline.

<ul style = "font-size : 17.5px;">
**Was all the testing worth it?**
<ul style = "font-size : 17.5px;">
Yes, because of all the tests we have done, we were able to avoid any potential bugs before submitting the project for each release.

<ul style = "font-size : 17.5px;">
**What advice would you give to the next students who take 276?**
<ul style = "font-size : 17.5px;">

An advice that we would give to future students working on a project like this would be to plan all details and cases out ahead of time even if you don’t think it is necessary, it would help out later when problems arise. One example would be to plan out and subdivide your work into smaller and manageable parts in the beginning, so that when you are merging with the rest of your team’s code, the process would be smooth. Another advice would be to communicate with your team more often. Be sure to tell them if you are going to be sick, won’t be able to attend a meeting, or did not complete your assigned part so everyone can plan accordingly.


### __References__ (UPDATED)

http://devernay.free.fr/hacks/chip8/C8TECH10.HTM

https://en.wikipedia.org/wiki/CHIP-8

http://blog.alexanderdickson.com/javascript-chip-8-emulator

https://github.com/reu/chip8.js/

https://github.com/JohnEarnest/Octo/

https://elgoog.im/t-rex/

https://stackoverflow.com/questions/41904975/refresh-page-and-run-function-after-javascript(NEW)
