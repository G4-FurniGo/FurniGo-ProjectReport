<p align = "center"> <img src = "https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img> </p>

# Universidad Peruana de Ciencias Aplicadas

## Ingeniería de Software - Ciclo V

## Desarrollo de Aplicaciones Open Source

## SV52

## Profesor:

Mori Paiva, Hugo Allan  

# Informe de Trabajo Final

## SparkLabs

## FurniGo

## Integrantes:

- Cancho Coila, Diego Fabian U20201F479  
- Isla Quispe, Luis Fernando U202124146  
- Velarde Luyo, Piero Alberto U20211A620  
- Loli Ruiz, Renzo Javier U202161C993  
- Rondon Añaños, Cristopher U20201A291  

## Registro de versiones del informe

| Fecha      | Version | Autor     | Descripción                                             |
|:----------:|:-------:|:---------:|:-------------------------------------------------------:|
| 03/09/2023 | 0.1     | SparkLabs | Creación del documento                                  |
| 10/09/2023 | 0.2     | SparkLabs | Se agregaron los capítulos para la entrega de TB1       |
| 30/09/2023 | 0.3     | SparkLabs | Se agregó el capítulo 5.2.2 correspondiente al Sprint 2 |
| 03/11/2023 | 0.4     | SparkLabs | Se agregó el capítulo 5.2.3 correspondiente al Sprint 3 |

## Project Report Collaboration Insights

## Contenido

### Capitulo I: Introducción

#### 1.1. Startup Profile

##### 1.1.1. Descripcion de la Startup

FurniGo nació como una solución innovadora para abordar las limitaciones y desafíos que enfrenta el proceso de adquisición de muebles. La carencia de precisión y comunicación en este proceso a menudo derivaba de la falta de herramientas digitales en la industria, lo que daba lugar a malentendidos en el diseño, ambigüedades y descontento con los productos finales. Además, el proceso tradicional requería una inversión considerable de tiempo por parte de los compradores, quienes tenían que visitar talleres de carpintería en persona, detallar sus requerimientos y esperar a que fueran comprendidos adecuadamente. Lo mismo aplicaba para los carpinteros, que debían interpretar descripciones detalladas, en su mayoría comunicadas verbalmente.  

Para abordar estos desafíos, surgió la concepción de FurniGo como una plataforma integral que beneficiaría tanto a quienes buscan muebles como a los artesanos carpinteros. Reconocimos la importancia de empoderar a ambos actores clave en este proceso: los clientes que diseñan los muebles y los talleres que los construyen. Nuestra solución proporciona un espacio donde los clientes pueden plasmar sus ideas de manera intuitiva, y almacenar y gestionar sus diseños. Al mismo tiempo, los carpinteros pueden acceder a información precisa proveniente de estos diseños, incluyendo la cantidad de piezas requeridas, dimensiones, materiales y colores.  

En esencia, nuestro propósito fundamental en FurniGo es mejorar la experiencia general en el proceso de adquisición de muebles, reduciendo el tiempo invertido y asegurando resultados satisfactorios. A través de una comunicación clara y una toma de decisiones informada, estamos comprometidos en transformar la manera en que las personas encuentran y obtienen muebles de alta calidad.  

##### 1.1.2. Perfiles de Integrantes del equipo

![Team](./img/equipo1.png)
![Team](./img/equipo2.png)  

#### 1.2. Solution Profile

##### 1.2.1. Antecedentes y problematica

Estamos en proceso de crear un producto que permitirá conectar directamente a aquellos clientes que buscan un diseño específico para sus muebles con talleres de carpintería capaces de fabricar sus pedidos de manera rápida, sencilla y segura.  

Como resultado de los desafíos que surgieron a raíz de la pandemia de COVID-19, nos vimos obligados a transformar nuestras rutinas y métodos de trabajo para adaptarnos a este nuevo panorama social. Con el objetivo de asegurarnos de que nadie quedara rezagado y brindar a los talleres de carpintería una oportunidad renovada para llegar a un público más amplio, decidimos abrazar la modalidad virtual.  

Como miembros del equipo de la startup FurniGo, nos hemos embarcado en la tarea de diseñar, desarrollar y administrar una plataforma web que aborde esta necesidad. En el transcurso de 2023, nuestro startup FurniGo lanzará una plataforma integral que atenderá todas las demandas de nuestros clientes.  

Para lograrlo, estamos realizando un estudio exhaustivo de nuestro público objetivo, teniendo en cuenta sus opiniones y sugerencias, procesando información y creando perfiles que nos servirán para definir las funcionalidades y la usabilidad de nuestra plataforma, con el objetivo de hacerla amigable y útil para los usuarios finales.  

###### 1.2.2.1. Lean UX Problem Statements

##### 1.2.2. Lean UX Process

Algunas personas tienen requisitos muy específicos cuando buscan diseñar un mueble a medida. Esto conlleva la necesidad de un servicio altamente personalizado, lo que los lleva a recurrir a talleres de carpintería. Sin embargo, en ocasiones, surgen desafíos en la comunicación que dificultan que el carpintero comprenda completamente el modelo o diseño que el cliente tiene en mente.

¿Cómo se puede mejorar la comunicación entre los clientes y los talleres para asegurar una comprensión precisa de los diseños que los clientes desean?

Observamos que hay personas interesadas en adquirir muebles, y esto nos brinda la oportunidad de conectar a estos compradores con talleres donde puedan comprar lo que necesitan. Sin embargo, hemos notado que algunas personas que están en busca de muebles sienten cierta desconfianza hacia los talleres cuando se trata de hacer una compra.

¿Cuál sería la mejor manera de fortalecer la confianza de los clientes en relación a los talleres?  

###### 1.2.2.2. Lean UX Assumptions

**SUPOSICIONES DE NEGOCIO:**

1\.    Creo que existe una demanda en el mercado de muebles personalizados, donde los clientes buscan una experiencia de compra rápida y segura.

2\.    Para abordar esta necesidad, planeo ofrecer una plataforma con características clave, como una función de búsqueda avanzada para encontrar talleres de muebles adecuados, un sistema de pago integrado en la aplicación y la capacidad de navegar por trabajos previos para inspiración.

3\.    Mis clientes iniciales incluirán tanto consumidores que deseen adquirir muebles personalizados como propietarios de talleres que deseen vender sus productos a través de la plataforma.

4\.    La principal propuesta de valor para los clientes será la seguridad y la facilidad de encontrar talleres de confianza, así como la rapidez en el proceso de compra de muebles personalizados.

5\.    También permitiré a los clientes evaluar y calificar los talleres con los que han trabajado, lo que proporcionará retroalimentación valiosa para otros compradores.

6\.    Planeo atraer a la mayoría de mis clientes a través de estrategias de marketing en redes sociales y campañas publicitarias dirigidas.

7\.    Generaré ingresos mediante un cargo adicional al momento de realizar la compra de muebles personalizados a través de la plataforma.

8\.    En el mercado, competiré principalmente con otros proveedores de muebles personalizados, aunque también tendré en cuenta competidores en el ámbito de muebles prefabricados.

9\.    Creo que nuestra ventaja competitiva radica en ofrecer a los clientes la posibilidad de diseñar sus propios muebles personalizados, lo que nos diferencia de la competencia.

10\.    Reconozco que uno de los mayores riesgos del producto es la posible falta de adopción inicial por parte de los usuarios y la complejidad percibida de la interfaz de la aplicación.

11\.    Planeo mitigar estos riesgos a través de una comunicación efectiva con nuestros usuarios, recopilando sus comentarios y realizando mejoras continuas en la interfaz y la experiencia del usuario.

12\.    Suposiciones Adicionales:

•    Anticipo una acogida inicial limitada, pero confío en que podremos retener a los usuarios a largo plazo mediante un servicio de alta calidad.

•    Creo que estamos ingresando a un mercado poco explotado, lo que nos brinda oportunidades de crecimiento significativas.  

**SUPOSICIONES DE USUARIO:**  

1\. ¿Quién es el usuario?

Personas que quieren comprar muebles y los dueños de talleres de carpintería

2\. ¿Dónde encaja nuestro producto en su trabajo o vida?

Tanto en actividades de su vida como trabajo

3\. ¿Qué problemas tiene nuestro producto y cómo se puede resolver?

Actualmente no se pueden encontrar talleres, esto se puede solucionar contactando y afiliando talleres.

4\. ¿Cuándo y cómo es usado nuestro producto?

Es usado cuando se quiere comprar un mueble y se usará a través de su dispositivo móvil mediante una aplicación.

5\. ¿Qué características son importantes?

Que sea fácil de instalar y utilizar, principalmente al momento de diseñar sus muebles.

6\. ¿Cómo debe verse nuestro producto y cómo debe comportarse?

Deberá mostrar muebles, además ser rápido y eficiente

###### 1.2.2.3. Lean UX Hypothesis Statements

Creemos que al permitir a los talleres registrar sus datos en la aplicación, les facilitará publicar sus servicios.

Sabremos que hemos tenido éxito

Cuando al menos un 30% de los talleres en Lima se registren.

Creemos que al permitir a los talleres registrar sus contactos, mejorará la comunicación con los usuarios.

Sabremos que hemos tenido éxito

Cuando la satisfacción de clientes y talleres aumente en un 10%.

Creemos que al implementar un sistema de valoraciones y reseñas sobre los servicios, ayudaremos a los usuarios a encontrar talleres ideales.

Sabremos que hemos tenido éxito

Cuando la satisfacción del cliente aumente en un 10%.

Creemos que al permitir a los talleres mostrar productos ya fabricados, aumentaremos sus ingresos.

Sabremos que hemos tenido éxito

Cuando la satisfacción de los talleres aumente en un 15%.

Creemos que al agregar la función de realizar pagos dentro de la aplicación, aumentará la confianza de los usuarios en nuestra plataforma.

Sabremos que hemos tenido éxito

Cuando el número de desinstalaciones de nuestra aplicación se reduzca en un 10%.

###### 1.2.2.4. Lean UX Canvas

<table><tr><th valign="top"><p><b>Business Problem</b> </p><p>Hemos observado que las personas que quieren adquirir muebles a medida tardan mucho tiempo encontrando talleres adecuados a sus necesidades y mucho más explicando el producto que quieren. </p><p>Además, los talleres de carpintería tienen dificultades para expandir su clientela. </p></th><th rowspan="2" valign="top"><p><b>Solution Ideas</b> </p><p>- Una aplicación que ayude a los usuarios a encontrar el taller más adecuado para su diseño. </p><p>- Una aplicación que permita al usuario diseñar sus propios muebles </p><p>- Una aplicación donde el usuario pueda calificar el servicio de carpintería. </p><p>- Una aplicación que le permita al taller de carpintería aumentar y controlar su afluencia de clientes y pedidos. </p><p>- Una aplicación que le permita al taller de carpintería vender sus muebles prefabricados. </p></th><th valign="top"><p><b>Business Outcomes</b> </p><p>- Nuestros usuarios consiguen los muebles que quieren </p><p>- Los talleres consiguen más clientes y por consecuencia más ingresos </p><p>- Que al menos un 25% de usuarios conserven la aplicación </p><p></b>  </p></th></tr>
<tr><td valign="top"><p><b>Users & Customers</b> </p><p>Clientes: Personas de 18 a 60 años que quieren comprar muebles para decorar sus hogares o para algún uso particular. </p><p>Talleres: Talleres de carpintería que quieren publicitarse para aumentar sus clientes y sus ventas </p></td><td valign="top"><p><b>User Benefits</b> </p><p>- Reducir el tiempo que toma comprar un mueble. </p><p>- Diseñar muebles de forma fácil e intuitiva, con una interfaz fácil de entender </p><p>- La posibilidad de reseñar el servicio brindado y ver las recomendaciones de otros usuarios </p><p>- Publicitar sus servicios para aumentar su alcance </p></td></tr>
<tr><td valign="top"><p><i><b>Hypotheses</b></i> </p><p>- Creemos que al registrar los datos del taller les permitirá publicar su taller en la aplicación </p><p>- Sabremos que hemos tenido éxito </p><p>- Cuando al menos un 30% de los talleres en Lima se registren </p></td><td valign="top"><p><i><b>What's the most important thing we need to learn first?</b></i> </p><p>- Conocer los distintos talleres de carpintería en Lima y el proceso de construcción de un mueble </p><p>- Conocer los patrones de conducta de las personas que compran muebles o están interesadas en comprar muebles. </p></td><td valign="top"><p><i><b>What's the least amount of work we need to do to learn the next most important thing?</b></i> </p><p>- Entrevistas a las personas que compran muebles de forma regular </p><p>- Contactar dueños de talleres de carpintería </p></td></tr>
</table>

#### 1.3. Segmentos Objetivos

Nuestra aplicación tiene dos segmentos objetivos, listados a continuación:  

\- Clientes:  

`  `Estos son personas naturales que desean adquirir muebles hechos a pedido. Tienen en mente el diseño de dicho mobiliario y lo tienen plasmado en un esquema o plano o, preferentemente, pueden utilizar un programa de modelado como SketchUp para generar un modelo 3D de dicho mueble.

\- Carpinteros/Ebanistas:  

`  `Son personas (o talleres) con experiencia y los medios y recursos necesarios para poder fabricar muebles a pedido a partir de un plano esquemático y/o modelos 3D. Buscan nuevas formas de ofrecer sus servicios, tales como el uso de plataformas web que les permita ofrecer presupuestos a potenciales clientes que tienen un diseño de mueble en mente.

