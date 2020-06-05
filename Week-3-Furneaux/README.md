## Week 3 - What I learnt / key concepts
[project](https://furneauxs-563.superhi.com/) </br>
Week 3 was about transitioning from building single column websites,to multi-column websites. We focused on creating complex layouts using floats and clears,fixed headers ,hiding elements,mixing layouts and making everything responsive using different breaking points.</br>
- floats get boxes to display in columns that stack side by side(in 3 column or 2 column layouts) using either `float:left` or ` float;right`. Boxes will only be as wide as their content so in this case we need to assign a width.
- Floats take tags outs of the 'normal flow' of the parent tag that wraps it,so that it moves the other tags around it.
Without overflow,the height of the parent tag is just the height of the normal flow,so if we float everything inside a tag,there's no other normal tag left so height goes down to zero.By adding `overflow:hidden` we're forcing the parent tag to stretch to contain both normal and floated tags so that they don't impact any other tags near it.
- `overflow:hidden` is also used when content starts leaking into the gaps between columns,it's known as clearfix.
- Media queries breaking points for responsive styles
- `display:none`
- `text-shadow` and `box-shadow`
- `:nth-child selector` to select elements in a sequence e.g to grab the last anchor tag in a series use `a:last-child`
