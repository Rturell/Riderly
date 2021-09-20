# Riderly

**HTML**

The site is structured with HTML5 and the Bootstrap framework, which facilitates the development of responsive, mobile-first sites. 


**SASS/SCSS**

Also, SASS preprocessor was used.
I structured the site in several .scss files. Maybe it is unnecessary in a small project like this, but SASS allows us to make a project scalable and will be beneficial when stylesheets get larger, more complex, and harder to maintain.

Different sections of the project have their own .scss file. Then everything is compiled into a single css file, so it can be read by any browser. 

Fonts sizes, weights and all the colors of the site were set up in sass variables. If any change is needed it can be done in a simple and fast way only modifying the variable value.  


**BEM**

I used BEM (Block. Element. Modifier) in a non-strict way, as a class naming methodology for this project. BEM does a great job structuring css styles and enables you to create reusable components, something relevant in large or scalable projects.
BEM is also a great ally to work hand in hand with SASS. With BEM and SASS we can encapsulate our component into a single block, and having the classes in one block makes it easy to identify, edit and move it around.


**Some Improvements**

I decided to optimize resources and upload the Riderly logo in svg format, avoiding using a special font only for the logo.

I added a hover effect in the table rows to make the user interaction more dynamic and easier to read, especially on mobile devices that with one touch de row is highlighted.

Also, I implemented a shadow hover effect in the settings cards. A simple detail to make the site feel a little bit more modern.
