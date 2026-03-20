# Workflow

This file contains the blueprint of the entire workflow used to develop the extension v1.0

## How the extension works?

1. user goes to a webpage in a url
2. user **opens the popup** via the puzzle icon or right click in the webpage and open the extension from there 
  - selects fonts (header, content, links, buttons, font size)
  - color theme (light, dark, sepia)
3. all preferences user selected are saved auto in *storage*
4. DOM auto updates corresponding to user preferences + webpage is in one grid view style 
5. user opens the webpage later --> load stored preferences
