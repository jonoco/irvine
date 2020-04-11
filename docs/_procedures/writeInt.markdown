---
layout: default
title: WriteInt
summary: Displays a signed integer to output.
receives: EAX
returns: None
---
{% highlight asm %}
mov eax, number
call WriteDec
{% endhighlight %}