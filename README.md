# Sass-7-1
Batch, SH and main.scss file to prepare dev environment

## What's the aim ?  
I like using Sass, but preparing development environment takes a lot of time (to me).
I had to look for the commands, and the syntax, etc.
I decided to create a .sh file (for Linux) and a .bat file (for Windows) to create the 7-1 file structure and the files inside.

## Sass ?
You can find a lot of information here : https://sass-lang.com/

To install Sass, you can begin with : 
npm install node

And then :
npm install -g sass

And to conclude :
npm init

Answer the question and it is almost done.

The nearly last step :  
Take the package.json file in this repository and replace its values by yours.  
The most important part to use Sass is :  
  "scripts": {  
    "sass": "sass --watch ./sass/main.scss ./css/style.css"  
     },  
Take care of the paths and it will be done !

The finally last step :   
In the repository, take the main.scss file. It contains the import for all other files.
