

# ENCS5150 Android Project – Real Estate Hub

This Android application was developed as part of **ENCS5150 – Advanced Computer Systems Engineering Laboratory** (Spring 2025). It is a real estate app that allows users to view, favorite, and reserve properties online or using a local database. The app supports both customer and admin roles, offering distinct interfaces and features for each.

## Features

### 1. Welcome Screen

* Connects to a REST API to fetch property categories.
* Displays error message on connection failure.

### 2. Login & Registration

* User login with "Remember Me" (SharedPreferences).
* Registration with validation: email, name, password, gender, country, city, and phone.

### 3. Customer Interface

* Navigation Drawer:

  * Home (About Us, History)
  * Properties Menu with filters and search
  * Reservations & Favorites
  * Featured Properties
  * Profile Management (view/update info and add profile photo)
  * Contact Us (Call, Email, Google Maps)
  * Logout

### 4. Properties

* Lists properties grouped by type with thumbnail, details, price, location.
* Add to Favorites with heart animation.
* Reserve property with a details fragment.

### 5. Admin Interface

* Manage customers (delete).
* Statistics dashboard (user count, reservations, gender distribution).
* Add new admins.
* View all reservations.
* Create special offers for featured properties.

### 6. Additional

* SQLite local database.
* RESTful API integration.
* Animations for UI (favorites, loading).
* Data validation and exception handling.
* Pre-created admin account:
  **Email:** [admin@admin.com](mailto:admin@admin.com)
  **Password:** Admin123!

## Technical Details

* Minimum SDK: API 26 (Pixel 3a XL compatible)
* Fragments for property details, reservations, and favorites.
* Uses SharedPreferences for login persistence.


## Team Members

| Name         | Student ID |
| ------------ | ---------- |
| Diana Nasser | 1210363    |
| Hala Jebreel | 1210404    |


---

