# JSON Schema Structure for Questions

This document provides an overview of the JSON schema used in the project for representing questions.

## Schema Definition

The JSON schema defines the structure of a question object, including the required fields and their data types.

### Required Fields
- **id**: `string` - A unique identifier for the question.
- **question_text**: `string` - The text of the question.
- **options**: `array` - An array of possible answers to the question.
  - Each option can be an object containing:
    - **value**: `string` - The text for the answer option.
    - **is_correct**: `boolean` - Indicates if this option is the correct answer.
- **category**: `string` - The category to which the question belongs.
- **difficulty**: `string` - Difficulty level of the question (e.g., Easy, Medium, Hard).

### Example

```json
{
  "id": "q1",
  "question_text": "What is the capital of France?",
  "options": [
    { "value": "Berlin", "is_correct": false },
    { "value": "Madrid", "is_correct": false },
    { "value": "Paris", "is_correct": true },
    { "value": "Rome", "is_correct": false }
  ],
  "category": "Geography",
  "difficulty": "Easy"
}
```

## Conclusion

This schema ensures that all question objects conform to a standard structure, which facilitates consistency and validity in data processing.