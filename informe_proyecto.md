<div align="center">
    <h1>Análisis de Negocios para Ciencia de Datos</h1>
    <img src="https://imgur.com/sNVyRNT.png" width="">
</div>

## Tabla de contenido

- [El mundo de los datos: data science y machine learning](#el-mundo-de-los-datos-data-science-y-machine-learning)
  - [¿Qué es ciencia de datos y big data? ¿Cómo afectan a mi negocio?](#qué-es-ciencia-de-datos-y-big-data-cómo-afectan-a-mi-negocio)
  - [Tipología de datos | ¿Qué tipo de información podemos analizar?](#tipología-de-datos--qué-tipo-de-información-podemos-analizar)
  - [Empresas data-driven | ¿Cómo crear empresas y culturas data-driven?](#empresas-data-driven--cómo-crear-empresas-y-culturas-data-driven)
  - [¿Qué es inteligencia artificial y machine learning?](#qué-es-inteligencia-artificial-y-machine-learning)
  - [¿Qué es deep learning? Análisis de imagen, audio y video](#qué-es-deep-learning-análisis-de-imagen-audio-y-video)
- [Herramientas y roles de trabajo en ciencia de datos](#herramientas-y-roles-de-trabajo-en-ciencia-de-datos)
  - [Flujo de trabajo en ciencia de datos: fases, roles y oportunidades laborales](#flujo-de-trabajo-en-ciencia-de-datos-fases-roles-y-oportunidades-laborales)
  - [Herramientas para cada etapa del análisis de datos](#herramientas-para-cada-etapa-del-análisis-de-datos)
  - [¿Qué es y cómo usar una base de datos relacional con SQL?](#qué-es-y-cómo-usar-una-base-de-datos-relacional-con-sql)
    - [SQL](#sql)
      - [Comando SQL: DQL (Data Query Language)](#comando-sql-dql-data-query-language)
      - [Clausulas SQL para DQL](#clausulas-sql-para-dql)
      - [Operadores Lógicos SQL para DQL](#operadores-lógicos-sql-para-dql)
      - [Funciones agregadas SQL para DQL](#funciones-agregadas-sql-para-dql)
- [Problema de negocio: análisis](#problema-de-negocio-análisis)
- [Problema de negocio: implementación](#problema-de-negocio-implementación)

# El mundo de los datos: data science y machine learning

## ¿Qué es ciencia de datos y big data? ¿Cómo afectan a mi negocio?

El análisis de datos empieza con el concepto de Big Data o gran cantidad de datos. Con los datos le podemos permitir saber a las compañías cuál es el próximo paso que deben tomar. Descubrir patrones de consumo y correlaciones. Les da una percepción clara del mercado para **tomar decisiones inteligentes y seguras**.

Características:

- Gran volumen de información. No hay una definición clara sobre cifras exactas, un ejemplo podría ser cuando Excel se bloquea, ahi debemos acudir a otras herramientas de procesamiento de datos.

- Las empresas almacenan datos diariamente. Hay empresas que generan información, pero no hacen uso de estos. Los especialistas en Big Data se encargan de convertir esta información en acción.

- Con Data Science podemos reducir costos, ser mas eficientes y entender a los clientes. Adicionalmente tenemos información de categorías, de textos y otros. El Big Data ayuda a crear un puente entre la **empresa y los usuarios finales**.

- Entonces trabajar en la industria de los datos es llegar a crear una solución matemática a un problema de negocio.

## Tipología de datos | ¿Qué tipo de información podemos analizar?

![tipologia_de_datos](https://imgur.com/dlMm9zx.png)

- **Personas**: gustos, likes o preferencias, lugares que has visitado, personas con las que estás más tiempo.
- **Transacciones**:
  - **Monetarias**: pagos, cuanto pagas, en qué establecimiento, que producto o servicio obtienes.
  - **No monetarias**: por ejemplos tus llamadas telefónicas, cuánto duran, a quién le marcas, etc.
- **Navegación web**: Quién accede a las páginas web, de dónde son, clicks que das, cuánto tiempo duras en la página, estas son las **COOKIES**.
- **Machine 2 Machine**: conexión de una máquina a otra máquina. Por ejemplo el GPS de tu teléfono para ubicar al conductor de Didi más cercano.
- **Biométricos**: datos que te identifican como persona única, huella dactilar, tipo de sangre, tu voz, tu rostro para desbloquear tu smartphone, iris.

## Empresas data-driven | ¿Cómo crear empresas y culturas data-driven?

> ¿En qué consisten las empresas data-driven? Y ¿Qué se necesita para hacerlo?

1. **Crear una cultura de datos: entenderla**

- Hacer que todos los empleados tomen decisiones basados en datos. Para eso tienen que entender los tipos de datos visto en la sección anterior.

2. **Recolectar información**

- Almacenar y procesar toda la información.
- No basarnos solo en una parte de la información, sino entender toda la información que llega a nosotros

3. **Medir todo**

- Entender el tamaño de la información
- Entender el ritmo de crecimiento de los tipos de información que se producen. La información de precios podría crecer menos que los de ventas.

4. **Datos relevantes y precisos**

- Basarnos en la información que nos sirvan: tal para un estudio sea prioritario el tiempo, los tipos de clientes y si es el tiempo, cual es la frecuencia que deberíamos tomas (¿días, horas, minutos?)
- Pensar muy bien qué información y con qué características serán importantes para un estudio en particular o para todo el modelo de negocio
- Después tenemos que ver si la información es precisa y estándar (tipo de datos).
  
> Por ejemplo, en el caso de tener ingresos por ventas por diferentes monedas, de acuerdo con el país donde se transa, será necesario esta clasificación; de manera similar sucede con el uso horario. En ambos casos será necesario transformar a una denominación estándar.

5. **Testear y crear hipótesis**

- Tenemos que partir de una hipótesis **–una pregunta—**. El análisis tiene que partir de una pregunta específica.

> Por ejemplo, para estudiar si las ventas de diciembre incrementaron, hipótesis: en invierno ¿el consumo de gas se incrementa?, entonces ¿las ventas se incrementarán entre octubre y enero?; en el estudio se enfocará en testear si dicha hipótesis es cierta o no.

6. **Desde los insights de datos a las acciones**

- Los insights son obtenidas de los resultados del estudio enfocado a probar si la hipótesis planteada era cierta o no.

> Por ejemplo, un insight podría ser: efectivamente en diciembre los hogares consumen más gas; ya con esta información tendremos que decidir que acción debemos tomar.

- ¿Cuál es la pregunta? >> ¿tenemos la información para validarla? >> ¿cómo lo convertimos en acción los resultados?

- Bajo este enfoque las decisiones de acción son tomadas con datos **–Data driven**. Ya no en base a una intuición.
- La intuición sirve para plantear las hipótesis, pero la acción solo será tomada si esta es validada.

7. **Cumplir las regulaciones de datos**

- No podemos tomar decisiones en base al género, información privada, etc. - Cumplir todas las regulaciones

> La ética en los datos es muy importante

8. **Automatizar**

- Un estudio no tiene por qué ser hecha recurrentemente, sino automatizar la validación en cada periodo.

**Resumen:**
![empresas_data_driven](https://imgur.com/PTKiq52.png)

## ¿Qué es inteligencia artificial y machine learning?

![ia_ml_dl](https://imgur.com/VNFFDiz.png)

**Inteligencia Artificial** es la capacidad de las computadoras de mostrar un comportamiento “inteligente”.

Mientras que **Machine Learning** es una de técnica que se utiliza para crear y mejorar dicho comportamiento. Esto mediante entrenamientos automáticos basados en la exposición a datos.

Utilidad de **Machine Learning**:

- Detección de fraudes
- Búsqueda web
- Anuncios a tiempo real
- Análisis de textos
- Next best action: Predecir la acción que un usuario va a tomar

Al utilizar redes neuronales de gran profundidad, el aprendizaje automático se convierte en aprendizaje profundo o **deep learning**.

![ia_ml_dl2](https://imgur.com/EtBWxrg.png)

![ia_ml_dl_resumen](https://imgur.com/NA0uhS4.png)

## ¿Qué es deep learning? Análisis de imagen, audio y video

Entrena a una computadora para que realice tareas, como el reconocimiento del habla, la identificación de imágenes o hacer predicciones.

El deep learning configura parámetros básicos acerca de los datos y entrena a la computadora para que aprenda por cuenta propia reconociendo patrones mediante el uso de muchas capas de procesamiento.

Ejemplo de imagenes para que una red neuronal detecte que es que.
<div align="center"> 
  <table>
    <tr>
    <td><img src="https://imgur.com/5msw8z0.png" width=""></td>
    <td><img src="https://imgur.com/6Jg187z.png" width=""></td>
    </tr>
  </table>
</div>

Comparación entre Machine Learning y Deep Learning

![ml_vs_dl](https://imgur.com/g9lohpw.png)

Aplicando un ejemplo práctico utilizando Decision Tree como algoritmo de Machine Learning y Feature Extraction + Classification en Deep Learning, el cual lo hace todo la RN.

![ejemplo_auto](https://imgur.com/UpOlPcM.png)

> Anteriormente solo necesitábamos conjuntos de datos (matrices, vectores, datasets etc)
> Pero en Deep Learning podemos tener otro tipo de datos. En lugar de tener datos numéricos, categóricos etc, ahora tenemos: **Imágenes, videos, audios, notas de voz, textos complejos**.

# Herramientas y roles de trabajo en ciencia de datos

## Flujo de trabajo en ciencia de datos: fases, roles y oportunidades laborales

![roles1](https://imgur.com/zXllOA6.png)

- **Data Engineer (Ingenierio de datos)**: hace la conexión entre el dispositivo y la creación de una base de datos.
Trabajan haciendo APIs, ETLs, conectores y las herramientas más usadas son SQl y NoSQL

- **Analista Business Intelligence**: a partir de la información que creo el ingeniero de datos extrae la información que le interesa, crea cuadros de control, automatiza estos procedimientos y las herramientas más usadas son SQL y Excel.

- **Data Scientist (Cientifico de datos)**: sabe el rol del analista, extraer la información, y sabe predecir. Las herramientas más usadas son R y Python.

- **Data Translator**: persona que pueda interpretar los datos y pueda comunicarnos con los otros equipos de negocios. Experto en la necesidad de negocio.

Con un poco mas de profundidad en los roles anteriormete descriptos tenemos algo como:
![roles2](https://imgur.com/eajizv7.png)

Un poco mas seccionado con las herramientas podemos encontrar algo como: 
![roles3](https://imgur.com/4kOzUit.png)

## Herramientas para cada etapa del análisis de datos

- _**Ingeniero de Datos**_
  - **SQL**: Nos ayuda a extraer información, nos ayuda a encontrar la información para la cual hacemos un estudio, lo más específica que queramos. Vamos a sintetizar una base de datos pequeña o gigante. Esto nos va a ayudar para poder entregar un cuadro de control, una evolución en un gráfico tanto del presente, pasado y futuro. Un ejemplo es un embudo.

![](https://imgur.com/uL1iDPJ.png)

- _**Analista de datos**_
  - **R**: Es un lenguaje mas orientado a la estadística, nos ayuda a sacar P-Values o intervalos de confianza. Es un lenguaje mas orientado a la econometría. Ambos tiene apoyos adicionales en R son ggplot2 (graficos muy visuales) y dplyr (reorganizar la información).

  - **Python**: Es mas basado en la ingeniería, tiene un enfoque mas parecido a los lenguajes de programación como Java o C++. En Python tenemos Pandas y Numpy que nos sirven para organizar la información y no tener que escribir tanto código.

![](https://imgur.com/wo5fwLo.png)

##  ¿Qué es y cómo usar una base de datos relacional con SQL?

El Lenguaje de Consulta Estructurado (SQL), es un tipo de lenguaje de programación que ayuda a solucionar problemas específicos o relacionados con la definición, manipulación e integridad de la información representada por los datos que se almacenan en las bases de datos.

¿Por qué es importante aprender SQL?

- SQL simplifica tu código
- SQL te ahorrará en mucho
- Mejorarás tu lógica de programación aprendiendo SQL
- Tu aplicación puede ejecutarse más rápidamente
- SQL puede hacer que tu aplicación se vuelva independiente de los cambios en los datos.
- SQL se mantiene en constante evolución pero el núcleo de SQL cambia muy poco
- Eficacia en la solución de problemas

![](https://imgur.com/0QxpCCm.png)
### SQL

#### Comando SQL: DQL (Data Query Language)
![](https://imgur.com/cfzaTpS.png)
#### Clausulas SQL para DQL
![](https://imgur.com/NBjOr4S.png)
#### Operadores Lógicos SQL para DQL
![](https://imgur.com/JFHv1vm.png)
#### Funciones agregadas SQL para DQL 
![](https://imgur.com/pl2mUo5.png)

> [Un poco mas de profundidad en SQL](https://www.ticportal.es/glosario-tic/base-datos-sql)
# Problema de negocio: análisis

# Problema de negocio: implementación
