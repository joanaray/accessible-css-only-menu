# Accessible CSS-only burger menu
## tl;dr
A frontend exercise about making an accessible CSS-only burger menu with checkbox and popover methods, by Joana Ray and Samuel Traquina. In this article we demonstrate animated menus using pure CSS without JavaScript while ensuring accessibility.

You can check the demo and read the full article about it here: [https://joana.cc/sandbox/css-menu/]

## summary
I was talking to my friend @Trakina about frontend development and the use of JS for "nice-to-have" features and he shared this idea of an animated menu with CSS only, using a checkbox.

The basic idea was to use a label to control a checkbox's :checked state and then use that as a reference to animate its sibling containing the menu.

So when the checkbox is :checked, the menu opens up.

But we came across accessibility issues and decided to experiment with a different approach: a button toggling a popover element.