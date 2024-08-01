Facebook Login Page
This project is a simple HTML and CSS implementation of the Facebook login page. It includes a form for users to enter their email address or phone number and password to log in, as well as options to recover a forgotten account or create a new one.

Project Structure
The project consists of the following files:

index.html: Contains the HTML structure of the Facebook login page.
style.css: Contains the CSS styles for the page, ensuring it is responsive and visually similar to the Facebook login page.
HTML Structure
The index.html file includes:

A meta tag for setting the character set and viewport settings.
A link to the external CSS file (style.css).
A div container that houses two main sections:
A facebook section with an image and a paragraph describing Facebook's purpose.
A contact section with a form for logging in, a link for forgotten accounts, and a button for creating a new account.
CSS Styles
The style.css file includes:

Global styles for resetting margins and padding, and setting box-sizing.
Styles for the body to set the background color and default font size.
Styles for the .container to center its contents and set maximum width and height.
Styles for the .row, .facebook, .contact, and other classes to arrange the layout and appearance of elements.
Media queries to ensure the layout is responsive on different screen sizes, adjusting the styles for tablets and mobile devices.
How to Run
Clone the repository or download the files.
Open the index.html file in your web browser.
Facebook Login Page CSS
This CSS file contains the styling for a simple HTML implementation of the Facebook login page. The styles are designed to make the page responsive and visually similar to the official Facebook login page.

Styles Overview
Global Styles
Global Reset: All elements have their margin and padding set to 0, and box-sizing is set to border-box to ensure consistent sizing.
Body: The background color is set to #f0f2f5 and the default font size is 14px.
Container
Container: Centers its content both horizontally and vertically with display: flex, and has a maximum width of 1000px and a height of 100vh.
Row
Row: Uses display: flex to center its content and align items.
Facebook Section
Facebook Image: Adjusts the width and height of the Facebook logo and sets a margin at the bottom.
Facebook Paragraph: Sets the font family, size, margin, and color for the paragraph explaining Facebook's purpose.
Contact Section
Contact Container: Uses display: block to center and align its content, sets font family, padding, background color, border-radius, and box-shadow.
Contact Heading: Sets the font size and margin for the heading.
Form
Form: Uses display: flex and flex-direction: column to stack input fields vertically.
Form Inputs: Sets padding, font size, border radius, border color, text color, line-height, and margin for the input fields.
Buttons: Styles the buttons with padding, border-radius, font size, font family, font weight, text color, margin, and cursor pointer.
Buttons
.btn-blue: Sets the background color to Facebook's blue.
.btn-new: Sets the background color to green and adjusts the font size and margin.
Question
Question Text: Styles the question text with color, font size, font weight, and margin.
Divider
.or: Styles the "or" text with color, font size, and relative positioning.
.or::before and .or::after: Adds lines before and after the "or" text to visually separate sections.
Media Queries
@media (max-width: 768px): Adjusts styles for tablet and small laptop screens.

Sets the container to have a maximum width of 100%, adjusts the height and padding.
Changes the row direction to column.
Adjusts the Facebook image width and font size of the paragraph.
Adjusts the contact section width and padding.
Changes the form input padding and font size.
Adjusts the button padding and font size.
@media (max-width: 480px): Further adjusts styles for mobile devices.

Adjusts the Facebook image width.
Changes the font size of the Facebook paragraph.
Adjusts the contact heading font size.
Changes the form input padding and font size.
Adjusts the button padding and font size.
How to Use
Ensure your HTML file links to this CSS file with <link rel="stylesheet" href="style.css">.
Open the index.html file in your web browser to see the styled Facebook login page.

