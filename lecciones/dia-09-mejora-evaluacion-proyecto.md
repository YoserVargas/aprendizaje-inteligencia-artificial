
# Día 9: Mejora y evaluación de un proyecto con IA

**Estado:** Completado  
**Nivel:** Principiante  
**Duración:** 30 minutos

## 1. Objetivos

- Evaluar una aplicación mediante requisitos y pruebas.
- Identificar casos límite.
- Solicitar mejoras específicas a una IA.
- Evitar cambios innecesarios que afecten funcionalidades existentes.
- Comprobar que las mejoras funcionan correctamente.

## 2. ¿Cómo evaluar una aplicación?

Una aplicación no está terminada solo porque se abra o parezca funcionar. Debe cumplir los requisitos establecidos.

El proyecto práctico es un organizador de tareas desarrollado con HTML, CSS y JavaScript.

Sus funcionalidades principales son:

1. Añadir tareas.
2. Mostrar tareas.
3. Marcar tareas como completadas.

También debe evitar que se añadan tareas vacías.

### Criterios de aceptación

Un criterio de aceptación define una condición que debe cumplirse para considerar terminada una funcionalidad.

Ejemplos:

- Una tarea añadida aparece en la lista.
- Dos tareas aparecen sin que una sustituya a la otra.
- Una tarea completada cambia su apariencia.
- Una tarea vacía no se añade.

## 3. Mejorar sin romper lo que funciona

Al incorporar una funcionalidad nueva, es importante conservar las anteriores.

Una petición útil para la IA debe explicar qué se quiere añadir, qué debe mantenerse y cómo comprobar el resultado.

Es preferible modificar solo las partes necesarias en lugar de reescribir toda la aplicación sin motivo.

Después de cada cambio, debo volver a probar las funcionalidades existentes.

## 4. Casos límite

Los casos límite son situaciones que pueden revelar errores o comportamientos inesperados.

Ejemplos para el organizador de tareas:

- Intentar añadir una tarea vacía.
- Escribir solamente espacios.
- Introducir una tarea con un nombre muy largo.
- Completar una tarea y después desmarcarla.
- Eliminar una tarea sin afectar a las demás.

Las pruebas deben comprobar que la aplicación se comporta como se espera en estas situaciones.

## 5. Escribir instrucciones claras para la IA

Mi prompt inicial fue:

"Quiero agregar un botón que pueda eliminar tareas sin modificar las otras funcionalidades. Uso HTML, JavaScript, CSS. Quiero que se mantenga agregar tareas, completarlas, pero con un botón que borre tareas también".

La instrucción identifica el objetivo, las tecnologías y las funcionalidades que deben conservarse.

Una versión mejorada sería:

"Quiero añadir un botón para eliminar cada tarea de mi organizador de tareas, desarrollado con HTML, CSS y JavaScript. Conserva las funcionalidades existentes: añadir tareas, mostrarlas y marcarlas como completadas. No reescribas toda la aplicación si no es necesario. Explícame qué cambios debo hacer en cada archivo, ayúdame a implementarlos paso a paso y dime cómo probar que el botón elimina únicamente la tarea seleccionada y que las demás funcionalidades siguen funcionando".

Una buena instrucción define el objetivo, los límites, la forma de trabajo y las pruebas necesarias.

## 6. Actividad práctica

### Ejercicio 1: detectar un problema

Problema: la aplicación permite añadir tareas vacías.

Mi respuesta: definir el resultado esperado, corregir la validación y probar que no se añadan tareas vacías.

Resultado: correcto.

### Ejercicio 2: identificar el archivo adecuado

Pregunta: ¿qué archivo se utiliza principalmente para cambiar el color de fondo sin modificar el comportamiento?

Mi respuesta: `style.css`.

Resultado: correcto.

### Ejercicio 3: mejorar una instrucción

Mi objetivo fue pedir un botón para eliminar tareas, conservando las funciones existentes de añadir y completar tareas.

Resultado: correcto. La instrucción puede mejorarse solicitando una explicación de los cambios y pruebas de funcionamiento.

### Pregunta final de repaso

Pregunta: ¿qué hacer después de modificar una aplicación con ayuda de la IA?

Mi respuesta: probar la nueva funcionalidad, comprobar los requisitos y verificar que las funciones anteriores siguen funcionando.

Resultado: correcto.

## 7. Conclusiones

Aprendí que evaluar un proyecto requiere comprobar sus requisitos mediante pruebas concretas. También comprendí la importancia de detectar casos límite y mejorar una aplicación sin alterar innecesariamente lo que ya funciona.

La IA puede ayudarme a planificar cambios y encontrar posibles errores, pero debo comprender las modificaciones y verificar sus resultados.

## 8. Próximo paso

Completar el proyecto práctico, revisar las funcionalidades principales y preparar el repaso final del curso de Inteligencia Artificial.
