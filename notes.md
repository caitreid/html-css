## Why would I use classes and ids? Don't they seem to do the same thing, target elements on the page.

Good question!

Let's say you have a bunch of divs with a .timing class, but you have one specific div that needs different styles, you could combine classes and ids 

``.timing { background-color: red; color: black }
#afternoon { color: blue} ``

All of the divs with .timing class will have a red background and a black font color, but the div with the ID `#afternoon` will target the one specific div with a #afternoon ID. 

This is an efficient way to give styles to a collection of elements, but override styles for a specific element that needs to be targeted.

