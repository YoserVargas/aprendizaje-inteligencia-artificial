
# Día 6: Aplicaciones de IA en programación

**Estado:** Completado  
**Nivel:** Principiante  
**Duración:** 30 minutos

## 1. Objetivos

- Aprender cómo utilizar la IA para resolver problemas de programación.
- Descomponer un problema en entrada, proceso y salida.
- Escribir instrucciones claras para pedir ayuda a una IA.
- Comprender código JavaScript generado por IA.
- Revisar y probar una solución antes de utilizarla.

## 2. ¿Cómo puede ayudar la IA a programar?

La inteligencia artificial puede ayudar durante distintas etapas del desarrollo:

### Comprender un problema

Podemos pedirle que explique el objetivo y los requisitos antes de escribir código.

### Planificar una solución

Podemos dividir el problema en pasos pequeños y ordenados.

### Escribir código

La IA puede proponer funciones y explicar cómo funcionan. Debemos revisar sus sugerencias antes de utilizarlas.

### Encontrar errores

Podemos compartir el código y los mensajes de error para investigar qué está fallando.

La IA es una herramienta de apoyo, no una garantía de que el código generado sea correcto.

## 3. Descomponer un problema

Ejemplo: contar cuántas personas tienen 18 años o más.

```javascript
const edades = [12, 18, 25, 16, 40, 15];
```

- **Entrada:** un array de edades.
- **Proceso:** comprobar cuáles son mayores o iguales que 18 y contarlas.
- **Salida:** un número que indica cuántas personas cumplen la condición.

Las edades que cumplen la condición son 18, 25 y 40. El resultado esperado es `3`.

## 4. Cómo escribir una instrucción clara para la IA

Una buena instrucción debe describir el problema y el resultado que se necesita.

Ejemplo:

"Necesito una función de JavaScript que reciba un array con diferentes edades y devuelva el número de personas que tienen 18 años o más. Explícame la lógica paso a paso antes de mostrarme el código".

Una instrucción clara puede incluir:

- El objetivo.
- Los datos de entrada.
- La condición que debe cumplirse.
- El resultado esperado.
- El tipo de explicación que necesitamos.

## 5. Comprender una solución de JavaScript

```javascript
function contarMayores(edades) {
    return edades.filter(edad => edad >= 18).length;
}

console.log(contarMayores([12, 18, 25, 16, 40, 15]));
```

Resultado esperado:

```text
3
```

### ¿Cómo funciona?

- `filter()` selecciona las edades que cumplen la condición.
- `edad >= 18` significa que la edad es mayor o igual que 18.
- `.length` cuenta los elementos del array filtrado.
- `console.log()` muestra el resultado.

El array filtrado es `[18, 25, 40]`, por lo que su longitud es `3`.

### Diferencia entre `>` y `>=`

- `edad > 18`: solo incluye edades superiores a 18.
- `edad >= 18`: incluye edades de 18 o más.

Esta diferencia importa porque cambiar el operador puede producir un resultado incorrecto.

## 6. Cómo comprobar el código generado por IA

Para verificar una solución:

1. Comprender el problema.
2. Definir el resultado esperado.
3. Revisar el código.
4. Ejecutarlo.
5. Probar diferentes casos.
6. Corregir los errores.
7. Volver a comprobar los resultados.

Las pruebas ayudan a detectar errores que no siempre son evidentes al leer el código.

## 7. Actividad práctica

### Ejercicio 1: comprender el problema

Problema: contar las personas que tienen 18 años o más.

Mis respuestas:

1. Entrada: un array de edades.
2. Condición: edad mayor o igual que 18.
3. Salida: un número que indica cuántas personas cumplen la condición.
4. Resultado esperado: `3`.

Resultado: 4 de 4 respuestas correctas.

### Ejercicio 2: escribir una instrucción para la IA

Mi instrucción inicial:

"Necesito contar las personas de un grupo que tiene diferentes edades, necesito saber cuáles tienen 18 o más, y que me des el número de personas".

La instrucción expresa el objetivo y la condición. Para mejorarla, añadí que necesito una función de JavaScript, que recibe un array y que explique la lógica antes de mostrar el código.

Resultado: comprendí cómo hacer una petición más precisa.

### Ejercicio 3: analizar el código

Mis respuestas:

1. `filter()` selecciona las edades que cumplen la condición.
2. `.length` cuenta las edades seleccionadas.
3. Al utilizar `edad > 18`, la edad 18 deja de contar.

Resultado: 3 de 3 respuestas correctas.

### Pregunta final de repaso

Pregunta: ¿Qué hacer con código generado por IA que todavía no se ha ejecutado?

Mi respuesta: revisar el código, comprender cómo funciona, ejecutarlo y probar diferentes casos.

Resultado: correcto.

## 8. Conclusiones

Aprendí a utilizar la IA como apoyo durante la resolución de problemas de programación. Comprendí la importancia de definir la entrada, el proceso y la salida antes de escribir código.

También practiqué cómo formular instrucciones claras, interpretar una función de JavaScript y verificar sus resultados.

Mi objetivo no es copiar código sin entenderlo, sino utilizar la IA para aprender, resolver problemas y desarrollar mis propias habilidades de programación.

## 9. Próximo paso

Continuar con el Día 7: resolución de problemas de código con ayuda de la IA.
