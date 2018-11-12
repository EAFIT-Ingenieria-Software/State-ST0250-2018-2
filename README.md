# State-ST0250-2018-2
### *Cajero con patron de diseño state*
# State Pattern

### Nombre de Integrantes
-Sebastian Bustamante
-Jhon Fernado Oquendo
-Juan Pablo Ramirez

### Explicación de la Problemática
Considere el escenario ATM. El cajero automático puede estar en varios estados / modos como trabajo, sin efectivo, error, etc. Cuando el cliente interactúa con el cajero automático, debe responder según el estado actual. Por ejemplo, cuando el cajero automático está en estado "Sin efectivo" o "Error", no se debe permitir el retiro. Normalmente, las sentencias condicionales se utilizan para implementar este tipo de comportamiento. También las mismas declaraciones condicionales pueden tener que repetirse en diferentes funciones para soportar las posibles interacciones. Esto hace que el código sea frágil y admitir un nuevo estado / operación puede volverse difícil.

El patrón de estado se puede utilizar aquí para simplificar el diseño. Por ejemplo, cuando es necesario agregar un nuevo estado ATM, se puede hacer fácilmente agregando un nuevo estado. Las otras clases se mantendrán sin cambios.
## Modelo de Clases
![enter image description here](https://lh3.googleusercontent.com/TE7BF868Ia1enpSzfbGjJOyYa473p8WutJvpJ0yoMlt6e8N3ddCvVcATCQYXTWxEZIr6Rp3UNZcf)
### Lenguaje: *Java*

#### Ejecución del Código
Ejecutar el main en la clase StateClient

### Referencias Bibliográficas
-App Desing Patterns(Gof)
-wikipedia.org
