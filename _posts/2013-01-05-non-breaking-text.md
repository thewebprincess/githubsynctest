---
ID: 877
post_title: >
  Super/Duper/Long/NonBreaking/Path/Name/To/A/File/That/Is/Way/Deep/Down/In/Some/Mysterious/Remote/Desolate/Part/Of/The/Operating/System/To/A/File/That/Just/So/Happens/To/Be/Strangely/Named/Supercalifragilisticexpialidocious.txt
author: ""
post_date: 2013-01-05 12:00:59
post_excerpt: ""
layout: post
permalink: >
  http://githubsync.dev/2013/01/05/non-breaking-text/
published: true
---
Super/Duper/Long/NonBreaking/Path/Name/To/A/File/That/Is/Way/Deep/Down/In/Some/Mysterious/Remote/Desolate/Part/Of/The/Operating/System/To/A/File/That/Just/So/Happens/To/Be/Strangely/Named/Supercalifragilisticexpialidocious.txt

A few things to check for:
<ul>
	<li>Non-breaking text in the title, content, and comments should have no adverse effects on layout or functionality.</li>
	<li>Check the browser window / tab title.</li>
	<li>If you are a plugin or widget developer, check that this text does not break anything.</li>
</ul>
The following CSS properties will help you support non-breaking text.
<pre>-ms-word-wrap: break-word;
word-wrap: break-word;</pre>