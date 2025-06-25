# WebDev

## Design Choices

- **Responsive Layout:**  
  The form is wrapped in a `.container` with a maximum width, centered on the page. Media queries adjust the layout for smaller screens, ensuring readability and ease of use.

- **HTML5 Validation:**  
  Each input uses appropriate HTML5 validation attributes such as `required`, `type`, and `minlength` to ensure that users provide valid data. A custom JavaScript snippet enhances validation by checking that the password and confirm password fields match.

- **User-Friendly Styling:**  
  The form uses a clean and modern design with ample spacing, clear labels, and consistent styling. Elements like the submit button change appearance on hover to indicate interactivity.



## Challenges Faced

- **Cross-Device Consistency:**  
  Ensuring the form looked good on all devices required careful use of media queries and flexible layout techniques.
  
- **Custom Validation:**  
  While HTML5 provides basic validation, comparing password and confirm password fields necessitated a small JavaScript snippet to provide a better user experience.

## Additional Features

- **Profile Picture Upload:**  
  The form includes a file input that accepts image files, allowing users to upload a profile picture.

## HTML Tags Used

- `<!DOCTYPE html>`
- `<html>`, `<head>`, `<meta>`, `<title>`, `<link>`
- `<body>`, `<div>`, `<form>`, `<h2>`
- `<label>`, `<input>`, `<select>`, `<option>`
- `<script>`

## Browser Compatibility

Tested on Brave Browser, this form is compatible with modern web browsers. Simply open the **index.html** file in Brave to view the page live.

This is what it looks like on my Browser 
![Screenshot 2025-02-13 220053](https://github.com/user-attachments/assets/a0042803-56ac-473d-8a92-20da38a1d7a5)

