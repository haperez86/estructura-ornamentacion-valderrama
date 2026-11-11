# Estructura y Ornamentación Valderrama

Aplicación web mobile-first para administrar las órdenes de trabajo de un pequeño taller de estructuras metálicas.

## Funcionalidades

- Dashboard con utilidad estimada, valor de trabajos, saldo por cobrar, gastos y órdenes activas.
- Creación de órdenes con consecutivo automático (OT-001, OT-002...).
- Registro de abonos vinculados a una orden.
- Selección del medio de pago de cada abono: Nequi, Daviplata o efectivo.
- Validación para impedir abonos mayores al saldo pendiente.
- Registro de gastos por categoría.
- Detalle de cada orden con historial de abonos y gastos.
- Marcación de trabajos terminados mediante un check.
- Exportación de reporte Excel (.xlsx) con cuatro hojas: Resumen, Ordenes, Abonos y Gastos.

## Estado inicial y almacenamiento

La aplicación inicia vacía, sin clientes, órdenes, abonos ni gastos ficticios.

Esta versión es una demo sin backend ni base de datos. Los registros se conservan únicamente durante la sesión actual del navegador. Al recargar o cerrar la página, los datos de esa sesión se pierden.

El reporte Excel descarga los datos disponibles en la sesión actual.

## Ejecutar localmente

Abre `index.html` en un navegador moderno. No requiere instalación local de dependencias. Para exportar a Excel, se carga SheetJS desde CDN, por lo que se necesita conexión a internet.

## Publicación

El repositorio se publica con GitHub Pages desde la rama `main`, carpeta `/(root)`.

> Esta demo no es un sistema productivo: no tiene autenticación, servidor ni base de datos compartida entre dispositivos. No ingreses información financiera real o sensible.
