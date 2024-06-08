#### Here is a comprehensive cheat sheet for JavaScript Element objects:

**Properties:**

1. `accessKey`: Sets or retrieves the access key for the element.
   - Returns: `string`
   - Returns if no results: `null`
2. `attributes`: Returns a collection of attributes for the element.
   - Returns: `NamedNodeMap`
   - Returns if no results: `null`
3. `childElementCount`: Returns the number of child elements for the element.
   - Returns: `number`
   - Returns if no results: `0`
4. `childNodes`: Returns a collection of child nodes for the element.
   - Returns: `NodeList`
   - Returns if no results: `[]`
5. `children`: Returns a collection of child elements for the element.
   - Returns: `HTMLCollection`
   - Returns if no results: `[]`
6. `className`: Sets or retrieves the class name for the element.
   - Returns: `string`
   - Returns if no results: `""`
7. `clientHeight`: Returns the height of the element's content area.
   - Returns: `number`
   - Returns if no results: `0`
8. `clientLeft`: Returns the width of the left border of the element.
   - Returns: `number`
   - Returns if no results: `0`
9. `clientTop`: Returns the height of the top border of the element.
   - Returns: `number`
   - Returns if no results: `0`
10. `clientWidth`: Returns the width of the element's content area.
    - Returns: `number`
    - Returns if no results: `0`
11. `contentEditable`: Sets or retrieves whether the element is editable.
    - Returns: `string`
    - Returns if no results: `""`
12. `dataset`: Returns a collection of custom data attributes for the element.
    - Returns: `DOMStringMap`
    - Returns if no results: `{}`
13. `dir`: Sets or retrieves the direction of the element's text.
    - Returns: `string`
    - Returns if no results: `""`
14. `firstChild`: Returns the first child node of the element.
    - Returns: `Node`
    - Returns if no results: `null`
15. `firstElementChild`: Returns the first child element of the element.
    - Returns: `Element`
    - Returns if no results: `null`
16. `hidden`: Sets or retrieves whether the element is hidden.
    - Returns: `boolean`
    - Returns if no results: `false`
17. `id`: Sets or retrieves the ID of the element.
    - Returns: `string`
    - Returns if no results: `""`
18. `innerHTML`: Sets or retrieves the HTML content of the element.
    - Returns: `string`
    - Returns if no results: `""`
19. `innerText`: Sets or retrieves the text content of the element.
    - Returns: `string`
    - Returns if no results: `""`
20. `isContentEditable`: Returns whether the element is editable.
    - Returns: `boolean`
    - Returns if no results: `false`
21. `lang`: Sets or retrieves the language of the element.
    - Returns: `string`
    - Returns if no results: `""`
22. `lastChild`: Returns the last child node of the element.
    - Returns: `Node`
    - Returns if no results: `null`
23. `lastElementChild`: Returns the last child element of the element.
    - Returns: `Element`
    - Returns if no results: `null`
24. `localName`: Returns the local name of the element.
    - Returns: `string`
    - Returns if no results: `""`
25. `namespaceURI`: Returns the namespace URI of the element.
    - Returns: `string`
    - Returns if no results: `""`
26. `nextElementSibling`: Returns the next sibling element of the element.
    - Returns: `Element`
    - Returns if no results: `null`
27. `nextSibling`: Returns the next sibling node of the element.
    - Returns: `Node`
    - Returns if no results: `null`
28. `nodeName`: Returns the name of the element.
    - Returns: `string`
    - Returns if no results: `""`
29. `nodeType`: Returns the type of the element.
    - Returns: `number`
    - Returns if no results: `1` (Element node type)
30. `nodeValue`: Returns the value of the element.
    - Returns: `string`
    - Returns if no results: `""`
31. `offsetHeight`: Returns the height of the element, including borders and padding.
    - Returns: `number`
    - Returns if no results: `0`
32. `offsetLeft`: Returns the left offset of the element, including borders and padding.
    - Returns: `number`
    - Returns if no results: `0`
33. `offsetParent`: Returns the offset parent element of the element.
    - Returns: `Element`
    - Returns if no results: `null`
34. `offsetTop`: Returns the top offset of the element, including borders and padding.
    - Returns: `number`
    - Returns if no results: `0`
35. `offsetWidth`: Returns the width of the element, including borders and padding.
    - Returns: `number`
    - Returns if no results: `0`
36. `outerHTML`: Sets or retrieves the outer HTML of the element.
    - Returns: `string`
    - Returns if no results: `""`
37. `outerText`: Sets or retrieves the outer text of the element.
    - Returns: `string`
    - Returns if no results: `""`
38. `ownerDocument`: Returns the document object that owns the element.
    - Returns: `Document`
    - Returns if no results: `null`
39. `parentElement`: Returns the parent element of the element.
    - Returns: `Element`
    - Returns if no results: `null`
