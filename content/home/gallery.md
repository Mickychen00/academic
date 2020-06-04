+++
widget = "blank"
headless = true  # This file represents a page section.
active = false
weight = 40  # Order that this section will appear.
title = "My Photography"
[[gallery_item]]
	album = "1"
	image = "IMG_1.jpg"
	caption = "Default"
[[gallery_item]]
	album = "1"
	image = "IMG_2.jpg"
	caption = "Default1"
# ... Put Your Section Options Here (title etc.) ...

+++
{{< figure library="true" src="IMG_1.jpg" title="A caption" lightbox="true" >}}
{{< gallery album="1" >}}