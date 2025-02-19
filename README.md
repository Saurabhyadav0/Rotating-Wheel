# Rotating-Wheel-Project

## index.html

The `index.html` file contains the HTML and CSS code for the rotating wheel effect.

### HTML Structure

The HTML file contains a `div` with the class `wheel-container` that centers the wheel both vertically and horizontally. Inside it, there is another `div` with the class `wheel` that represents the wheel.

### CSS Styles

- **.wheel-container**: A flex container that centers its content both horizontally and vertically. The height is set to 100% of the viewport height (`100vh`).
- **.wheel**: The wheel itself, styled as a circle with a diameter of 200px. The border creates a wheel with four different colors (red, yellow, green, blue) on each side. The `border-radius: 50%` makes the div a circle. The `transition` property ensures a smooth transition when the `transform` property changes.
- **.wheel:hover**: When the wheel is hovered, it starts an infinite spin animation.
- **.wheel:not(:hover)**: When the wheel is not hovered, it starts the `spin-back` animation.
- **@keyframes spin**: Defines the `spin` animation that rotates the wheel 360 degrees.
- **@keyframes spin-back**: Defines the `spin-back` animation that rotates the wheel back to 0 degrees.

## How to Run

1. Open the `index.html` file in a web browser.
2. Hover over the wheel to see it rotate.
3. Remove the cursor to see the wheel smoothly return to its original position.

## License

This project is licensed under the MIT License.
