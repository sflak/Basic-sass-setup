# Basic-sass-setup
Website starter code set up with sass file structure and 4-column float grid layout. 

## What is sass?
Sass is a css preprocessor. Every peice of sass code you write will get compiled to css code. The reason people use sass is because it gives you access to things like variables and nested styles. There are tons of resources for learning sass online. For a quick overview, visit https://www.creativebloq.com/web-design/what-is-sass-111517618 

## Don't want to use sass?
No problem! The base css styles and the grid styles have already been written to the styles.css file. Simply delete the Sass folder and use Css how you would normally. 

## Live Serving
To start a live server install live-server globally
```
npm install -g live-server
```
To start serving your project, simply navigate into your project folder and run this command.
```
live-server
```
You project will then start running on a local host, and any changes you make will automatically cause your page to reload and show the new changes. 

## Getting Started using Sass
Make sure you have Node installed. After cloning the repository, run this command to download the dependencies. (In this case, just sass). 

```
npm install
```


## Compiling Sass
In the terminal, run this command. This will watch for file changes in your sass file, and write them to the styles.css file. It can be finicky though. So if you write a style that is not showing up, 50% of the time its because you need to restart this command. Other than that, it's usually just a syntax error. This command will also tell you if there are errors in your css code. 
```
npm run compile:sass
```






