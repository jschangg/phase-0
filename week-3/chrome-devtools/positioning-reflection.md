![pic 1](/JustinChang/devbootcamp/phase-0/week-3/chrome-devtools/imgs/1.png)
![pic 2](/JustinChang/devbootcamp/phase-0/week-3/chrome-devtools/imgs/2.png)
![pic 3](/JustinChang/devbootcamp/phase-0/week-3/chrome-devtools/imgs/3.png)
![pic 4](/JustinChang/devbootcamp/phase-0/week-3/chrome-devtools/imgs/4.png)
![pic 5](/JustinChang/devbootcamp/phase-0/week-3/chrome-devtools/imgs/5.png)
![pic 6](/JustinChang/devbootcamp/phase-0/week-3/chrome-devtools/imgs/6.png)
![pic 7](/JustinChang/devbootcamp/phase-0/week-3/chrome-devtools/imgs/7.png)
![pic 8](/JustinChang/devbootcamp/phase-0/week-3/chrome-devtools/imgs/8.png)
<p>
How can you use Chrome's DevTools inspector to help you format or position elements?
</p>
Chrome dev tools inspector helps your format and position elements by allowing you to odify specifics elements via the dev tool. You can add css to each specific element via the css commands.
<p>
How can you resize elements on the DOM using CSS?
you can resize elements on the dom by modifying the width and height of the elements
</p>
<p>
What are the differences between absolute, fixed, static, and relative positioning? Which did you find easiest to use? Which was most difficult?
So static is actually the default for every single page element. Different elements don't have different default values for positioning, they all start out as static. Static doesn't mean much, it just means that the element will flow into the page as it normally would.

Relative type of positioning is probably the most confusing and misused. What it really means is "relative to itself". If you set position: relative; on an element but no other positioning attributes (top, left, bottom or right), it will no effect on it's positioning at all, it will be exactly as it would be if you left it as position: static; But if you DO give it some other positioning attribute, say, top: 10px;, it will shift it's position 10 pixels DOWN from where it would NORMALLY be.

So absolute positioning is a very powerful type of positioning that allows you to literally place any page element exactly where you want it. You use the positioning attributes top, left bottom and right to set the location. Remember that these values will be relative to the next parent element with relative (or absolute) positioning. If there is no such parent, it will default all the way back up to the element itself meaning it will be placed relatively to the page itself.

A fixed type of positioning is fairly rare but certainly has its uses. A fixed position element is positioned relative to the viewport, or the browser window itself. The viewport doesn't change when the window is scrolled, so a fixed positioned element will stay right where it is when the page is scrolled, creating an effect a bit like the old school "frames" days.
</p>
<p>
What are the differences between margin, border, and padding?
</p>
<p>
  Padding is the space that’s inside the element between the element and the border. Padding goes around all four sides of the content and you can target and change the padding for each side with CSS.

Margin is the space between the border and next element. The space outside the border between it and the other elements is the margin. Just like padding, it’s possible to target all four sides of an element to change it’s margin.
</p>
<p>
What was your impression of this challenge overall? (love, hate, and why?)
</p>
<p>
  this challenge was difficult, wouldl ike to go back so i can better use css positioning.

</p>