# Basic Instagram Profile – Part 1  

Welcome to your first assignment! 🎉  

This is a two-part project where you’ll build a simple Instagram profile. For **Part 1**, we’re focusing only on **HTML structure** — no CSS yet. This will help you practice creating and organizing content on a page before we start styling.

---

## Getting Started  

1. Open VSCode

2. In your terminal, create a new directory to store all of your CS+SG Education Team files (call it something that makes sense) with the following commands
   ```bash
   mkdir cssg-education-team-fa25
   cd cssg-education-team-fa25
   
3. Accept the assignment through the GitHub Classroom link (you've already done this):  
   👉 [https://classroom.github.com/a/ZihBBQbD]
   
   This will create your own private repository.
   
4. Clone your repository to your computer with the following commands 
   ```bash
   git clone <your-repo-url>
   cd <your-repo-name>
   
5. Re-open the folder in VSCode

6. Your repo should include this README.md and index.html

## ✅ Part 1 Requirements 

Your task is to create a **basic Instagram profile** using **HTML only** (no CSS or JavaScript).  

### Required Elements
- **Header area:**
  - An Instagram logo png
- **User info area:**
  - A  profile picture (`<img>`)
  - A username (use a heading, e.g. `<h1>`)
  - A short paragraph describing the user
  - Optional: small details (e.g. location or "Edit Profile" button)
- **Posts section:**
  - At least **3 image placeholders**
  - Each image must include a meaningful `alt` attribute
  - Wrap each post in a semantic container (e.g. `<article>`)
- **Footer:**
  - Navigation links such as: About, Help, Privacy
  - Copyright or small text
- **Additional things to include:**
  - Links
    - Use an **absolute** link to an external website
    - Use a **relative** link to another html page that contains a link back to index.html
    - Feel free to reference these links wherever you'd like on your site
  - One HTML comment

### Rules
- Use **HTML only** (no CSS, no inline `<style>`, no JS)
- Use **semantic HTML tags** (`<header>`, `<main>`, `<section>`, `<article>`, `<footer>`)
- All images must include `alt` text for accessibility
- Ensure you are using attributes in the right places (`src` for images, `href` for links)
- Your `index.html` file must be located in the **root of the repo**

p.s. Don't worry about making this look pretty, we will work on styling next week! The purpose of this assignment is just to get you started with HTML.

## 📤 Submitting Your Work

Follow these steps to submit your assignment properly:

1. **Save your work**  
   - Make sure your `index.html` file is inside your assignment repo folder.  
   - Double-check that your HTML opens in a browser with no errors.  

2. **Stage your changes**  
   ```bash
   git add .
3. **Commit your changes**
   ```bash
   git commit -m "<meaningful commit message here>"

5. Push to GitHub
   ```bash
   git push
  
7. Confirm your submission
   - Go to your repo on GitHub
   - Make sure your most recent changes appear (can see this in code, or on the main page of your repo with the commit message)
