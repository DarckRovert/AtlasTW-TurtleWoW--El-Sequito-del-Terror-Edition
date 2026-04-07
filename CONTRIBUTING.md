# Contributing to Atlas-TW (Instance Maps) 🎭🗺️

¡Gracias por contribuir a la cartografía del **Séquito del Terror**! Para mantener el estándar **Diamond Tier** de **DarckRovert**, todas las contribuciones deben centrarse en la precisión de los datos de Turtle WoW.

---

## 🛡️ Estándares Técnicos (Dungeon Core)

Este AddOn está optimizado para **Turtle WoW** (WoW v1.12.1). Las contribuciones DEBEN cumplir con:

1.  **Loot Synchronization**: Asegúrate de que las IDs de los objetos coincidan con la base de datos actual de Turtle WoW.
2.  **No Lua 5.1+**: El motor es Lua 5.0. Prohibido el operador `#` (usa `table.getn`).
3.  **Performance Focus**: No cargues bases de datos pesadas en memoria de forma innecesaria. Usa el sistema de carga bajo demanda de Atlas.
4.  **Skin Cohesion**: Cualquier nueva interfaz debe ser compatible con los perfiles visuales de pfUI.

## 📐 Arquetipo de Desarrollo

Si deseas contribuir:
- **`TWLoot/`**: Contiene las tablas de botín de cada jefe. Es la parte más dinámica.
- **`TWAtlas/`**: Contiene los mapas y la lógica de navegación por coordenadas.
- **`TWQuest/`**: Vinculación de misiones de instancia de pfQuest a las páginas de jefes.

## 💎 Proceso de Pull Request

1.  **Fork & Branch**: Trabaja en ramas descriptivas (`fix/dungeon-loot`, `feature/custom-map`).
2.  **Documentación**: Actualiza `CHANGELOG.md` antes de enviar el PR.
3.  **Branding**: Mantén los enlaces institucionales oficiales de **DarckRovert**.

---
© 2026 **DarckRovert** — El Séquito del Terror.
*Cartografía de élite para la conquista de Azeroth.*