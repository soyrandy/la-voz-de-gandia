# Características Principales

Descubre las funcionalidades clave que hacen de **La Voz de Gandia** una herramienta directa e interactiva.

## Funcionalidades destacadas

1. **Mapa de Incidencias en Vivo:**
   - Visualización por *pines valorados por colores*:
     - **Verde:** Pasable / Bajo impacto.
     - **Amarillo:** Requiere atención a medio plazo.
     - **Rojo:** Urgente / Riesgo para el ciudadano.
   - Mapa de calor: a mayor concentración de pines en una calle, mayor es la urgencia de intervención.

2. **Generación de Reportes PDF y Envío Automático:**
   - Crea un documento PDF automático con la *foto*, la *ubicación exacta* y la *descripción*.
   - Posibilidad de descargarlo o enviarlo con un solo clic directamente al correo del **Ayuntamiento de Gandia**.

3. **Sistema de Moderación y Control:**
   - Filtros inteligentes para garantizar que las denuncias sean legítimas y respetuosas.


```bash
# Formato de la petición generada por la app al enviar la incidencia
POST /api/v1/incidencias/crear
Content-Type: application/json

{
  "ciudad": "Gandia",
  "tipo": "Contenedor quemado",
  "gravedad": "rojo",
  "anonimo": true
}
```
