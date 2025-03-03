# E-Commerce Order Management System

## 📌 Overview
This is a simple **E-Commerce Order Management System** built using **Python OOP (Object-Oriented Programming)** concepts. The project allows users to manage products, add them to orders, and calculate the total bill.

## 🚀 Features
- **Product Management:** Add electronic and grocery items with price, deal price, ratings, etc.
- **Order Processing:** Add items to the cart and generate a bill.
- **Warranty for Electronics:** Electronics products include warranty details.
- **Expiry for Groceries:** Grocery items display an expiry date.
- **Optimized Billing System:** Calculates the total amount dynamically.

## 📂 Project Structure
```
├── product.py      # Defines Product, ElectronicItem, GroceryItem classes
├── order.py        # Defines Order class for managing cart and checkout
├── main.py         # Executes the program and handles user interactions
├── README.md       # Project documentation
```

## 🛠️ Installation & Setup
1. **Clone the Repository**
   ```sh
   git clone https://github.com/your-repo-url.git
   cd your-repo-folder
   ```
2. **Run the Program**
   ```sh
   python main.py
   ```

## 📖 Usage
### Adding Products
```python
milk = GroceryItem("Milk", 40, 35, 4, "30/04/2025")
tv = ElectronicItem("TV", 25000, 20000, 4.2, 12)
```

### Creating an Order
```python
order = Order("Prime Delivery", "Hyderabad, India")
order.add_item(milk, 2)
order.add_item(tv, 1)
```

### Displaying Order Details
```python
order.display_order_details()
order.display_total_bill()
```

## 📷 Sample Output
```
📦 Order Details:
-------------------
Product: Milk
Price: ₹40
Deal Price: ₹35
You Saved: ₹5
Ratings: 4 ⭐
Expiry Date: 30/04/2025
Quantity: 2
-------------------
Product: TV
Price: ₹25000
Deal Price: ₹20000
You Saved: ₹5000
Ratings: 4.2 ⭐
Warranty: 12 Months
Quantity: 1
-------------------

💰 Total Bill: ₹40070
🚚 Delivery Type: Prime Delivery
📍 Delivery Address: Hyderabad, India
-------------------
```

## 🏗️ Future Enhancements
- Add **database support** for persistent data storage.
- Implement a **GUI or Web Interface** for better user interaction.
- Introduce **discount coupons and tax calculations**.

## 🤝 Contributing
Feel free to contribute! Fork the repository, make changes, and submit a pull request.

## 📜 License
This project is **open-source** and available under the MIT License.