### Capitulo II: Requirements Elicitation & Analysis

#### 2.1. Competidores

##### 2.1.1. Analisis Competitivo

<table style="undefined;table-layout: fixed; width: 903px">
<colgroup>
<col style="width: 72.2px">
<col style="width: 146.2px">
<col style="width: 171.2px">
<col style="width: 171.2px">
<col style="width: 171.2px">
<col style="width: 171.2px">
</colgroup>
<thead>
  <tr>
    <th colspan="6">Competitive Analysis Landscape</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td colspan="2" rowspan="2">¿Por qué llevar a cabo este análisis?</td>
    <td colspan="4">¿Cuáles son las fortalezas y debilidades de nuestros competidores? ¿Cuáles son nuestras fortalezas y debilidades en comparación con nuestros competidores? ¿Existen oportunidades para diferenciarnos de nuestros competidores y cómo podemos aprovecharlas?</td>
  </tr>
  <tr>
    <td colspan="4">Nos diferenciaremos de la comptencia ofreciendo al cliente la oportunidad de conseguir muebles mucho más personalizados, puesto que ellos pueden enviar sus diseños a varios carpinteros, ebanistas y tapiceros para que evalúen la propuesta y envíen una proforma y fecha.</td>
  </tr>
  <tr>
    <td colspan="2">Competidores</td>
    <td>FurniGo</td>
    <td>Promart</td>
    <td>Sodimac</td>
    <td>Saga Falabella</td>
  </tr>
  <tr>
    <td rowspan="2">Perfil</td>
    <td>Overview</td>
    <td>Plataforma de comercio especializada en la manufactura de muebles a pedido con diseños personalizados, llevados a cabo por carpinteros y talleres especializados. </td>
    <td>Tienda de mejoramiento del hogar. Vende, entre otros, mobiliario de diferentes materiales y diseños. Cuenta con servicio de envío a domicilio y opciones de financiamiento a través de Financiera Oh!.</td>
    <td>Tienda de mejoramiento del hogar. En su división Homecenter, en contraste a Constructor, vende artículos para el hogar y muebles en diferentes materiales y diseños. Cuenta con servicio de envío a domicilio y financiamiento con Banco Falabella. </td>
    <td>Tienda de ventas por departamento. En la sección de hogar, vende muebles y juegos completos para diferentes ambientes. Cuenta con servicio de envío a domicilio y financiamiento con Banco Falabella.</td>
  </tr>
  <tr>
    <td>Ventaja competitiva ¿Qué valor ofrece al cliente?</td>
    <td>Brinda al usuario comprador la posibilidad de hallar múltiples ofertas y cotizaciones para los muebles que tiene en mente con solo presentar su diseño en plano o modelo 3D.</td>
    <td colspan="3">Cuentan con muchos locales alrededor del Perú, una página web y un amplio catálogo de opciones accesibles, además de contar con delivery a todo Lima y, ocasionalmente, a zonas aledañas a tiendas en provincia.</td>
  </tr>
  <tr>
    <td rowspan="2">Perfil de marketing</td>
    <td>Mercado objetivo</td>
    <td>Personas de 18 a 60 años que desean adquirir mobiliario con diseño personalizado de manera conveniente.
Carpinteros/Talleres: Profesionales que desean utilizar medios digitales para ampliar su alcance y aumentar sus ganancias.
</td>
    <td colspan="3">El mercado objetivo de las tres tiendas son personas de entre 18 y 60 años que desean adquirir diferentes productos para su uso o mejora/decoración del hogar.</td>
  </tr>
  <tr>
    <td>Estrategias de marketing</td>
    <td>Dar a los talleres carpinteros la oportunidad de fabricar piezas únicas para potenciales clientes que desean tener un mueble único.</td>
    <td>Brindamos soluciones integrales con productos especializados para cada sector </td>
    <td>El objetivo de Sodimac en marketing es convertirse como marca en el mejor socio para los especialistas de la construcción, acompañándolos en el camino del progreso y crecimiento y ayudándolos a llevar a cabo sus obras del mejor modo.</td>
    <td>Ha implementado el marketing on-line utilizando las diferentes estrategias y tácticas del mismo, para expandir su mercado, captar nuevos clientes, lograr un mayor posicionamiento y promover sus productos y/o servicios; por consiguiente, generar más ventas.</td>
  </tr>
  <tr>
    <td rowspan="4">Perfil del producto</td>
    <td>Productos y servicios</td>
    <td>Plataforma web especializada orientada a conectar clientes compradores y talleres de carpintería. </td>
    <td>Tiendas físicas y virtual para la adquisición de productos para el mejoramiento del hogar o construcción.
</td>
    <td>Tiendas físicas y virtual para la adquisición de productos para el mejoramiento del hogar o construcción.
</td>
    <td>Tiendas físicas y virtual para la adquisición de artículos de moda, belleza, electrodomésticos y mobiliario para el hogar.
</td>
  </tr>
  <tr>
    <td>Precios y costos</td>
    <td>Cobro de comisión a los talleres por orden de trabajo.</td>
    <td colspan="3">Dependen del artículo comprado.</td>
  </tr>
  <tr>
    <td>Canales de distribución</td>
    <td>Web</td>
    <td>Tiendas físicas y web</td>
    <td>Tiendas físicas y web</td>
    <td>Tiendas físicas y web</td>
  </tr>
  <tr>
    <td>Tecnologías usadas</td>
    <td>Java, HTML, CSS, Angular.js Typescript flavoured, HTTPS</td>
    <td>Kotlin/Swift</td>
    <td>Kotlin/Swift</td>
    <td>Kotlin/Swift</td>
  </tr>
  <tr>
    <td rowspan="4">Análisis SWOT</td>
    <td>Fortalezas</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Debilidades</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Oportunidades</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Amenazas</td>
    <td>Competidores con mucha más experiencia</td>
    <td></td>
    <td></td>
    <td>Competencia más especializada. Sodimac es incluso una empresa de la misma matriz.</td>
  </tr>
</tbody>
</table>

##### 2.1.2. Estrategias y tacticas frente a competidores

**Estrategias:**  
**Desarrollo de una plataforma de prototipos virtuales**: Crearemos una plataforma en línea donde los diseñadores puedan visualizar sus prototipos de manera virtual. Esto les permitirá mostrar sus diseños de manera realista y atractiva, sin necesidad de fabricar los productos físicamente.  
**Enfocaremos nuestros esfuerzos en la personalización y la exclusividad**: Destacaremos la posibilidad de obtener productos únicos y personalizados a través de nuestra plataforma. Aprovecharemos la tendencia actual hacia lo exclusivo y lo personalizado, atrayendo a los consumidores que buscan artículos distintivos para sus hogares.  

**Tácticas**:  
**Implementación de una estrategia de marketing de contenidos**: Adicionalmente a prestar el servicio de conectar a los clientes y fabricantes, incluiremos la posibilidad de poder compartir resultados de los muebles fabricados a través de nuestro servicio, lo cual ayuda a respaldar la experiencia y calidad del trabajo de los carpinteros y talleres.  
**Ofreceremos una experiencia de usuario excepcional**: Garantizaremos que nuestra plataforma sea fácil de usar y brinde una experiencia de usuario excepcional. Destacaremos la navegación intuitiva, la visualización en 3D y las opciones de personalización para atraer y retener a los usuarios.  
**Identificaremos nichos específicos en el mercado**: Reconoceremos segmentos no atendidos por las grandes marcas en el mercado de decoración para el hogar. Nos enfocaremos en estilos particulares, como el minimalismo, el vintage o lo étnico, buscando incluir talleres dispuestos a incursionar en estos estilos.  
**Recopilaremos retroalimentación constante**: Estableceremos un sistema para captar comentarios y sugerencias de talleres y clientes. Utilizaremos esta información para mejorar continuamente nuestra plataforma y los servicios que brindamos.  

#### 2.2. Entrevistas

##### 2.2.1. Diseño de entrevistas

**Estructura de la entrevista**:  

- Saludo inicial  
- Preguntas del segmento correspondiente  
- Explicación de la aplicación de forma relevante a su segmento.  
- Preguntas sobre el proyecto  
- Preguntas y autovaloración sobre habilidades digitales  

**Lista de preguntas:**  

*Preguntas introductorias:* 

Segmento cliente persona:  

- ¿Cuál es su nombre?
- ¿Edad?
- ¿Cuál es su ocupación? ¿Estudia o trabaja?
- ¿Se consideraría creativo o sensible?
- ¿Con qué regularidad hace compras por internet?
- ¿Cuál es el tipo de artículos que suele comprar?
- Por lo general, ¿cómo adquiere un mueble? ¿Tiene alguna tienda preferida?
- ¿Alguna vez ha comprado mobiliario a través de internet? De ser así, ¿puede comentarme alguna experiencia?
- ¿Alguna vez se ha frustrado por no encontrar los muebles con el diseño o estilo que deseaba?
- ¿Le agradaría la posibilidad de poder crear sus propios diseños? Si es así, ¿cree que sería capaz de plasmar los diseños en planos que detallen medidas, material, colores? ¿Sería práctico para usted?
- ¿Conoce alguna aplicación de diseño que pueda servir para este propósito?
  Preguntas sobre el proyecto:
- ¿Qué opina sobre nuestra aplicación? ¿Considera que podría ser útil?
- ¿Cree que sería práctico el uso de esta o es muy complejo para su propósito?
- ¿Le agradaría la idea de realizar los pagos a través de la aplicación?
- ¿Qué funcionalidades propondría para la aplicación?
- ¿Pagaría usted por el uso de la aplicación? ¿Cuánto?  

Segmento carpintero/taller de carpintería:

- ¿Cuál es su nombre?
- ¿Edad?
- Respecto a su trabajo de carpintero, ¿tuvo algún tipo de formación profesional, fue aprendiz o es autodidacta?
- Respecto a su taller, ¿solo usted trabaja en él o tiene otros colaboradores?
- ¿Cuántos pedidos suele tener por mes? ¿Me podría detallar un poco de ellos? Tal vez son juegos completos de sala, reparaciones de muebles, etc.
- ¿Simultáneamente cuantos pedidos avanza? ¿Se dedica completamente a uno, los reparte con sus colaboradores o de qué forma se organiza?
- ¿Alguna vez un cliente le llevó un plano o modelo 3D sobre el mueble que deseaba? ¿Cómo fue la experiencia? ¿Fue fácil de comprender?
- ¿Cree usted poder comprender como fabricar un mueble a partir de un modelo 3D?
  o    De ser posible, presentar un modelo 3D al carpintero e interactuar para determinar si lo entendió o no. Apuntar qué detalles requiere para la fabricación.
- ¿Publicita su trabajo en redes sociales o prefiere las recomendaciones por sus mismos clientes?
- ¿Usted, o alguien en el taller, también hace diseños para los muebles? ¿Con qué frecuencia?
- Al momento de realizar el diseño, ¿utiliza algún tipo de software para hacerlo o depende completamente de planos o maquetas?
- ¿Le es atractiva la idea de contar con una herramienta digital para este fin?
- ¿Le interesaría una aplicación que le ayude en la búsqueda de clientes?  

*Preguntas sobre el proyecto:*

- ¿Qué opina de nuestra aplicación? ¿Considera que le sería útil?
- ¿Considera que es práctica para su fin?
- ¿Conoce alguna herramienta similar a esta? ¿La usa o conoce algún otro taller que la use?
- ¿Considera que nuestra aplicación puede aumentar sus ventas e ingresos?
- ¿Qué funcionalidades considera usted importantes para la aplicación?
  Preguntas sobre competencia de herramientas digitales:
  En una escala del 1 al 10:
- ¿Cómo se califica con el uso de los smartphones y/o tablets?
- ¿Cómo se califica con el uso de laptops y computadoras?
- ¿Cómo se califica con el uso de navegadores de internet?
- ¿Cómo se califica con el uso de aplicaciones móviles? ¿Y de escritorio?
- ¿Qué herramientas de diseño conoce? ¿Cómo se califica con su uso?
- Para el uso de la aplicación y diseño de los muebles, ¿podría usted aprender a utilizar la aplicación o se vuelve una tarea muy compleja?
  
  #### 2.3. Needfinding
  
  ##### 2.3.1. User Personas
  
  ![User Persona 1](./img/user-persona-1.png)  
  ![User Persona 2](./img/user-persona-2.png)  

##### 2.3.2. User Task Matrix

<table style="undefined;table-layout: fixed; width: 550px">
<tbody>
<tr>
    <td rowspan="2">Task Matrix</td>
    <td colspan="2">Cliente</td>
    <td colspan="2">Carpintero</td>
  </tr>
  <tr>
    <td>Frecuencia</td>
    <td>Importancia</td>
    <td>Frecuencia</td>
    <td>Importancia</td>
  </tr>
  <tr>
    <td>Buscar información de talleres de carpintería confiables</td>
    <td>Media</td>
    <td>Alta</td>
    <td>-</td>
    <td>-</td>
  </tr>
  <tr>
    <td>Buscar modelos de muebles en internet</td>
    <td>Media</td>
    <td>Alta</td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Realizar un bosquejo de lo que de lo que deseo</td>
    <td>Media</td>
    <td>Alta</td>
    <td>-</td>
    <td>-</td>
  </tr>
  <tr>
    <td>Investigar qué materiales me convienen para mi mueble</td>
    <td>Media</td>
    <td>Alta</td>
    <td>Baja</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Contactar a algún taller que pueda realizar lo que deseo</td>
    <td>Alta</td>
    <td>Alta</td>
    <td>-</td>
    <td>-</td>
  </tr>
  <tr>
    <td>Acordar tiempo de entrega del mueble</td>
    <td>Media</td>
    <td>Alta</td>
    <td>Media</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Reunirse para afinar detalles</td>
    <td>Media</td>
    <td>Alta</td>
    <td>Media</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Definir un presupuesto</td>
    <td>Media</td>
    <td>Alta</td>
    <td>Media</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Comprar materiales</td>
    <td>-</td>
    <td>-</td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Realizar medidas</td>
    <td>-</td>
    <td>-</td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Construir las partes del mueble</td>
    <td>-</td>
    <td>-</td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Armar el mueble</td>
    <td>-</td>
    <td>-</td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Afinar detalles del mueble</td>
    <td>Baja</td>
    <td>Alta</td>
    <td>Media</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Entrega del mueble terminado</td>
    <td>Media</td>
    <td>Alta</td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  </tbody>
