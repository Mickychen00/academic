+++
widget = "blank"
headless = true  # This file represents a page section.
active = true
weight = 60  # Order that this section will appear.
title = "My Photography"
[design]
	columns = "2"
# [[gallery_item]]
# 	album = "1"
# 	image = "IMG_1.jpg"
# 	caption = "Default"
# [[gallery_item]]
# 	album = "1"
# 	image = "IMG_2.jpg"
# 	caption = "Default1"
# ... Put Your Section Options Here (title etc.) ...
[design.spacing]
padding = [ "20px", "0", "50px", "0" ]
[design.background]
color = "white"


+++
{{< gallery caption-position="none" dir="./img" />}} {{< load-photoswipe >}}