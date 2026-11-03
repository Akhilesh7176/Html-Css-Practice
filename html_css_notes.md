HTML is the Hypertext Markup Language which is the content that can be seen on any website.\
The document first we write is ususally index.html\
Then the chronological order is we start with <!DOCTYPE html> this indicates and tells the Browser that this website follows the new website HTML type version 5 not the older versions which makes the website behave normally.\
Then we have the HTML Elements.\
head body html this are the the html elements. if you keep in the brackets then those are called the html tags.\

<head></head> these are the html tags.\
So the chronological order is <!DOCTYPE html><html><head></head><body></body></html>
Here the content what is written should be written inside html tag.\
There are various types of headings that can be written in an HTML page chronoloogical order is from h1 to h6. Its the decreasing sizes of the headings.\
H1 indicates there is only one main heading for a page. 
Then decreasing sizes according to the needs. Better to stop after h3 because it looks very small on a web page\
Then the next most important part of the HTML content is p paragraphs. It is the <p>Content</p> Inside the tags content is written.\
Then we have List items as well.\
Usually The list items are like two types either ordered list or unordered list. Depending on that we can write it and as the name suggests.
<ol><li></li></ol>
<ul><li></li></ul>
As shown above we write whether it is an ordered list or an unoredered list tags and then each item should be written in a list element.\
Now there are these elemnts when you write a paragraph or the content we have <strong> html element which makes the content bold.\
We have em as well this makes the content in italic\
Now if in a statement as content we need to add any link to that particular word or statement we can add by adding a tag <a></a>\ This a tag alway sasks for and href means hypertextreference it's nothing but the the address where the link has to connect.
We have something called span tag as well.
But the span tag is for the applying styles inside the paragraph tag.
To add the styles we can add inline styles but it is better to add as a separate file in the extension of css.
Then we can add that stykes to the main html file by adding to the tag <head></head>
<link rel="stylesheet" href="source">.\
linking the css file to the html file.\
<header>	For introductory content, logos, and main navigation.\
<main>	Once per page, wrapping the core content that changes from page to page.\
<footer>	At the bottom of the page or section for copyright, contact links, and privacy policies.
These above things are there because the screen reeaders like the ones used by people who are visually impaired or they need assistance of taking some screen reader for that reader to understand we have to follow the the order in order to get assisted by the readers.\
Even when the same way there is image html element <img src="" alt=""> here the src is the path where the image is present and the alt is the alternate text whenever the image is not dispalyed the alt text is displayed there or when the screen readers are in use then the alt text is read out.\
SO we have various properties\
text-align thsi we can just say it centre left right anything 
Then we have font family usually what font to be applied to the content and its better to write atleast 3 font families so even one is not availble fo rthe user in their own browser the next one applies. \
Line-height is nothing bu tthe space between the lines and we can do space between the paragraphs as well\
Dev tools we know if we keep inspect the dev tools open and we can know a particular website how it has the properties and what code styling they used exactly with the colour hex codes as well.\
Padding is nothing but the content how much it has to be inside the space of the box.
Borders are the property that can give the design to the border.
Margin is the distance between the paragraphs.
classes and ID these are nothing if we want to add styling to a particular object. Then we give it a class name rather than just applying the property to all the paragraphs all the headings. beacuse to apply a css property we give by p{ }or h1{} which gets all the items which are written. rather than in the html document when we write code for example. 
divs we know like the common box fo rthe content 
ID should be only one for the page.
and id can be recalled in the styles file by #
Then we have other properties as well mainly the column style 
grid template column and we can just google and get to know about this. Then there is about the properties that should be active or hover when the points on a specific link or a word we can do that as well. Rest everything is properties and how we handle it and even the background images as well.
Then the main part when the window is resized we can write a media query 
@media(condition){attribute}
condition is when should the mdeia query start applying 
like width is this much or more than this less than this 
attribute columns should become as one or three anything
  <form action="">
        <input type="text" name="fname" id="customer" />
        <label for="customer">Your name</label>
      </form>
User input styling for forms.
