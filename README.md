# Task8- (Laundry Service Hamburger Menu in Mobile)

## Project Description
A fully responsive Laundry Service Landing Page built using HTML, CSS, Flexbox, and Media Queries.
This version includes a hamburger menu for mobile view implemented using pure CSS (:focus) without JavaScript.

## Features

- Responsive Navigation Bar
- Logo (left), Menu (center), Username (right)
- Flexbox-based layout
- Hero section with text + image
- Book a Service button
- Mobile-friendly hamburger menu
- No JavaScript used for menu toggle

## Responsive Behavior
Desktop View
- Full navigation menu visible
- Horizontal layout using Flexbox
- Hero section in two columns

Tablet View (≤ 992px)
- Reduced font sizes
- Smaller image size
- Layout remains horizontal

Mobile View (≤ 600px)
- Navigation links hidden
- Hamburger menu appears
- Clicking hamburger shows sidebar menu
- Hero section switches to column layout
- Center-aligned content

## Hamburger Menu (Pure CSS)

The mobile menu is implemented using the :focus pseudo-class instead of JavaScript.

How it works:
 .hamburger:focus .mobile-menu {
     display: flex;
 }

- When the button is clicked → it gets focus
- The .mobile-menu (child element) becomes visible
- When focus is lost → menu hides automatically

## Technologies Used

- HTML5
- CSS3
- Flexbox
- Media Queries
- CSS Pseudo-classes (:focus)

##  How to run it 
1. Download or clone the repository.
2. Open the project folder.
3. Double click **index.html** or open it in any web browser.
