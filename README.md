# 🧪 API Testing – JSONPlaceholder

> Manual API testing project covering full CRUD operations on the JSONPlaceholder REST API.

---

## 📌 Project Info

| Field | Details |
|-------|---------|
| **Project** | JSONPlaceholder API Testing |
| **URL** | https://jsonplaceholder.typicode.com |
| **Date** | 17.04.2026 |
| **Tester** | Romanyuk Roman |
| **Environment** | Windows 11 Pro 25H2, Postman 12.6.7 |

---

## 🎯 Scope

Testing REST API endpoints for the **Posts** resource:

| Method | Endpoint | Description |
|--------|----------|-------------|
| `GET` | `/posts` | Get list of all posts |
| `GET` | `/posts/{id}/comments` | Get comments for a specific post |
| `POST` | `/posts` | Add new post |
| `PUT` | `/posts/{id}` | Update post (full update) |
| `PATCH` | `/posts/{id}` | Change post title (partial update) |
| `DELETE` | `/posts/{id}` | Delete post |

---

## 🛠 Tools Used

- **Postman** 12.6.7 — API requests & collections
- **JSONPlaceholder** — free fake REST API for testing
- **Excel** — test cases & checklist documentation

---

## 📋 Test Cases

| TC ID | Summary | Pre-conditions | Expected Result | Status |
|-------|---------|----------------|-----------------|--------|
| TC-001 | Get list of posts | DB contains at least one post | Status: 200 OK | ✅ Passed |
| TC-002 | Get comments for a specific post | Post with id=10 exists | Status: 200 OK | ✅ Passed |
| TC-003 | Add new post | Valid request body is prepared | Status: 201 Created | ✅ Passed |
| TC-004 | Update post | Post with id=5 exists | Status: 200 OK | ✅ Passed |
| TC-005 | Change post title | Post with id=5 exists | Status: 200 OK | ✅ Passed |
| TC-006 | Delete post | Post with id=10 exists | Status: 200 OK | ✅ Passed |

---

## 📄 Test Artifacts

- 📂 [Postman Collection](https://github.com/RRomanyuk/api-testing-jsonplaceholder/blob/29d889a3d421dfe793dfa90526015ee9b356e475/postman/API-Testing.postman_collection.json)
- 📊 [Test Cases & Checklist](https://github.com/RRomanyuk/api-testing-jsonplaceholder/blob/29d889a3d421dfe793dfa90526015ee9b356e475/test-artifacts/API_Testing_Project.xlsx)
