#Challenge: Absolute Positioning
Continuing from the final challenge in the previous lesson, we are going to add a link-to-top image to the bottom right of the content div.

layout

1- Remove the borders and left align the paragraphs (optional).

2- Place the image (located in this lessons image folder) after the final paragraph closing tag in content div.

Note: Syntax of the img tag
3- Give the image an id of linkToTop and we can give all paragraphs a bottom margin of 50px to make room for the image.

sidebar-content

4- This is the most important step! Change the position of content to relative and linkToTop to absolute.

5- Notice how the element is now removed from the normal flow of the page. Now we can offset it where we like in relation to the content div.

6- Place the linkToTop on the bottom right of content.

    bottom: 0px;
    right: 0px;   /*experiment with other values*/
layout2

7- From here we can offset the image if we wish. This example shows the offset is to the right with a minus value which will place it outside the content box.

    right: -80px; /**/
layout3

8- For practice add another element to the left of the sidebar. It should have its own id (`#sideLinkToTop)

layout3

#Developer Tools

Challenge: Developer Tools

Open up Developer Tools in Chrome.
Using your new toolbox select HTML elements and alter their CSS rules in the browser.
Try refreshing the page (shortcut F5)

css

You can also add new CSS rules !!

Try and replicate the following:

red
_Change Background Color _

alignment
_Change text alignment _

text-color
_Add a color property to change the font color. _

See what else you can do!!
Remember none of your changes are saved when using Chrome Developer tools.
Go to a website you use often (maybe wikipedia) open Developer Tools and change the layout as you see fit