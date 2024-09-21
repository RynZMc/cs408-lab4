# Web Dev Starter Code

## Overview

This is a site that was provided to us and updated by me to improve overall accessibility. To use, simply open a live preview of the site and navigate as normal.

## Accessibility Lab Answers

//Color//

1. I was able to run a test at the first link sourced below (coolors.co) to see
how accessible the background and text color combinations were and the result 
was a 2.74 or "very poor" (1/5 stars) for both small text and large text. After
swapping out the background0 color for white (#ffffff) I ran the same test with the 
new background color replacing the old one, this time the site scored a 14.09, "super",
(5/5 stars) for color contrast and color accessiblity.

//Semantic HTML//

1. Spacebar sends the scroll bar to the bottom of the screen, tab seems to work moderately 
well, but skips to the elements at the bottom of the screen prior to the links located on 
the right which jolts your vision straight downard in a harsh fashion. Arrow keys allow
the user to scroll. There aren't any fantastic options for a user to navigate the article
either. 

2. Yes, by placing each of the titles (The trouble with Bears, types of bears, etc) into a header, a person using a screen reader should be able to far more easily navigate between them as screen readers allow for the user to navigate by headers. Since there is a header at each important seperation in the article, the user will be able to navigate anywhere in the article with ease.

3. The proper html semantic element is a "nav" element. I have swapped out the div for a nav instead. 

//The Images//

1. I have added alt text to each of the images which describes the type of bear and their surroundings concisely.

//The Audio Player//

1. I have added a transcript of the audio file as my choice of accessible alternative. It has been placed directly below the audio menu. 

2. I added a direct link along with the message about HTML audio incompatibility. This will allow the user to directly follow the link. The user could also download the file as our audio tag has a download button.

//The Forms//

1. I added an aria-label with the name "search". This label will allow screen reader users to hear the label read to them while keeping it invisible for sighted users.

2. I added a proper label tag to both the "your name" and "your comment" inputs. This will allow for these to be unambiguously associated with their labels now. Along with that I edited the text to be bold (in css) for a better reading experience. 

//The Show/Hide Comment Control//

1. Yes, by replacing the previous "div" element with a button, the user will now be able to both tab to the show comments section and use the return key to toggle the comments to be shown or not. 

//The Table//

1. Yes, by utilizing "th" tags with scope set to columns and rows for respective types, the table becomes far easier to read and differentiate sections. Along with this, using a caption above the table allows the user to understand what the table contains even if they use a screen reader. 


//Other Considerations//

1. Adding some element (for the user to tab to) between the navigation bar and the audio section to make it so that if the user is using tab rather than the arrows to navigate up and down the page they don't get immediately jolted down to the audio section would be quite helpful for accessibility. 

2. Allowing users to change font sizes easily on the fly would be a great way to help those who cannot read smaller fonts have an easier time reading this article and navigating the site.


## Sources and Credits

- (color contrast test) https://coolors.co/contrast-checker/2a2a3a-008000 
- (Screen reader explanation) https://accessibility.wayne.edu/news/how-screen-readers-work-60460#:~:text=Screen%20reader%20users%20often%20move,desired%20section%20of%20the%20page.
- (Labels) https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Attributes/aria-label
- (Labels) https://www.w3schools.com/tags/tag_label.asp
