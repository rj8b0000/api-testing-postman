# Rudraksh Git, GitHub & Postman Assessment

This repository contains a basic assessment demonstrating the usage of **Git**, **GitHub**, and **Postman** for API testing and version control.

---

## Required Sections

- Git & GitHub usage
- Postman API testing
- API request chaining (where applicable)
- Basic CRUD operations testing

---

## Tools Used

- **Git** – Version control
- **GitHub** – Remote repository hosting
- **Postman** – API testing

---

## APIs Tested

The following REST APIs were tested using Postman:

### GET Requests

- `GET {{baseUrl}}/albums`
- `GET {{baseUrl}}/photos`
- `GET {{baseUrl}}/posts/1`

### POST Request

- `POST {{baseUrl}}/posts`

### PUT Request

- `PUT {{baseUrl}}/posts/1?userId=1`

### DELETE Request

- `DELETE {{baseUrl}}/posts/1`

---

## Steps to Run the Project

1. **Clone the repository**

   ```bash
   git clone <repository-url>
   ```

2. **Import Postman collection**

   ```bash
   postman <collection-file>
   ```

3. **Select environment**

   ```bash
   postman <environment-file>
   ```

4. **Run requests**
   ```bash
   postman <collection-file>
   ```

## Git commands used

- `git init`
- `git add .`
- `git commit -m "Initial commit"`
- `git status`
- `git push`
- `git branch -a`
- `git checkout -b <branch-name>`
- `git merge <branch-name>`
- `git pull`
