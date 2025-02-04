# Class 1 | August 23

## 📋 Introductions

* Your [instructor](https://cacheflowe.com)
* Review course description. This isn't a frontend course
* Please sign up for Slack if you haven't yet
* "Grad Student Code Helper"
* Student introductions & interests
* Various skill levels
  * Everyone: Learn about the craft, the state of the art, and express yourself creatively with code
  * Beginners: I want you to learn to find joy in coding, and get comfortable with tools, techniques, and nomenclature
  * Advanced: I want you to dig deep, explore concepts, seek out additional challenges to hone your skills
* Special requests to make this course work for you?
* Expectations of conduct & [ethos](../docs/policies.md#ethos-for-learning-code) for learning code

## 📋 What is code?

* Code is software, code is everywhere
  * Code is a web of logic
  * Language & syntax
  * Most modern languages are [very similar](https://en.wikipedia.org/wiki/Comparison_of_programming_languages)
  * Also, node editors
* Why code?
  * Jobs
  * Interdisciplinary work
  * It's fun and magic!
* How to love it
  * Find something that speaks to your interests
    * You'll each find your own path with code (languages, career paths)
  * Find the magic
  * Personal story of failure & persistence
* How to learn it
  * Practice! Try, fail, repeat
    * It's better to start writing bad code than to let yourself get stuck
  * *Write a lot of code*
  * Where to find answers?
    * Break problems down & iterate
      * Ask the questions in English
    * How to search
      * Google
      * [Stack Overflow](https://stackoverflow.com)
      * Blogs/Tutorials
      * [Technical documentation](https://p5js.org/reference/)
    * Community learning - ask each other questions
      * Since we don't have much class time together, this will be an important part of the class. Ask questions along the way.
  * Don't get overwhelmed - some concepts take a long time, and this is a long journey
  * We're learning a new language, but we don't have to memorize everything like a spoken language. We can always look things up on the fly. It's more important to learn the capabilities of the tools than to memorize syntax.
* How to do code
  * Get an IDE that's good for your language of choice
  * Write code into text files
  * Compile or run your program

## 📋 What is (creative) code?

* It's still just code!
  * (With an emphasis on media, graphics, audio)
* "Creative coding", the buzzword
* [Generative art](https://github.com/cacheflowe/creative-coding-notes)
* Tool-making
* All code is creative!
* What kind of creative coder do you want to be?
  * Some [artists](../docs/artists.md) for inspiration
  * Let's build a portfolio and make conceptual work. Generative art becomes much more meaningful with an artist statement.
* What topics are you interested in?
  * Fill out intro survey
  * How can we merge our interests with code?
  * Justin: music, graphics, interaction, games
  * Self-directed and meandering exploration in this field is essential
  * Beginners vs. experts
    * Experts should take this opportunity to build a portfolio

## 🛠️ Get your tools ready

* Processing/p5js
  * For p5js, create an account for [the editor](https://editor.p5js.org/)
    * For Processing, [install the IDE](https://processing.org/download/)
    * If you'd like to use other tools like Unity, TouchDesigner, THREE.js, Openframeworks:
      * I can help during office hours, but you're largely on your own
      * I expect video documentation of your projects, since you can't turn them in via a link to the p5js editor. Use Drive/Dropbox/etc to hand in your documentation
      * Use [GitHub](https://github.com/) to post your code
* Slack
  * Use this to help each other out - like the real world
    * See the [original works](../docs/policies.md#original-works) policy
* Screen capture
  * OS X: [Quicktime](https://support.apple.com/en-us/HT208721)
  * Windows 10: [Xbox Game Bar](https://support.microsoft.com/en-us/help/4027180/windows-10-record-a-game-clip-with-xbox-game-bar)

## 🛠️ Code basics

* Gauge class's comfort levels with basic concepts:
  * Variables
  * Functions
  * Conditionals (if/else)
  * [for() loops](https://en.wikipedia.org/wiki/For_loop#Timeline_of_the_for-loop_syntax_in_various_programming_languages)
  * Arrays
  * Animation
  * Input
  * Objects
  * Classes
* Every language has these - the first goal is to understand these constructs & tools
* If you're *not* comfortable with these, come to office hours and study the following links

## 📝 Homework:

* Get familiar (or refamiliarize) with basic programming concepts
  * If you have little or no code experience, start [here](https://hello.processing.org)
  * Go through the 1st section of articles at [Welcome to Coding](https://happycoding.io/tutorials/p5js/)
    * Even if you're comfortable with the basic concepts, there are lots of important tips within.
    * Get comfortable with:
      * Functions
      * Variables (numbers & booleans for now)
      * Conditionals (if/else)
      * for() loops
      * Arrays
      * Animation
      * Input
  * A video series to reinforce the **Welcome to Coding** articles:
    * [Code! Programming with p5.js](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA)
      * Please follow along with this series, sections 1-4
* Books!
  * https://www.aesthetic-programming.net/index.html
  * https://natureofcode.com/book/
* Prepare your tools & workspace
* Prepare to share & document your work
* Build an [ATLAS logo](https://clementzheng.github.io/atlas-wordmark/index.html) "**A**" of your choice with [code](https://editor.p5js.org/cacheflowe/sketches/igKe9eDoB). Use basic drawing tools to set colors and create shapes:
  * w/p5js:
    * Color
      * [background()](https://p5js.org/reference/#/p5/background)
      * [fill()](https://p5js.org/reference/#/p5/fill)
      * [noFill()](https://p5js.org/reference/#/p5/noFill)
      * [noStroke()](https://p5js.org/reference/#/p5/noStroke)
    * Shapes
      * [Triangles](https://p5js.org/reference/#/p5/triangle)
      * [Rectangles](https://p5js.org/reference/#/p5/rect) and [Quads](https://p5js.org/reference/#/p5/quad)
      * [Ellipses](https://p5js.org/reference/#/p5/ellipse)
      * [Polygons](https://p5js.org/reference/#/p5/vertex)
      * [Bezier](https://p5js.org/reference/#/p5/bezier) or [Quadratic](https://p5js.org/reference/#/p5/quadraticVertex) curves
  * w/Processing:
    * Color
      * [background()](https://processing.org/reference/background_.html)
      * [fill()](https://processing.org/reference/fill_.html)
      * [noFill()](https://processing.org/reference/noFill_.html)
      * [noStroke()](https://processing.org/reference/noStroke_.html)
    * Shapes
      * [Triangles](https://processing.org/reference/triangle_.html)
      * [Rectangles](https://processing.org/reference/rect_.html) and [Quads](https://processing.org/reference/quad_.html)
      * [Ellipses](https://processing.org/reference/ellipse_.html)
      * [Polygons](https://processing.org/reference/beginShape_.html)
      * [Bezier](https://processing.org/reference/bezier_.html) or [Quadratic](https://processing.org/reference/quadraticVertex_.html) curves
  * If this is easy for you, try some stretch goals:
    * Add animation or interactivity
    * Get creative with color
    * Build an "A" with different drawing functions. For example: ellipse() circle() and a rounded rect() can all draw the same shape
    * Make your own "A" designs
    * Build several different "A" logos
      * Explore p5 API and learn how to create even more shapes
    * Build the "A" in a larger, designed layout with code
    * Morph one "A" to another
    * Make it "pixel-perfect": Load an image and draw your shapes on top to make sure it's perfect
    * Make an interesting background - use an image or generate a pattern
    * Use a different tool (Shadertoy, TouchDesigner, Unity) to make an "A"
  * Turn in your work via Canvas
    * Post the link to your code on (https://editor.p5js.org/)
    * Add a description of your intent, your successes, and failures
    * If you're using a different tool, post a link to a video and optionally post your code to GitHub
