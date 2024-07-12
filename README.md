# React Native Assignment 7

This repository contains the code for the seventh assignment of my Mobile Application Development course. The task was to build upon the previous assignment by adding a product detail component and implementing specific functionalities, including local storage for selected items. Custom components were used throughout the application.

## Table of Contents

- [Features](#features)
- [Screenshots](#screenshots)
- [How I Built the Application](#how-i-built-the-application)
- [Design Choices](#design-choices)
- [Data Storage](#data-storage)

## Features

- Add a product detail component.
- HomeScreen: Display a list of available products.
- ProductDetailScreen: Display detailed information about a product.
- CartScreen: Display selected items.
- A drawer component/navigation menu accessible through a swipe gesture or button.
- Add to cart button for each product.
- Remove from cart button for each selected item.
- Fetch data from an external API using fetch or axios.
- Manage asynchronous operations with async/await or promises.
- Render product lists and details.
- Use local storage (AsyncStorage, SecureStore, or FileSystem) to store selected items locally on the device.
- Users can:
  - View a list of available products from an external API.
  - Preview detailed information about a product.
  - Add products to their cart.
  - Remove products from their cart.
  - View the items in their cart.

## Screenshots

### Home Screen

![Home Screen](./pg1.jpg)

### Product Detail Screen

![Product Detail Screen](./pg2.jpg)

### Cart Screen 1

![Cart Screen 1](./pg3.jpg)

### Cart Screen 2

![Cart Screen 2](./pg4.jpg)

### Cart Screen 3

![Cart Screen 3](./pg5.jpg)

### Product Screen

![Product Screen](./pg6.jpg)

## How I Built the Application

The application was built following the instructions of the assignment, which required building upon a given UI mockup. I started by setting up a new Expo project and installing the necessary dependencies for navigation, icons, and data fetching. The application features a drawer navigator with screens for Home, Product Details, and Cart. Each screen was styled to closely match the provided UI design using custom components and React Native's styling system.

## Project Description

This app is a straightforward e-commerce platform showcasing a catalog of items that users can view in detail and add to their cart. The design focuses on simplicity and ease of use, with a clean and intuitive interface.

## Design Choices

- **Minimalist Design**: Emphasizing usability and readability, the app uses clean layouts and intuitive navigation. Icons are employed to effectively convey information, enhancing the user experience.
- **Custom Fonts**: Utilizing the `ArefRuqaaInk_400Regular` font, the app achieves a unique and elegant look, contributing to an enhanced overall user experience.

## Data Storage

- **AsyncStorage**: For persistent data storage, the app utilizes AsyncStorage to store cart items. This choice allows for a simple, yet effective way to persist user's cart data across app launches without needing a backend.
- **JSON Storage Format**: Cart items are stored in JSON format, enabling easy parsing and manipulation of the cart data. This approach simplifies the process of adding, removing, and retrieving items from the cart.

## Conclusion

This app demonstrates a practical implementation of a shopping cart and product details interface using React Native and AsyncStorage. The design choices and implementation strategies aim to create a user-friendly and efficient shopping experience. Key aspects of the app include the use of AsyncStorage for data persistence and a minimalist design approach, both of which contribute to the app's functionality and aesthetic appeal.
