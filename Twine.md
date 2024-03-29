# Twine

*Created by Miranda Jones-Davidis and Miriam Neptune*

*Updated April 6, 2023 by Fatima Azimova*

## Introduction to the tool

Twine is a flexible tool for creating an interactive narrative game.

With Twine, you can use very simple markup commands to link blocks of text together, and create moments of interaction for the reader, i.e. through making choices. Images and sound can be added.

Using Javascript and CSS, Twine authors can add layers of complexity and aesthetics. Twine games are easily published and shared.

### This tool is great for:

- Writing "choose your own adventure" style stories, tours, and narrative games.
- Encouraging creativity in writing, where students are encouraged to think through aesthetics, form, and rhetorical choices.
- Practicing a basic markup language that is simpler than HTML.

### This tool is not great for:

- Visualizing data
- Collaborative projects (You must save and share your Twine story as an HTML file to work collaboratively)

### Materials:

- Internet access
- Reliable web browser (preferably Chrome or Firefox)
- (optional) 20 Post-it notes or index cards
- (optional) Markers

## Part 1 - Exploring Narrative Structure with Twine

Before you begin to work with Twine, you may want to explore possible structures to implement in your interactive narrative. Linked here is some background reading for creating interactive narratives: ["Interactive Narrative | Play with Learning"](http://playwithlearning.com/2010/10/14/exploring-interactive-narrative-part-1-of-6/), ["Serious Interactive Fiction: Constraints, Interfaces, and Creative Writing Pedagogy](https://scholarworks.rit.edu/jcws/vol3/iss1/10/), and ["Game Design as Narrative Architecture](http://web.mit.edu/~21fms/People/henry3/games&narrative.html).

### Thinking about Narrative Structure

Think of a movie or a TV episode you watched recently. Think about the protagonist in that story. What happened for the character at the beginning, middle, and end of the story? What was their goal at the beginning, what obstacles did they face, and where did they end up? What was the climax of the story? Diagram the story. Below is an example of a way to illustrate story structure.

<p align="center">
  <img align="center" src="https://github.com/dhc-barnard/tutorials/blob/master/images/twine/narrative%20structure%201.jpg" width="75%" alt="example of narrative structure in which a character has a goal and goes through a series of events where they come home changed">
</p>

You can create a line and add some points, or list each plot point on a post it and try to arrange them in a shape indicating rising action, climax, falling action. Or maybe your story is circle, a straight line, or a non-linear experience! Twine has the capability to allow users to create branching narratives and multi-linear narratives, and you can explore these narrative types as you learn more about the tool.

## Part 2 - Twine Basics

In this section, we will:
1. Start a Twine story.
2. Learn basic markup to connect parts of a story.
3. Add or change the story.

### Step 1 - Getting Started

Go to [twinery.org](http://twinery.org/). Here, you have two options for using Twine: you can download the application onto your computer where files will be saved locally in your Documents folder, or you can access the website through your web browser, where stories are saved in the browser's local storage. If you decide to download the application onto your computer, click the download link for your type of computer on the yellow sticky note on the right-hand side of the page. Follow the prompts to download. If you decide to use Twine online, click "use it online" on the yellow sticky note on the right-hand side of the page.

Important things to remember when using Twine online are that clearing sessions and cookies in a browser may also clear the storage of Twine. **If you clear your browser's data, you'll lose your work!** Also, you need to use the same browser every time you use Twine because local storage is browser specific. Finally, anyone who uses your browser can see and make changes to your work if they access the Twine website. 

### Step 2 - Creating a New Story

To create a new story, click on the "+ new" symbol below the Story tab on the left of the page.

<img align="center" width="10%" src="https://github.com/dhc-barnard/tutorials/blob/master/images/twine/new_story.png" alt="Screen grab of New Story Button">

Name your story: enter a name for your story (you can change this later!) If you're planning to use the text from this tutorial, you can name your story "Strange Encounter in Space."

<p align="center">
  <img src="https://github.com/dhc-barnard/tutorials/blob/master/images/twine/3-name-story.png" alt="Screen grab of naming story" width="75%">
</p>

Again, if you are using the browser-based version of Twine, the story file will be saved in your browser so if you erase your browser cache, your work will be deleted. Select 'Build' from the navigation bar at the top and click "Export as Twee" - if you want to save the code and/or "Publish to File" - if you want to save the full story as html document.

<img align="right" width="20%" src="https://github.com/dhc-barnard/tutorials/blob/master/images/twine/2-archive.png" alt="Screen grab of Archive Button">

If you are using the desktop version of Twine, your story will be saved to your documents folder. If you would like to archive a particular version of your story, select "Archive" to save the most recently edited version as an html document. 

### Step 3 - Adding Content


After you name your story, you will find yourself at a page that looks like a blueprint. You are now in the Passages View, where you can view all of the passages of your story. Right now you only have one passage in the middle of the screen labelled "Untitled Passage."

<p align="center">
  <img src="https://github.com/dhc-barnard/tutorials/blob/master/images/twine/4-passage-view.png" alt="Passages view" width="75%">
</p>

Double click the box to edit the passage.

<p align="center">
  <img align="center" width="30%" src="https://github.com/dhc-barnard/tutorials/blob/master/images/twine/5-untitled%20passage.png" alt="Double click this passage to edit">
</p>

Once opening the passage, you can edit its name (we're using "Arrival"), tags, and contents. To change the contents of the passage, double click the text "Double-click this passage to edit it" and add some content of your own. If you are just learning how to use twine, we suggest adding the following text:
 > As soon as the hatch of your ship, the Coriolis, opens, you see the creatures swarming around you. There are many of them, more than you can easily count, and they are all continuously in motion. </br>
[[Try talking to the creatures]]</br>
[[Walk down the ramp of your spaceship]]


You are now using hypertext markup! Each of these bracketed phrases will become a “block” or page in the story. When you are done editing, close the passage editor by using the Escape key or by clicking the "x" in the upper right corner.


### Step 4 - Continue Building Your Story

You are now in the Passages view and should see the two new blocks created by your markup. You can drag each passage while maintaining their connection to the initial passage block. For each new passage, double-click the block and add write in what you think happens next for each choice.

<p align="center">
  <img align="center" width="30%" src="https://github.com/dhc-barnard/tutorials/blob/master/images/twine/connected-passages.png" alt="Three passages connected with arrows.">
</p>

You can continue "branching" your narrative by additing additional choices. Remember to add two brackets around choice text in order for your text to become a link to a new passage (e.g. ``[[Try talking to the creatures]]``). 

At some point, you may wish for your reader to return to a specific passage. For example, they may fail a choice and be sent back to the beginning of the story. To connect a passage to an existing passage, add an error to the block notation. ``[[Arrival<- Start Over]]`` sends the reader back to the first passage in our story, titled "Arrival."  

Create a link back to the beginning on one of your passages. You can experiment more with links by reading the [Twine Cookbook](http://twinery.org/wiki/twine2:how_to_create_links).


### Step 5 - Playing a Story

Now that you've added some text to your story, play your story to see how it looks!

In the navigation bar, select Build and clikc on Play This menu allows you to navigate, change, and play your story. Click on the "Play" button in the bottom right-hand corner of the screen.

<p align="center">
  <img align="center" src="https://github.com/dhc-barnard/tutorials/blob/master/images/twine/8-top-play.png" alt="story menu at the bottom of the screen" width="75%">
</p>

Your story will open as an HTML file in your web browser.


### Step 6 - Save your Story

When you are ready to save and/or share your story, navigate to the menu bar and click on the Build. Select the option "Publish to File" to save your story as an HTML file that you can open in any browser to play.

## Part 3 - Personalizing Your Twine Story

In this section you will learn how to do the following with Twine:
1) Change your story's background color
2) Change font type, font size & font color
3) Customize a specific text block
4) Add an image

