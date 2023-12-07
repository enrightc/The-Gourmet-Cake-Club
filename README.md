# GOURMET CAKE CLUB

Visit Gourmet Cake Clubs website here [The Gourmet Cake Club](https://enrightc.github.io/Gourmet-Cake-Club-Website/)

## Overall Website Aim

The primary aim of the Cake Gourmet Club website is to delight cake enthusiasts with an exquisite collection of high-end, visually stunning cakes, providing a sophisticated platform for discovering and indulging.

## External User Goals

- Discover Delicious Recipes: Users will want to explore a variety of cake recipes, including the unique “Cake of the month”
- Learn Baking Techniques: Through the FAQ section users can acquire baking tips and techniques to improve their cakes.
- Submit Questions: Users can submit further questions.
- Access Cake of the Month Features: Users are excited to discover and potentially try the featured Cake of the Month.
- Sign-Up: Users can sign up to the monthly newsletter to receive more cake recipes straight to their inbox.

## Website Owners Goals

- Generate Newsletter Subscriptions: The site owner wants users to sign up for a newsletter or subscription to receive monthly cake recipes.
- Showcase Cake Expertise: The site aims to establish itself as a go-to source for cake-related information, showcasing the owner's expertise.
- Increase Website Traffic: The site owner desires increased traffic to the website through engaging content and marketing efforts.
- Encourage Social Media Sharing: The owner hopes users will share their favourite recipes, blog posts, or Cake of the Month features on social media, contributing to the website's visibility.

## Additional Features

Features to be added at a later date of development:

- Build a Community: The site owner aims to create a community of cake lovers, fostering engagement and interaction among users through comment sections on recipes.
- Promote Featured Products: If applicable, the site owner may want to showcase and promote certain baking products, tools, or ingredients.

## Credit

### Images


## Code

- For help with position navigation links to centre of nav bar: <https://stackoverflow.com/questions/19733447/bootstrap-navbar-with-left-center-or-right-aligned-items> [Accessed 21st Nov 2023]

## Wireframes

[Homepage Wireframe](assets/wireframes/index.html.png)

[Cake of the Month](assets/wireframes/cake-of-the-month.png)

[Recipes](assets/wireframes/recipes.png "Recipes")

[sign-up](assets/wireframes/sign-up.png "Sign up wireframe")

[Tips](assets/wireframes/tips.png "Tips wireframe")

## Bugs

### Fixed Bugs

#### Hero Image Rendering Issue on Mobile Devices
- Issue: The hero image does not render correctly on mobile devices, resulting in a zoomed-in view on a small section of the image.
- Description: During testing on a mobile phone display, it was observed that the hero image was not rendering as expected. The issue was identified to be related to the "fixed" value in the background property, causing the image to display incorrectly and eliminating the intended parallax effect.
- Expected Behavior: The hero image should render correctly on all devices, including mobile, without sacrificing the intended parallax effect.
- Steps to Reproduce:
    - Access the website on a mobile device.
    - Observe the rendering of the hero image, noting the zoomed-in view.
- Investigation and Solution:
    - Reviewed CSS properties for the background image.
    - Identified that the "fixed" value in the background property was causing the rendering issue.
    - Removed the "fixed" value, resolving the rendering problem but sacrificing the parallax effect.


###  Known Bugs

#### Navigation Bar Overlaps Section Headings
- Issue: When clicking on a link to jump to a specific section of the page, the fixed navigation bar overlaps the headings of that section, making them partially or entirely hidden from view.
- Description: The fixed navigation bar does not account for the presence of section headings, causing a visual obstruction when navigating to specific sections. This affects the user experience as essential information becomes concealed, impacting the clarity of the content.
- Expected Behavior: When the user uses a link to navigate to a section of the page the section sub-headings should be visible without any overlap or obstruction from the navigation bar.
- Steps to Reproduce:
    - Navigate to any page with multiple sections.
    - Click on a link in the fixed navigation bar to jump to a specific section.

#### Cursor Not Changing to Pointer on Safari

- Issue: On the Safari browser, when hovering over links, the cursor does not change to the expected pointer icon as it does on other browsers. 
- Description: The default cursor behavior is not being observed on Safari when hovering over clickable links. Users may expect a visual cue, such as a pointer icon, to indicate a interactive link. This non-standard behavior can cause confusion and impact the perceived responsiveness of the website.
- Expected Behavior: When hovering over links, the cursor should change to a pointer icon across all browsers, providing a clear indication to users that the element is clickable.
- Steps to Reproduce:
    - Open the website on Safari.
    -   Hover over any clickable link.
