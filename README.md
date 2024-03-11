### Alura Challenge: Esencia del cliente 🛒🚦

*Esencia del cliente* es un algoritmo que permite segmentar a los clientes de un supermercado de acuerdo a sus hábitos mediante la clusterización: técnica de machine learning que implica inteligencia artificial. 

Dicha asignación permiten comprender las necesidades y hábitos de consumo de los clientes, de modo que, pueden tomarse decisiones de negocio en pro de favorecer la interacción clientes-supermercado, buscando satisfacer y generar mayor fidelidad, a la vez que se garantiza el éxito de la empresa. 

### **Librerias utilizadas:**
- *Pandas*
- *Numpy*
- *Matplotlib*
- *Seaborn*
- *Scikit-Learn*

#### 1. Configuración del ambiente:  ⚙
Instalando librerías que serán necesarias para el deasarrollo del proyecto.

#### 2. Obtención y transformación de datos: ⛏
 - Adaptación de la base de datos para la interacción y transformación de los datos.
 - La base de datos original se encuentra disponible en Kaggle a través del siguiente enlace: https://www.kaggle.com/datasets/ramjasmaurya/medias-cost-prediction-in-foodmart

#### 3. Exploración de datos: 🧹
Aplicación de bibliotecas Matplotlib y Seaborn para generar algunas visualizaciones que permiten entender la composición del dataset e identificar características importantes, como son valores atípicos, distribuciones, correlaciones y agrupaciones.

#### 4. Procesamiento y obtención de features: 🤔
Asignación de mecanismo codificación mediante la sustitución de valores, lo cuál, permite al algoritmo de clusterización entender el conjunto el datos que será procesado. Posteriormente, reducción de la dimensión del dataset mediante la selección de las variables categóricas que mejor representan el conjunto de datos, seguidamente, estandarización de los datos a la misma escala mediante StandardScaler.

#### 5. Validación de clusters: 📈
Aplicación de algortmo de clusterización KMeans y obtención de puntajes para las métricas: 'Inercia', 'Silhouette', 'Davies-Bouldin' y 'Calinski and Harabasz' para evaluar la calidad de los resultados del modelo. Paso seguido, el algoritmo de clusterización es instanciado con la configuración del número de clusters seleccionada, lo que indica el cluster perteneciente a cada cliente como un nuevo atributo en el dataset. Adicionalmente, se realizan gráficos de dispersión para comparar las variables y describir las características de cada cluster.

#### 6. Análisis e interpretación de clusters: 🤖
Finalmente, se incluye la descripción para cada cluster, así como recomendaciones y estrategias para mejorar y personalizar la experiencia de los clientes. 

![](https://github.com/geeorgebixleer/Esencia-del-cliente-Alura-Challenge/blob/main/esencia_cliente.png)
