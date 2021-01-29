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
  - [Cómo estructurar queries en SQL](#cómo-estructurar-queries-en-sql)
    - [10 preguntas frecuentes de SQL en entrevistas de trabajo](#10-preguntas-frecuentes-de-sql-en-entrevistas-de-trabajo)
  - [Conflictos y retos actuales sobre la ética y tratamiento de datos](#conflictos-y-retos-actuales-sobre-la-ética-y-tratamiento-de-datos)
- [Problema de negocio: análisis](#problema-de-negocio-análisis)
  - [Aplica técnicas de storytelling para convertir problemas de datos en historias](#aplica-técnicas-de-storytelling-para-convertir-problemas-de-datos-en-historias)
  - [Cómo estructurar un caso de negocio](#cómo-estructurar-un-caso-de-negocio)
    - [¿Qué?](#qué)
    - [¿Por qué?](#por-qué)
    - [¿Cómo?](#cómo)
  - [Análisis cuantitativo en un caso de negocio](#análisis-cuantitativo-en-un-caso-de-negocio)
    - [Analisis cuantitativo: Primeros pasos](#analisis-cuantitativo-primeros-pasos)
    - [Analisis cuantitativo: Mapeo](#analisis-cuantitativo-mapeo)
    - [Hipótesis](#hipótesis)
    - [Analisis cuantitativo: aplicación](#analisis-cuantitativo-aplicación)
  - [Análisis cualitativo en un caso de negocio](#análisis-cualitativo-en-un-caso-de-negocio)
  - [Fusión cuanti-cualitativa en un caso de negocio](#fusión-cuanti-cualitativa-en-un-caso-de-negocio)
  - [¿Qué es minería de texto? ¿Cómo usarla para obtener información adicional?](#qué-es-minería-de-texto-cómo-usarla-para-obtener-información-adicional)
  - [Variación de comportamientos a partir de la geolocalización](#variación-de-comportamientos-a-partir-de-la-geolocalización)
- [Problema de negocio: implementación](#problema-de-negocio-implementación)
  - [Acciones, algoritmos y toma de decisiones según los resultados del análisis](#acciones-algoritmos-y-toma-de-decisiones-según-los-resultados-del-análisis)
    - [Algoritmos usados](#algoritmos-usados)
    - [Acciones](#acciones)

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

## Cómo estructurar queries en SQL

El procedimiento para hacer convertir los datos contenido en una tabla en información útil es:

1. Tener claro el **OBJETIVO**, esta es la pregunta que nos hacemos.
2. Tener las **TABLA** o las **TABLAS** en algún motor de bases de datos relacional, o puede ser en excel. 
3. Debemos tener una **COMPRENSIÓN** de los datos, esto es saber **como se llama** la tabla o las tablas y **que columnas tiene**.
4. Escribimos la **QUERY en SQL** sabiendo **DQL**.
5. Obtenemos el resultado.

Ejemplo: 
![](https://imgur.com/Arlo7R6.png)

### 10 preguntas frecuentes de SQL en entrevistas de trabajo

1. Query SQL para encontrar el segundo salario más alto de los empleados:

```sql
SELECT MAX(Salary)
FROM Employee
WHERE Salary NOT IN (SELECT MAX(Salary) FROM Employee );
```

2. SQL para encontrar el salario máximo de cada departamento.

```sql
SELECT DeptID, MAX(Salary)
FROM Employee
GROUP BY DeptID.
```

3: Escriba una consulta SQL para mostrar la fecha actual.

```sql
SELECT GetDate();
```

4: Escriba una consulta SQL para comprobar si la fecha pasada a la consulta es la fecha del formato dado o no.

```sql
SELECT ISDATE(‘1/08/13’) AS “MM/DD/YY”;
```


5: Escriba una consulta SQL para imprimir el nombre del empleado distinto cuya fecha de nacimiento es entre el 01/01/1960 al 31/12/1975.

```sql
SELECT DISTINCT EmpName
FROM Employees
WHERE DATE BETWEEN ‘01/01/1960’ AND ‘31/12/1975’;
```

6. Escriba una consulta SQL para encontrar el número de empleados según el género cuya fecha de nacimiento sea entre el 01/01/1960 y el 31/12/1975.

```SQL
SELECT COUNT(*), sex
FROM Employees
WHERE DATE BETWEEN ‘01/01/1960’ AND ‘31/12/1975’
GROUP BY sex
```

7. Escriba una consulta SQL para encontrar un empleado cuyo salario sea igual o superior a 10000.

```SQL
SELECT EmpName
FROM  Employees
WHERE  Salary>=10000;
```

8. Escriba una consulta SQL para encontrar el nombre del empleado cuyo nombre comience con "M"

```SQL
SELECT *
FROM Employees
WHERE EmpName LIKE ‘M%’;
```

9. busque todos los registros de empleados que contengan la palabra “Joe”, independientemente de si se almacenó como JOE, Joe o joe.

```SQL
SELECT *
FROM Employees
WHERE UPPER(EmpName) LIKE '%JOE%';
```

10. Escriba una consulta SQL para encontrar el año desde la fecha.

```SQL
SELECT YEAR(GETDATE()) as “Year”;
```

## Conflictos y retos actuales sobre la ética y tratamiento de datos

> "… ¿Cómo tiene que avanzar la ley digital para explicar una realidad? Por ley, o la falta de esta, es que la tecnología avanza a un ritmo diferente –para unos amenazador o muy retador para otros— pero la ley no lo ha hecho a este ritmo solo la digitalización…"
>
> ¿Quien quieres ser en los datos?
> ¿Cuanto quieres compartir?

> VER [The Social Dilemma en Netflix](https://www.imdb.com/title/tt11464826/)

# Problema de negocio: análisis

## Aplica técnicas de storytelling para convertir problemas de datos en historias

El objetivo del **Storytelling** es enamorar al oyente. Esto es para que todas las personas de la empresa puedan entender y les importe el problema en cuestión. Sabiendo esto debemos estructurar en como vamos a contar nuestra historia:

> - **PROBLEMA: ¿Que queremos resolver?, hipótesis de la cual estamos partiendo.**
> - **SOLUCIÓN: Debemos plantear e imaginar hacia donde queremos ir.**
> - **ALCANCE: ¿Que pretendemos explicar con este análisis?**

**Caso práctico:**

- **Problema (Hipótesis):** Algunos clientes contactan a soporte en exceso.
  - No los podemos identificar.
  - No podemos prevenir este comportamiento.
  - Analisis con una distribución normal. Tenemos puntos extremos los cuales serán anomalos y son los que queremos identificar.
- **Solución**: Script que identifique y clasifique a los **Top Offenders**.
  - Entender sus motivaciones - clasificarlos.
  - Definir acciones para prevenir esta tendencia.
- **Alcance**: LATAM con distinción por ciudades y mes a mes. (Siempre lo mas grande posible.)
  - Clientes.
  - Actualización mensual.
  - Hacer una distinción geogragica.

> **Target**: Los clientes de Latinoametica con distinción por ciudad y viendo esto mes a mes, de forma automática.

## Cómo estructurar un caso de negocio

Debemos desglosar un problema de negocio en una hipótesis estructurada:

### ¿Qué?

> ¿Qué? > Problema de negocio -> Hipótesis: Partir de una pregunta específica.

### ¿Por qué?

> ¿Por qué? > Clasificar todos los motivos y sistematizarlo en pocas categorías, ejemplo:

- Motivaciones económicas
- Preguntas
- Problemas tecnológicos (relacionado con problema de como comunica la empresa).
- Política de la empresa.

### ¿Cómo?

> ¿Cómo? > Estrategia de cómo vamos a diseñar y organizar todo el análisis.

1. **Análisis cuantitativo**. Debe ir siempre primero ya que es toda la información. Hacer una clasificación numérica.
2. **Análisis cualitativo**. Buscar categorías en función de texto. Nos ayuda a identificar características, tipos, relacionados con el problema.
3. **Matriz cuantitativa-cualitativa**. Poner en conjunto la información, entender los números y explicarlos más a profundidad.
4. **Acciones de prevención**. Definir acciones con la información que tenemos. Pasar de los insights a acciones.
5. **Validación**. Verificar si nuestro análisis ha servido y si nuestras acciones de prevención están teniendo efecto.

> Resumen:
>
> 1. Identificar datos.
> 2. Encontrar categorias.
> 3. Poner en conjunto esta información.
> 4. Crear acciones con esta información.
> 5. Validar que todo nuestro estudio esté sirviendo.

## Análisis cuantitativo en un caso de negocio

### Analisis cuantitativo: Primeros pasos

![pasos_analisis_cuantitativo](https://imgur.com/mZg57Sp.png)

1. **Descargar la información.**
   1. Descargar información desde SQL o con SQL.
   2. Nuestra pregunta: ¿Quienes pueden ser esos TOP OFFENDERS?
   3. Descargar la información genérica de todos los clientes que hayan hecho por lo menos 1 queja.
2. **Identificar**.
   1. Debemos definir las variables que nos ayudarán a identificar si alguien es TOP OFFENDER.
   2. En la imagen podemos ver las variables.
   3. Las variables identificadas serán a lo que se le prestará atención para identificar patrones.
       - Madurez. Experiencia del usuario utilizando la plataforma, lo evaluamos al verificar el número de comprar realizadas.
       - Quejas mensuales. Número de quejas que hizo un cliente o usuario.
       - Compras Mensuales. Evaluar el numero de compras y el número de quejas correspondientes a esas compras. Encontrar una relación de comportamiento.
       - Gasto mensual. Tomar en cuenta el tipo de producto y su complejidad, lo cuál va relacionado muchas veces con el precio del mismo.
       - Créditos y dinero devuelto. Identificar si es una persona que busca una compensación económica.
       - Margen operativo neto. Es el Rendimiento. Que te queda como empresa a partir del comportamiento del usuario o cliente.
         - (Lo que vendí x precio de lo que vendí)- recursos de soporte post venta - Dinero devuelto == Cuanto nos queda a la empresa.

3. **Definir**
   1. **Objetivo** = encontrar una segmentación con base en la rentabilidad.Si un usuario es más rentable(compra más), le permito que se queje más.
   2. **Threshold**(límite). Definir el límite entre una persona que sus quejas sean normales y otra que excede las quejas normales. Definir un Threshold para cada categoría.

### Analisis cuantitativo: Mapeo

> Se hace un mapeo de los datos.

Se observa en la siguiente lista los usuarios que almenos se han quejado una vez.

**Ratio de contacto = Promedio quejas / Promedio compras**

Debemos porcentuar los datos para saber el peso que tiene realmete cada uno, ya que el volumen de personas por cada categoria es diferente.

![mapeo](https://imgur.com/mfm5Wi1.png)

### Hipótesis

Hipótesis inicial: Lo usuarios que han realizado más compras se quejan menos porque ya entienden mejor la plataforma.

![hipotesis](https://imgur.com/yT7sOol.png)

Vemos en la gráfica como nuestra teoria inicial es válida. Lo que hicimos fue separar los usuarios nuevos de los experimentados. El criterio fue que los usuarios que tenia menos de 10 compras erán nuevos.

Con lo dicho anteriormente graficamos a los usuario nuevos y experimentado. Se puede observar como el ratio de contacto en los usuarios experimentados es cercano a 0 en la gráfica de arriba. En cambio en los usuarios menos experimentados las quejas son mayores confirmando nuestra hipotesis.

### Analisis cuantitativo: aplicación

![](https://imgur.com/fDHcC5Y.png)

Se busca impactar el minimo grupo de personas posibles y afectar al maximo posible el numero de quejas. Poco usuarios, muchas quejas

Afectando el 20% de los usuarios regulares atacamos al 35% de las quejas.
Afectando el 5% de los usuarios bronca atacamos al 17% de las quejas.
Afectando el 1% de los usuarios plata atacamos al 7% de las quejas.
Afectando el 1% de los usuarios oro atacamos al 7% de las quejas.

## Análisis cualitativo en un caso de negocio

![clus-vs-clas](https://imgur.com/BEmJv1O.png)

![](https://imgur.com/1SUAsxA.png)

**Clusterizar**: Agrupar las problemáticas, motivaciones y contactos por parte de los clientes a las que nos enfrentamos. Este ejemplo se clasificaron en 4 categorías las más de 500 tipos contactos:

- Motivación económica. Buscan que se les devuelva el dinero. Ésta es la más grave ya que además de ser una queja, se les devuelve el dinero.
- Preguntas. Los clientes tienen dudas.
- Problemas tecnológicos. Relevante para identificar fallas técnicas del servicio o producto.
- Política de empresa.

![](https://imgur.com/DCNc2gD.png)

**Clasificación**: Definir los motivos detrás de los mensajes, cuando los hayamos clasificado dentro de una categoría profundizaremos en los motivos de contacto de una manera geolocalizada por lo que tendremos especificidad en cada contexto social.

## Fusión cuanti-cualitativa en un caso de negocio

> En resumen:
> Los datos cuantitativos nos dicen qué clientes se quejaron y cuantas veces
> Los datos cualitativos nos explican el motivo de su queja (devolución de dinero, problemas técnicos, dudas, etc)

Resolver de manera conjunta la información cuantitativa y cualitativa para sacar conclusiones.

Una vez que tenemos información sobre cuáles son las razones por las que los clientes nos contactan así como una clasificación de los top offenders vamos a ver por qué se queja cada uno de los tipos de top offenders para encontrar las claves del análisis.

Para este análisis se utiliza **una tabla con un mapa de calor** para resaltar los porcentajes más elevados y poder concentrar nuestra atención en los problemas mayores más rapidamente.

![](https://imgur.com/7e8qgSp.png)

Se puede observar que los clientes menos experimentados quieren devoluciones y los clientes mas experimentados quieren soluciones a problemas tecnologicos y politicas de empresa. Se puede obsercar que los clientes experimetados son mas fieles.

## ¿Qué es minería de texto? ¿Cómo usarla para obtener información adicional?

La **minería de textos** es una rama específica de la **minería de datos** que se refiere al proceso de analizar y derivar información nueva de textos. Por medio de la identificación de patrones o correlaciones entre los términos se logra encontrar información que no está explícita dentro del texto. Los textos que se usan como recursos pueden ser páginas web, libros, correos electrónicos, reseñas de clientes, artículos, entre otros.

La minería de textos es un área multidisciplinaria basada en la recuperación de información, aprendizaje automático, estadísticas y la lingüística computacional. Como la mayor parte de la información (más de un 80%) se encuentra actualmente almacenada como texto, se cree que la minería de textos tiene un gran valor comercial.

Por ejemplo: Twitter, tiene su base de negocio en la exploración de los mensajes.

En la caso siguiente se analizaron los mensajes dejados por los usuarios que se han quejado, y se llego a ciertas conclusiones vistas en el gráfico.

![](https://imgur.com/0B7iDfN.png)

## Variación de comportamientos a partir de la geolocalización

Relevancia del comportamiento de acuerdo al origen geográfico por país, ciudad, distrito.

En el caso de top offenders se creó un gráfico que compara las quejas vs compras de acuerdo al origen geográfico de las mismas, a nivel de ciudad. Se espera obtener una línea de 45º si el comportamiento de los resultados es normal como se observa en el gráfico.

![](https://imgur.com/weI8RGD.png)

Aquellas ciudades que se alejen de la línea son aquellas que tienen más top offenders de lo normal. Las ciudades con más top offenders son Puebla, Querétaro, Toluca; esto se define al observar que las ciudades se encuentran más alejadas del eje normal y más cercanas al eje de las quejas.

# Problema de negocio: implementación

## Acciones, algoritmos y toma de decisiones según los resultados del análisis

En la siguiente imagen se ve los algoritmos que se utilizarón para realizar el estudio.

![](https://imgur.com/vAhFlnz.png)

### Algoritmos usados

- **Minería de texto**: es el analisis de las palabras
- **Encontrar correlaciones y patrones de comportamiento**: por ejemplo aprender si los usuarios que mas compran son los que mas se quejan, y porque lo hacen, etc.
- **Arboles de decisiones**: Nos ayudan a la toma de decisiones, partiendo de una hipótesis A o una hipótesis B y nos iremos acercando con teoría de juegos para predecir cual es la mejor estrategia.
- **Validación con bayesianos**: la estadística bayesiana es muy útil para identificar patrones que se comportan de maneja conjunta. Por ej. cual es la probabilidad que si yo aviso a un usuario de que es un top offender, reincida o lo entienda y deje de comportarse asi.
- **Cadenas de Montecarlo**: Son probabilidades concatenadas, conjuntas. Por ej. si un mes fue top offender, el mes siguiente lo va a ser? Ya no lo sera?. Son estudios que se hacen después de nuestro análisis, son métodos de validación. Es ver como impacto el modelo.

### Acciones

- **Taggear, identificar a los top offenders**: saber quienes son y taggearlos, para saber si ya reincidió una vez, si darle beneficios o no.
- **Advertirlos**.
- **Llamar usuarios**: en los mejores clientes, es mejor llamarlos y se obtiene un trato personalizado.
- **Bloquear usuarios**: es en casos extremos.
- **Validación con A/B test**: donde la A puede ser una llamada, y la B puede ser mandarles un mensaje y ver el comportamiento de cada uno para ver cual funciono mejor.
