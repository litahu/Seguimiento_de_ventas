# 🛒 **Seguimiento de ventas**
 
<br>

## 📂 **ETAPA 0: Planteamiento del problema** 
### Introducción
El análisis del desempeño empresarial es una clave importante para que las empresas logren el éxito en sus negocios. Las empresas pueden realizar análisis para identificar sus problemas, debilidades y fortalezas. Para el negocio "EmpowerTravel Store", es importante comprender los peligros de los clientes. <br>
Al comprender las preferencias de los clientes, las empresas pueden descubrir qué factores influyen en los clientes a la hora de realizar sus compras. Aparte de eso, las empresas también pueden identificar qué productos o servicios no se venden bien en el mercado. Esto se hace para ajustar las estrategias comerciales adecuadas para que las empresas puedan mejorar la experiencia del cliente y lograr objetivos comerciales a largo plazo.

### Preguntas del negocio
-¿Qué tiendas tienen mayor facturación y identificar la frecuencia de las visitas de los clientes?  <br>
-¿Cual es la factura total por productos?  <br>
-¿El desfase de distancia entre tiendas afecta las ventas?  <br>
 
### Objetivo
Análizar el desempeño de las ventas a nivel nacional de "EmpowerTravel Store" 


## 📂 **ETAPA 1: Análisis de datos**
Llevé a cabo la evaluación de datos para garantizar que los datos estén listos y de acuerdo con las necesidades del análisis.
Ver: [Notebook](https://github.com/litahu/Seguimiento_de_ventas/blob/main/EmpowerTravel.ipynb)

**Qué hacer:**
- Compruebo si hay valores nulos o datos de valor faltante <br>
- Menos datos duplicados <br>
- Realizo consistencia de tipos y valores de datos(inapropiados o inconsistentes) <br>
- Compruebo el valor atípico y datos que no son sesgo <br>
<br>

```
=== ANÁLISIS COMPARATIVO COMPLETO ===
          Facturación Total  Facturación Promedio  Calificación Promedio  \
tienda                                                                     
Tienda 1          755685100             347921.32                   3.97   
Tienda 2          748131300             343336.99                   4.03   
Tienda 3          775590500             352061.05                   4.05   
Tienda 4          717851900             326444.70                   3.99   

          Costo Envío Promedio  Porcentaje Envío/Precio  Total Ventas  
tienda                                                                 
Tienda 1              18526.84                     5.33          2172  
Tienda 2              18303.40                     5.33          2179  
Tienda 3              18768.36                     5.33          2203  
Tienda 4              17392.86                     5.33          2199  

Eficiencia (Facturación/Costo de envío):
tienda
Tienda 1    40788.66
Tienda 2    40873.91
Tienda 3    41324.36
Tienda 4    41272.79
Name: Eficiencia, dtype: float64


La tienda menos eficiente es: Tienda 1

Razones para recomendar la venta de esta tienda:
1. Eficiencia más baja: 40788.66
2. Costo de envío más alto: $18526.84
3. Porcentaje envío/precio: 5.33%

Comparativa con la mejor tienda (Tienda 3):
Diferencia en eficiencia: 535.70
```

## 📂 **ETAPA 2: Visualización de datos**
Luego me aseguré de que el modelo de datos sea escalable y eficiente para consultas. <br>
De ese modo, realicé la conexión de la fuente de datos a Power BI:

<p align="center">
  <kbd> <img width="800" alt="eer" src="https://github.com/litahu/Seguimiento_de_ventas/blob/main/Assets/final_inform.PNG"></kbd> <br>
</p>

<br>


