# 🛠️ Wiki: Guía de API — Atlas Navigator (Atlas-TW)

Atlas-TW expone métodos para que otros AddOns del ecosistema **Séquito del Terror** puedan consultar datos de botín y posicionamiento.

## 📡 Funciones de Datos (Loot API)

### `AtlasLoot_GetBossLoot(bossName)`
Consulta la tabla de botín oficial de un jefe específico de Turtle WoW.
- **`bossName`**: Nombre exacto del jefe.
- **Retorno**: Tabla de IDs de objetos y porcentajes.

### `AtlasQuest_Link(questID)`
Muestra la página de Atlas correspondiente a una misión de pfQuest.
- **`questID`**: ID numérica de la misión.

## 📎 Integración con Ecosistema Gravity

- **Neural Stats**: Los datos de botín preferidos por **WCS_Brain** para la optimización de equipo de la mascota pueden consultarse a través de los índices de Atlas.
- **Terror Alertas**: Si un ítem de alta prioridad (definido en TerrorMeter) cae en una mazmorra, Atlas resalta el origen en su mapa.

---
© 2026 **DarckRovert** — El Séquito del Terror.
*Cartografía de élite para la conquista de Azeroth.*
