---
description: Minehut API Documentation
---

# Edit Server Properties

## Endpoint

**Method** `POST`

**Path** `/server/{server-id/edit_server_properties`

**Body** `{"field":"field in properties, see list below","value":"new value for field"}`

**Fields** `max_players`, `level_type`, `level_name`, `generator_settings`, `gamemode`, `force_gamemode`, `pvp`, `spawn_mobs`, `spawn_animals`, `allow_flight`, `generator_settings`, `difficulty`, `hardcore`, `enable_command_block`, `announce_player_achievements`, `allow_nether`, `generate_structures`, `resource_pack`

**Information** Modifies a field in the server.properties file.

Requires authorization.
