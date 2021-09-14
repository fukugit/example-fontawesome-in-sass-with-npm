# example-fontawesome-in-sass-with-npm
This project explains that the way of the usage of FontAwesome in Sass with npm without Webpack.  
If you want to know that the project consists of Webpack, you can see [the another project](https://github.com/fukugit/example-fontawesome-in-sass-with-webpack).  
<br/>

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
## Table of contents

- [Getting Started](#getting-started)
- [Demo](#demo)
- [Project Structure](#project-structure)
- [Dependency](#dependency)
- [Acknowledgement](#acknowledgement)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

<br/>


## Getting Started
```
npm insatall
npm run build
sass --watch style.scss style.css

## Then, open the ```./index.html``` with Browser.
```

<br/>

## Demo
You can see the webpage [here](https://fukugit.github.io/example-fontawesome-in-sass-with-npm/) that uses FontAwesome, which consists of sass and npm.  
<br/>


## Project Structure
| File                       | Explanation                                               |
| -------------------------- | --------------------------------------------------------- |
| [style.scss](./style.scss) | The main page to get know how to set FontAwesome in sass. |
| [style.css](./style.css)   | The file generaed by sass.                                |
| [index.html](./index.html) | HTML file to use the style.css file.                      |

<br/>

## Dependency 

```
npm install --save-dev @fortawesome/fontawesome-free
```
<br/>

## Acknowledgement
To create this project, I read through [the document on the official site.](https://fontawesome.com/v5.0/how-to-use/on-the-web/using-with/sass).  

<br/>



