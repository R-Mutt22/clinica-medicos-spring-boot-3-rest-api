# clinica-medicos-spring-boot-3-rest-api

Java  
-Cree una API Rest de Java desde cero con Spring Boot  
-Desarrolle CRUD usando la base de datos MySQL  
-Use Flyway como una herramienta de migración de API  
-Realice validaciones usando Bean Validation  
-Realice paginación de datos API  
  
# Clínica Médicos - API REST

![Clinica Médicos](https://via.placeholder.com/800x200.png?text=Clinica+M%C3%A9dicos+API) <!-- Puedes reemplazar esta URL con una imagen relevante -->

## Descripción

La **Clínica Médicos** es una API REST desarrollada con **Spring Boot 3** que permite gestionar la información de pacientes, médicos y citas en una clínica. Este proyecto tiene como objetivo facilitar la administración de datos médicos y mejorar la eficiencia en la gestión de citas y pacientes.

## Características

- **Gestión de Pacientes:** Agregar, actualizar, eliminar y consultar información de pacientes.
- **Gestión de Médicos:** Agregar, actualizar, eliminar y consultar información de médicos.
- **Gestión de Citas:** Programar, cancelar y consultar citas médicas.
- **API RESTful:** Cumple con los principios REST, permitiendo una fácil integración con aplicaciones frontend.

## Tecnologías Utilizadas

- **Java 17**
- **Spring Boot 3**
- **Spring Data JPA**
- **Hibernate**
- **MySQL**
- **Maven**
- **Postman** (para pruebas de API)

## Instalación

Sigue estos pasos para configurar y ejecutar la API en tu entorno local:

1. **Clona el repositorio:**

   ```bash
   git clone https://github.com/R-Mutt22/clinica-medicos-spring-boot-3-rest-api.git

2. **Navega al directorio del proyecto:**

   ```bash
   cd clinica-medicos-spring-boot-3-rest-api

3. **Configura la base de datos:**

-Crea una base de datos en MySQL llamada clinica_medicos.
-Actualiza el archivo application.properties con tus credenciales de MySQL.

   ```bash
   spring.datasource.url=jdbc:mysql://localhost:3306/clinica_medicos
   spring.datasource.username=tu_usuario
   spring.datasource.password=tu_contraseña
   ```

4. **Ejecuta el proyecto:**

   ```bash
   mvn spring-boot:run


## Uso

Una vez que la API esté en funcionamiento, puedes utilizar herramientas como **Postman** para interactuar con los siguientes endpoints:

### Pacientes:
- `GET /api/pacientes` - Obtener todos los pacientes.
- `POST /api/pacientes` - Agregar un nuevo paciente.
- `PUT /api/pacientes/{id}` - Actualizar un paciente existente.
- `DELETE /api/pacientes/{id}` - Eliminar un paciente.

### Médicos:
- `GET /api/medicos` - Obtener todos los médicos.
- `POST /api/medicos` - Agregar un nuevo médico.
- `PUT /api/medicos/{id}` - Actualizar un médico existente.
- `DELETE /api/medicos/{id}` - Eliminar un médico.

### Citas:
- `GET /api/citas` - Obtener todas las citas.
- `POST /api/citas` - Programar una nueva cita.
- `DELETE /api/citas/{id}` - Cancelar una cita.

## Contribuciones

Si deseas contribuir a este proyecto, siéntete libre de abrir un **issue** o enviar un **pull request**. Todas las contribuciones son bienvenidas.

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.

## Contacto

Para más información, puedes contactarme a través de:

- **LinkedIn:** [Tu perfil de LinkedIn](https://www.linkedin.com/in/matiaszelarayan22/)
- **GitHub:** [R-Mutt22](https://github.com/R-Mutt22)
