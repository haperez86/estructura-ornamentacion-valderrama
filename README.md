# Estructura y Ornamentación Valderrama

Demo interactiva mobile-first para validar el flujo de órdenes de trabajo de un taller de estructuras metálicas.

## Funcionalidades incluidas

- Dashboard con utilidad estimada (valor total de trabajos menos gastos).
- Valor de los trabajos, saldo por cobrar, gastos y órdenes activas.
- Creación de órdenes con consecutivo automático (OT-001, OT-002...).
- Registro de abonos por orden, con saldo precargado y validación para no superar el pendiente.
- Registro de gastos asociados a una orden.
- Detalle de órdenes con historial de abonos y gastos.
- Órdenes recientes en el dashboard.
- Planeador de entregas y alertas por fecha.
- Datos ficticios de demostración y botón para restablecerlos.

## Ejecutar localmente

Abre `index.html` directamente en un navegador moderno. No requiere backend ni dependencias.

La demo reinicia los datos ficticios al recargar la página. Los registros interactivos se conservan durante la sesión actual del navegador.

## Publicar con GitHub Pages

1. En GitHub, abre **Settings → Pages**.
2. En **Build and deployment**, selecciona **GitHub Actions** como fuente.
3. El workflow del repositorio publicará el contenido de la raíz.
4. Cuando termine el workflow, la URL de Pages aparecerá en esa misma sección.

> Esta es una demo de validación. No es un sistema productivo: no tiene autenticación, servidor ni base de datos compartida entre dispositivos. No ingreses información financiera real o sensible.

