# use-case-examples
SVG documents for messing around with. The primary purpose of these is to figure out the relevant use cases, 
and how to meet them - or what is lacking in SVG at the moment to do so.

Please feel free to make pull requests on this readme (I don't do markdown very well) or on the files themselves.

The key thing is to explain in your comments why your change makes the thing more accessible, and to whom.

We are tracking this through the [W3C SVG wiki](https://www.w3.org/wiki/SVG_Accessibility)

So far a couple of images have been worked up to the point where we would really like issues filed:

;composed-tree
:[composed-tree.svg](composed-tree.svg) is a tree diagram, as per the [description](composed-tree-desc.html). There is also a version as [HTML with SVG code inline](composed-tree.html) and some [notes about the changes and lessons](composed-tree-notes.html).
:The original image came from the [W3C draft Shadow DOM specification](https://w3c.github.io/webcomponents/spec/shadow). Hopefully the improvements made here translate to an improvement in that document's accessibility.
;sparse-chord
:[sparse-chord.svg](sparse-chord.svg) is a graph that links things shown in 2 individual bar charts to each other.
:[Notes about the changes and lessons](sparse-chord-notes.html) are pretty sparse, and we welcome additional testing results

There are a couple of images that are being worked on, but are known to be buggy. We would love people to fork them and file Pull Requests for suggesting improvements...
;chem-BV-ox
:[chem-BV-ox.svg](chem-BV-ox.svg) presents a chemical reaction, using a graphical representation familiar to who work with organic chemistry. This is still very much a work in progress.
;chord
:[chord.svg](chord.svg) is a pretty complex graph. A [description of the image](https://www.w3.org/wiki/SVG_Accessibility/Cool_Graphs#uc-chord) is available
:[Notes about the changes and lessons](sparse-chord-notes.html) are pretty sparse, and we welcome additional testing results
