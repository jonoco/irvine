---
layout: default
title: WriteDec
summary: Displays a 32-bit unsigned integer to output.
receives: EAX = integer
returns: None
categories: general
---
{% highlight asm %}
mov  eax, 256
call WriteDec
{% endhighlight %}