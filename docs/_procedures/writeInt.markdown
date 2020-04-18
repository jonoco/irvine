---
layout: default
title: WriteInt
summary: Displays a 32-bit signed integer to output.
receives: EAX = integer
returns: None
---
{% highlight nasm %}
mov  eax,216543
call WriteInt       ; displays: "+216543"
{% endhighlight %}