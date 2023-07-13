# CSS In-Class Assignment Instructions

### Class Vs. Tag Specificity Rule

1. Open your HTML-in-class-project
2. Open the styles.css file
3. At the top of the file, write a style rule to turn all h1's blue ![CSS code to turn all h1's blue](/assets/h1-blue.png)
4. Look at your website in the browser
5. In your HTML, find an h1 and add a class attribute with a value of "red-text"
6. Write a style rule in your CSS to turn that element red ![color-red code example](assets/red-h1.png)
7. Which style rule 'won'?

### Inline/Internal/External

Using the code examples on the slides, add three different style rules, three different ways (inline, internal, & external)!
   
### As A Group: Dev Tools

Sometimes your browser's Dev Tools can be a great way to try out different rules. Each step in this section should be tried out in the Chrome Dev Tools _before_ you put the working code into VS Code.

**Keep in mind that making changes in the Dev Tools does _not_ affect your code.** It makes a _temporary_ change in the browser's view of your page. Even reloading the page will remove your changes! To make them permanent, the change _must_ go in your actual code.

##### How To Change A Specific Element's Style

1. Press `command-shift-c` on your keyboard to launch the element picker.
2. Click in the browser on the element you want to change. In the Dev Tools, there should now be an HTML section on top with your element selected. On the bottom, there should be a "Styles" section with CSS.
3. Click on `element.style` in the bottom section.
4. Type in your CSS property and value. The element should change to match!

##### How To Change Multiple Elements' Styles

1. If you don't already have the Dev Tools open, press `command-shift-i` on your keyboard. Make sure you are at the "Elements" tab at the top of the Dev Tools.
2. In the bottom half of the Dev Tools, make sure you are at the Styles tab.
3. Just below the tabs that include "Styles", and almost all the way to the right of the screen, there's a `+` button. Press that.
4. Now you can enter any selector, and then any rule for it. The selected element or elements should change to match.

##### Task Instructions

- In the Dev Tools, change the first paragraph to green—it's the one that begins with, "Welcome to the world of HTML!" Once you have that working in the Dev Tools, add a class to the paragraph in the HTML file and use CSS to make the change permanent in the CSS file.
- In the Dev Tools, change the image in the About Our Products section to have a width of 100 pixels. Once you have that in the Dev Tools, find the line of CSS setting the width of the image and change it to make the 100-pixel width permanent. The selector being used is `.about-img-wrapper img`—you can find it using VS Code's Find command (`command-f`) and typing in that selector.
- Use the Dev Tools to write a rule to change _all_ H1s to a different color (see directions of how to change multiple elements' styles above!). Once you've got working code, write that same rule in your CSS file.
- Use the Dev Tools to change all headings (of any size!) to use the font "Times New Roman". Either do them individually, or with a ["selector list"](https://developer.mozilla.org/en-US/docs/Web/CSS/Selector_list), where you separate the selectors with a comma and a space. Now make the change permanent in your CSS file—you'll definitely want to use a selector list here to save time.
- Using the Dev Tools, make all text in the gallery section a different color. Find an **already-existing** class in the HTML file that you can use to affect the text, then add the rule to your CSS file.
- Using the Dev Tools, make the blue box of text for the certification process section 40% of the viewport height. Find an **already-existing** class in the HTML file that you can use to affect the blue box, then add the rule to your CSS file.

### Border Bonanza - Lab Time

1. Open your in-class HTML project
2. Navigate to styles.css 
3. Add borders to at least 20 style rules. See below for an example!
4. You can choose different styles and have fun with it!
5. Check out your work in the browser

![border code example](/assets/border-example.png)

### Styling Text

There are endless ways to style text. We'll learn a few and practice them!

1. Check out [this text styling cheatsheet ](https://medium.com/swlh/css-styling-cheat-sheet-109bd78038e1) to get some ideas.
2. Let's take a moment and style the text to our CSS In Class Exercises. You can add whatever styles you'd like.
3. We'll come back and take volunteers to share what they did!
