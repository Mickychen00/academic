+++
widget = "blank"
headless = true  # This file represents a page section.
active = true
weight = 40  # Order that this section will appear.
title = "My Photography"
[[gallery_item]]
album = "1"
image = "IMG_1.jpg"
caption = "Default"

[content]
	{{< gallery album="1" >}}
# ... Put Your Section Options Here (title etc.) ...

+++