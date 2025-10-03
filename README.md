GUI/Interface
The website is fully responsive using fluid design and media queries.
I did not use Flexbox, as it is not part of the course requirement. Instead, I relied on inline-block, percentages, and separate CSS files for different viewport sizes.
The breakpoints and dimensions I used are:
Mobile (≤768px) – mobile.css
This size covers small smartphones. The layout is simplified to a single column so that all text, forms, and images stack vertically for easy readability on small screens.
Tablet (769px – 1024px) – tablet.css
This range covers medium devices like iPads and Android tablets. The layout shows more content side-by-side compared to mobile, but still keeps elements large and touch-friendly.
Laptop/Desktop (≥1025px) – laptop.css
This range is for larger screens, desktops, and laptops. The layout is wider with more spacing, making use of the available screen width while keeping readability balanced.
This approach ensures the website looks consistent and user-friendly across all devices.


I used a linear gradient in the **header and footer** of the About Me page:  
  `background: linear-gradient(to right, #ff7e5f, #feb47b);`  
  This creates a smooth horizontal gradient effect.
  I used an angled linear gradient in the **about-container section** of the About Me page:  
  `background: linear-gradient(45deg, #6a11cb, #2575fc);`  
  This creates a diagonal gradient effect from purple to blue.
