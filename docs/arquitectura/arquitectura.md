# Arquitectura

Este proyecto sigue una arquitectura simple basada en frontend desacoplado y uso de servicios externos (SaaS).

## Enfoque

- Frontend estático (HTML, CSS, JavaScript)
- Sin backend propio
- Integración con servicios externos para funcionalidades clave

## Flujo general

1. Usuario interactúa con la interfaz web
2. Acciones clave (como reservar) redirigen a servicios externos
3. La lógica de negocio compleja es manejada por el proveedor SaaS

## Ventajas

- Implementación rápida
- Bajo costo de mantenimiento
- No se requiere infraestructura backend

## Limitaciones

- Dependencia de terceros
- Menor control sobre la lógica de negocio