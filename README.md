# Restaurant-Management-System

1. Database Setup
  menu table: Stores menu items with name and price.
  customers table: Stores customer data (name and phone).
  orders table: Stores each order's details (customer_id and total amount).
  order_items table: Links orders to menu items with their quantities.
2. Functions
  create_tables(): Ensures the tables are created if they don’t exist.

Menu Operations:

  add_menu_item(): Adds a new item to the menu.
  view_menu(): Displays all menu items.
  update_menu_item(): Updates an existing menu item by id.
  delete_menu_item(): Deletes an item from the menu by id.

Customer Operations:

add_customer(): Adds a new customer to the system.
view_customers(): Displays the list of all customers.
Order Operations:

place_order(): Takes a customer ID and the list of items with quantities to create an order, calculating the total based on item prices.
generate_sales_report(): Joins orders and customers to generate a sales report showing each order with its customer and total amount.

3. User Interface
The script provides a simple text-based menu that allows the user to:

    1.Add a new menu item.
    2.View the menu.
    3.Update or delete a menu item.
    4.Add a new customer.
    5.View all customers.
    6.Place an order.
    7.Generate a sales report.
    8.Exit the application.
