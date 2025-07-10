# Bubble trouble #

After implementing our flying_balls application, we had a look at the game "Bubble Trouble", where a player fires on bouncing balls (resp. bubbles). You can find an online version of this game [here](https://poki.com/en/g/bubble-trouble).

Mitch Koko has published a lot of videos where he is implementing simple versions of several games, e.g. Tetris, Flappy Bird or Mine Sweeper, and also for Bubble Trouble.
See a list of all his videos [here](https://www.youtube.com/playlist?list=PLlvRDpXh1Se6kipeBLiF1xByAEmxYie6J) and the video on Bubble Trouble [here](https://www.youtube.com/watch?v=ZBLOxhiym7k).

Mitch said, that the code developed in these videos can be found on his home page, but unfortunately we did not find it. What we found was e.g. a page, where you can download his code for Tetris, but you have to pay for it, even it's only 5$, see [here](https://mitchkoko.gumroad.com/l/TetrisGameFlutter).

But on GitHub we found several repositories where Bubble Trouble was implemented in Flutter according to Mitch's video, e.g. from [Irina Vasilescu](https://github.com/irinavasilescu/bubble_trouble) and a French developer called [navalnorth](https://github.com/navalnorth/bubbleTrouble_flutter).

We have forked navalnorth's repository into our fdg2425 GitHub account under [bubbleTrouble_flutter_navalnorth_forked](https://github.com/fdg2425/bubbleTrouble_flutter_navalnorth_forked) and in branch gs_ideas, we have implemented several enhancements, e.g.

- put more responsibility into the classes Player, Missile and Ball and thus simplify homepage.dart
- position the elements in the playground on a pixel base by using widget Positioned and not using the alignment property in a Container
- provide an auto-repeater for the buttons to move the player
- as an alternative to buttons, allow to move the player by panning gestures
- to make the game more varied, let the balls have differents sizes and speed, and let big balls split into 2 balls when hit by the missile
- offer a settings page where the user can e.g. select between 2 different layouts (the one from Mitch in pink & grey and the one from Irina in blue & green)
-  use a "pixeloid" font for the game title (copied from Irina)
- add some simple animation when the game starts
  
We have created 3 WebApps to demonstrate what was implemented 
- by Irina, see https://fdg2425.github.io/webtest/bubble/irina_branch_fdg2425
- by navalnorth, see https://fdg2425.github.io/webtest/bubble/navalnorth_branch_end_of_mitch_video/
- in our branch gs_ideas, see https://fdg2425.github.io/webtest/bubble/navalnorth_branch_gs_ideas/



