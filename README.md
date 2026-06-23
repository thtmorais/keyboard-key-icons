# Keyboard Key Icons

A simple, lightweight CSS icon library for displaying keyboard keys.

## Getting Started

To use Keyboard Key Icons in your project, install the package via [npm](https://docs.npmjs.com/about-npm):

```
npm install keyboard-key-icons
```

## Basic Usage

To use an icon, add an `<i>` element with the class corresponding to the key you want to display. For example, to display the "A" key, you would use the following code:

```html
<i class="key-a"></i>
```

### Sizing

You can change the size of the icons by adding the appropriate class to the `<i>` element.

#### Relative size guide:

Example:

```html
<i class="key-a key-lg"></i>
```

Available classes: `.key-xxs`, `.key-xs`, `.key-sm`, `.key-lg`, `.key-xl`, `.key-xxl`

#### Literal size guide:

Example:

```html
<i class="key-a key-lg"></i>
```

Available classes: `.key-1x`, `.key-2x`, `.key-3x`, `.key-4x`, `.key-5x`, `.key-6x`, `.key-7x`, `.key-8x`, `.key-9x`, `.key-10x`, `.key-11x`, `.key-12x`

### Coloring

You can change the color of the icons by applying a `text-*` (Boostrap classes) class to the `<i>` element.

```html
<i class="key-c key-3x text-danger"></i>
<i class="key-c key-3x text-warning"></i>
<i class="key-c key-3x text-primary"></i>
```

Available classes: `.text-danger`, `.text-warning`, `.text-primary`, etc. (any Bootstrap text color class).

## Available Icons

### Alphabetic Keys (A-Z)

<table>
  <tr>
    <td><code>.key-a</code></td>
    <td><code>.key-b</code></td>
    <td><code>.key-c</code></td>
    <td><code>.key-d</code></td>
    <td><code>.key-e</code></td>
  </tr>
  <tr>
    <td><code>.key-f</code></td>
    <td><code>.key-g</code></td>
    <td><code>.key-h</code></td>
    <td><code>.key-i</code></td>
    <td><code>.key-j</code></td>
  </tr>
  <tr>
    <td><code>.key-k</code></td>
    <td><code>.key-l</code></td>
    <td><code>.key-m</code></td>
    <td><code>.key-n</code></td>
    <td><code>.key-o</code></td>
  </tr>
  <tr>
    <td><code>.key-p</code></td>
    <td><code>.key-q</code></td>
    <td><code>.key-r</code></td>
    <td><code>.key-s</code></td>
    <td><code>.key-t</code></td>
  </tr>
  <tr>
    <td><code>.key-u</code></td>
    <td><code>.key-v</code></td>
    <td><code>.key-w</code></td>
    <td><code>.key-x</code></td>
    <td><code>.key-y</code></td>
  </tr>
  <tr>
    <td><code>.key-z</code></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</table>

### Number Keys (0-9)

<table>
  <tr>
    <td><code>.key-0</code></td>
    <td><code>.key-1</code></td>
    <td><code>.key-2</code></td>
    <td><code>.key-3</code></td>
    <td><code>.key-4</code></td>
  </tr>
  <tr>
    <td><code>.key-5</code></td>
    <td><code>.key-6</code></td>
    <td><code>.key-7</code></td>
    <td><code>.key-8</code></td>
    <td><code>.key-9</code></td>
  </tr>
</table>

### Command Keys

<table>
  <tr>
    <td><code>.key-enter</code></td>
    <td><code>.key-alt</code></td>
    <td><code>.key-ctrl</code></td>
    <td><code>.key-fn</code></td>
    <td><code>.key-tab</code></td>
  </tr>
  <tr>
    <td><code>.key-caps-lock</code></td>
    <td><code>.key-shift</code></td>
    <td><code>.key-backspace</code></td>
    <td><code>.key-insert</code></td>
    <td><code>.key-home</code></td>
  </tr>
  <tr>
    <td><code>.key-delete</code></td>
    <td><code>.key-end</code></td>
    <td><code>.key-esc</code></td>
    <td><code>.key-command</code></td>
    <td><code>.key-option</code></td>
  </tr>
  <tr>
    <td><code>.key-num-lock</code></td>
    <td><code>.key-arrow-up</code></td>
    <td><code>.key-arrow-down</code></td>
    <td><code>.key-arrow-left</code></td>
    <td><code>.key-arrow-right</code></td>
  </tr>
  <tr>
    <td><code>.key-page-up</code></td>
    <td><code>.key-page-down</code></td>
    <td><code>.key-space</code></td>
    <td><code>.key-print-screen</code></td>
    <td><code>.key-windows</code></td>
  </tr>
</table>

### Special Keys

<table>
  <tr>
    <td><code>.key-dollar</code></td>
    <td><code>.key-plus</code></td>
    <td><code>.key-hyphen-or-minus</code></td>
    <td><code>.key-asterisk</code></td>
    <td><code>.key-slash</code></td>
  </tr>
  <tr>
    <td><code>.key-equal</code></td>
    <td><code>.key-percent</code></td>
    <td><code>.key-double-quotes</code></td>
    <td><code>.key-single-quotes</code></td>
    <td><code>.key-number-sign</code></td>
  </tr>
  <tr>
    <td><code>.key-at</code></td>
    <td><code>.key-ampersand</code></td>
    <td><code>.key-underscore</code></td>
    <td><code>.key-paren-left</code></td>
    <td><code>.key-paren-right</code></td>
  </tr>
  <tr>
    <td><code>.key-comma</code></td>
    <td><code>.key-period</code></td>
    <td><code>.key-semicolon</code></td>
    <td><code>.key-colon</code></td>
    <td><code>.key-question</code></td>
  </tr>
  <tr>
    <td><code>.key-exclamation</code></td>
    <td><code>.key-backslash</code></td>
    <td><code>.key-bar</code></td>
    <td><code>.key-brace-left</code></td>
    <td><code>.key-brace-right</code></td>
  </tr>
  <tr>
    <td><code>.key-less</code></td>
    <td><code>.key-greater</code></td>
    <td><code>.key-bracket-left</code></td>
    <td><code>.key-bracket-right</code></td>
    <td><code>.key-grave</code></td>
  </tr>
  <tr>
    <td><code>.key-circumflex</code></td>
    <td><code>.key-tilde</code></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</table>

### Function Keys

<table>
  <tr>
    <td><code>.key-f1</code></td>
    <td><code>.key-f2</code></td>
    <td><code>.key-f3</code></td>
    <td><code>.key-f4</code></td>
    <td><code>.key-f5</code></td>
  </tr>
  <tr>
    <td><code>.key-f6</code></td>
    <td><code>.key-f7</code></td>
    <td><code>.key-f8</code></td>
    <td><code>.key-f9</code></td>
    <td><code>.key-f10</code></td>
  </tr>
  <tr>
    <td><code>.key-f11</code></td>
    <td><code>.key-f12</code></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</table>

## License

This project is licensed under the **MIT License**. See the [LICENSE.md](LICENSE.md) file for details.

Copyright (c) 2024 Matheus Evangelista Morais.

### Font License

Please note that the font "212 Keyboard" by "212 Fonts" is used in this project and is subject to its own license terms. It is free for personal and small commercial use, but cannot be resold. For more details, please see the `LICENSE.md` file.
