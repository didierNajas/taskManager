# Task Manager

Una aplicación de gestión de tareas sencilla y ligera diseñada para mantener el orden en tu día a día. Permite organizar actividades por categorías, marcarlas como completadas y limpiar el historial de tareas finalizadas.

## Características Principales

- **Categorización Flexible**: Organiza tus tareas en diferentes contextos:
  - Trabajo
  - Estudio
  - Personal
  - Urgente
  - Otra...
- **Gestión de Estado**:
  - Crea nuevas tareas instantáneamente.
  - Marca tareas como completadas.
  - Visualiza el progreso con un contador (ej. "0 de 0 tareas completadas").
- **Limpieza Rápida**: Botón dedicado para **Limpiar completadas**, manteniendo la vista libre de tareas ya finalizadas.
- **Interfaz Minimalista**: Diseño limpio enfocado en la productividad sin distracciones.

## Cómo Usar

1. **Agregar Tarea**:
   - Selecciona una categoría (Trabajo, Estudio, etc.) o elige "Otra...".
   - Escribe el nombre de tu tarea y presiona el botón `➕ Agregar`.

2. **Completar Tarea**:
   - Haz clic en la tarea para marcarla como completada. El contador se actualizará automáticamente.

3. **Limpiar Historial**:
   - Una vez que tengas tareas completadas, haz clic en el botón 🗑️ `Limpiar completadas` para borrarlas de la lista actual.

## Tecnologías Utilizadas

*(Nota: Esta sección es un ejemplo, ajústala según el stack real de tu proyecto)*
- **Frontend**: HTML5, CSS3, JavaScript (Vanilla o framework ligero).
- **Almacenamiento**: LocalStorage (para persistencia básica en el navegador).

## Estructura del Proyecto

```text
/task-manager
├── index.html       # Estructura principal de la interfaz
├── style.css        # Estilos visuales (minimalistas)
├── app.js           # Lógica de agregar, completar y limpiar tareas
└── README.md        # Este archivo
