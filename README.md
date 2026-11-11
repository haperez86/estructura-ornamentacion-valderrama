# Estructura y Ornamentación Valderrama

Aplicación interactiva mobile-first para gestionar las órdenes de trabajo de un taller de estructuras metálicas.

## Estado inicial

La aplicación inicia completamente vacía: no incluye clientes, órdenes, abonos ni gastos de ejemplo. Los indicadores comienzan en cero. Registra la primera orden desde el botón **Nueva orden**.

## Funcionalidades incluidas

- Dashboard con utilidad estimada (valor total de trabajos menos gastos).
- Valor de los trabajos, saldo por cobrar, gastos y órdenes activas.
- Creación de órdenes con consecutivo automático (OT-001, OT-002...).
- Registro de abonos por orden, con saldo precargado y validación para no superar el pendiente.
- Registro de gastos asociados a una orden.
- Detalle de órdenes con historial de abonos y gastos.
- Órdenes recientes en el dashboard.
- Planeador de entregas y alertas por fecha.

## Ejecutar localmente

Abre `index.html` directamente en un navegador moderno. No requiere backend ni dependencias.

**Importante:** esta versión es una demo sin persistencia. Los datos que registres estarán disponibles mientras mantengas abierta la página. Al recargarla o cerrarla, se borrarán y la aplicación volverá a iniciar vacía.

## Publicación

El repositorio se publica con GitHub Pages desde la rama `main`, carpeta `/(root)`.

> Esta es una demo de validación. No es un sistema productivo: no tiene autenticación, servidor ni base de datos compartida entre dispositivos. No ingreses información financiera real o sensible.
