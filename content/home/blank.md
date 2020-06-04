+++
widget = "blank"
headless = true  # This file represents a page section.
active = true
weight = 40  # Order that this section will appear.
title = "My Photography"

# ... Put Your Section Options Here (title etc.) ...

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

[content]
{{< gallery >}}


gallery_item:
 - album: gallery
   image: IMG_1.jpg
   caption: A caption
 - album: gallery
   image: IMG_2.jpg
   caption: Another caption
+++