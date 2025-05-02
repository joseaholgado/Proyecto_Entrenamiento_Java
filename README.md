# Proyecto de Entrenamiento Java

Este es un proyecto de gestión de entrenamientos desarrollado en Java, que permite administrar rutinas de ejercicios, usuarios y planes de entrenamiento.

## Estructura del Proyecto

El proyecto está organizado en las siguientes carpetas principales:

### `/ProyectoEntreno/src/main/java`
- **auxiliares/interfaces**: Contiene interfaces auxiliares como ReproductorAudio
- **clases**: Contiene las clases principales del modelo de negocio
  - Calistenia.java
  - Ejercicio.java
  - Entrenamiento.java
  - Gimnasio.java
  - Material.java
  - PlanEntrenamiento.java
  - Series.java
  - Usuario.java
- **enumeration**: Enumeraciones para la gestión de datos
  - Musculo.java
  - NivelUsuario.java
  - TipoEjercicio.java
- **exception**: Excepciones personalizadas
  - ContraseñaInvalidaExcepcion.java
  - NombreConNumerosException.java
  - UsuarioNoExisteException.java
- **interfaces**: Interfaces del sistema

### `/Base_de_datos`
Contiene los archivos SQL para la gestión de la base de datos del proyecto.

### `/OtrosEntreno`
Contiene recursos adicionales organizados por categorías de ejercicios:
- Brazos
- Espalda
- Hombros
- Pecho
- Piernas
- Materiales

## Características Principales

- Gestión de usuarios con diferentes niveles
- Control de ejercicios y rutinas de entrenamiento
- Planificación de entrenamientos
- Gestión de materiales y equipamiento
- Base de datos integrada
- Interfaz gráfica de usuario
- Recursos visuales para ejercicios

## Requisitos Técnicos

- Java JDK 8 o superior
- Base de datos MySQL
- Biblioteca JCalendar para gestión de fechas

## Dependencias

- JCalendar 1.4 (incluida en el proyecto)
- Controladores MySQL para la conexión a la base de datos

## Instalación

1. Clonar el repositorio
2. Importar el proyecto en su IDE favorito
3. Configurar la base de datos usando el script SQL proporcionado en la carpeta `Base_de_datos`
4. Ejecutar la aplicación

## Licencia

Este proyecto está disponible para uso educativo y personal.
