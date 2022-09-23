## NATOURS PROJECT

---


### [Live Demo](https://sadiquex.github.io/Natours/)

#### Things I've learnt

- How to use clip path to draw shapes
- -webkit-background-clip: text is used to clip a text to an element. eg: a background image or gradient. set text color to transparent
- use the 'not' selector to remove elements you don't want the style to apply to.
- [Site for videos](https://coverr.co/)
- In a background video, add 'autoplay, mute and loop' to the parent element, to make video play accordingly
- "object-fit:cover" fills the element while still having that aspect ratio

#### How to compile sass code

- Create a package.json file with **_npm init_**
- Install node-sass using **_npm install node-sass --save-dev_**
  **Compiling**
- Create a script in package.json in the scripts column
  **_"compile:sass": "node-sass sass/main.scss css/style.css -w"_**
- Run the script(with its name) and leave that terminal open
  **_npm run compile:sass_**
