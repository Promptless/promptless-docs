---
slug: /api-reference
sidebar_position: 5
---

# API Reference

This page documents the available API endpoints for the Promptless service.

## Random Number Generation

The API provides endpoints for generating random numbers for various use cases.

### Get Random Number

Generates a random integer between 1 and 100.

**Endpoint:** `/api/random`

**Method:** GET

**Response:**

```json
{
  "random": 42
}
```

**Example:**

```bash
curl https://api.gopromptless.ai/api/random
```

### Get Random Number in Range

Generates a random integer within a specified range.

**Endpoint:** `/api/random/range`

**Method:** GET

**Parameters:**

| Parameter | Type | Default | Description |
|-----------|------|---------|-------------|
| min | integer | 1 | The minimum value (inclusive) |
| max | integer | 100 | The maximum value (inclusive) |

**Response:**

```json
{
  "random": 42,
  "min": 1,
  "max": 100
}
```

**Example:**

```bash
# Get a random number between 1 and 100 (default)
curl https://api.gopromptless.ai/api/random/range

# Get a random number between 10 and 50
curl https://api.gopromptless.ai/api/random/range?min=10&max=50
```

## Error Handling

All API endpoints return standard HTTP status codes:

- 200: Success
- 400: Bad request (e.g., invalid parameters)
- 500: Server error

Error responses include a JSON object with an error message:

```json
{
  "error": "Error message details"
}
```