Background:
MYT-3108: the search text is now a parameter. Sort input is sanitized.

Tasks:

1. Improve the cleaning of the apostrophe in the search by running a HTML decoding
2. Find a better approach to avoid SQL injection in the search query. Consider using prepared statements or parameterized queries instead of manual sanitization.
3. It should be an exact match instead of partial ones.


Improvements:


