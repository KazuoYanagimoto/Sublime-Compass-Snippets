##Mixins

###A

######Adjust a block to have a different font size and line height to maintain the rhythm. [>>](http://compass-style.org/reference/compass/typography/vertical_rhythm/#mixin-adjust-font-size-to)

```compass
adjust-font-size-to(${1:\$to-size}, ${2:[\$lines]}, ${3:[\$from-size]})
```

######Adjust a block to have different line height to maintain the rhythm. [>>](http://compass-style.org/reference/compass/typography/vertical_rhythm/#mixin-adjust-leading-to)

```compass
adjust-leading-to(${1:\$lines}, ${2:[\$font-size]})
```

######Legal values: flex-start | flex-end | center | space-between | space-around | stretch [>>](http://compass-style.org/reference/compass/css3/flexbox/#mixin-align-content)

```compass
align-content(${1:\$align-content})
```

######Legal values: flex-start | flex-end | center | baseline | stretch [>>](http://compass-style.org/reference/compass/css3/flexbox/#mixin-align-items)

```compass
align-items(${1:\$align-items})
```

######Legal values: auto | flex-start | flex-end | center | baseline | stretch [>>](http://compass-style.org/reference/compass/css3/flexbox/#mixin-align-self)

```compass
align-self(${1:\$align-self})
```

######description [>>](http://compass-style.org/reference/compass/utilities/tables/alternating_rows_and_columns/#mixin-alternating-rows-and-columns)

```compass
alternating-rows-and-columns(${1:\$even-row-color}, ${2:\$odd-row-color}, ${3:\$dark-intersection}, ${4:[\$header-color]}, ${5:[\$footer-color]})
```

######Shortcut to apply any number of animations to an element, with all the settings. [>>](http://compass-style.org/reference/compass/css3/animation/#mixin-animation)

```compass
animation(${1:\$animation...})
```

######Apply any number of animation delays. [>>](http://compass-style.org/reference/compass/css3/animation/#mixin-animation-delay)

```compass
animation-delay(${1:\$delay...})
```

######Apply any number of animation directions. [>>](http://compass-style.org/reference/compass/css3/animation/#mixin-animation-direction)

```compass
animation-direction(${1:\$direction...})
```

######Apply any number of animation durations. [>>](http://compass-style.org/reference/compass/css3/animation/#mixin-animation-duration)

```compass
animation-duration(${1:\$duration...})
```

######Apply any number of animation fill modes. [>>](http://compass-style.org/reference/compass/css3/animation/#mixin-animation-fill-mode)

```compass
animation-fill-mode(${1:\$mode...})
```

######Apply any number of animation iteration counts. [>>](http://compass-style.org/reference/compass/css3/animation/#mixin-animation-iteration-count)

```compass
animation-iteration-count(${1:\$count...})
```

######Apply any number of animation names. [>>](http://compass-style.org/reference/compass/css3/animation/#mixin-animation-name)

```compass
animation-name(${1:\$name...})
```

######Apply any number of animation play states. [>>](http://compass-style.org/reference/compass/css3/animation/#mixin-animation-play-state)

```compass
animation-play-state(${1:\$state...})
```

######Apply any number of animation timing functions. [>>](http://compass-style.org/reference/compass/css3/animation/#mixin-animation-timing-function)

```compass
animation-timing-function(${1:\$function...})
```

######Change the appearance for Mozilla, Webkit and possibly the future. [>>](http://compass-style.org/reference/compass/css3/appearance/#mixin-appearance)

```compass
appearance(${1:\$appearance})
```

######Transform-origin Transform-origin sent as a complete string [>>](http://compass-style.org/reference/compass/css3/transform/#mixin-apply-origin)

```compass
apply-origin(${1:\$origin}, ${2:\$only3d})
```

######Apply a border and whitespace to any side without destroying the vertical rhythm. [>>](http://compass-style.org/reference/compass/typography/vertical_rhythm/#mixin-apply-side-rhythm-border)

```compass
apply-side-rhythm-border(${1:\$side}, ${2:[\$width]}, ${3:[\$lines]}, ${4:[\$font-size]}, ${5:[\$border-style]})
```

###B

######Determine the visibility of an element when it's back is turned [>>](http://compass-style.org/reference/compass/css3/transform/#mixin-backface-visibility)

```compass
backface-visibility(${1:[\$visibility]})
```

######Background property support for vendor prefixing within values. [>>](http://compass-style.org/reference/compass/css3/images/#mixin-background)

```compass
background(${1:\$backgrounds...})
```

######Clip the background (image and color) at the edge of the padding, border, or content. $clip... [>>](http://compass-style.org/reference/compass/css3/background_clip/#mixin-background-clip)

```compass
background-clip(${1:\$clip...})
```

######Background image property support for vendor prefixing within values. [>>](http://compass-style.org/reference/compass/css3/images/#mixin-background-image)

```compass
background-image(${1:\$images...})
```

######Set the origin of the background (image and color) at the edge of the padding, border, or content. [>>](http://compass-style.org/reference/compass/css3/background_origin/#mixin-background-origin)

```compass
background-origin(${1:\$origin...})
```

######Set the size of background images using px, width and height, or percentages. [>>](http://compass-style.org/reference/compass/css3/background_size/#mixin-background-size)

```compass
background-size(${1:\$size...})
```

######Set any number of background layers, along with a fallback. [>>](http://compass-style.org/reference/compass/css3/images/#mixin-background-with-css2-fallback)

```compass
background-with-css2-fallback(${1:\$backgrounds...})
```

######A hack to supply IE6 (and below) with a different property value. [>>](http://compass-style.org/reference/compass/utilities/general/hacks/#mixin-bang-hack)

```compass
bang-hack(${1:\$property}, ${2:\$value}, ${3:\$ie6-value})
```

######Add just the baseline grid to an element's background [>>](http://compass-style.org/reference/compass/layout/grid_background/#mixin-baseline-grid-background)

```compass
baseline-grid-background(${1:[\$baseline]}, ${2:[\$color]})
```

######Round bottom-left corner only [>>](http://compass-style.org/reference/compass/css3/border_radius/#mixin-border-bottom-left-radius)

```compass
border-bottom-left-radius(${1:[\$radius]})
```

######Round both bottom corners by amount [>>](http://compass-style.org/reference/compass/css3/border_radius/#mixin-border-bottom-radius)

```compass
border-bottom-radius(${1:[\$radius]})
```

######Round bottom-right corner only [>>](http://compass-style.org/reference/compass/css3/border_radius/#mixin-border-bottom-right-radius)

```compass
border-bottom-right-radius(${1:[\$radius]})
```

######Round radius at position by amount. [>>](http://compass-style.org/reference/compass/css3/border_radius/#mixin-border-corner-radius)

```compass
border-corner-radius(${1:\$vert}, ${2:\$horz}, ${3:[\$radius]})
```

