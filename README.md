# Mosaic Contact Form 

A clean and structured contact form built entirely with standard HTML5. This project focuses on the core of web forms .

##  Features

a.- **Semantic Grouping**: Uses `<fieldset>` and `<legend>` to logically separate user identity from the message content.

b.- **Built-in Validation**: 
    - `required` attributes prevent empty submissions.
    - `type="email"` ensures users provide a valid email format.
    - `type="tel"` provides a number-focused keyboard on mobile devices.
    
c.- **High Accessibility**: Every input is  linked to a `<label>` using `for` and `id` attributes, allowing screen readers 
to easily identify fields.

d.- **User Assistance**: Includes `placeholder` text to provide visual cues for the expected data format.

e.- **Form Controls**: Features a dropdown selection for inquiry types and a multi-line `textarea` for detailed messages.

f.- **Reset Functionality**: Includes a clear button to allow users to wipe their inputs and start over.

##   Lessons Learned

During the construction of this form, I mastered several key web development concepts :

### 1. The "For/ID" Connection
I learned that the `for` attribute on a `<label>` must match the `id` of its `<input>`. This is crucial for accessibility; it 
allows a user to click the label text to put their cursor inside the input box.

### 2. Data Integrity
I discovered that choosing the correct `type` (like `email` vs `text`) is the first line of defense in data collection. It lets the 
browser do the cumbersome duty of checking for errors before the data even reaches a server.

### 4. Grouping Context
Using `<fieldset>` is for organization, and it also provides context. For example, it tells a user (or a screen reader) that the 
"Name" and "Email" fields specifically belong to the "Personal Information" section.

---
*Created as part of my HTML Fundamentals journey.*
