jQuery.sortable
===============

A jQuery plugin to drag, drop and sort elements

##How to use##

```js
$('#container div').sortable();
```

###Parameters###
* anchor: the zone to click to select the element. Default: the element. Can be restricted to a smaller zone using CSS selectors.
* axis: direction in which the dragging is limited. Default: none. Can be 'x' or 'y'.
* dropArea: where the dragged element can be dropped. Default: parent element. Can be extended using CSS selectors.
* showContent: whether to show the content of the element while dragging or not. Default: true.

###CSS classes###
* anchor: class applied to the drag anchor. See the anchor parameter above.
* dragged: class applied to a dragged element.
* target: class applied to the target area.
* overlay: class applied to the dragged element when ```showContent == false```.

##License##
Copyright (c) 2010, rohm1 <rp@rohm1.com>.
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions
are met:

* Redistributions of source code must retain the above copyright
notice, this list of conditions and the following disclaimer.

* Neither the name of rohm1 nor the names of his
contributors may be used to endorse or promote products derived
from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
"AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT
LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS
FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE
COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT,
INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING,
BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT
LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN
ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE
POSSIBILITY OF SUCH DAMAGE.