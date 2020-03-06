# Advanced CSS tutorial

## [Natours](https://ddeveloper72.github.io/Natours/)

  _from a Udemy tutorial presented by [Jonas Schmedtmann](https://github.com/jonasschmedtmann)_

## Preface

In this tutorial, I'm looking for ways in which to improve and expand on my experience in front-end development.  I love the platforms that I've been working on before, namely Django and Angular along with all the backend services and deployment processes and I believe that the look and feel of these applications can be vastly improved by the better use of advanced CSS.

## Getting started

There are many certainties in web development and one of them that I'm very certain of is that it is near impossible to remember everything.  When I first learned about using and implementing CSS I worked with the bootstrap frame-work and so relied on the built in framework styles.  I love it and still do.  This time around, I've deep-dived into the use of Sass and to work trough setting up grass-roots CSS styles, using only the standards pre-defined by the html document object model (DOM).

I felt that The author of this tutorial is excellent at identifying with his target audience and been excellent at explaining and demonstrating the use of pure CSS to crate animation of page elements by the cleaver use of transitions and 3-dimensional perspective through the cleaver use of box-shadows, transform-translate and scales.

In order to teach CSS the desktop first approach  was used.  So anyone following the tutorial who has prior development experience, may think that this is all wrong- which it may be, but there is a process, a flow on how to get from A to B.  I was that person- I didn't ready the lesson pan!  I followed the process and now that the application is build, I'm presented with looking at setting up media queries that support a desktop first approach- the opposite of what I was taught but refreshing and grate to learning development from a different perspective.

## Planning, planning, planning

Wire frames are key.  Just something simple.  The tutorial referenced a finished application as the basis of using a wire frame.  Then each section was broken done in to smaller items that could be discussed and though about.  The analysis of each item lets one then build a development framework that the project can be build around.

In this case Advanced Sass require that one starts noting the basics of the application.  Here's a list, that is not limited to what I've noted:

A page is going to have...
colour, fonts, font-sizes, margins, padding, buttons, images, rounded corners on the images, animations, fixed position elements so on and so fourth.

But wait, its going to have a header, footer, a grid, perhaps forms cards, buttons...

It's going to be a mess if we don't plan how to manage all these bits.  Thankfully Sass helps one to create order out of all of these different bits and bobs.

See all these things listed above and then group them in categories.
Eg you think of a category called variables - colours, you may lots of them, they are all variables. You have lots of different margin sizes, padding etc. Well these can all be given a class which can be grouped as utility classes.
And so can anything to do with the use of text, call it typography - which is for anything relating to the layout of text, so styling headings, body-text and all that.
So now the information about the CSS variables, use of certain styles in a certain way as well as a bit of housekeeping by creating utility/helper classes can help to structure and build a framework for the bits and bobs above.

Here's a sample sass folder