40. `parentNode`: Returns the parent node of the element.
    - Returns: `Node`
    - Returns if no results: `null`
41. `prefix`: Returns the namespace prefix of the element.
    - Returns: `string`
    - Returns if no results: `""`
42. `previousElementSibling`: Returns the previous sibling element of the element.
    - Returns: `Element`
    - Returns if no results: `null`
43. `previousSibling`: Returns the previous sibling node of the element.
    - Returns: `Node`
    - Returns if no results: `null`
44. `scrollHeight`: Returns the height of the element's scrollable area.
    - Returns: `number`
    - Returns if no results: `0`
45. `scrollLeft`: Returns the left scroll position of the element.
    - Returns: `number`
    - Returns if no results: `0`
46. `scrollTop`: Returns the top scroll position of the element.
    - Returns: `number`
    - Returns if no results: `0`
47. `scrollWidth`: Returns the width of the element's scrollable area.
    - Returns: `number`
    - Returns if no results: `0`
48. `spellcheck`: Sets or retrieves whether the element is spell-checked.
    - Returns: `string`
    - Returns if no results: `""`
49. `style`: Returns the style object of the element.
    - Returns: `CSSStyleDeclaration`
    - Returns if no results: `null`
50. `tabIndex`: Sets or retrieves the tab index of the element.
    - Returns: `number`
    - Returns if no results: `0`
51. `tagName`: Returns the tag name of the element.
    - Returns: `string`
    - Returns if no results: `""`
52. `textContent`: Sets or retrieves the text content of the element.
    - Returns: `string`
    - Returns if no results: `""`
53. `title`: Sets or retrieves the title of the element.
    - Returns: `string`
    - Returns if no results: `""`

**Methods:**

1. `addEventListener()`: Adds an event listener to the element.
   - Returns: `void`
2. `appendChild()`: Adds a new child node to the element.
   - Returns: `Node`
3. `cloneNode()`: Creates a copy of the element.
   - Returns: `Node`
4. `compareDocumentPosition()`: Compares the position of the element in the document.
   - Returns: `number`
5. `contains()`: Returns whether the element contains another element.
   - Returns: `boolean`
6. `dispatchEvent()`: Dispatches an event to the element.
   - Returns: `boolean`
7. `getAttribute()`: Returns the value of an attribute of the element.
   - Returns: `string`
8. `getAttributeNode()`: Returns the attribute node of the element.
   - Returns: `Attr`
9. `getElementsByTagName()`: Returns a collection of elements with a specified tag name.
   - Returns: `HTMLCollection`
10. `getElementsByTagNameNS()`: Returns a collection of elements with a specified tag name and namespace.
    - Returns: `HTMLCollection`
11. `hasAttribute()`: Returns whether the element has a specified attribute.
    - Returns: `boolean`
12. `hasAttributeNS()`: Returns whether the element has a specified attribute and namespace.
    - Returns: `boolean`
13. `hasChildNodes()`: Returns whether the element has child nodes.
    - Returns: `boolean`
14. `insertAdjacentElement()`: Inserts an element at a specified position.
    - Returns: `Element`
15. `insertAdjacentHTML()`: Inserts HTML at a specified position.
    - Returns: `void`
16. `insertAdjacentText()`: Inserts text at a specified position.
    - Returns: `void`
17. `matches()`: Returns whether the element matches a specified selector.
    - Returns: `boolean`
18. `normalize()`: Normalizes the text nodes of the element.
    - Returns: `void`
19. `querySelector()`: Returns the first element that matches a specified selector.
    - Returns: `Element`
20. `querySelectorAll()`: Returns a collection of elements that match a specified selector.
    - Returns: `NodeList`
21. `removeAttribute()`: Removes an attribute from the element.
    - Returns: `void`
22. `removeAttributeNode()`: Removes an attribute node from the element.
    - Returns: `Attr`
23. `removeChild()`: Removes a child node from the element.
    - Returns: `Node`
24. `removeEventListener()`: Removes an event listener from the element.
    - Returns: `void`
25. `replaceChild()`: Replaces a child node of the element.
    - Returns: `Node`
26. `replaceChildren()`: Replaces the children of the element with new nodes. Removes EventListeners for the removed children.
    - Returns: `void`
27. `scrollIntoView()`: Scrolls the element into view.
    - Returns: `void`
28. `setAttribute()`: Sets an attribute of the element.
    - Returns: `void`
29. `setAttributeNode()`: Sets an attribute node of the element.
    - Returns: `Attr`
30. `setCapture()`: Sets the capture mode of the element.
    - Returns: `void`
31. `webkitMatchesSelector()`: Returns whether the element matches a specified selector (WebKit only).
    - Returns: `boolean`

Note that this is not an exhaustive list, and some properties and methods may be specific to certain browsers or versions.
