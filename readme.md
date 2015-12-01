# :space_invader: nes-palette

A scss palette based on NES palette.

## The palette

Nes-palette includes 56 colors to represent the original nes-palette.

![Nes palette representation](http://dev.bowdenweb.com/nes/a/i/nes-color-palette.png) 

There are 14 different hues within 4 different shades each one. 
The hue names are:

````
'grey', 'blue', 'dark-blue', 'purple', 'dark-purple', 'red', 'orange', 'dark-orange', 'brown', 
'light-green', 'green', 'dark-green', 'blue-grey', 'dark-grey'.
````

Any hue has 4 different values representing different luminosities:

````
'00', '10', '20', '30' 
````

````00```` represents the darkest value for a hue and ````30```` represents the lightest value.


## Install nes-palette as bower dependency

````bower install --save-dev nes-palette````

## Usage

Use the nes-palette function combining ````color-name```` and ````color-value```` to print the color you choose.

````scss
.css-selector {
  background-color: nes-palette('grey', '30');
  color: nes-palette('blue-grey', '20');
}
````


## Roadmap
- [x] Make it bower friendly
- [ ] Create a demo page
- [ ] Write multilingual article about css palettes
