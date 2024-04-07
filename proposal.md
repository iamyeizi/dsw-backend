# Propuesta TP DSW

## Grupo

### Integrantes

- 47855 - Conti, Martin Patricio
- 47412 - Tobajas Ramírez, Ignacio
- 44865 - Fernández, Mateo Sebastian
- 42704 - Ariati, Juan Cruz

### Repositorios

- [frontend app](https://github.com/iamyeizi/dsw-frontend)
- [backend app](https://github.com/iamyeizi/dsw-backend)

## Tema

### Descripción

Desarrollo de un sistema integral de gestión para psicólogos, brindando herramientas para la administración eficiente de sus consultorios. El sistema permitirá a los psicólogos gestionar sus agendas, llevar registros de pacientes y sus historiales clínicos, así como realizar seguimiento de sesiones.

### Modelo

*Nota*: incluir un link con la imagen de un modelo, puede ser modelo de dominio, diagrama de clases, DER. Si lo prefieren pueden utilizar diagramas con [Mermaid](https://mermaid.js.org/) en lugar de imágenes.

## Alcance Funcional

### Alcance Mínimo

Regularidad:

| Req | Detalle |
|:-|:-|
| CRUD simple | 1. CRUD Psicologos<br>2. CRUD Pacientes<br>3. CRUD Historial Clinico<br>4. CRUD |
| CRUD dependiente | 1. CRUD Historial Clinico {depende de} CRUD Pacientes<br>2. CRUD Pacientes {depende de} CRUD Psicologos |
| Listado<br>+<br>detalle | 1. Listado de Pacientes filtrado por tipo de nombre, fecha de registro, fecha_ultima_sesion, edad, genero => detalle CRUD Pacientes<br>2. Listado de Historial Clinico filtrado por nombre_paciente,  fecha_sesion, tipo_sesion, fecha_ultima_sesion, progreso_tratamiento, observaciones => detalle muestra datos completos de las sesiones de un paciente |
| CUU/Epic | 1. Registro de pacientes<br>2. Registro de sesiones  |

Adicionales para Aprobación

| Req | Detalle |
|:-|:-|
| CRUD ||
| CUU/Epic ||

### Alcance Adicional Voluntario

Por ejemplo: CU cancelacion de sesion, notificaciones via mail, logs, etc.

| Req | Detalle |
|:-|:-|
| Listados |  |
| CUU/Epic |  |
| Otros |  |
