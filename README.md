# json-dynamic-form

# JSON Dynamic Form

A simple HTML page with plain JavaScript that dynamically renders a form based on a JSON configuration.  
On form submission, it displays an alert saying **"Submitted successfully"**.

---

## 📑 Project Overview

This project was built as part of a web developer test exercise.  
It reads a predefined JSON constant inside the HTML page, dynamically creates corresponding form fields, and handles validations like input types and maxlength.

GitHub Repo: [https://github.com/pinkeshroy/json-dynamic-form](https://github.com/pinkeshroy/json-dynamic-form)

---

## 🚀 How to Run

1. Clone this repository:
```
   git clone https://github.com/pinkeshroy/json-dynamic-form.git
```
2. Open `index.html` in your preferred web browser.
3. Fill in the form fields.
4. Click the **Submit** button.
5. An alert message **"Submitted successfully"** will appear.

---

## 📦 JSON Configuration

The form is driven by a JSON array of objects.  
Each object contains:
- `key` — unique identifier for the form field
- `label` — label to display
- `type` — input type (text, email, tel, etc.)
- `maxLength` — (optional) maximum character length

Example:
```
const formFields = [
  { "key": "user_name", "label": "Name", "type": "text", "maxLength": "50" },
  { "key": "mobile_no", "label": "Mobile number", "type": "tel" },
  { "key": "email", "label": "Email", "type": "email" }
];
```
---
## Features
1. JSON-driven dynamic form rendering.

2. Validations for type and maxLength.

3. Plain JavaScript — no external libraries.

4. Clean, responsive form layout.

## 📄 Files Included
* index.html — Main HTML and JavaScript code.

* README.md — Project overview and instructions.

📖 Notes
* Any changes to the JSON constant inside json_form_test.html will automatically reflect in the rendered form.

* Mobile number field uses type="tel" for better input experience on mobile devices.
---

**🧑‍💻 Author:**  
Crafted with ❤️ by [@pinkeshroy](https://github.com/pinkeshroy)
---
