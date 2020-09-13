Steps taken:
1. Changed the title of the page to Horiseion

2. Making the link for search engine optimization work by adding id="search-engine-optimization" in addition to the class of the same name
		Note: WHen navigating to a point in the same page, you can navigate to an ID as they are unique to the element but you CANNOT navigate to a class

3. Added alt tags to three images on left side bar and three icons of right sidebar

4.Getting alt text for the background-image in the hero division
		Added a transparent image to the hero division with an appropriate alt tag

5. I consolidated the three .benefit-(lead, brand, cost) to .benefits p to avoid redundancy

6. In CSS file, I removed the following from the .benefit-(lead, brand, cost) and into the .benefits since it applied to all three to avoid redundancy
color: #ffffff;

7. I removed the three .benefit-(lead, brand, cost) h3 and replaced it with just h3 to avoid redundancy

8. I replaced the three .benefit-(lead, brand, cost) img with .benefits img since it applied to all three (I did need to include the .benefits since there are other images in the html file)

9. I added additional classes to the three sections of the left sidebar such that I could replace the three portions of identical CSS code with one 

10. Replaced three separate .class img with .content img to avoid redundancy

11. Replaced three separate .search-engine….. h2 with .content h2 to avoid redundancy

12. I removed the .footer h2 and added that command to .footer as that was the only text in that section

13. Removed the following from CSS as it didn’t seem to change functionality:
p {
    font-size: 16px;
}

14. Removed the following from the CSS as it didn’t seem to change the functionality
.header div ul {   list-style-type: none;}

Goals:
Make sure HTML is semantically correct 


There should be a logical flow of HTML elements

All links should be working 
	Had to fix one link (see #2 above)

The title is logical
	See #1 above

Images need alt tags
	See #3 and #4 above

CSS selectors and properties are efficient
	See #5-14




