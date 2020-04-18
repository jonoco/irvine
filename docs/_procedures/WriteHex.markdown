---
layout: default
title: WriteHex
summary: Writes a 32-bit unsigned integer to output in 8-digit hexidecimal.
receives: EAX = integer
returns: None
---
{% highlight asm %}
mov  eax,7FFFh
call WriteHex       ; displays: "00007FFF"
{% endhighlight %}