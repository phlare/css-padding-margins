css-padding-margins
====================

really basic less / css utility for adding padding and/or margins to things using classes

##The gist
a three-letter acronym class can be added to any block element to easy add either padding or margin

####Type
p -> padding
m -> magin

####Position
t -> top
r -> right
b -> bottom
l -> left
h -> horizontal (left and right)
v -> vertical (top and bottom)
a -> all (top)

####Size
default sizes listed, and available as variables in the .less format
adjust as fits your theme, and feel free to conver to em or whatever suits your use case.
```
@positioning-tiny: 4px;
@positioning-small: 8px;
@positioning-medium: 16px;
@positioning-large: 24px;
@positioning-giant: 36px;
```
g -> giant
l -> large
m -> medium
s -> small
n -> none

###Examples:
A simple div with medium-sized margin-top
```
<div class="mtm"></div>
```

A simple div with large horizontal padding (padding on both right and left sides)
```
<div class="phl"></div>
```

A div with no margins at all
```
<div class="man"></div>
```