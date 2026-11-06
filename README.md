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

