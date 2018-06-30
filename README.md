# Project 0

Web Programming with Python and JavaScript

> Your website must contain at least four different .html pages, and it should be possible to get from any page on your website to any other page by following one or more hyperlinks.

For this project, I borrowed content from my church's website: [seacoastredondo.com](http://seacoastredondo.com).
* index.html includes the descriptions of the worship services.
* ministries.html includes descriptions of the ministries.
* groups.html includes descriptions of the life groups.
* pastors.html includes descriptions of the pastors.

Each page can be accessed from a navigation bar near the top.


>Your website must include at least one list (ordered or unordered), at least one table, and at least one image.

groups.html includes an unordered list of question in the first group. pastors.html lays out the descriptions using a table. All pages include a SeaCoast Church logo at the top.


>Your website must have at least one stylesheet file. Your stylesheet(s) must use at least five different CSS properties, and at least five different types of CSS selectors. You must use the #id selector at least once, and the .class selector at least once.

style.scss includes properties for display, margin, width, font, and color; and selectors for the logo, navigation, footer, headings, and specific people.

>Your stylesheet(s) must include at least one mobile-responsive @media query, such that something about the styling changes for smaller screens.

style.scss includes a @media query that changes the size of the logo from fixed to dynamic if the viewport is 700px or less.

>You must use Bootstrap 4 on your website, taking advantage of at least one Bootstrap component, and using at least two Bootstrap columns for layout purposes using Bootstrap’s grid model.

All pages use a Bootstrap navigation bar, and index.html uses Bootstrap’s grid model to layout descriptions of the worship services.

>Your stylesheets must use at least one SCSS variable, at least one example of SCSS nesting, and at least one use of SCSS inheritance.

style.scss uses a variable for the maximum logo width, nesting for the text style of headers, and inheritance for the text style of the pastor descriptions.

>In README.md, include a short writeup describing your project, what’s contained in each file, and (optionally) any other additional information the staff should know about your project.

Hi.