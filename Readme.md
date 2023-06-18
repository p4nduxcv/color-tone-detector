# Color Tone Detector

This npm package is used to identify whether a given color is light or dark. It provides a function called `colorToneDetector(color)` that takes a color as input and returns either "light" or "dark" based on the intensity of the color.

## Installation

You can install the package using npm: npm install color-tone-detector

## Usage

To use the `colorToneDetector` function, first import it into your code:

```javascript
const colorToneDetector = require("color-tone-detector");
```

Then, you can call the function with a color as input:

```javascript
const color = "#FF0000"; // Example color

const tone = colorToneDetector(color);
console.log(tone); // Output: "dark"
```

The colorToneDetector function supports both RGB and HEX color formats. It automatically detects the format and converts it to RGB if necessary.

## Examples

Here are a few examples of using the colorToneDetector function:

```javascript
const color1 = "rgb(255, 255, 255)";
const tone1 = colorToneDetector(color1);
console.log(tone1); // Output: "light"

const color2 = "#000000";
const tone2 = colorToneDetector(color2);
console.log(tone2); // Output: "dark"
```

## License

This project is licensed under the MIT License. See the LICENSE file for details.

### Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please create a new issue or submit a pull request.

### Feedback

If you have any feedback or questions about this package, feel free to reach out to the author or open a new issue.

Happy color tone detecting!
