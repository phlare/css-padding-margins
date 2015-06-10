#css-padding-margins
really simple less / css utility for adding padding and/or margins to things using classes. useful as a common import, or as an extra on top of your favorite reset css.

Especially useful for LESS users, but the concept carries well.

I personally use it on top of bootstrap and find it saves me a lot of time.

##The gist
a three-letter acronym class can be added to any block element to easily add either padding or margin (or both).

####Type
* p -> padding
* m -> margin

####Position
* t -> top
* r -> right
* b -> bottom
* l -> left
* h -> horizontal (right and left)
* v -> vertical (top and bottom)
* a -> all

####Size
(configurable in .less version)

* g -> giant (default: 36px)
* l -> large (default: 24px)
* m -> medium (default: 16px)
* s -> small (default: 8px)
* t -> tiny (default: 4px;)
* n -> none

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