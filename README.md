# Clasificacion Automatica de Tickets con NLP


**Descripcion del Problema**
crear un modelo que pueda clasificar las quejas (complaints) de los clientes en función de los productos/servicios. Al hacerlo, puede segregar estos tickets en sus categorías relevantes y, por lo tanto, ayudar en la resolución rápida del problema.

Realizar el modelado de temas en los datos .json proporcionados por la empresa. Dado que estos datos no están etiquetados, se aplica NMF para analizar patrones y clasificar los tickets en los siguientes cinco grupos según sus productos/servicios:

    - Tarjetas de Credito / Tarjetas Prepagadas (Credit card / Prepaid Card)

    - Servicios de Cuentas de Banco (Bank account services)

    - Reportes de Robos (Theft/Dispute reporting)

    - Prestamos Hipotecarios y Otros Prestamos (Mortgages/loans)


Con la ayuda del modelado de temas, se podrá asignar cada ticket a su respectivo departamento/categoría. Luego puede usar estos datos para entrenar cualquier modelo supervisado, como regresión logística, árbol de decisión o bosque aleatorio. Usando este modelo entrenado, puede clasificar cualquier nuevo ticket de soporte de quejas de clientes en su departamento correspondiente.



===============================================================================


## Flujo de Trajajo:

1.	Data Loading
2.	Text preprocessing
3.	Exploratory Data Analysis (EDA)
4.	Feature Extraction
5.	Topic modeling
6.	Model building using Supervised Learning
7.	Model training and evaluation
8.	Model inference


===============================================================================

