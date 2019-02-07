# 100 Days Of Code - Log

## Day 41: 3 January, 2019

**Today's Progress:** More testing, and cleaning up the code (writing comments)

**Thoughts:** I guess it's a good sign if the computer is beating me the majority of the time? Like, since I wrote the program, is it a case of me being smarter than myself? I wasn't expecting the algorithm to be that good yet. Although since it's a card game, maybe it depends on luck more than anything.


## Day 42: 4 January, 2019

**Today's Progress:** Changed checkHand to a class function (with no parameters except self), and now starting to get rid of repeating code from the player and computerPlayer classes.

**Thoughts:** Currently at 563 lines of code (including comments), aiming to reduce this number. Hopefully the code won't become unreadable now that I'm adding new functions.


## Day 43: 5 January, 2019

**Today's Progress:** Hit a bit of a road block with the "put out card from discard pile" function. For some reason, it says it's putting out one card, but a different card is actually put out.

**Thoughts:** A bit of a bummer not to get that much work done. Going to look at it with fresh eyes tomorrow.


## Day 44: 6 January, 2019

**Today's Progress:** Fixed the bug - it was in the original logic (not something I just changed), where the computer would always put out the card from the first discard pile (if the card came from a discard pile).

**Thoughts:** I suspect that I copied code from the "from hand" part of the function and didn't check it properly. Serves me right for copying code instead of making one function that does both.


## Day 45: 7 January, 2019

**Today's Progress:** Finished putOutCardFromHand function

**Thoughts:** No notable incidents or anything. Seemed almost peaceful - it's weird not getting any errors.


## Day 46: 8 January, 2019

**Today's Progress:** Changed the way pickUpPile works - [random.shuffle](https://stackoverflow.com/questions/976882/shuffling-a-list-of-objects) runs at the start of the game and players then take the top card each time they fill up their hand. Also, created an intermediate function in canStockCardBeReached called createPath, which also takes cases where the pile has to run past 12 to put out the stockCard.

**Thoughts:** I forgot I had that link saved - it's a much simpler solution than picking a random card from the list each time. I'd like to think that only calling a random function once (as opposed to each time someone wants a card) makes the program run faster.


## Day 47: 9 January, 2019

**Today's Progress:** General tidying of code, adding comments to make it more readable, and added a new step to computer endTurn when deciding where to put a card.

**Thoughts:** Not sure what else I could do at this point to improve the code? The new step was to tell the computer to try to put a card on a pile with only 1 other card on it before devolving to 'guess I'll pick a random card to go anywhere' since there could be a pile with lots of the same card that you don't want to block off unnecessarily.


## Day 48: 10 January, 2019

**Today's Progress:** Changed tryDiscardPile to be more efficient, and started the JS SoloLearn course. Was able to skip ahead to the Objects module since I already knew a bit of JS from last year.

**Thoughts:** There's probably a lot more I could do to improve this Skip-Bo program, but I'm not too sure where to go from here. What I probably should have done was planned out how I was going to do it instead of jumping right in (which felt good at the time!) since I'm now left with ~500 lines of code that could probably be organized and structured better, but at this point that's such a daunting task that I don't know how to start, and I don't really know too much about coding best practises to want to attempt that right now. Plus, the next step after that is most likely to move to a GUI, which would either involve me learning pygame, or moving the code to C#, which I'm not quite ready to do yet. I'm happy to leave this text-based version as tentatively finished, and take a break to work on something else for a while.


## Day 49: 11 January, 2019

**Today's Progress:** Did the next two JS SoloLearn modules ('Core Objects' and 'DOM & Events') and finished off the first two chapters of FreeCodeCamp (that I hadn't done from three years ago apparently).

**Thoughts:** Learnt about Bezier curves in CSS, Array methods in JS, the Math Object, and the Document Object Model. An interesting coincidence that the last time I logged in to FreeCodeCamp was exactly three years ago - 11 Feb 2016.


## Day 50: 12 January, 2019

**Today's Progress:** Started learning p5.js from a YouTube tutorial called The Coding Train, and drew a cat whose eyes grow and shrink depending on where the mouse is hovering.

**Thoughts:** It was fun to mess around like this, and it's always worth creating something unique instead of following a tutorial directly. Also, I'm halfway there already!! I feel like I will be able to do this

