# Propuesta TP DSW

## Grupo
### Integrantes
48952-Franco Natalia Belén
49082- Abele Federico
50194 - Zallocco Emilio


### Repositorios
* [aplicación frontend](https://github.com/EmilioZallocco/frontend-app)
* [aplicación backend](https://github.com/EmilioZallocco/Backend-app)


## Tema
### Descripción
Proponemos elaborar una página para solicitar y reservar turnos médicos en la cual se van a poder registrar todos los doctores que atienden con sus respuestas horarios de consulta y cargar todos los pacientes para así cambiar registradores en el calendario.

### modelo
![imaginario](https://github.com/EmilioZallocco/tp/assets/129116072/7911be77-19c4-4552-9f42-cc0786e38062)


*Nota*: incluir un enlace con la imagen de un modelo, puede ser modelo de dominio, diagrama de clases, DER. Si lo prefieren pueden utilizar diagramas con [Sirena](https://mermaid.js.org) en lugar de imágenes.

## Alcance Funcional 

### Alcance Mínimo

*Nota*: el siguiente es un ejemplo para un grupo de 3 integrantes para un sistema de hotel. El 

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUDO simple|1. CRUD Tipo Paciente<hermano>2. CRUD Medico<hermano>3. CRUD Paciente|
|CRUD dependiente|1. CRUD ObraSocial{depende de} CRUD Medico<hermano>2. CRUD Horarios {depende de} CRUD Medico |
|Listado<hermano>+<hermano>detalle| 1. Listado de turnos del médico, mucho nombre médico y turnos <hermano> 2. Listado de reservas filtrado por rango de fecha, mucha nro de turno, fecha inicio, estado y nombre del paciente |
|CUU/Epic|1.Reservar turno para un determinado médico<hermano>2. Cancelar Turno|

