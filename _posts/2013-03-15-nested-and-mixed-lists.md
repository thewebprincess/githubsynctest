---
ID: 1000
post_title: Nested And Mixed Lists
author: ""
post_date: 2013-03-15 14:48:32
post_excerpt: ""
layout: post
permalink: >
  http://githubsync.dev/2013/03/15/nested-and-mixed-lists/
published: true
---
Nested and mixed lists are an interesting beast. It's a corner case to make sure that
<ul>
	<li>Lists within lists do not break the ordered list numbering order</li>
	<li>Your list styles go deep enough</li>
</ul>
<h3>Ordered - Unordered - Ordered</h3>
<ol>
	<li>ordered item</li>
	<li>ordered item
<ul>
	<li><strong>unordered</strong></li>
	<li><strong>unordered</strong>
<ol>
	<li>ordered item</li>
	<li>ordered item</li>
</ol>
</li>
</ul>
</li>
	<li>ordered item</li>
	<li>ordered item</li>
</ol>
<h3>Ordered - Unordered - Unordered</h3>
<ol>
	<li>ordered item</li>
	<li>ordered item
<ul>
	<li><strong>unordered</strong></li>
	<li><strong>unordered</strong>
<ul>
	<li>unordered item</li>
	<li>unordered item</li>
</ul>
</li>
</ul>
</li>
	<li>ordered item</li>
	<li>ordered item</li>
</ol>
<h3>Unordered - Ordered - Unordered</h3>
<ul>
	<li>unordered item</li>
	<li>unordered item
<ol>
	<li>ordered</li>
	<li>ordered
<ul>
	<li>unordered item</li>
	<li>unordered item</li>
</ul>
</li>
</ol>
</li>
	<li>unordered item</li>
	<li>unordered item</li>
</ul>
<h3>Unordered - Unordered - Ordered</h3>
<ul>
	<li>unordered item</li>
	<li>unordered item
<ul>
	<li>unordered</li>
	<li>unordered
<ol>
	<li><strong>ordered item</strong></li>
	<li><strong>ordered item</strong></li>
</ol>
</li>
</ul>
</li>
	<li>unordered item</li>
	<li>unordered item</li>
</ul>