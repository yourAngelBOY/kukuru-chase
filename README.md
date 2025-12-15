# kukuru chase

tiny arcade-ish roguelike game contained in one html file. it's like pac-man crossed with binding of isaac and played entirely offline with zero internet connection required!

## what's the deal?

an endless running through maze game with a small round character trying to collect all the pellets in order to get to the next floor while avoiding the ghosts that want to eat him.

kukuru provides you with multiple power-ups every time you finish a level. which do you want to use? a nuclear bomb, a super speedy directional dash, or an increase in life?

it's created using no external libraries or frameworks at all! there are no react or vite to use and the graphics are all done through plain javascript code and simple maths. all sound effects/music are created live through your web browser while playing!

## how do i play?

Just run around tasting pellets as quickly as possible before the ghosts can kill you. See how far you can survive.

### game controls

*   **w, a, s, d** or **arrow keys** = movement direction
*   **space bar** = dash (uses a cooldown timer so plan ahead!)
*   **e** = use any active ability you may have collected.
*   **mouse** = click on any upgrades you’ve completed.

if you are using a mobile phone, there will automatically be an on-screen control layout.

## some game features

*   **the game is infinite:** each time you play, the maps get randomly created as you go, making them unique every single time you play.
*   **sharing the love:** if you find a fun run, you can copy the unique seed associated with it and share it with your friends so they can experience it too.
*   **collecting cards:** there are 40+ collectible upgrade cards for you to collect. the combine passives allow you to mess with the physics of the game, as well as giving you some great active abilities like "time freezing" and "black hole."
*   **score to access more themes:** the higher you score, the more color themes will unlock, like game boy, matrix & neon.
*   **all tech, no tricks:** the game is built on 100% vanilla javascript and does not require any libraries, meaning the entire game is contained in one `index.html` file.

## how to play the game

1. download the `index.html` file from releases.
2.  double click on it to open it in your web browser.
3.  that's it!

## develop the game

if you're feeling adventurous, then go ahead and play around with the code. since everything is contained in one file, open the file in your text editor and edit the values as you see fit. for example, if you want to become invincible, find the `health` variable and change it to 999. have fun!
