CSS
1. Selector
2. Declaration: property and value

Three types of selector
1. Element selector
p {
  color: blue;
}
2. Class selector
.blue {
  color: blue;
}
<p class="blue">...</p>
3.id selector (define the value of id)
#name {
  color: blue;
}
<p id = "name">...</p>

Combining selector
1. Element with class Selector
p.big {
  font-size: 20px;
}
2. child selector (direct child)
article > p {
  color: blue;
}
represent the p is in the article tag, must be direct child
3. Descendent selector
article p {
  color: blue;
}
every p is in the article is valid

Pseudo-class selector
:link, :visited
:hover, :active
:nth-child()

selector:pseudo-class {
  ...
}

Real world always use external styles
Head style are usually override external ones
