# Guía de Referencia

La Guía de Referencia proporciona información técnica detallada sobre las características del proyecto.

## API

Este proyecto cuenta con una API REST que permite interactuar con los datos de forma programática. Aquí te dejamos los detalles principales:

### Endpoints

- **GET /api/tareas**: Recupera todas las tareas disponibles.
- **POST /api/tareas**: Crea una nueva tarea.
- **PUT /api/tareas/{id}**: Actualiza los detalles de una tarea.
- **DELETE /api/tareas/{id}**: Elimina una tarea específica.

### Ejemplo de Solicitud

Para crear una tarea, realiza una solicitud `POST` a `/api/tareas` con el siguiente cuerpo JSON:

```json
{
  "titulo": "Comprar alimentos",
  "descripcion": "Ir al supermercado a comprar víveres",
  "fecha": "2025-02-11"
}
