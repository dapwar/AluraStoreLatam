# AluraStoreLatam
___________________________________________________________________________________________________________________________________________________________________
Análisis de Ventas de AluraStoreLatam.

Este repositorio contiene el cuaderno de Google Colab AluraStoreLatam.ipynb, el cual realiza un análisis exploratorio de datos sobre las ventas de cuatro tiendas de AluraStore en Latinoamérica. El objetivo principal de este análisis es evaluar métricas clave de rendimiento para cada tienda, incluyendo facturación, ventas por categoría de producto, calificación promedio, productos más y menos vendidos, y costos de envío promedio.

## 🚀 :rocket:Cómo Abrir y Ejecutar el Cuaderno
Para interactuar con este análisis de datos, sigue estos sencillos pasos:

Abre el cuaderno en Colab: Haz clic en el siguiente enlace para abrir el cuaderno directamente en Google Colab:
[(https://drive.google.com/file/d/16uZDn6cSFSDxTHL99ORTvSCMb4takDy9/view?usp=sharing)].

Ejecuta las celdas: Una vez abierto en Colab, puedes ejecutar cada celda secuencialmente haciendo clic en el botón "Ejecutar celda" (el icono de triángulo ▶️) en la parte superior izquierda de cada celda. También puedes ejecutar todas las celdas a la vez yendo a Entorno de ejecución > Ejecutar todo.

Nota: El cuaderno importa datos directamente desde URLs de GitHub, por lo que no se requiere descarga manual de archivos CSV.

___________________________________________________________________________________________________________________________________________________________________
📊 Descripción del Conjunto de Datos

El análisis se realiza sobre los datos de ventas de cuatro tiendas diferentes (tienda_1.csv, tienda_2.csv, tienda_3.csv, tienda_4.csv) de AluraStoreLatam. Cada conjunto de datos contiene información transaccional con las siguientes columnas clave:

Producto: Nombre del producto vendido.

Categoría del Producto: Categoría a la que pertenece el producto (ej., Electrónicos, Muebles, Juguetes).

Precio: Precio de venta del producto.

Costo de envío: Costo asociado al envío del producto.

Fecha de Compra: Fecha en que se realizó la compra.

Vendedor: Nombre del vendedor.

Lugar de Compra: Ciudad donde se realizó la compra.

Calificación: Calificación otorgada al producto/servicio.

Fuente: Los datos son accesibles directamente desde el repositorio de GitHub de Alura-es-cursos.

🎯 Objetivos del Análisis
Los principales objetivos de este cuaderno de análisis de datos son:

Análisis de Facturación: Calcular y comparar el ingreso total de cada una de las cuatro tiendas.

Ventas por Categoría: Determinar las categorías de productos más y menos vendidas en cada tienda.

Calificación Promedio: Evaluar la calificación promedio recibida por cada tienda.

Productos Más y Menos Vendidos: Identificar los productos individuales con mayor y menor volumen de ventas en cada tienda.

Costo de Envío Promedio: Calcular el costo de envío promedio para cada tienda.

## :hammer:Herramientas y Librerías Utilizadas
Este proyecto utiliza Google Colab y las siguientes librerías de Python:

pandas: Fundamental para la importación, manipulación y análisis de los datos tabulares.

##:💡 :Hallazgos y Conclusiones Clave
A continuación, se presentan algunos de los hallazgos destacados del análisis:

Facturación Total:

Tienda 1: $1,150,880,400.00

Tienda 2: $1,116,343,500.00

Tienda 3: $1,098,019,600.00

Tienda 4: $1,038,375,700.00
(La Tienda 1 es la que generó mayores ingresos.)

Categorías de Productos Más Vendidas: En general, "Muebles" y "Electrónicos" son consistentemente las categorías más vendidas en todas las tiendas.

Calificación Promedio de la Tienda: Las calificaciones promedio oscilan entre 3.98 y 4.05, lo que indica un rendimiento generalmente bueno en todas las tiendas.

Costo de Envío Promedio:

Tienda 1: $26,018.61

Tienda 2: $25,216.24

Tienda 3: $24,805.68

Tienda 4: $23,459.46
(La Tienda 4 tiene el costo de envío promedio más bajo.)
