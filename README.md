**Proyecto KPIs y Operaciones Logísticas**


Este proyecto tiene como objetivo diseñar y analizar una base de datos relacional para operaciones logísticas, utilizando SQLite y Python sin necesidad de archivos externos.
El sistema simula el funcionamiento de una empresa de distribución que gestiona productos, almacenes, inventarios, órdenes, clientes y entregas, permitiendo calcular indicadores clave de desempeño (KPIs) y realizar consultas operativas en tiempo real.

Modelo de datos
El modelo integra siete tablas principales:
productos, almacenes, inventario_actual, movimientos_almacen, clientes, ordenes, y entregas.
A partir de ellas, se ejecutan consultas SQL que miden el rendimiento de las operaciones y ayudan a detectar áreas de mejora en la cadena de suministro.

Principales KPIs generados
On-Time Delivery Rate: mide entregas puntuales.
In-Full Rate: mide pedidos entregados en su totalidad.
OTIF (On Time In Full): combina puntualidad y completitud.
Lead Time Promedio: calcula el tiempo medio entre orden y entrega.
Rotación de productos: muestra los productos con mayor movimiento.
Inventario valorizado: estima el valor total del stock por almacén.
Además, se desarrollaron consultas adicionales para detectar backorders, alertas de inventario bajo, puntualidad y retrasos por transportista, y fill rate promedio por producto.
Estos indicadores permiten tomar decisiones más informadas sobre eficiencia operativa, control de inventarios y desempeño logístico.

Herramientas y Tecnologías Utilizadas
Jupeter Notebook
SQL

Conclusiones El proyecto demuestra que una base de datos bien estructurada puede convertirse en una herramienta esencial para analizar el rendimiento logístico y detectar oportunidades de mejora.
La integración de Python y SQL permite automatizar cálculos de KPIs y generar reportes actualizables de manera eficiente, contribuyendo a la toma de decisiones estratégicas.
Los resultados obtenidos evidencian la importancia del seguimiento de entregas, la gestión de inventarios y la precisión documental para mantener altos niveles de servicio al cliente.
En conjunto, este trabajo reafirma el valor del análisis de datos en la logística moderna, al convertir la información operativa en conocimiento útil para la planificación, control y mejora continua.
