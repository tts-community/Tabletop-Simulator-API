The Custom PDF is a type in-game Spawnabble Object that renders a PDF from a URL. It has its own class, Book, with functions/members associated with it. This allows you to manipulate the special properties of a Custom PDF.

Example Usage: `ojb.Book.setPage(page, offsetPageNumbering = false)`

##Member Variables

Like [Object member variables](object.md#member-variables), Books have their own member variables.

Variable | Description | Type
-- | -- | :--
<a class="anchor" id="page_offset"></a>page_offset | Offset virtual book numbers are from numbers rendered on pages. | [<span class="tag int"></span>](types.md)

###Object Functions

Function Name | Description | Return | &nbsp;
-- | -- | -- | --:
<a class="anchor" id="getpage"></a>getPage([<span class="tag boo"></span>](types.md)&nbsp;offsetPageNumbering = false) | Offset virtual book numbers are from numbers rendered on pages. | [<span class="ret int"></span>](types.md)
<a class="anchor" id="setpage"></a>setPage([<span class="tag int"></span>](types.md)&nbsp;page, [<span class="tag bool"></span>](types.md)&nbsp;offsetPageNumbering = false) | Set current page. | [<span class="ret boo"></span>](types.md)
<a class="anchor" id="sethighlight"></a>setHighlight(x1, y1, x2, y2) | Set highlight box on current page. | [<span class="ret boo"></span>](types.md)
<a class="anchor" id="clearhighlight"></a>clearHighlight() | Clear highlight. | [<span class="ret boo"></span>](types.md)
