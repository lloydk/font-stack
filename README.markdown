## Font-stack

A Compass plugin that provides a library of CSS font stacks as Sass variables. 

## Installation

Install the plugin:
    sudo gem install font-stack

To add font-stack to an existing compass project:

    # Add the following lines to your compass configuration file:
    require 'font-stack'

## Example Usage

Import the font stack scss file

  @import "font-stack"

  body { font-family: $tahoma-font-stack; }
  h1 { font-family: $palatino-font-stack; }
  code { font-family: $monospace-font-stack; }
  .signature { font-family: $cursive-font-stack; }
 
    

## Credits

Serif and sans-serif font stacks from:

A Revised Font Stack
http://www.awayback.com/revised-font-stack


Monospace font stack from: 
  
8 Definitive Web Font Stacks
http://articles.sitepoint.com/article/eight-definitive-font-stacks


Cursive font stack from:
  
Build better CSS font stacks
  Cursive  font stack featuring Bradley Hand ITC
http://www.codestyle.org/css/font-family/BuildBetterCSSFontStacks.shtml



    