**Link to work:** [Cat Eyes project](https://codepen.io/rogerthat35/pen/EGGoyL)


## Day 51: 13 January, 2019

**Today's Progress:** Continuing from yesterday, gave the cat a mouth, nose, and stripes.

**Thoughts:** I'm kinda impressed with how good this looks for a slapdash of shapes and only one moving part.

**Link to work:** [Cat Eyes project](https://codepen.io/rogerthat35/pen/EGGoyL)


## Day 52: 14 January, 2019

**Today's Progress:** Made a ball bounce around the screen using p5.js, taking inspiration from a tutorial from The Coding Train on YouTube.

**Thoughts:** It reminds me of the old DVD screensavers. It's pretty nice to look at.

**Link:** [Coding Train tutorial](https://www.youtube.com/watch?v=LO3Awjn_gyU)


## Day 53: 15 January, 2019

**Today's Progress:** Found an interesting website called Advent of Code, which supplies Christmas-themed puzzles one day at a time throughout December. Obviously I'm a bit late (it being mid-January) but all the challenges are still up, for every year since 2015. I completed the two Day 1 puzzles for 2018.

**Thoughts:** The first puzzle was straightforward enough, but the second stalled for so long that I thought it was broken. Nope, it was working, just really slowly. In other words, part of the puzzle was optimizing the algorithm so that it works for large inputs. I ended up looking at the Reddit page for help with making the program more efficient.

**Link:** [Advent of Code Day 1](https://adventofcode.com/2018/day/1)


## Day 54: 16 January, 2019

**Today's Progress:** Did four puzzles today, both of Day 2's and both of Day 3's! And completed the FreeCodeCamp Applied Vidual Design module.

**Thoughts:** I found these puzzles easier than yesterday, probably since none of them needed to be optomized. They were certainly different to anything I've done before, though, and I enjoyed the challenge.

**Links:** 
1. [Advent of Code Day 2](https://adventofcode.com/2018/day/2)
2. [Advent of Code Day 3](https://adventofcode.com/2018/day/3)
3. [FreeCodeCamp Applied Visual Design module](https://learn.freecodecamp.org/responsive-web-design/applied-visual-design)


## Day 55: 17 January, 2019

**Today's Progress:** Finished both Advent of Code Day 4 puzzles, using Python and regex. It runs surprisingly quickly for the amount of data given.

**Thoughts:** Spent a while debugging a silly error I introduced while trying to make the program more efficient prematurely, so didn't get as many done as yesterday. I still felt accomplished after getting this far, though. I'm also very thankful for Python's .sort function, as the puzzle would've been much harder without it!

**Link:** [Advent of Code Day 4](https://adventofcode.com/2018/day/4)


## Day 56: 18 January, 2019

**Today's Progress:** Finished both Day 5 puzzles, then looked on Reddit for how I could have approached the problem differently. 

**Thoughts:** My algorithms both worked, but clearly aren't optimized, as it takes at least 10 minutes to get an answer (for the first one - it has to run x26 for the second). I ended up stopping it for the second puzzle after it reached a number that was clearly lower than any others I'd gotten so far, tried it, and it ended up being correct. Looking at other answers showed that I was calling the function way too many times - each time I found a match and got rid of it, I'd start the entire loop again and start comparing from the beginning! No wonder it took so long. It would have been much better to stay in the same place in the polymer, and compare the letters before and after the pointer, since no combinations could have spontaneously appeared where the reaction had not taken place.

**Links:** 
1. [Advent of Code Day 5](https://adventofcode.com/2018/day/5)
2. [Reddit Solutions}(https://www.reddit.com/r/adventofcode/comments/a3912m/2018_day_5_solutions/)


## Day 57: 19 January, 2019

**Today's Progress:** Got stuck on the Day 6 puzzle (first puzzle). Instead, I completed the FreeCodeCamp Accessibility module.

**Thoughts:** The puzzle concerns something I'm not familiar with and couldn't get my head around in a day ([Taxicab Geometry](https://en.wikipedia.org/wiki/Taxicab_geometry)). Perhaps I'll come back to it some other day, once I've brushed up on high school trig.

**Links:** 
1. [Advent of Code Day 6](https://adventofcode.com/2018/day/6)
2. [FreeCodeCamp Accessibility module](https://learn.freecodecamp.org/responsive-web-design/applied-accessibility)


## Day 58: 20 January, 2019

**Today's Progress:** Did the FreeCodeCamp Responsive Web Design module.

**Thoughts:** Since this module was quite short, I spent the rest of the time looking up terms I didn't understand, and looking for other resources about accessibility on the web.

**Link to work:** [FreeCodeCamp Responsive Web Design module](https://learn.freecodecamp.org/responsive-web-design/responsive-web-design-principles)


## Day 59: 21 January, 2019

**Today's Progress:** Did the last SoloLearn JS module about ECMAScript 6, which means I've completed the course.

**Thoughts:** Was away from my computer for most of the day, so I worked on the SoloLearn app.

**Link to work:** [Certificate](https://www.sololearn.com/Certificate/1024-11756375/pdf/)


## Day 60: 22 January, 2019

**Today's Progress:** Completed the CSS Flexbox and CSS Grid modules.

**Thoughts:** The CSS Grid stuff was revision, but I hadn't learnt Flexbox before. I was expecting it to be much more complicated, but I might actually prefer it to Grid.

**Links to work:** 
1. [FreeCodeCamp CSS Flexbox](https://learn.freecodecamp.org/responsive-web-design/css-flexbox)
2. [FreeCodeCamp CSS Grid](https://learn.freecodecamp.org/responsive-web-design/css-grid)


## Day 61: 23 January, 2019

**Today's Progress:** Completed the first FreeCodeCamp project - a tribute page about a ship cat that survived three of his ships sinking.

**Thoughts:** Whoever looks at my codepen account at this point is going to think I'm a cat fanatic, lol.

**Link to work:** [Tribute page](https://codepen.io/rogerthat35/pen/vbEjLw)


## Day 62: 24 January, 2019

**Today's Progress:** Completed a survey page about breakfast food (must've been hungry when I thought of the topic).

**Thoughts:** I had to look up a few things, but mostly it was done from memory. Hopefully with more practise I'll be able to do it faster and without having to look online.

**Link to work:** [Survey page](https://codepen.io/rogerthat35/pen/ZwGjxb)


## Day 63: 25 January, 2019

**Today's Progress:** Started a landing page, not sure what to make the subject yet. I've started the layout for now, can think of a subject later.

**Thoughts:** There's a glitch in the nav bar where the image and the links (which are in an unordered list) have a gap between them. I've spent most of the day trying to get rid of it, but so far unsuccessful.

**Link to work:** [Landing Page](https://codepen.io/rogerthat35/pen/wNMweo)


## Day 64: 26 January, 2019

**Today's Progress:** Continued working on the landing page, and figured out what the glitch was almost immediately. I hadn't set the padding and margins of the \<ul> element to 0, hence the gap between the img and links, but not between the links themselves. I spent the whole time thinking it was the img's fault.

**Thoughts:** I guess it can be beneficial to step away from a problem for a while/sleep on it lmao.

**Link to work:** [Landing Page](https://codepen.io/rogerthat35/pen/wNMweo)


## Day 65: 27 January, 2019

**Today's Progress:** Completed a landing page, decided to make it about ball-point pens, in honour of the hiring managers that pull a pen out of their pockets and ask you to sell it back to them.

**Thoughts:** Spent a while on the media queries, trying to get the three product divs to look nice no matter what the device size was. Definitely opened my eyes to how different a website can look depending on the browser width.

**Link to work:** [Landing Page](https://codepen.io/rogerthat35/pen/wNMweo)


## Day 66: 28 January, 2019

**Today's Progress:** Completed the functionality for the personal portfolio, still have to do the layout and make it look nice.

**Thoughts:** Dabbled a bit in color palettes as well, but wow is it hard to pick a color. I was staring at a color wheel for a while thinking about which one I should start with. Graphic designers, you have my respect.

**Link to work:** [Personal Portfolio](https://codepen.io/rogerthat35/pen/QYEjjM)


## Day 67: 29 January, 2019

**Today's Progress:** Mostly done with the styling, spent a lot of time wondering why the flex property wouldn't apply to the nav bar and make the links right-aligned. Turns out the flex property was being applied, I just hadn't made the width 100vh which was why it didn't go all the way across the screen.

**Thoughts:** Probably would've completely finished today, but it was getting late and the light was starting to attract a colony of bugs. I looked up and went "well, guess I'm doing this tomorrow" and got out of there as quickly as possible.

**Link to work:** [Personal Portfolio](https://codepen.io/rogerthat35/pen/QYEjjM)


## Day 68: 30 January, 2019

**Today's Progress:** Finished the portfolio page, and played a couple of interesting games intended to help learn CSS Grid and FlexBox.

**Thoughts:** There aren't a lot of projects I have right now that I'm that... proud of? I know I'm still fairly new at this, but I feel the urge to do something more complex. Perhaps I should come back to these early projects later once I know more and spruce them up a bit.

**Links:** 
1. [Personal Portfolio](https://codepen.io/rogerthat35/pen/QYEjjM)
2. [Grid Garden game](http://cssgridgarden.com/)
3. [Flexbox Froggy game](https://flexboxfroggy.com/)


## Day 69: 31 January, 2019

**Today's Progress:** Started a codepen using p5.js of a cat's tail swinging. I didn't get that far - it's just a line swinging at the moment - I had to look up the formula y = x^2 and then play with numbers that would make the line appear on the screen.

**Thoughts:** Didn't realize I'd forgotton so much since high school.

**Link to work:** [Cat tail](https://codepen.io/rogerthat35/pen/LqxLbm)


## Day 70: 1 February, 2019

**Today's Progress:** Got half of the tail tip working - I want it to curl up at the top of the swing, and uncurl while going back down again. Mostly it's a case of trial and error.

**Thoughts:** Hopefully the other half will just be a case of flipping some numbers around. It's quite funny when the numbers aren't quite right and the tip of the tail goes haywire.

**Link to work:** [Cat tail](https://codepen.io/rogerthat35/pen/LqxLbm)


## Day 71: 2 February, 2019

**Today's Progress:** Finished the other half of the swing. It doesn't quite look right, but the tail tip is at least attached now and not in the void.

**Thoughts:** I think I'm going to abandon this project since it probably isn't possible to do quite what I'm intending. I could tweak the numbers so that it doesn't appear to "jump" between states, but even then I don't think I'll be fully happy with it. Tomorrow I'm planning on starting the last freecodecamp project I need to get the certificate.

**Link to work:** [Cat tail](https://codepen.io/rogerthat35/pen/LqxLbm)


## Day 72: 3 February, 2019

**Today's Progress:** Finished the technical documentation page (based on some things I learned about C#) and got the certificate!

**Thoughts:** Very happy and proud of myself. I was putting off this project since I thought it was the hardest one, but after sitting down and working through it, the difficult parts didn't seem as daunting. It's nice to have something tangible that represents my accomplishments.

**Links to work:**
1. [Technical Documentation page](https://codepen.io/rogerthat35/pen/qgmXgv)
2. [Certificate](https://www.freecodecamp.org/certification/rogerthat35/responsive-web-design)


## Day 73: 4 February, 2019

**Today's Progress:** Completed the Basic JavaScript module from the JavaScript Algorithms and Data Structures Certification.

**Thoughts:** Onto the next certificate! This was all familiar, since I learnt a bit of JavaScript last year before starting this challenge. Doing all 107 exercises tired me out, though.

**Link to work:** [FreeCodeCamp Intro to JS](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript)


## Day 74: 5 February, 2019

**Today's Progress:** Started on the ES6 module, learning about the spread operator and destructuring assignment.

**Thoughts:** This is a lot different from anything I've done before in JS, syntax-wise. I'm going to have to look up some other explanations for it to sink in.

**Link to work:** [FreeCodeCamp ES6 module](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/es6)


## Day 75: 6 February, 2019

**Today's Progress:** Finished the rest of the ES6 module on freecodecamp.

**Thoughts:** Starting to feel a bit unmotivated/burnt out. It's getting hard to continue after the first hour of work.

**Link to work:** [FreeCodeCamp ES6 module](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/es6)


## Day 76: 7 February, 2019

**Today's Progress:**

**Thoughts:** Finally got around to learning how GitHub works and forking the 100DaysOfCode repo to write about my journey publically. I wasn't originally going to do this, since I have my own journals I write in every day, but Git is a valuable skill to learn, and I was just putting it off. So if anyone noticed the start date of the 100DaysOfCode was before the start date of this account, that's why. I should also move some of the projects I worked on over here.
