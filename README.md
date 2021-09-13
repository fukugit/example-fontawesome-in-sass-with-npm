# example-fontawesome-in-sass-with-npm
This project explains that the way of usage of FontAwesome in Sass with npm without Webpack.  
If you want to know that with Webpack, you can see [the another project](https://github.com/fukugit/example-fontawesome-in-sass-with-webpack).
<br/>

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
## Table of contents

- [Demo](#demo)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

<br/>


## Getting Started
It is necessary to install ```npm``` before executing the below commands.  
<br/>

```
npm insatall
npm run build
sass --watch style.scss style.css
```

<br/>

Then, open the ```./index.html``` with Browser.  
<br/>

## Demo
You can see the webpage in [here](https://fukugit.github.io/example-fontawesome-in-sass-with-npm/) that uses FontAwesome, which is made by sass with npm.  
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
Creating this project ,I was basically following [this document in official site.](https://fontawesome.com/v5.0/how-to-use/on-the-web/using-with/sass).  

<br/>



