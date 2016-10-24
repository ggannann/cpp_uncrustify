# cpp_uncrustify
This is modified version of https://gist.github.com/mkroman/1372117

Modifications:
* Not using relalignment when over 80 chars on a row, because when had comments, there was a bug, that on every save, new break was added.
* Using 120 chars per line, because noone has 80 chars per line and automatic breaking makes code sometimes too ugly