</table>

##### 2.3.4. Empathy Mapping

### Segmento Cliente

![Empathy mapping clientes](./img/empathy-mapping-clientes.jpg)  

### Segmento Carpintero

![Empathy mapping carpinteros](./img/empathy-mapping-carpinteros.jpg)  

##### 2.3.5. As-is Scenario Mapping

![As-Is Scenario Map for Client](./img/as-is-scenario-map-cliente.jpg)  

![As-Is Scenario Map for Expert](./img/as-is-scenario-map-carpintero.jpg)  

### Capitulo III: Requirements Specification

#### 3.1. To-Be Scenario Mapping

+ ![To-Be 1](./img/To-be1.png)
+ ![To-Be 2](./img/To-be2.png)

#### 3.2. User Stories


<table  border="2" cellpadding="1" bordercolor="#3253dd">
    <tbody>
        <tr>
            <td rowspan=1 align="center">HU:</td>
            <td rowspan=1 align="center">183309360</td>
            <td align="center">Título:</td>
            <td align="center">Usuario taller contacta con un usuario </td>
        </tr>
        <tr>
            <td rowspan=1 align="center">Usuario:</td>
            <td rowspan=1 align="center">Taller</td>
            <td align="center">Sprint:</td>
            <td align="center">1</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Descripción</td>
            <td colspan=3 align="justify"> Como usuario taller quiero poder contactar con un usuario el cual posea un diseño que pueda realizar.
        </tr>
        <tr>
            <td colspan=1 align="center">Criterios de Aceptación</td>
            <td colspan=3 align="justify"> 
            <b>Scenario 1: Ingreso a la sección Diseños</b> 
            <br><b>Dado que </b> el usuario taller es un usuario verificado
            <br><b>Y</b> el usuario taller ha iniciado sesión correctamente
            <br><b>Y</b> el usuario taller se encuentra en la pantalla principal
            <br><b>Cuando </b> haga click en la pestaña de la sección Diseños
            <br><b>Entonces</b> podrá acceder a una interfaz de búsqueda de diseños la cual está compuesta de un buscador, una barra de filtrado de datos y los resultados mostrados en una grilla de cards.
            <br>          
            <br>          
            <b>Scenario 2: Selecciona un diseño en específico</b> 
            <br><b>Dado que </b> el usuario taller es un usuario verificado
            <br><b>Y</b> el usuario taller ha iniciado sesión correctamente
            <br><b>Y</b> el usuario taller se encuentra en la sección Diseños
            <br><b>Y</b> el usuario taller ha buscado un taller en específico          
            <br><b>Cuando </b> seleccione un diseño en específico
            <br><b>Entonces</b> se desplegará una ventana con el gráfico del diseño, detalles técnicos e información relacionada.
            </td>            
        </tr>
        <tr>
            <td colspan=1 align="center">Prioridad</td>
            <td colspan=3 align="center">Alta</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Puntos de Historia</td>
            <td colspan=3 align="center">8 puntos</td>
        </tr>
    </tbody>
</table>

<table  border="2" cellpadding="1" bordercolor="#3253dd">
    <tbody>
        <tr>
            <td rowspan=1 align="center">HU:</td>
            <td rowspan=1 align="center">183309362</td>
            <td align="center">Título:</td>
            <td align="center">Usuario taller elige qué pedido de mueble construir </td>
        </tr>
        <tr>
            <td rowspan=1 align="center">Usuario:</td>
            <td rowspan=1 align="center">Taller</td>
            <td align="center">Sprint:</td>
            <td align="center">1</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Descripción</td>
            <td colspan=3 align="justify"> Como usuario taller quiero visualizar todos los pedidos disponibles a diseñar para elegir el que sea capaz de construirlo
        </tr>
        <tr>
            <td colspan=1 align="center">Criterios de Aceptación</td>
            <td colspan=3 align="justify"> 
            <b>Scenario 1: Elige el pedido de un cliente</b> 
            <br><b>Dado que </b> el usuario taller ha iniciado sesión correctamente
            <br><b>Cuando </b> le de click a la opción Mis Proyectos
            <br><b>Entonces</b> se abrirá una nueva ventana con las demandas de diseños de clientes mas cercanos a la zona
            <br>            
            </td>            
        </tr>
        <tr>
            <td colspan=1 align="center">Prioridad</td>
            <td colspan=3 align="center">Alta</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Puntos de Historia</td>
            <td colspan=3 align="center">8 puntos</td>
        </tr>
    </tbody>
</table>

<table  border="2" cellpadding="1" bordercolor="#3253dd">
    <tbody>
        <tr>
            <td rowspan=1 align="center">HU:</td>
            <td rowspan=1 align="center">183309370</td>
            <td align="center">Título:</td>
            <td align="center">Usuario taller revisa sus pedidos pendientes </td>
        </tr>
        <tr>
            <td rowspan=1 align="center">Usuario:</td>
            <td rowspan=1 align="center">Taller</td>
            <td align="center">Sprint:</td>
            <td align="center">1</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Descripción</td>
            <td colspan=3 align="justify"> Como usuario de la aplicación quiero visualizar los proyectos de diseño que tengo pendientes, para así poder organizar mi tiempo y entregarlos satisfactoriamente.
        </tr>
        <tr>
            <td colspan=1 align="center">Criterios de Aceptación</td>
            <td colspan=3 align="justify"> 
            <b>Scenario 1: Visualización de pedidos</b> 
            <br><b>Dado que </b> el usuario taller es un usuario autenticado
            <br><b>Y</b> el usuario ha iniciado sesión
            <br><b>Y</b> el usuario se encuentra en la sección de mis proyectos
            <br><b>Cuando </b> el usuario seleccione la opción de "Pendientes"
            <br><b>Entonces</b> se visualizarán los proyectos pendientes
            <br>
            </td>            
        </tr>
        <tr>
            <td colspan=1 align="center">Prioridad</td>
            <td colspan=3 align="center">Alta</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Puntos de Historia</td>
            <td colspan=3 align="center">5 puntos</td>
        </tr>
    </tbody>
</table>

<table  border="2" cellpadding="1" bordercolor="#3253dd">
    <tbody>
        <tr>
            <td rowspan=1 align="center">HU:</td>
            <td rowspan=1 align="center">183309370</td>
            <td align="center">Título:</td>
            <td align="center">Cliente revisa sus últimas órdenes </td>
        </tr>
        <tr>
            <td rowspan=1 align="center">Usuario:</td>
            <td rowspan=1 align="center">Cliente</td>
            <td align="center">Sprint:</td>
            <td align="center">1</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Descripción</td>
            <td colspan=3 align="justify"> Como usuario cliente quiero una sección de órdenes para tener mis órdenes organizadas
        </tr>
        <tr>
            <td colspan=1 align="center">Criterios de Aceptación</td>
            <td colspan=3 align="justify"> 
            <b>Scenario 1: No ha realizado ninguna órden</b> 
            <br><b>Dado que </b> el usuario cliente ha iniciado sesión
            <br><b>Y</b> se encuentra en la pantalla principal
            <br><b>Y</b> entra al menú
            <br><b>Cuando </b> seleccione la opción Mis ordenes
            <br><b>Entonces</b> se mostrará una pantalla vacía con el mensaje "No ha realizado ninguna orden"
            <br>
            <b>Scenario 2: Tiene órdenes</b> 
            <br><b>Dado que </b> el usuario cliente ha iniciado sesión
            <br><b>Y</b> se encuentra en la pantalla principal
            <br><b>Y</b> entra al menú
            <br><b>Cuando </b> seleccione la opción Mis ordenes
            <br><b>Entonces</b> se mostrará una pantalla mostrando una lista de todas las órdenes pagadas, por pagar y entregadas
            <br>
            </td>            
        </tr>
        <tr>
            <td colspan=1 align="center">Prioridad</td>
            <td colspan=3 align="center">Alta</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Puntos de Historia</td>
            <td colspan=3 align="center">5 puntos</td>
        </tr>
    </tbody>
</table>

<table  border="2" cellpadding="1" bordercolor="#3253dd">
    <tbody>
        <tr>
            <td rowspan=1 align="center">HU:</td>
            <td rowspan=1 align="center">183309370</td>
            <td align="center">Título:</td>
            <td align="center">Usuario cliente se registra </td>
        </tr>
        <tr>
            <td rowspan=1 align="center">Usuario:</td>
            <td rowspan=1 align="center">Cliente</td>
            <td align="center">Sprint:</td>
            <td align="center">1</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Descripción</td>
            <td colspan=3 align="justify"> Como usuario cliente quiero completar mis datos al registrarme
        </tr>
        <tr>
            <td colspan=1 align="center">Criterios de Aceptación</td>
            <td colspan=3 align="justify"> 
            <b>Scenario 1: Ingreso de datos correctamente</b> 
            <br><b>Dado que </b> el usuario cliente es un usuario sin registrar
            <br><b>Y</b> se encuentra en el formulario para cliente
            <br><b>Cuando </b> presione el botón Registrar
            <br><b>Entonces</b> se le enviará a la pantalla principal
            <br>
            <b>Scenario 2: Omisión de uno de los datos</b> 
            <br><b>Dado que </b> que el usuario cliente es un usuario sin registrar
            <br><b>Y</b> se encuentra en el formulario para cliente
            <br><b>Cuando </b> presione el botón Registrar
            <br><b>Entonces</b> se cambiará el color del campo omitido a rojo
            <br>
            <b>Scenario 3: Ingreso de dato incorrecto</b> 
            <br><b>Dado que </b> que el usuario cliente es un usuario sin registrar
            <br><b>Y</b> se encuentra en el formulario para cliente
            <br><b>Cuando </b> presione el botón Registrar
            <br><b>Entonces</b> se cambiará el color del campo omitido a rojo
            <br>
            </td>            
        </tr>
        <tr>
            <td colspan=1 align="center">Prioridad</td>
            <td colspan=3 align="center">Alta</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Puntos de Historia</td>
            <td colspan=3 align="center">8 puntos</td>
        </tr>
    </tbody>
</table>

<table  border="2" cellpadding="1" bordercolor="#3253dd">
    <tbody>
        <tr>
            <td rowspan=1 align="center">HU:</td>
            <td rowspan=1 align="center">183309370</td>
            <td align="center">Título:</td>
            <td align="center">Usuario taller se registra </td>
        </tr>
        <tr>
            <td rowspan=1 align="center">Usuario:</td>
            <td rowspan=1 align="center">Taller</td>
            <td align="center">Sprint:</td>
            <td align="center">1</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Descripción</td>
            <td colspan=3 align="justify"> Como usuario taller quiero completar mis datos al registrarme
        </tr>
        <tr>
            <td colspan=1 align="center">Criterios de Aceptación</td>
            <td colspan=3 align="justify"> 
            <b>Scenario 1: Ingreso de datos correctamente</b> 
            <br><b>Dado que </b> el usuario taller es un usuario sin registrar
            <br><b>Y</b> se encuentra en el formulario para taller
            <br><b>Cuando </b> presione el botón Registrar
            <br><b>Entonces</b> se le enviará a la pantalla principal
            <br>
            <b>Scenario 2: Omisión de uno de los datos</b> 
            <br><b>Dado que </b> que el usuario taller es un usuario sin registrar
            <br><b>Y</b> se encuentra en el formulario para taller
            <br><b>Cuando </b> presione el botón Registrar
            <br><b>Entonces</b> se cambiará el color del campo omitido a rojo
            <br>
            <b>Scenario 3: Ingreso de dato incorrecto</b> 
            <br><b>Dado que </b> que el usuario taller es un usuario sin registrar
            <br><b>Y</b> se encuentra en el formulario para taller
            <br><b>Cuando </b> presione el botón Registrar
            <br><b>Entonces</b> se cambiará el color del campo omitido a rojo
            <br>
            </td>            
        </tr>
        <tr>
            <td colspan=1 align="center">Prioridad</td>
            <td colspan=3 align="center">Alta</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Puntos de Historia</td>
            <td colspan=3 align="center">8 puntos</td>
        </tr>
    </tbody>
</table>

