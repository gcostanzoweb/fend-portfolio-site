# FEND Nanodegree "Portfolio Website" Project
"Portfolio Website" project for the FEND Google Developer Nanodegree 

The code has been reviewed to respect the project's guidelines. 
Responsiveness using the `flexbox` display method has been achieved in the following way:
1. Ensuring the flex box has a `flex-wrap` value of `wrap`
2. Assigning a default `flex-basis` for items inside flex boxes
3. Setting a value of 1 for `flex-grow`
4. Assigning a maximum width where needed
This way, the items won't be stretched in an unexpected behaviour, but instead will wrap accordingly to their minimum and maximum width.

In addition, the following tweaks were added:
- shorthands were used where possible (i.e. `flex` instead of `flex-grow`, `flex-shrink` and `flex-basis` independently)
- media queries for the CSS to use in `meta` tags in the index's `head`
- three sizes: small, medium, large
- use of `srcset` to apply limited-resolution images on smaller screens
- on-hover effects in the boxes for the projects
- personalized images, logo and titles / description
- while waiting for completing more FEND projects, old ones on Github were used as placeholder
- style customization for borders, colors, text effects, etc.
