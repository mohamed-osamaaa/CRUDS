

https://github.com/user-attachments/assets/7dc7b489-f563-4203-b5a0-cefa78554a0e






# CRUDS - Product Management App

A web-based app for managing products built with JavaScript, HTML, and CSS. Users can add, update, delete, and search products by title or category. The app calculates the total price (price, taxes, ads, discounts) and stores product data in `localStorage`.

## Features

- **Create a Product**: Add a product with title, price, taxes, ads, discount, count, and category.
- **Update a Product**: Edit the details of an existing product.
- **Delete a Product**: Remove a product from the list.
- **Delete All Products**: Remove all products from the list.
- **Search Products**: Search products by title or category.
- **Total Calculation**: Automatically calculates the total price including taxes, ads, and discounts.

## Technologies Used

- JavaScript
- HTML
- CSS
- localStorage (for data persistence)

## How to Use

1. Clone or download this repository.
2. Open `index.html` in your browser.
3. Use the inputs to add products and see the data update in the table.
4. You can search by title or category to filter the displayed products.
5. Products will be stored in `localStorage`, so they persist even after refreshing the page.

## LocalStorage Data

The app stores product data in `localStorage` under the key `product`. The data is stored in the following structure:

```json
[
  {
    "title": "product name",
    "price": "price value",
    "taxes": "taxes value",
    "ads": "ads value",
    "discount": "discount value",
    "total": "calculated total",
    "count": "product count",
    "category": "product category"
  }
]
```

## Installation

1. Clone the repository:

```bash
git clone https://github.com/mohamed-osamaaa/CRUDS.git
```

2. Open the `index.html` file in your browser.
