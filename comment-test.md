
### MarkdownTesting

# Comment Test

This file is an example of (code) "comments" in Markdown
as suggested by the StackOverflow question/answer/comments 
[Comments in markdown](https://stackoverflow.com/questions/4823468/comments-in-markdown).

The next paragraph/line is prefixed with "[comment]: <> ".

[comment]: <> This is possibly a comment prefixed paragraph.

The next paragraph/line is prefixed with "[//]: <> ".

[//]: <> This is possibly a comment prefixed paragraph.

The next paragraph/line is prefixed with "[//]: # ".

[//]: # This is possibly a comment prefixed paragraph.

The next paragraph/line is surrounded with dash arrows like '<!---' and '-->'.
It is suggested for Vim [Instant-Markdown](https://github.com/suan/vim-instant-markdown) use.

<!---
This is a dash-arrow surrounded paragraph.
-->

The next paragraph/line is commented in Jekyll or octopress style like '{% comment %}' and '{% endcomment %}'.

{% comment %}
This is a Jekyll/octopress style comment.
{% endcomment %}

The empty-text hyperlink comment seems like an excellent approach.  The next paragraph/line is an example.

[](Comment text example in an empty-text hyperlink.)

The comments in the StackOverflow discussion concerning the use of comments for 
document metadata are possibly worth considering for specific usage scenarios.

There are a number of other possible scenarios not yet covered in this test file
that are described in the StackOverflow linked page.