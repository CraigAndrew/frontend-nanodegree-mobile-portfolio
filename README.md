# frontend-nanodegree-mobile-portfolio
Udacity Front-end Nanodegree Program

[View Project](https://github.com/CraigAndrew/frontend-nanodegree-mobile-portfolio/views/pizza.html)

## Steps Taken to Optimize this portfolio website:

1. Clone the [orginal repo.](https://github.com/CraigAndrew/frontend-nanodegree-mobile-portfolio)
2. Initialize the repo for node.js and the install gulp. This assumes npm and gulp are already installed globally.

  ```bash
  sudo npm init
  sudo npm install --save-dev gulp
  ```
3. Setup minification for images, css, javascript, and html files using the approiate gulp plugins.

4. Changes to the index html
  - a. move the google analytics script to just just before end of body tag
  - b. inline the style.css file
  - c. add media tag to print.css files
  - d. added async tag to analytics.js
  - e. optimize pizzera.jpg.  In the design the image never seems to get bigger
  than 360x270, so resized to that.
  - f. google fonts disabled, to get 90 PSI we need to use user's fonts


4. Optimze main.js file.
  - three changes made to the loop that moves the pizzas, comments in the main.js file.
  
## To Run this project

1. [Link to minified final work](https://github.com/CraigAndrew/frontend-nanodegree-mobile-portfolio/build/)
2. [Link to dev version](https://github.com/CraigAndrew/frontend-nanodegree-mobile-portfolio/)

## To Build this project
1. You will need to have node, npm, and gulp installed globally.
2. You will need to install all the project dependancies:
```bash
npm install
````
3. Now you can build the project using the following commands:
```bash
gulp clean
gulp
```

The built version of the project will appear in the build sub-directory.
