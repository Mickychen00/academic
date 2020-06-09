+++
widget = "blank"
headless = true  # This file represents a page section.
active = true
weight = 40  # Order that this section will appear.
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


+++
{{< figure library="true" src="IMG_1.jpg" title="A caption" lightbox="true" >}}
{{< figure library="true" src="IMG_2.jpg" title="A caption" lightbox="true" >}}
{{< figure library="true" src="IMG_3.jpg" title="A caption" lightbox="true" >}}
{{< figure library="true" src="IMG_4.jpg" title="A caption" lightbox="true" >}}
{{< figure library="true" src="IMG_5.jpg" title="A caption" lightbox="true" >}}
{{< figure library="true" src="IMG_6.jpg" title="A caption" lightbox="true" >}}
{{< figure library="true" src="IMG_7.jpg" title="A caption" lightbox="true" >}}
{{< gallery dir="/static/img/" />}} {{< load-photoswipe >}}