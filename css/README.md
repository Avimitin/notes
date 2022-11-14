## Selector

* element.class: select element that has specific class
* element1 element2: select child of the element1
* element1+element2: select sibling element
* element:state: select element by status
* body h1+p .special: select element `<p>` that contains `special` class,
which come just after `<h1>`, and is the child of `<body>`
* element, element, element: select those element

* Later styles replace conflicting styles that appear earlier in the stylesheet. This is the cascade rule.
* More specific selector will cancel other. Like class is more specific that element
* @media can apply rule by browser view point
* When browser met some css it doesn't understand, it just ignore it.

* CSS 的子元素默认会从父元素继承样式
