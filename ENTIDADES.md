# Entidades del Sistema (Prueba Repo 2)

Este repositorio contiene la definición y el modelo de entidades del proyecto.

## Estructura de Entidades

### 1. Usuario (User)
- `id`: Identificador único (UUID / Auto-incremental)
- `nombre`: Nombre completo del usuario
- `email`: Correo electrónico único
- `password_hash`: Hash de la contraseña de acceso
- `rol`: Rol dentro del sistema (`ADMIN`, `USER`, `GUEST`)
- `created_at`: Fecha y hora de creación
- `updated_at`: Fecha y hora de última actualización

### 2. Producto (Product)
- `id`: Identificador único
- `titulo`: Título o nombre del producto
- `descripcion`: Descripción detallada
- `precio`: Precio actual del producto
- `stock`: Cantidad disponible en inventario
- `categoria_id`: Llave foránea hacia la categoría
- `created_at`: Fecha de registro

### 3. Categoría (Category)
- `id`: Identificador único
- `nombre`: Nombre de la categoría
- `slug`: Identificador amigable para URLs

---
*Generado y gestionado automáticamente mediante Git y la API de GitHub.*
