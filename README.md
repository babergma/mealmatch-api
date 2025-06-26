# MealMatch API 🍽️🐶

A playful little backend project that returns ideal dog meal recommendations based on breed, age, and weight. Built for fun and learning — and inspired by my love of dogs, personalization, and product-minded backend systems.

### 💡 What it does:
- Accepts inputs like dog breed, age, and weight
- Returns a mock meal profile with calories, protein mix, and portion suggestions
- Great as a backend sandbox for REST API design, input validation, and testing

### 🧰 Tech Stack:
- Java + Spring Boot
- JUnit (for testing)
- Optional: Swagger/OpenAPI for endpoint docs
- Mock data (JSON or static files)

### 📦 Example API Call:
```http
POST /api/meal
{
  "breed": "Labrador Retriever",
  "age": 3,
  "weight": 70
}
