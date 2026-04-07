# ❓ Wiki: FAQ [El Séquito del Terror] — Atlas-TW

Preguntas frecuentes y resolución de problemas técnicos para el navegador de mazmorras v9.4+.

## 🛠️ Error: No veo los jefes de las mazmorras custom de Turtle WoW.
- **Causa**: Atlas-TW requiere cargar módulos específicos para las zonas personalizadas del servidor.
- **Solución**: Asegúrate de que las carpetas `TWAtlas`, `TWLoot` y `TWQuest` estén dentro de `Interface\AddOns\Atlas-TW\`. Si el error persiste, realiza un `/reloadui`.

## ⚙️ ¿Por qué los porcentajes de botín no coinciden con mi WoW?
- **Sincronización**: Los porcentajes son estimativos basados en la base de datos global de Turtle WoW. Los cambios en los parches del servidor pueden tardar unos días en reflejarse en la base de datos de Atlas.

## ⚡ El juego da tirones al abrir Atlas por primera vez.
**Estado**: ✅ Optimizado en v9.4.0.
- El motor de carga ahora usa **Selective Loading** para no saturar el cliente al iniciar la sesión.

---
© 2026 **DarckRovert** — El Séquito del Terror.
*Cartografía de élite para la conquista de Azeroth.*
