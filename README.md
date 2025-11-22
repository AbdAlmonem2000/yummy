# 🍽️ Yummy – Meals Explorer  
A modern web application for exploring meals and recipes using **TheMealDB API**, built with **Native JavaScript**, **Bootstrap**, and **jQuery**.

---

## 🚀 Project Features

- Search meals by **name** or **first letter**.
- Browse meals by:
  - **Category**
  - **Area**
  - **Ingredients**
- View full meal details:
  - Image  
  - Instructions  
  - Area  
  - Category  
  - Ingredients & Measures  
  - External links (Source & YouTube)
- Smooth **Side Navigation Menu** with jQuery animations.
- Contact form with full **input validation**.

---

## 🧰 Technologies Used

- **HTML5**
- **CSS3**
- **Bootstrap 5**
- **JavaScript (Vanilla JS)**
- **jQuery**
- **Font Awesome**
- **Fetch API**
- **TheMealDB API**

---

## 📡 API Source

The project uses the official MealDB API:


Key endpoints used:

- `/search.php?s=`
- `/search.php?f=`
- `/categories.php`
- `/list.php?a=list`
- `/list.php?i=list`
- `/filter.php?c=`
- `/filter.php?a=`
- `/filter.php?i=`
- `/lookup.php?i=`

---

## 📂 Main Functions Inside the Project

### 🔹 **Display meals**
```js
function displayMeals(arr)
