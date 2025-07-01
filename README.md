# TASK 6: Contact Form with Client-Side Validation

## Objective  
Build a responsive contact form that validates inputs using HTML, CSS, and JavaScript. The form checks for proper name, email, and message formats before allowing submission.

---

## Tools Used  
- HTML  
- CSS  
- JavaScript  
- [Google Fonts](https://fonts.google.com)  
- VS Code  
- Chrome Browser

---

## Features Implemented  

- A fully functional **contact form** with the following fields:
  - Name  
  - Email  
  - Message  
  - Submit button

- **Client-side validation** with JavaScript:
  - Non-empty fields
  - Valid email format using **regex**
  - Real-time error messages displayed under each field

- **Success message** shown on valid submission (no actual backend/email sending)

- **Responsive design** to ensure the form works on all screen sizes

- Styled with a custom font inspired by **Iron Man** for visual appeal

---

## How Validation Works

- **Regex** is used to check if the email format is valid
- If any field is empty or email is invalid:
  - Error messages appear below the fields
  - Form submission is prevented
- On successful validation:
  - Form fields are cleared
  - A green success message is shown below the form

---

## Files Included
- `index.html` → HTML form structure  
- `style.css` → Styling for desktop and mobile view  
- `script.js` → JS for input validation logic
- `Background.jpg` → Background image for the web page



