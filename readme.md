*This repository is a mirror of the [component](http://component.io) module [ramitos/luminosity](http://github.com/ramitos/luminosity). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/ramitos-luminosity`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# luminosity

luminosity functions from [harthur/color](https://github.com/harthur/color)

## install

```bash
component install ramitos/luminosity
```

## api

The WCAG luminosity of the color. 0 is black, 1 is white.
#### .luminosity(array: rbg)

The WCAG contrast ratio to another color, from 1 (same color) to 21 (contrast b/w white and black).
#### .contrast(array: rgb1, array: rgb2)

Get whether the color is "dark"/"light"
#### .dark(array: rgb) / .light(array: rgb)

## license

MIT