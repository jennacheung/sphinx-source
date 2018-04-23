=============
源代码
=============

代码文本块由末尾有特殊标记 :: 的段落引发。
整个代码文本块必须缩进 (同所有的段落一样,使用空白行和周围文本完成分隔):

This is a normal text paragraph. The next paragraph is a code sample::

   It is not processed in any way, except
   that the indentation is removed.

   It can span multiple lines.

This is a normal text paragraph again.

:: 标记是智能处置的:

* 如果作为一个独立段落出现,则和其它文本完全隔离
* 如果它紧跟有空格,则将被删除不起作用
* 如果它在非空白字符之前,则替换为普通的单一冒号

