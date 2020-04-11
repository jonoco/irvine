---
layout: default
title: WriteDec
summary: Displays an unsigned integer to output.
receives: EAX
returns: None
---
{% highlight asm %}
mov eax, number
call WriteDec
{% endhighlight %}