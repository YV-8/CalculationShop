# 📊 Análisis de Datos: AluraStore LATAM - Challenge 1

Este proyecto consiste en un análisis exhaustivo de los datos de ventas de **AluraStore**, una tienda de e-commerce con presencia en Latinoamérica. El objetivo principal fue procesar información bruta, realizar una limpieza de datos técnica y extraer insights valiosos sobre el comportamiento de ventas y productos.

## 📋 Tabla de Contenidos
1. [Descripción del Proyecto](#descripción-del-proyecto)
2. [Fases del Análisis](#fases-del-análisis)
3. [Herramientas Utilizadas](#herramientas-utilizadas)
4. [Resultados y Conclusiones](#resultados-y-conclusiones)
5. [Galería de Análisis Final](#galería-de-análisis-final)

---

## 🚀 Descripción del Proyecto
El dataset contiene información sobre transacciones, incluyendo categorías de productos, precios unitarios, costos de envío y volúmenes de venta. El análisis se centró en entender qué categorías generan más ingresos y cómo optimizar la visualización de estos resultados.

---

## 🔍 Fases del Análisis

### 1. Importación y Carga de Datos
Se utilizaron las librerías **Pandas** y **Numpy** para la ingesta de los datos. En este punto, se identificaron las dimensiones del dataset y los tipos de datos iniciales.

### 2. Exploración y Limpieza (Data Wrangling)
Esta fue la etapa más crítica. Se realizaron las siguientes acciones:
* **Tratamiento de Nulos:** Se identificaron valores faltantes en columnas clave y se aplicaron técnicas de imputación o eliminación según el caso.
* **Formateo de Tipos:** Se convirtieron columnas de precios y costos (que venían como texto/objetos) a formato numérico (`float`) para permitir cálculos matemáticos.
* **Corrección de Errores:** Se eliminaron duplicados y se estandarizaron los nombres de las categorías.

### 3. Transformación de Datos
Se crearon nuevas métricas para profundizar en el análisis:
* **Ingreso Total:** Cálculo del `Precio * Unidades Vendidas`.
* **Costo Logístico:** Análisis de la relación entre el precio del producto y su costo de envío.

### 4. Análisis Estadístico y Agrupación
Se agruparon los datos por **Categoría del Producto** y **País** para identificar:
* ¿Cuál es la categoría líder en ventas? (Ej. Electrónicos).
* Promedio de precios por segmento.
* Distribución de costos de envío.

### 5. Visualización de Datos
Se generaron gráficos (Bar charts, Pie charts) utilizando **Matplotlib** y **Seaborn** para comunicar visualmente los hallazgos técnicos de manera que cualquier stakeholder pueda entenderlos.

---

## 🛠️ Herramientas Utilizadas
* **Lenguaje:** Python 3.x
* **Entorno:** Jupyter Notebook / Google Colab
* **Librerías principales:**
    * `Pandas`: Manipulación de estructuras de datos.
    * `Matplotlib`: Creación de gráficos estáticos.
    * `Seaborn`: Visualización de datos estadística y estética.

---

## 📈 Resultados y Conclusiones
* Se logró reducir el ruido en los datos en un X% tras la limpieza.
* Se identificó que la categoría de **[Insertar Categoría Mayoritaria]** representa el mayor margen de beneficio.
* El análisis permite tomar decisiones basadas en datos para futuras campañas de marketing en AluraStore.

---

## 🖼️ Galería de Análisis Final

En esta sección se presentan las evidencias visuales del comportamiento de los datos:

### Análisis de Ventas Globales
![Análisis de Ventas](ruta/de/tu/foto_analisis_final.png)

### Comportamiento de Categorías
![Fotos de Gráficos](ruta/de/tu/foto_graficos.png)

> **Nota:** Para visualizar las fotos anteriores, asegúrate de haber subido los archivos de imagen a la carpeta de tu repositorio y reemplaza `ruta/de/tu/foto...` con el nombre real del archivo (ej: `img/resultado.png`).
