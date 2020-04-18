---
layout: default
title: CloseFile
summary: Creates a new disk file for writing in output mode.
receives: EDX = address of filename
returns: EAX = file handle if successful, or INVALID_HANDLE_VALUE if not
---
{% highlight nasm %}
.data
filename BYTE "newfile.txt",0

.code
mov  edx,OFFSET filename
call CreateOutputFile
{% endhighlight %}