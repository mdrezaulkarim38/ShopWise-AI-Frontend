# ShopWise AI Frontend

A Razor Pages based frontend project for ShopWise AI.

---

## 📌 Collaboration Guidelines

To maintain a clean and scalable workflow, follow the branching strategy below.

---

## 🔀 Branching Strategy

### 🚫 Do NOT work directly on `main`

All development must follow this structure:

### 1️⃣ Create `dev` branch from `main` (Only Once)

```bash
git checkout -b dev
git push origin dev
```

---

### 2️⃣ Create Your Own Feature Branch from `dev`

Before starting work:

```bash
git checkout dev
git pull origin dev
git checkout -b feature/your-feature-name
```

Example:

```bash
git checkout -b feature/login-page
```

---

### 3️⃣ After Completing Your Work

- Push your branch:

```bash
git push origin feature/your-feature-name
```

- Create a Pull Request to `dev`
- Do NOT merge directly to `main`
- Do NOT merge directly to `dev`

All merges must go through Pull Request review.

---

# 🚀 Task Requirements

## 🔐 Authentication Module

You must create:

- Login Page
- Register Page

---

# 📝 Register Page Requirements

All fields are **mandatory**:

- Name
- Email
- Phone
- Password

---

## ✅ Validation Rules

| Field    | Requirement |
|----------|-------------|
| Name     | Required |
| Email    | Required + Must be valid email format |
| Phone    | Required |
| Password | Required (Minimum 6 characters recommended) |

### Behavior Rules:

- If any field is empty → Show validation error
- Email must be properly formatted
- Password must not be empty

---

# 🔑 Login Page Requirements

Fields:

- Email (Required)
- Password (Required)

### Validation:

- Both fields must be validated before submission
- Show proper validation messages

---

# 🧱 Development Rules

- Use proper folder structure
- Keep components reusable
- Write clean and readable code
- Do not push unnecessary files
- Always pull latest `dev` before starting new work
- Follow proper naming conventions for branches

---

# 🛑 Important Rules

- ❌ No direct push to `main`
- ❌ No direct push to `dev`
- ✅ All changes must go through Pull Request
- ✅ Resolve conflicts before merging

---

# 📂 Project Structure (Example)

```
Pages/
 ├── Login.cshtml
 ├── Register.cshtml

wwwroot/

Services/
```

---

# 🛠 Tech Stack

- ASP.NET Core Razor Pages
- HTML5
- CSS3
- JavaScript
- REST API Integration

---

# 🎯 Goal

Build a clean, maintainable, and scalable authentication module while following proper Git workflow and development standards.

---

# 📌 Notes

- Do not hardcode sensitive information
- Follow clean coding principles
- Keep UI simple and professional
- Code should be production-ready