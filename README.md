# Cinema Online - Movie Ticketing Web App

**Cinema Online** is an interactive, web-based movie ticketing platform developed for the **CIA 4103 - Data Driven Web Technologies** course. Built using **ASP.NET Core MVC**, it allows users to browse, filter, and purchase movie tickets through a responsive and secure interface.

---

## Project Overview

Cinema Online streamlines the process of movie discovery and ticket booking with features like:

* Genre-based browsing
* Price and year filters
* Role-based authentication
* Cart and checkout system

The platform emphasizes **data-driven architecture**, **clean UI**, and **secure operations**, showcasing proficiency in:

* ASP.NET Core MVC
* Razor Pages
* SQL Server integration using Entity Framework Core

---

## Key Features

### User Roles

* **Public**: Browse movies, register
* **Member**: Add to cart, checkout, view purchase history
* **Admin**: Full access to manage movies and users

### Movie Management

* Browse by **genre**, **year**, or **price**
* Admin can **add/edit/delete** movies

### Cart System

* Add and remove movies from the cart
* Modify quantity and complete checkout
* Store transaction history

### Security Plan

* Role-based access (public/member/admin)
* Secure authentication and authorization using ASP.NET Identity

### Responsive UI

* Razor Views for clean, server-side rendered pages
* Accessible layout for users across devices

---

## Screenshots & Diagrams


| Feature             | Screenshot                                 | 
| ------------------- | ------------------------------------------ | 
| Site Map            | ![SiteMap](https://github.com/user-attachments/assets/94f27ff1-9a59-426c-9894-e10bc8be6aa0) |
| Class Diagram       | <img width="1268" height="693" alt="RD" src="https://github.com/user-attachments/assets/e53c2584-ceec-4449-a3bd-43bbb54ad551" /> |
| Security Plan Table | <img width="941" height="1069" alt="image" src="https://github.com/user-attachments/assets/6eb8f38c-fabe-4dcb-83fc-4975997de762" /> |
| Login Page          | <img width="495" height="388" alt="image" src="https://github.com/user-attachments/assets/4781b8ce-39d8-4731-b029-2516e421b894" /> |
| Movie Browse        | <img width="493" height="274" alt="image" src="https://github.com/user-attachments/assets/e10e204a-769d-4ca1-8f07-ed9246b630ee" /> |
 | Movie Details        | <img width="604" height="393" alt="image" src="https://github.com/user-attachments/assets/1bc6863f-4c1b-4b41-8783-430508c5cea6" /> |

---

## Technical Details

### Models

* `Account`: User details and authentication
* `Movie`: Title, genre, price, release year
* `CartItem`: Items selected for checkout
* `TransactionHistory`: Completed orders and details

### ⚖Controllers

* `AccountController`: Login, register, logout
* `MovieController`: CRUD and filter logic
* `CartItemController`: Cart management and checkout

### Database

* **Entity Framework Core** with code-first approach
* Models mapped to **SQL Server** via `AppDbContext`

---

## 💼 License

This project is created for educational purposes only as part of the CIA 4103 coursework.

---

## 👥 Authors

* CIA 4103 Group Project Team (2024)

---

## 📖 Tags

`ASP.NET Core` `MVC` `Entity Framework` `Movie Booking System` `Data-Driven Web App` `Razor Pages` `SQL Server`
