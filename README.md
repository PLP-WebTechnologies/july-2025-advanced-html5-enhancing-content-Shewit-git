# 📘 HTML5 Content & Forms Showcase

## Overview

This project demonstrates advanced HTML5 features including semantic elements, lists, tables, media embedding, and comprehensive form implementation with native HTML5 validation.

## Features Implemented

### 1. Semantic HTML5 Structure
- Proper use of semantic elements (`<header>`, `<section>`, `<article>`, `<footer>`)
- Well-organized content with clear sectioning
- Responsive design that works on various screen sizes

### 2. Content Sections
- **Lists**: Ordered, unordered, and description lists with semantic markup
- **Tables**: Responsive data table with proper structure and styling
- **Media**: Embedded images, audio, and video with fallback content

### 3. Advanced HTML5 Form
- **Input Types**: text, email, tel, date, password, url, checkbox, radio, file
- **Form Validation**:
  - Required fields
  - Input patterns
  - Min/max length
  - Email and URL validation
  - Custom validation messages
  - Password confirmation with real-time feedback
- **Accessibility**:
  - Proper labels and fieldset/legend usage
  - ARIA attributes where appropriate
  - Keyboard navigation support

### 4. Styling and UX
- Clean, modern design
- Visual feedback for form interactions
- Responsive layout using CSS Flexbox
- Custom styling for form validation states

## File Structure

```
.
├── enhanced-form.html  # Main HTML file with all content and styles
└── README.md          # This documentation file
```

## Usage

1. Clone the repository
2. Open `enhanced-form.html` in any modern web browser
3. Interact with the form to see validation in action

## Form Fields Overview

### Personal Information
- Full Name (required, min 3 chars)
- Email (required, email validation)
- Phone Number (optional, pattern validation)
- Date of Birth (required, max date validation)

### Account Details
- Username (required, alphanumeric with underscores)
- Password (required, strong password requirements)
- Confirm Password (must match password)

### Additional Information
- Country (required dropdown)
- Interests (checkbox group, at least one required)
- Preferred Contact Method (radio buttons)
- Website (optional, URL validation)
- Biography (text area)
- Profile Picture (image file upload)
- Terms and Conditions acceptance (required checkbox)
- Newsletter subscription (optional checkbox)

## Browser Support

The page uses modern HTML5 and CSS3 features and is best viewed in the latest versions of:
- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Safari

## Validation

All form validation is done using native HTML5 attributes:
- `required` for mandatory fields
- `type` for input validation (email, url, etc.)
- `pattern` for custom validation
- `minlength`/`maxlength` for text input length
- Custom validation messages using `setCustomValidity()`

## Notes

- The form includes a small amount of JavaScript for password confirmation validation
- All other validations are handled by HTML5 native validation
- The design is responsive and works on mobile devices
- External resources (images, audio, video) are loaded from public CDNs

## License

This project is open source and available under the MIT License.

