Creating, Positioning, and Formatting Divisions
• To format divisions, employ styles similar to other elements. Styles allow you to specify font family, font style, font weight, alignment, color, and more.
• Alter the background color of a division using the background-color style rule.
• For instance, to introduce a khaki-colored background to the navigation bar, utilize the following CSS code:

```css
nav {
  float: left;
  width: 150px;
  padding-top: 15px;
  background-color: khaki;
}
```

• However, when incorporating colors into divisions, potential underlying issues with the page layout may surface.
• Positioning a Division on the Page [Important]
• To position a division, specify whether it should be relative to its natural position or absolute based on its parent element.
• If precision in placing a division is necessary, employ the position style rule with three possible values:
  - `position: absolute`: Specifies a fixed position relative to the parent element. Generally, the parent element is the <body> tag, placing the element relative to the upper-left corner of the page.
  - `position: relative`: Specifies an offset from the element's natural position. Other elements on the page remain unaffected, even if the new position causes overlaps.
  - `position: fixed`: Specifies a fixed position within the browser window, unaffected by scrolling. Note that Internet Explorer does not support this setting.

Example:
**Index.html:**
```html
<div class="parent">
  <div class="box" id="one">One</div>
  <div class="box" id="two">Two</div>
  <div class="box" id="three">Three</div>
  <div class="box" id="four">Four</div>
</div>
```

**Style.css:**
```css
.parent {
  border: 2px black dotted;
  display: inline-block;
}

.box {
  display: inline-block;
  background: red;
  width: 100px;
  height: 100px;
}

#two {
  position: fixed/relative/absolute; /* Choose one */
  background: green;
}
```

This example demonstrates the use of CSS to style divisions within a parent container, including the application of different positioning styles, such as fixed, relative, or absolute, to the second box with the ID "two."