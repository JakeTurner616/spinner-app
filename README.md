# spinner-app

A simple web-based prize wheel application implemented in HTML, CSS, and JavaScript.

## Features

1. Enter any number of labels via the "Enter Label" input field.
2. Click the "Add Label" button or press Enter to add the label to the wheel.
3. Added labels will be displayed below the input field. To remove labels, simply click on the '❌' icon next to the respective label in the displayed list. The label list is automatically updated on the wheel.
4. Spin the wheel manually for true randomness, or with a button press for pseudo-randomness, using averages against a custom crypto-based arithmetic algorithm.

## Library

spinner-app's main functionalites are powered by the [spin-wheel](https://github.com/CrazyTim/spin-wheel) library licensed under [MIT](https://github.com/CrazyTim/spin-wheel/blob/main/LICENSE.md) .

## License

spinner-app is licensed under the GNU General Public License v3.0 - see the [LICENSE](https://github.com/JakeTurner616/spinner-app/blob/main/LICENSE) file for details.

## Script import info

The main library script is loaded using the followng ES6 module import using jsdelivr:

```html
<script type="module">
  import { Wheel } from 'https://cdn.jsdelivr.net/npm/spin-wheel@4.3.1/dist/spin-wheel-esm.js';
  // ...
</script>
