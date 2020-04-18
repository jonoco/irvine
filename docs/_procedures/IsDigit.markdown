---
layout: default
title: IsDigit
summary: Determines whether the value in AL is the ASCII code for a valid decimal digit.
receives: AL = character
returns: Zero flag is set if valid digit, else clear
---
{% highlight nasm %}
mov  AL,somechar
call IsDigit
{% endhighlight %}