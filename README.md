# Sepeda Onthel Skena (SOS) - Cashier Wesbite

## Description

This website is designed to support the cashier operations for PT. Sepeda Onthel Surabaya, specializing in selling vintage bicycles and related accessories. The cashier website helps staff process customer purchases and manage inventory efficiently. Additionally, the website allows product ordering from suppliers, and suppliers can send goods using distributors. This project built using **Flask** and **TailwindCSS** as part of my corporate application integration course mid test. The visualizes the results using **ApexCharts**. The project utilizes **Firebase** as the database for data management.

## Features

1. Data visualization on the dashboard using **ApexCharts**.
2. Responsive design with **TailwindCSS** for a modern user interface.
3. Data management integrated with **Firebase**.

### Key Features:

1. **Checkout System:**
   The cashier can process customer purchases quickly and easily. The checkout system supports various payment methods and records all sales transactions. Here is the sequence:

   1. **Select Product:**

      Cashier can quickly and easily select the products they wish to purchase.
   2. **Checkout Confirmation:**

      The system confirms the selected products and payment details before finalizing the transaction.
   3. **After Confrim:**

      After confirmation, the checkout system processes the payment and the purchase history will be displayed on the dashboard page.
2. **Dashboard:**
   The website includes a dashboard where the cashier or manager can review transaction history and sales reports, including metrics on revenue, total sales, and stock levels. This helps in making informed business decisions. The cashier can view the complete history of all transactions. This feature is useful for keeping track of daily sales and verifying orders.
3. **Product:**

   * **Add Products:** Staff can add new products with desired specifications, such as product name, price, stock quantity, and additional item details like wheel type and frame type.
   * **Edit Products:** Existing product information can be updated, including price, stock, and specifications.
   * **Delete Products:** Products that are no longer sold can be removed from the inventory.
   * **View Products:** All available products can be displayed on the product page, making it easy for staff to check inventory.
4. **Order Products from Suppliers:**
   Image

   The cashier can place orders to suppliers for items that are low in stock. The supplier will ship the ordered items using a distributor service.

## Technologies Used

- **Flask**: Python web framework used to build the backend and manage routing, data handling, and server-side logic for the application.
- **TailwindCSS**: CSS framework for responsive and flexible UI/UX design.
- **Firebase**: Cloud-based platform offering database and storage solutions to manage product data and user interactions.
- **ApexCharts**: Library used for creating interactive and dynamic data charts.

## Installation

Follow the steps below to run this project locally:

1. Clone this repository:

   ```bash
   git clone https://github.com/nykbswr/retail-pt-sepedaonthelsurabaya.git
   ```
2. Navigate to the project directory:

   ```bash
   cd retail-pt-sepedaonthelsurabaya
   ```
3. Create a virtual environment:

   ```bash
   python -m venv env
   ```
4. Install Python dependencies:

   ```bash
   pip install -r requirements.txt
   ```
5. npm install -D tailwindcss

   ```bash
   npm install -D tailwindcss
   ```
6. Run the Flask application:

   ```bash
   flask --app app.py --debug run
   ```
7. Run Tailwind CSS in watch mode:

   ```bash
   npx tailwindcss -i ./static/src/input.css -o ./static/css/output.css --watch
   ```

## Usage

Once the installation is complete, open your browser and go to `http://localhost:8000` to use the dashboard. You can explore cashier the dashboard to view the visualized manufacturing data using  **ApexCharts** , which provides interactive and dynamic charts based on the integrated data.

### How to Integrate with Other Modules (Supplier & Distributor)

1. Supplier
