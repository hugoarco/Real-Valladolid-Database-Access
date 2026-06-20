<h1 align = "center" >Real Valladolid – Sistema de Gestión de Base de Datos (Microsoft Access)</h1> 

Sistema de base de datos relacional diseñado en Microsoft Access para la gestión integral de la información de un club de fútbol profesional.

El proyecto simula el funcionamiento interno de un departamento de gestión deportiva, centralizando datos de jugadores, equipos, competiciones y estructura organizativa del club.

🎯 Objetivo del sistema
Desarrollar un modelo de base de datos capaz de gestionar de forma estructurada toda la información clave de un club de fútbol, permitiendo:

Control de plantilla y персонal deportivo
Seguimiento de lesiones, sanciones y rendimiento
Gestión de partidos y estadísticas
Administración de socios y actividades del club
Registro de eventos, viajes y patrocinadores
Historial deportivo y transferencias
<br><br>

🗂️ Modelo de datos

📌 Entidades principales (17 tablas)
Entrenadores
Equipos
Jugadores
Estadísticas
Lesiones
Partidos
Socios
Sanciones
Merchandising
Viajes
Patrocinadores
Eventos
Palmarés
Ídolos históricos
Canteranos
Premios individuales
Transferencias
<br><br>

🔗 Relaciones del sistema
El modelo relacional está diseñado con integridad referencial completa, garantizando coherencia entre entidades.

Ejemplos de relaciones:

Equipos → Jugadores (1:N)
Equipos → Entrenadores (1:N)
Equipos → Partidos (1:N)
Jugadores → Lesiones (1:N)
Jugadores → Transferencias (1:N)
Partidos → Estadísticas (1:N)
Socios → Sanciones (1:N)
<br><br>
📊 Consultas implementadas

El sistema incluye consultas para análisis y gestión de información:

Plantilla de jugadores activos
Jugadores por posición (delanteros, etc.)
Jugadores lesionados o sin imagen
Socios con sanciones activas
Partidos disputados en casa
Entrenadores con contrato vigente
Canteranos con debut en primer equipo
Jugadores veteranos
Filtrado por nacionalidad
<br><br>

🧩 Interfaz del sistema
Formularios interactivos para gestión de datos
Navegación estructurada entre entidades
Uso de cuadros combinados para optimizar la selección de registros
Diseño orientado a facilitar la administración de información compleja

<br><br>

🛠️ Tecnologías utilizadas
Microsoft Access (modelo relacional)
SQL (consultas estructuradas)
Microsoft Word (documentación técnica del modelo)

<br><br>

🎓 Contexto académico
Asignatura: Aplicaciones Ofimáticas
Curso: 1º SMR
Proyecto de diseño y modelado de base de datos relacional

<br><br>

💡 Enfoque del proyecto
Este proyecto simula un sistema real de gestión interna de un club deportivo, aplicando conceptos de:

Modelado entidad-relación
Normalización de bases de datos
Integridad referencial
Diseño de consultas y formularios
Gestión estructurada de información
<br><br>

👨‍💻 Autor
Desarrollado por Hugo Arco 
