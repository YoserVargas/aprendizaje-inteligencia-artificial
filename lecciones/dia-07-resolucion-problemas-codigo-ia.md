
# Día 7: Resolución de problemas de código con IA

**Estado:** Completado  
**Nivel:** Principiante  
**Duración:** 30 minutos

## 1. Objetivos

- Identificar diferentes tipos de errores en programación.
- Aprender a describir un error a una IA.
- Investigar las posibles causas de un problema.
- Comprender las correcciones propuestas por IA.
- Ejecutar pruebas para comprobar que una solución funciona.

## 2. ¿Qué es la depuración?

La depuración, también conocida como debugging, es el proceso de encontrar, comprender y corregir errores en un programa.

Existen tres tipos de errores:

### Error de sintaxis

Ocurre cuando el código no respeta las reglas del lenguaje de programación.

### Error de ejecución

Ocurre un problema mientras el programa se está ejecutando.

### Error lógico

El programa se ejecuta, pero produce un resultado diferente del esperado.

Ejemplo:

```javascript
function multiplicar(a, b) {
  return a + b;
}

console.log(multiplicar(4, 3));
```

El resultado es `7`, pero debería ser `12`. Es un error lógico porque se utiliza la suma en lugar de la multiplicación.

## 3. Cómo pedir ayuda a la IA para investigar un error

Una petición útil debe incluir:

1. El código donde aparece el problema.
2. El resultado esperado.
3. El resultado real o el mensaje de error.
4. Una petición concreta para investigar la causa.

Ejemplo de instrucción:

"Estoy aprendiendo JavaScript. Mi función debería sumar dos números, pero devuelve un resultado incorrecto. Ayúdame a identificar la causa, explícame el error y dame una pista para corregirlo antes de mostrarme la solución completa".

Cuanto más clara sea la información proporcionada, más útil puede ser la ayuda de la IA.

## 4. Investigar antes de corregir

Cuando la IA propone una solución, debo:

1. Leer y comprender la explicación.
2. Comprobar si la causa propuesta coincide con el código.
3. Realizar un cambio concreto.
4. Ejecutar el programa.
5. Probar diferentes valores.
6. Comparar los resultados con lo esperado.

Es mejor cambiar una cosa a la vez para poder identificar qué solucionó el problema.

## 5. Ejemplo: calcular un descuento

Código inicial:

```javascript
function calcularDescuento(precio, descuento) {
  return precio - descuento;
}

console.log(calcularDescuento(10000, 20));
```

El resultado es `9980`, pero el precio final esperado es `8000`.

El problema es que se resta el número 20 directamente en lugar de calcular el 20 % del precio.

Una corrección sería:

```javascript
function calcularDescuento(precio, descuento) {
  return precio - (precio * descuento / 100);
}

console.log(calcularDescuento(10000, 20));
```

Resultado esperado:

```text
8000
```

Aprendizaje: hay que comprender la causa del error y comprobar que la corrección resuelva el problema.

## 6. Ejemplo: comprobar una condición

Código inicial:

```javascript
function esMayorDeEdad(edad) {
  return edad > 18;
}
```

La regla es considerar mayores de edad a las personas que tienen 18 años o más.

El error está en el operador `>` porque excluye a quienes tienen exactamente 18 años.

Corrección:

```javascript
function esMayorDeEdad(edad) {
  return edad >= 18;
}
```

Pruebas:

| Edad | Resultado esperado |
|---|---|
| 17 | false |
| 18 | true |
| 19 | true |

Aprendizaje: los casos límite ayudan a descubrir errores en las condiciones.

## 7. Actividad práctica

### Ejercicio 1: identificar el error

Una función llamada `multiplicar` utiliza `+` en lugar de `*`.

Mi primera respuesta fue error de sintaxis. La respuesta correcta era error lógico, porque el código se ejecuta, pero realiza una operación diferente de la esperada.

### Ejercicio 2: investigar el descuento

1. Identifiqué que se restaba 20 directamente en lugar de calcular el porcentaje.
2. Elegí pedirle a la IA una explicación de la causa y una corrección paso a paso.

Resultado: ambas respuestas correctas.

### Ejercicio 3: comprobar una condición

1. Identifiqué que `>` excluye la edad exacta de 18.
2. Elegí probar las edades 17, 18 y 19.

Resultado: ambas respuestas correctas.

### Pregunta final de repaso

Pregunta: ¿Qué hacer después de que la IA propone una corrección?

Mi respuesta: comprender la causa del error, ejecutar el código corregido y probar distintos casos, incluidos los límites importantes.

Resultado: correcto.

## 8. Conclusiones

Aprendí que los errores pueden ser de sintaxis, ejecución o lógica. También comprendí que una buena petición a la IA debe explicar el problema, el resultado esperado y lo que realmente sucede.

Para resolver errores debo investigar la causa, comprender la corrección y probar el código. La IA puede ayudarme, pero necesito verificar sus sugerencias y comprobar que la solución funcione.

## 9. Próximo paso

Continuar con el Día 8: desarrollo de un proyecto práctico con ayuda de la IA.
