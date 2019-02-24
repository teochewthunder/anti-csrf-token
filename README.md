# Anti CSRF Token

This is a demo on one of the commonly accepted ways to defeat Cross-Site Request Forgery, CSRF.

# HTML
A hidden field that holds the value of a session variable, generated at login time.

# PHP
When processing POST requests, validate the value of the hidden field against the value of the session variable. If the value does not matcj, then the request does *not* originate from the correct user.
