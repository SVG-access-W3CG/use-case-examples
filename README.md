# use-case-examples
SVG documents for messing around with. The primary purpose of these is to figure out the relevant use cases, 
and how to meet them - or what is lacking in SVG at the moment to do so.

Please feel free to make pull requests on this readme (I don't do markdown very well) or on the files themselves.

The general approach you should take is to pick a file from here, or somewhere else, and start working on it. Making a new directory for the file is handy, and please provide a version of the code inline in an HTML document. Please also document what you did in a file called <var>notes.html</var>.

We are also trying to tracking this work through the [W3C SVG wiki](https://www.w3.org/wiki/SVG_Accessibility) - but feel free to help bring that up to date because it probably isn't.

So far a handful of images have been worked up to the point where we would really like <a href="http://github.com/SVG-access-W3CG/use-case-examples/issues">issues filed</a>:

<dl>
 <dt>beaker</dt>
 <dd><a href="beaker.html">beaker.html</a> is an animated diagram demonstrating a science principle. It uses SVG animation - <code>animate</code> and <code>set</code> elements for most of the interactivity and dynamic update, and <code>aria-live</code> to communicate some of what's going on to screen readers. See also <a href="beaker-notes.html">notes on the beaker exercise</a></dd>
 <dt>composed-tree</dt>
  <dd><a href="composed-tree.svg">composed-tree.svg</a> is a tree diagram - a <a href="composed-tree-desc.html">more detiled description</a> is available. There is also a <a href="composed-tree.html">version as HTML with SVG code inline</a> and some <a href="composed-tree-notes.html">notes about the changes and lessons learned</a>.</dd>
  <dd>The original image came from the <a href="https://w3c.github.io/webcomponents/spec/shadow">W3C draft Shadow DOM specification</a>. Hopefully the improvements made here translate to an improvement in that document's accessibility.</dd>
 <dt>hc-chart</dt>
  <dd>A <a href="hc-chart/notes.html">couple of different versions</a> of the SVG chart exported from <a href="http://highcharts.com">Highcharts.com</a>'s <a href="">example accessible line graph</a> since the exported version doesn't include their accessibility features.</dd>
 <dt>sparse-chord</dt>
  <dd><a href="sparse-chord.svg">sparse-chord.svg</a> is a graph that links things shown in 2 individual bar charts to each other.</dd>
  <dd>[Notes about the changes and lessons](sparse-chord-notes.html) are pretty sparse, and we welcome additional testing results</dd>
 <dt>rectrack2.svg is a flowchart with various loops</dt>
  <dd><a href="revisedrec2.svg">revisedrec2</a> is a proposed replacement for <a href="revisedrec.svg">revisedrec</a> which is part of the W3c process document. <a href="rectrack-notes.html">Notes about this set of diagrams</a> are a bit sparse, and we welcome additional testing results</dd>
</dl>

There are a couple of images that are being worked on, but are known to be buggy. We would love people to fork them and file Pull Requests for suggesting improvements...
<dl>
 <dt>chem-BV-ox</dt>
  <dd><a href="chem-BV-ox.svg">chem-BV-ox.svg</a> presents a chemical reaction, using a graphical representation familiar to who work with organic chemistry. This is still very much a work in progress.</dd>
 <dt>chord</dt>
  <dd><a href="chord.svg">chord.svg</a> is a pretty complex graph. A <a href="https://www.w3.org/wiki/SVG_Accessibility/Cool_Graphs#uc-chord">description is available</a>.</dd>
  <dd><a href="chord-notes.html">Notes about the changes and lessons</a> are pretty sparse, and we welcome additional testing results.</dd>
 <dt>revisedrec</dt>
  <dd><a href="revisedrec.svg">revisedrec.svg</a> is a flowchart between 5 explicit states and one implicit state, with a number of loops. I started to work it up, and then took what I had done to create <a href="rectrack2.svg">rectrack2.svg</a>. At some point the changes should be backported to finish this, because the diagrams are used in the W3C Process document.</dd>
</dl>
