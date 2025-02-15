# Temi's Turoring

[View deployed site here](https://kc-vic.github.io/MilestoneProject1/)

Temi's Tutoring is a responsive website designed to provide information about private tutoring services for children aged 5-16. The site offers details about available subjects, session times, and includes a registration form for new students.

## Business Goal

The primary goal of Temi's Tutoring website is to establish a strong online presence that effectively connects qualified tutors with students aged 5-16 who need academic support in Mathematics and English.

# UX

## The ideal client for this business is:

- English speaking.
- Is a parent or guardian to a child aged 5-16.
- Has access to fast internet broadband services.
- Lives in the UK.

## Visitors to this website are searching for:

- A tutor to provide online personalized education services for their child or ward.

## This project is the best way to help them achieve these things because:

- Other tutoring websites are over complicated and produce information overload quickly.
- This website is easy to navigate.
- The website gives the client the information they need without overloading them.
- Guiding them to the goal of the website - to fill out the registration form.

## Client Stories

- As a parent, I want to see the services available on this platform.
- As a prospective client I want to see the list of subjects taught on this platform.
- As a parent, I want to see the available sessions for my child.
- As a prospective client I want to register on the website.

## Wireframe Mockups

- [Homepage](wireframes/index.html.png)
- [Form](wireframes/Form.png)

# Features

## Existing Features

The website consists of two main pages to help potential clients achieve the desired satisfaction:

- ### Home Page (index.html)
  - Navigation menu for easy access to different sections
  - Hero image featuring a learning child
  - Overview section highlighting the tutoring service's value proposition
  - Subjects section with detailed information about Mathematics and English tutoring offerings
  - Sessions section displaying available weekday and weekend time slots
  - Registration button linking to the signup form.
- ### Registration Page (form.html)

* Comprehensive signup form collecting:
  - Parent/Guardian details (name, email, phone)
  - Student information (name, age, key stage)
  - Form validation for required fields
  - Custom error messaging for invalid email formats

- ### Design Features
  - Responsive design that adapts to different screen sizes
  - Consistent color scheme with #284a5a as the primary color

# Resources Used

- Typography using [Google Fonts](https://fonts.google.com/):
  - Oswald for main headings
  - Roboto Condensed for subheadings
  - IBM Plex Sans for content headings
  - Lato for body text
- [Bootstrap 5.3.3](https://getbootstrap.com/) framework for enhanced functionality and styling
- [Custom CSS](assets/css/style.css) for unique styling elements.

# Challenges and errors

- ### Media Query Screen Size Implementation Challenges:
  The current implementation of media queries presents limitations in handling screen sizes around 896px, which impacts the website's responsive design. When users view the site on devices with screen widths near 896px, such as certain tablets in landscape orientation or smaller laptop displays, they may experience layout inconsistencies.
- ### Form validation feedback.
  The current form validation feedback system isn't providing users with clear, timely feedback about their input. This creates a suboptimal user experience where errors might not be immediately apparent or might be displayed inconsistently across different form fields.

# Future improvements

## Online Booking System Enhancement

The addition of a booking button and form would streamline the session scheduling process. Currently, users can view available session times but cannot directly schedule them. A comprehensive booking system would include:

### Direct Session Scheduling

The booking form would allow parents to select specific time slots they've seen in the sessions section. The form would need to:

- #### Display real-time availability of tutoring slots

* Allow selection of subject and academic level
* Include a calendar interface for date selection
* Provide immediate confirmation of booking
* Send automated email confirmations to both parent and tutor

- #### Integration with Current Registration
  The booking system would work seamlessly with the existing registration system by:
  - Automatically populating fields for registered users
  - Maintaining consistent styling with the current form design
  - Storing booking history for repeat customers
  - Allowing modification of existing bookings

## Client Review Implementation

The addition of a review carousel would build trust and showcase success stories. This feature would provide social proof through:

- ### Interactive Review Display

* A Bootstrap carousel component showing multiple review cards
* Each card containing a client testimonial, rating, and relevant details
* Automatic rotation with manual navigation controls
* Mobile-responsive design matching the website's current aesthetic

- ### Review Management
  - A system for collecting and moderating reviews
  - Display of verified customer badges
  - Integration of star ratings
  - Highlighted reviews for specific subjects or grade levels

## Contact Page Development

A dedicated contact page would enhance communication channels between the tutoring service and its clients. This would involve:

- ### Direct Communication Features
  - A comprehensive contact form for general inquiries
  - Specific sections for feedback about tutoring sessions
  - Emergency contact information for urgent matters

# Deployment

## GitHub Pages Deployment

1. Navigate to GitHub repository
2. Click on "Settings" in the repository menu
3. Scroll down to the "GitHub Pages" section
4. Under "Source", select "main" branch
5. Click "Save"
6. Your site will be published at [MilestoneProject1](https://kc-vic.github.io/MilestoneProject1/)

## Local Development to GitHub

    To run locally, you can clone this repository directly into the editor of your choice in this case VS Code by pasting git clone https://github.com/Kc-Vic/MilestoneProject1.git into your terminal. To cut ties with this GitHub repository, type git remote rm origin into the terminal.

# Testing

## Functionality Testing

1. Navigation Links
   - Description: Tested all navigation links across both pages
   - Expected: All links should direct to correct sections/pages
   - Result: Pass
   - Test Environment: Chrome browser
2. Form Validation
   - Description: Tested required fields and email validation
   - Expected: Form should not submit with empty required fields or invalid email format
   - Result: Pass
   - Notes: Custom error message displays for invalid email format
3. Social Media Links
   - Description: Tested all footer social media links
   - Expected: Links should open in new tab with correct URL
4. Markup Validation
   - HTML validation using [W3C](https://validator.w3.org/) returning no errors.
   - CSS Validation using [W3C](https://jigsaw.w3.org/css-validator/) returning no errors.

## Responsiveness Testing

1. Mobile Devices (320px - 480px)

   - Description: Tested layout and functionality on small screens
   - Expected: Content should stack vertically, text should be readable
   - Result: Pass
   - Tested on: iPhone SE, iPhone 12, Google Pixel 5

2. Tablets (768px - 1024px)

   - Description: Tested layout and functionality on medium screens
   - Expected: Two-column layout where appropriate, maintained readability
   - Result: Pass
   - Tested on: iPad Air, iPad Mini, Samsung Galaxy Tab

3. Desktop (1024px+)
   - Description: Tested layout and functionality on large screens
   - Expected: Full layout with optimal spacing and readability
   - Result: Pass
   - Tested on: Various monitors (1080p, 1440p, 4K)

## Performance Testing

1. Load Time

   - Description: Tested page load times across different devices and connections
   - Expected: Load time under 3 seconds on broadband, under 5 seconds on 3G
   - Result: Pass
   - Tool Used: Google Lighthouse

2. Image Optimization
   - Description: Verified image loading and scaling
   - Expected: Images should load efficiently and maintain quality across devices
   - Result: Pass
   - Notes: Hero image uses aspect-ratio for optimal scaling

# Credits

## Content

- Bootstrap 5.3.3 framework
- Google Fonts (Oswald, Roboto Condensed, IBM Plex Sans, Lato)
- Font Awesome icons

## Media

- Hero image: Photo by Julia M Cameron from Pexels: [learningchild.jpg](https://www.pexels.com/photo/girl-in-pink-t-shirt-looking-at-the-imac-4143800/)

# Acknowledgement

- A lot of the guidance for developing the html and css files were from the code institute love running and the Broadwalk games tutorial.

# Disclaimer

The content of this Website is for educational purposes only.
