# Furniture-shop-e-commerce
A flutter-based furniture shopping app
## FurniCart – Furniture Shop E-Commerce App
A simple and modern Flutter-based e-commerce app to browse and buy furniture items with smooth navigation and clean UI.

## Tagline  
"Style your home, one tap away."

## app Overview  
FurniCart is a furniture shopping mobile application built using **Flutter**.  
The app includes user login, product browsing, cart management, checkout process, profile management, and admin product editing.

##  Main Screens  
- Login Screen  
- Register Screen  
- Home Screen  
- Product Detail Screen  
- Cart Screen  
- Checkout Screen  
- Profile Screen  
- Admin Home Screen  
- Product Edit Screen  

##  Navigation Flow  
Login → Register → Home → Product Detail → Cart → Checkout → Profile

Admin Login → Admin Home → Product Edit

---

##  Tech Used  
- Flutter  
- Dart  
- Material UI Widgets  

##  Group Members  
-  Submitted by
Hira Asghar (FA23-BSE-074)
Samiya Azeem (FA23-BSE-087)
Muhammad Uzair (FA22-BSE-036)
Muhammad Affan (FA22-BSE-024)

## Folder structure 
lib/
├── screens/
│ ├── home_screen.dart
│ ├── login_screen.dart
│ ├── register_screen.dart
│ ├── product_detail_screen.dart
│ ├── cart_screen.dart
│ ├── checkout_screen.dart
│ ├── profile_screen.dart
│ ├── admin_home_screen.dart
│ └── product_edit_screen.dart
│
├── widgets/
│ ├── app_drawer.dart
│ ├── cart_item.dart
│ └── search_bar.dart
│
├── main.dart
└── product.dart
# FurniShop — Week 2 

## Current Progress (Week 2)
- Core flow working: Browse products → View details → Add to cart → View cart & checkout (demo).
- Navigation: Home, Product Details, Cart implemented using Navigator.push.
- UI: Basic layout with Scaffold, AppBar, ListView, TextField (search), FloatingActionButton and icons.
- Data: In-memory only (resets on app restart).
- Demo ready for lab: will show add-to-cart flow and cart operations without crash.

# Navigation Added  
- App now has **3 screens**:  
  **Home → Product Details → Cart**
- Navigation implemented using `Navigator.push()`  
- UI built with:
  - `Scaffold`
  - `AppBar`
  - `ListView`
  - `Column` / `Row`
  - `TextField` (Search)
  - `FloatingActionButton`
  - `ElevatedButton`
  - Icons (`Icons.search`, `Icons.shopping_cart`, etc.)

###  UI Improvements  
- Clean and simple layout for lab demo  
- Fun AppBar title: **“FurniShop — Buy Smart 🪑”**  
- Product images & clean cards  
- Basic search bar added


###  Data Handling (Temporary)  
- App uses **in-memory list only**  
- Data resets on restart (allowed for Week 2)





 
