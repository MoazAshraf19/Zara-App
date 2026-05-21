# Zara App - Fashion E-Commerce Mobile Application

<img width="1672" height="941" alt="Zarar App" src="https://github.com/user-attachments/assets/17f1d71d-8251-4287-96ca-f70ed1306da9" />


## Project Overview

Zara App is a Flutter fashion e-commerce mobile application UI built to practice clean mobile interface implementation, product browsing, shopping flow, and feature-based project organization.

The project focuses on creating a modern fashion shopping experience with screens for home, product details, search, cart, checkout, wishlist, profile, orders, and notifications. It was developed as a portfolio project to improve Flutter UI skills, reusable widget creation, organized file structure, and professional GitHub presentation.

## Project Type

Flutter fashion e-commerce mobile application.

## Project Summary

| Item | Description |
|---|---|
| Project Name | Zara App |
| Platform | Android & iOS |
| Framework | Flutter |
| Language | Dart |
| Project Type | Fashion E-Commerce App |
| Status | UI and shopping flow completed |
| Architecture | Feature-based structure |
| Main Focus | Flutter UI, reusable widgets, product browsing, cart, checkout, and profile screens |

## Main Features

### Home Screen

Displays fashion categories and product sections such as new arrivals, hoodies, top selling items, and category-based product lists.

### Product Browsing

Allows users to explore different fashion products and categories through a clean product listing interface.

### Product Details

Includes a detailed product page with product image, options, size selection, color selection, and product-related actions.

### Search Screen

Provides a product search interface with filtering components and organized product results.

### Cart Screen

Displays selected cart items with a clean cart item layout and shopping summary flow.

### Checkout Screen

Includes checkout UI components for selecting checkout options and completing the shopping process.

### Wishlist

Allows users to view saved fashion items in a dedicated wishlist screen.

### Profile Screen

Includes user profile UI and profile-related sections for a complete shopping app experience.

### Orders

Includes order screens and order details UI to represent the user’s purchase history flow.

### Notifications

Includes a notification screen for displaying app updates or shopping-related notifications.

## Tech Stack and Packages

| Technology / Package | Usage |
|---|---|
| Flutter | Building the mobile application UI |
| Dart | Application logic and project structure |
| Material Design | UI components and mobile layout structure |
| SVG Assets | Rendering custom icons |
| Lottie | Empty state / no data animation support |
| Custom Fonts | Using local font assets for consistent typography |
| Git & GitHub | Version control and project documentation |

## Project Architecture

The project follows an organized structure with a shared core layer and feature-based folders.

```text
lib/
├── core/
│   ├── constant/       # App image paths and constants
│   ├── functions/      # Navigation helper functions
│   ├── styles/         # Colors, text styles, and themes
│   └── widgets/        # Shared reusable widgets
│
├── feature/
│   ├── cart/           # Cart page and cart item widgets
│   ├── checkout/       # Checkout page and checkout components
│   ├── product/        # Product details page and option widgets
│   ├── profile/        # Profile page, wishlist, and profile widgets
│   └── search/         # Search page, filtering, and search result widgets
│
├── main/
│   ├── HomePage/       # Home screen, product lists, categories, and dummy data
│   ├── List_Screen/    # Orders, order details, and order list widgets
│   ├── Notification_Screen/
│   └── main_screen.dart
│
└── main.dart           # App entry point
