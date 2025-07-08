# API Reference

All available API endpoints for SEFGH-AI Playground.

## `GET /search`

**Description:** Performs a search with the given query.

**Params:**
- `q` (string) — the search query
- `limit` (int) — number of results (default: 10)

## `POST /index`

**Description:** Adds or updates indexed documents.

**Body:**
```json
{
  "documents": [
    { "id": "doc1", "content": "..." },
    ...
  ]
}
