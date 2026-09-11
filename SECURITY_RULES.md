# SECURITY RULES — PONT CAFE

Required:

Authentication:
Admin area must be protected.

Validation:
Validate all user input.

Uploads:
Validate images.
Limit file size.
Protect filenames.

Environment:
Never expose secrets.

Production:
APP_DEBUG=false

Database:
Use Laravel protection against SQL injection.