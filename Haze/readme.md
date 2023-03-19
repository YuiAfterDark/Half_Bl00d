# Haze

### Info

Released: 2022-Jul-22

Private forum link: https://myanimelist.net/forum/?topicid=1997232

### Blurb

This design is based on an [earlier one](https://halfblood.rf.gd/lshiirol/watching.html) made as a commission, by changing it into a row structure instead of the grid. The main goal was to somehow make it usable with all the columns turned on, but also flexible enough so it doesn't break if any are turned off. Half Blood made that using the display: flex; property on the columns, so that they automatically stack depending on their predetermined order, and if any are missing, another one would just take its place, as well as introducing a second "page" for the columns which appears on hover of the small "More" button on the top left above the image.

### Feature List
- Adapts to all list columns hopefully without breaking. It can handle all of them being turned on without a problem.
- Supports anime and manga lists equally.
- Supports default background image and cover image uploaders for users that still desire to add them.
- Sorting list automatically adapts dimensions based on which columns are turned on/off.
