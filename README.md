# 🚀 E-Commerce Web API

E-Commerce backend API built with **.NET 9** and **Clean Architecture**, designed for **scalability**, **maintainability**, and **high performance**.

---

## 🎯 Project Goal
Build a smart platform for managing online stores, products, and orders, with interactive customer engagement features like **promotions**, **reviews**, and multiple **delivery/payment options**.

---

## 🏗 Architecture & Layers

- **Presentation Layer** – Handles API requests & responses  
- **Service Layer** – Business logic & service orchestration  
- **Core Layer** – Commands, Queries, Mapping, and Filters  
- **Domain Layer** – Entities, Enums, and Business Rules  
- **Infrastructure Layer** – Database context, Configuration, Data Seeding, Repositories, External Integrations (Memory Cache, Paymob, Email, Azure Translation API)  

This layered design ensures **separation of concerns**, **testability**, and **maintainability**.

---

## 🛠 Tech Stack

- **.NET 9 Web API** – Clean Architecture  
- **Entity Framework Core + SQL Server**  
- **CQRS + MediatR** – Commands & Queries separation  
- **FluentValidation + Data Annotations** – Strong input validation  
- **JWT Authentication** – Role & Policy-based access  
- **AutoMapper** – DTO ↔ Entity mapping  
- **Memory Cache** – In-memory cart management and caching  
- **Paymob Integration** – Secure payment processing  
- **MailKit** – Confirm Email, Reset Password, Order Confirmation  
- **SignalR** – Real-time notifications via WebSockets  
- **Serilog** – Structured logging  
- **Localization** – Multi-language support  
- **Azure Translation API** – Multi-language translation services  

---

## 📦 Database & Key Entities

- **Users:** Admin, Customer, Employee  
- **Products & Categories** – Product management, reviews, and category organization  
- **Cart & CartItems** – Shopping cart management  
- **Orders & OrderItems** – Order processing  
- **Delivery Types:** Standard, Express, Same Day, Scheduled, Pickup from Branch  
- **Payment Methods:** Cash on Delivery, Cash at Branch, Paymob  
- **Shipping Address** – Flexible address management  
- **Reviews** – Customer product feedback  

---

## ⚡ Key Features (Implemented)

- **CRUD Operations** – Complete CRUD for Products, Categories, Orders, Users, Shipping Addresses  
- **Promotions & Discounts** – Interactive offers and discount management  
- **Secure Authentication** – JWT with roles & policies, plus Google OAuth integration  
- **Cart Management** – Shopping cart with distributed caching for guest and authenticated users  
- **Order Processing** – Multi-step checkout with transaction management and stock validation  
- **Advanced Search & Filtering** – Products & orders with pagination and sorting  
- **Reviews System** – Customer product feedback with ratings  
- **Real-Time Notifications** – SignalR-based notifications for orders & promotions  
- **Payment Processing** – Paymob integration for secure online payments  
- **Email Services** – Automated emails for order confirmation, password reset, and email verification  
- **Delivery Management** – Multiple delivery methods with flexible scheduling  
- **Shipping Address Management** – Flexible address management for customers  

---

## 🔮 Future Enhancements

- Enhanced Analytics Dashboard – Order analytics and reporting  
- Recommendation Engine – AI-powered product recommendations  
- Multi-Vendor Support – Support for multiple sellers on the platform  

---

## 💡 Why This Project Matters

- Modern backend best practices  
- Scalable, maintainable, testable architecture  
- Secure authentication & authorization  
- Integration with real payment gateways  

---

## 🏷 Tags

`.NET 9` `.AspNetCore` `.WebAPI` `.CSharp` `.CleanArchitecture` `.JWT` `.CQRS` `.EFCore` `.FluentValidation` `.Paymob` `.MailKit` `.SignalR` `.Serilog` `.MemoryCache` `.Azure` `.OAuth` `.SoftwareEngineering` `.ECommerce` `.BackendDevelopment` `.MultiLayeredArchitecture` `.DatabaseDesign`
