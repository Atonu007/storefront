# Storefront

Storefront is a powerful Django-based e-commerce platform designed to deliver a seamless shopping experience. This project incorporates four essential APIs using Django, Celery, PostgreSQL, Redis, and a RESTful API framework.

## APIs

1. **Products API:**
   - Retrieve a comprehensive list of all products available in the storefront.
   - Utilizes Django REST framework for efficient and standardized data representation.

2. **Individual Product API:**
   - Fetch detailed information about a specific product.
   - Provides in-depth details on product specifications, pricing, and availability.

3. **Cart API:**
   - Manage the shopping cart with functionalities like add, remove, and update items.
   - Utilizes Celery for asynchronous task processing, ensuring seamless cart updates and order processing.

4. **User Authentication API:**
   - Implements a secure authentication system for user accounts and personal information.
   - Integrates Django authentication for user registration, login, and password management.

## Technologies

- **Django:** High-level Python web framework for rapid development and clean, pragmatic design.
- **Celery:** Distributed task queue system for background task processing.
- **PostgreSQL:** Powerful, open-source relational database management system.
- **Redis:** In-memory data structure store, used for caching and improving overall system performance.

## Scope

- Seamless integration of APIs to create a cohesive shopping experience.
- Utilization of PostgreSQL for robust and scalable data storage.
- Implementation of Celery for background task processing, ensuring efficient and responsive updates.
- Integration of Redis for caching to optimize API response times.

Storefront aims to provide a reliable, secure, and feature-rich platform for both buyers and sellers, offering a dynamic and engaging online shopping experience.

---

