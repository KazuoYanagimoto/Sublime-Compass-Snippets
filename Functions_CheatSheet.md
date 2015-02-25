##Functions

###Sass Based Functions

######Computes the "brightness" of a color [>>](http://compass-style.org/reference/compass/utilities/color/brightness/#function-brightness)

```compass
brightness(${1:\$color})
```

######Check if the browser is in scope given the browser support and current prefix minimums. [>>](http://compass-style.org/reference/compass/support/#function-browser-out-of-scope)

```compass
browser-out-of-scope(${1:\$browser}, ${2:[\$version]})
```

######Create the color-stops needed for horizontal grids [>>](http://compass-style.org/reference/compass/layout/grid_background/#function-build-grid-background)

```compass
build-grid-background(${1:[\$total]}, ${2:[\$column]}, ${3:[\$gutter]}, ${4:[\$offset]}, ${5:[\$column-color]}, ${6:[\$gutter-color]})
```

######coerce a list to be comma delimited or make a new, empty comma delimited list. [>>](http://compass-style.org/reference/compass/support/#function-comma-list)

```compass
comma-list(${1:[\$list]})
```

######Returns either the $light or $dark color by deciding which contrasts more with $color. [>>](http://compass-style.org/reference/compass/utilities/color/contrast/#function-contrast-color)

```compass
contrast-color(${1:\$color}, ${2:[\$dark]}, ${3:[\$light]}, ${4:[\$threshold]})
```

######description [>>](http://compass-style.org/reference/compass/css3/box_shadow/#function-default-box-shadow)

```compass
default-box-shadow()
```

######description [>>](http://compass-style.org/reference/compass/support/#function-display-browser-range)

```compass
display-browser-range(${1:\$browser}, ${2:\$min-version}, ${3:[\$max-version]})
```

######Create the gradient needed for baseline grids [>>](http://compass-style.org/reference/compass/layout/grid_background/#function-get-baseline-gradient)

```compass
get-baseline-gradient(${1:[\$color]})
```

######Convert a grid from fixed units into percentages. [>>](http://compass-style.org/reference/compass/layout/grid_background/#function-get-column-fluid-grid)

```compass
get-column-fluid-grid(${1:[\$total]}, ${2:[\$column]}, ${3:[\$gutter]}, ${4:[\$offset]}, ${5:[\$column-color]}, ${6:[\$gutter-color]})
```

######Return the gradient needed for horizontal grids [>>](http://compass-style.org/reference/compass/layout/grid_background/#function-get-column-gradient)

```compass
get-column-gradient(${1:[\$total]}, ${2:[\$column]}, ${3:[\$gutter]}, ${4:[\$offset]}, ${5:[\$column-color]}, ${6:[\$gutter-color]}, ${7:[\$force-fluid]})
```

######Returns true if at least one browser-version pair in $subset-ranges is a higher (or same) version than the browser-version pairs in $ranges. [>>](http://compass-style.org/reference/compass/support/#function-has-browser-subset)

```compass
has-browser-subset(${1:\$ranges}, ${2:\$subset-ranges})
```

######When the same browser is in both maps, then the minimum will be set to the maximum of the two minimum versions, [>>](http://compass-style.org/reference/compass/support/#function-intersect-browser-ranges)

```compass
intersect-browser-ranges(${1:\$ranges}, ${2:\$new-ranges})
```

######Checks if the value given is a unit of time. [>>](http://compass-style.org/reference/compass/css3/transition/#function-is-time)

```compass
is-time(${1:\$value})
```

######Create a linear gradient using standard official or legacy syntax. [>>](http://compass-style.org/reference/compass/css3/images/#function-linear-gradient)

```compass
linear-gradient(${1:\$angle})
```

######Calculate the minimum multiple of rhythm units needed to contain the font-size. [>>](http://compass-style.org/reference/compass/typography/vertical_rhythm/#function-lines-for-font-size)

```compass
lines-for-font-size(${1:\$font-size})
```

######description [>>](http://compass-style.org/reference/compass/support/#function-prefix-identifier)

```compass
prefix-identifier(${1:\$ident}, ${2:[\$prefix]})
```

######Returns $property with the given prefix if it is found in $transitionable-prefixed-values. [>>](http://compass-style.org/reference/compass/css3/transition/#function-prefixed-for-transition)

```compass
prefixed-for-transition(${1:\$prefix}, ${2:\$property})
```

######description [>>](http://compass-style.org/reference/compass/support/#function-prefixes-for-capability)

```compass
prefixes-for-capability(${1:\$capability}, ${2:\$threshold}, ${3:[\$capability-options]})
```

######Calculate rhythm units. [>>](http://compass-style.org/reference/compass/typography/vertical_rhythm/#function-rhythm)

```compass
rhythm(${1:[\$lines]}, ${2:[\$font-size]}, ${3:[\$offset]})
```

######Set a default value if the given arglist is empty [>>](http://compass-style.org/reference/compass/support/#function-set-arglist-default)

```compass
set-arglist-default(${1:\$arglist}, ${2:\$default})
```

######Check whether the browser is supported according to the supported browsers, declared minimum support and usage thresholds. [>>](http://compass-style.org/reference/compass/support/#function-support-legacy-browser)

```compass
support-legacy-browser(${1:\$browser}, ${2:\$min-version}, ${3:[\$max-version]}, ${4:[\$threshold]})
```

######Returns $transition-map which includes key and values that map to a transition declaration [>>](http://compass-style.org/reference/compass/css3/transition/#function-transition-map)

```compass
transition-map(${1:\$transition})
```

######Returns true if the prefixed usage stats for the capability exceed the threshold or if the minimum version for a supported browser would require a prefix for the capability. [>>](http://compass-style.org/reference/compass/support/#function-use-prefix)

```compass
use-prefix(${1:\$prefix}, ${2:\$capability}, ${3:\$threshold}, ${4:[\$capability-options]})
```

###Compass Functions

markl