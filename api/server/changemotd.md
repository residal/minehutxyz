---
description: Minehut API Documentation
---

# Change MOTD

## Endpoint

**Method** `POST`

**Path** `/server/{server-id}/change_motd`

**Body** `{"motd":"New motd!"}`

**Information** Attempts to the change the MOTD of the server. Error 402 is returned if MOTD exceeds 64 character limit.

Requires authorization.
