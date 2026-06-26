# TUNIM — Control de Recaudo | ACCESVIAL

Aplicación optimizada para el registro de pasajeros, control de tiquetes y tarifas en tiempo real para la flota de vehículos de ACCESVIAL.

## 🚌 Tarifas por Ruta
- **Planadas Río ↔ Portal Dorado:** $3.400
- **Soacha ↔ Bogotá:** $3.700
- **Bogotá ↔ Soacha:** $3.300
- **Soacha ↔ Centro:** $2.300
- **Funza ↔ Bogotá:** $6.200
- **Funza ↔ Mosquera:** $3.000
- **Soacha ↔ Funza:** $8.000

## 🛠️ Próximas Mejoras en Firebase (Por implementar)
- [ ] **Persistencia Local (Modo Offline):** Habilitar `enablePersistence()` en Firestore para que el registro de tiquetes (como el #002) no falle en zonas sin señal.
- [ ] **Contadores Agregados en Servidor:** Crear Cloud Functions para actualizar `RECAUDADO HOY` y `PASAJEROS HOY` de forma automática.
- [ ] **Reglas de Seguridad (Antifraude):** Bloquear la edición/eliminación de tiquetes por parte de los conductores y validar los precios directamente desde Firebase Rules.
Sistema de control de recaudo y control de pasajeros .
