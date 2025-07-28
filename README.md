# 📰 Social Links Profile Frontend Mentor  
_A clean profile page challenge focused on HTML and CSS, from Frontend Mentor._

...

This project is a **social links profile page** created as a challenge from the **Frontend Mentor** platform, focused on **HTML** and **CSS**.  
The goal is to display a profile image, basic information, and a list of links with a modern and responsive design.  
It’s a *simple and clean* visual solution, but with good practices in organization, typography, and responsiveness.

---

## Table of contents

 - [📷 Design preview](#-design-preview)
 - [🎯 Goals](#-goals)
 - [🚀 Technologies Used](#-technologies-used)
 - [🧠 How It Was Done](#-how-it-was-done)
 - [🧩 Challenges Faced](#-challenges-faced)
 - [📚 What I Learned](#-what-i-learned)
 - [📁 Folder Structure](#-folder-structure)
 - [🔗 Project Link](#-project-link)

---

## 📷 Design preview

![Design preview for the Social links profile coding challenge](./docs/design/preview.jpg)

---

## 🎯 Goals

- Practice organizing **components using pure HTML and CSS**.  
- Work with **CSS variables in `:root`**, including fonts and sizes.  
- Apply **responsiveness using media queries** for different screen sizes.  
- Explore spacing best practices using **efficient selectors**.

---

## 🚀 Technologies Used

- `HTML5`
- `CSS3`
  - **Reset, main styles**, and **responsive design**
  - **Custom fonts** (`Inter` and `InterVar`)
  - **CSS variables with** `:root`
  - Styling with `hover` and transitions
  - Responsive layout using `media queries`

---

## 🧠 How It Was Done

I followed a structure similar to previous projects, separating files into **fonts**, **images**, and **styles**.  
During the process, a few highlights stood out:

I discovered the `li + li` selector, which allows spacing to be applied only **between** list items, without affecting the first one.  
This helped keep the link button spacing clean without needing extra classes.

```css
.links li + li {
  margin-top: 0.75rem;
}
```

I also used the `:root` to define **typographic variables** for the whole project — including font family, weights, and sizes — to keep the code centralized and reusable.

```css
:root {
  --ff: 'InterVar', 'Inter', sans-serif;
  --fs-body: 0.875rem;
  --fs-heading: 1.375rem;
  --fw-400: 400;
  --fw-600: 600;
  --fw-700: 700;
}
```

In addition, I reviewed the **media queries** to ensure padding and font sizes adapt well to smaller screens.

---

## 🧩 Challenges Faced

- **Understanding and correctly applying** the `li + li` *selector*.  
- **Learning that full typographic variables** can be declared in `:root`.  
- **Fixing responsive issues** like button width and spacing on smaller devices.

---

## 📚 What I Learned

- **Better use of CSS selectors** to reduce unnecessary code.  
- **Typographic organization** using `:root` variables.  
- **Clear separation** between reset, base, and responsive styles.  
- **More confidence** in adapting reusable structures for new challenges.

---

## 📁 Folder Structure

```bash
social-links-profile-frontend-mentor
├── docs/  -> Documentation, guides and design materials
├── src/     
│   ├── assets/
│   │   ├── fonts/
│   │   │   ├── static/
│   │   │   │   ├── Inter-Bold.ttf
│   │   │   │   ├── Inter-Regular.ttf
│   │   │   │   └── Inter-SemiBold.ttf
│   │   │   └── variable/
│   │   │       └── Inter-VariableFont_slnt-wght.ttf
│   │   └── imagens/          
│   │       ├── avatar-jessica.jpeg
│   │       └── favicon-32x32.png               
│   └── css/
│       ├── reset.css
│       ├── fonts.css
│       ├── style.css
│       └── responsivo.css              
├── index.html 
├── README.md
└── .gitignore
```

---

## 🔗 Project Link

[View the project here](https://andre363-br765.github.io/social-links-profile-frontend-mentor/)

