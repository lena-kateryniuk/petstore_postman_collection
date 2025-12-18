# Petstore Postman Collection

## Як запускати

1. Відкрити Postman
2. Імпортувати колекцію (файл):
   - Petstore.postman_collection.json
3. Натиснути **Run** у Postman → запускати колекцію.

## Змінні колекції

- `{{base_url}}` — базовий url для запитів
  
Наступні змінні генерується динамічно у Pre-request Script запитів, і видаляються після виконання останнього запиту
- `{{petId}}`
- `{{petName}}`
- `{{updatedPetName}}`
- `{{newStatus}}`
