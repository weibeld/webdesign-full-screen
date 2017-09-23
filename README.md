# Full-Screen Slides

![Walkthrough](walkthrough.gif)

A simple example how to create ["full-screen slides"](https://webdesign.tutsplus.com/articles/current-web-design-trends-full-on-full-screen-home-pages--cms-25490) on a home page with HTML5 and CSS3

## Summary

Make an element as wide and high as the viewport (i.e. browser window):

~~~css
width: 100vw;
height: 100vh;
~~~

The unit `vw` stands for *viewport width*, and `vh` for *viewport height*.

***

Center an element horizontally and vertically within another element (the following is the CSS for the *containing* element):

~~~css
display: flex;
align-items: center;      /* Center vertically */
justify-content: center;  /* Center horizontally */
~~~

See alternative approaches to center elements [here](https://www.w3.org/Style/Examples/007/center.en.html).
