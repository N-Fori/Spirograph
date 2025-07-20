# Turtle Spirograph

This is a Python project that draws colorful spirographs using the Turtle graphics module.

## Features

- Uses the `turtle` module to create graphics.
- Draws a spirograph with customizable gap size between circles.
- Each circle is drawn in a random RGB color.
- Runs quickly with the turtle speed set to "fastest".
- Closes the window when clicked.

## How to Run

1. Make sure you have Python installed (version 3.x recommended).
2. Save the script to a `.py` file, for example `spirograph.py`.
3. Run the script in your terminal or IDE:

   ```bash
   python spirograph.py
   
A window will appear showing the colorful spirograph.

Click anywhere on the window to close it.

Code Overview
random_color() generates a random RGB color tuple.

draw_spirograph(size_of_gap) draws circles around a center, rotating by the specified gap angle.

Turtle’s color and heading are updated on each iteration to create the spirograph effect.

Dependencies
Python standard library (turtle and random modules).

Author
Nandor Forgo
📧 nfori.coding@gmail.com
