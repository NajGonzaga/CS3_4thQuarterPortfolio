# CS3_4thQuarter Seatwork 2

## Answers

### Step 1 (Static vs Relative)

- Guided Question: What changed compared to the default static positioning? Try to give different values to top and left or you can change it to bottom, right.
- **Answer** : The sidebar's position changes going either or both down and to the left depending on the value you input on the css.

### Step 2 (Fixed)

- Guided Question: What happens when you scroll the page? Why does the footer behave differently from position relative?
- **Answer**: When we scrolled the page, the footer did not move or change its position at all. It remained fixed on it's original position. Position relative, on the other hand, remains in the normal flow of the page. The only thing position relative can do is shift its position on the page and when scrolled, will simply just stay where it currently is.

### Step 3 (Absolute)
- Guided Question: What is the effect of position: absolute on an element? How is it different from fixed?
- **Answer**: This made the element's position to be relative to its nearest positioned ancestor. It stays in place even when we scroll down. This is different from fixed as position fixed is positioned relative to the viewport, not the nearest positioned ancestor.

### Step 4 (Fixed)
- Guided Question: Why does the notice appear on top of the content? What happens if you swap the z‑index values?'
- **Answer**: Because the z-index has a high value, "notice" would appear on the top of the content. When we swap the z-index values, the stacking order will change and notice will appear behind the content, while content will appear in front of notice.

### Challenge
- What changes that you have to do on the code that will position .notice box on the top right corner of the .content box? Please write the code on paper as well (both html and css on the part of .notice and .content).
- **Answer**: 
- Try to change the position of .content to relative then to fixed. What do you observed each time?
- **Answer**: .content followed the top and left property values when the position was changed to relative. When we use fixed, it ignores the given property values.

- What do you observe on about the effect of z-index on .notice and .content boxes?
- **Answer**: The z-index with the higher value will be positioned "on top" of the element with the lesser value.

### Please answer the following reflection questions (15 minutes)

- a. Could you summarize the differences between the CSS position values (static, relative, absolute, fixed)?
- **Answer**: The difference between the four CSS position values (static, relative, absolute, fixed) is that first, Static position value makes your content stay in place, whether you change the values of its margin. Relative position value on the other hand, makes your content move anywhere you desire by inputting values on its margins that determine where it'll go. Absolute position value does not occupy space layout, meaning that its element will be removed from the normal document flow. Lastly, Fixed position value is similar to the Absolute position value, but the special thing about Fixed is that it's anchored to the viewport, making it stay in the same position even when scrolling.

- b. How does absolute positioning depend on its parent element?
- **Answer**: The absolute positioning relatively depend on its nearest ancestor that has a position other than static.

c. How do you differentiate sticky from fixed (you can research on sticky)?
- **Answer**: Stucky allows its element to stick in within its parent container when scrolling, whie Fixed keeps elements fixed relative to the viewport.

d. If you were designing a webpage for a school event, how might you use positioning to highlight important information? Please give concrete examples.

