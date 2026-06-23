# Bootstrap-Basics
It's a responsive demo site practicing the core Bootstrap building blocks — navbar, grid form with validation, data table, responsive images, and display/visibility utilities — that adapts cleanly between desktop and mobile.

Here is a version of that description rewritten to sound natural, conversational, and direct—perfect for a project summary, portfolio piece, or readme file:

Project Overview
I built a clean, single-page registration website using Bootstrap 5 and custom CSS. The entire project is organized into just two files: index.html for the structural layout and content, and styles.css for custom color tweaks and design polishes. To keep the project lightweight and fast-loading, Bootstrap's styling and functionality are pulled directly from a CDN.

The layout flows down through four main, interconnected sections:

1. Navigation Bar
At the very top is a dark navbar featuring a "MySite" brand logo on the left and three navigation links (Home, About, Contact) that smoothly jump to their corresponding sections on the page. On mobile devices or smaller tablets, these links automatically collapse into a standard hamburger menu (☰) to keep the interface clean, utilizing Bootstrap’s native JavaScript for the toggle animation.

2. Registration Form (#home)
The core feature is a user registration form housed inside a clean, shadowed white card. It features a responsive layout that displays the First Name and Last Name fields side-by-side on desktop views but stacks them vertically on mobile screens. The form also captures Email, Password, and a mandatory "Terms & Conditions" checkbox. All fields are strictly required; clicking the green Submit button triggers a custom JavaScript validation check, firing off clear red error messages underneath any empty or invalid fields.

3. Registered Users Table (#about)
Directly below the form is a user directory table pre-populated with four sample entries (Jane, John, Maria, and Wei) tracking their names, emails, and terms status. I styled the table with a dark header row, alternating striped rows, and interactive hover highlighting to make scanning data effortless. To prevent layout breaking on mobile, it is wrapped in a responsive container that allows it to scroll sideways on smaller viewports.

4. Images & Buttons (#contact)
The final section leads with a full-width banner image that stretches edge-to-edge across the screen, followed by a circular profile image framed in a custom green border. Right underneath, I implemented a couple of call-to-action buttons—one that stays visible across all devices, and a second, secondary button that intelligently hides on mobile and only pops into view on medium screens and larger.

Custom Styling Highlights (styles.css)
While Bootstrap handles the heavy responsive lifting, I wrote a tailored styles.css file to give the page its unique look. These custom additions include:

A soft, modern gray background across the entire page.
Distinctive, green-underlined section headings.
The custom shadow depth for the registration form card.
The green accent border wrapping the profile photo.
A smooth, subtle "lift" animation whenever a user hovers over any button on the page.
