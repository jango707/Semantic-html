# Semantic html

Playing around with some more advanced html and css features.

## What I learnt

- in ordered lists you can `reverse` the direction
- in ordered lists you can use `start=''`
- in ordered lists you can use `type=''`

- use `*, *::before, *::after { box-sizing: border-box; }`

- direct child selectors `.hello > h1 {`
- general sibling selector `.hello li ~ li {`
  - matches the element if a sibling is found before the element
- adjacent sibling selector `.hello li + li {`

- use `[]` to match attributes

- you can add text via CSS in using `:: after{ content: ''}` (MINDBLOWN)

- access last or first elements with `ul li:first-child { color: seagreen; } ul li:last-child { color: seagreen; }`

- list style properties (MINDBLOWN) `list-style-type: "❤️";`

-`dd { /* TRouBLe */ margin: 0 0 0 0; }`

## Resources

https://www.htmhell.dev/
https://developer.mozilla.org/en-US/docs/Web/HTML/Element
