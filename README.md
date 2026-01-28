Markdown
# RESTful API Activity - CYRUS J. FAJARDO
## Best Practices Implementation
**1.Environment Variables:**
- Why did we put `BASE_URI` in `.env` instead of hardcoding it?
- to encapsulate or hide sensitive data that malicious hackers may find and exploit
**2. Resource Modeling**
- Why did we use plural nouns (e.g., `/dishes`) for our routes?
- It is one of the best practices for the routes
**3. Status Codes:**
- When do we use `201 Created` vs `200 OK`?
- Why is it important to return `404` instead of just an empty array or a generic error?
- We use `200 OK` when the request is successful while `201 Created` is used for every POST request, it is important to return `404` to quickly identify which exactly is the error.

**4. Testing**
 - 