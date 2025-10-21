Live Demo
Deployed URL: https://starprofilecard.netlify.app/

GitHub Repository: https://github.com/Camerlia/Profile-Card

Project Structure
text
profile-card/
 # index.html          
 # about.html          
 # contact-us.html    
 # public/
 # camelia_afolabi.png
 # README.md
Features
Profile Card (index.html)
All required data-testid attributes for testing

Avatar with upload functionality

Live timestamp display that updates every second

Social media links to GitHub, Twitter, and LinkedIn

Hobbies and dislikes sections

Responsive grid layout

About Me Page (about.html)
Comprehensive bio section

My program goals

Areas where I'm building confidence

Note to my future self

Additional thoughts section

Quick navigation sidebar for easy browsing

Semantic HTML5 structure with proper headings

Contact Form (contact-us.html)
Four validated fields:

Full Name

Email

Subject

Message

Real-time validation with helpful error messages

Character counter for message field (10 character minimum)

Success message on valid submission

ARIA attributes for accessibility

Full keyboard navigation support

Navigation
Consistent navigation bar across all pages

Smooth hover effects and active states

Responsive design for mobile devices

Accessible navigation with proper ARIA labels

Design Features
Color Scheme: Pink/purple gradient theme using #aa67a1 and #f8a3cb

Typography: Clean system font stack for optimal performance

Animations: Smooth transitions and hover effects

Layout: CSS Grid with layered shadows for depth

Accessibility
Semantic HTML5 elements throughout

All form inputs have associated label elements

Error messages linked with aria-describedby

ARIA attributes for dynamic content

Fully keyboard accessible

Clear focus indicators on all interactive elements

Screen reader friendly with proper heading hierarchy

Responsive Design
Mobile-first approach

Breakpoints at 640px (tablet) and 768px (desktop)

Flexible CSS Grid with responsive columns

Large tap targets for mobile users

Local Setup
What You'll Need
A modern web browser (Chrome, Firefox, Safari, or Edge)

No build tools or dependencies required!

Getting Started
Clone the repository

bash
git clone https://github.com/Camerlia/Profile-Card.git
cd Profile-Card




Testing
Manual Testing Checklist
All data-testid attributes are present and correct

Avatar upload works properly

Timestamp updates every second as expected

Social links open in new tabs

Contact form validates all fields correctly

Error messages appear and disappear appropriately

Success message shows after valid submission

All pages are fully keyboard navigable

Navigation works smoothly across all pages

Responsive design works on mobile, tablet, and desktop

Test IDs Reference
Profile Card:

test-profile-card - Main article wrapper

test-user-avatar - Profile image

test-user-name - User name heading

test-user-time - Timestamp display

test-user-bio - Biography paragraph

test-user-social-links - Social links navigation

test-user-social-github - GitHub link

test-user-social-twitter - Twitter link

test-user-social-linkedin - LinkedIn link

test-user-hobbies - Hobbies list

test-user-dislikes - Dislikes list

About Page:

test-about-page - Main wrapper

test-about-bio - Biography section

test-about-goals - Goals section

test-about-confidence - Confidence areas section

test-about-future-note - Future self note section

test-about-extra - Extra thoughts section

Contact Form:

test-contact-name - Name input

test-contact-email - Email input

test-contact-subject - Subject input

test-contact-message - Message textarea

test-contact-submit - Submit button

test-contact-error-name - Name error message

test-contact-error-email - Email error message

test-contact-error-subject - Subject error message

test-contact-error-message - Message error message

test-contact-success - Success message

Technologies Used
HTML5 - Semantic markup

CSS3 - Modern styling with Grid and Flexbox

Vanilla JavaScript - No frameworks or libraries

File API - For avatar upload functionality

Regular Expressions - For email validation

Form Validation Rules
Full Name: Required field, cannot be empty

Email: Required, must match standard email format (name@example.com)

Subject: Required, cannot be empty

Message: Required, minimum 10 characters

Browser Support
Chrome/Edge (latest versions)

Firefox (latest versions)

Safari (latest versions)

Mobile browsers (iOS Safari, Chrome Mobile)

License
This project is open source and available for educational purposes.

Author
Camelia Afolabi

GitHub: @camerlia

Twitter: @cameliafolabi

LinkedIn: camelia-afolabi