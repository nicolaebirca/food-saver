# 🍽️ FoodSaver – Food Management PWA

**FoodSaver** is a Progressive Web App (PWA) designed to help users reduce food waste by keeping track of what's in their fridge, pantry, and freezer, while receiving alerts before items expire.

---

## 🚀 Features

### ✅ MVP (Minimum Viable Product)

- Add new product (name, category, expiration date, quantity)
- View a list of products sorted by expiration date
- Filter by storage location (Fridge, Freezer, Pantry)
- Push notifications for items expiring in the next 3 days
- Edit and delete products

### 🎯 Advanced Features (Planned)

- Barcode scanning for quick entry
- Smart shopping list (based on usage and waste history)
- Cross-device sync via Firebase
- Personalized dashboard with waste analytics
- Recipe suggestions based on current ingredients (Spoonacular API)
- Export list as PDF/Excel
- "Waste statistics" view: what you threw away, how often, how much
- Expiry calendar view

---

## 🧱 Tech Stack

- **Frontend:** React + Vite
- **Styling:** PostCSS + CSS Modules
- **PWA:** Workbox (offline support, installable)
- **Auth:** Firebase Authentication (Google/Email)
- **Backend:** Firebase Firestore
- **Push Notifications:** Firebase Cloud Messaging
- **PDF/Excel Export:** jsPDF + SheetJS
- **Recipe Search API:** Spoonacular

---

## 📁 Folder Structure

```bash
src/
├── assets/          # Images, icons, logos
├── components/      # Reusable UI components
├── features/
│   └── food/        # Food management logic and components
├── pages/           # Page views (Home, Dashboard, etc.)
├── services/        # Firebase and API integrations
├── utils/           # Helpers and utility functions
├── App.jsx
├── main.jsx
└── index.css