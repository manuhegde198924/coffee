# coffee
- pseudo-elements
A CSS pseudo-element is a keyword added to a selector that lets you style a specific part of the selected elements. For Example, Styling the first letter or line of an element, and Inserting content before or after the content of an element. All of these can be done using Pseudo Elements in CSS.
- pseudo-classes
A Pseudo class in CSS is used to define the special state of an element. It can be combined with a CSS selector to add an effect to existing elements based on their states. For Example, changing the style of an element when the user hovers over it, or when a link is visited. All of these can be done using Pseudo Classes in CSS.

Note that pseudo-class names are not case-sensitive.

Syntax:  

selector: pseudo-class{
    property: value;
}

There are many Pseudo-classes in CSS but the ones that are most commonly used are as follows:

:hover Pseudo-class: This pseudo-class is used to add a special effect to an element when our mouse pointer is over it. The below example demonstrates that when your mouse enters the box area, its background color changes from yellow to orange. 

Example: This example shows the hover pseudo-class in CSS.
- position
The position property in CSS tells about the method of positioning for an element or an HTML entity and the positioning of an element can be done using the top, right, bottom, and left properties. These specify the distance of an HTML element from the edge of the viewport. 

There are five different types of position properties available in CSS:

    Fixed position: Any HTML element with position: fixed property will be positioned relative to the viewport. An element with fixed positioning allows it to remain in the same position even we scroll the page. We can set the position of the element using the top, right, bottom, and left.
    Static: This method of positioning is set by default. If we don’t mention the method of positioning for any element, the element has the position: static method by default. By defining Static, the top, right, bottom, and left will not have any control over the element. The element will be positioned with the normal flow of the page.
    Relative: An element with position: relative is positioned relatively with the other elements which are sitting on top of it. If we set its top, right, bottom, or left, other elements will not fill up the gap left by this element. An element with its position set to relative and when adjusted using top, bottom, left, and right will be positioned relative to its original position.
    Absolute: An element with position: absolute will be positioned with respect to its nearest Non-static ancestor. The positioning of this element does not depend upon its siblings or the elements which are at the same level.
    Sticky: Element with position: sticky and top:0 played a role between fixed & relative based on the position where it is placed. If the element is placed in the middle of the document then when the user scrolls the document, the sticky element start scrolling until it touched the top. When it touches the top, it will be fixed at the top place in spite of further scrolling. we can stick the element at the bottom, with the bottom property.
- inset

- background (linear gradient)
- z-index
The z-index property is used to displace elements on the z-axis i.e in or out of the screen. It is used to define the order of elements if they overlap on each other. 

Syntax:

z-index: auto|number|initial|inherit;

Property values:

    auto: The stack order is equal to that of the parent(default).
    number: The stack order depends in the number.
    initial: Sets the property to its default value.
    inherit: Inherits the property from the parent element.
- box-shadow
The box-shadow property in CSS is used to give a shadow-like effect to the frames of an element. The multiple effects can be applied to the element’s frame which is separated by the comma. The box-shadow can be described using X and Y offsets relative to the element, blur and spread radius, and color.

Syntax:

box-shadow: h-offset v-offset blur spread color |none|inset|initial|
inherit;

Default Value : Its default value is none. 

Property Value:  All the properties are described well with the example below.

    h-offset: It is required to set the position of the shadow horizontally. The positive value is used to set the shadow on the right side of the box and a negative value is used to set the shadow on the left side of the box.
    v-offset: It is required to set the position of shadow value vertically. The positive value is used to set the shadow below to the box and a negative value is used to set the shadow above the box.
    blur: It is an optional attribute, the work of this attribute is to blur the shadow of the box.

Syntax:

box-shadow: h-offset v-offset blur;
- margin/padding
The CSS margin-bottom property is used to specify the amount of margin to be used on the bottom of an element. The margin can be set in terms of length or percentage. 

Syntax:

margin-bottom: <length> | <percentage> | auto
Padding is the space between its content and its border. The padding-left property in CSS is used to set the width of the padding area on the left of an element. 
- width/height
