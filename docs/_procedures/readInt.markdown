---
layout: default
title: ReadInt
summary: Read a signed integer to from input.
receives: None
returns: EAX
---
{% highlight asm %}
mov eax, number
call WriteDec
{% endhighlight %}