# iOS Pokemon Go Image Reader
Read values via OCR from screenshots of Pokemon Go


Run `pod install`

It's entirely Swift 3 compatible code. 

The idea is to take a in-App screen shot of a caught Pokemon in the PokemonGo App. Then open this App, select the screen shot and it will parse the image with OCR technology to read the values of this Pokemon. Then calculate the reccomendation if or if/not to power up this Pokemon. See https://docs.google.com/spreadsheets/d/1wbtIc33K45iU1ScUnkB0PlslJ-eLaJlSZY47sPME2Uk/copy

An advanced version would be to calculate the reccomendation in background every time a screen shot is added and the display a notification on screen while still in the Pokemon Go App. (and then delete the screen shot)
