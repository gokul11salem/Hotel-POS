# 🍵 Murugan's Tea Stall — Smart Billing & POS System

A modern, fast, single-file Point of Sale (POS) and billing application built specifically for tea stalls, cafes, and small restaurants. **Murugan's Tea Stall** manages dine-in hold orders, menu items, table numbers, multi-currency pricing, and thermal receipt printing.

🚀 **Use the live app by clicking this link**: [https://gokul11salem.github.io/Hotel-POS/](https://gokul11salem.github.io/Hotel-POS/)

---

## 🌟 Key Features

* **📊 Live Dashboard Analytics**: Real-time sales insights tracking daily revenue, monthly totals, order counts, open dine-in table orders, and recent transaction logs.
* **🍵 Smart Menu Catalog**: Categorized dish grids (Beverages, Snacks, Parotta Varieties, Tiffin, Sweets, Rice & Curry) with quick-add actions and multi-currency support (INR, MYR, SGD, USD, AED, SAR).
* **🪑 Dine-In & Table Management**: Save/hold running orders assigned to specific table numbers ("Eat now, pay later") and update active table orders mid-meal as customers order extra items.
* **🖨️ Thermal Receipt Printing**: Clean, beautifully structured thermal receipt printouts (`window.print()`) for customer billing.
* **🔒 PIN-Protected Admin Panel**: Secure admin console (Default PIN: `1234`) to manage inventory, change prices, edit custom shop branding (name, slogan, header logo), and configure custom table numbers.
* **💳 Digital Payment Integration**: Custom payment QR code support alongside international bank routing fields (UPI, IFSC, SWIFT/BIC, IBAN).
* **📜 Audit History & CSV Export**: 30-day transaction history with locked status badges and one-click CSV export capabilities for bookkeeping.
* **🌗 High-Contrast Light & Dark Themes**: Boots natively in a clean light mode with a high-contrast theme switch button for evening/night shifts.
* **💾 Local Data Persistence**: Powered by standard browser `localStorage` to ensure all custom prices, images, table setups, and sales logs survive page refreshes without needing a backend server.

---

## 🛠️ Technical Stack & Architecture

* **Frontend**: HTML5, CSS3 (CSS Custom Variables, Flexbox, & CSS Grid)
* **Scripting**: Vanilla JavaScript (ES6+)
* **Data Storage**: Synchronous Browser `localStorage` API (Zero backend/database dependency)
* **Typography & Styling**: Google Fonts (`Rozha One`, `Work Sans`) with high-contrast UI visibility for outdoor legibility
* **Printing Engine**: Native CSS `@media print` rules formatted for thermal receipt printers (`window.print()`)

---

## 🚀 Step-by-Step User Guide

### 1. Processing a Takeaway / Direct Sale
1. Go to the **Shop** tab and tap on dishes to add them to the cart.
2. Open the **Cart Drawer** and click **Proceed to Payment**.
3. Review the **Order Summary**, select a payment method, and complete the payment.
4. Click **🖨️ Print Bill Summary** to generate a thermal receipt for the customer.

### 2. Managing Dine-In Orders (Eat Now, Pay Later)
1. Add customer dishes to the cart.
2. In the Order Summary screen, select a **Table Number** from the dropdown menu.
3. Click **Save Order (Hold/Dine-In)**. The order will be saved to active table logs without requiring immediate payment.
4. When the customer orders more items later, go to **History / Recent Orders**, click **Edit Order**, add the new dishes, and update the held order.
5. Once the customer finishes their meal, open the held order, proceed to checkout, and complete the sale.

### 3. Admin Panel Setup & Customization
1. Click the **Settings** tab and enter the master PIN (Default: `1234`).
2. **Branding**: Update the shop name, slogan, or upload your official logo image.
3. **Products**: Add new menu items, update prices, change currency tags, or upload dish photos.
4. **Tables**: Add, rename, or remove physical table numbers for dine-in operations.
5. **Payment Setup**: Upload custom payment QR code graphics and fill in bank transfer details.

---

## 👨‍💻 Local Setup & Deployment

Since the entire application is self-contained within a single `index.html` file, no build tools or package managers are required.

1. **Clone the repository**:
   ```bash
   git clone [https://github.com/gokul11salem/Hotel-POS.git](https://github.com/gokul11salem/Hotel-POS.git)

# 1. Run locally:
Double-click index.html to open it in any modern web browser.

# 2. Deploy with GitHub Pages:

* Go to Repository Settings > Pages.

* Select main branch as the source and save.

* Your app will be live instantly!

# 📄 License
This project is open-source and free to use for personal or commercial restaurant and tea shop operations.
