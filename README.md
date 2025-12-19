# Segment Intersection Animation

This project is an interactive animation that visualizes line segment intersection in real-time. The animation shows two line segments where one rotates around the mouse cursor, and dynamically calculates and displays their intersection point when the segments cross.

## Overview

The animation features two line segments:
- Segment AB: A rotating segment that follows the mouse cursor and spins continuously
- Segment CD: A static segment defined by points C and D

Key features:
- **Mouse Interaction**: Segment AB rotates around the mouse position as you move the cursor
- **Dynamic Rotation**: Segment AB continuously rotates at a constant angular velocity
- **Real-time Intersection Detection**: When the two segments intersect, point I is displayed at the exact intersection location
- **Parametric Calculation**: Uses parametric equations to accurately determine if and where the segments intersect

The intersection algorithm checks both parameters `t` and `u` to ensure the intersection point lies on both line segments (not just on their infinite extensions).

## Getting Started

To run this project locally:

1. Clone this repository or download the HTML file.
2. Open the `index.html` file in your web browser.
3. Move your mouse around the canvas to see segment AB follow and rotate.
4. Watch as point I appears when the segments intersect.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

