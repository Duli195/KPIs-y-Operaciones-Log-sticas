# KPIs-y-Operaciones-Log-sticas
Este proyecto implementa una base de datos relacional para operaciones logísticas, creada completamente desde cero
El objetivo es simular el funcionamiento de una empresa de distribución, incluyendo inventarios, órdenes, entregas y transportistas, y calcular indicadores clave de desempeño (KPIs) logísticos como On-Time Delivery, In-Full, OTIF, rotación de inventario y lead time promedio.
La base incluye 7 tablas principales:
| Tabla                   | Descripción                                                  |
| ----------------------- | ------------------------------------------------------------ |
| **productos**           | Catálogo de productos con SKU y costo unitario.              |
| **almacenes**           | Información de los centros de distribución.                  |
| **inventario_actual**   | Stock actual de cada producto por almacén.                   |
| **movimientos_almacen** | Entradas y salidas de inventario.                            |
| **clientes**            | Datos básicos de los clientes.                               |
| **ordenes**             | Pedidos realizados por los clientes.                         |
| **entregas**            | Entregas asociadas a cada orden, con transportista y estado. |
