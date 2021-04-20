## Advanced CSS and practical tricks

### Why CSS?
Well, it all started with TailwindCSS and Vue. Although they are very good frameworks and libraries, I felt they tend to distance us from the basic concepts of CSS and javascript.
In addition, the more you start develop real applications and go through the whole process of creating and maintaining code, practices such as those embedded in Design Patterns, SOLID principles and CLEAN code becomes very important. Therefore, separation of concerns, makes it easy to expand your code. In this sense, decoupling CSS from HTML, becomes very important. The utility-first tailwindcss seems to be useful for small, quick, apps, but it rapidly becomes cumbersome and impractical to read the code in large chunks of code.
In addition, CSS and javascript has evolved during the years, and knowing how to organize them, provides you freedom from frameworks, which is also a SOLID principle: your code should be framework agnostic.


### Notes

1. Absolute vs relative position. Normally define parent widget as relative and child widgets as absolute.
2. transform: translate, position it relative to widget itself
3. @keyframe: provides frames per time stamp, from 0 to 1. Here you can define many types of animations.
4. display: block (display elements one after the other, like paragraphs)or inline-block (display elements in the inline direction, like words are displayed in a sentence).
5. sudo elements

- credits to [Advanced CSS and Sass: Flexbox, Grid, Animations and More!](https://www.udemy.com/course/advanced-css-and-sass/), by Jonas Schmedtmann.