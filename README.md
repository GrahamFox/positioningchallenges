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