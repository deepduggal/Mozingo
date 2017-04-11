# Mozingo - Modern default colors for CSS Preprocessors

- No dependencies
- Tiny file size. Furthermore, only the colors you use will appear in your final CSS. 
- Works with all popular preprocessors
- Create faster. Make web apps that are beautiful right out of the box. 
- Perfect for mockups and live production. 

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

1. Pick a color (see color list below). Use it as a variable like you normally would in you SASS, SCSS, or LESS. 

### SASS

    color: $blue;
    
### SCSS
    
    color: $blue
    
### LESS
    
    color: @blue;
 

2. Use a darker or lighter version of a base color by adding a one of the valid keywords (Dark, Darker, Light, or Lighter) to the variable name:

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
