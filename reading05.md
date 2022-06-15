# Introduction to CSS

While HTML is the primary way to structure your website and is where the foundation of your website is, CSS provides the bells and whistles that make the website look good. CSS stands for Cascading Style Sheets and per its name, adds style and sophistication to the relatively lackluster HTML. CSS can change the colors of your background, add images and move them, as well as all types of formatting for a website. 

## How to use CSS

To implement CSS for a website, you have to first link it up to your HTML page. To do this, simply first create a file first that ends with a .css for its name, let's say I name mine mystyle.css. Following that, simply write `<link rel="stylesheet" href="mystyle.css">` As we can see, I put my css file name into the hyper reference, meaning that my HTML file will go to my css file to see what to do when it reads that element.

## Basic CSS Functions

Once we have linked our HTML to our CSS, we can finally begin work on our actual CSS. The format of our code in CSS differs somewhat from what we would write in HTML. If we wanted to change how our body looks, then this is what it would look like in CSS.

`body {
  background-color: lightblue;
}`

As we can see, we wrote body in front of the curly brackets which delineates the body is what we want to change. The content inside the curly brackets indicate that we wish to change the background color to lightblue. And we closed the CSS element with another curly bracket.