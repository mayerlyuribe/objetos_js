# Math

En JavaScript, **Math** es un objeto incorporado especial que te brinda un conjunto de herramientas para realizar cálculos matemáticos. Es como una calculadora súper poderosa a la que puedes acceder desde tu código. Como Math es un objeto global, puedes acceder directamente a sus propiedades y métodos usando la notación de punto.

El principal uso de Math en JavaScript es realizar cálculos matemáticos y operaciones numéricas. Es una herramienta fundamental para cualquier desarrollador que trabaje con JavaScript, ya que proporciona una amplia gama de funciones y constantes que pueden ser utilizadas para una gran variedad de tareas.

## ¿Qué puedes hacer con Math?
- **Constantes matemáticas:** Proporciona valores constantes como PI (aproximadamente 3.14159) para la relación entre la circunferencia y el diámetro de un círculo, o E (aproximadamente 2.71828) para la base del logaritmo natural.

- **Funciones matemáticas:** Te ofrece una amplia gama de funciones para realizar operaciones como:
    - Funciones trigonométricas: `sin()`, `cos()`, `tan()` para calcular seno, coseno, tangente, y otras funciones relacionadas con ángulos y triángulos.

    - Redondeo: `ceil()`, `floor()`, `round()` para redondear números hacia arriba, hacia abajo, o al entero más cercano.

    - Exponenciación: `pow(x, y)` para elevar `x` a la potencia de `y`.

    - Números aleatorios: `random()` para generar un número decimal aleatorio entre 0 (inclusive) y 1 (exclusivo).

    - Valores mínimo y máximo: `min(x, y)`, `max(x, y)` para encontrar el número más pequeño o más grande entre dos valores.

    - Valor absoluto: `abs(x)` para obtener el valor sin signo (positivo) de x.

    - Raíz cuadrada: `sqrt(x)` para calcular la raíz cuadrada de un número.
## ejemplo 1. Generar un número aleatorio entre 1 y 100:
``` Javascript
const numeroAleatorio = Math.floor(Math.random() * 100) + 1;
console.log("Número aleatorio:", numeroAleatorio);
```
## ejemplo 2. Calcular la hipotenusa de un triángulo rectángulo:
``` Javascript
const catetoA = 3;
const catetoB = 4;
const hipotenusa = Math.sqrt(Math.pow(catetoA, 2) + Math.pow(catetoB, 2));
console.log("Hipotenusa:", hipotenusa);
```
## ejemplo 3. Calcular el área de un círculo:
``` Javascript
const radio = 5;
const area = Math.PI * Math.pow(radio, 2);
console.log("Área del círculo:", area);
``` 





