# Item Management REST API

## Overview
This is a simple Java Spring Boot RESTful API that allows users to manage a collection of items.
The application uses in-memory storage (ArrayList) and does not require a database.

## Features
- Add a new item
- Fetch an item by ID
- Input validation
- Global exception handling

## Technologies Used
- Java 17
- Spring Boot
- Spring Web
- Jakarta Validation
- Maven

## Project Structure
- Controller layer handles HTTP requests
- Service layer contains business logic
- Model layer defines the Item entity
- Exception layer handles errors globally

## API Endpoints

### Add Item
**POST** `/api/items`

Request Body:
```json
{
  "id": 1,
  "name": "Laptop",
  "description": "Gaming Laptop"
}
### Get Item By id
**GET** `/api/items/id`