<table  border="2" cellpadding="1" bordercolor="#3253dd">
    <tbody>
        <tr>
            <td rowspan=1 align="center">HU:</td>
            <td rowspan=1 align="center">183309372</td>
            <td align="center">Título:</td>
            <td align="center">Registro de Tarjeta </td>
        </tr>
        <tr>
            <td rowspan=1 align="center">Usuario:</td>
            <td rowspan=1 align="center">Cliente</td>
            <td align="center">Sprint:</td>
            <td align="center">1</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Descripción</td>
            <td colspan=3 align="justify"> Como usuario cliente quiero poder administrar mis datos de tarjeta en la aplicación
        </tr>
        <tr>
            <td colspan=1 align="center">Criterios de Aceptación</td>
            <td colspan=3 align="justify"> 
            <b>Scenario 1: Registro de tarjeta</b> 
            <br><b>Dado que </b> el usuario cliente ha iniciado sesión
            <br><b>Y</b> se encuentra en la pantalla de información de pago
            <br><b>Cuando </b> presione el botón "Agregar tarjeta" 
            <br><b>Entonces</b> se mostrará un formulario para ingresar los datos de la tarjeta
            <br>
            <b>Scenario 2: Eliminación de tarjeta registrada</b> 
            <br><b>Dado que </b> el usuario cliente ha iniciado sesión
            <br><b>Y</b> se encuentra en la pantalla de información de pago
            <br><b>Cuando </b> presione el botón "Borrar" de la parte derecha de una de las tarjetas de la lista
            <br><b>Entonces</b> dicha tarjeta será removida de la lista
            <br>
            </td>            
        </tr>
        <tr>
            <td colspan=1 align="center">Prioridad</td>
            <td colspan=3 align="center">Alta</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Puntos de Historia</td>
            <td colspan=3 align="center">5 puntos</td>
        </tr>
    </tbody>
</table>

<table  border="2" cellpadding="1" bordercolor="#3253dd">
    <tbody>
        <tr>
            <td rowspan=1 align="center">HU:</td>
            <td rowspan=1 align="center">183309374</td>
            <td align="center">Título:</td>
            <td align="center">Ingreso al menú principal </td>
        </tr>
        <tr>
            <td rowspan=1 align="center">Usuario:</td>
            <td rowspan=1 align="center">Cliente</td>
            <td align="center">Sprint:</td>
            <td align="center">1</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Descripción</td>
            <td colspan=3 align="justify"> Como usuario cliente quiero un menú donde todas las funciones de la aplicación estén disponibles
        </tr>
        <tr>
            <td colspan=1 align="center">Criterios de Aceptación</td>
            <td colspan=3 align="justify"> 
            <b>Scenario 1: Ingreso al menú</b> 
            <br><b>Dado que </b> el usuario cliente ha iniciado sesión
            <br><b>Y</b> se encuentre en la pantalla principal
            <br><b>Cuando </b> presione los tres puntos de forma vertical
            <br><b>Entonces</b> se mostrará atajos a todas las secciones de la aplicación
            <br>
            </td>            
        </tr>
        <tr>
            <td colspan=1 align="center">Prioridad</td>
            <td colspan=3 align="center">Media</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Puntos de Historia</td>
            <td colspan=3 align="center">4 puntos</td>
        </tr>
    </tbody>
</table>

<table  border="2" cellpadding="1" bordercolor="#3253dd">
    <tbody>
        <tr>
            <td rowspan=1 align="center">HU:</td>
            <td rowspan=1 align="center">183309376</td>
            <td align="center">Título:</td>
            <td align="center">Acceso a las notificaciones </td>
        </tr>
        <tr>
            <td rowspan=1 align="center">Usuario:</td>
            <td rowspan=1 align="center">Taller</td>
            <td align="center">Sprint:</td>
            <td align="center">1</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Descripción</td>
            <td colspan=3 align="justify"> Como usuario taller quiero acceder a un menú de notificaciones para poer administrarlas
        </tr>
        <tr>
            <td colspan=1 align="center">Criterios de Aceptación</td>
            <td colspan=3 align="justify"> 
            <b>Scenario 1: Acceso a las notificaciones</b> 
            <br><b>Dado que </b> el usuario taller es un usuario registrado
            <br><b>Y</b> se encuentra en el menú
            <br><b>Cuando </b> presione el botón "Notificaciones"
            <br><b>Entonces</b> entrará a la pantalla de notificaciones
            <br>
            </td>            
        </tr>
        <tr>
            <td colspan=1 align="center">Prioridad</td>
            <td colspan=3 align="center">Media</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Puntos de Historia</td>
            <td colspan=3 align="center">3 puntos</td>
        </tr>
    </tbody>
</table>

<table  border="2" cellpadding="1" bordercolor="#3253dd">
    <tbody>
        <tr>
            <td rowspan=1 align="center">HU:</td>
            <td rowspan=1 align="center">183309378</td>
            <td align="center">Título:</td>
            <td align="center">Manejo de notificaciones </td>
        </tr>
        <tr>
            <td rowspan=1 align="center">Usuario:</td>
            <td rowspan=1 align="center">Taller</td>
            <td align="center">Sprint:</td>
            <td align="center">1</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Descripción</td>
            <td colspan=3 align="justify"> Como usuario taller quiero administrar las distintas notificaciones que recibo
        </tr>
        <tr>
            <td colspan=1 align="center">Criterios de Aceptación</td>
            <td colspan=3 align="justify"> 
            <b>Scenario 1: Activación de las notificaciones</b> 
            <br><b>Dado que </b> el usuario taller es un usuario registrado
            <br><b>Y</b> se encuentre en la pantalla de notificaciones
            <br><b>Cuando </b> presione el switch al lado derecho de la categoría correspondiente
            <br><b>Entonces</b> el switch cambiará a color verde y el usuario recibirá notificaciones de esa categoría
            <br>
            </td>            
        </tr>
        <tr>
            <td colspan=1 align="center">Prioridad</td>
            <td colspan=3 align="center">Media</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Puntos de Historia</td>
            <td colspan=3 align="center">2 puntos</td>
        </tr>
    </tbody>
</table>

<table  border="2" cellpadding="1" bordercolor="#3253dd">
    <tbody>
        <tr>
            <td rowspan=1 align="center">HU:</td>
            <td rowspan=1 align="center">183309380</td>
            <td align="center">Título:</td>
            <td align="center">Ingreso al perfil</td>
        </tr>
        <tr>
            <td rowspan=1 align="center">Usuario:</td>
            <td rowspan=1 align="center">Cliente</td>
            <td align="center">Sprint:</td>
            <td align="center">1</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Descripción</td>
            <td colspan=3 align="justify"> Como usuario cliente quiero acceder a mi perfil para manejar mi información
        </tr>
        <tr>
            <td colspan=1 align="center">Criterios de Aceptación</td>
            <td colspan=3 align="justify"> 
            <b>Scenario 1: Ingreso a la información de su perfil</b> 
            <br><b>Dado que </b> que el usuario cliente ha iniciado sesión correctamente
            <br><b>Y</b> se encuentre en el menú principal
            <br><b>Cuando </b> presione el botón Mi Perfil
            <br><b>Entonces</b> entrará a una pantalla con todos sus datos registrados.
            <br>
            </td>            
        </tr>
        <tr>
            <td colspan=1 align="center">Prioridad</td>
            <td colspan=3 align="center">Media</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Puntos de Historia</td>
            <td colspan=3 align="center">2 puntos</td>
        </tr>
    </tbody>
</table>

<table  border="2" cellpadding="1" bordercolor="#3253dd">
    <tbody>
        <tr>
            <td rowspan=1 align="center">HU:</td>
            <td rowspan=1 align="center">183309328</td>
            <td align="center">Título:</td>
            <td align="center">Modificación de datos</td>
        </tr>
        <tr>
            <td rowspan=1 align="center">Usuario:</td>
            <td rowspan=1 align="center">Cliente</td>
            <td align="center">Sprint:</td>
            <td align="center">1</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Descripción</td>
            <td colspan=3 align="justify"> Como usuario cliente quiero modificar la información de mi perfil
        </tr>
        <tr>
            <td colspan=1 align="center">Criterios de Aceptación</td>
            <td colspan=3 align="justify"> 
            <b>Scenario 1: Cambio de datos </b> 
            <br><b>Dado que </b> el usuario cliente ha iniciado sesión correctamente
            <br><b>Y</b> se encuentra en su perfil
            <br><b>Cuando </b> presione la opción Modificar
            <br><b>Entonces</b> todos los campos estarán libres para modificar
            <br>
            </td>            
        </tr>
        <tr>
            <td colspan=1 align="center">Prioridad</td>
            <td colspan=3 align="center">Media</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Puntos de Historia</td>
            <td colspan=3 align="center">3 puntos</td>
        </tr>
    </tbody>
</table>

<table  border="2" cellpadding="1" bordercolor="#3253dd">
    <tbody>
        <tr>
            <td rowspan=1 align="center">HU:</td>
            <td rowspan=1 align="center">183309384</td>
            <td align="center">Título:</td>
            <td align="center">Ingreso al perfil</td>
        </tr>
        <tr>
            <td rowspan=1 align="center">Usuario:</td>
            <td rowspan=1 align="center">Taller</td>
            <td align="center">Sprint:</td>
            <td align="center">1</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Descripción</td>
            <td colspan=3 align="justify">Como usuario taller quiero acceder a mi perfil para manejar mi información personal.
        </tr>
        <tr>
            <td colspan=1 align="center">Criterios de Aceptación</td>
            <td colspan=3 align="justify"> 
            <b>Scenario 1: Ingreso a la información de su perfil</b> 
            <br><b>Dado que </b> el usuario taller ha iniciado sesión correctamente
            <br><b>Y</b> se encuentre en el menú principal
            <br><b>Cuando </b> presione el botón Mi Perfil
            <br><b>Entonces</b> entrará a una pantalla con todos sus datos registrados.
            <br>
            </td>            
        </tr>
        <tr>
            <td colspan=1 align="center">Prioridad</td>
            <td colspan=3 align="center">Media</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Puntos de Historia</td>
            <td colspan=3 align="center">2 puntos</td>
        </tr>
    </tbody>
</table>

<table  border="2" cellpadding="1" bordercolor="#3253dd">
    <tbody>
        <tr>
            <td rowspan=1 align="center">HU:</td>
            <td rowspan=1 align="center">183309388</td>
            <td align="center">Título:</td>
            <td align="center">Aceptación de pedido</td>
        </tr>
        <tr>
            <td rowspan=1 align="center">Usuario:</td>
            <td rowspan=1 align="center">Taller</td>
            <td align="center">Sprint:</td>
            <td align="center">1</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Descripción</td>
            <td colspan=3 align="justify"> Como usuario taller quisiera habilitar el pago del pedido de un cliente
        </tr>
        <tr>
            <td colspan=1 align="center">Criterios de Aceptación</td>
            <td colspan=3 align="justify"> 
            <b>Scenario 1: Agregación de Monto </b> 
            <br><b>Dado que </b> el usuario taller es un usuario autenticado
            <br><b>Y</b> el usuario taller se encuentre en la sección Diseños
            <br><b>Y</b> el usuario taller ha buscado un taller en específico
            <br><b>Y</b> el usuario taller ha seleccionado un taller en específico
            <br><b>Y</b> el usuario taller ha llegado a un acuerdo con el cliente
            <br><b>Y</b> el usuario taller ha escrito el monto correcto
            <br><b>Cuando </b> pulse el botón Aceptar
            <br><b>Entonces</b> la orden se mostrará en la sección Mis Órdenes del cliente
            <br>
            <br><b>Scenario 2: Equivocación del monto </b> 
            <br><b>Dado que </b> el usuario taller es un usuario autenticado
            <br><b>Y</b> el usuario taller se encuentre en la sección Diseños
            <br><b>Y</b> el usuario taller ha buscado un taller en específico
            <br><b>Y</b> el usuario taller ha seleccionado un taller en específico
            <br><b>Y</b> el usuario taller ha llegado a un acuerdo con el cliente
            <br><b>Y</b> el usuario taller ha escrito un monto incorrecto
            <br><b>Cuando </b> pulse el botón Cancelar
            <br><b>Entonces</b> volverá a la sección Diseños
            <br>
            </td>            
        </tr>
        <tr>
            <td colspan=1 align="center">Prioridad</td>
            <td colspan=3 align="center">Media</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Puntos de Historia</td>
            <td colspan=3 align="center">2 puntos</td>
        </tr>
    </tbody>
</table>

<table  border="2" cellpadding="1" bordercolor="#3253dd">
    <tbody>
        <tr>
            <td rowspan=1 align="center">HU:</td>
            <td rowspan=1 align="center">183309398</td>
            <td align="center">Título:</td>
            <td align="center">Filtro de órdenes</td>
        </tr>
        <tr>
            <td rowspan=1 align="center">Usuario:</td>
            <td rowspan=1 align="center">Cliente</td>
            <td align="center">Sprint:</td>
            <td align="center">1</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Descripción</td>
            <td colspan=3 align="justify"> Como usuario cliente quiero filtras mis órdenes para tener una visualización más clara de las mismas
        </tr>
        <tr>
            <td colspan=1 align="center">Criterios de Aceptación</td>
            <td colspan=3 align="justify"> 
            <b>Scenario 1: Filtro por órdenes no pagadas </b> 
            <br><b>Dado que </b> el cliente ha iniciado sesion
            <br><b>Y</b> se encuentra en la sección Mis Órdenes
            <br><b>Y</b> se encuentra en el menú de filtros
            <br><b>Cuando </b> desmarque la casilla Pagados
            <br><b>Entonces</b> no se mostrarán las órdenes pagadas
            <br>
            <br><b>Scenario 2: Filtro por órdenes no entregadas </b> 
            <br><b>Dado que </b> el cliente ha iniciado sesion
            <br><b>Y</b> se encuentra en la sección Mis Órdenes
            <br><b>Y</b> se encuentra en el menú de filtros
            <br><b>Cuando </b> desmarque la casilla Entregados
            <br><b>Entonces</b> no se mostrarán las órdenes entregadas
            <br>
            </td>            
        </tr>
        <tr>
            <td colspan=1 align="center">Prioridad</td>
            <td colspan=3 align="center">Baja</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Puntos de Historia</td>
            <td colspan=3 align="center">2 puntos</td>
        </tr>
    </tbody>
