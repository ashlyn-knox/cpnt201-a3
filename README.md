#CPNT201-A3 SVG Optimization
github repo: https://github.com/ashlyn-knox/cpnt201-a3
gitup pages: https://ashlyn-knox.github.io/cpnt201-a3

## Project Overview
* Lavapad is a ficticious device that is meant to auto connect the user to any open wifi network within a 1km radius. It has a setting to create an array of non-existent IP addresses to create a fake tor like network. The user's actual IP address is masked as the user can hop between these different aliases. Not an overly legal device... but a fun concept.
* I started reviewing the material guidelines for design when I began this project. The approach to shadow on hover etc is all based on those readings. My goal with this particular site is to improve my ability to use a consistent theme and adhere to a stylesheet. All future work on this site will include improvements to that goal and specifically relate to the material.io manual of style.

### Animation on Load
Keyframe Animation on load: the main logo in the hero section has been set up using keyframes. This will be replaced with javascript for cpnt262.

The long term goal for this animation is that the red color will spark through the site navigation on desktop.

Getting the dot to stay in its place when scaling required a little research to learn how svgs react to transforms.

* HTML: line 78
* CSS: Line 324

### Text Logo Animation
My partner Mandi designed this one, we wanted to see what our workflow would be like between her designing in illustrator and sending me the file and if I would have any extra hassles working with it in figma. The illustrator made files seemed to create a lot more code.

This svg uses a blur filter on half of the text and the other half changes colour. the whole thing scales up on hover as well.
* HTML: Line 33
* CSS: Line 305

### Dark Mode Logo
This was really fun to make. I didn't like how the border box theming applied to the text logo, so I tried applying it to the dark mode using an inverted shadow colour. This logo scales, uses the same animation styling as the navigation links for a consistent theme, and uses a high contrast filter on all the svg elements.
* HTML: 104
* CSS: 411

## Attributions
* Lavapad logos by [Ashlyn Knox](https://github.com/ashlyn-knox) license under a [MIT License](https://mit-license.org/)
* Text Logo designed by [Mandi Schrader](https://www.facebook.com/idnami/)no license
* [Google Fonts]
* [Material Design Icons](https://material.io/resources/icons/?style=baseline) by [Google](https://google.com) licensed under [Apache license version 2.0](https://www.apache.org/licenses/LICENSE-2.0.html)
* [Material Design box shadow code](https://codepen.io/sdthornton/pen/wBZdXq) by [Samuel Thornton](https://codepen.io/sdthornton)

