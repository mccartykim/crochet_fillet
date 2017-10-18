# Fillet Crochet Browser Toy
I was curious about fillet crochet, a type of crochet where an image or other pattern is created through lace, and noticed there wasn't a lot about fillet crochet in the round, and thought it was interesting how the craft resembled threshold or dithered images.
This tool tries to do a dithering sort-of like atkinson dithering on a flat crochet-in-the-round chart.

Parameters in url: `[domain+path]/index.html?src="URL_TO_IMAGE.JPG"&rows=40&basestitch=6&height=10&thresh=45`
* src: Path to image file
* rows: Number of rows in pattern
* base stitch: Number of stitches in first row, added to each subsequent row
* height: Height of each stitch
* thresh: Threshold percentage. Lower = Lighter image

This program is pretty slow.  I need to optimize it in some way.