######Border image property support for vendor prefixing properties and values. [>>](http://compass-style.org/reference/compass/css3/images/#mixin-border-image)

```compass
border-image(${1:\$value})
```

######Round both left corners by amount [>>](http://compass-style.org/reference/compass/css3/border_radius/#mixin-border-left-radius)

```compass
border-left-radius(${1:[\$radius]})
```

######Round all corners by a specific amount, defaults to value of $default-border-radius. [>>](http://compass-style.org/reference/compass/css3/border_radius/#mixin-border-radius)

```compass
border-radius(${1:[\$radius]}, ${2:[\$vertical-radius]})
```

######Round both right corners by amount [>>](http://compass-style.org/reference/compass/css3/border_radius/#mixin-border-right-radius)

```compass
border-right-radius(${1:[\$radius]})
```

######Round top-left corner only [>>](http://compass-style.org/reference/compass/css3/border_radius/#mixin-border-top-left-radius)

```compass
border-top-left-radius(${1:[\$radius]})
```

######Round both top corners by amount [>>](http://compass-style.org/reference/compass/css3/border_radius/#mixin-border-top-radius)

```compass
border-top-radius(${1:[\$radius]})
```

######Round top-right corner only [>>](http://compass-style.org/reference/compass/css3/border_radius/#mixin-border-top-right-radius)

```compass
border-top-right-radius(${1:[\$radius]})
```

######Box align [ start | end | center | baseline | stretch ] [>>](http://compass-style.org/reference/compass/css3/box/#mixin-box-align)

```compass
box-align(${1:[\$alignment]})
```

######Box direction [ normal | reverse | inherit ] [>>](http://compass-style.org/reference/compass/css3/box/#mixin-box-direction)

```compass
box-direction(${1:[\$direction]})
```

######Takes an int argument for box flex. Apply this to the children inside the box. [>>](http://compass-style.org/reference/compass/css3/box/#mixin-box-flex)

```compass
box-flex(${1:[\$flex]})
```

######Takes an int argument for flexible grouping [>>](http://compass-style.org/reference/compass/css3/box/#mixin-box-flex-group)

```compass
box-flex-group(${1:[\$group]})
```

######Box lines [ single | multiple ] [>>](http://compass-style.org/reference/compass/css3/box/#mixin-box-lines)

```compass
box-lines(${1:[\$lines]})
```

######Takes an int argument for ordinal grouping and rearranging the order [>>](http://compass-style.org/reference/compass/css3/box/#mixin-box-ordinal-group)

```compass
box-ordinal-group(${1:[\$group]})
```

######Box orientation [ horizontal | vertical | inline-axis | block-axis | inherit ] [>>](http://compass-style.org/reference/compass/css3/box/#mixin-box-orient)

```compass
box-orient(${1:[\$orientation]})
```

######Box pack [ start | end | center | justify ] [>>](http://compass-style.org/reference/compass/css3/box/#mixin-box-pack)

```compass
box-pack(${1:[\$pack]})
```

######Provides cross-browser for Webkit, Gecko, and CSS3 box shadows when one or more box shadows are needed. [>>](http://compass-style.org/reference/compass/css3/box_shadow/#mixin-box-shadow)

```compass
box-shadow(${1:\$shadow...})
```

######Change the box model for Mozilla, Webkit, IE8 and the future [>>](http://compass-style.org/reference/compass/css3/box_sizing/#mixin-box-sizing)

```compass
box-sizing(${1:[\$box-model]})
```

######Mixin for setting break-after [>>](http://compass-style.org/reference/compass/css3/columns/#mixin-break-after)

```compass
break-after(${1:[\$value]})
```

######Mixin for setting break-before [>>](http://compass-style.org/reference/compass/css3/columns/#mixin-break-before)

```compass
break-before(${1:[\$value]})
```

######Mixin for setting break-inside [>>](http://compass-style.org/reference/compass/css3/columns/#mixin-break-inside)

```compass
break-inside(${1:[\$value]})
```

###C

######This basic method is preferred for the usual case, when positioned content will not show outside the bounds of the container. [>>](http://compass-style.org/reference/compass/utilities/general/clearfix/#mixin-clearfix)

```compass
clearfix($1)
```

######color-interpolation-filters (auto | sRGB | linearRGB ) [>>](http://compass-style.org/reference/compass/css3/filter/#mixin-color-interpolation-filters)

```compass
color-interpolation-filters(${1:\$value})
```

######All-purpose mixin for setting column breaks. [>>](http://compass-style.org/reference/compass/css3/columns/#mixin-column-break)

```compass
column-break(${1:[\$type]}, ${2:[\$value]})
```

######description [>>](http://compass-style.org/reference/compass/css3/columns/#mixin-column-break-after)

```compass
column-break-after(${1:[\$value]})
```
######description [>>](http://compass-style.org/reference/compass/css3/columns/#mixin-column-break-before)

```compass
column-break-before(${1:[\$value]})
```

######description [>>](http://compass-style.org/reference/compass/css3/columns/#mixin-column-break-inside)

```compass
column-break-inside(${1:[\$value]})
```

######Specify the number of columns [>>](http://compass-style.org/reference/compass/css3/columns/#mixin-column-count)

```compass
column-count(${1:\$count})
```

######Mixin for setting column-fill [>>](http://compass-style.org/reference/compass/css3/columns/#mixin-column-fill)

```compass
column-fill(${1:[\$fill]})
```

######Specify the gap between columns e.g. 20px [>>](http://compass-style.org/reference/compass/css3/columns/#mixin-column-gap)

```compass
column-gap(${1:\$width})
```

######Add just the horizontal grid to an element's background [>>](http://compass-style.org/reference/compass/layout/grid_background/#mixin-column-grid-background)

```compass
column-grid-background(${1:[\$total]}, ${2:[\$column]}, ${3:[\$gutter]}, ${4:[\$offset]}, ${5:[\$column-color]}, ${6:[\$gutter-color]}, ${7:[\$force-fluid]})
```

######Mixin encompassing all column rule properties For example: [>>](http://compass-style.org/reference/compass/css3/columns/#mixin-column-rule)

```compass
column-rule(${1:\$width}, ${2:[\$style]}, ${3:[\$color]})
```

######Specify the color of the rule between columns e.g. blue. This works like border-color. [>>](http://compass-style.org/reference/compass/css3/columns/#mixin-column-rule-color)

```compass
column-rule-color(${1:\$color})
```

######Specify the style of the rule between columns e.g. dotted. This works like border-style. [>>](http://compass-style.org/reference/compass/css3/columns/#mixin-column-rule-style)

```compass
column-rule-style(${1:\$style})
```

######Specify the width of the rule between columns e.g. 1px [>>](http://compass-style.org/reference/compass/css3/columns/#mixin-column-rule-width)

