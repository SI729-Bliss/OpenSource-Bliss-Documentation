<p align="center">
  <img src="resources/UPCLogo.png" alt="UPC" width="150">
</p>

# <center>Universidad Peruana de Ciencias Aplicadas</center>

###  <center>Ingeniería de Software</center>

###  <center>Ciclo 2024-01</center>

## <center>Desarrollo de Aplicaciones Open Source WS53</center>

###  <center>Docente: Juan Antonio Flores Moroco</center>

## <center>Informe del TB1</center>

###  <center>Startup: BeautyServices </center>

###  <center>Producto: Bliss </center>

##  <center>Integrantes

| Nombre |Código de alumno|
|:-------:|:----------:|
|André Arturo Bernaola Pérez|U202114192|
|Diego Ivan Cabrera Buitron|U20211B293|
|Elvia Marcela Rodriguez Villa|U20231C784|
|David Alejandro Rivas Sarango|U20191E831|
|Diego Martin Soriano Medrano|U202114793|

## <center>Agosto 2024</center>

## Registro de versiones del informe

| Versión   | Fecha     | Autor |Descripción de la modificación |
|-----------|-----------|-------|-------------                  |
| 1         | 16/08/24  |       |                               |
|           |           |       |                               |
|           |           |       |                               |

## Project Report Collaboration Insights

