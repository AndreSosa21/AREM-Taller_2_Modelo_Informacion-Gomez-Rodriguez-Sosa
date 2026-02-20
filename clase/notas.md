# 🗒️ Registro de Trabajo en Clase - Taller 2

## 📆 Fecha de la sesión
14 de febrero de 2026

## 👥 Integrantes presentes
- Juan Andres Gomez 
- Samuel Andres Rodriguez
- Andrea Julieth Sosa Rodriguez

## 🧠 Actividades realizadas en clase

Durante la sesión trabajamos con el caso base de la **Clínica Salud Viva** para entender cómo modelar entidades y flujos de información:

- **Discutimos** qué entidades principales maneja una clínica (Paciente, Médico, Especialidad, Cita, Factura) y cómo se relacionan entre sí.
- **Decidimos** usar cardinalidad 1:N para la mayoría de relaciones (un paciente tiene muchas citas, un médico atiende muchas citas, etc.).
- **Identificamos** los actores clave (Paciente, Médico, Asistente) y sistemas internos (ERP, Agendamiento, BD, Notificador, Facturación) para el diagrama de contexto.
- **Mapeamos** los flujos de información: paciente solicita cita → sistema valida → notifica → médico consulta agenda → se genera factura → se valida con aseguradora.
- **Usamos** draw.io para crear los diagramas directamente en digital.
- **Logramos** terminar borradores funcionales del ERD y del diagrama de contexto durante la clase.

## 🧩 Boceto inicial del modelo

**Modelo ER borrador:** `modelo-er-borrador.drawio`  
Incluye las 5 entidades (Paciente, Médico, Especialidad, Cita, Factura) con sus atributos principales y relaciones.

**Diagrama de contexto borrador:** `contexto-borrador.drawio`  
Muestra el sistema central con sus módulos internos, actores externos (Paciente, Médico, Asistente, Aseguradora) y los flujos de datos entre ellos.

## 🔁 Tareas definidas para complementar el taller

| Tarea asignada | Responsable | Fecha estimada |
|----------------|-------------|----------------|
| Modelado final en draw.io | Juan Andres | 18/02 |
| Redacción del informe | Andrea Sosa | 20/02 |
| Investigación y referencias | Samuel Rodriguez | 20/02 |

---

_Este documento resume el trabajo colaborativo realizado durante la sesión del Taller 2 en el curso AREM - Universidad de La Sabana._
