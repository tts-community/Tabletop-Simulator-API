The Custom PDF is a type in-game Spawnable Object that renders a PDF from a URL. It has its own class, Book, with functions/members associated with it. This allows you to manipulate the special properties of a Custom PDF.

Example Usage: `obj.Book.setPage(1, false)`

##Member Variables

Like [Object member variables](object.md#member-variables), Books have their own member variables.

Variable | Description | Type
-- | -- | :--
<a class="anchor" id="page_offset"></a>page_offset | This number is added to the displayed page number when determining which page of the PDF to show.  | [<span class="tag int"></span>](types.md)

!!! info
    For example, if `page_offset` were set to 10, the first page in the UI would be 11, rather than 1. Negative numbers are accepted, and useful if a rule book contains a front cover, index etc. within the PDF file.

###Object Functions

Function Name | Description | Return | &nbsp;
-- | -- | -- | --:
<a class="anchor" id="getpage"></a>getPage([<span class="tag boo"></span>](types.md)&nbsp;offsetPageNumbering) | Gets the current page of the PDF. | [<span class="ret int"></span>](types.md) | [<span class="i"></span>](#getpage)
<a class="anchor" id="setpage"></a>setPage([<span class="tag int"></span>](types.md)&nbsp;page, [<span class="tag boo"></span>](types.md)&nbsp;offsetPageNumbering) | Set current page. | [<span class="ret boo"></span>](types.md)| [<span class="i"></span>](#setpage)
<a class="anchor" id="sethighlight"></a>setHighlight(x1, y1, x2, y2) | Set highlight box on current page. | [<span class="ret boo"></span>](types.md)
<a class="anchor" id="clearhighlight"></a>clearHighlight() | Clear highlight. | [<span class="ret boo"></span>](types.md)

---

####getPage(...)

[<span class="ret int"></span>](types.md)&nbsp; Gets the current page of the PDF.

!!! info "getPage(offsetPageNumbering)"
	  * [<span class="tag boo"></span>](types.md) **offsetPageNumbering**: Indicates whether or not [page_offset](#page_offset) should be applied to the page number returned.
        * {>>Optional, defaults to `false`.<<}
---

####setPage(...)

[<span class="ret boo"></span>](types.md)&nbsp; Sets the current page of the PDF. Returns true if the page was succesfully set, false if the page number was invalid.

!!! info "setPage(page, offsetPageNumbering)"
    * [<span class="tag int"></span>](types.md) **page**: The new page number.
    * [<span class="tag boo"></span>](types.md) **offsetPageNumbering**: Indicates whether or not [page_offset](#page_offset) should be applied to the page number set.
        * {>>Optional, defaults to `false`.<<}
