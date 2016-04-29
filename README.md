# Box Style Code Along

## Objectives

1. Review CSS Background property
2. Review CSS Box Shadow
3. Review CSS Gardient backgrounds.

## Introduction

Building upon previous code alongs, in this exercise you will add styling to the the backgrounds of your page elements by coding along with the video provided. This will help you to review the concepts you were introduced to in the previous lessons.

## Instructions

1. Fork this repository.
2. Use Terminal to clone your forked copy.
3. Then change directory into the repository folder.
4. Code along with the provided video below and/or its supplementary reading located below the video. Code everything you see there. Feel free to stop, pause, rewind or fast forward through the content to keep pace.

*Note: The gradient code that is copied and pasted in teh video is located below the video as code snippets as well.*

<iframe width="100%" height="720" src="//www.youtube.com/embed/Y4El1I-hagQ?rel=0&controls=1&showinfo=1" frameborder="0" allowfullscreen></iframe>

The gradient code that is copied and pasted in the exercise video is available here:

```css
/* LIGHT-FADE */
  background: #efefef; /* Old browsers */
  background: -moz-linear-gradient(top,  #efefef 0%, #ffffff 24%, #ffffff 68%, #dddddd 100%); /* FF3.6+ */
  background: -webkit-gradient(linear, left top, left bottom, color-stop(0%,#efefef), color-stop(24%,#ffffff), color-stop(68%,#ffffff), color-stop(100%,#dddddd)); /* Chrome,Safari4+ */
  background: -webkit-linear-gradient(top,  #efefef 0%,#ffffff 24%,#ffffff 68%,#dddddd 100%); /* Chrome10+,Safari5.1+ */
  background: -o-linear-gradient(top,  #efefef 0%,#ffffff 24%,#ffffff 68%,#dddddd 100%); /* Opera 11.10+ */
  background: -ms-linear-gradient(top,  #efefef 0%,#ffffff 24%,#ffffff 68%,#dddddd 100%); /* IE10+ */
  background: linear-gradient(to bottom,  #efefef 0%,#ffffff 24%,#ffffff 68%,#dddddd 100%); /* W3C */
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#efefef', endColorstr='#dddddd',GradientType=0 ); /* IE6-9 */
```

```css
/* MEDIUM-FADE */
  background: rgb(229,229,229); /* Old browsers */
  background: -moz-linear-gradient(top,  rgba(229,229,229,1) 0%, rgba(255,255,255,1) 99%); /* FF3.6+ */
  background: -webkit-gradient(linear, left top, left bottom, color-stop(0%,rgba(229,229,229,1)), color-stop(99%,rgba(255,255,255,1))); /* Chrome,Safari4+ */
  background: -webkit-linear-gradient(top,  rgba(229,229,229,1) 0%,rgba(255,255,255,1) 99%); /* Chrome10+,Safari5.1+ */
  background: -o-linear-gradient(top,  rgba(229,229,229,1) 0%,rgba(255,255,255,1) 99%); /* Opera 11.10+ */
  background: -ms-linear-gradient(top,  rgba(229,229,229,1) 0%,rgba(255,255,255,1) 99%); /* IE10+ */
  background: linear-gradient(to bottom,  rgba(229,229,229,1) 0%,rgba(255,255,255,1) 99%); /* W3C */
```

```css
/* NAVBAR-HOVER */
  background: rgb(0,0,0); /* Old browsers */
  background: -moz-linear-gradient(top,  rgba(0,0,0,1) 0%, rgba(71,71,71,1) 28%, rgba(81,81,81,1) 35%, rgba(71,71,71,1) 72%, rgba(43,43,43,1) 87%, rgba(28,28,28,1) 91%, rgba(0,0,0,1) 100%); /* FF3.6+ */
  background: -webkit-gradient(linear, left top, left bottom, color-stop(0%,rgba(0,0,0,1)), color-stop(28%,rgba(71,71,71,1)), color-stop(35%,rgba(81,81,81,1)), color-stop(72%,rgba(71,71,71,1)), color-stop(87%,rgba(43,43,43,1)), color-stop(91%,rgba(28,28,28,1)), color-stop(100%,rgba(0,0,0,1))); /* Chrome,Safari4+ */
  background: -webkit-linear-gradient(top,  rgba(0,0,0,1) 0%,rgba(71,71,71,1) 28%,rgba(81,81,81,1) 35%,rgba(71,71,71,1) 72%,rgba(43,43,43,1) 87%,rgba(28,28,28,1) 91%,rgba(0,0,0,1) 100%); /* Chrome10+,Safari5.1+ */
  background: -o-linear-gradient(top,  rgba(0,0,0,1) 0%,rgba(71,71,71,1) 28%,rgba(81,81,81,1) 35%,rgba(71,71,71,1) 72%,rgba(43,43,43,1) 87%,rgba(28,28,28,1) 91%,rgba(0,0,0,1) 100%); /* Opera 11.10+ */
  background: -ms-linear-gradient(top,  rgba(0,0,0,1) 0%,rgba(71,71,71,1) 28%,rgba(81,81,81,1) 35%,rgba(71,71,71,1) 72%,rgba(43,43,43,1) 87%,rgba(28,28,28,1) 91%,rgba(0,0,0,1) 100%); /* IE10+ */
  background: linear-gradient(to bottom,  rgba(0,0,0,1) 0%,rgba(71,71,71,1) 28%,rgba(81,81,81,1) 35%,rgba(71,71,71,1) 72%,rgba(43,43,43,1) 87%,rgba(28,28,28,1) 91%,rgba(0,0,0,1) 100%); /* W3C */
```

### Styling The Backgrounds

Lets start out by making a new feature branch in Terminal by typing `git checkout -b navbar-and-background-styles` and press return. 

Next, bring up the style.css file in your code editor. Start by removing the background colors from our column classes. Scroll down to the area of the code with the comment label for "LAYOUT".

```css
/*////////// LAYOUT //////////*/

.col-1 {
  float: left;
  width: 32%;
}

.col-2 {
  float: left;
  width: 66%;
}

.col-3 {

}

```

Next, in the ""

It's now time to version our changes using Git. To do so, in Terminal type `git add .` and press return. Then type `git commit -m "style backgrounds for section, navbar, and details"` and press return. Then push up this feature branch `git push -u origin navbar-and-background-styles` and press return. Next merge the changes into your master branch. Type `git checkout master` and press return, then `git merge navbar-and-background-styles` and press return. Then `git push origin master` and press return.

After you finish, make sure you install Firefox if you haven't already as it is required for the screenshot tests to run. Then, type learn command from Terminal to run local tests (Mac) or type learn-test for Windows.

After all tests are passing submit a pull request on Github and move on to the next lesson!

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/fe-code-along-ex-5' title='Code Along Exercise 5'>Code Along Exercise 5</a> on Learn.co and start learning to code for free.</p>
