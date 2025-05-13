# Password Generator App

A simple, responsive app that generates two secure, random 15-character
passwords at the click of a button.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)

## Overview

### The challenge

Users should be able to:

- Click a button to generate two random passwords
- Each password should be exactly 15 characters long
- Passwords are generated using a mix of letters, numbers, and symbols
- The UI should be responsive and mobile-first

### Links

- Solution URL: https://github.com/OlesiaShcherbenko/password-generator
- Live Site URL: https://olesiashcherbenko.github.io/password-generator/

## My process

### Built with

- Semantic HTML5
- Mobile-first CSS (Flexbox)
- Vanilla JavaScript

### What I learned

- How to use `Math.random()` and `Math.floor()` to generate random characters
- DOM manipulation using `querySelector()` and `.textContent`
- How to structure semantic HTML using `<main>`, `<section>`, and `<output>`
- Writing responsive layouts using mobile-first CSS
- The importance of accessibility (using real semantic elements)

### Continued development

In the future, I want to:

- Add a “Copy to Clipboard” button next to each password
- Let the user choose password length
- Add checkboxes for including/excluding symbols or numbers
- Show a toast or tooltip when a password is copied
