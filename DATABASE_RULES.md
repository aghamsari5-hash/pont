# DATABASE RULES — PONT CAFE

Database must use real Laravel migrations.

Main entities:

Categories:
- id
- parent_id
- slug
- status
- sort_order

Products:
- id
- category_id
- price
- status
- availability

Translations:
- category translations
- product translations

Images:
- product images

Admin:
- users
- roles if required

Rules:
- No hardcoded arrays as database replacement.
- Use relationships.
- Validate all input.
- Add indexes based on queries.