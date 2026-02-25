Perfect 👍 Anandhu!

---

# ⚽ Football Image Grid Layout

A responsive **Image Gallery Grid Layout** built using **HTML5** and **Tailwind CSS (CDN version)**.
This project demonstrates how to create a structured grid system with different column and row spans.

---

## 🚀 Project Overview

This project is designed to practice:

* Tailwind CSS utility classes
* CSS Grid layout
* Responsive design basics
* Image aspect ratio handling
* Column and row spanning

The layout displays a football-themed image gallery arranged in a clean grid structure.

---

## 🛠️ Technologies Used

* **HTML5**
* **Tailwind CSS v4 (CDN version)**
* **CSS Grid (via Tailwind utilities)**


---

## 📂 Project Structure

```
football-grid-gallery/
│
├── index.html
└── README.md
```

---

## 🎯 Features

✅ Full-screen dark background
✅ Centered container
✅ 4-column grid layout
✅ Image spacing using `gap-2`
✅ Square aspect ratio using `aspect-square`
✅ Large featured images using:

* `col-span-2`
* `row-span-2`
  ✅ Responsive utility classes
    
    preview

    ![img](/image.png)
    [live](https://anandhu-photogallery.netlify.app/)

---

## 🧠 Concepts Used

### 1️⃣ Grid Layout

```html
grid grid-cols-4 gap-2
```

* `grid` → Enables CSS Grid
* `grid-cols-4` → 4 equal columns
* `gap-2` → Spacing between grid items

---

### 2️⃣ Image Scaling

```html
aspect-square w-full h-full
```

* `aspect-square` → Keeps images perfectly square
* `w-full` → Full width of grid cell
* `h-full` → Full height of grid cell

---

### 3️⃣ Featured Large Images

```html
col-span-2 row-span-2
```

This makes selected images larger to create a dynamic layout.

---

## 🖥️ How to Run the Project

1. Create a folder.
2. Create a file named `index.html`.
3. Paste the code inside.
4. Open the file in browser
   OR
   Use **VS Code Live Server** extension.

---

## 📸 Layout Structure

* Background: Black (`bg-black`)
* Container: Stone color (`bg-stone-500`)
* Width: 50% of screen (`w-1/2`)
* Padding: `p-10`

---

## 🔥 What I Practiced in This Project

* Using Tailwind without installing via npm
* Working with CDN version
* Creating masonry-style grid
* Managing image sizes properly
* Understanding grid column and row span

---

## 🚀 Future Improvements

* Make it fully responsive (`md:grid-cols-2`, `lg:grid-cols-4`)
* Add hover effects
* Add smooth animations
* Add image overlay text
* Convert into dynamic gallery using JavaScript

---

## 👨‍💻 Author

**Anandhu Es**
Aspiring Frontend / MERN Stack Developer
Practicing Tailwind CSS & Layout Design 


