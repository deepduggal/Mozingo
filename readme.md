# Mozingo - Modern Colors for CSS Preprocessors

- Tiny file size. 
- In most cases, this file will NEVER be served to your users. No http requests. No load time. No problem. 
- Works with SASS, SCSS, and LESS. It's your choice. 
- Save time. Make web apps that are beautiful right out of the box. 
- Perfect for mockups and live production websites. 

## Installation

Mozingo is super easy to install. 

### Option 1: The @import directive. 

1. Download Mozingo into your project folder: mozingo.sass, mozingo.scss, or mozingo.less
2. Include an @import statement at the top of your code. 
    
    @import "code/mozingo";
    
3. Done. Get back to creating awesome things!

### Option 2: Good old fashioned Copy & Paste
1. Copy the code from mozingo.sass, mozingo.scss, or mozingo.less
2. Paste it into your code. 
3. Done. Have a cookie and give yourself a pat on the back. 


## Usage

**Pick a color** (see color list below). **Use it as a** SASS/SCSS, or LESS **variable**. Variable names will always be in camelCase.

### SASS

    color: $blue;
    
### SCSS
    
    color: $blue
    
### LESS
    
    color: @blue;
 

Use a darker or lighter color by adding a valid keyword (**Dark, Darker, Light, or Lighter**) to the end of the variable name:
    
    color: $red;
    
    color: $redLight; // A lighter red.
    
    color: $redLighter; // An even lighter red!
    
    color: $redDark; // A darker red.
    
    color: $redDarker; // An even darker red!
    

**That's it!**


## Color List - A list of all of the colors included in Mozingo.
    
### Normal Colors

- red
- orange
- yellow
- green
- blue (light and dark currently unavailable)
- purple
- pink (light and dark currently unavailable)
- gray
- white (Dark and Darker are available!)
- black (Light and Lighter are available!)

### Fancy Colors (light and dark currently unavailable)

- aqua
- navy
- teal
- olive
- lime
- fuchsia
- maroon
- sepia
