# Gold Forever: datos

Archivos JSON que lee la web de Gold Forever: precios, ventas y chollos de las casas de subastas
de **WoW Forever** (EU). Los genera un recolector cada hora; este repositorio se reescribe entero
en cada pasada.

- Fuente: API oficial de Blizzard (Game Data API, namespaces `dynamic-forever-eu` y
  `static-forever-eu`). World of Warcraft es una marca de Blizzard Entertainment; este proyecto
  no está afiliado a Blizzard.
- Se guardan como máximo 30 días de datos, como piden los términos de la API.
- Vendedores NPC: base de datos de VMaNGOS (GPL-2.0), sin verificar en Forever.