</table>

<table  border="2" cellpadding="1" bordercolor="#3253dd">
    <tbody>
        <tr>
            <td rowspan=1 align="center">HU:</td>
            <td rowspan=1 align="center">183309398</td>
            <td align="center">Título:</td>
            <td align="center">Lista de tarjetas</td>
        </tr>
        <tr>
            <td rowspan=1 align="center">Usuario:</td>
            <td rowspan=1 align="center">Cliente</td>
            <td align="center">Sprint:</td>
            <td align="center">1</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Descripción</td>
            <td colspan=3 align="justify"> Como usuario cliente quiero ver una lista de las tarjetas que he registrado al momento de pagar para legir la correcta
        </tr>
        <tr>
            <td colspan=1 align="center">Criterios de Aceptación</td>
            <td colspan=3 align="justify"> 
            <b>Scenario 1: Varias tarjetas registradas </b> 
            <br><b>Dado que </b> el usuario cliente es un usuario registrado
            <br><b>Y</b> se encuentra en la sección Mis Órdenes
            <br><b>Cuando </b> seleccione la opción Pagar en uno de sus diseños por pagar
            <br><b>Entonces</b> se mostrará una lista de todas las tarjetas que ha registrado, con el botón Agregar tarjeta al final de dicha lista.
            <br>
            <br><b>Scenario 2: Ninguna tarjeta registrada </b> 
            <br><b>Dado que </b> el usuario cliente es un usuario registrado
            <br><b>Y</b> se encuentra en la sección Mis Órdenes            
            <br><b>Cuando </b> seleccione la opción Pagar en uno de sus diseños por pagar
            <br><b>Entonces</b> se mostrará un formulario para registrar una tarjeta
            <br>
            </td>            
        </tr>
        <tr>
            <td colspan=1 align="center">Prioridad</td>
            <td colspan=3 align="center">Media</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Puntos de Historia</td>
            <td colspan=3 align="center">2 puntos</td>
        </tr>
    </tbody>
</table>

<table  border="2" cellpadding="1" bordercolor="#3253dd">
    <tbody>
        <tr>
            <td rowspan=1 align="center">HU:</td>
            <td rowspan=1 align="center">183309394</td>
            <td align="center">Título:</td>
            <td align="center">Verificación de tarjeta</td>
        </tr>
        <tr>
            <td rowspan=1 align="center">Usuario:</td>
            <td rowspan=1 align="center">Cliente</td>
            <td align="center">Sprint:</td>
            <td align="center">1</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Descripción</td>
            <td colspan=3 align="justify">Como usuario cliente quiero revisar los datos de mi tarjeta antes de pagar
        </tr>
        <tr>
            <td colspan=1 align="center">Criterios de Aceptación</td>
            <td colspan=3 align="justify"> 
            <b>Scenario 1: Varias tarjetas registradas </b> 
            <br><b>Dado que </b> el usuario cliente es un usuario registrado
            <br><b>Y</b> se encuentra en la lista de tarjetas registradas
            <br><b>Cuando </b> el usuario selecciona una tarjeta
            <br><b>Entonces</b> se mostrará una pantalla mostrando los datos de la tarjeta elegida junto con el monto a pagar y dos botones, uno de "Confirmar" y otro de "Cancelar"
            <br>
            </td>            
        </tr>
        <tr>
            <td colspan=1 align="center">Prioridad</td>
            <td colspan=3 align="center">Media</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Puntos de Historia</td>
            <td colspan=3 align="center">3 puntos</td>
        </tr>
    </tbody>
</table>

<table  border="2" cellpadding="1" bordercolor="#3253dd">
    <tbody>
        <tr>
            <td rowspan=1 align="center">HU:</td>
            <td rowspan=1 align="center">183309398</td>
            <td align="center">Título:</td>
            <td align="center">Momento del pago</td>
        </tr>
        <tr>
            <td rowspan=1 align="center">Usuario:</td>
            <td rowspan=1 align="center">Cliente</td>
            <td align="center">Sprint:</td>
            <td align="center">1</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Descripción</td>
            <td colspan=3 align="justify">Como usuario cliente quiero confirmar o cancelar el pago de mi producto
        </tr>
        <tr>
            <td colspan=1 align="center">Criterios de Aceptación</td>
            <td colspan=3 align="justify"> 
            <b>Scenario 1: Confirmación de pago </b> 
            <br><b>Dado que </b> el usuario cliente es un usuario registrado
            <br><b>Y</b> se encuentra en la pantalla de confirmación
            <br><b>Cuando </b> presione el botón "Confirmar"
            <br><b>Entonces</b> Se mostrará el mensaje "Pago realizado con éxito" y se regresará a la pantalla de Mis Órdenes.
            <br>
            <br><b>Scenario 2: Saldo insuficiente </b> 
            <br><b>Dado que </b> el usuario cliente es un usuario registrado
            <br><b>Y</b> se encuentra en la pantalla de confirmación            
            <br><b>Cuando </b> presione el botón "Confirmar"
            <br><b>Entonces</b> se mostrará un mensaje "Transacción rechazada" y se regresará a la pantalla de Mis Órdenes.
            <br>
            <br><b>Scenario 3: Declinación de Pago </b> 
            <br><b>Dado que </b> el usuario cliente se encuentra en la pantalla de confirmación
            <br><b>Cuando </b> presione el botón "Cancelar"
            <br><b>Entonces</b> lo llevará a la pantalla de Mis Órdenes.
            </td>            
        </tr>
        <tr>
            <td colspan=1 align="center">Prioridad</td>
            <td colspan=3 align="center">Media</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Puntos de Historia</td>
            <td colspan=3 align="center">3 puntos</td>
        </tr>
    </tbody>
</table>

<table  border="2" cellpadding="1" bordercolor="#3253dd">
    <tbody>
        <tr>
            <td rowspan=1 align="center">HU:</td>
            <td rowspan=1 align="center">183309398</td>
            <td align="center">Título:</td>
            <td align="center">Ajustes de notificaciones</td>
        </tr>
        <tr>
            <td rowspan=1 align="center">Usuario:</td>
            <td rowspan=1 align="center">Cliente</td>
            <td align="center">Sprint:</td>
            <td align="center">1</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Descripción</td>
            <td colspan=3 align="justify">Como usuario cliente quiero editar la configuración de las notificaciones.
        </tr>
        <tr>
            <td colspan=1 align="center">Criterios de Aceptación</td>
            <td colspan=3 align="justify"> 
            <b>Scenario 1: Activación de notificaciones </b> 
            <br><b>Dado que </b> el usuario entra en configuración
            <br><b>Y</b> está en el apartado de notificaciones
            <br><b>Y</b> seleccione la opción Recibir notificaciones al correo
            <br><b>Cuando </b> seleccione la opción SI
            <br><b>Entonces</b> Recibirá las notificaciones al correo electrónico.
            <br>
            <br><b>Scenario 2: Desactivación de notificaciones </b> 
            <br><b>Dado que </b> el usuario entra en configuración
            <br><b>Y</b> está en el apartado de notificaciones
            <br><b>Y</b> seleccione la opción Recibir notifiaciones al correo
            <br><b>Cuando </b> seleccione la opción NO
            <br><b>Entonces</b> no recibirá las notificaciones al correo electrónico.
            </td>            
        </tr>
        <tr>
            <td colspan=1 align="center">Prioridad</td>
            <td colspan=3 align="center">Media</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Puntos de Historia</td>
            <td colspan=3 align="center">2 puntos</td>
        </tr>
    </tbody>
</table>

<table  border="2" cellpadding="1" bordercolor="#3253dd">
    <tbody>
        <tr>
            <td rowspan=1 align="center">HU:</td>
            <td rowspan=1 align="center">183309400</td>
            <td align="center">Título:</td>
            <td align="center">Múltiples Dispositivos</td>
        </tr>
        <tr>
            <td rowspan=1 align="center">Usuario:</td>
            <td rowspan=1 align="center">Taller</td>
            <td align="center">Sprint:</td>
            <td align="center">1</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Descripción</td>
            <td colspan=3 align="justify">Como usuario Taller quiero poder ver mis proyetos en diferentes dispositivos al mismo tiempo
        </tr>
        <tr>
            <td colspan=1 align="center">Criterios de Aceptación</td>
            <td colspan=3 align="justify"> <b>Scenario 1: Uso de dos dispositivos </b> 
            <br>
            <b>Dado que </b> el usuario puede iniciar sesión en varios dispositivos al mismo tiempo 
            <br>
            <b>Cuando </b> esté eligiendo dos pedidos diferentes en dos dispositivos al mismo tiempo
            <br>
            <b>Entonces</b> le aparecerá un mensaje de advertencia en un dispositivo que en el otro dispositivo se está ejecutando una selección de pedido.
            <br><br>        
        </tr>
        <tr>
            <td colspan=1 align="center">Prioridad</td>
            <td colspan=3 align="center">Media</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Puntos de Historia</td>
            <td colspan=3 align="center">3 puntos</td>
        </tr>
    </tbody>
</table>

<table  border="2" cellpadding="1" bordercolor="#3253dd">
    <tbody>
        <tr>
            <td rowspan=1 align="center">HU:</td>
            <td rowspan=1 align="center">183309401</td>
            <td align="center">Título:</td>
            <td align="center">Eliminar tarjeta</td>
        </tr>
        <tr>
            <td rowspan=1 align="center">Usuario:</td>
            <td rowspan=1 align="center">Cliente</td>
            <td align="center">Sprint:</td>
            <td align="center">2</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Descripción</td>
            <td colspan=3 align="justify">Como usuario Cliente quiero poder eliminar una tarjeta que he registrado
        </tr>
        <tr>
            <td colspan=1 align="center">Criterios de Aceptación</td>
            <td colspan=3 align="justify"> <b>Sceniario 1: Eliminar tarjeta adrede. </b> 
            <br>
            <b>Dado que </b> el usuario seleccione una tarjeta registrada 
            <br>
            <b>Cuando </b> el usuario presione el botón de eliminar y confirme en el mensaje de verificación
            <br>
            <b>Entonces</b> aparecerá un mensaje confirmando la eliminación de la tarjeta
            <br><br>
            <b>Scenario 2: Eliminar tarjeta por error. </b> 
            <br>
            <b>Dado que </b> el usuario seleccione una tarjeta registrada
            <br>
            <b>Cuando </b> el usuario presione el botón de eliminar y rechace en el mensaje de verificación
            <br>
            <b>Entonces</b> volverá al apartado de mis tarjetas.
            </td>            
        </tr>
        <tr>
            <td colspan=1 align="center">Prioridad</td>
            <td colspan=3 align="center">Alta</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Puntos de Historia</td>
            <td colspan=3 align="center">5 puntos</td>
        </tr>
    </tbody>
</table>

<table  border="2" cellpadding="1" bordercolor="#3253dd">
    <tbody>
        <tr>
            <td rowspan=1 align="center">HU:</td>
            <td rowspan=1 align="center">183309402</td>
            <td align="center">Título:</td>
            <td align="center">Agregar Cuenta Bancaria</td>
        </tr>
        <tr>
            <td rowspan=1 align="center">Usuario:</td>
            <td rowspan=1 align="center">Taller</td>
            <td align="center">Sprint:</td>
            <td align="center">2</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Descripción</td>
            <td colspan=3 align="justify">Como usuario Taller quiero poder agregar una cuenta bancaria para poder recibir los pagos
        </tr>
        <tr>
            <td colspan=1 align="center">Criterios de Aceptación</td>
            <td colspan=3 align="justify"> <b>Scenario 1: Cuenta correcta.</b> 
            <br>
            <b>Dado que </b> el usuario taller seleccione “Agregar cuenta” en la sección de “Mis cuentas” y llene los campos correctamente.
            <br>
            <b>Cuando </b> el usuario presione el botón de “Añadir”
            <br>
            <b>Entonces</b> aparecerá un mensaje confirmando la agregación de la cuenta.
            <br><br>
            <b>Scenario 2: Cuenta incorrecta. </b> 
            <br>
            <b>Dado que </b> el usuario taller seleccione “Agregar cuenta” en la sección de “Mis cuentas” y llene los campos incorrectamente.
            <br>
            <b>Cuando </b> el usuario presione el botón de “Añadir”
            <br>
            <b>Entonces</b> aparecerá un mensaje indicando un error en alguno de los campos llenados.
            </td>
        </tr>
        <tr>
            <td colspan=1 align="center">Prioridad</td>
            <td colspan=3 align="center">Alta</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Puntos de Historia</td>
            <td colspan=3 align="center">5 puntos</td>
        </tr>
    </tbody>
</table>

