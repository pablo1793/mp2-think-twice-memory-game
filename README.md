# Think-Twice

## Card Pairing Memory Game

[View deployed site here](https://pablo1793.github.io/mp2-think-twice-memory-game/)

A simple but detailed browser game in which players must find pairs of cards with identical images by flipping them over. The games features include background music and sounds indicating card flips and matches, as well as victory and game over themes reminiscent of old-school video games. There are also a timer and flip counter, to enhance the competitive nature of the game. As the goal is to match all twenty cards with the fewest possible flips and with as much time remaining as the player can manage. The images on the front and back of the cards also execute animations when hovered over or matched.

The primary goal of Think-Twice is to provide the user with an entertaining passtime. Which can be played once or many times; depending on how much the player wishes to improve on their priors efforts.

<img src="assets/images/scr-cap-midgame.min.webp" alt="Mid-game screen capture.">

The business goal of Think-Twice is to provide a non-profit game which users can play briefly or for an extended period of time, depending on their level of interest and competitivity. Its design and implementation does not have any financial incentives.

From a user perspective, the goals vary between casual and more competitive players. As such the aim is to pass a little bit of time playing a fun, musical-themed memory game for the former. And - as mentioned earlier - the objective is to beat the game with the lowest number of flips and highest possible time remaining for the latter.
## UX

#### Ideal user

##### The ideal user for this game is:

* English speaking. Although it's not fundamental to play the game.
* Technologically literate at a beginner level.
* Someone who enjoys memory games.

##### Visitors to this website are searching for:

* A card-matching memory browser game of medium to low difficulty.
* A game that contains the option to improve on previous scores.

##### This project is the best way to help them achieve these things because:

* It can be played casually, but only grants the player 100 seconds to match all 10 pairs of cards. So it necessitates basic strategy and quick-thinking to beat.
* It can be played at a higher level of competitiveness. Since it has a limited timeframe and a counter that keeps a tab of how many times the player has flipped a card, the user can restart the game after each attempt with the aim of completing the game faster and with fewer flips than they scored previously.

##### Client stories:

1. As a new player, I want to be able to play the game without having to read an extensive list of instructions.
2. As a new player, I want to play a simple memory game to distract me during my 15-minute break.
3. As a new player, I want the game to look appealing and function intuitively.
4. As a new player, I want the game to be interactive and engaging.
5. As a returning player, I want to play the game with my child and have her understand the game in a short period of time.
6. As a returning player, I want to play for an extended period and achieve my best possible score.
7. As a returning player, I want to see some changes made to the game.

## Technologies Used

### Languages Used

* HTML5
* CSS3
* JavaScript

### Libraries & Programs Used

1. Hover.css:
    - Hover was used on the treble-clef and instrument images that appear on the front and back of the cards respectively. Hovering over the images with the cursor reduce their size somewhat.
2. Google Fonts:
    - Google Fonts were used to import the "ZCOOL Kuaile" and "Architects Daughter" fonts. Which are used on the game title and timer/flip counter text respectively.
3. Git:
    - Git was used for version control by utilizing the Gitpod terminal to commit to Git and push to Github.
4. GitHub:
    - GitHub is used to store the project's code after being pushed from Git. It also serves as a platform to deploy, clone, and share the project.
5. Gitpod:
    - Gitpod served as the online IDE in which the project was coded.
6. Balsamiq:
    - Balsamiq was used before beginning to code to create wireframes which served as reference for the design of the website. Although these wireframes do not reflect the final site design, they served as a useful foundation to build on.
7. CloudConvert:
    - cloudconvert.com was used to convert all png image files to the webp format, reducing their size and ameliorating page load time.
8. Image Resizer Online:
    - imageresizer.online was used to resize all images to match the sizes of the actual images and their rendered counterparts. This was done in order to save data a load time.
9. Gimp 2.10:
    - I used Gimp to crop any screen captures in which I needed to remove irrelevant image content.
10. TinyPNG:
    - TinyPNG.com was used to minify all images to reduce the game's loading time and minimise the user's data usage if not relying on a wifi connection.

## Functionality

### Non-technical

### Technical

### Existing Features

### Features to implement in future

## Installation Instructions

## Testing & Bugfixes

### HTML Testing

Using the W3C Markup Validator:

* First test indicates I did not add alt attributes to the images used and that I duplicated an ID used for the media query hiding a number of card pairs on smaller screen sizes.
* After adding alt attributes to all images and changing the duplicated IDs to classes on all relevant cards in the html file and in the media query in the css file, I run the test again. The result returns *No errors or warnings to show*.

### CSS Testing

Using the W3C CSS Validator:

* First test indicates I forgot to add the unit to the transform property on line 66.
* After correcting the error by adding the correct unit (degrees), I run the test again. The result returns *Congratulations! No Error Found*.

### JavaScript Testing



### web.dev Testing

#### Audit results screencap:

<img src="assets/images/web-dev-audit1.min.webp" alt="Lighthouse audit results screencapture">

#### Audit conclusions:

1. 

### Manual testing of all elements and functionality

## Screenshots

## Credits

### Content

* The inspiration for the design of the game was taken from a two-part video lesson created by YouTube content creators [Web Dev Simplified](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw) and [PortEXE](https://www.youtube.com/channel/UCjGQyJCSU_VVMTu5nigonqg). The [first video](https://www.youtube.com/watch?v=28VfzEiJgy4) focuses on the HTML and CSS needed to create the game, and the [second](https://www.youtube.com/watch?v=3uuQ3g92oPQ) is centered of the JavaScript functionality.

* The fonts used to style the header and subheader texts are [ZCOOL Kwaile](https://fonts.google.com/specimen/ZCOOL+KuaiLe) and [Architects Daughter](https://fonts.google.com/specimen/Architects+Daughter?preview.text=Time%20Flips&preview.text_type=custom#standard-styles) respectively. The latter was designed by [Kimberley Geswein](https://fonts.google.com/?preview.text=Time%20Flips&preview.text_type=custom&query=Kimberly+Geswein), and the former by [ZCOOL](https://fonts.google.com/?query=ZCOOL), [Liu Bingke](https://fonts.google.com/?query=Liu+Bingke), [Yang Kang](https://fonts.google.com/?query=Yang+Kang), and [Wu Shaojie](https://fonts.google.com/?query=Wu+Shaojie).

#### Images

* The **treble-clef** image used for the design on the back of the cards was downloaded from icon-library.com. Although I wasn't able to find the content contributor, here is a [link](https://icon-library.com/icon/musical-notes-icon-5.html) to the page from where it was sourced.
* The **accordion** image was downloaded from pngegg.com. I wasn't able to find its contributor either. Here is a [link](https://www.pngegg.com/en/png-zddaf) to the page where it was sourced.
* The **violin** image was downloaded from pngegg.com. I wasn't able to find its contributor. Here is a [link](https://www.pngegg.com/en/png-exaxv) to the page where the file was sourced.
* The **electric guitar** image was downloaded from clipart-library.com. Contributor not found. Here is a [link](http://clipart-library.com/clip-art/electric-guitar-silhouette-16.htm) to the page where it was sourced.
* The **guitar** image was downloaded from clipart-library.com. Contributor not found. Here is a [link](http://clipart-library.com/clip-art/electric-guitar-silhouette-21.htm) to the page where it was sourced.
* The **snare drum** image was downloaded from cleanpng.com. It was originally contributed by [Ishawar](https://www.cleanpng.com/users/@ishawar.html), and here is a [link](https://www.cleanpng.com/png-snare-drums-drum-stick-a-drum-dog-5575172/) to the page the file was sourced from.
* The **trumpet** image was downloaded from cleanpng.com. It was originally contributed by [Hobno](https://www.cleanpng.com/users/@hobno.html), and here is a [link](https://www.cleanpng.com/png-drawing-vector-graphics-clip-art-portable-network-7014149/) to the page the file was sourced from.
* The **flute** image was downloaded from pnghut.com. It was originally contributed by [Mradoii](https://pnghut.com/user/mradoii), and here is a [link](https://pnghut.com/png/SVBFi5tFvk/musical-instruments-western-concert-flute-silhouette-transparent-png#) to the page the file was sourced from.
* The **saxophone** image was downloaded from iconscout.com. It was originally contributed by [DDara](https://iconscout.com/contributors/ddara), and here is a [link](https://iconscout.com/icon/saxophone-2157836) to the page the file was sourced from.
* The **harp** image was downloaded from pngwing.com. Contributor not found. Here is a [link](https://www.pngwing.com/en/free-png-byhey) to the page where it was sourced.
* The **xylophone** image ws downloaded from vexels.com. I couldn't find its contributor, but here is a [link](https://www.vexels.com/png-svg/preview/223515/xylophone-instrument-black-design) to the page the file was sourced from.

#### Audio

* The **background drum loop** was sourced from looperman.com. This is the [page](https://www.looperman.com/loops/detail/123116/classical-drum-by-krolbeats-free-120bpm-classical-drum-loop) where I downloaded it, and [jensmuse](https://www.looperman.com/loops?mid=Krolbeats) is the artist that originally uploaded it.
* The **flip**, **match**, **victory**, and **game-over** sounds were sourced from [Zack Wilson/PortEXE's](https://github.com/portexe) gitHub page. Specifically from this [repository](https://github.com/portexe/Mix-Or-Match/tree/tutorial-code).

### Acknowledgements

#### Disclaimer

The content of this Website is for educational and entertainment purposes only.