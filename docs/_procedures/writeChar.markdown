---
layout: default
title: WriteChar
summary: Displays a character to the output.
receives: AL = character
returns: None
---
{% highlight nasm %}
mov  al, '+'
call WriteChar
{% endhighlight %}