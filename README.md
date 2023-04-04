# Thomas' Landing Page

Landing page developed by Thomas Fenaroli to practice HTML and CSS skills.

[deployed url](https://tfenaroli-lab1.onrender.com/)

## What Worked Well

During this project, using flex-box worked well. For the most part, it was extremely intuitive to use flex-box to arrange the elements of my website. Moreover, flex-box made developing the mobile layout extremely easy. After changing some of my flex-boxes to columns, all I had to do was some touching up in order to create a layout that accomodates mobile views.

## What Didn't

I struggled quite a bit with the nav bar in mobile mode. Specifically, I found it difficult to use the checkbox hack to make the nav bar respond to click events. The concept of having a label element act as a proxy for a checkbox input was a bit difficult to wrap my head around. I also had to use Stack Overflow to better understand the paradigm of using a label element and the checkbox:checked pseudoclass to implement interactive features into the site.

## Extra Credit

For extra credit, I implemented the following:

- CSS transition for the "Join Now" bottom at the bottom right of the website that involves rotating and scaling transformations
- Expand and collapse features for the link headers using the CSS checkbox hack
- CSS transition for the nav bar when expanded and collapsed in mobile mode

To implement the first extra credit feature, I had to understand both how transformations and transitions work in CSS. I ended up using a 1 second transition that would rotate the button by 360 degrees and scale it by a factor of 1.2.

To implement the second extra credit feature, I had to get a better understanding of how CSS selectors and pseudo-classes work. After learning how I could use the :checked pseudoclass alongside the ~ and + sibling selectors, I was able to create four different checkboxes that, when toggled, would trigger CSS rules to either hide or display the content below each of the link headers at the bottom of the website.

In implementing the third extra credit feature, I gained a better understanding of the overflow property. The nav bar, when expanded, expands from height 0px to height 300px, and uses the 'overflow: hidden' property to ensure that content outside of the container does not get rendered.

## Screenshots

Link headers can expand and collapse in mobile mode!

<img width="421" alt="Screenshot 2023-04-03 at 9 18 19 PM" src="https://user-images.githubusercontent.com/83674002/229661490-affa17e4-73cb-42f3-ace6-6e02c697e10f.png">

Nav bar in mobile mode slides in from the top when expanded!

<img width="616" alt="Screenshot 2023-04-03 at 9 18 28 PM" src="https://user-images.githubusercontent.com/83674002/229661524-27adf9c5-8e4a-4c5a-aeed-d398493ecb2b.png">

Try hovering over this button! It rotates and scales up in size.

<img width="152" alt="Screenshot 2023-04-03 at 9 18 32 PM" src="https://user-images.githubusercontent.com/83674002/229661555-76ccc888-6d28-45c7-9d95-296bb3464304.png">
