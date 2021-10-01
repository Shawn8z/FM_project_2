# FM_project_2

# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj).

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![desktop](./screenshots/order_summary_desktop.png)
![mobile](./screenshots/order_summary_mobile.png)

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/order-summary-component-html-css-YzEnORsgs](https://www.frontendmentor.io/solutions/order-summary-component-html-css-YzEnORsgs)
- Live Site URL: [https://shawn8z.github.io/FM_project_2/](https://shawn8z.github.io/FM_project_2/)

### Built with

- html
- css
- mobile-first workflow

### What I learned

1. Should place a:visited selector before any other action base selector, if not it will overwrite all selector`s styling before it.
2. Adding background image in CSS.
3. A better understanding of when and where should different types of units be used.
4. Understand how different font weight work in the same font family.
5. In the first draft of solution preview on frontend mentor webside, the elements in .current_plan and .change_link are not behaving correctly (their position are not where they should be) their position was set to relative. That seems to cause the element's width value to inherite from its parent.(I tryed to force its size by putting in width value but it don't seem to work) I change their position from relative to absolute, the unwanted width inherite problem goes away and I can position they correctly.

## Author

- Frontend Mentor - [@Shawn8z](https://www.frontendmentor.io/profile/Shawn8z)

