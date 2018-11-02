# LSD
## Show a subset of the most recent files in a directory

Given a directory, show the most recent N files. The list is also copied to the clipboard.

Usage: `lsd directory number-of-files`

<hr>

Dump out most recent download:
<pre>cat `lsd ~/Downloads 1` </pre>

Copy two most recent downloads to current directory:
<pre>cp `lsd ~/Downloads/ 2` .</pre>

<hr>

The name is a portmanteau of `ls` and `date`.



