# Web Development BootCamp Concepts

## CSS Properties -->

 - ### Display
	1. **Block** - The element generates a block-level box, which occupies the whole width of the page but adjusts according to the height of the element. We can change the width of this display element. e.g. h1-h6,p
	2. **Inline** - The element generates an inline-level box, which occupies width and height as much as required by the element. We can't change the width of this display element. e.g. span,img
	3. **Inline-Block** - A block box, which itself is flowed as a single inline box, similar to a replaced element. The inside of an inline-block is formatted as a block box, and the box itself is formatted as an inline box. We can change the width of this display element.
 
 - ### Position
	1. **Relative** - This position CSS property sets how an element is positioned in a document relative to it's original position. The top, right, bottom, and left properties determine the final location of positioned elements. The element shifts position but doesn't leave the heirarchy and keeps it's initial position intact with itself.
	2. **Absolute** - This position CSS property sets how an element is positioned in a document relative to it's parent's position which needs to be relative. The top, right, bottom, and left properties determine the final location of positioned elements. The element shifts position and leaves the heirarchy and it's not yet intact to it's initial position.
	3. **Fixed** - This position CSS property fixes the element to the top,right,bottom or left property and other elements can scroll below that.