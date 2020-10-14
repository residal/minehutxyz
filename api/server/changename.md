---
description: Minehut API Documentation
---

# Change Name

## Endpoint

**Method** `POST`

**Path** `/servers/{server-id}/change_name`

**Body** `{"name":"new name"}`

**Information** Tries to change the name of the server. If the name is taken, Error 400 is returned.

Requires authorization.
