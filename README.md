# HNG Task — Testable Profile Card (Stage 0 → Stage 1)

## 🚀 Overview
This project is part of the HNG Internship program.  
It begins with **Stage 0** (a Testable Profile Card) and expands in **Stage 1** into a **multi-page website** that includes:
- A Home Page(Profile Card)
- An About Me Page
- A Contact Us Page

All pages are built using semantic HTML, accessible design principles, and responsive layouts.

---

## 🏠 Pages

### 1. Home Page — index.html
Displays a personal profile card that includes:
- Name, bio, and current time (in milliseconds)
- Avatar image
- Social links (Twitter, GitHub, LinkedIn)
- Hobbies and dislikes lists

All required 'data-testid' attributes are included for automated testing.

### 2. About Me Page — About.html
A reflective page that shares:
- Personal bio
- Goals in the program
- Areas of low confidence
- Note to future self
- Extra thoughts

Each section is semantically structured using '<main>' and '<section>' elements.

### 3. Contact Us Page — Contact.html
Contains a validated contact form with:
- Full name, email, subject, and message fields
- Validation for required fields, valid email format, and minimum message length
- Error and success messages with appropriate 'data-testid' attributes

---

## 🧩 Technologies Used
- HTML5
- CSS3 
- JavaScript (for time and form validation)

Layouts adapt automatically using CSS Flexbox and media queries.

## ⚙️ Accessibility
- Semantic HTML (<article>, '<main>', '<section>', '<nav>', '<figure>', '<header>')
- Labels linked to form inputs using the 'for' attribute
- aria-describedby attributes for error messages
- Keyboard-focusable links and visible focus states


## 🔗 Live Demo
Visit the live hosted site here:  
👉 **[https://Annoor24.github.io/HNG_Task0/](https://Annoor24.github.io/HNG_Task0/)**

## 💻 How to Run Locally

1. Clone the Repository
   bash
   git clone https://github.com/Annoor24/HNG_Task0.git
