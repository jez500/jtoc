jToc - jQuery/Jeremy's Table of Contents
========================================

Builds a table of contents based on headings on the page.

Usage
-----
Call on a ul/ol and it will get populated with TOC links.

Example
-------
```
$('ul.toc').jtoc({content: '.content', headings: 'h2,h3'});
```

Options
-------
- content: The selector to search for headings in. Default: 'body'
- headings: Headings to search for. Default: "h1,h2,h3"
- anchorPrefix: Optionally add a prefix to anchors.
- scrollEnabled: Should there be smooth scrolling to headings. Default true
- scrollSpeed: Speed of animation when scrolling to headings. Default 400
- scrollEase: Scroll animation. Default: 'swing'
- scrollEl: The element that scrolls. Default: 'body,html'
- scrollOffset: A pixel offset for scroll. Default 0

Credits/Authors
---------------
Full credit goes to original authors here:

- https://github.com/firstandthird/smooth-scroller
- https://github.com/ndabas/toc
- https://github.com/jgallen23/toc

I simply merged functionality from all of these projects, refactored a bit and added a few extra features.

