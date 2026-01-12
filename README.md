# EcoBazaar

EcoBazaar is a robust full-stack e-commerce application designed to facilitate a multi-role shopping environment. It features a high-performance **Spring Boot** backend and a responsive **React (Vite)** frontend, complete with dedicated dashboards for Admins, Sellers, and Users.

## Key Features

* **User Roles & Authentication:** Secure Login/Register flows with support for Users, Sellers, and Admins.
* **Product Management:** * Sellers can `Add`, `Edit`, and manage products via the **Seller Dashboard**.
    * Users can browse, filter, and view `ProductDetails`.
* **Shopping Experience:**
    * Full `Cart` and `Checkout` functionality.
    * `Wishlist` management for saving favorite items.
    * `ProductReviews` system for user feedback.
* **Order Management:** Track order history and status via `Orders` page.
* **Admin Controls:** Comprehensive **Admin Dashboard** for platform oversight.
* **Image Handling:** Backend support for file uploads (stored in `uploads/`).

## Tech Stack

### Frontend
* **Framework:** React.js (powered by Vite)
* **HTTP Client:** Axios
* **Routing:** React Router (implied by `pages` structure)
* **State Management:** Context API (implied by `context` folder)

### Backend
* **Framework:** Java Spring Boot
* **Build Tool:** Maven
* **Containerization:** Docker
