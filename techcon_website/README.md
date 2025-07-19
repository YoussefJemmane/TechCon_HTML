# TechCon 2024 Conference Website

This repository contains the complete HTML structure for the TechCon 2024 conference website. All pages follow modern HTML5 semantic structure and accessibility standards.

## Files Created

### 1. index.html (Homepage)
- **Header**: Contains conference name in `<h1>` and navigation menu in `<nav>`
- **Main Section**: Includes conference description and promotional video with accessibility features
- **Footer**: Copyright information with explicit "copyright" text
- **Features**: 
  - Embedded video with controls and subtitle support
  - Semantic HTML structure
  - Proper navigation links to all other pages

### 2. about.html (About Page)
- **Header**: Page title "About TechCon 2024" and consistent navigation
- **Main Content**: Multiple `<article>` sections covering:
  - **History**: Origins and evolution of TechCon with historical images
  - **Mission**: Goals and principles with motivational imagery
  - **Past Speakers**: Notable speakers with photos and biographies
- **Features**:
  - Proper `alt` attributes for all images
  - Structured content using semantic HTML
  - Consistent navigation across pages

### 3. schedule.html (Schedule Page)
- **Header**: "Schedule for TechCon 2024" title with navigation
- **Main Content**: Detailed conference schedule using HTML table
- **Table Features**:
  - `<caption>` describing the table content
  - `<th>` headers with `scope` attributes for accessibility
  - Time, Session, and Speaker columns
  - Complete day's agenda from 9:00 AM to 6:00 PM
- **Structured Data**: Clear time slots, session names, and speaker information

### 4. register.html (Registration Page)
- **Header**: "Register for TechCon 2024" title and navigation
- **Main Content**: Registration form with required fields:
  - Name field with `type="text"`
  - Email field with `type="email"` for validation
  - Password and confirm password fields
  - Terms and conditions checkbox
  - Submit button labeled "Register Now"
- **Accessibility**: Proper `<label>` associations with form inputs

### 5. contact.html (Contact Page)
- **Header**: "Contact Us" title and navigation
- **Main Content**: Two main sections:
  - **Contact Information**:
    - Email with `mailto:` link using exact example provided
    - Social media links with `target="_blank"`
    - Embedded Google Maps iframe for venue location
  - **Contact Form**:
    - Name, email, and message fields
    - Proper labels and form validation
    - "Send Message" submit button

## Key Features Implemented

### Semantic HTML Structure
- Proper use of `<header>`, `<main>`, `<section>`, `<article>`, and `<footer>`
- Consistent navigation across all pages
- Meaningful heading hierarchy

### Accessibility Features
- Alt attributes for all images
- Proper form labels
- Video with subtitle support
- Table headers with scope attributes
- Semantic markup throughout

### Interactive Elements
- Registration form with validation
- Contact form for user inquiries
- Embedded promotional video with controls
- Google Maps integration
- Social media links opening in new tabs

### Navigation
- Consistent navigation menu on all pages
- Proper internal linking between pages
- External links with appropriate targeting

## File Structure
```
techcon_website/
├── index.html      # Homepage
├── about.html      # About page
├── schedule.html   # Schedule page
├── register.html   # Registration page
├── contact.html    # Contact page
└── README.md       # This documentation
```

## Standards Compliance
- Valid HTML5 markup
- Semantic structure for improved SEO
- Accessibility standards (alt text, labels, scope attributes)
- Responsive viewport meta tags
- Consistent styling structure ready for CSS implementation

This website provides a complete foundation for the TechCon 2024 conference, with all required functionality and proper HTML structure ready for styling and further development.
