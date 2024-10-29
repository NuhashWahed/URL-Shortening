# URL-Shortening
Make a simple Django project

1. Create a form for url shortening.
2. Each url should be unique. And the key must be in 6 digits.
Example: http://localhost:8000/m3q2xt
3. Anti spamming mechanism. Example: if anyone uses the address more than 3 times from the same IP within 1 minute, we will block the IP for 5 minutes. Here the numbers are configurable from form.
