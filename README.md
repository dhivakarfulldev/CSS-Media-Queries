# CSS Media Queries (Desktop First - `max-width`)

A simple project to learn and practice **CSS Media Queries** using the **Desktop First** approach.

In this project, the default styles are written for desktop screens, and then `max-width` media queries are used to make the website responsive for smaller devices like laptops, tablets, and mobile phones.

---

## 📖 What is Desktop First?

Desktop First means:

- Design the website for large screens first.
- Use `max-width` media queries to adjust the layout for smaller screens.
- This approach starts from desktop and moves down to tablet and mobile.

Example:

```css
/* Desktop Styles */
.container {
  width: 1200px;
  margin: auto;
}

/* Laptop */
@media (max-width: 1024px) {
  .container {
    width: 90%;
  }
}

/* Tablet */
@media (max-width: 768px) {
  .container {
    width: 95%;
  }
}

/* Mobile */
@media (max-width: 480px) {
  .container {
    width: 100%;
  }
}
```

---

## 📱 Common Breakpoints

| Device | Media Query |
|---------|-------------|
| Large Desktop | Default CSS |
| Laptop | `@media (max-width: 1024px)` |
| Tablet | `@media (max-width: 768px)` |
| Mobile | `@media (max-width: 480px)` |

---



## 🚀 Features

- Desktop First responsive design
- Uses `max-width` media queries
- Clean and simple CSS
- Easy to understand for beginners
- Works on desktop, tablet, and mobile devices

---

## 🎯 Why Use Desktop First?

- Great for desktop-focused websites
- Easy to reduce layouts for smaller screens
- Helps maintain a structured design
- Commonly used in many existing projects

---

## 🛠 Technologies Used

- HTML5
- CSS3
- CSS Media Queries

---

## 📚 What You'll Learn

- How media queries work
- Difference between Desktop First and Mobile First
- Using `max-width` effectively
- Creating responsive layouts
- Making websites look good on different screen sizes

---


## ⭐ Support

If you found this project helpful, please consider giving it a ⭐ on GitHub.

Happy Coding! 