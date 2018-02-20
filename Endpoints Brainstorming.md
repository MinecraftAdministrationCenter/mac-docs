# Global Endpoints

GET     /global/api

GET     /global/info

GET     /global/status

GET     /global/encryption-key

---
# v1 Endpoints

## Relevant Hardware Informations

GET     /v1/hardware/memory

GET     /v1/hardware/cpu

GET     /v1/hardware/storage

GET     /v1/hardware/network

## Relevant Software Informations

GET     /v1/software/java

GET     /v1/software/minecraft

## Minecraft Server - Basic Controls

POST    /v1/minecraft/start

POST    /v1/minecraft/stop

POST    /v1/minecraft/kill

POST    /v1/minecraft/console/msg

POST    /v1/minecraft/console/cmd

CONNECT /v1/minecraft/console/live

GET     /v1/minecraft/logs

GET     /v1/minecraft/log/:file

GET     /v1/minecraft/stats

GET     /v1/minecraft/properties

GET     /v1/minecraft/properties/:key

PUT     /v1/minecraft/properties/:key

DELETE  /v1/minecraft/properties/:key

DELETE  /v1/minecraft/properties

## Minecraft Server - Bukkit Controls

GET     /v1/bukkit/plugins

GET     /v1/bukkit/plugin/:id

PUT     /v1/bukkit/plugin

DELETE  /v1/bukkit/plugin/:id

## Minecraft Server - Forge Controls

GET     /v1/forge/mods

GET     /v1/forge/mod/:id

PUT     /v1/forge/mod

DELETE  /v1/forge/mod/:id

---
*to be continued...*
