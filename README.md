# Análisis Estratégico Alura Store Latam – Challenge ONE

## 🎯 Objetivo del Proyecto
Este análisis forma parte del programa Oracle Next Education (ONE) - Alura Latam. El propósito principal es asesorar al Sr. Juan en la evaluación de sus cuatro tiendas de Alura Store. Ante la necesidad de capital para un nuevo emprendimiento, el proyecto busca identificar cuál de las sucursales presenta el rendimiento menos favorable para una posible venta, basándose en datos reales de facturación, logística y satisfacción del cliente.

## 📂 Metodología y Herramientas
El estudio se centraliza en el notebook AluraStoreLatam.ipynb, donde se procesan los datos utilizando las siguientes librerías de Python:
Pandas: Para la manipulación y estructuración de los datos.
Numpy: Para el soporte de operaciones matemáticas y arreglos.
Matplotlib: Para la creación de visualizaciones base.
Seaborn: Para la generación de gráficos estadísticos avanzados.

## 📈 Hallazgos y Visualizaciones

### **1. RENDIMIENTO FINANCIERO POR SUCURSAL**
Este análisis permite visualizar el flujo de caja bruto de cada tienda, siendo la métrica principal para entender el impacto económico de cada sede.

![Facturación Total](https://github.com/Jenn-Mohito/AluraStoreLatam/blob/main/imagenes/img1.png?raw=true)
* **Enlace directo:** https://github.com/Jenn-Mohito/AluraStoreLatam/blob/main/imagenes/img1.png

* **Análisis:** La **Tienda 1** se identifica como el motor financiero de la cadena con una facturación que supera los **$1,212 millones**. Existe una diferencia de más de **$118 millones** respecto a la Tienda 4.

### **2. MAPA DE CALOR: VENTAS POR CATEGORÍA**
A través de esta visualización, se observa la densidad de unidades vendidas cruzando cada categoría de producto con su respectiva tienda.

![Heatmap de Ventas](https://github.com/Jenn-Mohito/AluraStoreLatam/blob/main/imagenes/img2.png?raw=true)
* **Enlace directo:** https://github.com/Jenn-Mohito/AluraStoreLatam/blob/main/imagenes/img2.png

* **Análisis:** Se detecta una especialización por sede; la Tienda 3 domina el mercado de mobiliario, mientras que la Tienda 4 es un punto estratégico para artículos del hogar y educación.

### **3. ÍNDICE DE SATISFACCIÓN DEL CLIENTE**
Se evalúa la percepción del consumidor mediante la calificación promedio, contrastando la calidad del servicio con el volumen de ventas.

![Calificación Promedio](https://github.com/Jenn-Mohito/AluraStoreLatam/blob/main/imagenes/img3.png?raw=true)
* **Enlace directo:** https://github.com/Jenn-Mohito/AluraStoreLatam/blob/main/imagenes/img3.png

* **Análisis:** La **Tienda 3** lidera la satisfacción con una puntuación de **4.05**. Es notable que la Tienda 1, a pesar de sus ingresos, tiene la oportunidad de mejora más alta en fidelización.

### **4. ANÁLISIS DE PRODUCTOS CON MENOR VENTA**
Esta gráfica identifica los 10 artículos que presentan el menor movimiento en el inventario global.

![Menor Rotación](https://github.com/Jenn-Mohito/AluraStoreLatam/blob/main/imagenes/img4.png?raw=true)
* **Enlace directo:** https://github.com/Jenn-Mohito/AluraStoreLatam/blob/main/imagenes/img4.png

* **Análisis:** Identificar productos con demanda crítica permite ajustar la estrategia de stock en lugar de considerar el cierre de una sucursal por bajo rendimiento.

### **5. LÍDERES DE VENTAS: TOP 10 PRODUCTOS GLOBALES**
Visualización de los productos que sostienen la actividad comercial y generan el mayor flujo de transacciones.

![Líderes Globales](https://github.com/Jenn-Mohito/AluraStoreLatam/blob/main/imagenes/img5.png?raw=true)
* **Enlace directo:** https://github.com/Jenn-Mohito/AluraStoreLatam/blob/main/imagenes/img5.png

* **Análisis:** Artículos como el **Microondas** y la **Cama King** son los pilares de la demanda. Mantener el abastecimiento de estos productos en las cuatro tiendas es fundamental para la competitividad.

## 🛠️ Ejecución del Proyecto
Entorno: El notebook es compatible con Google Colab y entornos Jupyter locales.

## 💡 Conclusión Estratégica
Tras el análisis integral, la recomendación para el Sr. Juan es no vender ninguna de las tiendas. Aunque la Tienda 4 registra la facturación más baja, su altísima eficiencia logística la convierte en una pieza clave para la rentabilidad futura de la red. El análisis concluye que la mejor estrategia para financiar el nuevo emprendimiento no es la liquidación de un activo, sino la optimización operativa: replicar el modelo logístico de la Tienda 4 y la calidad de servicio de la Tienda 3 en las sedes con mayor volumen de ventas para maximizar los beneficios netos globales.

Autor: Jennifer Noelia Soto Quiñonez

Especialista en Gestión Pública y Análisis de Datos | Alumna ONE - Alura Latam