<table  border="2" cellpadding="1" bordercolor="#3253dd">
    <tbody>
        <tr>
            <td rowspan=1 align="center">HU:</td>
            <td rowspan=1 align="center">183309403</td>
            <td align="center">Título:</td>
            <td align="center">Eliminar Cuenta Bancaria</td>
        </tr>
        <tr>
            <td rowspan=1 align="center">Usuario:</td>
            <td rowspan=1 align="center">Taller</td>
            <td align="center">Sprint:</td>
            <td align="center">2</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Descripción</td>
            <td colspan=3 align="justify">Como usuario Taller quiero poder eliminar una cuenta bancaria.
        </tr>
        <tr>
            <td colspan=1 align="center">Criterios de Aceptación</td>
            <td colspan=3 align="justify"> <b>Scenario 1: Eliminar Cuenta adrede.</b> 
            <br>
            <b>Dado que </b> el usuario taller seleccione esté en la sección de “Mis cuentas” y seleccione una cuenta para eliminarla.
            <br>
            <b>Cuando </b> el usuario presione el botón de “Eliminar” y confirme su operación.
            <br>
            <b>Entonces</b> aparecerá un mensaje confirmando la eliminación de la cuenta.
            <br><br>
            <b>Scenario 2: Eliminar Cuenta por error. </b> 
            <br>
            <b>Dado que </b> el usuario taller seleccione esté en la sección de “Mis cuentas” y seleccione una cuenta para eliminarla.
            <br>
            <b>Cuando </b> el usuario presione el botón de “Eliminar” y rechace su operación.
            <br>
            <b>Entonces</b> se retornará a la sección de “Mis cuentas”.
            </td>    
        </tr>
        <tr>
            <td colspan=1 align="center">Prioridad</td>
            <td colspan=3 align="center">Alta</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Puntos de Historia</td>
            <td colspan=3 align="center">5 puntos</td>
        </tr>
    </tbody>
</table>

<table  border="2" cellpadding="1" bordercolor="#3253dd">
    <tbody>
        <tr>
            <td rowspan=1 align="center">HU:</td>
            <td rowspan=1 align="center">183309404</td>
            <td align="center">Título:</td>
            <td align="center">Ingresar costo de mueble</td>
        </tr>
        <tr>
            <td rowspan=1 align="center">Usuario:</td>
            <td rowspan=1 align="center">Taller</td>
            <td align="center">Sprint:</td>
            <td align="center">2</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Descripción</td>
            <td colspan=3 align="justify">Como usuario Taller quiero poder ingresar el precio que cobraré por un mueble.
        </tr>
        <tr>
            <td colspan=1 align="center">Criterios de Aceptación</td>
            <td colspan=3 align="justify"> <b>Scenario 1: Ingresar un monto correcto.</b> 
            <br>
            <b>Dado que </b> el usuario taller seleccione un mueble a cotizar.
            <br>
            <b>Cuando </b> el usuario presione el botón de “Cotizar” e ingrese un monto de 5 cifras como máximo.
            <br>
            <b>Entonces</b> aparecerá un mensaje confirmando el registro de la cotización.
            <br><br>
            <b>Scenario 2: Ingresar un monto incorrecto. </b> 
            <br>
            <b>Dado que </b> el usuario taller seleccione un mueble a cotizar.
            <br>
            <b>Cuando </b> el usuario presione el botón de “Cotizar” e ingrese un monto superando el máximo de cifras permitido.
            <br>
            <b>Entonces</b> aparecerá un mensaje indicando un error en el monto registrado en la cotización.
            </td>    
        </tr>
        <tr>
            <td colspan=1 align="center">Prioridad</td>
            <td colspan=3 align="center">Alta</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Puntos de Historia</td>
            <td colspan=3 align="center">5 puntos</td>
        </tr>
    </tbody>
</table>

<table  border="2" cellpadding="1" bordercolor="#3253dd">
    <tbody>
        <tr>
            <td rowspan=1 align="center">HU:</td>
            <td rowspan=1 align="center">183309405</td>
            <td align="center">Título:</td>
            <td align="center">Filtrar pedidos pendientes.</td>
        </tr>
        <tr>
            <td rowspan=1 align="center">Usuario:</td>
            <td rowspan=1 align="center">Taller</td>
            <td align="center">Sprint:</td>
            <td align="center">2</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Descripción</td>
            <td colspan=3 align="justify">Como usuario Taller quiero poder filtrar según fecha de entrega, monto y nombre de cliente los pedidos que tengo pendientes.
        </tr>
        <tr>
            <td colspan=1 align="center">Criterios de Aceptación</td>
            <td colspan=3 align="justify"> <b>Scenario 1: Existen pedidos pendientes.</b> 
            <br>
            <b>Dado que </b> el usuario taller esté en la sección de “Pedidos Pendientes”.
            <br>
            <b>Cuando </b> seleccione un filtro de los existentes.
            <br>
            <b>Entonces</b> aparecerán los/el registro(s) que cumpla con el filtro seleccionado.
            <br><br>
            <b>Scenario 2: No existen pedidos pendientes. </b> 
            <br>
            <b>Dado que </b> el usuario taller esté en la sección de “Pedidos Pendientes”.
            <br>
            <b>Cuando </b> seleccione un filtro de los existentes.
            <br>
            <b>Entonces</b> no aparecerán los/el registro(s) debido a que no existen.
            </td>    
        </tr>
        <tr>
            <td colspan=1 align="center">Prioridad</td>
            <td colspan=3 align="center">Media</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Puntos de Historia</td>
            <td colspan=3 align="center">3 puntos</td>
        </tr>
    </tbody>
</table>

<table  border="2" cellpadding="1" bordercolor="#3253dd">
    <tbody>
        <tr>
            <td rowspan=1 align="center">HU:</td>
            <td rowspan=1 align="center">183309406</td>
            <td align="center">Título:</td>
            <td align="center">Visualizar historial de pedidos completados.</td>
        </tr>
        <tr>
            <td rowspan=1 align="center">Usuario:</td>
            <td rowspan=1 align="center">Taller</td>
            <td align="center">Sprint:</td>
            <td align="center">2</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Descripción</td>
            <td colspan=3 align="justify">Como usuario Taller quiero poder visualizar el historial de pedidos que he completado.
        </tr>
        <tr>
            <td colspan=1 align="center">Criterios de Aceptación</td>
            <td colspan=3 align="justify"> <b>Scenario 1: Existen pedidos completados.</b> 
            <br>
            <b>Dado que </b> el usuario taller esté en la sección de “Inicio”.
            <br>
            <b>Cuando </b> el usuario seleccione el apartado de “Pedidos Completados”.
            <br>
            <b>Entonces</b> aparecerán los/el registro(s) que el usuario taller haya realizado.
            <br><br>
            <b>Scenario 2: No existen pedidos completados. </b> 
            <br>
            <b>Dado que </b> el usuario taller esté en la sección de “Inicio”.
            <br>
            <b>Cuando </b> el usuario seleccione el apartado de “Pedidos Completados”.
            <br>
            <b>Entonces</b> no aparecerán los/el registro(s) que el usuario taller haya realizado debido a que no existen tales registros.
            </td>    
        </tr>
        <tr>
            <td colspan=1 align="center">Prioridad</td>
            <td colspan=3 align="center">Media</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Puntos de Historia</td>
            <td colspan=3 align="center">3 puntos</td>
        </tr>
    </tbody>
</table>

<table  border="2" cellpadding="1" bordercolor="#3253dd">
    <tbody>
        <tr>
            <td rowspan=1 align="center">HU:</td>
            <td rowspan=1 align="center">183309407</td>
            <td align="center">Título:</td>
            <td align="center">Filtrar historial de pedidos completados.</td>
        </tr>
        <tr>
            <td rowspan=1 align="center">Usuario:</td>
            <td rowspan=1 align="center">Taller</td>
            <td align="center">Sprint:</td>
            <td align="center">2</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Descripción</td>
            <td colspan=3 align="justify">Como usuario Taller quiero poder filtrar el historial de pedidos que he completado.
        </tr>
        <tr>
            <td colspan=1 align="center">Criterios de Aceptación</td>
            <td colspan=3 align="justify"> <b>Scenario 1: Existen pedidos completados.</b> 
            <br>
            <b>Dado que </b> el usuario taller esté en la sección de “Inicio”.
            <br>
            <b>Cuando </b> el usuario seleccione el apartado de “Pedidos Completados” y seleccione alguno de los filtros existentes.
            <br>
            <b>Entonces</b> aparecerán los/el registro(s) filtrados que el usuario taller haya realizado.
            <br><br>
            <b>Scenario 2: No existen pedidos completados. </b> 
            <br>
            <b>Dado que </b> el usuario taller esté en la sección de “Inicio”.
            <br>
            <b>Cuando </b> el usuario seleccione el apartado de “Pedidos Completados” y seleccione alguno de los filtros existentes
            <br>
            <b>Entonces</b> no aparecerán los/el registro(s) que el usuario taller haya realizado debido a que no existen registros completados.
            </td>    
        </tr>
        <tr>
            <td colspan=1 align="center">Prioridad</td>
            <td colspan=3 align="center">Media</td>
        </tr>
        <tr>
            <td colspan=1 align="center">Puntos de Historia</td>
            <td colspan=3 align="center">3 puntos</td>
        </tr>
    </tbody>
</table>

#### 3.3. Impact Mapping

+ ![To-Be 2](./img/Impact-map.png)

#### 3.4. Product Backlog

### Capitulo IV: Product  Design

#### 4.1. Style Guidelines

##### 4.1.1 General Style Guidelines

Se usaran botones para la navegacion entre frames. Cada frame tendra un boton principal para volver al menu principal segun si es cliente o experto.  

##### 4.1.2. Web Style Guidelines

Header simple con redireccion al principal.  
Seccion main donde ocurriran todos los eventos principales.  
Barra lateral en el main para seleccionar los datos visualizables.  
Botones crud para actualizar y eliminar. 
#### 4.2. Information Architecture

##### 4.2.1. Organization Systems

Como equipo, hemos optado por implementar una estructura visual organizativa en la presentación de contenido para una organización, conocida como "Jerarquía Visual". Esta elección se basa en el hecho de que una jerarquía visual bien definida dirige la atención de los usuarios hacia los elementos más relevantes en una página o aplicación. La jerarquía visual de la página desempeña un papel crucial en la manera en que se presenta la información del sistema al usuario final, permitiéndoles identificar de manera instantánea dónde deben enfocar su atención al realizar un vistazo rápido a la página o la aplicación.  
Para lograr esta jerarquía visual, utilizamos el color y el contraste como herramientas clave. Esto se debe a que la aplicación selectiva de colores a un diseño tiene el efecto de atraer nuestra atención y determina la importancia que asignamos a distintos elementos en el diseño de un sitio web.  

##### 4.2.2. Labeling Systems

Cuando abordamos el diseño de nuestro sistema de etiquetado, nos sumergimos en el estudio de las etiquetas utilizadas por nuestros competidores, quienes, es importante destacar, son competidores indirectos. Nuestra intención era identificar las etiquetas más relevantes y comunes que se emplean en plataformas similares para simplificar su comprensión. Esto se hizo con el objetivo de evitar cualquier confusión o sobrecarga de información para nuestros clientes, evitando la ambigüedad.  
Nos enfocamos en las necesidades de nuestros consumidores y en consonancia con la propuesta de nuestro producto, buscamos proporcionar una experiencia fácil y amigable. Nuestro objetivo era que la mayoría de las personas pudiera utilizar nuestro producto de manera intuitiva y navegar sin dificultades a través de la plataforma.  

##### 4.2.3. SEO Tags and Meta Tags

En relación al SEO y las Meta Etiquetas, hemos decidido emplear el nombre de nuestra nueva empresa, FurniGo, como la etiqueta de título (Title Tag). Además, en la Meta Etiqueta, proporcionamos una descripción de los beneficios que nuestro servicio puede ofrecer a los usuarios. También utilizamos etiquetas meta de robots para indicar a los motores de búsqueda cómo deben interactuar con esa página en particular.  

##### 4.2.4. Searching Systems

Con el fin de lograr un posicionamiento eficaz de nuestra aplicación web y la página de inicio (Landing Page), planeamos incorporar palabras clave en las diversas secciones de ambas, específicamente en los selectores de tipo H en el código HTML, además de aprovechar la información de metadatos ya existente.  
En la aplicación web, específicamente en la sección de 'Mis Pedidos', estamos considerando implementar una función de búsqueda que permitirá a los usuarios buscar según varios criterios, como la fecha, el nombre del taller o una búsqueda específica. De esta manera, planeamos indexar estos contenidos por separado para optimizar su rendimiento en las búsquedas.  

##### 4.2.5. Navigation Systems

Hemos optado por incorporar un componente denominado 'Breadcrumb' (migas de pan) para facilitar la navegación de los usuarios. Este componente tiene la utilidad de informar al usuario acerca de la ubicación actual de la página que está visitando, así como las páginas previas que exploró para llegar a la pantalla actual.  
En nuestro diseño de 'Breadcrumb', hemos observado que la página actual no se presenta como seleccionable y se diferencia del resto mediante un color distinto.  

#### 4.3. Landing Page UI Design

Nos enfocamos en una UI simple pero bien enfocada a darle toda la informacion al usuario de lo que obtendra en nuestra aplicacion web.  

##### 4.3.1. Landing Page Wireframe

El landing page sera simple y enfocara a ambos miembros (cliente y experto) a encontrar facilmente sus necesidades.  

![Landing Page Wireframe](./img/landing-page-wireframe.png)  
![Landing Page Wireframe](./img/landing-page-wireframe-register.png)  
![Landing Page Wireframe](./img/landing-page-wireframe-login.png)

