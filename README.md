# spinner-app

A simple web-based prize wheel application implemented in HTML, CSS, and JavaScript.

## Features

1. Enter any number of labels via the "Enter Label" input field.
2. Click the "Add Label" button or press Enter to add the label to the wheel.
3. To add labels, enter a label in the 'Enter Label' input field, and click the 'Add Label' button or press Enter. The added labels will be displayed below the input field. To remove labels, simply click on the '❌' icon next to the respective label in the displayed list. The label list is automatically updated on the wheel.
4. Spin the wheel manually for true randomness, or with a button press for pseudo-randomness, using averages against a custom crypto-based arithmetic algorithm.

## Library

The Wheel of Fortune functionality is powered by the [spin-wheel](https://github.com/CrazyTim/spin-wheel) library.

## License

This Wheel of Fortune application is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

## Script Loading

The script is loaded using an ES6 module import statement:

```html
<script type="module">
  import { Wheel } from 'https://cdn.jsdelivr.net/npm/spin-wheel@4.3.1/dist/spin-wheel-esm.js';
  // ...
</script>
