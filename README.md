## Real Valladolid - Base de Datos en Access
Descripcion del Proyecto
Base de datos relacional en Microsoft Access para la gestion integral de un club de futbol profesional.

Proyecto educativo para la asignatura de Aplicaciones Ofimaticas.

Objetivo
Gestionar toda la informacion de un club de futbol:

Jugadores (activos, lesionados, canteranos, idolos)

Equipos y entrenadores

Partidos y estadisticas

Socios, sanciones y merchandising

Viajes, eventos y patrocinadores

Palmares historico y transferencias

Estructura
Tablas (17)
Entrenadores

Equipos

Estadistica

Jugadores

Lesiones

Merchandising

Partidos

Socios

Viajes

Palmares

Patrocinadores

Idolos

Canteranos

Eventos

Premios Individuales

Sanciones

Transferencias

Relaciones (16)
Todas con integridad referencial.

Equipos -> Jugadores (1:N)

Equipos -> Entrenadores (1:N)

Equipos -> Partidos (1:N)

Jugadores -> Lesiones (1:N)

Jugadores -> Transferencias (1:N)

Socios -> Sanciones (1:N)

Partidos -> Estadistica (1:N)

Formularios
Todos incluyen cuadros combinados para facilitar la seleccion de datos.

Consultas (12)
Jugadores Activos

Jugadores Delanteros

Jugadores Sin Fotos

Jugadores con Lesion Activa

Socios con Sanciones

Partidos en Casa (1er Equipo)

Entrenadores con Contrato Vigente

Canteranos con Debut

Jugadores Veteranos

Jugadores por Nacionalidad

Tecnologias
Microsoft Access

SQL

Microsoft Word

Contexto Educativo
Asignatura: Aplicaciones Ofimaticas
Curso: 1º SMR