URL de la organización del proyecto: [https://github.com/upc-opensource-g-bliss]

**TB1**
|Integrante|Tareas Asignadas|
|-|-|
|André Arturo Bernaola Pérez||
|Diego Ivan Cabrera Buitron||
|Elvia Marcela Rodriguez Villa||
|David Alejandro Rivas Sarango||
|Diego Martin Soriano Medrano||

**TB1 Github**


***

## Contenido
1. [**Capítulo I: Introducción**](#capítulo-i-introducción) <br>
1.1. [***1.1.Startup Profile***](#11-startup-profile) <br>
1.1.1. [1.1.1. Descripción del startup](#111-descripción-del-startup) <br>
1.1.2.[1.1.2. Perfiles de los integrantes del equipo](#112-perfiles-de-los-integrantes-del-equipo) <br>
1.2. [***1.2. Solution Profile***](#12-solution-profile) <br>
1.2.1. [1.2.1.Antecedentes y Problemática](#121-antecedentes-y-problemática) <br>
1.2.2. [1.2.2.Lean UX Process](#122-lean-ux-process) <br>
1.2.2.1. [1.2.2.1.Lean UX Problem Statements](#1221-lean-ux-problem-statements) <br>
1.2.2.2. [1.2.2.2.Lean UX Assumptions](#1222-lean-ux-assumptions) <br>
1.2.2.3. [1.2.2.3.Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements) <br>
1.2.2.4. [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas) <br>
1.3. [***1.3. Segmentos objetivo***](#13-segmentos-objetivo) <br>
2. [**2. Capítulo II: Requirements Elicitation & Analysis**](#capítulo-ii-requirements-elicitation-&-analysis) <br>
2.1. [***Competidores***](#21-competidores) <br>
2.1.1. [Análisis competitivo](#211-análisis-competitivo) <br>
2.1.2. [Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores) <br>
2.2. [***Entrevistas***](#22-entrevistas) <br>
2.2.1. [Diseño de entrevistas](#221-diseño-de-entrevistas) <br>
2.2.2. [Registro de entrevistas](#222-registro-de-entrevistas) <br>
2.2.3. [Análisis de entrevistas](#223-análisis-de-entrevistas) <br>
2.3. [***Needfinding***](#23-needfinding) <br>
2.3.1. [User Personas](#231-user-personas) <br>
2.3.2. [User Task Matrix](#232-user-task-matrix) <br>
2.3.3. [User Journey Mapping](#233-user-journey-mapping) <br>
2.3.4. [Empathy Mapping](#234-empathy-mapping) <br>
2.3.5. [As-is Scenario Mapping](#235-as-is-scenario-mapping) <br>
2.4. [***Ubiquitous Language***](#24-ubiquitous-Language)
3. [**Capítulo III: Requirements Specification**](#capítulo-iii-requirements-specification) <br>
3.1. [***To-Be Scenario Mapping***](#31-to-be-scenario-mapping) <br>
3.2. [***User Stories***](#32-user-stories) <br>
3.3. [***Impact Mapping***](#33-impact-mapping) <br>
3.4. [***Product Backlog***](#34-product-backlog) <br>
4. [**Capítulo IV: Product Design**](#capítulo-iv-product-design) <br>
4.1. [***Style Guidelines***](#41-style-guidelines) <br>
4.1.1. [General Style Guidelines](#411-general-style-guidelines) <br>
4.1.2. [Web Style Guidelines](#412-web-style-guidelines) <br>
4.2. [***Information Architecture***](#42-information-architecture) <br>
4.2.1. [Organization Systems](#421-organization-systems) <br>
4.2.2. [Labeling Systems](#422-labeling-systems) <br>
4.2.3. [SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags) <br>
4.2.4. [Searching Systems](#424-searching-systems) <br>
4.2.5. [Navigation Systems](#425-navigation-systems) <br>
4.3. [***Landing Page UI Design***](#43-landing-page-ui-design) <br>
4.3.1. [Landing Page Wireframe](#431-landing-page-wireframe) <br>
4.3.2. [Landing Page Mock-up](#432-landing-page-mock-up) <br>
4.4. [***Web Applications UX/UI Design***](#44-web-applications-uxui-design) <br>
4.4.1. [Web Applications Wireframes](#441-web-applications-wireframes) <br>
4.4.2. [Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams) <br>
4.4.3. [Web Applications Mock-ups](#443-web-applications-mock-ups) <br>
4.4.4. [Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams) <br>
4.5. [***Web Applications Prototyping***](#45-web-applications-prototyping) <br>
4.6. [***Domain-Driven Software Architecture***](#46-domain-driven-software-architecture) <br>
4.6.1. [Software Architecture Context Diagram](#461-software-architecture-context-diagram) <br>
4.6.2. [Software Architecture Container Diagrams](#462-software-architecture-container-diagrams) <br>
4.6.3. [Software Architecture Components Diagrams](#463-software-architecture-components-diagrams) <br>
4.7. [***Software Object-Oriented Design***](#47-software-object-oriented-design) <br>
4.7.1. [Class Diagrams](#471-class-diagrams) <br>
4.7.2. [Class Dictionary](#472-class-dictionary) <br>
4.8. [***Database Design***](#48-database-design) <br>
4.8.1. [Database Diagram](#481-database-diagram) <br>
5. [**Capítulo V: Product Implementation, Validation & Deployment**](#capítulo-v-product-implementation-validation-&-deployment) <br>
5.1. [***Software Configuration Management***](#51-software-configuration-management) <br>
5.1.1. [Software Development Environment Configuration](#511-software-development-environment-configuration) <br>
5.1.2. [Source Code Management](#512-source-code-management) <br>
5.1.3. [Source Code Style Guide & Conventions](#513-source-code-style-guide-&-conventions) <br>
5.1.4. [Software Deployment Configuration](#514-software-deployment-configuration) <br>
5.2. [***Landing Page, Services & Applications Implementation***](#52-landing-page-services-&-applications-implementation) <br>
5.2.1. [Sprint 1](#sprint-1) <br>
5.2.1.1. [Sprint Planning 1](#5211-sprint-planning-1) <br>
5.2.1.2. [Sprint Backlog 1](#5212-sprint-backlog-1) <br>
5.2.1.3. [Development Evidence for Sprint Review](#5213-development-evidence-for-sprint-review) <br>
5.2.1.4. [Testing Suite Evidence for Sprint Review](#5214-testing-suite-evidence-for-sprint-review) <br>
5.2.1.5. [Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review) <br>
5.2.1.6. [Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review) <br>
5.2.1.7. [Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review) <br>
5.2.1.8. [Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint) <br>
5.3. [***Validation Interviews***](#53-validation-interviews) <br>
5.3.1.[Diseño de Entrevistas](#531-diseño-de-entrevistas) <br>
5.3.2.[Registro de Entrevistas](#532-registro-de-entrevistas) <br>
5.3.3.[Evaluaciones según Heurísticas](#533-evaluaciones-según-heurísticas) <br>
5.4. [***Video About-the-Product***](#54-video-about-the-product) <br>
6. [**Conclusiones**](#conclusiones) <br>
7. [**Bibliografía**](#bibliografía) <br>
8. [**Anexos**](#anexos)

## Students Outcomes

| Criterio específico | Acciones realizadas | Conclusiones |
|---------------------|---------------------|--------------|
|Comunica oralmente con efectividad a diferentes rangos de audiencia.| **André Arturo Bernaola Pérez** <br> **TB1** <br> <br>**Diego Ivan Cabrera Buitron** <br> **TB1** <br> <br>**Elvia Marcela Rodriguez Villa** <br> **TB1** <br> <br>**David Alejandro Rivas Sarango** <br> **TB1** <br> <br>**Diego Martin Soriano Medrano** <br> **TB1** | |
|Comunica por escrito con efectividad a diferentes rangos de audiencia|**André Arturo Bernaola Pérez** <br> **TB1** <br> <br>**Diego Ivan Cabrera Buitron** <br> **TB1** <br> <br>**Elvia Marcela Rodriguez Villa** <br> **TB1** <br> <br>**David Alejandro Rivas Sarango** <br> **TB1** <br> <br>**Diego Martin Soriano Medrano** <br> **TB1** <br> | |

***

## Capítulo I: Introducción

### 1.1. Startup Profile

#### 1.1.1. Descripción del startup

<p style="text-align: justify">
Las empresas de belleza y del cuidado personal están creciendo a un ritmo acelerado, especialmente el sector de tratamientos faciales y dermocosmética, que ha crecido casi 8 veces en los últimos 10 años. Los centros de belleza están diseñados para satisfacer las necesidades de la clase media emergente de 2019, la cual está creciendo. 

La importancia del servicio personalizado al usuario es evidente en este contexto. Los salones de belleza en Perú, que crecen cada vez más, luchan por diferenciarse en un mercado donde la oferta aún está polarizada e informal. Las pequeñas empresas familiares son un buen lugar para empezar, son un poco más moldeables y tienen un estilo de gestión diferente y poco complejo. La principal ventaja que tienen estos establecimientos es que los servicios suelen ser bastante personalizables de acuerdo a las necesidades específicas de cada cliente. Los datos del Inei muestran que el 75.6% de los salones de belleza están dirigidos por mujeres. 

Para aprovechar al máximo la alta competitividad y el constante crecimiento de estos establecimientos, es fundamental elevar la calidad del servicio y prestar atención a la forma en que se gestiona la atención a los clientes, con un mayor énfasis en ofrecer experiencias de usuario personalizadas. No sólo aumentará la satisfacción del cliente, sino que también ayudará a formalizar y "profesionalizar" la industria de la belleza, permitiéndoles establecer relaciones más sólidas y duraderas con sus clientes.
</p>

<br/>

**Misión**: Ofrecer un servicio de belleza y cuidado personal altamente personalizado, centrado en satisfacer las necesidades y expectativas de cada cliente.

**Visión**: Ser los referente en la industria de la belleza y cuidado personal, reconocidos por brindar experiencias personalizadas, contribuyendo al crecimiento y formalizar este sector.

##### Logotipo de la Startup:

<img src="resources/beautyServices.png" alt="BeautyServices" width="150">

##### Logotipo del producto:

<img src="resources/bliss.png" alt="bliss" width="150" style="margin-left: 2px; margin-top: 15px; margin-bottom: 10px"> <br>

#### 1.1.2. Perfiles de los integrantes del equipo

|Integrante |Descripción|
|-----------|-----------|
||**André Arturo Bernaola Pérez**|
|<img src="resources/diego.png" alt="diego">|**Diego Ivan Cabrera Buitron** <br> Mi nombre es **Diego Cabrera**, estoy cursando la carrera de Ingeniería de Software, me considero una persona responsable y perseverante. Al culminar mi carrera quiero especializarme en el sector de la ciberseguridad|
|<img src="resources/rivas-foto.jpg"/>|**David Alejandro Rivas Sarango** <br> Mi nombre es **David Rivas**, actualmente estoy cursando la carrera de Ingeniería de Software en la UPC. Soy una persona honesta y responsable. Me interesa el área de Data Science, por esto estoy siguiendo cursos de capacitacion en SQL y Python.|
|<img src="resources/rodriguez.jpg"/>|**Elvia Marcela Rodríguez Villa** <br> Soy Elvia Rodríguez, actual estudiante universitaria y egresada de Laboratoria. Soy actual embajadora del programa de estudiantes de Microsoft y fui participante de diversos voluntariados y Hackathons cómo Ciencia en tu Comunidad y el Laboratorio de Emprendimientos de SENAJU. Asimismo, soy maestra de inglés y suelo incorporar mis conocimientos de programación de interfaces de usuario en mi labor educativa. |
|<img src="resources/foto.jpg"/>|**Diego Martin Soriano Medrano** <br/> Estudio la carrera de ingeniería de software. Me considero una persona creativa y paciente. Tengo conocimiento en el uso de diferentes herramientas informáticas y lenguajes de programación. que ayudan a realizar distintos tipos de trabajo y a resolver problemas. Parte de mis habilidades blandas es siempre tomar en cuenta la opinión de mis compañeros, lo cual me facilita el poder trabajar en equipo, para agilizar diferentes actividades.|

### 1.2. Solution Profile
#### 1.2.1. Antecedentes y Problemática

##### What (Qué)
###### ¿Cuál es el problema?
Muchas personas pueden encontrar difícil reservar citas de servicios de cuidado y belleza. Asimismo, a muchas Mypes de este rubro se les dificulta encontrar nuevos clientes.
###### ¿Cuál es la relación con la persona en cuestión?
Las personas en cuestión son clientes potenciales que desean acceder a servicios de cuidado y belleza de manera conveniente y confiable; y estilistas o dueños de negocio que desean promocionar su negocio a más personas.

##### When (Cuando)
###### ¿Cuándo sucede el problema?
El problema puede ocurrir cuando los clientes desean reservar citas de servicios de cuidado y belleza, mas no tienen tiempo para buscar proveedores o llamar por teléfono para hacer una reserva.
###### ¿Cuándo utiliza el cliente el producto?
Cuando los clientes deseen buscar, reservar y pagar por servicios de cuidado y belleza, ya sea en casa o en el establecimiento del proveedor, y cuando los proveedores de servicios de cuidado y belleza necesitan hacer uso de una plataforma para promocionar sus servicios.

##### Where (Dónde)
###### ¿A dónde se dirige?
El cliente se dirige a la aplicación para buscar y reservar citas de servicios de cuidado y belleza con proveedores cercanos a su ubicación.
###### ¿Dónde surge el problema?
El problema surge cuando los clientes desean reservar citas de servicios de cuidado y belleza, pero encuentran dificultades para encontrar proveedores confiables o para coordinar horarios que se ajusten a su agenda.
###### ¿Dónde está el cliente cuando usa el producto?
El cliente puede usar el producto desde cualquier lugar donde tenga acceso a Internet, como su hogar, su lugar de trabajo o en movimiento a través de dispositivos móviles.

##### Who (Quién)
###### ¿Quiénes están involucrados?
Los clientes que buscan servicios de cuidado y belleza y los proveedores que ofrecen estos servicios.
###### ¿A quiénes les sucede el problema?
El problema afecta a los clientes que desean acceder a servicios de cuidado y belleza y a los proveedores que buscan aumentar su clientela y gestionar sus citas de manera eficiente.
###### ¿Quién lo utilizará?
El cliente de este producto es quien busque servicios de cuidado y belleza, especialmente mujeres de 20 a 45 años en el sector socioeconómico B-C de Lima, así como Mypes que brinden servicios de cuidado y belleza en Lima.

##### Why (Por qué)
###### ¿Cuál es la causa del problema?
La causa del problema es la falta de una plataforma centralizada que conecte de manera conveniente a los clientes con proveedores de servicios de cuidado y belleza, así como la dificultad para coordinar horarios y encontrar proveedores confiables en el mercado actual.

#### 2H
##### How (Cómo)
###### ¿En qué condiciones nuestros clientes usan el producto?
Nuestros clientes usarán el producto en diversas condiciones, ya sea cuando estén en casa buscando un servicio de cuidado y belleza para una ocasión especial, durante un descanso en el trabajo mientras navegan por opciones de tratamientos, o incluso en movimiento cuando necesiten reservar rápidamente un servicio mientras están fuera de casa.
###### ¿Cómo nos conocieron los compradores? 
Los compradores pueden conocernos a través de diversas fuentes, como recomendaciones de amigos o familiares, publicidad en línea a través de redes sociales, reseñas en línea, o incluso a través de promociones con otros negocios locales
###### ¿Cómo prefieren los consumidores acceder a nuestro contenido?
A través de dispositivos móviles, como teléfonos inteligentes o tabletas. A los consumidores les gustaría poder encontrar fácilmente información sobre los servicios disponibles, ver reseñas y calificaciones de otros usuarios, y realizar reservas en pocos pasos.
###### ¿Que llevó a la persona a llegar a esta situación?
La situación surge de la necesidad de las personas de mantener su apariencia y bienestar mediante servicios de cuidado y belleza, así como de la dificultad para encontrar proveedores confiables y coordinar citas de manera conveniente en el mercado actual. Esto puede deberse a la falta de tiempo o a la falta de opciones cercanas.

##### How much (Cuánto)
###### ¿Cuál es la magnitud del problema?
De acuerdo con la Asociación Peruana de Empresarios de la Belleza (2022), 4 de cada 10 peluquerías se vieron obligadas a cerrar a raíz de la pandemia, y solo un 30% de estas siguen en la formalidad. Esto, en muchos casos, es producto de los elevados costos tanto del alquiler como de la materia prima que los estilistas requieren para realiza su labor.

#### 1.2.2. Lean UX Process
El objetivo de nuestra aplicación es mejorar la gestión de clientes mediante una plataforma que facilite a los clientes la búsqueda y reserva de servicios de belleza y cuidado personal.

##### 1.2.2.1. Lean UX Problem Statements

a) El objetivo de nuestra aplicación es mejorar la gestión de clientes mediante una plataforma que facilite a los clientes la búsqueda y reserva de servicios de belleza y cuidado personal. 
Sin embargo, nos enfrentamos a un desafío significativo: la alta tasa de informalidad en la industria, que genera desconfianza entre los clientes al seleccionar un centro para sus necesidades de belleza. Esta falta de transparencia y garantías sobre la calidad de los servicios ofrecidos crea incertidumbre y afecta negativamente la experiencia del usuario.

¿Cómo podemos mejorar el proceso de selección del cliente para salones, tratamientos y servicios, asegurando un diseño que promueva la confianza y seguridad?

b) Otro objetivo a mencionar es el de proporcionar un sistema eficiente de y transparente para la búsqueda y reserva de servicios, así como establecer canales de comunicación efectivos con los clientes. Nos enfrentamos a otro desafío significativo, los sistemas de gestión de citas para servicios de cuidado y belleza son ineficientes y generan desconfiaza en el usuario final.

¿Cómo podemos implementar estrategias efectivas para fomentar la transparencia y la calidad en los servicios ofrecidos por los centros de belleza, mejorando así la confianza de los usuarios en nuestra plataforma?

c) Reconocemos la importancia de garantizar una experiencia segura y sin preocupaciones para los usuarios que utilizan nuestra plataforma para reservar servicios de belleza. La alta tasa de informalidad en la industria de los centros de belleza crea desafíos adicionales para garantizar la calidad y confiabilidad de los servicios ofrecidos.

¿Cómo podemos establecer procedimientos claros y efectivos para verificar y promover la formalidad y calidad de los centros de belleza asociados, brindando así una experiencia de usuario más segura y confiable en nuestra plataforma?

###### 1.2.2.2. Lean UX Assumptions

Creo que mis clientes necesitan saber cómo y dónde acceder a servicios de manicure, pedicure y tratamientos faciales a domicilio de manera conveniente y segura. 

Estas necesidades se pueden resolver con una aplicación que conecte a clientes con profesionales de belleza verificados, ofreciendo una amplia gama de servicios personalizados y garantizando medidas de seguridad y calidad. 

Mis clientes son personas que buscan comodidad y confiabilidad al reservar servicios de belleza, sin comprometer la calidad y la seguridad. 

El valor N°1 que mi cliente quiere de mi servicio es la facilidad de reserva, la calidad de los servicios y la tranquilidad de tener profesionales confiables en su hogar. 

El cliente también puede adquirir estos beneficios adicionales como descuentos por lealtad, recomendaciones personalizadas y acceso a productos exclusivos. 

Voy a adquirir a la mayoría de mis clientes a través de estrategias de marketing digital, colaboraciones con empresas de belleza y programas de referidos. Haré dinero a través de anuncios por colaboraciones con marcas de belleza, comisiones por reservas y membresías premium. 

Mi competencia principal en el mercado serán aplicaciones similares que ofrecen servicios de belleza a domicilio, salones de belleza locales y plataformas de reserva en línea. Los venceremos debido a nuestra estrategia de enfoque en la seguridad y calidad, personalización de servicios, y programas de fidelización. 

Mi mayor riesgo de producto es que los clientes no confíen en la seguridad de tener desconocidos en sus hogares o que prefieran la experiencia tradicional en un salón de belleza. 

Resolveremos esto a través de la implementación de rigurosos procesos de verificación de profesionales, garantías de seguridad y promoción de la comodidad y conveniencia de nuestros servicios a domicilio.

###### 1.2.2.3. Lean UX Hypothesis Statements

* **Hypothesis Statement 01:**
  
  **Creemos que** ofrecer una amplia gama de servicios de cuidado y belleza a través de nuestra aplicación para usuarios que buscan comodidad y conveniencia ayudará a que estos puedan reservar citas fácilmente y acceder a servicios de calidad.

  **Sabremos** que hemos tenido éxito
  
  **Cuando** se vea un aumento significativo en la cantidad de reservas realizadas a través de nuestra aplicación, así como una mayor retención de clientes satisfechos.

* **Hypothesis Statement 02:**
  
**Creemos que** implementar un sistema de verificación de estilistas calificados y negocios confiables garantizará la calidad de las citas reservadas y ayudará a que nuestros usuarios se sientan seguros al reservar servicios de cuidado y belleza.

**Sabremos** que hemos tenido éxito
  
  **Cuando** se reciban comentarios positivos de los usuarios acerca de la garantía y la buena calidad del servicio recibido, así como cuando veamos un mayor tráfico en la aplicación.

* **Hypothesis Statement 03:**
  
  **Creemos que** establecer colaboraciones estratégicas con salones de belleza, estilistas, marcas de belleza relevantes, y ofrecer programas de referidos atractivos ayudará a que adquiramos clientes de manera efectiva y aumentemos la visibilidad de nuestra aplicación.

**Sabremos** que hemos tenido éxito

  **Cuando** observemos un aumento en la adquisición de clientes durante los períodos de nuestras colaboraciones, así como una mayor interacción de los usuarios con la aplicación a través de programas de referidos.

* * **Hypothesis Statement 04:**
    
**Creemos que** aumentaremos la confianza del usuario y fomentaremos la lealtad a nuestra marca si incorporamos funciones de calificación y reseñas para que los usuarios puedan evaluar la calidad de los servicios recibidos y compartir sus experiencias con otros usuarios.

**Sabremos** que hemos tenido éxito

**Cuando** observemos un aumento significativo en la participación de los usuarios en la función de calificación y reseñas, así como un incremento en la cantidad de reseñas positivas y una mejora general en la percepción de la calidad de los servicios por parte de los usuarios.

###### 1.2.2.4. Lean UX Canvas

  <img src="resources/leanuxcanvas.png" alt="LeanUxCanvas">

Enlace para acceder al Canvas (https://app.mural.co/t/studentprojects6765/m/studentprojects6765/1723924811878/e2acd47a64a2a0139c4cf13feb7c67c6a2e5f92d?sender=u9e84aeace61d1c60b4be6095)

### 1.3. Segmento objetivo

1. Clientas aficionadas al embellecimiento: Este segmento esta compuesto por mujeres en el rango de edad de 20 a 45 años, del sector socioeconómico B-C que residan en Lima.

2. MYPES: Este segmento esta compuesto por dueños de negocios que brindan servicios de cuidado y belleza que funcionan en Lima.

<br/>

## Capítulo II: Requirements Elicitation & Analysis
### 2.1. Competidores

Identificación y descripción 

<br/>

#### 2.1.1. Análisis Competitivo

||Bliss <br><img src='resources/bliss.png' width="110" height="70">|Treatwell <img src='resources/treatwell.png' width="70" height="70">|SimplyBook <img src='resources/simply.png' width="70" height="70">|Booksy <br><img src='resources/boosky.png' width="70" height="70">|
|:-:|:-:|:-:|:-:|:-:|
|**Overview**|Bliss es una plataforma de citas y reservas, enfocadas en la búsqueda, comparación y programación del servicio de negocios de belleza y bienestar|Treatwell es una plataforma de reserva de servicios de belleza y bienestar en Europa.|SimplyBook.me es una plataforma de programación en línea para una variedad de negocios, que facilita la gestión de citas y reservas.|Booksy es una aplicación de reserva de citas enfocada en la industria de belleza y bienestar, que facilita a los usuarios la búsqueda y reserva de servicios de peluquería, estética y cuidado personal.|
|**Ventajas Competitivas**|Ofrece una interfaz intuitiva para su facilidad de uso, disponibilidad las 24 horas del día, gestión centralizada de citas con la finalidad de poder ver y gestionar todas sus citas desde la plataforma.|Ofrece conveniencia alpermitir a los clientes reservar servicios de belleza en línea y acceso a una amplia gama de salones y tratamientos.|Ofrece conveniencia al permitir a los clientes reservar citas en línea las 24 horas del día y acceso a funciones como recordatorios automáticos y pagos en línea.|Ofrece conveniencia al permitir a los clientes encontrar y reservar servicios de belleza en línea las 24 horas del día, así como acceder a información detallada sobre profesionales, servicios y precios.|
|**Mercado Objetivo**|Las micro y pequeñas empresas enfocadas en la industria de belleza y bienestar que estén interesadas en publicar sus servicios en una plataforma online, también las mujeres que busquen gestionar y pedir este servicio.|Usuarios urbanos interesados en servicios de belleza y bienestar en Europa.|Negocios de servicios que requieren programación de citas, como peluquerías, salones de belleza, consultorios médicos, centros de fitness y más. |Usuarios que buscan servicios de belleza y bienestar, así como profesionales de la industria de belleza y cuidado personal.|
|**Estrategias de Marketing**|Fomentar la participación en nuestra plataforma al permitir que los clientes reaccionen y compartan los servicios, al igual que hacer colaboraciones con las empresas de esta industria para un marketing digital.|Marketing digital, colaboraciones con salones de belleza, promociones y programas de fidelización.|Marketing digital, promoción en redes sociales, colaboraciones con negocios afines y programas de referidos.|Marketing digital, promoción en redes sociales, colaboraciones con negocios afines y programas de referidos.|Marketing digital dirigido a usuarios finales y a profesionales, promoción en redes sociales, colaboraciones con salones y eventos de la industria.|
|**Productos & Servicios**|Gestión de citas y reserva a servicios del sector belleza y bienestar, permitir transacciones de pago en línea, interfaz intuitiva para presentar los servicios que ofrece su empresa y sección de comentarios para que los clientes muestres y opiniones y las empresas puedan comunicarse con sus clientes.|Reserva de citas para servicios de peluquería, belleza y bienestar|Plataforma de programación en línea con funciones como calendarios, recordatorios de citas, gestión de personal y pagos en línea.|Aplicación móvil y plataforma en línea que permite la reserva de citas, gestión de agendas y comunicación entre clientes y profesionales.|
|**Precios & Costos**|Las empresas deberán pagar en nuestra plataforma, será un porcentaje bajo por cada reserva o cita pagada, sin embargo, para los que buscan un servicio la aplicación será gratuita.|Varían según el servicio y la ubicación del salón.|Varían según el plan y las características seleccionadas, con opciones de suscripción mensual o anual.|Varían según el plan y las características seleccionadas para los profesionales, mientras que para los usuarios finales, la aplicación es gratuita.|
|**Canales de distribución (WEB y/o Móvil)**|Plataforma en línea y aplicación móvil.|Plataforma en línea y aplicación móvil.|Plataforma en línea y aplicación móvil.|Aplicación móvil disponible en tiendas de aplicaciones y plataforma en línea.|
|**Fortalezas**|Función de filtrado de servicios de belleza según precio, lugar, valorados por la comunidad, entre otros. Interfaz intuitiva para que las empresas puedan mostrar a los usuarios sus servicios. Herramientas para permitir a la comunidad expresarse y recomendar los servicios de su agrado.|Amplia red de salones asociados, conveniencia de reserva en línea, variedad de servicios.|Interfaz intuitiva, amplia personalización, adaptabilidad a diferentes industrias y tipos de negocios.|Especialización en la industria de belleza, interfaz intuitiva, amplia red de profesionales y servicios.|
|**Debilidades**|Dependencia por los comentarios y puntajes de los usuarios, pues sin ellos no podremos filtrar los mejores servicios. Las empresas que paguen por nuestro servicio posiblemente no puedan seguir nuestra curva de aprendizaje para todas las|Dependencia de la disponibilidad de los salones asociados, posibles problemas de calidad del servicio.|Posible curva de aprendizaje para usuarios nuevos, limitaciones en funciones avanzadas en planes más básicos.|Dependencia de la disponibilidad de los profesionales, posibles problemas de calidad del servicio.|
|**Oportunidades**|Existen usuarios interesados en plataformas similares. Muchas empresas pequeñas no usan estos medios, pero están interesados. Colaboraremos con ellos para llegar al público objetivo. Facilidad al expandir nuestros servicios pues es digital. Después de la pandemia las plataformas digitales ganaron confianza.|Expansión a nuevos mercados, introducción de nuevos servicios, mejorar la experiencia del usuario.|Expansión a nuevos mercados, mejora continua de características y funciones, colaboraciones estratégicas con otros servicios.|Expansión a nuevos mercados, introducción de nuevas características y servicios, colaboraciones estratégicas con marcas de belleza.|
|**Amenazas**|Competiremos con aplicaciones ya establecidas. Podría haber problemas a la seguridad de los datos y física de las empresas al cualquier usuario pedir sus servicios. |Competencia de otras plataformas similares, cambios en las preferencias de los consumidores, problemas regulatorios.|Competencia de otras plataformas de programación en línea, cambios en las necesidades y expectativas de los usuarios, problemas de seguridad de datos.|Competencia de otras aplicaciones de reserva de citas, cambios en las preferencias de los usuarios, problemas de calidad del servicio por parte de los profesionales.|

#### 2.1.2. Estrategias y tácticas frente a competidores

**Estrategias:**

* Ampliación de servicios: Ofrecer una amplia gama de servicios de manicura, pedicura y tratamientos faciales, asegurando que cubran las necesidades de los usuarios y proporcionen una experiencia de belleza completa en el hogar.

* Verificación de profesionales: Implementar un riguroso proceso de verificación para los estilistas y negocios asociados, garantizando la calidad y confiabilidad de los servicios ofrecidos a través de la plataforma.

* Enfoque en la comodidad del usuario: Centrarse en la conveniencia y la facilidad de uso de la aplicación para mejorar la experiencia del usuario y fomentar la repetición de negocios.

**Tácticas:**

* Optimización de la interfaz de usuario: Mejorar la navegación y la búsqueda dentro de la aplicación para que los usuarios puedan encontrar fácilmente servicios disponibles que se ajusten a sus horarios y preferencias.

* Sistema de calificación y comentarios: Implementar un sistema de calificación y comentarios para que los usuarios puedan evaluar la calidad de los servicios recibidos, lo que ayudará a construir confianza y transparencia en la plataforma.

* Programación flexible: Permitir a los usuarios seleccionar franjas horarias específicas y preferencias de estilistas al reservar citas, ofreciendo opciones que se adapten a sus
horarios y necesidades.

* Promoción de garantía de calidad: Comunicar claramente la garantía de calidad y verificación de profesionales en la plataforma a través de campañas de marketing y mensajes en la aplicación para generar confianza entre los usuarios.

* Incentivos para usuarios y estilistas: Ofrecer descuentos, promociones o recompensas tanto para los usuarios que realicen reservas como para los estilistas que mantengan altos estándares de servicio y calidad.

* Colaboraciones estratégicas: Establecer asociaciones con marcas de productos de belleza o influencers para aumentar la visibilidad y la credibilidad de la plataforma entre el público objetivo.

### 2.2. Entrevistas
#### 2.2.1. Diseño de entrevistas

### Segmento 1

• ¿Cómo sueles enterarte de nuevos servicios de cuidado y belleza, como tratamientos de belleza, manicura, masajes, extensiones de pestañas, tintes de cabello, depilación, etc.?

• ¿Qué canales de información utilizas con más frecuencia para buscar estos servicios? (Por ejemplo, redes sociales, buscadores en línea, recomendaciones de amigos o familiares, etc.)

• Cuando buscas un servicio específico, como manicura o extensiones de pestañas, ¿qué características te gustaría ver en un catálogo en línea para ayudarte a tomar una decisión informada?

• ¿Has buscado servicios de tintes de cabello, cortes de pelo o peinados en línea? ¿Qué información te gustaría encontrar en una plataforma digital para obtener una cotización precisa?

• ¿Qué aspectos te llaman más la atención al descubrir un nuevo servicio de cuidado y belleza en línea? (Por ejemplo, la calidad de las imágenes, las reseñas de otros usuarios, la descripción detallada de los servicios, etc.)

• ¿Has utilizado alguna vez plataformas digitales específicas para encontrar y reservar servicios de cuidado y belleza? Si es así, ¿qué aspectos te gustaron más de esas plataformas y cuáles crees que podrían mejorar?

• ¿Qué información consideras más importante al buscar y comparar diferentes proveedores de servicios de cuidado y belleza en línea? (Por ejemplo, precios, disponibilidad de citas, ubicación, reseñas de clientes, etc.)

• ¿Qué tan importante es para ti la facilidad y rapidez del proceso de reserva en línea al elegir un proveedor de servicios de cuidado y belleza?

• ¿Has experimentado algún problema o dificultad al reservar servicios de cuidado y belleza en línea en el pasado? ¿Qué aspectos crees que podrían mejorar para hacer este proceso más eficiente?

• ¿Te gustaría tener acceso a promociones especiales o descuentos exclusivos al reservar servicios de cuidado y belleza a través de una plataforma digital? ¿Cómo te gustaría recibir esta información?

• ¿Qué características adicionales te gustaría ver en una plataforma digital para reservar servicios de cuidado y belleza que aún no existan en otras plataformas?

• ¿Qué tan importante es para ti la seguridad y confianza en la plataforma digital al proporcionar información personal y financiera para reservar servicios de cuidado y belleza?


### Segmento 2

• ¿Qué servicios de cuidado y belleza ofrece actualmente en su negocio?

• ¿Cuáles son los servicios más solicitados por los clientes de su negocio?

• ¿Cómo suelen los clientes reservar citas actualmente en su negocio?

• ¿Cuál es su principal desafío o dificultad al gestionar las reservas y citas en su negocio actualmente?

• ¿Qué características o funciones le gustaría ver en una aplicación que les ayude a gestionar las reservas y citas de su negocio y dar a conocerlo a más personas?

• ¿Con qué frecuencia hace uso de las redes sociales o medios de información para poder contactar a sus clientes?

• ¿Qué aspectos considera más importantes al elegir una plataforma para promocionar sus servicios y aceptar reservas? (Por ejemplo, costo, facilidad de uso, popularidad)

• Actualmente, ¿ofrece servicios de cuidado y belleza a domicilio?

• Sí: ¿A qué tipo de clientes ofrece este tipo de servicio? (Por ejemplo, clientes frecuentes o conocidos, cualquier persona que lo/a contacte)

• No: ¿Por qué? (qué necesita o desea para implementar este servicio)

• *Explicación breve de la aplicación* ¿Cómo cree que una aplicación como la que estamos desarrollando podría beneficiar a su negocio y a sus clientes?

• Considerando los posibles beneficios que podría traerle esta aplicación a su negocio, ¿estaría dispuesto/a a pagar una comisión por cada servicio adquirido a través de la aplicación? (de ser posible, especificar tasa máxima en % o, si es comisión fija, monto en soles)

• ¿Estaría dispuesto/a a ofrecer promociones o descuentos exclusivos a través de la aplicación para atraer nuevos clientes o fidelizar a los existentes?

• ¿Qué sugerencias o comentarios adicionales tiene para mejorar la experiencia de reserva de servicios de cuidado y belleza a través de una aplicación?

#### 2.2.2. Registro de entrevistas

***Entrevistas a Clientes***

|Nombre entrevistado| Paco Ramirez Serna|
|:-|:-|
|Edad|21 años|
|Profesión | Estudiante de Economía|
|Departamento|Lima, Perú|
|<img src="resources/entrevista1.png" />|Paco, estudiante de economía, utiliza principalmente Instagram y Facebook para descubrir servicios de cuidado y belleza, valorando las fotos y opiniones en tiempo real. En un catálogo en línea, busca fotografías de alta calidad, testimonios de clientes, precios claros e información sobre la experiencia de los profesionales. Al obtener cotizaciones, prefiere detalles de los servicios, comparativas de precios, imágenes antes y después, y reseñas. Le atraen las imágenes de calidad y reseñas al descubrir nuevos servicios, y ya ha usado plataformas como StyleSeat, aunque cree que podrían ofrecer más detalles sobre los profesionales y su trabajo. Al comparar proveedores, prioriza las reseñas, ubicación, disponibilidad y precios.|
|Duración entrevista: 2:32|URL: [ https://upcedupe-my.sharepoint.com/:v:/g/personal/u20211b293_upc_edu_pe/Eb1SlaolL0hPgcxnmQAkrl8BAtm7CIc5veK7VOxQ5YVp8g?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=BfN0lJ]|

|**Nombre entrevistado**|  **Valeria Fernanda Valle Martinez**|
|:-|:-|
|Edad|19 años|
|Profesión | Estudiante de Psicología|
|Departamento|Lima, Perú|
|<img src="resources/entrevista1ss.JPG" />|Valeria nos menciona que usa anuncios en las redes sociales para buscar salones de belleza, el que más usa es Instagram. Sin embargo, nos cuenta que los anuncios no le permiten conocer la información completa del local como, por ejemplo: la calidad de los productos, precio, ubicación o servicio. Nos contó que no usa aplicaciones para gestionar las citas, pero reconoce el valor de estas, pues le permitirían ver la información de los salones de belleza y los compararlo con otros para buscar el mejor servicio. Mostro interés en nuestro proyecto, y afirmo que la característica más resaltante seria que la mantengan informada de las promociones y datos de los salones de belleza.|
|Duración entrevista: 4:49|URL: [ https://drive.google.com/file/d/1S4OemuKdZ3HVOmgrfeUWXDjV7_4m7pIx/view?usp=sharing]|

|**Nombre entrevistado**|  **Gabriela Suemy Ayllón García-Pacheco**|
|:-|:-|
|Edad|19 años|
|Profesión | Estudiante de Psicología|
|Departamento|Lima, Perú|
|<img src="resources/entrevista1.1.png" />|Gabriela prefiere buscar servicios de belleza a través de recomendaciones de amigos y familiares, aunque también utiliza redes sociales y buscadores en línea. Valora las opiniones de otros clientes, descripciones detalladas de los servicios, fotos del trabajo previo, y la información sobre productos, estilistas, precios y duración de los servicios. Las imágenes de antes y después, la reputación basada en reseñas, y la calidad de los productos utilizados son aspectos clave para ella. Ha probado plataformas digitales para reservar servicios y aprecia la conveniencia de comparar proveedores, destacando la importancia de la calidad, experiencia, precios competitivos, y la facilidad para reservar citas.|
|Duración entrevista: 2:40|URL: [ https://upcedupe-my.sharepoint.com/:v:/g/personal/u20211b293_upc_edu_pe/EXVPmBeyC3NNrXrJxAJTREUBxxM7cyDQIthPcQAShXlw6g?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=jkShwY]|

***Entrevistas a MYPES***

|Nombre entrevistado|  María Margarita Rodríguez Ninaquispe de Cienfuegos|
|:-|:-|
|Edad|55 años|
|Profesión | Estilista|
|Departamento|Lima, Perú|
|<img src="resources/entrevista2ss.JPG" />|María, dueña de un salón de belleza con 30 años de historia, nos cuenta que sus clientes le pueden enviar un mensaje por WhatsApp para reservar una cita, esto beneficia a sus clientes pues no se molestan en esperar su turno mejorando la atención. Menciona que está interesada en promocionar su negocio por redes sociales u otras plataformas, pero teme exponerse a la delincuencia por estos medios. Esto no la detiene de llevar servicio a domicilio con sus clientes habituales. Le contamos de nuestro proyecto y como queremos presentarle una plataforma para que clientes puedan reservar citas, pero, aunque reconozca los beneficios teme que delincuentes creen perfiles falsos y lleguen a su local, por ello incluso usando WhatsApp como medio de comunicación con clientes reconoce que solo acepta cita a los clientes habituales o por recomendación, nunca a extraños. |
|Duración entrevista: 8:54|URL:[https://drive.google.com/file/d/1dBjvYYgw0as8N2YYhyk_MVW3MaRZ0CLA/view?usp=sharing]|

|**Nombre entrevistado**|  **Yaritza Gutiérrez Córdova**|
|Edad|21 años|
|:-|:-|
|Profesión |  Estilista – Estudiante de Ingeniería Civil|
|Departamento|Lima, Perú|
|<img src="resources/entrevista3ss.JPG" />|Yaritza, es una estudiante de la carrera de ingeniería Civil y actualmente tiene un emprendimiento de salón de belleza, ella nos cuenta que su hermana es la que hace sus reservas de las citas para sus clientes, pero tiene el miedo a que su hermana un día pueda confundirse y no pueda ella ir a la cita y que ella si va a hogares a hacer ofrecer sus servicios, pero siempre se demora al escoger los productos con los clientes. Le dimos la información sobre nuestro proyecto y le presentamos todas las funciones de nuestra plataforma con el sistema de reserva de citas, consultas y compra de productos de belleza, ella le sorprendió mucho nuestro proyecto también nos dio una recomendación para poder implementar a la aplicación y esta es que con ayuda de la IA los clientes puedan seleccionar los productos que van a querer que se le usen y puedan ver como un “resultado” con la ia con una foto de estos mismos.|
|Duración entrevista: 5:24|URL: [https://drive.google.com/file/d/1BaFeF2a1AaS3HgkfppCM8Afc9LAMu6gs/view?usp=sharing]|

|**Nombre entrevistado**|  **Matías Munives Santamaría**|
|Edad|21 años|
|:-|:-|
|Profesión |  Estilista – Estudiante de Ingeniería de Sistemas|
|Departamento|Lima, Perú|
|<img src="resources/entrevista2.1.png" />|Matías ofrece servicios básicos como cortes de cabello, manicura, pedicura, masajes y faciales. Comenta que los cortes de cabello y las manicuras son los servicios más solicitados por sus clientes. Actualmente, las citas se gestionan principalmente a través de llamadas y mensajes por WhatsApp, aunque a veces surgen problemas cuando los clientes cancelan a último minuto. Le interesó nuestra propuesta de una aplicación que simplifique la organización de las reservas y atraiga a más clientes, siempre que sea fácil de usar y no demasiado costosa. También mencionó que no ofrecen servicios a domicilio debido a la logística y el personal requerido, pero estarían abiertos a considerar esta opción si se simplificara el proceso. Finalmente, está dispuesto a pagar una comisión por cada servicio adquirido a través de la aplicación, pero con un límite de 50 soles.|
|Duración entrevista: 3:35|URL: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u20211b293_upc_edu_pe/EQDX9KlxHgNNlGByMHxjrF8B_SyjJnRMACdmvK-LQCMOcQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=R8XT2A]|

#### 2.2.3. Análisis de entrevistas</h4></div>

**Segmento 1: Clientes de la industria de belleza y bienestar.**

Basado en las entrevistas concluimos que los clientes buscan en los anuncios de las redes sociales salones de belleza o servicios, por ello les cuesta tener información actualizada e información relevante como marca de sus productos, servicio, entre otros. Por ello una plataforma como la nuestra que le ayude a acceder a esta información actualizada y gestione las visitas les sería muy útil.

**Segmento 2: Empresas pequeñas**

Con respecto a las entrevistas de trabajadores en el sector belleza y bienestar, notamos que sienten que se exponen al peligro cuando atienden a un cliente, siempre está la probabilidad que busquen hacerles daño y robarles. Aun con eso, reconocen que una plataforma que permita la comunicación con clientes para ofrecer un mejor servicio sería de gran ayuda. La característica más importante para estos trabajadores es la seguridad que ofrece la plataforma al agendar una cita.

### 2.3. Needfinding
#### 2.3.1. User Personas

**User Persona 1**

<img src="resources/userpersona1.png" alt="userpersona1"/>



**User Persona 2**

<img src="resources/userpersona2.png" alt="userpersona2"/>



####  2.3.2. User Task Matrix

Para la realizar el User Task Matrix se tomo a los dos sengmetos objetivos ya presenteados que son:

1. Clientas

2. MYPES

**Clientas**
|Task Matrix|Importancia|
|-|-|
|Buscar servicios de belleza|Alta|
|Elegir Servicio|Alta|
|Seleccionar un centro|Media|
|Reservar un servicio|Media|
|Visualizar centros cercanos|Baja|
|Recibir confirmación de reserva|Baja|
|Proporcionar retroalimentación|Baja|

<br/>

**MYPES**
|Task Matrix|Importancia|
|-|-|
|Mantener un catálogo de servicios actualizado|Alta|
|Mantener constante comunicación con los clientes|Alta|
|Gestionar y actualizar información del centro de belleza|Media|
|Confirmar y gestionar reservas por distintos medios|Media|
|Recibir y responder a la retroalimentación de los clientes|Media|
|Crear y administrar promociones|Baja|

<br/>

#### 2.3.3. User Journey Mapping

|Etapa|Descubrimiento|Investigación|Reserva|Experiencia de servicio|Post-servicio|
|-|-|-|-|-|-|
|Feliz|Encuentra la plataforma por recomendación.|Encuentra reseñas positivas sobre servicios ofrecidos.|Recibe confimarción inmediata de la reserva.|Recibe un servicio satisfactorio según sus preferencias.|Recibe un agradecimiento y una invitación para futuros servicios.|
|Neutra|Navega por varias opciones de búsqueda.|Lee descripciones de servicios y precios.|Elije fecha y hora disponible para la cita.|Llega al centro de belleza según lo programado.|Deja comentarios o calificaciones sobre	la experiencia.|
|No Feliz|Selecciona nuestra plataforma debido a buenas críticas.|Filtra resultados según ubicación y servicios deseados.|Proporciona detalles	sobre preferencias del servicio.|No se	siente bienvenido	y cómodo en el centro.|No se siente valorado como cliente y motivado para regresar.|
|Experiencia|Siente curiosidad por explorar opciones.|Busca información detallada y reseñas para tomar decisiones informadas.|Necesita transparencia en los precios y opciones de personalización.|Desea un servicio de alta calidad que cumpla con sus expectativas.|Desea compartir su experiencia y ayudar a otros usuarios.|
|Expectativa|Expectativas de encontrar una solución conveniente.|Desea un centro con buena reputación y servicios	de calidad.|Necesita una herramienta intuitiva para programar citas.|Desea una experiencia satisfactoria y sin contratiempos.|Desea sentirse valorado como cliente y motivado para volver.|



#### 2.3.4. Empathy Mapping

<img src="resources/empathymap1.png">



<img src="resources/empathymap2.png">



#### 2.3.5. As-is Scenario Mapping

**User Persona 1**

|Phases|Búsqueda y Descubrimiento de Servicios|Selección y Reserva de Citas|Experiencia del Servicio|Post-Servicio y Retorno|
|-|-|-|-|-|
|Doing| - Los usuarios buscan servicios de cuidado y belleza. <br> - Solicitud de recomendaciones a amigos, familiares o buscando en directorios en línea. | - Los usuarios llaman por teléfono al salón de belleza seleccionado. <br> - Se consulta por la disponibilidad de citas y se reserva una si es que hay.|-	Los usuarios asisten a su cita programada. <br> - Se recibe el servicio	de cuidado y belleza acordado.|Después del servicio, los usuarios pueden proporcionar comentarios verbales al estilista o al salón de belleza.|
|Thinking|“Me siento limitado por las opciones disponibles  y  me preocupa no poder encontrar un lugar que se ajuste a lo que necesito. No estoy seguro de si podré encontrar un servicio de calidad cerca de mí”.|“Estoy	frustrado porque	tengo	que comunicarme	por teléfono en lugar de reservar  de  manera más sencilla. Además, me preocupa que no haya disponibilidad de citas cuando llame”.|“Me pregunto si el	estilista cumplirá	con mis expectativas. Me	preocupa también que el ambiente	del salón  no  sea cómodo y que el servicio no sea de	buena calidad”.|“El servicio no está mal, pero no cumplió del todo con mis expectativas”.|
|Feeling|Pueden sentirse limitados por las pocas opciones disponibles. Preocupación por la calidad del servicio que recibirán.|Ansiedad al tratar de encontrar un horario conveniente	para confirmar una cita.|Satisfacción si la experiencia fue positiva, pero también decepción si el servicio	no cumplió con sus expectativas.|Desánimo si la experiencia no fue satisfactoria y no se tiene un medio claro de proporcionar comentarios.|

<br>

**User Persona 2**

|Phases|Promoción	y visibilidad|Gestión de citas y comunicación|Experiencia	del Servicio|Retroalimentación y fidelización|
|-|-|-|-|-|
|Doing|-	Publicación anuncios   en   redes sociales  locales  y directorios en línea para promocionar los servicios de belleza.|-	Los clientes se contactan por teléfono con los estilistas para preguntar	sobre	los servicios	y	para programar citas.|-	El estilista realiza los servicios de belleza acordados con los clientes en el salón| - Al  final  del servicio, el estilista solicita retroalimentación verbalmente a los clientes.|
|Thinking|“Me siento frustrado porque	la competencia es alta y es difícil destacar entre otros estilistas o salones. Me preocupa no poder llegar a suficientes clientes potenciales”.|“Me siento estresado porque responder a llamadas telefónicas y mensajes	consume mucho tiempo y a menudo interrumpe mi trabajo. Me preocupa que algunos clientes se vayan a otra parte si no puedo responder	de inmediato".|“Me pregunto si el cliente está satisfecho con el resultado. La verdad es que no entendí bien lo que me explicó”.|“Ojalá este cliente vuelva. Me ha dicho que el servicio estuvo bien, pero no se veía muy convencido”.|
|Feeling|Los estilistas se desmotivan por la falta de visibilidad y se lucha constantemente para atraer nuevos clientes.|Los estilistas abruman por la constante interrupción de las llamadas telefónicas y los mensajes, y se preocupan	por mantener la lealtad de los clientes.|Se siente tensión por cumplir con las expectativas del cliente y mantener una reputación positiva.|Sensación	de inseguridad		y preocupación por la retroalimentación del cliente. <br> Ansiedad	por mantener la lealtad del cliente y su reputación profesional.|

<br>

### 2.4. Ubiquitous Language

|Término (Inglés)|Término (Español)|Definición|
|-|-|-|
| **Client** | Cliente | Persona que utiliza los servicios de cuidado y belleza ofrecidos por el salón. El cliente puede reservar citas, pedir servicios personalizados y proporcionar feedback. |
| **Stylist** | Estilista | Profesional que ofrece servicios de cuidado y belleza dentro del salón. El estilista realiza las tareas según las citas agendadas y es responsable de la satisfacción del cliente. |
| **Appointment** | Cita | Reserva realizada por un cliente para recibir uno o más servicios en una fecha y hora específicas. Las citas pueden ser gestionadas y confirmadas a través del sistema. |
| **Service** | Servicio | Actividad específica ofrecida por el salón, como un corte de cabello, manicura, pedicura, etc. Los servicios son solicitados y recibidos por los clientes durante una cita. |
| **Reservation** | Reservación | Proceso de solicitar y asegurar una cita en el sistema del salón. Una reservación incluye la selección del servicio, estilista, y la fecha/hora preferida. |
| **Feedback** | Retroalimentación | Opinión o evaluación proporcionada por un cliente después de recibir un servicio. El feedback se utiliza para mejorar la calidad del servicio y la satisfacción del cliente. |
| **Promotion** | Promoción | Estrategias y acciones diseñadas para aumentar la visibilidad de los servicios del salón y atraer más clientes. Las promociones pueden incluir descuentos, paquetes especiales, y publicidad. |
| **Availability** | Disponibilidad | El tiempo en que un estilista está libre para realizar servicios y el horario disponible para que un cliente haga una reservación. La disponibilidad se gestiona a través del sistema de citas. |


## Capítulo 3: Requirements Specification
### 3.1. To-be scenario mapping

**User Persona 1**

| Phases | Doing | Thinking | Feeling |
|-|-|-|-|
| **Búsqueda y Descubrimiento de Servicios** | Los usuarios utilizan una plataforma en línea con filtros avanzados para encontrar servicios de cuidado y belleza.<br>La plataforma ofrece recomendaciones personalizadas basadas en preferencias previas y reseñas de otros usuarios. | "Tengo una variedad de opciones de alta calidad y es fácil encontrar el servicio adecuado para mí."| Confianza en que encontrarán un servicio que cumpla con sus expectativas.|
| **Selección y Reserva de Citas** | Los usuarios reservan citas a través de una aplicación o sitio web, con disponibilidad de horarios en tiempo real.<br>Reciben confirmaciones automáticas y recordatorios antes de la cita. | "Es conveniente y rápido reservar una cita en línea, y tengo la seguridad de que mi horario está confirmado." | Tranquilidad al saber que la cita está confirmada y sin preocupaciones de disponibilidad.|
| **Experiencia del Servicio** | Los usuarios asisten a la cita con expectativas claras de lo que recibirán.<br>El servicio se personaliza según las preferencias del cliente previamente indicadas en la plataforma. | "Estoy emocionado por recibir el servicio, ya que sé que se han considerado mis preferencias."| Satisfacción y anticipación positiva por la experiencia.|
| **Post-Servicio y Retorno** | Los usuarios pueden dejar comentarios y reseñas a través de la plataforma, con incentivos para hacerlo.<br>Reciben recomendaciones de seguimiento para mantener el cuidado recibido. | "Me encanta cómo puedo dar mi opinión fácilmente y obtener recomendaciones personalizadas."| Empoderamiento y satisfacción continua con el servicio.|

<br>

**User Persona 2**

| Phases | Doing | Thinking | Feeling |
|-|-|-|-|
| **Promoción y Visibilidad** | Los estilistas utilizan la plataforma para destacar sus servicios con perfiles detallados, incluyendo portafolios y testimonios.<br>Reciben apoyo en marketing digital a través de la plataforma para llegar a más clientes potenciales. | "Tengo herramientas para destacar entre la competencia y atraer a los clientes correctos."| Motivación al ver cómo la visibilidad mejora y los clientes interesados aumentan.|
| **Gestión de Citas y Comunicación** | Las empresas gestionan sus citas través de la plataforma, liberando tiempo para que estos se concentren en su trabajo sin interrupciones.<br>Un sistema de mensajería dentro de la plataforma permite la comunicación directa y eficiente con los clientes. | "Puedo gestionar mi agenda de manera eficiente y dedicar más tiempo a los servicios."| Alivio al no tener que lidiar con interrupciones constantes y satisfacción con una gestión de citas organizada. |
| **Experiencia del Servicio** | Los estilistas proporcionan servicios personalizados basados en la información y preferencias del cliente disponibles en la plataforma.<br>Reciben retroalimentación en tiempo real a través de la aplicación. | "Estoy seguro de que el cliente recibirá exactamente lo que desea."| Confianza en su capacidad para cumplir y superar las expectativas del cliente.|
| **Retroalimentación y Fidelización** | La empresa recibe mediante la plataforma automáticamente una retroalimentación al cliente y comparte los resultados.<br>La plataforma ofrece herramientas para la fidelización de clientes, como descuentos personalizados o recomendaciones de productos. | "Tengo un sistema que me ayuda a mejorar continuamente y a mantener la lealtad de mis clientes."| Seguridad y confianza en la calidad del servicio que ofrecen y en la relación a largo plazo con sus clientes. |

<br>

###  3.2. User Stories

|Epic ID|Título|Descripción|
|-|-|-|
|EP001|Gestión de usuario|Como usuario de la aplicación, quiero poder gestionar mi perfil personal o de empresa para mantener la información actualizada.|
|EP002|Busqueda y selección de servicios|Como cliente, quiero poder buscar y seleccionar servicios de belleza con facilidad, para encontrar la opción que mejor se adapte a mis necesidades.|
|EP003|Reserva y confirmacion de servicios|Como cliente, quiero poder reservar un servicio y recibir una confirmación clara y rápida, para asegurarme de que mi cita esté programada.|
|EP004|Retroalimentación y valoración|Como cliente, quiero poder proporcionar retroalimentación y valoraciones sobre los servicios recibidos, para ayudar a otros clientes y mejorar la calidad de los servicios ofrecidos.|
|EP005|Gestión del catálogo de servicios|Como empresa, deseo poder gestionar mis servicios ofrecidos.|
|EP006|Personalización del servicio|Como cliente, quiero poder adaptar mi solicitud de servicios de belleza y/o cuidado de acuerdo a mis preferencias y a la disposición de la empresa que ofrece el servicio.|
|EP007|Seguridad y Verificación|Como usuario de la aplicación (cliente o empresa), quiero asegurarme de que mi identidad y la de otros usuarios estén verificadas, para garantizar un entorno seguro y confiable dentro de la plataforma. |
|EP008|Comunicación|Como empresa de belleza, quiero comunicarme eficientemente con mis clientes.|
|EP009|Reservas|Como empresa de belleza, quiero gestionar sus reservas para garantizar una experiencia de servicio mas fluida y satisfactoria.|
|EP010|Sistema de pagos| Como usuario de la aplicación (cliente o empresa), quiero gestionar los pagos de manera segura y eficiente, para asegurar transacciones confiables y sin inconvenientes.|
|EP011|Experiencia del Usuario en la Landing Page|Como visitante de la landing page de Bliss, quiero interactuar de manera fluida y obtener toda la información relevante sobre el producto y sus alianzas estratégicas, para tomar una decisión informada.|
|EP012|Gestión de Citas y Reservas|Como usuario, quiero visualizar mis citas y reservas.|

####  3.2.1 User Stories-Usuario

|ID|Título|Descripción|Criterios de Aceptación|EpicID|
|-|-|-|-|-|
| US001 | Creación de cuenta                            | Como  visitante de la aplicación web, quiero poder crear una cuenta en la aplicación proporcionando mi nombre, dirección de correo electrónico y contraseña.|**Escenario 1: Registro completado :** <br>Dado que un nuevo usuario quiere registrarse  <br> Cuando ingresa su nombre, dirección de correo electrónico y contraseña <br>Y presiona el botón de Crear Cuenta  <br> Entonces se envía un correo de verificación a la dirección enviada  <br> **Escenario 2:Error al registrar los datos**  <br> Dado que un nuevo usuario quiere registrarse  <br> Cuando ingresa un nombre, contraseña o un correo electrónico que no cumpla los requisitos establecidos  <br>  Y presiona el botón de Crear Cuenta  <br> Entonces aparece en pantalla un mensaje de error, indicando donde se encuentra el error y pidiendo que se ingrese de nuevo.| EP001: Gestión de usuario |
| US002  | Verificación de correo electrónico           | Como visitante, quiero recibir un correo electrónico de verificación después de registrarme para confirmar mi dirección de correo electrónico| **Escenario 1: Verificación exitosa** <br>Dado que un visitante quiere crear una nueva cuenta  <br> Cuando encuentra el correo que le mandamos donde está el enlace con el código para crear su cuenta  <br> Y ingresa correctamente su código al enlace  <br> Entonces la cuenta nueva esta creada y se le redirige a la página principal de la aplicación.<br>**Escenario 2: Error en la verificación** Dado que un visitante quiere crear una nueva cuenta  <br> Cuando no encuentra el correo que mandamos a la dirección registrada  <br> presiono el botón mandar de nuevo  <br> Y ya pasaron 15 minutos  <br> Entonces aparecerá un mensaje de error indicando que el correo no se pudo verificar y que pedirá ingresar de nuevo el correo electrónico.| EP007: Seguridad y Verificación|
| US003  |Inicio de sesión de usuario| Como usuario registrado, quiero poder iniciar sesión en la aplicación utilizando mi correo electrónico y contraseña.| **Escenario 1: Inicio sesión exitoso** <br> Dado que un usuario quiere ingresar a su cuenta <br> Cuando el usuario proporciona su dirección de correo electrónico y contraseña <br> Y presiona el botón Iniciar Sesión <br> Entonces el usuario es redirigido a la página principal de la aplicación <br> **Escenario 2: Error al iniciar sesión** <br> Dado que un usuario quiere ingresar a su cuenta <br> Cuando el usuario proporciona un correo electrónico o contraseña invalido <br> Y presiona el botón Iniciar Sesión <br> Entonces aparece en pantalla un mensaje de error, indicando donde se encuentra el error y pidiendo que se ingrese de nuevo | EP001: Gestión de usuario|
| US004  | Recomendación por ubicación                  | Como usuario, quiero visualizar como recomendados los servicios de belleza de establecimientos cercanos a mi ubicación actual.| **Escenario 1: Recomendaciones encontradas**<br> Dado que el usuario quiere buscar servicios cercanos<br> Cuando ingrese un filtro por ubicación <br> Entonces aparece en pantalla una lista de servicios ofrecidos por establecimientos cercanos a la ubicación del usuario **Escenario 2: No se encuentran recomendaciones** <br> Dado que el usuario quiere buscar servicios cercanos<br> Cuando ingrese un filtro por ubicación <br> Entonces el sistema muestra un mensaje indicando que no se pudieron obtener recomendaciones basadas en la ubicación y sugiere intentar más tarde o ingresar la ubicación manualmente.| EP002: Busqueda y selección de servicios|
| US005  | Visualización de historial                  | Como usuario, quiero visualizar los servicios de belleza de establecimientos a los que ya he solicitado servicios anteriormente. | **Escenario 1:Recomendaciones encontradas**<br> Dado que el usuario quiere buscar servicios ya solicitados <br> Cuando ingrese a su historial <br>Entonces aparece en pantalla una lista de servicios ofrecidos por establecimientos a los que el usuario ya ha solicitado servicios **Escenario2:No se encuentran recomendaciones**<br> Dado que el usuario quiere buscar servicios ya solicitados <br> Cuando ingrese a su historial <br> Entonces el sistema muestra un mensaje indicando que no se pudieron obtener servicios anteriores y sugiere intentar más tarde manualmente. | EP002: Busqueda y selección de servicios|
| US006  | Visualización de disponibilidad de citas     | Como usuario, quiero poder ver la disponibilidad de citas de los centros de belleza y cuidado para elegir un horario conveniente para mí.| **Escenario 1: Exploración de Calendario** <br>Cuando selecciona un servicio  específico <br> Y selecciono el especialista <br>  Y detallo los requerimientos personalizados del servicio <br> Entonces el sistema muestra un calendario con horarios disponibles y puede seleccionar una fecha y hora conveniente.<br>**Escenario 2: Actualización de Disponibilidad**<br> Cuando un especialista actualiza su horario, el sistema muestra los horarios actualizados por servicio.| EP003: Reserva y Confirmación de Servicios|
| US007  | Notificación de confirmación de reserva      | Como usuario, quiero recibir una notificación de confirmación después de reservar una cita en la aplicación para tener la seguridad de que se ha realizado correctamente.| **Escenario 1: Notificación Automática**<br> Dado que el usuario reserva una cita <br>Cuando pasa 1 minuto <br>Entonces recibe la notificación con detalles de la cita en su dispositivo móvil o correo electrónico. **Escenario 2: Notificación no enviada**<br> Dado que el usuario reserva una cita <br>Cuando pasa 1 minuto <br>Entonces no llega una notificación en ningún dispositivo vinculado. | EP003: Reserva y confirmacion de servicios|
| US008  | Cancelación de cita por parte del usuario    | Como usuario, quiero tener la opción de cancelar una cita reservada en la aplicación en caso de necesidad.| **Escenario 1: Cancelación Confirmada**<br> Dado que el usuario quiere cancelar una cita<br> Cuando selecciona la opción de cancelar la cita<br> Entonces se presenta un mensaje de confirmación para asegurar la cancelación.<br>**Escenario 2: Error de Cancelación** Dado que el usuario quiere cancelar una cita<br> Cuando selecciona la opción de cancelar la cita <br>Entonces el sistema muestra mensaje de erorr al cancelar la cita.| EP003:	Reserva y confirmacion de servicios|
| US009  | Dejar valoración y reseña después de la cita | Como usuario, quiero poder dejar una valoración y reseña sobre el servicio recibido después de completar una cita para ayudar a otros usuarios en su elección.| **Escenario 1: Publicación de Reseña Postcita confirmada** <br> Dado que el usuario ya recibio el servicio <br>Cuando pasan 5 minutos<br> Entonces en la aplicación donde puede escribir una reseña y seleccionar una calificación, confirmando la publicación de la reseña. **Escenario 2: Error en la reseña**  <br> Dado que el usuario ya recibio el servicio <br>Cuando pasan 5 minutos<br> Entonces en la aplicación no puede escribir una reseña.| EP004: Retroalimentación y valoración|
| US010  | Personalización del Servicio                 | Como usuario, quiero poder personalizar el servicio reservado, incluyendo peticiones extras y el tipo de producto.| **Escenario 1: Correcta personalización del Servicio** <br>Dado que el usuario quiere personalizar el servicio<br> Cuando realiza una reserva, puede modificar o incluir algo respecto al servicio (ej. técnicas específicas, productos deseados) y tiene la intencion de confirmar estas opciones.<br> Entonces se establecen los nuevos requisitos de servicio.<br>**Escenario 2: Error en la personalización del servicio**<br>Dado que el usuario quiere personalizar el servicio<br> Cuando realiza una reserva, puede modificar o incluir algo respecto al servicio (ej. técnicas específicas, productos deseados) y tiene la intencion de confirmar estas opciones.<br> Entonces el sistema muestra un mensaje de error. | EP006: Personalización del servicio|
| US011  | Reserva de citas periódicas                 | Como usuario, quiero tener la opcion de reservar citas en conjunto, de tratamientos de cuidado y belleza que requieren de más de 2 citas periódicas.| **Escenario 1: Confirmación Reserva de citas periódicas**<br> Dado que el usuario confirmó un servicio con cuidados que requieren más de 2 citas.<br> Cuando el usuario acepte agendar todo el paquete de citas<br> Entonces las reservas se harán válidas y podrán ser visualizadas en el calendario del usuario.<br>**Escenario 2: Error de reservas periódicas**<br> Dado que el usuario confirmó un servicio con cuidados que requieren más de 2 citas.<br> Cuando el usuario acepte agendar todo el paquete de citas<br> Entonces el sistema mostrará un mensaje de error indicando que no se han podido agendar las citas.| EP003: Reserva y confirmacion de servicios|
| US012  | Pago a través de la App                      | Como usuario, quiero poder pagar el servicio de belleza directamente a la empresa a través de la aplicación.| **Escenario 1: Pago Directo** <br>Dado que el usuario ha reservado correctamente <br> Cuando aparece el siguiente paso del proceso del servicio<br> Entonces puede pagar el servicio a través de la aplicación usando métodos de pago seguros.<br>**Escenario 2: Confirmación de Pago** Cuando realiza el pago, recibe una confirmación de la transacción en su dispositivo móvil o correo electrónico.| EP010: Sistema de pagos|
| US013  | Búsqueda de servicios                        | Como usuario, quiero  buscar un servicio o establecimiento específico mediante un cuadro de texto de busqueda. | **Escenario 1: Busqueda por nombre** <br>Cuando el usuario escribe el nombre del establecimiento o servicio Entonces visualiza resultados coincidentes con su búsqueda.<br>**Escenario 2: Filtro de servicios** Cuando el usuario selecciona los filtros de búsqueda sea por tipo de servicio o por rango de precios Entonces visualiza los servicios coincidentes con el  filtrado.| EP002: Busqueda y selección de servicios|
|US014|Navegacion por la landing page                   | Como visitante, quiero navegar por la landing page de Bliss para obtener mas informacion sobre el producto.|**Escenario 1:Navegación correcta**<br> Dado que soy un visitante en la pagina de inicio de la landing page de Bliss.<br> Cuando hago bajo para obtener mas informacion sobre el producto.<br> Entonces puedo ver las características y ventajas que tiene este.<br> **Escenario 2:Fallo al navegar por la landing** <br>Dado que siendo visitante<br> Cuando quiero bajar a la ultima sección de la landing page.<br> Entonces no me permite bajar a más secciones.|EP011: Experiencia del Usuario en la Landing Page|
|US015|Visualizar alianzas                              |Como visitante, quiero visualizar las alianzas que tiene Bliss para poder confiar en la experiencia que brinda el producto.|**Escenario 1:Visualización de alianzas**<br> Dado que el usuario quiere saber las alianzas estrategicas que posee elproducto.<br> Cuando observe la sección de Alianzas. <br>Entonces el usuario puede confiar más en la excelencia del producto. **Escenario 2: Incorrecta visualización de alianzas**<br> Dado que el usuario quiere saber las alianzas estrategicas que posee elproducto.<br> Cuando observe la sección de Alianzas. <br>Entonces no podra informare bien sobre la confiabilidad del producto. |EP011: Experiencia del Usuario en la Landing Page|
|US016|Crear reserva de citas                           | Como usuario de la aplicacion, quiero poder registrar una nueva reserva Para poder acceder a mi servicio deseado.|**Escenario 1:Correcta reserva de cita**<br>Dado que el usuario quiere reservar una cita <br>Cuando quiere confirmar su intención <br>Entonces el sistema se almacena en la base de datos y el usuario recibe una confirmación de reserva.<br> **Escenario 2:Error de reserva de cita**<br>Dado que el usuario quiere reservar una cita <br>Cuando quiere confirmar su intención <br>Entonces el sistema muestra un mensaje de error indicando que la reserva no pudo ser completada y sugerir intentar nuevamente.|EP003: Reserva y confirmacion de servicios|
|US017|Ver perfil de usuario                            |Como ususario de la aplicacion, Quiero poder ver mi perfil Para acceder a mi informacion personal en mi cuenta.|**Escenario 1: Correcta visualización del perfil del usuario** <br>Dado que el usuario quiere ver su perfil<br> Cuando ingrese a su perfil de usuario<br>  Entonces se muestra la información del usuario<br>**Escenario 2:Error en la visualización del usuario**<br>Dado que el usuario quiere ver su perfil<br> Cuando ingrese a su perfil de usuario<br>  Entonces la información no se carga.|EP001: Gestión de usuario|
|US018|Editar mi perfil de usuario                      |Como usuario de la palicacion, Quiero poder editar mi perfil para mantener actualizada mi cuenta.|**Escenario 1: Correcta actualización del perfil del usuario** <br>Dado que el usuario modificar su informacion personal<br> Cuando realiza las modificaciones necesarias en el perfil de usuario<br> Entonces el sistema actualiza la información editada.<br> **Escenario 2: Error en la visualización del usuario**<br>Dado que el usuario modificar su informacion personal<br> Cuando realiza las modificaciones necesarias en el perfil de usuario<br> Entonces el sistema muestra un mensaje de error al actualizar.|EP001: Gestión de usuario|


#### 3.2.2 User Stories-Empresa Especialista

| **ID** | **Título**                         | **Descripción**                                                                                                                          | **Criterios de Aceptación**                                                                                                                                                                                                                                                                     | **EpicID** |
| ------ | ---------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- |
| US019  | Registro de perfil de empresa | Como empresa, quiero crear un perfil en la aplicación para mostrar información sobre mi negocio y los servicios que ofrezco.|**Escenario 1: Creación exitosa de perfil de empresa:** <br>Dado que la empresa quiere crearse su perfil <br>Cuando llena el formulario de creación de perfil <br>Entonces el sistema mostrará un mensaje de creación correcta de perfil de empresa. <br>**Escenario 2: Error al crear perfil de empresa** <br>Dado que la empresa quiere crear su perfil de empresa. <br>Cuando llena el formulario de creación de perfil<br> Entonces el sistema mostrará un mensaje de error al crear el perfil.| EP001:Gestión de usuario|
| US020  | Edición de perfil de especialista  | Como empresa, quiero editar los perfiles de mis espicialistas  en la aplicación para actualizar la información sobre mi negocio y servicios.| **Escenario 1: Modificar el perfil de empresa satisfactoriamente**<br> Dado que la empresa quiere editar su informacion.<br>  Cuando cambia la información en su formulario<br> Y quiere confirmar la edicion<br> Entonces el sistema muestra un mensaje de correcto guardado<br> Y se guarda en la base de datos.<br>  **Escenario 2: Error al modificar el perfil de empresa**<br> Dado que la empresa quiere editar su informacion<br> Cuando cambia la informacion en su formulario<br> Y quiere confirmar la edicion <br>Entonces el sistema muestra un mensaje incorrecto<br> Y se guarda en la base de datos.| EP001: Gestión de usuario|
| US021  | Gestión de citas                   | Como empresa, quiero gestionar las citas realizadas a través de la aplicación.| **Escenario 1: Visualización de Citas:** <br> Dado que la empresa quiere gestionar las citas<br> Cuando accede a la lista de citas<br> Entonces puede ver detalles de cada cita y gestionar las reservas.<br> **Escenario 2: Error de Citas:** <br> Dado que la empresa quiere gestionar las citas<br> Cuando accede a la lista de citas<br> Entonces no aparecerá ninguna cita.| EP009: Reservas |
|US022|Creacion de servicio| Como empresa, quiero crear un servicio a traves de la aplicacion para que los usuarios de la aplicación lo visualizen.|**Escenario 1:Creacion correcta de servicio** <br> Dado que la empresa quiere crear un servicio<br> Cuando quiera confirmar la eliminacion<br> Entonces el sistema muestra que el servicio ha sido correctamente eliminado.<br> **Escenario 2: Error al crear servicio** <br> Dado que la empresa quiere crear un servicio <br>Cuando quiera confirmar la eliminacion<br> Entonces el sistema mostrará un mensaje de error.| EP005: Gestión del catálogo de servicios|
|US023|Eliminación de servicio| Como empresa, quiero poder eliminar un servicio que yo cree para mantener los servicio relevantes y a mi criterio.|**Escenario 1:Modificacion correcta de servicio** <br> Dado que la empresa quiere crear un servicio <br>Cuando quiera confirmar la eliminacion<br> Entonces el sistema muestra que el servicio ha sido correctamente eliminado.<br> **Escenario 1: Modificacion incorrecta de servicio** <br> Dado que la empresa quiere crear un servicio<br> Cuando quiera confirmar la eliminacion<br> Entonces el sistema muestra un mensaje de error o no guardado de modificaciones.| EP005: Gestión del catálogo de servicios|
| US024  | Actualización de servicios ofrecidos     | Como empresa, quiero actualizar los servicios que ofrezco en la aplicación, incluyendo la actualización de disponibilidad.| **Escenario 1: Actualización de Servicios:**<br>Dado que la empresa quiere modificar un servicio <br>Cuando modifica e intenta guardar los cambios uno de los servicios ofrecidos <br>Entonces los cambios se reflejan en la aplicación.<br>**Escenario 2:** Error de Disponibilidad de Servicios:<br> Dado que la empresa quiere modificar un servicio<br> Cuando modifica e intenta guardar los cambios uno de los servicios ofrecidos <br>Entonces los cambios no se han sido guardados en la aplicación ni en la base de datos. | EP005: Gestión del catálogo de servicios|
| US025  | Suscripción al sistema de pagos    | Como empresa, quiero suscribirme al sistema de pagos en la aplicación para gestionar los pagos de las citas de manera segura.| **Escenario 1: Habilitación de Pagos Seguros:** <br> Dado que la empresa quiere recibir pagos por los servicios en la aplicación <br>Cuando sigue los pasos para completar la suscripción y confirma los reglamentos <br>Entonces está habilitado para recibir pagos de manera segura. <br>**Escenario 2: Error en la habilitación** <br>Dado que la empresa quiere recibir pagos por los servicios en la aplicación<br> Cuando sigue los pasos para completar la suscripción y confirma los reglamentos<br>  Entonces el sistema muestra un mensaje de error al habilitar los pagos.| EP010: Sistema de pagos	|
|US026|Integración con calendario personal|Como usuario, quiero sincronizar mis citas y reservas con mi calendario personal (Google Calendar, Outlook) para mantenerme organizado.| **Escenario 1: Sincronización exitosa**<br> Dado que el usuario desea sincronizar su calendario. <br>Cuando el usuario conecta su cuenta de calendario personal a la aplicación.<br> Entonces las citas y reservas se sincronizan correctamente y se reflejan en el calendario personal del usuario. **Escenario 2: Error en la sincronización** Dado que el usuario desea sincronizar su calendario.<br> Cuando el usuario intenta conectar su cuenta de calendario pero hay un error de conexión o de API. <br>Entonces el sistema muestra un mensaje de error y no se sincronizan las citas.|EP012:Gestión de Citas y Reservas|
|US027|Visualizar objetivo de Bliss|Como visitante de la landing page, quiero ver la sección "Quiénes Somos" con información sobre el equipo, para conocer a las personas detrás de la empresa y su experiencia.|**Escenario 1: Información Correcta**<br> Dado que el visitante está en la sección "Quiénes Somos" <br>Cuando revisa la información del equipo <br>Entonces puede ver perfiles detallados de los miembros del equipo, incluyendo sus nombres, roles y biografías.<br> **Escenario 2: Información Incorrecta**<br> Dado que el visitante está en la sección "Quiénes Somos" <br>Cuando revisa la información del equipo<br> Entonces la información de los perfiles está incompleta o desactualizada.|EP011: Experiencia del Usuario en la Landing Page|
|US028|Visualizar visión del equipo|Como visitante de la landing page, quiero ver la visión de la empresa en la sección "Quiénes Somos" para entender los objetivos y valores fundamentales de la empresa.|**Escenario 1: Visión Correcta** <br>Dado que el visitante está en la sección "Quiénes Somos" <br>Cuando revisa la visión de la empresa <br>Entonces puede leer una declaración clara y bien presentada de la visión y objetivos de la empresa.<br> **Escenario 2: Visión Incorrecta**<br> Dado que el visitante está en la sección "Quiénes Somos" <br>Cuando revisa la visión de la empresa<br> Entonces la declaración de la visión está desactualizada o mal redactada.|EP011: Experiencia del Usuario en la Landing Page|


### 3.3. Impact Mapping
#### 3.4. Product Backlog

| **Orden**| **User Story ID**| **Título**| **Descripción**| **Story Points**|
| - | - | - | - | - |
|1|US014|Navegacion por la landing page|Como visitante, quiero navegar por la landing page de Bliss para obtener mas informacion sobre el producto.|1|
|2|US015|Visualizar alianzas	|Como visitante, quiero visualizar las alianzas que tiene Bliss para poder confiar en la experiencia que brinda el producto.|1|
|3|US027|Visualizar objetivo de Bliss	|Como visitante de la landing page, quiero ver la sección "Quiénes Somos" con información sobre el equipo, para conocer a las personas detrás de la empresa y su experiencia.|1|
|4|US028|Visualizar visión del equipo|Como visitante de la landing page, quiero ver la visión de la empresa en la sección "Quiénes Somos" para entender los objetivos y valores fundamentales de la empresa.|2|
|5|US004|Recomendación por ubicación	|Como usuario, quiero visualizar como recomendados los servicios de belleza de establecimientos cercanos a mi ubicación actual.|3|
|6|US005|Visualización de historial|Como usuario, quiero visualizar los servicios de belleza de establecimientos a los que ya he solicitado servicios anteriormente.|2|
|7|US010|Personalización del Servicio	|Como usuario, quiero poder personalizar el servicio reservado, incluyendo peticiones extras y el tipo de producto.|2|
|8|US013|Búsqueda de servicios|Como usuario, quiero buscar un servicio o establecimiento específico mediante un cuadro de texto de busqueda.|2|
|9|US016|Crear reserva de citas|Como usuario de la aplicacion, quiero poder registrar una nueva reserva Para poder acceder a mi servicio deseado.|2|
|10|US022|Creacion de servicio|Como empresa, quiero crear un servicio a traves de la aplicacion para que los usuarios de la aplicación lo visualizen.|1|
|11|US023|Eliminación de servicio|Como empresa, quiero poder eliminar un servicio que yo cree para mantener los servicio relevantes y a mi criterio.|1|
|12|US024|Actualización de servicios ofrecidos|Como empresa, quiero actualizar los servicios que ofrezco en la aplicación, incluyendo la actualización de disponibilidad.|2|
|13|US006|Visualización de disponibilidad de citas|Como usuario, quiero poder ver la disponibilidad de citas de los centros de belleza y cuidado para elegir un horario conveniente para mí.|1|
|14|US011|Reserva de citas periódicas	|Como usuario, quiero tener la opcion de reservar citas en conjunto, de tratamientos de cuidado y belleza que requieren de más de 2 citas periódicas.|2|
|15|US021|Gestión de citas	|Como empresa, quiero gestionar las citas realizadas a través de la aplicación.|2|
|16|US007|Notificación de confirmación de reserva|Como usuario, quiero recibir una notificación de confirmación después de reservar una cita en la aplicación para tener la seguridad de que se ha realizado correctamente.|1|
|17|US008|Cancelación de cita por parte del usuario|Como usuario, quiero tener la opción de cancelar una cita reservada en la aplicación en caso de necesidad.|2|
|18|US009|Dejar valoración y reseña después de la cita|Como usuario, quiero poder dejar una valoración y reseña sobre el servicio recibido después de completar una cita para ayudar a otros usuarios en su elección.|2|
|19|US017|Ver perfil de usuario|Como ususario de la aplicacion, Quiero poder ver mi perfil Para acceder a mi informacion personal en mi cuenta.|1|
|20|US018|Editar mi perfil de usuario|Como usuario de la palicacion, Quiero poder editar mi perfil para mantener actualizada mi cuenta.|3|
|21|US019|Registro de perfil de empresa|Como empresa, quiero crear un perfil en la aplicación para mostrar información sobre mi negocio y los servicios que ofrezco.|1|
|22|US020|Edición de perfil de especialista|Como empresa, quiero editar los perfiles de mis espicialistas en la aplicación para actualizar la información sobre mi negocio y servicios.|1|
|23|US001|	Creación de cuenta|Como visitante de la aplicación web, quiero poder crear una cuenta en la aplicación proporcionando mi nombre, dirección de correo electrónico y contraseña.|3|
|24|US003|Inicio de sesión de usuario|Como usuario registrado, quiero poder iniciar sesión en la aplicación utilizando mi correo electrónico y contraseña.|3|
|25|US025|Suscripción al sistema de pagos|Como empresa, quiero suscribirme al sistema de pagos en la aplicación para gestionar los pagos de las citas de manera segura.|3|
|26|US012|Pago a través de la App|Como usuario, quiero poder pagar el servicio de belleza directamente a la empresa a través de la aplicación.|2|
|27|US026|Integración con calendario personal|Como usuario, quiero sincronizar mis citas y reservas con mi calendario personal (Google Calendar, Outlook) para mantenerme organizado.|1|
|28|US002|Verificación de correo electrónico	|Como visitante, quiero recibir un correo electrónico de verificación después de registrarme para confirmar mi dirección de correo electrónico|2|


## Capítulo 4: Product Design
<div id='4.1.'><h3> 4.1. Style Guidelines</h3></div>
<div id='4.1.1.'><h4> 4.1.1. General Style Guidelines</h4></div>

El enfoque del estilo del presente producto está enfocade en el uso de la estética glassmorphism ya que está acorde a las tendencias de uso de los últimos años en el sector de la belleza y el cuidad personal.

A continuación mostraremos algunas imágenes de referencia del Style Guidelines document.

<img src="resources/styleg1.png" width="300"><br>
<img src="resources/styleg2.png" width="300"><br>
<img src="resources/styleg3.png" width="300"><br>
<img src="resources/styleg4.png" width="300"><br>
<img src="resources/styleg5.png" width="300"><br>

<br>

#### 4.1.2. Web Style Guidelines
#### 4.1.3. Mobile Style Guidelines
### 4.2. Information Architecture
#### 4.2.1. Organization Systems

El sistema de organización del contenido está basado en categorías específicas como servicios, especialistas, y comentarios. Además, se incluyen promociones y ofertas especiales, lo cual sugiere un esquema de categorización por tópicos y audiencia. La organización visual se presenta en formato jerárquico, mostrando primero los servicios disponibles y luego los detalles específicos de cada uno, como los comentarios de los usuarios.

#### 4.2.2. Labeling Systems

Las etiquetas utilizadas para representar la información son claras y concisas, buscando evitar la confusión. Por ejemplo, se utilizan etiquetas como "Servicios", "Especialistas", "Comentarios" y "Buscar" para guiar a los usuarios. Además, se emplean etiquetas específicas para describir los servicios, como "Limpieza y tratamiento de uñas" y "Diseño en Gel".

#### 4.2.3. SEO Tags and Meta Tags



#### 4.2.4. Searching Systems

El sistema de búsqueda está diseñado para facilitar el acceso rápido a la información. Se proporciona una barra de búsqueda en varias secciones del diseño, permitiendo a los usuarios filtrar los resultados por diferentes criterios, como el tipo de servicio o la ubicación. Además, se ofrecen opciones de búsqueda con filtros específicos y se muestra cómo lucirán los datos después de realizar una búsqueda.

#### 4.2.5. Navigation Systems

El sistema de navegación incluye menús y botones claros que guían a los usuarios a través del contenido de manera efectiva. Los usuarios pueden navegar fácilmente entre las diferentes secciones, como "Servicios", "Comentarios", y "Promociones". La navegación está diseñada para ser intuitiva, permitiendo a los usuarios cumplir sus metas e interactuar de manera satisfactoria con el producto.

#### 4.3.2. Landing Page Mock-up
### 4.4. Web Applications UX/UI Design


#### 4.4.1. Web Applications Wireframes
#### 4.4.2. Web Applications Wireflow Diagrams
#### 4.4.3. Web Applications Mock-ups
#### 4.4.2. Web Applications User Flow Diagrams
### 4.5. Web Applications Prototyping
### 4.6. Domain-Driven Software Architecture
#### 4.6.1. Software Architecture Context Diagram

<img src="resources/c4-model/bliss-context-diagram.png" />

#### 4.6.2. Software Architecture Container Diagrams
#### 4.6.3. Software Architecture Components Diagrams
### 4.7. Software Object-Oriented Design
#### 4.7.1. Class Diagrams
#### 4.7.2. Class Dictionary
### 4.8. Database Design
#### 4.8.1. Database Diagram
## Capítulo 5: Product Implementation, Validation & Deployment
### 5.1. Software Configuration Management
#### 5.1.1.Software Development Environment Configuration

**Project Management**

Para la organizacion del proyecto necesitabamos una planificación en cuanto a tareas asignadas, un punto de reunión y un repositorio donde trabajaramos en conjunto cada avance del proyecto, es por esto que elegimos las siguientes herramientas:

* Centro de organización de trabajo: Github
    
* Planificación de tareas: Trello
    
* Reuniones con el equipo: Google Meet
    
**Requirements Management**

Para realizar las actividades del proyecto necesitábamos designarlas a cada integrante del grupo en caso de revisión o cambios, esta lista de asignaciones fue realizada en Trello:

<table>
    <tbody>
        <tr>
            <td>Link de referencia: </td>
            <td>https://www.trello.com/</td>
        </tr>
    </tbody>
</table>

**Product UX/UI Design**

Para el diseño de los wireframe y mockups, además de un prototipo de Web App se utilizó Figma:

<table>
    <tbody>
        <tr>
            <td>Link de referencia: </td>
            <td>https://www.figma.com/</td>
        </tr>
    </tbody>
</table>

**Software Development**

La herramienta para la implementación del proyecto es IntelliJ de Jetbrains:

<table>
    <tbody>
        <tr>
            <td>Link de referencia: </td>
            <td>https://www.jetbrains.com/idea/</td>
        </tr>
    </tbody>
</table>

HTML: El lenguaje base de etiquetado para aplicaciones web sera empleado en este proyecto.

<table>
    <tbody>
        <tr>
            <td>Link de referencia: </td>
            <td>https://www.w3schools.com/html/html5_syntax.asp</td>
        </tr>
    </tbody>
</table>

CSS: Viene de la mano con HTML, Cascade Styles Sheet maneja el diseño de las aplicaciones web.

<table>
    <tbody>
        <tr>
            <td>Link de referencia: </td>
            <td>https://www.w3schools.com/css/css_intro.asp</td>
        </tr>
    </tbody>
</table>

Lenguaje empleado en la implementación del proyecto es TypeScript:

<table>
    <tbody>
        <tr>
            <td>Link de referencia: </td>
            <td>https://www.typescriptlang.org/</td>
        </tr>
    </tbody>
</table>

Framework de JavaScript Angular para el diseño (Frontend):

<table>
    <tbody>
        <tr>
            <td>Link de referencia: </td>
            <td>https://angular.io/</td>
        </tr>
    </tbody>
</table>

**Software Testing**

Gherkin es un sistema de etiquetado utilizado para detallar como se comporta el software de manera legible.

<table>
    <tbody>
        <tr>
            <td>Link de referencia: </td>
            <td>https://cucumber.io/docs/gherkin/</td>
        </tr>
    </tbody>
</table>

**Software Deployment**

Se ha utilizado Gitthub Pages para el despliegue de la landing page:

<table>
    <tbody>
        <tr>
            <td>Link de referencia: </td>
            <td>https://pages.github.com/</td>
        </tr>
    </tbody>
</table>

#### 5.1.2.Source Code Management

<table>
    <tbody>
        <tr>
            <td> Bliss-landing-page </td>
            <td> https://github.com/upc-opensource-g-bliss/Landing-Page </td>
        </tr>
        <tr>
            <td>Link Bliss-web-services: </td>
            <td>  </td>
        </tr>
        <tr>
            <td>Link Front Web Applications: </td>
            <td>  </td>
        </tr>
        <tr>
            <td>Link "Testing": </td>
            <td>  </td>
        </tr>
    </tbody>
</table>

**Flujo de trabajo GitFlow**

<img src="https://nvie.com/img/git-model@2x.png" width="60%" alt="Ejemplo flujo de Gitflow"/>

Usaremos el flujo de trabajo planteado por Vincent Driessen en "A successful Git branching model" con los siguientes parámetros:
 * Una rama de producción.
 * Una rama de pruebas.
 * Una rama en la que se solucionen los bugs rapidamente y vuelvan a producción.
 * Ramas de features a implementar.
 * Cada cambio en producción debe establecerse como una nueva versión.
 * Para este proyecto en concreto consideramos que los cambios en la rama de producción y de pruebas deben tener autorización de un compa­ñero de equipo.
   
Teniendo en cuenta la información anterior nos inclinamos por este tipo de organización en los branches:

* **Main branch:** Esta rama esta destinada a la producción de la aplicación, cada cambio deberá tener autorización de un compañero de equipo para evitar cambios sin verificar.
* **Hotfix branch:** En esta rama se incluirán todas las versiones que poseen errores identificados y que con cada arreglo de este se despliegue otra vez a Main Branch además de implementarla en lo que será Develop Branch.
* **Release branch:** Esta rama se utilizará para una previa a lo que será el Main Branch, aquí se seguirá de cerca a la aplicación en otros ambientes en busca de bugs.
* **Develop branch:** Esta rama está destinada a las constantes implementaciones en caliente de los features, 
* **Features branch:** Cada feature poseerá su respectiva rama, una vez que se encuentre correctamente implementada será fusionada con Develop branch.

Con cada deployment de la aplicación debe establecerse como una nueva versión.

#### 5.1.3.Source Code Style Guide & Conventions


Usaremos buenas prácticas en cuanto al código de manera que sea coherente y sostenible.

**HTML:**

* Cada etiqueta, id, nombre y clase será nombrada usando Lowercase.
* Utilizar UTF-8.
* Redacción en inglés.
* En cada referencia a un archivo, colocar el tipo de archivo (.css, .js).
* Terminar cada etiqueta con />.
    
**CSS:**

* Width del body al 100%.
* En cuanto a las imágenes, especificar el ancho (Width) de acuerdo a la etiqueta padre.
* Cada etiqueta, nombre y clase será nombrada de acuerdo al propósito y clasificación del elemento.
* Separación de palabras con un guion "-".
* Margin y padding en "*" con valor de 0.
  
<div id='5.1.4.'><h4> 5.1.4.Software Deployment Configuration</h4></div>

### Landing Page Deployment

Se desplegó en Github Pages, para esto necesitamos:

* Una cuenta personal
* Permisos de Github
* Repositorio existente

  Siguiendo los siguientes pasos:
  
1) Ir a configuración de nuestro repositorio de Github.
2) Seleccionar el apartado de Pages.
3) Elegir la rama main y folder(/root).
4) Una vez hecho el paso anterior se estaría contruyendo y poco tiempo después tendriamos que observar la landing desplegada.

<img src="resources/gthbpgsss1.JPG" />

<img src="resources/gthbpgsss2.JPG" />
  
#### 5.2.Landing Page, Services & Applications Implementation
#### 5.2.1.Sprint 1

<table>
    <thead>
        <tr>
            <td>Sprint #</td>
            <td>Sprint 1</td>
        </tr>
        <tr>
            <td colspan="2">Sprint Planning Background</td>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Date</td>
            <td>20/08/2024</td>
        </tr>
        <tr>
            <td>Time</td>
            <td>21:00</td>
        </tr>
        <tr>
            <td>Location</td>
            <td>UPC</td>
        </tr>
        <tr>
            <td>Prepared By</td>
            <td>BeautyServices</td>
        </tr>
        <tr>
            <td>Attendees (to planning meeting)</td>
            <td>Sorano Medriano, Diego Martin/Rodriguez Villa, Elvia Marcela/Cabrera Buitron, Diego Ivan/ Rivas Sarango, David Alejandro / Bernaola Pérez, André Arturo</td>
        </tr>
        <tr>
            <td>Sprint n – 1 Review Summary</td>
            <td>Siendo este el primer sprint, no hay reviews de sprints anteriores.</td>
        </tr>
        <tr>
            <td>Sprint n – 1 Retrospective Summary</td>
            <td>Siendo el primer sprint, se mencionará la expectativa de los miembros del equipo: Terminar las actividades antes de la crítica. </td>
        </tr>
        <tr>
            <td colspan="2">Sprint Goal & User Stories</td>
        </tr>
        <tr>
            <td>Sprint 1 Goal</td>
            <td>Diseñar e implementar la landing page</td>
        </tr>
        <tr>
            <td>Sprint 1 Velocity</td>
            <td></td>
        </tr>
        <tr>
            <td>Sum of Story Points</td>
            <td></td>
        </tr>
    </tbody>
</table>

##### 5.2.1.1.Sprint Planning 1
##### 5.2.1.2.Sprint Backlog 1
##### 5.2.1.3.Development Evidence for Sprint Review
##### 5.2.1.4.Testing Suite Evidence for Sprint Review
##### 5.2.1.5.Execution Evidence for Sprint Review

En este primer sprint se desarrolló la Landing Page con Tailwind, siendo desplegada en GithubPages. En esta landing encontraremos los features principales con el primer diseño de acuerdo al mockup de este.



##### 5.2.1.6.Services Documentation Evidence for Sprint Review

Para este primer sprint no fue contemplada la evidencia de documentación de los servicios.

###### 5.2.1.7.Software Deployment Evidence for Sprint Review

Link de Landing Page: https://upc-opensource-g-bliss.github.io/Landing-Page/

##### 5.2.1.8.Team Collaboration Insights during Sprint
#### 5.3.3.Evaluaciones según heurísticas
### 5.3. Validation Interviews
#### 5.3.1.Diseño de Entrevistas
#### 5.3.2.Registro de Entrevistas
### 5.4. Video About-the-Product
## Conclusiones
## Bibliografía
## Anexos
