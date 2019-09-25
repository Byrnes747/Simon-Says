# Simon-Says
##### By Ryan Byrnes

## Description
There are two games called Simon-Says. There is the game where someone is Simon and everyone else must do the actions they preface with the phrase, "Simon says." There is also the memory game where buttons light up in a sequence and you must press them in the same order until the sequence gets too long for you to replicate it. This project is an attempt to combine those games into one. 

The display that the player would see would contain a few things. Firstly, at the top there would be a number indicating the current round the player is on, which represents their score. Below the score the player will receive the instructions for the round, after the instructions are given there will be a timer here that denotes how long a player has to complete the round. Toward the lower half of the display there will be four buttons, each with a different color. 

The instructions the player will be given for the round Will either have *Simon Says* in them or they will not. An example of what a round could look like follows: 
*Simon says* **click** blue\n
**swipe** green\n
*Simon says* **swipe** yellow\n
*Steve* says **not** red\n
**swipe** green *Simon Says*\n

As you can see, some instructions will contain *Simon says* while others will not. Decoys will be throw in as well, in the case of the fourth instruction in the example, requiring players to pay more attention. The fifth example instruction also shows that the ordering for the instruction phrases might differ, which will again require the player to pay more attention. Other curve balls will be thrown in as well, such as the text for the colors not being the same as the color they are.

The instructions will contain **commands** which are denoted by the bold face in the example. The commands instruct the player on what to do. Click means the player has to click on the button. Swipe means the player must swipe the button with their finger if they are using a touch screen or to click and drag the mouse in on a webpage. The not command instruct the player to not interact with a color, meaning *Simon says* **not** red translates to clicking or swiping a color other than red. An interesting case is the instruction, **not** red, in which case since Simon didn't say, the player should click red.
