## 🛍️ Product Catalog with Filters (100% HTML)

### 📘 Overview

This project is a **Product Catalog with Filters**, built entirely using **HTML only** — no CSS, JavaScript, or external libraries.
It demonstrates how to structure and organize a catalog of products in a semantic and accessible way, while also using **HTML form elements** (like checkboxes, radio buttons, and dropdowns) to represent filters visually.

Although the filters in this version are **non-functional** (since there’s no JavaScript to handle interactivity), this structure serves as a **foundation** for building a functional e-commerce product listing in the future.

---

### 🚀 Features

* 🧱 Built with **pure HTML** — no CSS or JavaScript.
* 📦 Displays a structured **product catalog** using semantic HTML elements.
* 🔍 Includes **filter sections** (categories, price range, brand, and rating).
* 🏷️ Each product includes a name, image placeholder, description, and price.
* 📋 Easy-to-read and modify — great for beginners learning HTML structure.

---

### 🧩 Project Structure

```
product-catalog-html/
│
├── index.html         # Main catalog page
└── README.md          # Documentation (this file)
```

---

### 🖼️ Page Layout (Conceptual)

The catalog page contains two main sections:

1. **Filter Sidebar** – Displays filter options such as Category, Price Range, and Brand.
2. **Product Grid** – Displays all available products in a simple tabular or list-based structure.

---

### 📄 Example Code (index.html)

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Product Catalog with Filters</title>
</head>
<body>
  <header>
    <h1>Product Catalog</h1>
  </header>

  <main>
    <section>
      <h2>Filters</h2>
      <form>
        <fieldset>
          <legend>Category</legend>
          <label><input type="checkbox" name="category" value="electronics"> Electronics</label><br>
          <label><input type="checkbox" name="category" value="clothing"> Clothing</label><br>
          <label><input type="checkbox" name="category" value="home"> Home</label><br>
        </fieldset>

        <fieldset>
          <legend>Price Range</legend>
          <label><input type="radio" name="price" value="low"> $0 - $50</label><br>
          <label><input type="radio" name="price" value="medium"> $50 - $100</label><br>
          <label><input type="radio" name="price" value="high"> $100+</label><br>
        </fieldset>

        <fieldset>
          <legend>Brand</legend>
          <select name="brand">
            <option value="">Select a brand</option>
            <option value="brandA">Brand A</option>
            <option value="brandB">Brand B</option>
            <option value="brandC">Brand C</option>
          </select>
        </fieldset>

        <fieldset>
          <legend>Rating</legend>
          <label><input type="checkbox" name="rating" value="5"> ⭐⭐⭐⭐⭐</label><br>
          <label><input type="checkbox" name="rating" value="4"> ⭐⭐⭐⭐</label><br>
          <label><input type="checkbox" name="rating" value="3"> ⭐⭐⭐</label><br>
        </fieldset>

        <button type="submit">Apply Filters</button>
      </form>
    </section>

    <section>
      <h2>Products</h2>

      <article>
        <img src="https://via.placeholder.com/150" alt="Product 1">
        <h3>Smartphone</h3>
        <p>High-quality smartphone with 128GB storage.</p>
        <p><strong>Price:</strong> $299</p>
      </article>

      <article>
        <img src="https://via.placeholder.com/150" alt="Product 2">
        <h3>Headphones</h3>
        <p>Noise-cancelling wireless headphones.</p>
        <p><strong>Price:</strong> $89</p>
      </article>

      <article>
        <img src="https://via.placeholder.com/150" alt="Product 3">
        <h3>Smartwatch</h3>
        <p>Water-resistant smartwatch with fitness tracking.</p>
        <p><strong>Price:</strong> $120</p>
      </article>

    </section>
  </main>

  <footer>
    <p>© 2025 Product Catalog Example. All rights reserved.</p>
  </footer>
</body>
</html>
```

---

### 🧠 How It Works

* The **filters** are represented as form fields (`checkbox`, `radio`, and `select` elements).
* The **products** are displayed using the `<article>` tag, making each product a separate content block.
* The design is **pure HTML**, so the filters **don’t affect** the product list — but this layout allows developers to later add CSS for styling and JavaScript for filter logic.

---

### 💡 Future Improvements

If you want to enhance this HTML-only project later, consider:

* Adding **CSS** to style the layout and make it responsive.
* Using **JavaScript** to make filters functional (hide/show products).
* Storing product data in a JSON file and dynamically rendering items.
* Connecting it to a backend (Node.js, Python, or PHP) for real-time product filtering.

---

### 🧾 License

This project is open-source and available under the **MIT License**.
You’re free to use, modify, and distribute it for educational or personal projects.
