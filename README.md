# Prueba Codigo Test
Esqueleto de proyecto con Cypress para realizar pruebas de codigo.

### Ejercicio
**Prueba E2E:** En la pagina https://testsheepnz.github.io/BasicCalculator.html encontraras una aplicación de calculadora muy básica, la cual permite solo las 4 operaciones matemáticas básicas, más concatenación de cadenas. Tu tarea consiste en realizar una prueba End to End de la página y la funcionalidad de la calculadora, este prueba debe constar de las siguientes validaciones:
 - Validación de UI: Se debe de validar que los componentes necesarios para la operación de la calculadora existen en la página.
 - Camino de Errores: Se debe validar que no se pueden realizar operaciones incorrectas en la calculadora, ejemplo, sumar “hola” y 3, y que aparecen mensajes relevantes a estos errores
 - Camino Feliz: Se debe validar que la calculadora da los resultados correctos cuando se le da un uso apropiado (validar las 5 operaciones permitidas).

### Tecnologías a usar
Cypress o Playwright de preferencia, tambien es válido cualquier otro framework/herramienta que te permita realizar test de E2E, como Selenium, WebDriverIO, TestCafe, etc. (Este repositorio tiene Cypress configurado y listo para usar). 

### Lenguajes a usar
Javascript o Typescript. Python también es válido en el caso de Playwright.

### Duración de la prueba
No hay un tiempo límite establecido para entregar la prueba, sin embargo, mientras más rápido la entregues, más rápido será evaluada y más rápido avanzará el proceso de tu candidatura. El tiempo no debería de ser un factor de estrés para la realización de la prueba, toma el tiempo que consideres adecuado para entregar algo con lo que te sientas satisfecho.

### Modo de Entrega
El codigo de tu prueba debe subirse a un repositorio de github, comparte este repositorio con nosotros cuando estes listo para que evaluemos tu prueba. Puedes usar este repositorio como base, haciendo un fork de el, o crear uno completamente nuevo por tu cuenta.

#### Puntos extra
Los siguientes no son requeridos para considerar tu prueba como correcta, pero si los utilizas (incluso de forma sencilla) obtendras puntos extras:
 - fixtures
 - custom commands
 - validaciones de css


## Instalacion

Se ocupa [Node.js](https://nodejs.org/) v14+.

Instalar dependencias.

```sh
cd carpeta_raiz
npm install
```

Correr Cypress

```sh
npx cypress open
```
