## Bookstore-Management
Bookstore Management System

# Key Features

1. **Inventory Management**:
   - Tracks stock levels for books, stationery, pencils, and pens
   - Provides availability checks (`isAvailable()`)
   - Updates stock levels when items are sold (`decrementStock()`)

2. **Pricing System**:
   - Maintains fixed prices for each product type
   - Provides price lookup functionality (`getPrice()`)

3. **Sales Processing**:
   - Validates inventory before processing sales
   - Updates inventory on successful sales
   - Tracks total sales value and units sold via `SalesCounter`

4. **Reporting**:
   - Displays initial product availability and pricing
   - Shows transaction results
   - (Commented out) Potential for displaying total sales metrics
