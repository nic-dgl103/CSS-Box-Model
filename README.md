# Exercise 5

## Objectives
ractice working with the CSS box model to create some typical web card layouts.

## Instructions
Remember to:
* Regularly save your files and check out what your web page looks like in a web browser.
* Make regular commits and pushes.
### Get set up
* Clone your remote exercise repository onto your local machine.
* Add a comment in the head element of the homepage including: the course code and your section number - your name - Exercise 5. Example:
```
<!-- DGL 103 CVS1 - your name - Exercise 5 -->
```
### Card 1:
In VS Code, add the following styles to the article element with the class name card-one:
   * Make the image round by using the border-radius property.
   * Give the card a background colour of `hsl(0, 0%, 100%)`.
   * Make the width of the card 500px.
   * Give the card a 50px margin on all four sides so that it isn't so close to the browser window's edges.
   * Give the card 30px of padding on all four sides so that the content doesn't touch the edges of the card.
   * Round the corners of the card by a 5px radius.
   * Give the card a top border that is 3px thick, solid in style and of the color `hsl(180, 62%, 55%)`.
   * Give the card a shadow. Go to https://getcssscan.com/css-box-shadow-examples to find a pleasing shadow.
 When you are finished the card should look like this: <br />
 ![Image of card one](images/card-one.png)

### Card 2:
Add the following styles to the article element with the class name card-two:
   * Give the card a background colour of `hsl(234, 12%, 34%)`.
   * Give the card the same margin and padding as card one.
   * Change the width of card so that it matches the visual width of card one.
   * Round the corners of the card by a 30px radius.
   * Make the card's h2 and p elements white;
   * Play with background properties:
      * Using the background CSS property, add a gradient to the card's background. Go to https://cssgradient.io/ to create a gradient that you like.
      * Give the card a background image that uses the elephant image available in the images folder (the background image will hide the gradient).
      * Try out different background-size values until you find one that you like: https://developer.mozilla.org/en-US/docs/Web/CSS/background-size.
      * Combine your gradient with the image by copying and pasting the gradient in front of the image url - don't forget the comma in between the two. <br/>
      Ex: `background-image: linear-gradient(356deg, rgba(34,193,195,1) 0%, rgba(253,187,45,0.022846638655462215) 100%), url('images/elephants.jpeg');`
   * Just for fun, see what happens when you apply `filter: grayscale(100%);` to the card so that the whole card becomes grayscale.
 When you are finished, but before the grayscale filter, the card should look like this: <br />
 ![Image of card two](images/card-two.png)

### Card 3:
Recreate the card below. Try to use similar fonts (Google Fonts), colours, image, alignment and spacing. You can source an image from a website such as https://www.unsplash.com or https://www.pexels.com (any image of a landscape will work). Be as exact as you can with your styling, pixel-perfect if possible.<br />
![Image of card three](images/card-three.png)

### Card 4:
Recreate the card below. Try to use similar fonts (Google Fonts), colours, alignment and spacing. Use the file called yellow-background.png in the images folder. Be as exact as you can with your styling, pixel-perfect if possible. Note that the small text above the headline is not a button.<br />
![Image of card four](images/card-four.png)

### Format, organize and add comments 
* Use the Prettier VSCode extension to format your code.
* Add organizational CSS comments and order your style rules so that your CSS is easy to read.
* Add a few comments to explain your HTML and CSS code and highlight anything of interest.

### Check for errors
Use the VSCode HTMLHint extension and validate your code to make sure that it is correct(https://validator.w3.org/#validate_by_upload for HTML, https://jigsaw.w3.org/css-validator/ for CSS).

### Submit your work
1. Commit your changes.
2. Push your changes to GitHub. 
3. Submit in Brightspace to the "Unit 2 Exercises" assignment and follow the instructions. 
4. If you have been using a lab computer on campus, remember to restart the computer.

## Deadlines
Assignments must be submitted before the end of the week but they will only be graded at the end of every unit. Late assignments will not be accepted and will receive an F. You can complete and submit a contract that allows you to extend the deadline for an assignment but you must email it to your instructor a minimum of 48 hrs before the deadline. Deadline extensions are only allowed for those unplanned, unexpected emergencies that life sometimes throws at us, and they will only be approved by your instructor if you follow the correct process. See the Course Info folder in BrightSpace for more info.