# ---/// Intro ///---

Hello ! Thank you for reading this document. There's quite a lot written here and not all of it is of importance, so if you don't feel like reading it all, please read the "About Spoilers" and "How to save a Board" sections. The rest is useful information that you can come back to if need be.


# ---/// Bingo Board ? ///---

This software is a Bingo Board generator for "The Witness". A Bingo Board, at least in the context of gaming, is a 5 by 5 grid of goals. Players can challenge themselves to complete a certain amount of these goals, or can race against another player to see who can complete these goals the fastest. There are a lot of ways to use a bingo board.
This software will generate a random set of 25 objectives for you to complete. Note that it is only a tool to keep track of your goals, and that is doesn't in anyway track these itself
This generator currently contains around 80 goals


# ---/// About Spoilers ///---

The Witness is a game with much to find. As such, some of the goals in this software can spoil part of the game. As such, I've implemented a little survey that you'll have to answer upon booting the software for the first time. The questions are broad and ambiguous, and once the questionnaire is answered, you will not find any major spoilers in the software.

### HOWEVER

I would greatly suggest you do not use this software until you are confident you should. While the questionnaire will shield you from the big mysteries, it will not shield you from small discovering things you didn't want to discover. use it at your own risk. I'd suggest having answered all the questions you still had about the game and it's world through exploration and perseverance before using this software

If you wish to take the survey again for any reason, such as unlocking previously hidden goals or locking ones that might spoil another user, you can click the "Answer Survey Again" on the settings screen.


# ---/// The Settings ///---

To generate a board, you will first need to configure it. There are various settings, with the main 3 being the Tags, the Seed and the Length.

The tags are a set of... well tags that the goals can have. They describe certain types of goals. For each tag, you can decide to either Accept (White), Exclude (Red) or Include (Green) goals that fit said tag.
	Excluding (Red) a tag will prevent any goals featuring it from appearing
	Including (Green) a tag will make sure that any goal featuring it (that isn't already excluded) can appear
	Accepting (White) a tag means that the goals featuring it can, but will not necessarily appear.
If you need any information on a tag, simple hover over the button and a description will appear in the box on the right of the screen

The Seed is a number that controls how a board is generate. Set it within the indicated bounds to use is as a generation seed. If you leave the field blank, a random seed will be used instead. Note that the seed isn't the soul responsible from the board's look, the settings and length will impact the content of the board, even with the same seed

The Length will decide of the general time it might take to complete the board. Each goal is assigned a length depending on how long it might take to complete, and only goals featuring the selected length will be able to appear in the board. If you do not wish to exclude goals because of their length, tick the "All" button.
The Length also decides of the amounts chosen for goals that require them. Goals such as "Solve X amount of puzzles" or "Listen to X Audio Logs" will be given an amount that depends on the chosen length. This is not affected by the "All" button, so do chose a length that fits.

Upon attempted generation of your board, you might be given a message stipulating that your settings don't allow for 25 goals to be drawn. In such a case, you will have to fiddle with your settings to include more goals than you currently have.


# ---/// How to save a Board ///---

This software WILL NOT save your progression on a given board. Neither will is save the configuration of your current board.
To "save" your progress on any given board, simply take a screenshot of the board screen. On top of capturing the state of your board, it'll also save the settings that are written in the bottom right corner of the screen. To pick back up from where you left it, you will need to enter the exact same settings (Tag, Seed and Length), and recreate the board's state from this screenshot.

I understand that this is a complicated process, but this is a simple software I mostly did for fun, and I do not have the motivation to add a saving system. If I ever work more on this project, rest assured that it'll be the main priority.


# ---/// The Board ///---

Once you've selected your settings, click the "Generate Board" button to generate your board
The board screen feature your generated board, a description box and the settings used to generate the board.

To use the board itself, simply click on a goal to turn it from white to green, then from green to red. This doesn't affect the goals themselves, it is purely visual. Use this as a way to keep track of your completed goals, your opponent's goals, whatever you want ! It's up to you to chose how to keep track of what needs tracking. So use these 3 colors however you please

If a goal is too abstract for you, of your need clarification on how to complete it, you can hold the control key while hovering over a goal to prompt its description to appear in the right box

As described in the "How to save a Board" section, the settings box displays the settings used to generate the current board


# ---/// Okay, and then what ? ///---

For now, this is as far as I'm going with this software. It works, that works for me. If I ever come back to it though, I'll probably add certain features that would make usage of this software more practical, such as saving boards, better UI and even multiplayer integration ??? maybe ???
BUT, what I will add over time are goals. They're not too hard to add, I just need to find some more. As such, if you have any ideas for goals I could add, simple send them over to me on either Reddit (u/DarkFluo) or on Discord (darkfluo). Please send a message that features your goals and suggestions, and not a simple "Hello !", send the stuff right away. I'll try to often update this software on whatever place I put it on to share it


# ---/// Credits ///---

Most of the goals in this software aren't by me. There's from a Reddit post I made asking people for their own goals. The credits for each goal is accessible within the software through the "Credit" button in the settings screen. Goals that aren't featured are either by me or users that preferred not being credited. 


Thank you to all that gave suggestions
And thank you for using this software ! Feel free to use it however you want, though feel free to give me credit too if anyone asks :)

Thank you for reading, and I hope you have a good day
