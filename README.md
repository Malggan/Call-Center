## Índice

* ["Anonymous Bank" Call-Center](#:classical_building:anonymous-bank-call-center)

* [Análisis de los datos](#:newspaper:análisis-de-los-datos)

* [Dashboard](#bar_chart-dashboard-y-funcionalidades)

* [Preguntas](#question-preguntas)


# :classical_building: "Anonymous Bank" Call-Center

Este documento describe caso de negocio basado en un Call Center de un Banco: “Anonymous Bank” localizado en Israel. El dataset contiene las llamadas registradas durante 12 meses (desde el 01/01/99 hasta el 31/12/99).

##### El call center de "Anonymous Bank" provee varios servicios diferentes:

* Información y transacciones sobre cheques y cuentas de ahorros, de sus clientes bancarios.
* Respuesta de voz generada por computadora con información sobre las cuentas de los clientes (a través del dispositivo VRU = Voice Response Unit (unidad de respuesta de voz). Una unidad de respuesta de voz (VRU) es un sistema de contestador telefónico automático que posee un hardware y software que permite a la persona que llama navegar a través de una serie de mensajes pregrabados y utilizar un menú de opciones mediante los botones de un teléfono o el reconocimiento de voz.)
* Brindar información a prospectos de clientes. 
* Soporte a los clientes del web-site de "Anonymous Bank" (clientes que acceden al Home Banking)

##### El call center esta conformado por:
* 8 posiciones de agentes para llamadas de clientes y prospectos
* 1 posición de supervisor
* 5 posiciones de agentes para llamadas para soporte de internet home banking (en un cuarto adjac room)

#### Tareas a mejorar
Analizar las operaciones de un Call Center de un Banco, para proponer mejoras en:

* Eficiencia operativa, proponiendo mejoras operativas.
* Mejorar la satisfacción del cliente, cumpliendo los SLA comprometidos.
* Brindar una herramienta para la gestión y la toma de decisiones a los managers del Call Center.
  
En conclusión se solicita definir, construir y presentar un Dashboard que permita medir los niveles de calidad de servicio, eficiencia y productividad del Call Center. Para ello, se propone que definamos los KPIs adecuados para poder medir los objetivos propuestos, y definir nuevos niveles objetivos de manera de ofrecer esos niveles de SLA a terceras partes, o generar un nuevo servicio Premium para los clientes mas importantes del banco.

<br>

## :newspaper: Análisis de los datos

Antes de desarrollar el dashboard en Power BI, se realizó un exhaustivo Análisis Exploratorio de Datos (EDA) utilizando herramientas como Power Query y Power BI. Durante este proceso, se llevaron a cabo las siguientes acciones:

Exploración de Datos: Se utilizó Power Query para importar y explorar el conjunto de datos original. Esto incluyó la identificación de columnas, la revisión de tipos de datos y la detección de posibles problemas de calidad de datos.
Limpieza y Transformación de Datos: Se realizaron diversas transformaciones de datos en Power Query para limpiar y preparar el conjunto de datos para su análisis. Esto incluyó la eliminación de valores duplicados, la corrección de valores erróneos, la conversión de tipos de datos y la creación de nuevas columnas calculadas para enriquecer los datos.
Creación de Medidas y Columnas Calculadas: En Power BI, se crearon medidas y columnas calculadas utilizando DAX (Data Analysis Expressions) para calcular métricas adicionales y realizar análisis más avanzados sobre los datos. Esto permitió agregar más contexto y profundidad al dashboard final.

<p align="center">
<img src="Call Center IMGS/EDA.jpg" alt="Imagen tablas en power bi" width="650" height="400">
</p>
<br>

## :bar_chart: Dashboard y Funcionalidades

Antes de desarrollar el dashboard en Power BI, se realizó un exhaustivo Análisis Exploratorio de Datos (EDA) utilizando herramientas como Power Query y Power BI. Durante este proceso, se llevaron a cabo las siguientes acciones:

Exploración de Datos: Se utilizó Power Query para importar y explorar el conjunto de datos original. Esto incluyó la identificación de columnas, la revisión de tipos de datos y la detección de posibles problemas de calidad de datos.
Limpieza y Transformación de Datos: Se realizaron diversas transformaciones de datos en Power Query para limpiar y preparar el conjunto de datos para su análisis. Esto incluyó la eliminación de valores duplicados, la corrección de valores erróneos, la conversión de tipos de datos y la creación de nuevas columnas calculadas para enriquecer los datos.
Creación de Medidas y Columnas Calculadas: En Power BI, se crearon medidas y columnas calculadas utilizando DAX (Data Analysis Expressions) para calcular métricas adicionales y realizar análisis más avanzados sobre los datos. Esto permitió agregar más contexto y profundidad al dashboard final.

<p align="center">
<img src="Call Center IMGS/DashB.jpg" alt="imagen dashboard completo" width="650" height="400">
</p>
<br>

## :question: Preguntas

* ¿Cuál es el nivel de servicio para los clientes Prioritarios? 
* ¿Damos un mejor servicio que a los clientes normales?
* ¿Qué volumen de llamadas atendemos? 
* ¿Cuáles son los cuellos de botella? ¿En qué días? ¿En qué bandas horarias?
* ¿Cómo es la eficiencia y productividad de nuestros agentes?
* ¿Hay clientes recurrentes en el uso del servicio?
* ¿Cuáles son los tipos de servicio más recurrentes?
* ¿Podemos estimar la dotación necesaria para cumplir con una calidad de servicio determinada?  Ejemplo: si quiero que mi tiempo promedio de espera sea menor a 60 segundos?


