# Dvolada Local — Demo visual v0.1

Demostración independiente del sistema presencial **Dvolada Local** de Nexora Systems.

## Cómo verla
Esta rama incluye un `index.html` autocontenido que se puede publicar con GitHub Pages.

Para habilitar la URL pública:
1. Abrir **Settings → Pages** del repositorio.
2. En **Build and deployment**, elegir **Deploy from a branch**.
3. Seleccionar **main** y **/(root)**.
4. Presionar **Save** y consultar la dirección publicada en la misma página.

La URL esperada es `https://dvoladanexora.github.io/Dvolada-Local/`, sujeta a la configuración de GitHub Pages.

## Módulos de referencia
- Inicio con navegación flotante.
- Mesas, pedidos y cocina (KDS).
- Caja (POS) con venta de ejemplo.
- Inventario, reportes, personal y configuración.
- Vista de futura vinculación Dvolada Plus.

## Importante
- **Demo, no producción:** los datos y operaciones son simulados, se almacenan en el navegador cuando está permitido.
- No existen cobros reales, autenticación real ni conexión activa con Dvolada Online.
- La integración con Dvolada Online requerirá API autenticada, licencia Plus válida, idempotencia, aislamiento entre negocios y pruebas en QA.
- Este repositorio está separado de `dvoladanexora/DVolada-3.0.` y no modifica sus ramas ni su base de datos.

## Próximo paso
Desarrollar API/Worker y D1 propios para Local, módulos persistentes y conector Plus con pruebas aisladas.