##### 4.3.2. Landing Page Mock-up

![Landing Page UI Mockup](./img/landing-page-mockup.png)
![Landing Page UI Mockup](./img/landing-page-mockup-register.png)
![Landing Page UI Mockup](./img/landing-page-mockup-login.png)  

#### 4.4. Web Applications UX/UI Design

La aplicacion sera similar entre el cliente y experto pero tendra todo lo necesario para cada uno.  

##### 4.4.1. Web Application Wireframes

El cliente y el experto tendran tres secciones en las que podran:  

1. Cliente: Ver modelos con la lista de expertos que aceptan y sus perfiles, Añadir un nuevo modelo y Ver/Actualizar perfil.  
2. Experto: Explorar modelos, Ver modelos aceptados y Ver/Actualizar perfil.  

**Client wireframes:**

![Client Wireframe](img/app-wireframe-client-edit-order.png)
![Client Wireframe](img/app-wireframe-client-new-order.png)
![Client Wireframe](img/app-wireframe-client-offers.png)
![Client Wireframe](img/app-wireframe-client-order.png)
![Client Wireframe](img/app-wireframe-client-orders.png)
![Client Wireframe](img/app-wireframe-client-profile.png)

**Expert Wireframes:**
![Expert Wireframe](img/app-wireframe-expert-edit-order.png)
![Expert Wireframe](img/app-wireframe-expert-order.png)
![Expert Wireframe](img/app-wireframe-expert-orders.png)
![Expert Wireframe](img/app-wireframe-expert-profile.png)
![Expert Wireframe](img/app-wireframe-expert-search-orders.png)  

##### 4.4.2. Web Application Wireflow Diagrams

Los usuarios tendran a su dispocicion botones para navegar entre las diferentes secciones de la applicacion luego de iniciar sesion o registrarse.

**Expert Wireflow Diagrams:**  
![Expert Wireflow Diagrams](img/wireflow-expert-edit-order.jpg)  
![Expert Wireflow Diagrams](img/wireflow-expert-order.jpg)  
![Expert Wireflow Diagrams](img/wireflow-expert-orders.jpg)  
![Expert Wireflow Diagrams](img/wireflow-expert-profile.jpg)  
![Expert Wireflow Diagrams](img/wireflow-expert-search-order.jpg)  

**Client Wireflow Diagrams:**  
![Client Wireflow Diagrams](img/wireflow-client-edit-order.jpg)  
![Client Wireflow Diagrams](img/wireflow-client-new-order.jpg)  
![Client Wireflow Diagrams](img/wireflow-client-offers.jpg)  
![Client Wireflow Diagrams](img/wireflow-client-order.jpg)  
![Client Wireflow Diagrams](img/wireflow-client-orders.jpg)  
![Client Wireflow Diagrams](img/wireflow-client-profile.jpg)  

##### 4.4.3. Web Application Mock-ups

**Client Mockups:**
![Client Mockup](img/app-mockup-client-edit-order.png)
![Client Mockup](img/app-mockup-client-new-order.png)
![Client Mockup](img/app-mockup-client-offers.png)
![Client Mockup](img/app-mockup-client-order.png)
![Client Mockup](img/app-mockup-client-orders.png)
![Client Mockup](img/app-mockup-client-profile.png)

**Expert Mockups**
![Expert Mockup](img/app-mockup-expert-edit-order.png)
![Expert Mockup](img/app-mockup-expert-order.png)
![Expert Mockup](img/app-mockup-expert-orders.png)
![Expert Mockup](img/app-mockup-expert-profile.png)
![Expert Mockup](img/app-mockup-expert-search-orders.png) 

##### 4.4.4. Web Application User Flow Diagrams

**Expert User Flow Diagrams:**  
![Expert User Flow Diagrams](img/user-flow-expert.jpg)  

**Client User Flow Diagrams:**  
![Client User Flow Diagrams](img/user-flow-client.jpg)  

#### 4.5. Web Applications Prototyping

Enlace del prototyping del landing page: https://upcedupe-my.sharepoint.com/:f:/g/personal/u20161c993_upc_edu_pe/EuEouMKP5ERIrk-SczrfXDgBlhyw_bAB7zvvTZJthA-AJg  
#### 4.6. Domain-Drive Software Architecture

##### 4.6.1 Software Architecture Context Diagram

![Software architecture context diagram](./img/diagram-software-architecture-context.png) 
##### 4.6.2. Software Architecture Container Diagrams

![Software architecture container diagram](./img/diagram-software-architecture-container.png) 
##### 4.6.3. Software Architecture Components Diagrams

![Software architecture component diagram](img/diagram-software-architecture-component-user-profile.png)
![Software architecture component diagram](img/diagram-software-architecture-component-notification-manager.png)  
![Software architecture component diagram](img/diagram-software-architecture-component-order-manager.png)  
![Software architecture component diagram](img/diagram-software-architecture-component-payment.png) 
#### 4.7. Software Object-Oriented Design

##### 4.7.1 Class Diagrams

![Class Diagrams](./img/diagram-class.png) 
##### 4.7.2. Class Dictionary

#### 4.8. Database Design

##### 4.8.1. Database Diagram

![Database diagram](./img/diagram-database-design.png) 
### Capitulo V: Product Implementation, Validation & Deployment

#### 5.1. Software Configuration Management

##### 5.1.1. Software Development Environment

En esta sección se listan las aplicaciones y software, así como tecnologías tales como frameworks y lenguajes, que fueron utilizados para la elaboración de este proyecto.

1. Project management  
   **Github:**  
   Es una plataforma cloud orientada al alojamiento de repositorios de proyectos de desarrollo de software.  
   Enlace: https://www.github.com  
2. Requirements management  
   **Trello:**  
   Es una herramienta de gestión de proyectos. Permite organizar tareas en tableros, tarjetas y lista, asignando atributos diferentes como responsabilidad, fechas límites, título, descripción o multimedia.  
   Enlace: https://www.trello.com/es  
3. Product UX/UI design  
   **UXPressia:**  
   Es una herramienta de diseño orientada a la creación de esquemas y diagramas talles como los gráficos de User Person, Empathy Map y Journey Map.  
   Enlace: http://www.uxpressia.com  
   **Figma:**  
   Herramienta de diseño de interfaces en diferentes niveles de fidelidad, tales como thumbnails, wireframes, mockups y prototypes. Además, facilita la creación de componentes reusables, agilizando el tiempo de desarrollo de dichos componentes en código.  
   Enlace: https://www.figma.com  
4. Software Development  
   **HTML:**  
   Lenguaje de marcado orientado a la definición de la estructura de una página web.  
   **CSS:**  
   Lenguaje de estilos, los cuales determinan la apariencia de los contenidos estructurados por HTML.  
   **JavaScript:**  
   Lenguaje de programación multiparadigma. Dentro del entorno de desarrollo web, otorga funcionalidad a elementos de la página web, permitiendo la interacción con el usuario y comunicación con el servidor.  
5. Software Testing  
   JUnit:  
   Es un framework para pruebas automatizadas de proyectos de software. Permite al equipo probar cada método y determinar si estos funcionan de acuerdo con lo esperado.  
   Enlace: https://www.junit.org/junit5/  

##### 5.1.2. Source Code Management

Para el desarrollo de este proyecto, se creará un repositorio en GitHub, donde se alojará el código fuente de la aplicación. Esta misma plataforma permite además realizar el control de versiones a través de Git. A continuación, se presentan los enlaces de los repositorios usados y la metodología GitFlow, la cual será usada para el control de versiones y la implementación de nuevas características a nuestro software.  
Enlace del repositorio del Landing Page: https://github.com/G4-FurniGo/FurniGo-LandingPage  

#### GitFlow:

Es un flujo de trabajo para el control de versiones y la gestión de ramas en proyectos de desarrollo de software basados en Git. Se basa en mantener una estructura de ramas (branches) constante y predecible, facilitando la colaboración en equipos grandes.  
El modelo de GitFlow consiste en tener dos ramas principales en un repositorio de Git:  

1. Rama principal (Main Branch): Representa la versión estable y destinada a producción del software. Los commits deben producir siempre una versión estable y probada que pueda ser usada por los usuarios finales.

2. Rama de desarrollo (Development branch): Es la rama principal de desarrollo. Aquí se integran cambios y nuevas características de la aplicación que serán probados antes de ser liberados a la rama principal. También debe ser siempre funcional.

Como adicionales a las anteriores, GitFlow considera las siguientes ramas:

3. Rama de característica (Feature branch): Se crea a partir de la rama de desarrollo y se utiliza para introducir nuevas características o mejoras en la aplicación. Únicamente cuando la característica esté completa y la versión sea funcional, se hace el merge con la rama de desarrollo.

4. Rama de publicación (Release branch): Cuando el desarrollo amerita la liberación de una nueva versión estable de la aplicación, se crea esta rama a partir de la rama de desarrollo. No se añaden características en esta rama, sino que se concentran los esfuerzos en las pruebas y correcciones finales antes de realizar la fusión con la rama principal.

5. Rama de corrección de errores (Hotfix branch): Si se encuentra un error crítico que no puede ser postergado en la rama principal, se crea esta rama y realiza la corrección necesaria. Cuando se soluciona dicho problema, se fusiona esta rama en las ramas main y develop.

##### 5.1.3. Source Code Style Guide & Conventions

- Indentación y espaciado:  
  Utilizar una sangria de 2 espacios para la anidación de bloques de código. En el caso de Typescript, separar fragmentos de código con saltos de línea. En el caso de HTML, utilizar saltos de línea para etiquetas semánticas y de bloque. Para etiquetas de línea (in-line), se puede obviar.
- Capitalización:  
  En HTML y CSS, utilizar minúsculas para las etiquetas, atributos y directivas de estilo. En TypeScript, usar PascalCase para propiedades, tipos y métodos y camelCase para nombres de variables. En el caso de clases en HTML y CSS, usar kebab-case.
- Strings:  
  Usar comillas dobles para valores de atributos en HTML y para strings en TypeScript. Mantener la consistencia durante todo el proyecto.
- Codificación:  
  Se usará UTF-8 como formato de todos los archivos de código fuente. Sin embargo, se debe procurar utilizar el subconjunto de caracteres correspondientes a ASCII en la medida de lo posible.  

##### 5.1.4. Software Deployment Configuration

Para el despliegue del landing page, se utilizará GitHub Pages, servicio que nos permite desplegar una página web estática a partir de un repositorio.  
Las herramientas utilizadas para el desarrollo del Landing Page fueron HTML, CSS y TypeScript. El software utilizado fue Git, GitHub, GitHub Pages y GitFlow como metodología de control de versiones.  

#### 5.2 Landing Page, Services & Applications

##### 5.2.1. Sprint 1

###### 5.2.1.1. Sprint Planning 1

| Sprint 1                       | Implementación de funcionalidades y diseño de la Landing Page |
| ------------------------------ | ------------------------------------------------------------- |
| Sprint Planning Background     |                                                               |
| Date                           | 10/09/2023                                                    |
| Time                           | 18:00                                                         |
| Location                       | Reunión realizada mediante Google Meet                        |
| Attendees                      | Cancho Coila, Diego Fabian                                    |
| **Sprint Goal & User Stories** |                                                               |
| Sprint 1 Goal                  | Realizar y desplegar el landing page                          |
| Sprint 1 Velocity              | 20                                                            |
| Sum of Story Points            |                                                               |
###### 5.2.1.2. Sprint Backlog 1

| id  | Title | Id  | Title | Description | Estimations(Hours) | Assigned To | Status(To-do /InProcess/ToReview/Done) |
| --- | ----- | --- | ----- | ----------- | ------------------ | ----------- | -------------------------------------- |
###### 5.2.1.3. Development Evidence for Sprint Review

| Repository          | Branch          | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
| ------------------- | --------------- | --------- | -------------- | ------------------- | ------------------ |
| FurniGo-LandingPage | feature/develop |           | Feature:       | Feature(L. Page):…. | 10/09/2023         |
| FurniGo-LandingPage | feature/develop |           | Feature:       | Feature(L. Page):…. | 10/09/2023         |
| FurniGo-LandingPage | feature/develop |           | Feature:       | Feature(L. Page):…. | 10/09/2023         |
| FurniGo-LandingPage | feature/develop |           | Feature:       | Feature(L. Page):…. | 10/09/2023         |
| FurniGo-LandingPage | feature/develop |           | Feature:       | Feature(L. Page):…. | 10/09/2023         |

###### 5.2.1.4. Testing Suite Evidence for Sprint Review

En esta entrega no se incluyó contenido aplicable a la lógica de negocio, por lo que no se incluye evidencia de pruebas unitarias. 
###### 5.2.1.5. Execution Evidence for Sprint Review

Enlace del landing page en ejecución: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201f479_upc_edu_pe/ETNVvcZmNklMq6_yC1p4xkQBUswDH7Lw6X970T6noiUf5A?e=qoaZ16&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In19 

###### 5.2.1.6. Services Documentation Evidence for Sprint Review

En esta entrega no se requirió el uso de servicios externos al ser el landing page una página estática que no requiere de ellos. 
###### 5.2.1.7. Software Deployment Evidence for Sprint Review

El landing page se desplegó en GitHub Pages, un servicio para el hosting de páginas estáticas. 
Enlace del landing page desplegado en GitHub Pages: https://github.com/G4-FurniGo/FurniGo-LandingPage
###### 5.2.1.8. Team Collaboration Insights during Sprint

