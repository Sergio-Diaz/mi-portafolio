# Sistema de Gestión para Casa de Cambio de Divisas

## Descripción
Aplicación integral para la administración, control de divisas y procesamiento de operaciones de compra-venta de moneda extranjera en tiempo real. La solución está diseñada para automatizar el cálculo de tipos de cambio, llevar un arqueo de caja preciso y cumplir con los registros operativos exigidos en transacciones cambiarias.

---

## Características Principales

* **Cotización en Tiempo Real:** Configuración y actualización de tipos de cambio de compra y venta para múltiples divisas (USD, EUR, etc.).
* **Módulo de Compra-Venta:** Cálculo automático del total a entregar o recibir, aplicando comisiones o tasas preferenciales según el volumen.
* **Control de Inventario por Divisa:** Monitoreo del saldo disponible en bóveda/caja para cada tipo de moneda.
* **Arqueo y Cierre de Caja:** Registro de aperturas, movimientos intermedios y cierres diarios detallados por denominación de billetes.
* **Comprobantes de Operación:** Generación e impresión de tickets de transacción con datos del cliente y desglose de la operación.
* **Histórico y Reportes:** Registro auditable de todas las transacciones realizadas, ingresos/egresos y utilidades por margen cambiario.

---

## Flujo Operativo

1. **Apertura de Caja:** Definición del saldo inicial disponible por tipo de moneda.
2. **Ajuste de Tasas:** Registro de los tipos de cambio aplicables al día.
3. **Transacción:** Selección de moneda, tipo de operación (Compra/Venta), ingreso del monto y cálculo automático.
4. **Comprobación:** Verificación de fondos en caja e impresión del comprobante.
5. **Cierre:** Conciliación final de saldos físicos vs. saldos del sistema.

---

## Tecnologías Utilizadas

* **Backend / Lógica de Negocio:** C# / .NET Core (.NET 8)
* **Base de Datos:** SQL Server (Procedimientos almacenados para transacciones seguras)
* **Interfaz de Usuario:** Desktop / Web (según corresponda)
