---
Title: "Animations"
Subjects:
  - "Web Development"
  - "Web Design"
Tags: 
  - "Animation"
  - "Elements"
Catalog Content:
  - "https://www.codecademy.com/learn/learn-csss"
  - "https://www.codecademy.com/learn/paths/web-development"
---

CSS allows animation of HTML elements without using JavaScript or Flash!

An animation lets an element gradually change from one style to another. You can change as many CSS properties you want, as many times as you want.

To use CSS animation, you must first specify some keyframes for the animation.

## `@keyframes` Rule

Keyframes hold what styles the element will have at certain times.

When you specify CSS styles inside the `@keyframes` rule, the animation will gradually change from the current style to the new style at certain times.

To get an animation to work, you must bind the animation to an element.

```css
/* The animation */
@keyframes example {
  from {background-color: yello;}
  to {background-color: orange;}
}

/* The element */
div {
  width: 20px;
  height: 20px;
  background-color: yellow;
  animation-name: example;
  animation-duration: 5s;
}
```