In this section you will be using [CSS](https://www.w3schools.com/css/) markup language to customize your Twine story. You will need no prior experience in CSS to do this exercise.
- CSS stands for Cascading Style Sheets.
- CSS instructs your browser on how to display content (HTML elements).
- CSS saves a lot of work. It can control the layout of multiple web pages all at once.

**Basic CSS Terms:**

Text Align - Chose between “Left”, ”Right”, & “Center"

Color - Color of text, name color e.g. Red or Hex e.g. #0635c9

Font Size - Choose any font size number e.g. 18pt

Font Family - Choose any web-safe font

Background Color - Change the color of the individual block

Padding - Distance of text from border (recommendation choose between 1%-15%)

### Changing Background Color

navigate to the navigation bar and click on Story, then select “Stylesheet" The empty stylesheet can be used to enter CSS code. In this tutorial we will provide basic code that you can copy and paste into your own stylesheet

<p align="center">
  <img src="https://github.com/dhc-barnard/tutorials/blob/master/images/twine/stylesheet-new.png" alt="story stylesheet" width="18.4%"/>
  <img src="https://github.com/dhc-barnard/tutorials/blob/master/images/twine/stylesheet-popup.png" alt="story style sheet before" width="35%"/>
  <img src="https://github.com/dhc-barnard/tutorials/blob/master/images/twine/miriam%20-%203%20after.png" alt="story style sheet after" width="35%" />
</p>

Copy and paste the CSS code below into your stylesheet. Change background-color to any other color e.g. from “White” to “Red”

```
tw-story {
background-color: White;
}
```

Advanced: Use a [hex number color code](https://www.w3schools.com/colors/colors_picker.asp) e.g. #ed2d2d

```
tw-story {
background-color: #ed2d2d;
}
```

To view your changes, exit the style sheet (no save needed) and click play. Check to see if you like the changes you made. You can always go back and change it to a different color.

<p align="center">
  <img align="center" src="https://github.com/dhc-barnard/tutorials/blob/master/images/twine/miriam%20-%205%20before.png" alt="story page before" width="44%"/>
  <img align="center" src="https://github.com/dhc-barnard/tutorials/blob/master/images/twine/miriam%20-%206%20after.png" alt="story page after" width="45%"/>
</p>

### Changing the Font

Open the story stylesheet. Copy and paste the CSS code below into your stylesheet.

```
tw-passage {
color: Blue;
font-family: garamond;
font-size: 100%;
}
```

Switch out the word "garamond" with any other web-safe font family. For example, you could use "Arial Black" or any other font listed at [w3schools.com](https://www.w3schools.com/cssref/css_websafe_fonts.asp).

Check to see if you like the changes you made by exiting the style sheet and clicking "play."

<p align="center">
  <img align="center" src="https://github.com/dhc-barnard/tutorials/blob/master/images/twine/miriam%20-%207%20before.png" alt="font before" width="45%"/>
  <img align="center" src="https://github.com/dhc-barnard/tutorials/blob/master/images/twine/miriam%20-%208%20after.png" alt="font after" width="43%"/>
</p>

### Changing the Font Color

You can change the color of your text by changing the color in your CSS code (shown below) to another color, e.g. from "Blue" to "Pink."  You can also change the color to a hex number color code. Once you've changed your code, check to see the changes you've made by exiting the style sheet and clicking "play."

```
tw-passage {
color: Blue;
font-family: garamond;
font-size: 20pt;
}
```
<p align="center">
  <img align="center" src="https://github.com/dhc-barnard/tutorials/blob/master/images/twine/miriam%20-%209%20before.png" alt="font color before" width="45%"/>
  <img align="center" src="https://github.com/dhc-barnard/tutorials/blob/master/images/twine/miriam%20-%2010%20after.png" alt="font color after" width="45%"/>
</p>

### Customizing a Specific Block of Text

The CSS codes used in earlier parts of this tutorial will automatically apply to your whole story on Twine, so if you only want to customize a specific text block, you can use the "tag" function.

<p align="center">
  <img align="center" src="https://github.com/dhc-barnard/tutorials/blob/master/images/twine/block%20text%202.png" alt="one specific block on the map" width="45%"/>
</p>

First, open a block and add a tag (e.g. "IMATS") with the "+Tag" button. Then, go back to your style sheet.

<p align="center">
  <img align="center" src="https://github.com/dhc-barnard/tutorials/blob/master/images/twine/block%20text%203.png" alt="edit block and add tag" width="50%">
</p>

In order to change the style of the singular block, copy and paste the CSS code below into your style sheet.

```
tw-passage[tags~="IMATS"]{
text-align: center;
color: White;
font-size: 25pt;
font-family: Comic Sans MS;
background-color: Pink;
padding: 10%;
}
```

To customize your block, replace “IMATS” in the tw-passage[tags~="IMATS"] section to the name of the tag in the block you're trying to customize. Customize the style as you wish by changing the color, font family etc. as you did in the previous sections. Now that you've added a tag name to this set of code in your stylesheet, any changes you make to this block of code will only apply to the block in your story with the matching tag name.

### Adding an Image

First, choose an image that can be easily inserted into your Twine story. The image should have a url and either be your own image or be a copyright free image. Once you've found the image you'd like to use on Google or another website, right-click the image to "copy image address." Then, open the block you want to add your image to. Copy and paste the CSS code below into the block description (NOT the CSS style sheet). Replace the url in the code with the url you've copied.

<p align="center">
  <img align="center" src="https://github.com/dhc-barnard/tutorials/blob/master/images/twine/add%20image%201.png" alt="find image and right-click to copy address" width="41%">
  <img align="center" src="https://github.com/dhc-barnard/tutorials/blob/master/images/twine/add%20image%202.png" alt="open the block you want to add your image to" width="30%"/>
  <img align="center" src="https://github.com/dhc-barnard/tutorials/blob/master/images/twine/add%20image%203.png" alt="add CSS" width="27%"/>
  </p>

```
<style>
img {
max-width: 100%;
max-height 100%;
}
</style>

<img src=https://library.barnard.edu/ sites/default/files/inline-images/BLAIS-LIB-Peets_0.jpg></span>
```

Change the size of the image by changing the percentage of max-width and max-height. Your final code and final product might end up looking similar to the images below.

<p align="center">
  <img align="center" src="https://github.com/dhc-barnard/tutorials/blob/master/images/twine/add%20image%204.png" alt="final code" width="45%">
  <img align="center" src="https://github.com/dhc-barnard/tutorials/blob/master/images/twine/add%20image%205.png" alt="final product" width="49%"/>
</p>

# Reflections:

- What impact does branching narrative have on a story, and you as the reader? What are the challenges of writing in this way?
- How did creating multi-linear passages make you think differently about your project and its content?

# Resources:

- [How to get started with Twine](https://twinery.org/cookbook/starting/twine2/firststory.html)
  1. In the table of contents on the left, you can browse more and find more resources on how to add links, choose the story formats, how to review, etc.
- [How to add HTML and CSS](https://twinery.org/cookbook/html/reviewing.html)

  2. On the same web, on the left table of contents you can find sections like
  Working with HTML
  Working with CSS

## Examples of Successful Projects:

- [The Social Life of Data](https://sociallifeofdata.org/) - An educational experience created to allow users to explore how information is created, travels, and is contested across different media.

## Background Reading
- [“Interactive Narrative | Play with Learning.”](http://playwithlearning.com/2010/10/14/exploring-interactive-narrative-part-1-of-6/)
- Terry, Robert and Dusenberry, Lisa (2018) ["Serious Interactive Fiction: Constraints, Interfaces, and Creative Writing Pedagogy,"](https://scholarworks.rit.edu/jcws/vol3/iss1/10) Journal of Creative Writing Studies: Vol. 3 : Iss. 1 , Article 10.
- [“Branching Narrative from Borges to Twine | 60210-C • ELECTRONIC MEDIA STUDIO: Interactivity.”](http://cmuems.com/2015b/branching-narrative-from-borges-to-twine/)

## Other Guides & Tutorials:

- [The Twine Cookbook](http://twinery.org/cookbook/index.html) - A collection of tips and examples of how to use Twine. Also available on [Github](https://github.com/iftechfoundation/twine-cookbook).
- [The Interactive Fiction Community Forum](https://intfiction.org/c/authoring/twine/46) - A forum for discussions about how to use Twine.
- [The Twine Wiki](http://twinery.org/wiki/) - A wiki containing information on the history of Twine and how to use the program.
- [Twine Discord](https://discord.com/invite/n5dJvPp) - A Discord channel for Twine users to discuss their work and progress.
- [Twine Beginners Series](https://www.youtube.com/watch?v=iKFZhIHD7Xk&list) - A series of YouTube videos on how to use Twine.
- [W3Schools CSS Tutorials](https://www.w3schools.com/css/) - For more information on how to use CSS.

## Barnard Resources:

- Barnard faculty, staff, and students are free to reach out to the [DHC](https://digitalhumanities.barnard.edu/).
