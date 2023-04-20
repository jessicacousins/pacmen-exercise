# PacMen Exercise

## Description

This is a web page that displays a PacMan game where the user can add PacMen to the screen and start the game. The HTML code contains a title, two buttons for adding PacMen and starting the game, and a JavaScript file named "pacmen.js" that controls the game's behavior. The JavaScript code defines several variables and functions that create and move the PacMen across the screen. The makePac() function creates a PacMan at a random position on the screen with a random velocity, which is added to the pacMen array. The update() function updates the position of each PacMan every 20 milliseconds, checks for collisions with the screen boundaries, and changes the PacMan's direction if it hits the edge of the screen. The checkCollisions() function detects if a PacMan has collided with the screen boundaries and changes its direction accordingly. The PacMen are displayed as images on the screen with the help of HTML elements that are created dynamically in the makePac() function.

The CSS code defines the style for the buttons and the PacMan game's background and title. The buttons are stylized with a blue background color, a white font color, and rounded borders. The title is stylized with a yellow color and a pixelated font named "Press Start 2P". The background color of the game is black.

## Roadmap of future improvements

Creating a PacMan themed background instead of all black. Would like to add PacMen images facing different directions. Plan on adding an “end game” button to stop the animations and clear them from the screen.

## License Info

[MIT](https://choosealicense.com/licenses/mit/)

_Copyright (c) 2023 Jessica Cousins_

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