Tanto para la elaboración del reporte como para el landing page, se utilizaron repositorios en GitHub y la metodología GitFlow. Para esto, usando Visual Studio Code y la integración con Git, se realizaron commits a las branches correspondientes, y se realizaron pull requests para la revisión de los cambios.
![Evidencia de commits al reporte](./img/sprint-1-commits.png)  
![Evidencia de commits al landing page](./img/sprint-1-commits-landing.png) 

### 5.2.2 Sprint 2:

#### 5.2.2.1 Sprint planning 2

| Sprint 2                       | Implementación de front-end page                                                                              |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------- |
| **Sprint Planning Background** |                                                                                                               |
| Date                           | 16/09/2023, 23/09/2023                                                                                        |
| Time                           | 15:00-16:00, 15:00-17:00                                                                                      |
| Location                       | Reuniones presenciales en Campus UPC San Miguel                                                               |
| Prepared by                    | Diego Cancho Coila                                                                                            |
| Attendees                      | Diego Cancho Coila, Piero Velarde Luyo. Renzo Loli Ruiz, Cristopher Rondón Añaños (Virtual), Luis Isla Quispe |
| **Sprint Goal & User Stories** |                                                                                                               |
| Sprint 2 Goal                  | Realizar y desplegar el front-end webpage                                                                     |
| Sprint 2 Velocity              | 20                                                                                                            |
| Sum of Story Points            | 22                                                                                                            |

#### 5.2.2.2 Sprint Backlog 2
| ID | Title | Description | Estimation | Assigned to | Status |
| --- | --- | --- | --- | --- |--- |
| 183309406 | Visualizar historial de pedidos completados. | Como usuario Taller quiero poder visualizar el historial de pedidos que he completado. | 3 | Renzo Loli Ruiz | Done|
| 183309408 | Ver Lista de Pedidos en Pantalla Principal. | Como cliente, quiero ver una lista de mis pedidos en la pantalla principal de la plataforma para facilitar el acceso y seguimiento de mis pedidos. | 5 | Cristopher Rondon Añaños | Done |
| 183309410 | Ver Detalles de un Pedido Nuevo | Como cliente, quiero ver la información detallada de un nuevo pedido, y si el pedido aún no ha sido aceptado, para tener un registro completo y actualizado de mis pedidos pendientes. | 5 | Diego Cancho Coila | Done |
| 183309411 | Editar Detalles de un Pedido Nuevo | Como cliente, quiero tener la opción de editar la información introducida de mi pedido, como la descripción, fecha, presupuesto y modelo del mueble, para corregir o actualizar la información de manera oportuna si es necesario. | 3 | Piero Velarde Luyo | Done |
| 183309412 | Ver Información de un Pedido Existente | Como cliente quiero ser redirigido a una pantalla que muestre información detallada, incluyendo descripción, fecha, presupuesto y modelo del mueble, para poder acceder fácilmente a los detalles de mis pedidos anteriores. | 3 | Luis Isla Quispe | Done |
|183309414 | Acceder a la Información del Carpintero que Aceptó el Pedido | 	Como cliente, quiero poder acceder a la información del carpintero que aceptó mi pedido, incluyendo detalles sobre proyectos anteriores y experiencia, para conocer más sobre la experiencia y el historial del carpintero que trabaja en mi pedido. | 3 | Renzo Loli Ruiz | Done |

#### 5.2.2.3 Development Evidence for Sprint Review

| Repository | Branch                          | Commit ID | Commit message                                              | Commit message body | Commited on (Date) |
| ---------- | ------------------------------- | --------- | ----------------------------------------------------------- | ------------------- | ------------------ |
| FurniGo    | feature/components              | 0384b97   | code: remove unexistent comoponent importing                | -                   | 29/09/2023         |
| FurniGo    | feature/develop/structure       | 1815f4c   | code: add status tag                                        | -                   | 30/09/2023         |
| FurniGo    | feature/user/data-modify-create | 9eb06f5   | Merge branch 'develop' into feature/user/data-modify-create | -                   | 29/09/2023         |
| FurniGo    | feature/user-tag                | 41a2fea   | User tag                                                    | -                   | 29/09/2023         |
| FurniGo    | feature/navbar                  | a0f55ae   | Merge branch 'develop' into feature-navbar                  | -                   | 29/09/2023         |

#### 5.2.2.4 Testing Suite Evidence for Sprint Review

En esta entrega no se incluyó contenido aplicable a la lógica de negocio, por lo que no se incluye evidencia de pruebas unitarias.

#### 5.2.2.5 Execution Evidence for Sprint Review

Enlace del front-end en ejecución: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201f479_upc_edu_pe/ETNVvcZmNklMq6_yC1p4xkQBUswDH7Lw6X970T6noiUf5A?e=qoaZ16&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In19

#### 5.2.2.6 Services Documentation Evidence for Sprint Review

Para el desarrollo del front-end webpage no se requirió de servicios externos.

#### 5.2.2.7 Software Deployment Evidence for Sprint Review

Para el despliegue de nuestro front-end, utilizamos el servicio de hosting de Google Firebase, el cual aloja el código fuente de nuestro front-end y lo despliega en un servidor web de Google, el cual se puede acceder mediante un enlace.
Enlace del front-end desplegado en Google Firebase: https://furnigo-55d8d.web.app/

#### 5.2.2.8 Team Collaboration Insights during Sprint

Para el desarrollo del presente sprint, se siguió utilizando Git, GitHub y la metodología GitFlow, haciendo uso de ramas para la introducción de nuevas características.
A partir de un repositorio main, se clonó una rama develop para llevar a cabo los desarrollos necesarios en otras sub-ramas feature, las cuales se van integrando a la rama develop. Finalmente, antes del deployment, se crea una rama release, la cual luego se integra tanto a la rama main y la rama develop, siendo la primera la cual se despliega en Google Firebase.

![Evidencia de commits al front-end](./img/sprint2-teamcollaborationinsights.png)  
![Git network](./img/sprint2-gitnetwork.png)  

### 5.2.3 Sprint 3:
#### 5.2.3.1 Sprint planning 3
| Sprint 3                       | Implementación de back-end                                                                              |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------- |
| **Sprint Planning Background** |                                                                                                               |
| Date                           | 13/10/2023                                                                                        |
| Time                           | 11:00-13:00                                                                                      |
| Location                       | Reunión presencial en Campus UPC San Miguel                                                               |
| Prepared by                    | Diego Cancho Coila                                                                                            |
| Attendees                      | Diego Cancho Coila, Piero Velarde Luyo. Renzo Loli Ruiz, Cristopher Rondón Añaños (Virtual) |
| **Sprint Goal & User Stories** |                                                                                                               |
| Sprint 3 Goal                  | Diseñar e implementar backend de la aplicación                                                                      |
| Sprint 2 Velocity              | 20                                                                                                            |
| Sum of Story Points            | 22      
#### 5.2.3.2 Sprint Backlog 3
| ID | Title | Description | Estimation | Assigned to | Status |
| --- | ---- | --- | --- | --- | --- |
| 183309406 | Visualizar historial de pedidos completados. | Como usuario Taller quiero poder visualizar el historial de pedidos que he completado. | 3 | Renzo Loli Ruiz | Done|
| 183309408 | Ver Lista de Pedidos en Pantalla Principal. | Como cliente, quiero ver una lista de mis pedidos en la pantalla principal de la plataforma para facilitar el acceso y seguimiento de mis pedidos. | 5 | Christian Rondon Añaños | Done |
| 183309410 | Ver Detalles de un Pedido Nuevo | Como cliente, quiero ver la información detallada de un nuevo pedido, y si el pedido aún no ha sido aceptado, para tener un registro completo y actualizado de mis pedidos pendientes. | 5 | Diego Cancho Coila | Done |
| 183309411 | Editar Detalles de un Pedido Nuevo | Como cliente, quiero tener la opción de editar la información introducida de mi pedido, como la descripción, fecha, presupuesto y modelo del mueble, para corregir o actualizar la información de manera oportuna si es necesario. | 3 | Piero Velarde Luyo | Done |
| 183309412 | Ver Información de un Pedido Existente | Como cliente quiero ser redirigido a una pantalla que muestre información detallada, incluyendo descripción, fecha, presupuesto y modelo del mueble, para poder acceder fácilmente a los detalles de mis pedidos anteriores. | 3 | Luis Isla Quispe | Done |
|183309414 | Acceder a la Información del Carpintero que Aceptó el Pedido | 	Como cliente, quiero poder acceder a la información del carpintero que aceptó mi pedido, incluyendo detalles sobre proyectos anteriores y experiencia, para conocer más sobre la experiencia y el historial del carpintero que trabaja en mi pedido. | 3 | Renzo Loli Ruiz | Done |

#### 5.2.3.3 Development Evidence for Sprint Review
| Repository | Branch | Commit ID | Commit message | Commit message body | Commited on (Date) |
| --- | --- | --- | --- | --- | --- |
| FurniGo-WebServices | develop | 36deb69 | Code: implement query and command service impl | - | 04/11/2023 |
| FurniGo-WebServices | develop | 1d88047 | Code: add models and services | - | 04/11/2023 |
| FurniGo-FrontEnd | develop | eebd4c5 | code: repair test-server | - | 04/11/2023 |
| FurniGo-ProjectReport | tb2 | 1dc36e4 | Add Sprint 3 | - | 04/11/2023 |
#### 5.2.3.4 Testing Suite Evidence for Sprint Review
Dado el alcance actual del sprint, aún no se incluyeron los tests unitarios correspondientes a la lógica de negocio.
#### 5.2.3.5 Execution Evidence for Sprint Review
Debido al estado actual del proyecto, no se pueden mostrar evidencias de la ejecución de la aplicación.
#### 5.2.3.6 Services Documentation Evidence for Sprint Review
Aún no se requirió el uso de servicios externos.
#### 5.2.3.7 Software Deployment Evidence for Sprint Review
Debido al estado actual del proyecto, no se puede realizar el deployment de la aplicación. Sin embargo, se incluye a continuación el enlace del repositorio de GitHub, donde se puede encontrar el código fuente de la aplicación.  
Enlace del repositorio de GitHub: https://github.com/G4-FurniGo/FurniGo-WebServices
#### 5.2.3.8 Team Collaboration Insights during Sprint
Para el desarrollo de este sprint, se utilizó la metodología GitFlow, haciendo uso de ramas para la introducción de nuevas características. Sin embargo, debido al limitado alcance, no se incluyeron nuevas ramas, sino que se trabajó directamente en la rama develop.

![Evidencia de commits al back-end](./img/sprint3-teamcollaborationinsights.png)

# Conclusiones
## Conclusiones y recomendaciones
- Para una mejor organización del equipo, se recomienda utilizar herramientas de gestión de proyectos como Trello, las cuales permiten organizar las tareas de manera eficiente y asignar responsabilidades a los miembros del equipo.
- Para el desarrollo de la aplicación, se recomienda utilizar un framework de desarrollo web como Angular o React, los cuales permiten una mejor organización del código y una mayor facilidad para el desarrollo de componentes reusables.
- Es necesario un buen manejo de diseño de Base de Datos para evitar problemas de redundancia y normalizar la información.
- Es necesario un buen manejo de la metodología GitFlow para evitar problemas de integración de código y conflictos entre ramas.
- Se recomienda utilizar trabajos bien establecidos los cuales te proporcionen un inicio sólido para el desarrollo de la aplicación.
## Video About The Team

# Bibliografía
- Rodríguez, A. (30 de noviembre de 2020). La industria maderera peruana en tiempos del COVID-19: Efectos y esfuerzos para su recuperación. FORESTS. Recuperado de https://www.forest-trends.org/blog/la-industria-maderera-peruana-en-tiempos-del-covid-19-efectos-y-esfuerzos-para-su-recuperacion/ [Consulta: 1 de mayo de 2022].
- Bampakos, A., & Deeleman, P. (2023). Learning Angular, 4th Edition. [PDF]. https://dl.ebooksworld.ir/books/Learning.Angular.4th.Edition.Aristeidis.Bampakos.Packt.9781803240602.EBooksWorld.ir.pdf [Consulta: 18 de noviembre de 2023].
- Spring Boot documentation. (2023). Disponible en: [https://spring.io/projects/spring-boot]. [Consulta: 20 de noviembre de 2023].
- Green, B., Sanderson, S., & Hevery, M. (2012). Angular: Up & Running. Birmingham, UK: Packt Publishing. [Consulta: 4 de noviembre de 2023].
- Hevery, M., & Green, B. (2012). Angular: A New Framework for Web Application Development. IEEE Software, 29(5), 38-43. [Consulta: 13 de noviembre de 2023].
# Anexos
- Enlace del prototyping del landing page (https://upcedupe-my.sharepoint.com/:f:/g/personal/u20161c993_upc_edu_pe/EuEouMKP5ERIrk-SczrfXDgBlhyw_bAB7zvvTZJthA-AJg)
- Enlace del landing page (https://g4-furnigo.github.io/FurniGo-LandingPage/)
- Enlace del repositorio del Front End en GitHub (https://github.com/G4-FurniGo/FurniGo-FrontEnd)
- Enlace del repositorio del Back End en GitHub (https://github.com/G4-FurniGo/FurniGo-WebServices)
- Enlace del front-end desplegado en Google Firebase (https://furnigo-55d8d.web.app/)
- Enlace al back-end desplegado en Railway (http://bashful-boundary-production.up.railway.app)