```compass
column-rule-width(${1:\$width})
```

######Specify how many columns an element should span across. [>>](http://compass-style.org/reference/compass/css3/columns/#mixin-column-span)

```compass
column-span(${1:\$columns})
```
```compass
column-span(${1:[\$span]})

######Specify the width of columns e.g. 100px [>>](http://compass-style.org/reference/compass/css3/columns/#mixin-column-width)

```compass
column-width(${1:\$width})
```

######Specify the shorthand columns property. [>>](http://compass-style.org/reference/compass/css3/columns/#mixin-columns)

```compass
columns(${1:\$width-and-count})
```

######See delimited-list @deprecated [>>](http://compass-style.org/reference/compass/typography/lists/inline_list/#mixin-comma-delimited-list)

```compass
comma-delimited-list($1)
```

######content property support for vendor prefixing within values. [>>](http://compass-style.org/reference/compass/css3/images/#mixin-content)

```compass
content(${1:\$value})
```

######Sets the specified background color and calculates a dark or light contrasted text color. [>>](http://compass-style.org/reference/compass/utilities/color/contrast/#mixin-contrasted)

```compass
contrasted(${1:\$background-color}, ${2:[\$dark]}, ${3:[\$light]}, ${4:[\$threshold]})
```

######Full transform mixins For settings any combination of transforms as arguments [>>](http://compass-style.org/reference/compass/css3/transform/#mixin-create-transform)

```compass
create-transform(${1:[\$perspective]}, ${2:[\$scale-x]}, ${3:[\$scale-y]}, ${4:[\$scale-z]}, ${5:[\$rotate-x]}, ${6:[\$rotate-y]}, ${7:[\$rotate-z]}, ${8:[\$rotate3d]}, ${9:[\$trans-x]}, ${10:[\$trans-y]}, ${11:[\$trans-z]}, ${12:[\$skew-x]}, ${13:[\$skew-y]}, ${14:[\$origin-x]}, ${15:[\$origin-y]}, ${16:[\$origin-z]}, ${17:[\$only3d]})
```

###D

######Show a background image that can be used to debug your alignments. [>>](http://compass-style.org/reference/compass/typography/vertical_rhythm/#mixin-debug-vertical-alignment)

```compass
debug-vertical-alignment(${1:[\$img]})
```

######makes an inline list delimited with the passed string. [>>](makes an inline list delimited with the passed string.)

```compass
delimited-list(${1:[\$separator]})
```

######Apply 'display:box;' to an element. [>>](http://compass-style.org/reference/compass/css3/box/#mixin-display-box)

```compass
display-box($1)
```

######Values for $display are: flex (default), inline-flex [>>](http://compass-style.org/reference/compass/css3/flexbox/#mixin-display-flex)

```compass
display-flex(${1:[\$display]})
```

###E

######description [>>](http://compass-style.org/reference/compass/css3/images/#mixin-each-gradient-prefix)

```compass
each-gradient-prefix(${1:\$values})
```

######description [>>](http://compass-style.org/reference/compass/typography/text/ellipsis/#mixin-ellipsis)

```compass
ellipsis(${1:[\$no-wrap]})
```

######Establishes a font baseline for the given font-size. [>>](http://compass-style.org/reference/compass/typography/vertical_rhythm/#mixin-establish-baseline)

```compass
establish-baseline(${1:[\$font-size]})
```

###F

######Provides cross-browser support for the upcoming (?) css3 filter property. [>>](http://compass-style.org/reference/compass/css3/filter/#mixin-filter)

```compass
filter(${1:\$filters})
```

######Emit a IE-Specific filters that renders a simple linear gradient. [>>](http://compass-style.org/reference/compass/css3/images/#mixin-filter-gradient)

```compass
filter-gradient(${1:\$start-color}, ${2:\$end-color}, ${3:[\$orientation]})
```

######filter-margin [>>](http://compass-style.org/reference/compass/css3/filter/#mixin-filter-margin)

```compass
filter-margin(${1:\$widths})
```

######filter-margin-bottom [>>](http://compass-style.org/reference/compass/css3/filter/#mixin-filter-margin-bottom)

```compass
filter-margin-bottom(${1:\$width})
```

######filter-margin-left [>>](http://compass-style.org/reference/compass/css3/filter/#mixin-filter-margin-left)

```compass
filter-margin-left(${1:\$width})
```

######filter-margin-right [>>](http://compass-style.org/reference/compass/css3/filter/#mixin-filter-margin-right)

```compass
filter-margin-right(${1:\$width})
```

######filter-margin-top [>>](http://compass-style.org/reference/compass/css3/filter/#mixin-filter-margin-top)

```compass
filter-margin-top(${1:\$width})
```

######Shorthand for flex-grow, flex-shrink and optionally flex-basis. [>>](http://compass-style.org/reference/compass/css3/flexbox/#mixin-flex)

```compass
flex(${1:\$flex})
```

######Accepts any legal value for the width property. [>>](http://compass-style.org/reference/compass/css3/flexbox/#mixin-flex-basis)

```compass
flex-basis(${1:\$flex-basis})
```

######Values: row | row-reverse | column | column-reverse [>>](http://compass-style.org/reference/compass/css3/flexbox/#mixin-flex-direction)

```compass
flex-direction(${1:\$direction})
```

######Shorthand for flex-direction and flex-wrap. [>>](http://compass-style.org/reference/compass/css3/flexbox/#mixin-flex-flow)

```compass
flex-flow(${1:\$flow})
```

######Accepts a number. [>>](http://compass-style.org/reference/compass/css3/flexbox/#mixin-flex-grow)

```compass
flex-grow(${1:\$flex-grow})
```

######Accepts a number. [>>](http://compass-style.org/reference/compass/css3/flexbox/#mixin-flex-shrink)

```compass
flex-shrink(${1:\$flex-shrink})
```

######Values: nowrap | wrap | wrap-reverse [>>](http://compass-style.org/reference/compass/css3/flexbox/#mixin-flex-wrap)

```compass
flex-wrap(${1:\$wrap})
```

######This is the underlying implementation for all the other mixins in this module. [>>](http://compass-style.org/reference/compass/css3/flexbox/#mixin-flexbox)

```compass
flexbox(${1:\$properties}, ${2:[\$version]})
```

######Direction independent float mixin that fixes the double-margin bug in IE5/6 [>>](http://compass-style.org/reference/compass/utilities/general/float/#mixin-float)

```compass
float(${1:[\$side]})
```

######Implementation of float:left with fix for the double-margin bug in IE5/6 [>>](http://compass-style.org/reference/compass/utilities/general/float/#mixin-float-left)

```compass
float-left()
```

######Implementation of float:right with fix for the double-margin bug in IE5/6 [>>](http://compass-style.org/reference/compass/utilities/general/float/#mixin-float-right)

```compass
float-right()
```

######description [>>](http://compass-style.org/reference/compass/css3/regions/#mixin-flow-from)

```compass
flow-from(${1:\$target})
```

######Webkit, IE10 and future support for CSS Regions [>>](http://compass-style.org/reference/compass/css3/regions/#mixin-flow-into)

```compass
flow-into(${1:\$target})
```

######Cross-browser support for @font-face. Supports IE, Gecko, Webkit, Opera. [>>](http://compass-style.org/reference/compass/css3/font_face/#mixin-font-face)

```compass
font-face(${1:\$name}, ${2:\$font-files}, ${3:[\$eot]}, ${4:[\$weight]}, ${5:[\$style]})
```

######Renders the content once if any of the legacy browsers are supported. [>>](http://compass-style.org/reference/compass/support/#mixin-for-legacy-browsers)

```compass
for-legacy-browsers(${1:\$browsers}, ${2:[\$threshold]})
```

######Include content for a legacy browser Version can be a single version string or a list of versions ordered from oldest to newest. [>>](http://compass-style.org/reference/compass/support/#mixin-for-legacy-browser)

```compass
for-legacy-browser(${1:\$browser}, ${2:\$min-version}, ${3:[\$max-version]}, ${4:[\$threshold]}, ${5:[\$ranges]})
```

######Prevent long urls and text from breaking layouts originally from perishablepress.com [>>](http://compass-style.org/reference/compass/typography/text/force-wrap/#mixin-force-wrap)

```compass
force-wrap()
```

###G

######Based on Eric Meyer's reset 2.0 Global reset rules. [>>](http://compass-style.org/reference/compass/reset/utilities/#mixin-global-reset)

```compass
global-reset()
```

######Add both horizontal and baseline grids to an element's background [>>](http://compass-style.org/reference/compass/layout/grid_background/#mixin-grid-background)

```compass
grid-background(${1:[\$total]}, ${2:[\$column]}, ${3:[\$gutter]}, ${4:[\$baseline]}, ${5:[\$offset]}, ${6:[\$column-color]}, ${7:[\$gutter-color]}, ${8:[\$baseline-color]}, ${9:[\$force-fluid]})
```

###H

######Alias for horizontal-borders mixin. [>>](http://compass-style.org/reference/compass/typography/vertical_rhythm/#mixin-h-borders)

```compass
h-borders(${1:[\$width]}, ${2:[\$lines]}, ${3:[\$font-size]}, ${4:[\$border-style]})
```

######This mixin causes an element matching the selector to gain the "hasLayout" property in internet explorer.  [>>](http://compass-style.org/reference/compass/utilities/general/hacks/#mixin-has-layout)

```compass
has-layout(${1:[\$approach]})
```

######description [>>](http://compass-style.org/reference/compass/utilities/general/hacks/#mixin-has-layout-block)

```compass
has-layout-block()
```

######description [>>](http://compass-style.org/reference/compass/utilities/general/hacks/#mixin-has-layout-zoom)

```compass
has-layout-zoom()
```

######Hides text in an element so you can see the background. [>>](http://compass-style.org/reference/compass/typography/text/replacement/#mixin-hide-text)

```compass
hide-text(${1:[\$direction]})
```

######Apply both leading and trailing borders. [>>](http://compass-style.org/reference/compass/typography/vertical_rhythm/#mixin-horizontal-borders)

```compass
horizontal-borders(${1:[\$width]}, ${2:[\$lines]}, ${3:[\$font-size]}, ${4:[\$border-style]})
```

######A list(ol,ul) that is layed out such that the elements are floated left and won't wrap. [>>](http://compass-style.org/reference/compass/typography/lists/horizontal_list/#mixin-horizontal-list)

```compass
horizontal-list(${1:[\$padding]}, ${2:[\$direction]})
```

######Can be mixed into any selector that target a ul or ol that is meant to have a horizontal layout. [>>](http://compass-style.org/reference/compass/typography/lists/horizontal_list/#mixin-horizontal-list-container)

```compass
horizontal-list-container()
```

######Can be mixed into any li selector that is meant to participate in a horizontal layout. [>>](http://compass-style.org/reference/compass/typography/lists/horizontal_list/#mixin-horizontal-list-item)

```compass
horizontal-list-item(${1:[\$padding]}, ${2:[\$direction]})
```

######a link that only has an underline when you hover over it [>>](http://compass-style.org/reference/compass/typography/links/hover_link/#mixin-hover-link)

```compass
hover-link()
```

######Mixin for x-browser hyphenation based on @auchenberg's post: [>>](http://compass-style.org/reference/compass/css3/hyphenation/#mixin-hyphenation)

```compass
hyphenation()
```

######Mixin for the hyphens property [>>](http://compass-style.org/reference/compass/css3/hyphenation/#mixin-hyphens)

```compass
hyphens(${1:[\$value]})
```

###I

######description [>>](http://compass-style.org/reference/compass/css3/images/#mixin-image-property)

```compass
image-property(${1:\$property})
```

######Provides a cross-browser method to implement display: inline-block; [>>](http://compass-style.org/reference/compass/css3/inline_block/#mixin-inline-block)

```compass
inline-block(${1:[\$alignment]}, ${2:[\$ie-alignment]})
```

######A list(ol,ul) that is layed out such that the elements are inline-block and won't wrap. [>>](A list(ol,ul) that is layed out such that the elements are inline-block and won't wrap.)

```compass
inline-block-list(${1:[\$padding]})
```

######Can be mixed into any selector that target a ul or ol that is meant to have an inline-block layout. [>>](http://compass-style.org/reference/compass/typography/lists/inline-block-list/#mixin-inline-block-list-container)

```compass
inline-block-list-container()
```

######Can be mixed into any li selector that is meant to participate in a horizontal layout. [>>](http://compass-style.org/reference/compass/typography/lists/inline-block-list/#mixin-inline-block-list-item)

```compass
inline-block-list-item(${1:[\$padding]})
```

######makes a list inline. [>>](http://compass-style.org/reference/compass/typography/lists/inline_list/#mixin-inline-list)

```compass
inline-list()
```

######description [>>](http://compass-style.org/reference/compass/utilities/tables/borders/#mixin-inner-table-borders)

```compass
inner-table-borders(${1:[\$width]}, ${2:[\$color]})
```

######Style the html5 input placeholder in browsers that support it. [>>](http://compass-style.org/reference/compass/css3/user_interface/#mixin-input-placeholder)

```compass
input-placeholder()
```

###J

######Legal values: flex-start | flex-end | center | space-between | space-around [>>](http://compass-style.org/reference/compass/css3/flexbox/#mixin-justify-content)

```compass
justify-content(${1:\$justify-content})
```

###K

######Create a named animation sequence that can be applied to elements later. [>>](http://compass-style.org/reference/compass/css3/animation/#mixin-keyframes)

```compass
keyframes(${1:\$name})
```

###L

######Apply leading whitespace. [>>](http://compass-style.org/reference/compass/typography/vertical_rhythm/#mixin-leader)

```compass
leader(${1:[\$lines]}, ${2:[\$font-size]}, ${3:[\$property]})
```

######Apply a leading border. [>>](http://compass-style.org/reference/compass/typography/vertical_rhythm/#mixin-leading-border)

```compass
leading-border(${1:[\$width]}, ${2:[\$lines]}, ${3:[\$font-size]}, ${4:[\$border-style]})
```

######This older method from Position Is Everything called [>>](http://compass-style.org/reference/compass/utilities/general/clearfix/#mixin-legacy-pie-clearfix)

```compass
legacy-pie-clearfix()
```

######Set all the colors for a link with one mixin call. [>>](http://compass-style.org/reference/compass/typography/links/link_colors/#mixin-link-colors)

```compass
link-colors(${1:\$normal}, ${2:[\$hover]}, ${3:[\$active]}, ${4:[\$visited]}, ${5:[\$focus]})
```

######List style property support for vendor prefixing within values. [>>](http://compass-style.org/reference/compass/css3/images/#mixin-list-style)

```compass
list-style(${1:\$value})
```

######List style image property support for vendor prefixing within values. [>>](http://compass-style.org/reference/compass/css3/images/#mixin-list-style-image)

```compass
list-style-image(${1:\$image})
```

###M

######Apply leading whitespace as margin. [>>](http://compass-style.org/reference/compass/typography/vertical_rhythm/#mixin-margin-leader)

```compass
margin-leader(${1:[\$lines]}, ${2:[\$font-size]})
```

######Apply trailing whitespace as margin. [>>](http://compass-style.org/reference/compass/typography/vertical_rhythm/#mixin-margin-trailer)

```compass
margin-trailer(${1:[\$lines]}, ${2:[\$font-size]})
```

######Cross browser min-height mixin. [>>](http://compass-style.org/reference/compass/utilities/general/min/#mixin-min-height)

```compass
min-height(${1:\$value})
```

######Cross browser min-width mixin. [>>](http://compass-style.org/reference/compass/utilities/general/min/#mixin-min-width)

```compass
min-width(${1:\$value})
```

###N

######Reset all elements within some selector scope. [>>](http://compass-style.org/reference/compass/reset/utilities/#mixin-nested-reset)

```compass
nested-reset()
```

######Turn off the bullet for an element of a list [>>](http://compass-style.org/reference/compass/typography/lists/bullets/#mixin-no-bullet)

```compass
no-bullet()
```

######turns off the bullets for an entire list [>>](http://compass-style.org/reference/compass/typography/lists/bullets/#mixin-no-bullets)

```compass
no-bullets()
```

######When remembering whether or not there's a hyphen in white-space is too hard [>>](http://compass-style.org/reference/compass/typography/text/nowrap/#mixin-nowrap)

```compass
nowrap()
```

###N

######Provides cross-browser CSS opacity. [>>](http://compass-style.org/reference/compass/css3/opacity/#mixin-opacity)

```compass
opacity(${1:\$opacity})
```

######Make an element completely opaque. [>>](http://compass-style.org/reference/compass/css3/opacity/#mixin-opaque)

```compass
opaque()
```

######Accepts an integer [>>](http://compass-style.org/reference/compass/css3/flexbox/#mixin-order)

```compass
order(${1:\$order})
```

######description [>>](http://compass-style.org/reference/compass/utilities/tables/borders/#mixin-outer-table-borders)

```compass
outer-table-borders(${1:[\$width]}, ${2:[\$color]})
```

###P

######Apply leading whitespace as padding. [>>](http://compass-style.org/reference/compass/typography/vertical_rhythm/#mixin-padding-leader)

```compass
padding-leader(${1:[\$lines]}, ${2:[\$font-size]})
```

######Apply trailing whitespace as padding. [>>](http://compass-style.org/reference/compass/typography/vertical_rhythm/#mixin-padding-trailer)

```compass
padding-trailer(${1:[\$lines]}, ${2:[\$font-size]})
```

######Set the perspective of 3D transforms on the children of an element: [>>](http://compass-style.org/reference/compass/css3/transform/#mixin-perspective)

```compass
perspective(${1:\$p})
```

######Set the origin position for the perspective [>>](http://compass-style.org/reference/compass/css3/transform/#mixin-perspective-origin)

```compass
perspective-origin(${1:[\$origin]})
```

######This is an updated version of the PIE clearfix method that reduces the amount of CSS output. [>>](http://compass-style.org/reference/compass/utilities/general/clearfix/#mixin-pie-clearfix)

```compass
pie-clearfix()
```

######Output a property and value using the current prefix. [>>](http://compass-style.org/reference/compass/support/#mixin-prefix-prop)

```compass
prefix-prop(${1:\$property}, ${2:\$value}, ${3:[\$prefix]})
```

######Emit a set of properties with the prefix governed by the capability and usage threshold given. [>>](http://compass-style.org/reference/compass/support/#mixin-prefixed-properties)

```compass
prefixed-properties(${1:\$capability}, ${2:\$threshold}, ${3:\$properties}, ${4:[\$capability-options]})
```

######Make a list(ul/ol) have an image bullet. [>>](http://compass-style.org/reference/compass/typography/lists/bullets/#mixin-pretty-bullets)

```compass
pretty-bullets(${1:\$bullet-icon}, ${2:[\$width]}, ${3:[\$height]}, ${4:[\$line-height]}, ${5:[\$padding]})
```

######Classes that are useful for controlling what gets printed. [>>](http://compass-style.org/reference/compass/utilities/print/#mixin-print-utilities)

```compass
print-utilities(${1:[\$media]})
```

###R

######Hides html text and replaces it with an image.  [>>](http://compass-style.org/reference/compass/typography/text/replacement/#mixin-replace-text)

```compass
replace-text(${1:\$img}, ${2:[\$x]}, ${3:[\$y]})
```

######Like the replace-text mixin, but also sets the width and height of the element according the dimensions of the image. [>>](http://compass-style.org/reference/compass/typography/text/replacement/#mixin-replace-text-with-dimensions)

```compass
replace-text-with-dimensions(${1:\$img}, ${2:[\$x]}, ${3:[\$y]}, ${4:[\$inline]})
```

######Resets the baseline to 1 rhythm unit Does not work on elements whose font-size is different from $base-font-size. [>>](http://compass-style.org/reference/compass/typography/vertical_rhythm/#mixin-reset-baseline)

```compass
reset-baseline(${1:[\$font-size]})
```

######Reset a body element. [>>](http://compass-style.org/reference/compass/reset/utilities/#mixin-reset-body)

```compass
reset-body()
```

######Reset the box model measurements. [>>](http://compass-style.org/reference/compass/reset-legacy/utilities-legacy/#mixin-reset-box-model)

```compass
reset-box-model()
```

######Resets the display of inline and block elements to their default display according to their tag type. [>>](http://compass-style.org/reference/compass/reset/utilities/#mixin-reset-display)

```compass
reset-display(${1:[\$selector]}, ${2:[\$important]})
```

######Resets floated elements back to their default of float: none and defaults to display: block unless you pass inline as an argument [>>](http://compass-style.org/reference/compass/utilities/general/float/#mixin-reset-float)

```compass
reset-float(${1:[\$display]})
```

######Resets the outline when focus. [>>](http://compass-style.org/reference/compass/reset/utilities/#mixin-reset-focus)

```compass
reset-focus()
```

######Reset the font and vertical alignment. [>>](http://compass-style.org/reference/compass/reset/utilities/#mixin-reset-font)

```compass
reset-font()
```

######Unrecognized elements are displayed inline. [>>](http://compass-style.org/reference/compass/reset/utilities/#mixin-reset-html5)

```compass
reset-html5()
```

######Resets the border. [>>](http://compass-style.org/reference/compass/reset-legacy/utilities-legacy/#mixin-reset-image-anchor-border)

```compass
reset-image-anchor-border()
```

######Reset the list style of an element. [>>](http://compass-style.org/reference/compass/reset-legacy/utilities-legacy/#mixin-reset-list-style)

```compass
reset-list-style()
```

######Reset a quotation (q, blockquote) [>>](http://compass-style.org/reference/compass/reset-legacy/utilities-legacy/#mixin-reset-quotation)

```compass
reset-quotation()
```

######Reset a table [>>](http://compass-style.org/reference/compass/reset/utilities/#mixin-reset-table)

```compass
reset-table()
```

######Reset a table cell (th, td) [>>](http://compass-style.org/reference/compass/reset-legacy/utilities-legacy/#mixin-reset-table-cell)

```compass
reset-table-cell()
```

######Shorthand mixin to apply whitespace for top and bottom margins and padding. [>>](http://compass-style.org/reference/compass/typography/vertical_rhythm/#mixin-rhythm)

```compass
rhythm(${1:[\$leader]}, ${2:[\$padding-leader]}, ${3:[\$padding-trailer]}, ${4:[\$trailer]}, ${5:[\$font-size]})
```

######Apply borders and whitespace equally to all sides. [>>](http://compass-style.org/reference/compass/typography/vertical_rhythm/#mixin-rhythm-borders)

```compass
rhythm-borders(${1:[\$width]}, ${2:[\$lines]}, ${3:[\$font-size]}, ${4:[\$border-style]})
```

######Shorthand mixin to apply whitespace for top and bottom margins. [>>](http://compass-style.org/reference/compass/typography/vertical_rhythm/#mixin-rhythm-margins)

```compass
rhythm-margins(${1:[\$leader]}, ${2:[\$trailer]}, ${3:[\$font-size]})
```

######Shorthand mixin to apply whitespace for top and bottom padding. [>>](http://compass-style.org/reference/compass/typography/vertical_rhythm/#mixin-rhythm-padding)

```compass
rhythm-padding(${1:[\$padding-leader]}, ${2:[\$padding-trailer]}, ${3:[\$font-size]})
```

######Rotate an object around the z axis (2D) [>>](http://compass-style.org/reference/compass/css3/transform/#mixin-rotate)

```compass
rotate(${1:[\$rotate]}, ${2:[\$perspective]}, ${3:[\$only3d]})
```

######Rotate an object around an arbitrary axis (3D) [>>](http://compass-style.org/reference/compass/css3/transform/#mixin-rotate3d)

```compass
rotate3d(${1:[\$vector-x]}, ${2:[\$vector-y]}, ${3:[\$vector-z]}, ${4:[\$rotate]}, ${5:[\$perspective]})
```

######Rotate an object around the x axis (3D) @include rotate( [ rotation, perspective ] ) [>>](http://compass-style.org/reference/compass/css3/transform/#mixin-rotateX)

```compass
rotateX(${1:[\$rotate]}, ${2:[\$perspective]})
```

######Rotate an object around the y axis (3D) @include rotate( [ rotation, perspective ] ) [>>](http://compass-style.org/reference/compass/css3/transform/#mixin-rotateY)

```compass
rotateY(${1:[\$rotate]}, ${2:[\$perspective]})
```

######A longcut for 'rotate' in case you forget that 'z' is implied [>>](http://compass-style.org/reference/compass/css3/transform/#mixin-rotateZ)

```compass
rotateZ(${1:[\$rotate]}, ${2:[\$perspective]}, ${3:[\$only3d]})
```

###S

######Scale an object along the x and y axis: [>>](http://compass-style.org/reference/compass/css3/transform/#mixin-scale)

```compass
scale(${1:[\$scale-x]}, ${2:[\$scale-y]}, ${3:[\$perspective]}, ${4:[\$only3d]})
```

######Scale and object along all three axis @include scale3d( [ scale-x, scale-y, scale-z, perspective ] ) [>>](http://compass-style.org/reference/compass/css3/transform/#mixin-scale3d)

```compass
scale3d(${1:[\$scale-x]}, ${2:[\$scale-y]}, ${3:[\$scale-z]}, ${4:[\$perspective]})
```

######Scale an object along the x axis @include scaleX( [ scale-x, perspective, 3D-only ] ) [>>](http://compass-style.org/reference/compass/css3/transform/#mixin-scaleX)

```compass
scaleX(${1:[\$scale]}, ${2:[\$perspective]}, ${3:[\$only3d]})
```

######Scale an object along the y axis @include scaleY( [ scale-y, perspective, 3D-only ] ) [>>](http://compass-style.org/reference/compass/css3/transform/#mixin-scaleY)

```compass
scaleY(${1:[\$scale]}, ${2:[\$perspective]}, ${3:[\$only3d]})
```

######Scale an object along the z axis @include scaleZ( [ scale-z, perspective ] ) [>>](http://compass-style.org/reference/compass/css3/transform/#mixin-scaleZ)

```compass
scaleZ(${1:[\$scale]}, ${2:[\$perspective]})
```

######Style selected text. [>>](http://compass-style.org/reference/compass/css3/selection/#mixin-selection)

```compass
selection(${1:[\$background-color]}, ${2:[\$color]})
```

######A simplified set of options backwards-compatible with the previous version of the 'transform' mixin [>>](http://compass-style.org/reference/compass/css3/transform/#mixin-simple-transform)

```compass
simple-transform(${1:[\$scale]}, ${2:[\$rotate]}, ${3:[\$trans-x]}, ${4:[\$trans-y]}, ${5:[\$skew-x]}, ${6:[\$skew-y]}, ${7:[\$origin-x]}, ${8:[\$origin-y]})
```

######Provides a single cross-browser CSS box shadow for Webkit, Gecko, and CSS3. [>>](http://compass-style.org/reference/compass/css3/box_shadow/#mixin-single-box-shadow)

```compass
single-box-shadow(${1:[\$hoff]}, ${2:[\$voff]}, ${3:[\$blur]}, ${4:[\$spread]}, ${5:[\$color]}, ${6:[\$inset]})
```

######Provides a single cross-browser CSS text shadow. [>>](http://compass-style.org/reference/compass/css3/text-shadow/#mixin-single-text-shadow)

```compass
single-text-shadow(${1:[\$hoff]}, ${2:[\$voff]}, ${3:[\$blur]}, ${4:[\$spread]}, ${5:[\$color]})
```

######Transition all-in-one shorthand [>>](http://compass-style.org/reference/compass/css3/transition/#mixin-single-transition)

```compass
single-transition(${1:[\$property]}, ${2:[\$duration]}, ${3:[\$function]}, ${4:[\$delay]})
```

######Skew an element: [>>](http://compass-style.org/reference/compass/css3/transform/#mixin-skew)

```compass
skew(${1:[\$skew-x]}, ${2:[\$skew-y]}, ${3:[\$only3d]})
```

######Skew an element along the x axiz [>>](http://compass-style.org/reference/compass/css3/transform/#mixin-skewX)

```compass
skewX(${1:[\$skew-x]}, ${2:[\$only3d]})
```

######Skew an element along the y axis [>>](http://compass-style.org/reference/compass/css3/transform/#mixin-skewY)

```compass
skewY(${1:[\$skew-y]}, ${2:[\$only3d]})
```

######Generates a class for each space separated name in $sprite-names. [>>](http://compass-style.org/reference/compass/utilities/sprites/base/#mixin-sprites)

```compass
sprites(${1:\$map}, ${2:\$sprite-names}, ${3:[\$base-class]}, ${4:[\$dimensions]}, ${5:[\$prefix]}, ${6:[\$offset-x]}, ${7:[\$offset-y]}, ${8:[\$use-percentages]}, ${9:[\$separator]})
```

######Sets rules common for all sprites, assumes you want a square, but allows a rectangular region. [>>](http://compass-style.org/reference/compass/utilities/sprites/sprite_img/#mixin-sprite-background)

```compass
sprite-background(${1:\$img}, ${2:[\$width]}, ${3:[\$height]})
```

######Set the background position of the given sprite $map to display the sprite of the given $sprite name. [>>](http://compass-style.org/reference/compass/utilities/sprites/base/#mixin-sprite-background-position)

```compass
sprite-background-position(${1:\$map}, ${2:\$sprite}, ${3:[\$offset-x]}, ${4:[\$offset-y]}, ${5:[\$use-percentages]})
```

######Sets rules common for all sprites, assumes a rectangular region. [>>](http://compass-style.org/reference/compass/utilities/sprites/sprite_img/#mixin-sprite-background-rectangle)

```compass
sprite-background-rectangle(${1:\$img}, ${2:[\$width]}, ${3:[\$height]})
```

######Allows horizontal sprite positioning optimized for a single row of sprites. [>>](http://compass-style.org/reference/compass/utilities/sprites/sprite_img/#mixin-sprite-column)

```compass
sprite-column(${1:\$col}, ${2:[\$width]}, ${3:[\$margin]})
```

######Set the width and height of an element to the original dimensions of an image before it was included in the sprite. [>>](http://compass-style.org/reference/compass/utilities/sprites/base/#mixin-sprite-dimensions)

```compass
sprite-dimensions(${1:\$map}, ${2:\$sprite})
```

######Sets all the rules for a sprite from a given sprite image to show just one of the sprites. [>>](http://compass-style.org/reference/compass/utilities/sprites/sprite_img/#mixin-sprite-img)

```compass
sprite-img(${1:\$img}, ${2:\$col}, ${3:[\$row]}, ${4:[\$width]}, ${5:[\$height]}, ${6:[\$margin]})
```

######Allows vertical and horizontal sprite positioning from a grid of equal dimensioned sprites. [>>](http://compass-style.org/reference/compass/utilities/sprites/sprite_img/#mixin-sprite-position)

```compass
sprite-position(${1:\$col}, ${2:[\$row]}, ${3:[\$width]}, ${4:[\$height]}, ${5:[\$margin]})
```

######Similar to 'sprite-replace-text-with-dimensions' but does not autmaticly set the demensions [>>](http://compass-style.org/reference/compass/utilities/sprites/sprite_img/#mixin-sprite-replace-text)

```compass
sprite-replace-text(${1:\$map}, ${2:\$sprite}, ${3:[\$dimensions]}, ${4:[\$offset-x]}, ${5:[\$offset-y]})
```

######Similar to 'replace-text-with-dimensions' but with sprites To use, create your sprite and then pass it in the $map param [>>](http://compass-style.org/reference/compass/utilities/sprites/sprite_img/#mixin-sprite-replace-text-with-dimensions)

```compass
sprite-replace-text-with-dimensions(${1:\$map}, ${2:\$sprite}, ${3:[\$offset-x]}, ${4:[\$offset-y]})
```

######Allows vertical sprite positioning optimized for a single column of sprites. [>>](http://compass-style.org/reference/compass/utilities/sprites/sprite_img/#mixin-sprite-row)

```compass
sprite-row(${1:\$row}, ${2:[\$height]}, ${3:[\$margin]})
```

######Include the position and (optionally) dimensions of this $sprite in the given sprite $map. [>>](http://compass-style.org/reference/compass/utilities/sprites/base/#mixin-sprite)

```compass
sprite(${1:\$map}, ${2:\$sprite}, ${3:[\$dimensions]}, ${4:[\$offset-x]}, ${5:[\$offset-y]}, ${6:[\$use-percentages]}, ${7:[\$use-magic-selectors]}, ${8:[\$separator]})
```

######Hides text in an element by squishing the text into oblivion. [>>](http://compass-style.org/reference/compass/typography/text/replacement/#mixin-squish-text)

```compass
squish-text()
```

######Must be mixed into the top level of your stylesheet. [>>](http://compass-style.org/reference/compass/layout/sticky_footer/#mixin-sticky-footer)

```compass
sticky-footer(${1:\$footer-height}, ${2:[\$root-selector]}, ${3:[\$root-footer-selector]}, ${4:[\$footer-selector]})
```

######shorthand to stretch element height and width [>>](http://compass-style.org/reference/compass/layout/stretching/#mixin-stretch)

```compass
stretch(${1:[\$offset-top]}, ${2:[\$offset-right]}, ${3:[\$offset-bottom]}, ${4:[\$offset-left]})
```

######stretch element width to specified left and right position [>>](http://compass-style.org/reference/compass/layout/stretching/#mixin-stretch-x)

```compass
stretch-x(${1:[\$offset-left]}, ${2:[\$offset-right]})
```

######stretch element height to specified top and bottom position [>>](http://compass-style.org/reference/compass/layout/stretching/#mixin-stretch-y)

```compass
stretch-y(${1:[\$offset-top]}, ${2:[\$offset-bottom]})
```

###T

######description [>>](http://compass-style.org/reference/compass/utilities/tables/scaffolding/#mixin-table-scaffolding)

```compass
table-scaffolding()
```

######Emits styles for a tag cloud [>>](http://compass-style.org/reference/compass/utilities/general/tag_cloud/#mixin-tag-cloud)

```compass
tag-cloud(${1:[\$base-size]})
```

######Provides cross-browser text shadows when one or more shadows are needed. [>>](http://compass-style.org/reference/compass/css3/text-shadow/#mixin-text-shadow)

```compass
text-shadow()
```

######Apply trailing whitespace. [>>](http://compass-style.org/reference/compass/typography/vertical_rhythm/#mixin-trailer)

```compass
trailer(${1:[\$lines]}, ${2:[\$font-size]}, ${3:[\$property]})
```

######Apply a trailing border. [>>](http://compass-style.org/reference/compass/typography/vertical_rhythm/#mixin-trailing-border)

```compass
trailing-border(${1:[\$width]}, ${2:[\$lines]}, ${3:[\$font-size]}, ${4:[\$border-style]})
```

######Transform sent as a complete string: [>>](http://compass-style.org/reference/compass/css3/transform/#mixin-transform)

```compass
transform(${1:\$transform}, ${2:[\$only3d]})
```

######Transform-origin sent as individual arguments: [>>](http://compass-style.org/reference/compass/css3/transform/#mixin-transform-origin)

```compass
transform-origin(${1:[\$origin-x]}, ${2:[\$origin-y]}, ${3:[\$origin-z]}, ${4:[\$only3d]})
```

######Determine whether a 3D objects children also live in the given 3D space [>>](http://compass-style.org/reference/compass/css3/transform/#mixin-transform-style)

```compass
transform-style(${1:[\$style]})
```

######Shortcut to target all browsers with 2D transform support [>>](http://compass-style.org/reference/compass/css3/transform/#mixin-transform2d)

```compass
transform2d(${1:\$trans})
```

######Shortcut to target only browsers with 3D transform support [>>](http://compass-style.org/reference/compass/css3/transform/#mixin-transform3d)

```compass
transform3d(${1:\$trans})
```

######description [>>](http://compass-style.org/reference/compass/css3/transition/#mixin-transition)

```compass
transition()
```

######One or more transition-delays in seconds [>>](http://compass-style.org/reference/compass/css3/transition/#mixin-transition-delay)

```compass
transition-delay()
```

######One or more durations in seconds [>>](http://compass-style.org/reference/compass/css3/transition/#mixin-transition-duration)

```compass
transition-duration()
```

######One or more properties to transition [>>](http://compass-style.org/reference/compass/css3/transition/#mixin-transition-property)

```compass
transition-property()
```

######One or more timing functions [>>](http://compass-style.org/reference/compass/css3/transition/#mixin-transition-timing-function)

```compass
transition-timing-function()
```

######Move an object along the x or y axis (2D) @include translate( [ translate-x, translate-y, perspective, 3D-only ] ) [>>](http://compass-style.org/reference/compass/css3/transform/#mixin-translate)

```compass
translate(${1:[\$translate-x]}, ${2:[\$translate-y]}, ${3:[\$perspective]}, ${4:[\$only3d]})
```

######Move an object along the x, y and z axis (3D) @include translate( [ translate-x, translate-y, translate-z, perspective ] ) [>>](http://compass-style.org/reference/compass/css3/transform/#mixin-translate3d)

```compass
translate3d(${1:[\$translate-x]}, ${2:[\$translate-y]}, ${3:[\$translate-z]}, ${4:[\$perspective]})
```

######Move an object along the x axis (2D) @include translate( [ translate-x, perspective, 3D-only ] ) [>>](http://compass-style.org/reference/compass/css3/transform/#mixin-translateX)

```compass
translateX(${1:[\$trans-x]}, ${2:[\$perspective]}, ${3:[\$only3d]})
```

######Move an object along the y axis (2D) @include translate( [ translate-y, perspective, 3D-only ] ) [>>](http://compass-style.org/reference/compass/css3/transform/#mixin-translateY)

```compass
translateY(${1:[\$trans-y]}, ${2:[\$perspective]}, ${3:[\$only3d]})
```

######Move an object along the z axis (3D) @include translate( [ translate-z, perspective ] ) [>>](http://compass-style.org/reference/compass/css3/transform/#mixin-translateZ)

```compass
translateZ(${1:[\$trans-z]}, ${2:[\$perspective]})
```

######Make an element completely transparent. [>>](http://compass-style.org/reference/compass/css3/opacity/#mixin-transparent)

```compass
transparent()
```

###U

######A hack to supply IE6 (and below) with a different property value. [>>](http://compass-style.org/reference/compass/utilities/general/hacks/#mixin-underscore-hack)

```compass
underscore-hack(${1:\$property}, ${2:\$value}, ${3:\$ie6-value})
```

######A link that looks and acts like the text it is contained within [>>](http://compass-style.org/reference/compass/typography/links/unstyled_link/#mixin-unstyled-link)

```compass
unstyled-link()
```

######This property controls the selection model and granularity of an element. [>>](http://compass-style.org/reference/compass/css3/user_interface/#mixin-user-select)

```compass
user-select(${1:\$select})
```

###W

######If passed a map, that will be the new browser ranges. [>>](http://compass-style.org/reference/compass/support/#mixin-with-browser-ranges)

```compass
with-browser-ranges(${1:\$capability}, ${2:[\$prefix]})
```

######Enable browser support debugging within the content block. [>>](http://compass-style.org/reference/compass/support/#mixin-with-browser-support-debugging)

```compass
with-browser-support-debugging()
```

######Yields to the mixin content once for each prefix required. [>>](http://compass-style.org/reference/compass/support/#mixin-with-each-prefix)

```compass
with-each-prefix(${1:\$capability}, ${2:\$threshold}, ${3:[\$capability-options]})
```

######If there's a prefix context in scope, this will only output the content if the prefix matches. [>>](http://compass-style.org/reference/compass/support/#mixin-with-prefix)

```compass
with-prefix(${1:\$prefix})
```

######Mixin for word-break properties http://www.w3.org/css3-text/#word-break * legal values for $type : normal, keep-all, break-all [>>](http://compass-style.org/reference/compass/css3/hyphenation/#mixin-word-break)

```compass
word-break(${1:[\$value]})
```
