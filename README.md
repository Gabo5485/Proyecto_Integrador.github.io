# Proyecto_Integrador.github.io
Proyecto Integrador 
                                                            UNIVERSIDAD DEL VALLE DE MEXICO


                   ![image](https://user-images.githubusercontent.com/102937041/164844967-20726712-c3ab-4d66-9f85-a70660d99e15.png)


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


                  ![image](https://user-images.githubusercontent.com/102937041/164844791-06aec084-491b-41f0-aecb-baa8951cfc52.png)


 

• Impacto de los servicios web en la organización.
El impacto que se prever que generaran los servicios web en la empresa, son fundamentales para una empresa que busca crecer e incrementar su alcance en un mundo donde las tecnologías se han vuelto globales y al alcance de todos, con el solo hecho de dar clic se puede acceder a miles de servicios y aplicaciones, lo cual la empresa busca. Los servicios web lograran aumentar la rentabilidad del negocio actualizando los medios con los que cuenta actualmente.

• Descripción de la situación o problema a intervenir a través del establecimiento de un servicio web.
En la empresa Tu decide, se tiene un alcance muy limitado ya que el flujo de la empresa para sus servicios empieza con el cliente buscando opciones de crédito en páginas de internet que a su vez logran encontrar la página web, de ahí el cliente empieza a interactuar con cotizaciones y contacto con el personal de la empresa, 



cuando se tiene un acuerdo con el cliente, Tu decide se contacta con la institución bancaria y de ahí se hace el proceso adecuado.
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
En la arquitectura web para la empresa, se usará el formato SOAP (protocolo simple de acceso a objetos), el cual nos da las ventajas de facilitar las comunicaciones entre aplicaciones sin importar el lenguaje y plataformas. SOAP nos permite integrar 




normas que especiales para la empresa ofreciendo estándares puntuales con la seguridad, atomicidad, uniformidad, asilamiento y la durabilidad, lo cual nos dan certeza en las transacciones de las bases de datos.


              ![image](https://user-images.githubusercontent.com/102937041/164844920-b70db876-43a1-4012-8cbd-55aa42a45b52.png)

















