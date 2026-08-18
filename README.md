## Diccionario de Datos

El conjunto de datos contiene la información de transacciones de ventas con las siguientes columnas:

| Nombre de la Columna | Tipo de Dato | Descripción |

| `ID Venta` | Alfanumérico | Identificador único de la transacción. |
| `Fecha` | Fecha / Hora | Fecha y hora en que se registró la venta. |
| `Ciudad` | Texto | Ubicación geográfica donde se realizó la transacción (ej. Lima, Chiclayo, Arequipa). |
| `Segmento` | Texto | Tipo de cliente (Minorista, Empresa, Educación). |
| `Canal` | Texto | Medio por el cual se vendió (Marketplace, Tienda, Web). |
| `Vendedor` | Texto | Nombre del agente de ventas encargado. |
| `Producto` | Texto | Nombre comercial del artículo tecnológico. |
| `Categoría` | Texto | Clasificación del producto (Computadoras, Impresoras, Monitores, Accesorios, Audio, Componentes, Almacenamiento). |
| `Cantidad` | Numérico (Entero) | Número de unidades vendidas. |
| `Precio Unitario` | Numérico (Entero) | Precio de lista por cada unidad de producto. |
| `Descuento` | Numérico (Decimal/Porcentaje) | Porcentaje de descuento aplicado a la venta. |
| `Venta Bruta` | Numérico (Decimal) | Monto total antes de aplicar el descuento (`Cantidad` × `Precio Unitario`). |
| `Descuento Monto` | Numérico (Decimal) | Valor monetario restado debido al descuento aplicado. |
| `Venta Neta` | Numérico (Decimal) | Ingreso real recibido por la venta (`Venta Bruta` - `Descuento Monto`). |
| `Costo Total` | Numérico (Decimal) | Costo de adquisición o fabricación de los productos vendidos. |
| `Utilidad` | Numérico (Decimal) | Ganancia real obtenida en la transacción (`Venta Neta` - `Costo Total`). |
| `Método Pago` | Texto | Medio de pago utilizado (Yape/Plin, Transferencia, Tarjeta, Efectivo). |
| `Estado` | Texto | Condición de la venta (Completada, Cancelada). |
