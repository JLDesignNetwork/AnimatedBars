# JLDN Meters v2.0.0

![GitHub All Releases](https://img.shields.io/github/downloads/JLDesignNetwork/JLDN-Meters/total?color=brightgreen&style=plastic)

The code contained in this package is a result of searching for a way to implement a meter with a gradient background, but with a reveal based on a set inner width. The result is animated, layered HTML elements designed to mimick the html meter / progress tag.

The CSS code and HTML layout provided has been edited from its original form. Both the CSS and HTML layout was designed by Chris Coyier at ![CSS-Tricks](http://css-tricks.com).

These bars have been designed to 'reveal' a gradient that is hidden. The idea came about while working with a strength meter. The built HTML meter tag has the not the capability to reveal a section of the bar, nor does it allow full gradient spanning while having a visual indicator on the meter. These bars consist of 4 layers. Layer one contains a full spanning gradient, from red to green. Layer two consists of a striped layer with transparency. Layer three consists of cover, that reveals the gradients below. The last layer is a text layer that can always be seen.

## Features

- Meter length control
- Meter height (thickness) control
- Meter background color control
- Meter shadow control
- Font size control
- Animation speed control
- Reveal width control

## Instructions

All instructions and usage information can be found @ ![JLDN.org](https://www.repo.jldn.org/JLDN-Meters/).

The image below provides samples of the current meter styles in place.
![Animated Bars Example](animatedbars-sample.png?raw=true)

## Todo

* Add support for other candystripe colors instead of the default.
* Add support for font colors instead of the default gradient.
