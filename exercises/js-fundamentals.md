Here’s a clean exercise prompt you can give your students:

---

## JavaScript Fundamentals Exercise — User Login System

### Objective

Practice working with:

- Arrays
- Objects
- Functions
- Conditionals
- Parameters

---

## Instructions

Create an array containing user account details.

Each user should have:

- `email`
- `password`

Example:

```js
const users = [
  {
    email: "john@gmail.com",
    password: "12345",
  },
  {
    email: "mary@gmail.com",
    password: "password",
  },
  {
    email: "admin@gmail.com",
    password: "admin123",
  },
];
```

---

## Task

Create a function called `loginUser`.

The function should:

1. Accept two parameters:
   - `email`
   - `password`

2. Check whether the email and password match any user in the array.

3. If the credentials are correct:
   - Console log:

   ```js
   "Successful login";
   ```

4. If the credentials are incorrect:
   - Console log:

   ```js
   "Failed login";
   ```

---

## Example Usage

```js
loginUser("john@gmail.com", "12345");
// Successful login

loginUser("john@gmail.com", "wrongpassword");
// Failed login
```

---

## Bonus Challenge

- Add a `username`
- Make email checking case-insensitive
- Display:

```js
"Welcome John";
```

after successful login.

---
