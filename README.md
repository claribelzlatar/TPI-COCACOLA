# TPI-COCACOLA
## Sistema Inteligente de gestión de inventarios - The Coca Cola Company
## Descripción
Este sistema anota los movimientos: entradas y salidas.

Calcula el stock que queda.

Cuando queda poco se genera una alerta a Compras para reponer stock.

## Integrante
Claribel Denis Zlatar - Organización Empresarial - UTN
## ¿Qué problema resuelve?
Si en el depósito no estuviera este sistema, podría haber faltantes de stock y por ende afectaría la producción y ventas.
## Indicadores
###Indicador 1:

-Nombre: Precisión del inventario.

-Qué mide y para qué sirve: mide qué tan bien se registran los movimientos, y sirve para saber exactamente cuánto hay en el depósito.

-Fórmula: (stock contado en el depósito ÷ stock registrado en el sistema) × 100.

-Meta: mínimo 98%, ideal 100%.

###Indicador 2:

-Nombre: Tiempo de emisión de alertas.

-Qué mide y para qué sirve: mide cuánto tarda el sistema en avisar a Compras desde que el stock llega al punto de reorden. Sirve para que Compras pida más a tiempo y no se frene la producción.

-Fórmula: hora en que se genera la alerta − hora en que el stock llegó al punto de reorden.

-Meta: menos de 5 segundos.

## Declaración de uso de IA

**Herramientas que usé:** Google Gemini (entregas 1 a 3), Claude (entrega 4) y Copilot de GitHub (una sugerencia de mensaje de commit). No usé ChatGPT.

**En las entregas 1 a 3:** usé Gemini para producir prácticamente todo el contenido: la redacción, el FODA, el Gantt, el organigrama, el diccionario de datos y los indicadores.

**En esta entrega (4):**
- Usé Claude para que me explicara la consigna y me guiara paso a paso en GitHub, el tablero y draw.io.
- Le pedí cosas como: qué es BPMN, cómo se dibuja en draw.io, cómo crear una rama y un Pull Request.
- Claude me ayudó con la ortografía, con la redacción de dos historias de usuario y con la fórmula del indicador de precisión.
- Copilot de GitHub me sugirió un mensaje de commit en inglés y lo cambié por uno propio.

**Qué hice yo en esta reentrega:**
- Creé el repositorio, el README, la rama, los commits y el Pull Request (revisado por un compañero) y armé el tablero.
- Dibujé el BPMN en draw.io y agregué la excepción del stock que no coincide.
- Escribí la historia de ventas y las ideas de las otras dos.
- Expliqué con mis palabras para qué sirve cada indicador.
- Corregí el tablero, que tenía tarjetas en estados que no eran reales, y un error mío (había escrito que Compras vende, y quien vende es Ventas).
