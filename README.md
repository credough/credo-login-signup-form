# Credo | Login & Sign Up Form

This is my **first-ever personal front-end project** built using **HTML and CSS**, with a bit of **JavaScript** for transitioning between forms.  
I’ve made some practice pages before to learn basic syntax, but this is my first attempt at putting everything together into one working webpage.

---

## Overview

This project is a basic login and sign-up web page design. It features:
- A navigation bar
- A styled login form
- A planned (but incomplete) sign-up form
- Modern layout and styling using pure CSS

---

## What went wrong?

I **struggled while implementing the sign-up toggle using JavaScript**, especially when trying to switch views between login and registration forms. Specifically, I used the following JavaScript:

```js
function login() {
  document.querySelector('.form-box').classList.remove('active');
}

function register() {
  document.querySelector('.form-box').classList.add('active');
}

Because of that, the layout got messed up and the sign-up form didn’t show up.  
Only the login form works in this version.

---

## Screenshots

### Login Page (Working)  
![Login Screenshot](screenshots/login.png)

### Sign Up Page (Broken)  
![Sign Up Screenshot](screenshots/signup-error.png)

---

## What I Learned

Even though I didn’t finish this project 100%, I’m still proud of it.  
I learned that JavaScript is tricky, and I need to study it more.  
Next time, I want to fix this and build better websites.

---
 
## Tools Used

- HTML  
- CSS  
- A little JavaScript  
- Boxicons (for icons)

---

## Final Thoughts

This is only the beginning HEHE.  
I will keep practicing and improving. After fully learning this, I'll planning to implement logic and database in my projects using PHP and SQL.
