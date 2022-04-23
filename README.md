# Proyecto_Integrador.github.io

                                                           
                                                           
                                                           
                                                           UNIVERSIDAD DEL VALLE DE MEXICO



![image](https://user-images.githubusercontent.com/102937041/164844994-c26d2c13-ddb1-4213-b81d-8826c1b801cb.png)



                                                     Tecnologías de Construcción de Servicios Web



                                                      Actividad 9. Proyecto integrador. Etapa 3



                                                        Alumn. Jesús Gabriel Ocampo Bahena



                                                           Profe. Manuel Triana Vega



                                                             MÉXICO, CDMX, 22/04/2022




                                                                 Introducción
El presente trabajo nos dará una introducción de varias partes de lo que es una arquitectura web, como se puede usar para el aprovechamiento de una empresa en la resolución, mejoramiento, crecimiento y evolución. La arquitectura web se enfoca en diseñar y construir aplicaciones que usualmente usamos en la web gracias al protocolo HTPP (Protocolo de transferencia de hipertexto), con el cual se tiene comunicación con el usuario y otras aplicaciones.

En esta primera entrega del proyecto nos enfocaremos en dar una introducción del tema de la arquitectura web basándonos en un negocio, en el cual vamos a buscar cómo se puede agregar valoración a dicha empresa. Se describa a su vez la metodología, características, impacto, etc. De la arquitectura web que se decida usar para darnos una idea de cómo es el procedimiento para implementarla y tener un amplio entendimiento de su capacidad en un ambiente ficticio.

En la siguiente entrega del trabajo profundizaremos más en la creación del servicio web para nuestra empresa Tú Decide, ahora vamos a detallar más características y el proceso de creación del servicio, daremos una especie de maqueta de la arquitectura definiendo varios puntos. Definiremos los datos a usar y que se comunicarán en el servicio web, daremos una explicación de los procesos de extracción y carga de datos en nuestra arquitectura, revisaremos cuales serán nuestros procesos para el almacenamiento y gestión de datos, describiremos la forma de la interface a la cual tendrá accedo el cliente para interactuar con la empresa y, por último, hablaremos de los diferentes mecanismos de seguridad que podemos implementar en el servicio web.

En esta última entrega de proyecto nos enfocaremos en el desarrollo de un servicio web, usando todos los conocimientos adquiridos hasta el momento con las previas entregas del proyecto, desarrollaremos con un lenguaje de programación, en este caso se usará PHP para programar y desarrollar un servicio web muy básico, solo para representar la comunicación entre el cliente y el servidor, dando como resultado una interfaz básica de identificación para el cliente, es decir, identificación del usuario y contraseña.




                                                        Proyecto Integrador Etapa 1

La Etapa 1 del Proyecto integrador se centra en la identificación una situación o problemática en la organización que laboras o alguna de tu interés, que pueda ser atendida a través del establecimiento de un servicio web concreto, para generar una propuesta de intervención viable que agregue valor a la organización.

• Breve descripción de la organización (giro/sector que atiende, posición en el mercado).

La empresa donde se piensa implementar servicios web para dar un empuje a su diversificación y crecimiento, es una empresa dedicada a ofrecer servicios financieros como créditos hipotecarios, créditos para el automóvil, tarjetas de crédito, etc. A un perfil de clientes con poder adquisitivo medio. Esta empresa intenta posicionarse como un medio intermediario entre los clientes y las instituciones bancarias, es decir, como un moderador con la capacidad de ofrecer servicios personalizados y específicos para cada cliente.


![image](https://user-images.githubusercontent.com/102937041/164845029-3511dcc7-d0e5-4a73-93d7-16a9a7712561.png)


• Impacto de los servicios web en la organización.

El impacto que se prever que generaran los servicios web en la empresa, son fundamentales para una empresa que busca crecer e incrementar su alcance en un mundo donde las tecnologías se han vuelto globales y al alcance de todos, con el solo hecho de dar clic se puede acceder a miles de servicios y aplicaciones, lo cual la empresa busca. Los servicios web lograran aumentar la rentabilidad del negocio actualizando los medios con los que cuenta actualmente.

• Descripción de la situación o problema a intervenir a través del establecimiento de un servicio web.

En la empresa Tu decide, se tiene un alcance muy limitado ya que el flujo de la empresa para sus servicios empieza con el cliente buscando opciones de crédito en páginas de internet que a su vez logran encontrar la página web, de ahí el cliente empieza a interactuar con cotizaciones y contacto con el personal de la empresa, cuando se tiene un acuerdo con el cliente, Tu decide se contacta con la institución bancaria y de ahí se hace el proceso adecuado.
Todo este proceso es largo, tardado y hasta cierto punto ineficiente con la rapidez para canalizar y concretar con el servicio solicitado por el cliente. Con los servicios web se pretende mejorar este flujo de atención y contratación de servicios financieros.

• Descripción de la metodología o pasos generales en el desarrollo de un servicio web

Para el desarrollo de una arquitectura web se pueden emplear las metodologías de desarrollo agil las cuales tienen un enfoque en tomar decisiones basado en un desarrollo incremental donde los requisitos y resultados van evolucionando conforme el tiempo. Ejemplos de metodologías agiles:

![image](https://user-images.githubusercontent.com/102937041/164844881-7c6fdb00-42de-4bf0-a30a-41c3af25807b.png)
                                
Resumiendo, los pasos en una metodología en el desarrollo de un servicio web podemos concluir con los siguientes pasos:

Pasos
1. Manejo de proyecto
2. Captura de requerimientos
3. Análisis
4. Diseño
5. Implementación
6. Prueba
7. Desarrollo


• Justificación de la arquitectura a utilizar de acuerdo a los requerimientos de la organización (SOAP, REST o ambas)

En la arquitectura web para la empresa, se usará el formato SOAP (protocolo simple de acceso a objetos), el cual nos da las ventajas de facilitar las comunicaciones entre aplicaciones sin importar el lenguaje y plataformas. SOAP nos permite integrar normas que especiales para la empresa ofreciendo estándares puntuales con la seguridad, atomicidad, uniformidad, asilamiento y la durabilidad, lo cual nos dan certeza en las transacciones de las bases de datos.

![image](https://user-images.githubusercontent.com/102937041/164844920-b70db876-43a1-4012-8cbd-55aa42a45b52.png)


                                                       Proyecto Integrador Etapa 2

• Definición de fuentes de datos a utilizar.

Los datos a emplear serán de gran importancia ya que darán el medio para la comunicación entre el cliente, Tu Decide y las instituciones bancarias. Con esta información se podrán hacer filtros y perfilamiento de los clientes, con lo que a través del servicio web se podrán canalizar las necesidades puntuales a los productos y servicios financieros adecuados.
La información que sé que empleará para la comunicación en el servicio web que se planea implementar, será información del cliente como lo serán datos personales (nombre, edad, domicilio, productos financieros de interés, etc.), e información de los productos y servicios financieros de las instituciones financieras.


![image](https://user-images.githubusercontent.com/102937041/164845083-6cbb3c31-8f5d-44df-bc78-a3d88179d6a8.png)


• Procesos de extracción, transformación y carga de datos

El plano general del proceso de comunicación del servicio web que se planea implementar en de Tú Decide basado SOAP (Simple Object Access Protocol), y con el que se piensa transmitir la información y los datos, es de la siguiente forma:

Cliente: A través del servicio web el cliente solicitará información, es decir generara peticiones (información de productos, requisitos, etc.), a simples rasgos, se podría decir que se genera una llamada.

Esta información se procesará en el protocolo HTTP que es la usada para transferencias de archivos dentro del World Wide Web.

Tú decide (Proveedor):  Se recibe las peticiones y se generan las especificaciones que serán regresadas al cliente, se devuelve las respuestas a las peticiones del cliente. 

Es importante decir que esta comunicación de datos se realiza con la homologación de transferencia de ficheros en lenguaje XML, con el cual se generara el diseño y texto del servicio web de Tú decide.

Servidor Web: Es donde se llevará un resguardo y registro del servicio mensajes, ejecuciones y de las operaciones solicitadas por el cliente y Tú Decide.

![image](https://user-images.githubusercontent.com/102937041/164845180-2b242fb1-fb38-4b97-83f9-44fe5cbf7dbc.png)


• Mecanismos e infraestructura para el almacenamiento y gestión de datos

Para la infraestructura y control de los datos para el proyecto del servicio web en cuestión, nos estaríamos apoyando en varios elementos:
El servidor web: Se tendría un servidor web dentro de la Tú decide, el cuál almacenera todas la acciones, solicitudes y operaciones realizadas entre el usuario de internet y Tú decide, con esto aseguramos que la información se encuentre disponible las 24 horas para los clientes. 

![image](https://user-images.githubusercontent.com/102937041/164845219-d485d707-1173-45c8-b1c6-418bac17e016.png)


Web hosting: Otro elemento sería usar un Web hosting del tipo compartido por el momento para ahorrar en costos del servicio, al igual que un servidor web nos servirá para guardar la información de la página web de Tú decide.

![image](https://user-images.githubusercontent.com/102937041/164845263-3341b54f-59a8-4e90-acb3-4a547c9a2c58.png)

UDDI (Universal Description, Discovery, and Integration): Son el catalogo o directorio donde se almacenan servicios publicados, un tipo de biblioteca virtual de los servicios que proporcionara Tú decide.


• Interfaz de usuario a utilizar

La interface y diseño del servicio web que se planea implementar en Tú Decide, será una interface en la que el cliente tenga acceso a los servicios financieros que sean de su interés, esto será con una interface donde se tenga que dar datos muy sencillos
El cliente dará información de nombre, edad, ingresos aproximados y servicio financiero de su interés.

![image](https://user-images.githubusercontent.com/102937041/164845308-7274696c-d581-4c5b-acf7-00b44569d533.png)

El servicio web se comunicará con el servidor procesando la información para regresar una respuesta.

Le servidor regresa información al cliente donde se mostrará los posibles servicios financieros que están al alcance del cliente y los cuales puede contratar con Tú decide.

![image](https://user-images.githubusercontent.com/102937041/164845346-275fe7d8-8319-41b8-b430-aef7fb49248f.png)


• Mecanismos de seguridad

La claridad de la programación en XML, hace que nuestro servicio web sea blanco fácil de hackers, por lo que las medidas que se tendrán para aumentar la seguridad en el servicio web serán las siguientes:

HTTPS: En determinado caso se piensa usar una conexión para cifrar la información a través del protocolo de seguridad de transferencia, el cual asegura encriptar los datos y autentificar el servidor de Tú decide o el Web hosting.

Autentificación de identidades: En el momento de solicitar o enviar información, se procederá a solicitar a través de un usuario y contraseña al usuario del servicio web.


                                                       Proyecto Integrador Etapa 3
En la elaboración de la programación de los mensajes entre cliente y servidor, me tome la libertar de dejar comentarios en los códigos importantes para describir su función y el proceso que realiza.


![image](https://user-images.githubusercontent.com/102937041/164845497-2389793f-9315-47e1-9917-73cdff84ac3c.png)


![image](https://user-images.githubusercontent.com/102937041/164845514-6ce99adb-5640-41c4-ada2-fc7053905f4a.png)


![image](https://user-images.githubusercontent.com/102937041/164845537-8d0439fe-30b3-446b-824a-1fa319a27ef0.png)


![image](https://user-images.githubusercontent.com/102937041/164845553-5ff5beea-a0ec-412e-9edf-2f2ffc24e74f.png)


![image](https://user-images.githubusercontent.com/102937041/164845580-f96489fa-6a93-4d82-a1e0-28ca21147833.png)


![image](https://user-images.githubusercontent.com/102937041/164845597-aa3a9029-086d-4c9d-8733-803bed7f11e1.png)


![image](https://user-images.githubusercontent.com/102937041/164845611-0896a8b9-079a-4fbf-99eb-8f168074c132.png)


![image](https://user-images.githubusercontent.com/102937041/164845624-8f5ed560-43ec-4061-8259-203476e66919.png)


                                                          Conclusión
Después de la elaboración final del proyecto podemos concluir varios puntos de la importancia de los servicios web y su forma de estructuración. En cuanto a la programación y arquitectura observamos que la estructura básica de un servicio web es fundamental en cuanto a las comunicaciones entre el cliente y el servidor a través de protocolos como XML y HTTP. 

En este trabajo se representó de una forma muy sencilla y concreta esta comunicación, pero con eso no una damos idea de lo complejo que puede ser, ya que cuando se involucran más servicios, bases de datos, etc. Para programar todos estos elementos pueden volverse en traducción de código muy robusto, sin embrago, la funcionalidad que se obtiene es indiscutible en cuanto a tiempo, dinero y recursos. 

Hoy nos encontramos en una era que las tecnologías nos dan la oportunidad de gestionar información de empresas, finanzas personales, estudios, etc. Con la comodidad de hacerlo desde diversos dispositivos, con lo cual aprovechamos las ventajas que nos ofrecen los servicios web como: transparencia, reusabilidad y modularidad.



                                                        Bibliografía

•	Jaramillo, A (2019).  Servicios REST y servicios WEB. Haga clic para ver más opciones Recuperado de https://prezi.com/9myslid1esd-/integracion-de-aplicaciones-a-traves-de-web-services/

•	InformativaC (Productor). (18 de septiembre de 2014). Servicios Web REST con Java [archivo de Video]. Recuperado de https://www.youtube.com/watch?v=8L-xo3cxCYo

•	CSDI (2018).  Composición de servicios web Haga clic para ver más opciones [archivo PDF]. Recuperado de http://www.lsi.upc.edu/~bejar/ecsdi/Teoria/ECSDI06b-ComposicionSOA.pdf







