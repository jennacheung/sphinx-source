===============
列表和引用块
===============

-------------
列表
-------------
在段落的开始放置一个星号并正确缩进. 这同样适用于带编号的列表;

也可以使用``#``签署自动编号::

    * This is a bulleted list.
    * It has two items, the second
    item uses two lines.

    1. This is a numbered list.
    2. It has two items too.

    #. This is a numbered list.
    #. It has two items too.

允许嵌套列表但必须用空行同父列表分离开::

    * this is
    * a list

        * with a nested list
        * and some subitems

    * and here the parent list continues

---------------
引用块
---------------
创建引用段落只需要用缩进和其它段落区分即可.

线块 (ref) 是保留换行符的一种方法::

    | These lines are
    | broken exactly like in
    | the source file.

更多内容参考：
http://docutils.sourceforge.net/docs/ref/rst/restructuredtext.html#hyperlink-targets




   