# DEPLOYMENT RULES — PONT CAFE

Target:
Affordable Linux hosting.

Requirements:
- PHP 8.3+
- MySQL/MariaDB
- HTTPS

Production:
- APP_DEBUG=false
- Secure .env
- Database backup
- Correct Laravel public directory

Avoid:
- Firebase dependency
- Complex cloud services
- Unnecessary servers