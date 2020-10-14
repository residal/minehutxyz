---
description: Minehut API Documentation
---

# Edit File

## Endpoint

**Method** `POST`

**Path** `/file/{server-id}/edit/PATH`

**Body** `{"content":"new file content"}`

**Information** Sets a file's content to the content provided, max size is 4 GB. Creates a new file if it doesn't exist already.

Requires authorization.
