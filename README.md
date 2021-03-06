# Code Jam IV: This app hates you!

The theme for this code jam will be **This app hates you!**. You will be creating an application using a GUI library of your choice in Python. The application must serve a real purpose, but must also fit the theme.

You can use any GUI library that you wish to use, but you have to make _a desktop app_. For example, you may use frameworks like PySide, PyQt, tkinter, or wxPython. You can even use stuff like Kivy or PyGame, although we do not recommend that you do. You may not, however, use webframeworks like Django or Flask, and you may not use anything that turns HTML and CSS into a desktop app that runs as a browser. 

Here are a couple of examples of what we mean by an application that "serves a real purpose but also fits the theme":
* A calculator app that calculates the right answers, but represents the answer in a way that's completely impractical.
* An image resizer where you have to specify which part of the image to resize, specify how much force to apply to the resize operation in newtons, and then manually resize the image by turning a crank.
* An alarm clock app that plays a very loud sound effect every 5 minutes reminding you that your alarm will ring in 6 hours. The closer it gets to the 6 hour mark, the lower the volume of the sound effect. When the time is up, the sound effect is virtually inaudible.

Remember that teamwork is not optional for our code jams - You must find a way to work together. For this jam, we've assigned a leader for each team based on their responses to the application form. Remember to listen to your leader, and communicate with the rest of your team! 

**Remember to provide instructions on how to set up and run your app at the bottom of this README**.

# Tips

* Please lint your code, and listen to the linter. We recommend **flake8**, and you can use `pipenv run lint` to run it. We will be evaluating your style, and unlinted code will lead to point deductions.
* Remember to work closely with the rest of your team. We will deduct points for poor teamwork.
* Don't overcomplicate this. It's better to write a relatively simple app that is 100% feature complete than failing to finish a more ambitious project.
* For information on how the Code Jam will be judged, please see [this document](https://wiki.pythondiscord.com/wiki/jams/judging).

# Setting Up

You should be using [Pipenv](https://pipenv.readthedocs.io/en/latest/). Take a look 
[at the documentation](https://pipenv.readthedocs.io/en/latest/) if you've never used it before. In short:

* Setting up for development: `pipenv install --dev`
* Running the application (assuming you use our project layout): `pipenv run start`

# Project Information

This is the Code Jam 4 entry for team Cool Crocodiles.

## Description

Crocpad++ is a free replacement for Notepad.

## Setup & Installation

Use `pipenv install` from the root directory.

## How do I use this thing?

Use `pipenv run start` to run Crocpad++.

## Project Structure
`project/`  
Contains the Crocpad++ application.

`project/ui`  
Contains `.ui` files created for Qt and the Python modules generated from those UI files.

`project/sounds`  
Contains sound resources for a multimedia, user-friendly experience.

## Known bugs
- When running under Linux, occasionally the following message might appear:  
    >```qt.qpa.xcb: QXcbConnection: XCB error: 3 (BadWindow), sequence: 5441, resource id: 27411671, major code: 40 (TranslateCoords), minor code: 0```

## Attributions
`wrong.wav` is from https://freesound.org/people/sharesynth/sounds/341256/

## Spoilers
There are many subtle annoyances in Crocpad++. Please check `spoilers.txt` for a complete list.
