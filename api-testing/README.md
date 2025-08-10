# Sample API Testing (Postman)

This folder contains a minimal Postman collection to demonstrate API testing skills:
- Public API: https://reqres.in
- Requests:
  - GET /users?page=2  → verify status and list shape
  - POST /login        → verify auth success and token presence

How to use:
1) Import `postman-collection.json` into Postman (File → Import).
2) (Optional) Import `postman-environment.json` and select the environment "QA-Portfolio".
3) Open the collection "QA Portfolio - Sample API Tests".
4) Run requests manually or use Collection Runner.
5) Check the Tests tab for assertions (they appear in the Postman test results).

Notes:
- No auth required for GET; POST /login uses demo credentials.
- Adjust tests as needed for negative/edge cases.
