first, open the project folder in vs code and go to vs code terminal and also 
install node js on pc properly.

1) check the current node version. 
command: node -v
2) then type npm init to set mpn
command: npm init
3) then type project mane
4)enter on version
5) enter empty till author, and type author name as your name as alif
6) again enter on license 
7) then ok 
8) then we need to install sass for that type of this 
command: npm install node-sass --save-dev
9) delete this piece of code from the package.Jason -  "test": "echo \"Error: no test specified\" && exit 1"
10) and write this - "compile:sass": "node-sass sass/main.scss css/style.css"
10.1) before doing the step make sure that you have CSSflder and a style.css file on it.
      and also have a sass folder with the main.scss file on it.
11) type npm run compile:sass -green text will show if it works to compile sass to CSS
command: npm run compile:sass
12)now we need to setup auto-compile for that 
13) add -w in the last part of the script 
14) the script will look like this

"scripts": {
    "compile:sass": "node-sass sass/main.scss css/style.css -w"
  },

  15) then compile sass for the last time with the command
  command:npm run compile:sass

  Yeah all done properly.
  Good to go
  


another way.
      
1) if you include package.json then type this command
command: npm-install

good to go
