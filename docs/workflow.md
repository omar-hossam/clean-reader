# Workflow

This file contains the blueprint of the entire workflow used to develop the extension v1.0

## How does the extension work?

1. user goes to a webpage in a url
2. user **opens the popup** via the puzzle icon or right click in the webpage and open the extension from there 
  - selects fonts (header, content, links, buttons, font size)
  - color theme (light, dark, sepia)
3. all preferences user selected are saved auto in *storage*
4. DOM auto updates corresponding to user preferences + webpage is in one grid view style 
5. user opens the webpage later --> load stored preferences

## Style Blueprint Guides

in this file we are going to add **style blueprints** before developing each part, we are using specific format to make it easy for us to implement the style, just a quick guide on how it looks like:

- ~GitHub~ = GitHub icon
- <red, green, blue> = dropdown with values: red or green or blue
- (read more) = link 
- {Click Me!} = that's a button

## POPUP

files are in `popup/` folder:

1. index.html
2. script.js 
3. style.css 

### Style Blueprint

Clean Reader      ~GitHub~

Color Theme       <sepia, light, dark>

High Contrast     <yes, no>

Fonts

Header            <...>
Content           <...>
Links             <...>
Button            <...>

Page Size         <..., 0.8, default, 1.2,...> (how it works)

                  {Reset Page}    
