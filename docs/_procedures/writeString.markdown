---
layout: default
title: WriteString
summary: Displays a string to output.
receives: EDX
returns: None
---
{% highlight asm %}
mov edx, offset myString
call WriteString
{% endhighlight %}