





## Practical III

### Quick Check Q1
Q/ You change the footer colour in styles.css. How many pages update? What if the same colour was only set with an inline style on index.html?

All 5 pages update when changed in styles.css (external CSS). If only set with inline style on index.html, only that one page would change.

### Quick Check Q2
Q/ Which is more specific: h1 or #welcome? If both set color, which wins?

#welcome (ID selector) is more specific than h1 (element selector). #welcome wins and its color is applied.

### Quick Check Q3
Q/ Convert #0369a1 into an approximate rgb(...) value. Why do designers often prefer hex in stylesheets?

#0369a1 ≈ rgb(3, 105, 161). Designers prefer hex because it's more compact (shorter to write) and easier to copy from design tools.

### Quick Check Q4
Q/ Set a nav link to display: none, then to visibility: hidden. What is the difference in the layout?

display: none - element is completely removed from layout (takes no space). visibility: hidden - element is invisible but still occupies its space in the layout.

### Quick Check Q5
Q/ In your wireframe, how many event cards appear side-by-side at phone width? At desktop width?

Phone width (≤576px): 1 event card per row (stacked vertically). Desktop width (≥992px): 3 event cards per row (using col-md-4 grid).

### Quick Check Q6
Q/ Why must styles.css be linked AFTER the Bootstrap CSS file? What happens if you reverse the order and both set h1 colour?

styles.css must be linked after Bootstrap so our custom styles can override Bootstrap's defaults. If reversed, Bootstrap would override our styles (last rule in cascade wins).