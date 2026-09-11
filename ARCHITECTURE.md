# ARCHITECTURE RULES — PONT CAFE

Architecture:
Laravel Monolith.

Flow:

Browser
 -> Routes
 -> Controllers
 -> Services (when needed)
 -> Models
 -> Database
 -> Blade Views

Main modules:
- Public Menu
- Admin Panel
- Categories
- Products
- Languages
- Availability
- Settings

Rules:
- Do not introduce complex architecture without need.
- Avoid microservices.
- Keep hosting requirements simple.