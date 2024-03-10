---
name: Jump & Dash
tools: [Unity, C#, Prototype, Mobile, Hyper-casual]
image: /assets/jumpndashsplash.png
description: Hyper-casual prototype with editor tooling and custom physics
---

# Jump & Dash

The goal for this prototype was to create a runner with the feeling of Hollow Knight's dash mechanic where we overcome obstacles / collect collectables by mainly jumping and dashing.

I coded the entire prototype, including SDK integrations such as Facebook SDK and Google Analytics. The running / dashing physics were implemented by me as I opted not to use Unity's own physics engine for this project. 
I designed tools for the designers that allowed them to design the levels themselves by using:

- A path editor
- Volumes that modify the characters behaviour such as extra long dashes

See the showcase video below.

{% include elements/video.html id="AdVFGrtBHds" %}

**Highlighted skills:**

- **Custom Physics:** The physics for the character was handled manually
- **Editor Tool Development:** A custom path editor which allowed game designers to define the path that would be followed by the character. Special bounding boxes that modify the characters physics.
- **Game Logic:** Fully functional, looping game logic.

This project was developed during my time at Hero Games.
Due to being a prototype, there might be some bugs or unfixed issues in the video.