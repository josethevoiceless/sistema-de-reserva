
### Sistema de Reservas para un Hotel 

Este repositorio contiene la implementación de un sistema de reservas para un hotel en Java. El sistema está diseñado para permitir a los usuarios realizar reservas de habitaciones de forma online, así como a los administradores gestionar las habitaciones disponibles.

#### Funcionalidades

- **Usuarios:**
  - Registrarse e iniciar sesión.
  - Buscar habitaciones disponibles por fechas.
  - Reservar y cancelar sus propias reservas.
  - Ver detalles de sus reservas pasadas y activas.

- **Administradores del Hotel:**
  - Añadir o eliminar habitaciones.
  - Modificar detalles de las habitaciones.
  - Ver listas de todas las reservas.

- **Habitaciones:**
  - Clasificación en diferentes tipos (individual, doble, suite).
  - Precio por noche, capacidad máxima de huéspedes y comodidades.

#### Estructura del Código

El código se organiza en las siguientes clases:

- **AuthService:** Implementación del servicio de autenticación para usuarios.
- **Habitacion:** Clase abstracta que representa una habitación con métodos para verificar disponibilidad.
- **HabitacionEstandar:** Implementación concreta de una habitación estándar.
- **SistemaReservas:** Interfaz que define el comportamiento del sistema de reservas.
- **SistemaReservasImpl:** Implementación concreta del sistema de reservas.
- **Usuario:** Clase que representa a un usuario del sistema.
- **Administrador:** Clase que representa a un administrador del hotel.
- **Reserva:** Clase que representa una reserva de habitación.

#### Instrucciones de Ejecución

Para ejecutar el sistema, sigue estos pasos:

1. Clona este repositorio en tu máquina local.
2. Abre el proyecto en tu entorno de desarrollo Java preferido.
3. Compila y ejecuta el archivo principal que contiene la lógica del sistema.

