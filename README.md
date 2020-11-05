# Fundamentos-de-pruebas-de-software

**Contenido**

[Clase 1 Introducción](#Clase-1-Introducción])

[Clase 2 ¿Qué son las pruebas y por qué deberíamos hacerlas?](#Clase-2-¿Qué-son-las-pruebas-y-por-qué-deberíamos-hacerlas?])

[¿Qué son las pruebas?](¿Qué-son-las-pruebas?)

[Clase 3 Proceso de pruebas del software y los estándares internacionales](#Clase-3-Proceso-de-pruebas-del-software-y-los-estándares-internacionales)

[Etapas del desarrollo de software](#Etapas-del-desarrollo-de-software)

[Revision de las pruebas](#Revision-de-las-pruebas)

[Clase 4 Ciclo de vida del software](#Clase-4-Ciclo-de-vida-del-software)

[Clase 5 Proceso de pruebas del software: Calidad y Defectos](#Clase-5-Proceso-de-pruebas-del-software-Calidad-y-Defectos)

[Clase 6 Principios del testing moderno](#Clase-6-Principios-del-testing-moderno)

[Clase 7 Especialidades del testing](#Clase-7-Especialidades-del-testing)

[Manual tester:](#Manual-tester)

[Automation tester:](#Automation-tester)

[Security tester:](#Security-tester)

[Data science tester:](#Data-science-tester)

[SDET:](#SDET)

[DevOps:](#DevOps)

[QA Engineer:](#QA-Engineer)

[QE:](#QE)

[Habilidades dentro de las especialidades del testing](#Habilidades-dentro-de-las-especialidades-del-testing)

[Clase 8 Presupuesto, Recursos, Tiempo y Actividades Clave](#Clase-8-Presupuesto,-Recursos,-Tiempo-y-Actividades-Clave)

[Etapa de Analisis](#Etapa-de-Analisis)

[Etapa de Diseño](#Etapa-de-Diseño)

[Etapa de codigo](#Etapa-de-codigo)

[Etapa de pruebas](#Etapa-de-pruebas)

[Clase 9 Estrategia de pruebas](#Clase-9-Estrategia-de-pruebas)

[Escenarios y Contextos](#Escenarios-y-Contextos)

[Herramienta para organizar ideas](#Herramienta-para-organizar-ideas)

[¿Que problema tenemos?](#¿Que-problema-tenemos?)

[Clase 10 Testing en desarrollo de software](#Clase-10-Testing-en-desarrollo-de-software)

[¿Que es testing?](#¿Que-es-testing?)

[¿Que es cheking?](#¿Que-es-cheking?)

[Errores comunes durante la ejecución](#Errores-comunes-durante-la-ejecución)

[Clase 11 Testing ágil](#Clase-11-Testing-ágil)

[Estrategias Ágiles:](#Estrategias-Ágiles)

[Clase 12 Niveles de pruebas](#Clase-12-Niveles-de-pruebas)

[Nivel de pruebas de componentes](#Nivel-de-pruebas-de-componentes)

[Pruebas de integración](#Pruebas-de-integración)

[Prueba de sistema](#Prueba-de-sistema)

[Pruebas de aceptación](#Pruebas-de-aceptación)

[Clase 13 Tipos de pruebas](#Clase-13-Tipos-de-pruebas)

[Pruebas funcionales](#Pruebas-funcionales)

[Pruebas no funcionales](#Pruebas-no-funcionales)

[Pruebas estructurales](#Pruebas-estructurales)

[Prueba de manejo de cambios](#Prueba-de-manejo-de-cambios)

[Clase 14 Pruebas estáticas y dinámicas](#Clase-14-Pruebas-estáticas-y-dinámicas)

[¿Qué son los elementos?](#¿Qué-son-los-elementos?)

[Beneficios](#Beneficios)

[Herramientas para realizar mockups](#Herramientas-para-realizar-mockups)

[Clase 15 Definición y diseño de pruebas](#Clase-15-Definición-y-diseño-de-pruebas)

[¿Qué hace un tester?](#¿Qué-hace-un-tester?)

[¿Qué debe de contener un caso de prueba?](#¿Qué-debe-de-contener-un-caso-de-prueba?)

[Clase 16 Caja Blanca, Gris y Negra](#Clase-16-Caja-Blanca-Gris-y-Negra)

[Pruebas de caja negra](#Pruebas-de-caja-negra)

[Pruebas de caja blanca](#Pruebas-de-caja-blanca)

[Pruebas de caja gris](#Pruebas-de-caja-gris)

[Clase 17 Gestión, monitoreo y control: Monitoreo y Seguimiento](#Clase-17-Gestión-monitoreo-y-control-Monitoreo-y-Seguimiento)

[Planeacion de pruebas](#Planeacion-de-pruebas)

[Clase 18 Roles y Responsabilidades](#Clase-18-Roles-y-Responsabilidades)

[Clase 19 Roles y Responsabilidades en acción ](#Clase-19-Roles-y-Responsabilidades-en-acción)

[Clase 20 Ejercicios](#Clase-20-Ejercicios)

[Clase 21 Retrabajo](#Clase-21-Retrabajo)

[Clase 22 Sistema de seguimiento de bugs](#Clase-22-Sistema-de-seguimiento-de-bugs)

[Clase 23 Defectos y sugerencias](#Clase-23-Defectos-y-sugerencias)

[Clase 24 ¿Qué es la depuración?](#Clase-24-¿Qué-es-la-depuración?)

[Beneficiados](#Beneficiados)

[Errores](#Errores)

[Clase 25 Técnicas de depuración](#Clase-25-Técnicas-de-depuración)

[Clase 26 Pruebas de verificación](#Clase-26-Pruebas-de-verificación)

[Clase 27 Automatización de pruebas](#Clase-27-Automatización-de-pruebas)

[Clase 28 Gherkin](#Clase-28-Gherkin)

## Clase 1 Introducción

En este curso veremos diferentes formas, tips y estrategias de realizar pruebas de software. Todas las técnicas te ayudarán a mejorar la calidad de tu software.

Principios del testing moderno y trabajo en equipo para implementar pruebas desde la perspectiva del tester y desarrollador

## Clase 2 ¿Qué son las pruebas y por qué deberíamos hacerlas?

¿Cuántas veces hemos sido usuarios de alguna app móvil y falla? ¿Cuántas veces hemos sido parte del desarrollo de un producto y el retrabajo se desborda por todas las fallas o defectos que contiene?.

Muchas veces la mala experiencia que tiene el usuario hace que en ese momento se deje de usar un software, app o elemento que tenga que ver directamente con experiencia como usuario 

### ¿Qué son las pruebas?

Es el proceso de evaluar un producto, aprendiendo a través de la exploración  experimentación, lo cual incluye:

Cuestionar, estudiar, modelar, observar e inferir, checar salida de datos, etc.

Verlo y entenderlo en todos sus aspectos

![assets/img1.png](assets/img1.png)

Realmente siempre existe un sesgo en el cual tendremos la posibilidad a si sea del 0.001% de tener un error, con la implementacion de nuevas tecnologias es muy posible que suceda esto por lo que sera necesario en algun momento recurrir a la actualizacion y optimizacion de las pruebas 

Las pruebas son una manera de explorar, experimentar, entenderlo, entre menos entiendas el productos que estas desarrollando más errores tendrá. Las puedes hacer por cuestión de costo, prestigio o cuestiones legales.

![assets/img2.png](assets/img2.png)

Tres aspectos a considerar:

![assets/img3.png](assets/img3.png)

Es necesario entender completamente aunque se tengan las mejores practicas de desarrollo o de pruebas para evitar que los defectos y errores se conviertan en re-trabajo y multiplicar los defectos o convertirlo en bola de nieve, aqui uno de los aspectos mas importantes 

- Estimar bien

- Entender el producto

- Saber quien es el cliente

- Comunicacion con el equipo de desarrollo en los diferentes niveles y subniveles para que se pueda trabajar de una manera armoniosa y adecuada. Con esto se evita recurrir en reprocesos y estar apagando incendios

## Clase 3 Proceso de pruebas del software y los estándares internacionales

### Etapas del desarrollo de software

![assets/img4.png](assets/img4.png)

- Que es Metodologia 

Es la parte en donde se establecen criterios o estrategias de como se va a llevar a cabo las pruebas, quien es el responsable, como se debe entregar el material, Etc.

- Recursos

Aunque se quieran hacer pruebas y no se esta preparado con el tiempo esas carencias se van a mostrar como defectos

- Herramientas

Contar con las herramientas adecuadas permiten de alguna forma acelerar el trabajo como tester en cuanto a la identificacion de problemas, documentación y comunicación

Es necesario tener muy bien definidas estas etapas para evitar re-procesos y que todo el equipo entienda la finalidad del mismo 

![assets/img5.png](assets/img5.png)

### Revision de las pruebas

- Definir la falta de calidad del equipo

- Detectar y corregir la falta de calidad

- Calidad del proceso

- Verificar especificaciones y necesidades del cliente

![assets/img6.png](assets/img6.png)

Las certificaciones pueden ser aplicadas a cualquier tipo de industria, automotriz, farmaceutica, ventas, salud, personas y empresas en general

![assets/img7.png](assets/img7.png)

y cada una de este tipo de industrias lleva diferentes tipos de pruebas 

![assets/img8.png](assets/img8.png)

No solo se deben implementar certificaciones en las empresas porque muchas veces esto no significa que cumplan con los estandares de calidad, se debe velar por cumplir y mantener estandares que promuevan el buen desarrollo de la empresa

## Clase 4 Ciclo de vida del software

A lo largo del ciclo de vida del software se realizan distintas pruebas para garantizar que este cumpla con los requerimientos para los que fue diseñado y de la misma forma se encuentren procesos de mejora y optimización a medida que se desarrolla el software.

- Es necesario hacer pruebas en todas las fases del desarrollo de software ya que un error encontrado en una etapa tardía puede generar costos muy elevados.

- Errores detectados lo antes posible reducen los costos y son mucho más fáciles de corregir.

- El ciclo de vida permite que los errores se detecten lo antes posible y por lo tanto, permite a los desarrolladores concentrarse en la calidad del software, en los plazos de implementación y en los costos asociados.

El ciclo de vida básico de un software consta de los siguientes procedimiento

![assets/img9.jpg](assets/img9.jpg)

1. Definición de objetivos

    En esta fase se define el alcance general del software y su papel dentro de una estrategia global o dentro del ecosistema que va a funcionar.

2. Análisis de los requisitos y su viabilidad

    Se trata de recopilar la mayor cantidad de información posible para evaluar la viabilidad del producto, encontrar posibles restricciones y analizar todos los requisitos del cliente.

3. Diseño

    Alto nivel: Se trata de realizar un diseño básico que valide la arquitectura de la aplicación.
    Bajo nivel: Es una definición detallada de la estructura de la aplicación basada en el diseño general.

4. Programación

    Es la implementación de un lenguaje de programación para crear las funciones definidas durante la etapa de diseño.

5. Pruebas de verificación

    Aunque en todas las fases anteriores se hacen pruebas en esta fase se cubren: pruebas de componentes, integrales y de sistema.

6. Prueba beta (o validación)

    Se hace para garantizar que el software cumple con las especificaciones originales o también se hacen las pruebas de aceptación.

7. Implementación

    Se realiza una prueba del sistema implementado para encontrar posibles fallas en la Implementación.

8. Mantenimiento

    Se hace para todos los procedimientos correctivos (mantenimiento correctivo) y a las actualizaciones secundarias del software (mantenimiento continuo), junto con la actualización de las pruebas.

Si hacemos las pruebas durante cada fase del ciclo de vida del software tendremos al final del ciclo un producto validado y robusto de acuerdo a las necesidades del cliente

## Clase 5 Proceso de pruebas del software: Calidad y Defectos

![assets/img10.png](assets/img10.png)

La calidad es una percepción entre lo deseado, analizado y lo que vamos a entregar. La calidad la define el cliente, si esa persona esta satisfecha con lo entregado hasta ahí llega la calidad.

Los estandares de la IEEE(Insitute of Electrical and Electronics Engineers) (Instituto de Ingenieros Eléctricos y Electrónicos) asociación técnico-profesional mundial dedicada a la estandarización, entre otras cosas. Es la mayor asociación internacional, sin ánimo de lucro, formada por profesionales de las nuevas tecnologías.) forman parte de la documentacion y es la manera en la que define el cumplimiento de requisitos, necesidades o expectativas del cliente

![assets/img11.png](assets/img11.png)

Se hace enfasis en el entendimiento y necesidades del cliente. Si los procesos de pruebas de software no son eficientes, en cada una de las fases va a empezar a haber defectos

![assets/img12.png](assets/img12.png)

Dentro de las etapas existe una planificacion estandar que van a variar respecto a necesidades y tiempo del proyecto

![assets/img13.png](assets/img13.png)

- **Verificación:** Es ir en cada etapa revisando que se cumpla lo propuesto por el cliente.

- **Validación:** Antes de entregar al cliente, validamos que efectivamente el conjunto de requerimientos esta siendo cumplido con lo entregado.

- **Anomalía:** Cualquier condición insatisfactoria

- **Defecto:** Un problema que se reproduce una y otra vez, no desempeña funciones

- **Fallo:** Pueden ser situaciones no asociadas al software desarrollado, incapacidad dentro de márgenes

- **Error:** Acción humana incorrecta

![assets/img14.png](assets/img14.png)

## Clase 6 Principios del testing moderno

Los principios creados por Ellen Page y Brian Jensen es acerca del testing moderno que es la evolucion natural del testing agil

El desarrollo de este principio es la necesidad de que el tester y el desarrollador evoluciones en su perspectiva para que ambos trabajen como un equipo y no como dos entidades separadas

El tester deberia enfocarse en la calidad del producto, proceso (calidad de software)

El desarrollador deberia enfocarse en desarrollar la aplicacion

El tester podria ayudar a mejorar a encontrar las mejores herramientas a entender los procesos de prueba y mejorar la calidad del desarollo 

![assets/img15.png](assets/img15.png)

1. Nuestra prioridad es mejorar el negocio: El producto que se va a entregar al cliente permitirá hacer funcionar el negocio. Si en algún momento no quieres hacerlo, estás poniendo en riesgo ese negocio porque si el producto no se vende o no es aceptado la empresa puede cerrar o puedes perder el trabajo.

2. Nosotros aceleramos el equipo y usamos modelos como Lean Thinking y Teoría de las Restricciones para ayudar a identificar, priorizar y mitigar cuellos de botella en el sistema: Cuando queremos hacer algo, lo queremos hacer perfecto y eso puede ser demasiado. Deberías construir en base a procesos cortos para poder encontrar los defectos de una manera más rápida.

3. Nosotros somos la fuerza para la mejora continua, ayudando al equipo a adaptarse y optimizar para tener éxito, en lugar de proporcionar una red de seguridad para detectar fallas: El cliente puede entender que el producto se va a liberar por fases, es importante que nosotros enfoquemos nuestras pruebas en cada una de esas fases. No tiene que ser todo al inicio y al final, debe haber una distribución que nos permita manejar el riesgo del software

4. Nos preocupamos profundamente acerca de la cultura de calidad en nuestro equipo, y asesoramos, lideramos y nutrimos el equipo para llevarlos a una cultura de calidad más madura: Al inicio los testers eran personas desarrollando software y un día con tantos defectos y trabajo, separaron los roles para que así hubiese una persona dedicada a realizar las pruebas. El tester puede hacer recomendaciones de herramientas, mejorar el proceso o volverse un coach.

5. Nosotros creemos que el cliente es el único capaz de juzgar y evaluar la calidad de nuestro producto: Si el cliente esta satisfecho con lo entregado y cumple las expectativas entonces has alcanzado la calidad deseada.

6. Nosotros usamos datos de manera extensa y profunda para entender los casos de uso del cliente y entonces cerrar huecos entre hipótesis del producto e impacto del negocio.

7. Expandimos las habilidades de testing y el conocimiento en todo el equipo; entendemos que esto reduce o elimina la necesidad de una especialista dedicado al testing.

![assets/img16.png](assets/img16.png)

## Clase 7 Especialidades del testing

### Manual tester:

Nos ayuda a definir los casos de pruebas, establecer estrategias. También ejecuta, pero lleva lo necesario para que todos sepan qué hacer.

Pensamiento lateral, piensa fuera de la caja con una nueva perspectiva, agrega nuevos casos de usos y entiende muy bien al usuario.

### Automation tester: 

Se encarga de agilizar, acelerar el trabajo y actividades que nos quitan la oportunidad de encontrar más casos de usos.

Conoce de programación, no solo de forma básica, debe conocer como crear diseños de frameworks y soluciones. El código crece y las pruebas también, darle ese mantenimiento a las pruebas es un problema común.

### Security tester: 

Encargado para el área de seguridad. Debe ser alguien que aporte valor desde la perspectiva de la seguridad.

Protocolos, estándares, legalizaciones dependiendo de cada país y marca. Esta enfocado en prever ataques, virus, problemas de seguridad, acceso no autorizado. Profundizar en las técnicas y prácticas de seguridad.

### Data science tester: 

Con la manera en que crecen los datos en un proyecto, se necesita a alguien que los analice, agrupe y limpie estos datos.

Análisis y Limpieza de datos, omite tener un set de pruebas amplio donde la variedad va a permitir detectar defectos inesperados. Esto puede ser clave para que los resultados no sean falsos positivos

### SDET: 

Es la combinacion de un desarrollador que ya sabe hacer pruebas. Con la diferencia de automatiza y hace uso de herramientas que organizan la operación de la entrega de las pruebas. Esta persona se asegura de que las pruebas se ejecuten antes de liberar el código.

El programador ahora sabe hacer pruebas y conoce de herramientas que le permite entregarlas de una manera automatizada.

### DevOps: 

Conoce todo lo anterior y domina el conocimiento de automatizar el proceso, se asegura de una entrega continua.

Una automatización de la operación, Entrega Continua. Donde se entregan de forma más rápida las nuevas versiones.

### QA Engineer: 

Quality Assurance. Esta enfocado en el producto y en el proceso.

Procesos de Calidad

### QE: 

Quality Engineer. Es como un coach, acompaña en las politicas de calidad en la empresa o equipo.

Soluciones de estrategias de calidad.

### Habilidades dentro de las especialidades del testing 

![assets/img17.png](assets/img17.png)

## Clase 8 Presupuesto, Recursos, Tiempo y Actividades Clave

![assets/img18.png](assets/img18.png)

Elementos para crear un proyecto de software tienen que ver con el presupuesto, recursos y tiempos

Si un proyecto no tiene suficiente dinero para tener el equipo necesario de personas e infraestructura no se va a poder llevar a cabo

Si no se cuenta con el equipo de recurso humano ideal e idoneo con el conocimiento el proyecto peude que no se lleve a cabo o por lo menos puede pasar que no se cumpla el tiempo estimado del mismo

Los costos tambien pueden llegar a incrementar

![assets/img19.png](assets/img19.png)

![assets/img12.png](assets/img12.png)

## Etapa de Analisis

- Revision con el cliente y equipo

- Documentacion

- Pruebas de requerimientos del cliente

- Alcance y necesidad del cliente y como puedo empezar a abordar los problemas que se puedan llegar a aparecer por mas ambiguos que sean y tambien como voy a confirmar que un requerimiento se cumpla

## Etapa de Diseño

- Criterios visuales que espera el cliente

- Que espera en la funcionalidad combinado con el diseño del producto

- Alertas del producto al hacer check de manera correcta o incorrecta

## Etapa de codigo

- Revision e implementacion de modulos, funciones o bases de datos

- Verificacion de lo que esta en el backend y en lo posible si existe el Frontend

- Revision de las mejores practicas para la implementacion y desarrollo del software

## Etapa de pruebas

- Pruebas de transmision de datos en distintos dispositivos

- Confirmacion de los requerimientos del cliente a traves de la validacion y verificacion

- Pruebas de aceptacion donde el usuario final acepta el producto requerido pero se debe tener que cuenta que antes de entregar al cliente final se tuvieron que haber hecho todas las pruebas posibles en las anteriores etapas

## Clase 9 Estrategia de pruebas

Son aquellas que nos permiten saber por donde comenzar 

![assets/img20.png](assets/img20.png)

### Escenarios y Contextos

- Seguridad

- Arquitectura

- Performance

- Usabilidad

- Escalabilidad

### Herramienta para organizar ideas

https://mindmup.com 

![assets/img21.png](assets/img21.png)

### ¿Que problema tenemos?

![assets/img22.png](assets/img22.png)

## Clase 10 Testing en desarrollo de software

### ¿Que es testing?

Es la exploración de una idea, aprender a conocer como sucede un flujo, como se generan datos, como se llena un formulario y genere nuevos resultados

### ¿Que es cheking?

Es cuando se sabe que ya sucede algo y se verifica que sigue pasando

![assets/img23.png](assets/img23.png)

- Solo se ejecutan si ... sucede algo

- Se ejecutan cada que ... libere

- Se ejecutan de manera programada 

### Errores comunes durante la ejecución

![assets/img24.png](assets/img24.png)

- **Pruebas duplicadas:** Al no tener una buena organización o comunicación con el equipo, la cobertura de pruebas puede ser duplicada, por ejemplo que algún otro miembro ya probó

- **Pruebas similares:** A veces se pueden crear pruebas que tienen que ver con el mismo flujo.

- **Pruebas sin valor agregado:** Aquellas que no están asociadas al negocio, se debe priorizar siempre.

- **Pruebas caducadas:** Se refiere a la tecnología por ejemplo que se esté usando ya que como sabemos se suelen ir actualizando.

Cuando logramos distinguir correctamente entre pruebas y verificación es cuando entra la automatización de pruebas, con ella se usa un software especial para controlar y comparar los resultados obtenidos de los esperados, es entonces una verificación repetitiva y automatizada.

La automatización de pruebas consiste en el uso de software especial para controlar la ejecución de pruebas y la comparación entre los resultados obtenidos y los resultados esperados. 

Sin embaro, se trata de un checking repetitivo y automatizado.

![assets/img25.png](assets/img25.png)

![assets/img26.png](assets/img26.png)

## Clase 11 Testing ágil

![assets/img27.png](assets/img27.png)

Involucra a todos, no solo el tester, todos en el equipo son tester. La persona con este rol se aseguran de la mayor cobertura de pruebas tomando en cuenta todas las necesidades que cada uno de los miembros del equipo también esta intentando hacer que funcione. El tester tiene que definir si se esta cumpliendo con los requerimientos funciones y los del equipo, al final, sera el apoyo que dara dando retroalimentacion y viendo como puede dar funcionalidad para tener finalmente un proyecto o servicio optimo.

### Estrategias Ágiles:

- El testing es de “todo el equipo”

- El testing puede ser independiente

- Integración continua

- Testing guiado por pruebas (Test Driven Development)

- Desarrollo guiado por comportamiento (Behaviour Driven Development)

- Desarrollo guiado por las pruebas de aceptación (Acceptance Test Driven Development)

La finalidad de este es que entre todos puedan pensar como hacer pruebas teniendo distintos entornos y ambientes que se puedan llegar a presentar en una aplicacion cualquier contando con los detalles mas minimos para que el producto tenga todas las caracteristicas donde si hay un sesgo de error no se note con la funcionalidad del producto.

## Clase 12 Niveles de pruebas

Es ver las estrategias de como poder probar elementos por capas, componentes, niveles de estructura, etc.

Como separar las pruebas para que la cobertura que vayamos teniendo tenga una mejor descripcion, comprension y en la parte de desarrollo sea mas complementaria, pasando de los componentes, a la integracion y pruebas totales

### Nivel de pruebas de componentes

Los componentes son aquellas pequeñas cosas que se pueden ver por ejemplo cuando uno ve un video y esta el boton de play, pausa, like, etc. Pueden ser tambien componentes del formulario 

### Pruebas de integración

Una aplicación tiene una serie de componentes que trabajando juntos forman un pequeño sistema, pero cuando tienes varios de estos sistemas necesitas integrarlos entre ellos, como desde el inicio hasta el final de un flujo de negocio todos los componentes se comunican, como entran y salen los datos.

### Prueba de sistema 

Esta parte incluye que estás tomando en cuenta el contexto, no es lo mismo tener las mismas pruebas para iOS, Android, Web, etc.

### Pruebas de aceptación 

Si ya probamos que nuestro elemento o acción funcionan, estás pruebas nos aseguran con o sin el cliente que tiene cubierta todas las necesidades requeridas en el software. Es la última verificación.

## Clase 13 Tipos de pruebas

Necesitamos tener otra clasificación adicional. En los niveles sabemos la profundidad de las pruebas, pero en los tipos independientemente de su profundidad son las técnicas que vamos a usar para encontrar los defectos.

### Pruebas funcionales 

Cómo funciona un sistema, qué debe estar haciendo, cómo está interactuando el usuario con él.

### Pruebas no funcionales 

El usuario puede estar experimentando otro tipo de cosas que aún funcionando puede tener la sensación de lentitud, falta de legibilidad o claridad. Esas características de usabilidad están asociadas a estas pruebas.

### Pruebas estructurales 

Tienen que ver con la tecnología y el stack usado para construir nuestro producto. Nos tenemos que asegurarnos que nuestra base de datos o servidor funcionen de la manera correcta. Son conocidas como pruebas de caja blanca.

### Prueba de manejo de cambios 

Es probar nuevamente un componente ya probado para verificar que no ha sido impactado por actualizaciones.

Estas serian la clasificacion de actividades de cuando se prueba en el Frontend, Backend o la estructura, en base a cambios, nuevas caracteristicas o cuando se estan arreglando defectos

## Clase 14 Pruebas estáticas y dinámicas

Generalmente se espera que el tester siempre este ejecutando pruebas pero muchas veces, las pruebas estaticas no son consideradas durante el desarrollo porque este tipo de pruebas incluyen que se este leyendo documentación, analizando software, comparando, haciendo un planteamiento diseñando el plan de pruebas

![assets/img28.png](assets/img28.png)

![assets/img29.png](assets/img29.png)

### ¿Qué son los elementos?

- Contratos, planes y calendario del proyecto, asi como su presupuesto.

- El análisis de requerimientos

- Especificaciones o regras de negocio

    - Tecnicos

    - Seguridad 


Es cuestionar que elementos a lo mejor no esta incluyendo el cliente y el tester esta para preguntar qué, como, de que manera, debe hacer el desarrollador para incluir elementos que no se estan especificando en un principio pero que van a ser necesarios en la funcionalidad del producto que esta solicitando el cliente 

- Las definiciones de 

    - Historias del usuario

    - Criterios de aceptacion

    - Mockups

- El diseño de la arquitectura

- Las pruebas (Testware), puntos de verificacion, (Pruebas clave)

- Guias de usuario

- Evaluación/revisión del código

### Beneficios

- Detectar y corregir defectos de manera más eficiente

- Identificar y priorizar la ejecución de pruebas en etapas posteriores

- Prevenir defectos

    - Que no son fácilmente detedectables durante las pruebas dinámicas

    - Durante la etapa de análisis y diseño

- Cubrir aspectos como:

    - Inconsistencias, ambigûedades, contradicciones, definiciones inexactas, requerimientos redundantes

- Reducir el retrabajo e incrementar la productividad

- Reducir el costo y el tiempo

- Mejorando la comunicación entre todos los miembros del equipo

### Herramientas para realizar mockups

- Gliffy https://www.gliffy.com/

![assets/img30.png](assets/img30.png)

- Cacoo https://cacoo.com/

![assets/img31.png](assets/img31.png)

- Mockflow https://www.mockflow.com/

![assets/img32.png](assets/img32.png)

- Frame Box http://framebox.org/

![assets/img33.png](assets/img33.png)

- Wireframe cc https://wireframe.cc/ 

![assets/img34.png](assets/img34.png)

## Clase 15 Definición y diseño de pruebas

### ¿Qué hace un tester?

1. Encontrar problemas

2. Documentar problemas

3. Comunicar problemas

![assets/img35.png](assets/img35.png)

Si cuando encuentra problemas no sabe documentar y reproducir los pasos correctos su testing genera retrabajo y sube el costo

Si como representate de la calidad del producto no sabe argumentar y proteger los intereses del negocioo los clientes, entonces su testing no agregar valor

### ¿Qué debe de contener un caso de prueba?

Debe tener:

- nombre: corta descripcion de lo que se va a realizar

- descripción: Explicación de que se trata la prueba

- pasos: Cada uno de los pasos de la prueba

- resultados esperados

- resultados actuales

![assets/img36.png](assets/img36.png)

## Clase 16 Caja Blanca, Gris y Negra

Se llaman pruebas de caja porque es la manera de observar el contenido del software.

Los modelos de caja negra es cuando por ejemplo en un computador no vemos como fue construido, se puede referenciar dentro del desarrollo como la parte del Backend, el codigo, no sabemos de arquitectura, si no la unica noción que tenemos es la interfaz con la que interactua el usuario

### Pruebas de caja negra

- **Partición de equivalencia:** Que tipo de informacion dentro de los tipos de datos deberia contener por ejemplo un formulario, enteros, flotantes

- **Valores límite:** Establecer limites por ejemplo un maximo de digitos en una fraccion en pesos.
    Que pasa si coloco una fraccion de 90.001 o 90.000.001 o 90.000.00001

- **Tabla de decisiones:** Aplica para casos donde existen check box o listas y son valores fijos, no le corresponde la opcion de establecer un criterio a los usuarios

- **Transición de estados:** Como el componente se comporta 

- **Casos de usos:** Por ejemplo donde un usario puede llenar un formulario y enviarlo o los campos son obligatorios y no puede pasar al siguiente campo hasta no completar los que son obligatorios

Los modelos de caja blanca es llamada en ocasiones caja de cristal, se puede referenciar dentro del desarrollo como la parte del Frontend, donde se puede ver todo lo que hay adentro e incluso es posible ser parte del equipo que esta desarrollando software 

### Pruebas de caja blanca

- **Cobertura de declaración:** Es todo aquello que esta dentro del codigo y se pide hacer, es decir que cada linea de codigo realizada se ejecute por lo menos una vez, debe tener una cobertura medible por porcentaje

- **Cobertura de codigo:** Es eliminar todo tipo de codigo que sea innecesario en el producto o proyecto teniendo en cuenta:
    
    - Sentencias

    - Desiciones

    - Condiciones 

Los modelos de caja gris es donde se realizan integraciones, viene siendo un punto intermedio entre la caja blanca y la caja negra y podemos ver los datos como fluyen o se transmiten de un lugar a otro

### Pruebas de caja gris

- **Casos de negocios:** Como el usuario esta interactuando en el Frontend o la interfaz y como esta respondiendo el producto es decir todo lo que va al Backend, se transforma y de que forma regresa la informacion al Frontend de nuevo. Es decir datos de entrada y salida

- **Pruebas End-to-End:** Se refiere por ejemplo a la creacion de un usuario para una aplicacion pero no necesariamente se tiene que ver como quedo en la salida y posiblemente no se vea el resultado pero se visualiza en otro entorno

- **Pruebas de integración:** Es ver como se estan transmitiendo los datos del Frontend al Backend 


![assets/img37.png](assets/img37.png)

## Clase 17 Gestión, monitoreo y control: Monitoreo y Seguimiento

![assets/img38.png](assets/img38.png)

### Planeacion de pruebas

- **Planeación:** Definir los objetivos de las pruebas es muy importante, al no tener una estrategia clara termina causando una pobre cobertura de pruebas. Los elementos a considerar para una buena planeación son la estimación, recursos, el alcance y objetivo.

![assets/img39.png](assets/img39.png)

- **Monitoreo y Control:** Durante el monitoreo lo que estamos buscando son esas métricas que nos digan si estamos llevando avances o tenemos retrasos. Son nuestras alertas cuando nuestro plan no se esta ejecutando.

![assets/img40.png](assets/img40.png)

- **Análisis:** Incluye decidir cuáles son esas prioridades que nos ayudará a definir qué debemos probar.

![assets/img41.png](assets/img41.png)

- **Diseño:** Normalmente cuándo estas iniciando las pruebas es necesario crear un mapa de ideas. Después de esto, puedes realizar el diseño a detalle de qué va a incluir cada caso de uso. Casos de alto nivel, diseñar y priorizar pruebas, identificar el entorno de pruebas, hacer una trazabilidad entre pruebas y sus condiciones.

![assets/img42.png](assets/img42.png)

- **Implementación:** También nos aseguramos de contar con la estructura necesaria para realizar las pruebas, con un ambiente, datos y dónde documentar o realizar las pruebas.

![assets/img43.png](assets/img43.png)

- **Ejecución:** En esta etapa los suites de pruebas se ejecutan de acuerdo al programa o el plan diseñado con anterioridad. Se suelen agrupar los casos de pruebas para que no estén desorganizado y podemos hacerles un buen seguimiento.

![assets/img44.png](assets/img44.png)

- **Finalización:** Cuando queremos cerrar el ciclo de las pruebas, necesitamos saber qué porcentaje se cubrió, ejecutó, cuántos defectos se derivaron, aprender lecciones sobre el proceso.

![assets/img45.png](assets/img45.png)

## Clase 18 Roles y Responsabilidades

- **Especialista en pruebas manuales:** Entre las habilidades que debería de tener, es el pensamiento lateral, en la parte de organización, diseño y documentación, debería de ser el especialista en entender cuáles son los casos de uso que se van a llevar para cada área, debe de poder organizarse y asignar trabajo para sí mismo dependiendo las prioridades del negocio, los riesgos o el impacto.

- **Especialista en pruebas técnicas:** Esta persona se tiene que encargar de estar siempre actualizada en las herramientas que le permitan acelerar el trabajo, mejorar el trabajo, búsqueda, continuo entrenamiento, ser autodidacta.

- **Líder del equipo de pruebas:** Gestiona el equipo y es un facilitador para las actividades a realizar, como apoyar con ambiente de pruebas, darle seguimiento a los defectos, revisar que los lineamientos se sigan.

- **Ingeniero de calidad:** Se dedica a la parte del proceso, es quien se encarga de establecer las políticas, mantener involucrados a los equipos, alineados a las prioridades del negocio; además que verifica que todo esto se cumpla sobre todo para la entrega del cliente.

## Clase 19 Roles y Responsabilidades en acción 

Independientemente del rol, un tester participa de todas las etapas del proceso de desarrollo de software, colaborando para asegurar la máxima calidad del producto. Su perfil conjuga un conjunto de habilidades con el conocimiento del negocio, de la aplicación bajo prueba y de cómo planificar, diseñar, ejecutar y administrar las pruebas.

“Un tester investiga un producto de software con el objetivo de obtener información acerca de su calidad y del valor que representa para quienes lo utilizan”

![assets/img46.png](assets/img46.png)

Cuando el esfuerzo en la calidad se enfoca y se distribuye en roles y responsabilidades podemos encontrar que la mayoría de las empresas manejan los siguientes roles:

**El tester manual**, se enfoca en la estrategia, definición, ejecución y cobertura de pruebas para cumplir los requerimientos, echando mano de cualquier técnica para obtener información suficiente y así cumplir con las asignaciones correspondientes.

**El tester técnico**, trabaja muy de cerca con el tester manual, mientras que el tester manual define las pruebas, el tester técnico acelera la capacidad de ejecución de las pruebas. Esto lo hace implementando herramientas que permitan la automatización de pruebas, o la correcta selección de datos de pruebas, o el monitoreo de la ejecución de las pruebas.

**El líder de pruebas**, generalmente dentro de sus responsabilidad es volverse un facilitador de servicios, información y herramientas para el equipo de pruebas, para poder estimar presupuestos, recursos y tiempos respecto al plan de desarrollo de software.

**El Ingeniero de calidad**, ya no solamente está al pendiente del producto y los procesos, comienza a involucrarse más con el negocio, ayudando tanto a testers como cualquier otro miembro del equipo a llevar cabo pruebas que reduzcan, en todas las etapas del ciclo de vida del software, el error humano.

## Clase 20 Ejercicios

https://platzi.com/clases/1421-pruebas-software/15106-ejercicios8293/

## Clase 21 Retrabajo 

![assets/img47.png](assets/img47.png)

Es necesario identificar cada uno de los roles y responsabilidades para después evaluar si se esta haciendo o no re trabajo, es decir estamos utilizando tiempo que podría ser utilizado en otras actividades o sencillamente que no debería hacerse

También es necesario medir el rendimiento de nuestro trabajo y herramientas que nos permitan conocer paso a paso cómo vamos avanzado en el proceso de manera individual o en equipo.

Otra forma es analizando los resultados de las pruebas. Es ver cuantas de ellas se han ejecutado, cuantas no han pasado, cuantas derivaron defectos o que no le permitio continuar el traajo.

El desempeño del testing, Que circunstancias permiten o no realizar el trabajo, como por ejemplo el que una persona no vaya un dia al trabajo, el cliente no entregue alguna especificacion, el equipo no es adecuado, se fue el internet.

**¿Cuando sucede el retrabajo?**

![assets/img48.png](assets/img48.png)

**Retrabajo:** Es la principal causa del retraso, de que la estimación de tiempo falle, de que costos suban. Cuando estos suceden aumentamos exponencialmente el trabajo de todos

- Falta o mala documentación

- Falta de capacitación o dominio en las herramientas utilizadas

- Falta de capacitación o dominio en el software a desarrollar

- Falta de comunicación

**Herramienta Diagrama de Gantt**

https://www.easyredmine.com/

## Clase 22 Sistema de seguimiento de bugs

La mala administración, malas prácticas o falta de seguimiento entorpece las tareas de todo el equipo sino que además si sumamos el retrabajo en la mala documentación puede que nuestro proyecto se salga de presupuesto o tiempo.

**Razones por las que aparecen defectos:**

- Hay presión de tiempo en la entrega del software

- Descuidos en el diseño

- Inexperiencia o falta de conocimiento

- Falta de comunicación en los requerimientos

- Diseño complejo de código

- Desconocimiento de las tecnologías usadas

**Preguntas a realizar para construir un proceso de gestión de bugs:**

- ¿Qué debe de hacer la persona que encuentre el defecto?

- ¿En qué herramienta debe documentar el defecto?

- ¿Cómo vamos a almacenar la información?

- ¿Qué información requiere el equipo de desarrollo para poder resolver un defecto?

- ¿Cuáles son los estatus que se manejan para que fluya la resolución del defecto?

- ¿Cuáles son los criterios de aceptación de cierre del defecto?

![assets/img48.png](assets/img49.png)

- El ciclo de gestion comienza con el reporte, es revisado y se considera en estatus abierto porque aun no ha sido resuelto

- Una vez se define que se va a reparar se asigna un desarrollador para atender el caso

- Cuando se repara el estatus pasa a arreglado

- Si la confirmacion es exitosa se cierra el caso

- Si ocurre un defecto nuevamente pasa al ciclo de gestión nuevamente y dependiendo el caso se reescribe el reporte y se analiza si debe ser aceptado, rechazado o se puede tomar como una sugerencia, luego pasa a estatus reabierto y nuevamente se trabaja sobre la reparacion del reporte y posteriormente en caso que la confirmacion se exitosa, nuevamente se cierra el caso

![assets/img50.png](assets/img50.png)

Se debe tener en cuenta que la persona debe ser responsable y reportar o abrir nuevos casos o tickets para que se trabaje eficientemente en los cambios y no significa que se deba agregar algo mas de lo solicitado, si no unicamente trabajar en el reporte y comuunicar eficientemente los cambios para que sean revisados por el equipo o el lider del proceso

## Clase 23 Defectos y sugerencias

**Defectos**

Es aquello que no cumple los requerimientos funcionales, de diseño, arquitectura y es la consecuencia de un error humano o intepretacion con la cual se construyo un software

**Sugerencia**

Como la experiencia del usuario se ve afectada, colores, navegacion lenta, lenguaje, cultura etc.

![assets/img51.png](assets/img51.png)

![assets/img52.png](assets/img52.png)

**Cómo reportar un defecto/sugerencia**

para este caso se establece un ejemplo de un mensaje de error que le aparece a un usuario que se esta registrando y probablemente ya habia hecho un registro anterior pero el mensaje que le esta saliendo al usuario es erroneo y no es el esperado

![assets/img53.png](assets/img53.png)

Se debe tener la plantilla para realizar el reporte

![assets/img55.png](assets/img55.png)

En este caso se toma un Screenshot para ampliar la informacion que se esta comunicando

![assets/img54.png](assets/img54.png)

se pueden tomar datos de donde proviene la informacion que se esta reportando

![assets/img56.png](assets/img56.png)

Tambien se pueden añadir campos de ser necesarios a la plantilla de reporte para documentar el caso reportado

![assets/img57.png](assets/img57.png)

## Clase 24 ¿Qué es la depuración?

Hacer testing o depuración son dos actividades diferentes. Mientras el testing sirven para encontrar defectos, la depuración nos permitirá entender por qué esta sucediendo este defecto y que actividades están implicadas en el. Ambas pueden ir de la mano y son muy importantes.

**Debugger:** Es una herramienta que nos ayuda a encontrar todos estos errores ya sea de sintaxis, advertencias de seguridad, etc. Nos permite ejecutar línea por línea, detener la ejecución temporalmente, visualizar el contenido de las variables, cambiar el valor del entorno de ejecución para poder ver el efecto de una corrección en el programa.

### Beneficiados

- **Programador:** Requiere cada vez que programa ir depurando lo que ejecuta y escriba para que cumpla con su objetivo

- **Tester:** Le ayuda a reducir el tiempo de análisis que después puede ser asignado para el desarrollador

- **Analista:** Puede ser para analisis de encontrar información de un historial sobre cómo se comporta un sistema.

- **Objetivo:** Vamos a analizar cómo se comporta el sistema, cómo se transfieren los datos, cómo se procesa la información. Tenemos la capacidad de tener nuestro código en cualquier momento para conocer cómo funciona.

### Errores

Aunque se realice depuración existe probabilidad de encontrar defectos

![assets/img58.png](assets/img58.png)

![assets/img59.png](assets/img59.png)

se deben observar:

- Mensajes de advertencia

- Estándares de compilación

- Verificación sintáctica y lógica

## Clase 25 Técnicas de depuración

Deben ir cambiando de ser reactivas a ser preventivas. Si ya podemos observar a través de estas herramientas cómo se está utilizando la información, hacia dónde viaja, quién responde, deberíamos también recordar que parte de los principios del testing moderno es tratar de ir corrigiendo nuestras técnicas, implementar mejores prácticas y hacer uso de mejores herramientas. El debugging debería de ser la última alternativa.

**Técnicas de depuración:**

- **Debugging:** Observar valores de variables, detener temporalmente la aplicación.

- **Logs:** Hacer un vaciado de cómo las variables van cambiando y es más fácil rastrear la información.

![assets/img60.png](assets/img60.png)

- **Historial:** Agiliza la forma de monitorear y observar los comportamientos de nuestro software. - Comparando valores, agrupando información.

![assets/img61.png](assets/img61.png)

- **Reportes:** Observar anomalías, acelerar el tiempo de respuesta, prevenir ataques o fallas.

Tenemos Fase 1 para encontrar el error

Fase2 para corregir el error

- **Fase 1: Pasos para depurar:**

    - Ir al módulo que falla

    - Establecer breakpoints

        - En asignacion de valores

        - Procesamiento de valores

        - Cambio de estados

    - Diseñar una matrix de pruebas

    - Establecer los datos de prueba

    - Comenzar a depurar

## Clase 26 Pruebas de verificación

Las pruebas de verificación sirve para confirmar que un cambio se haya hecho o un defecto se haya corregido. Queremos verificar que lo que estamos buscando está en los requerimientos o documentación.

**Pruebas de verificación**

- Tratan de reproducir el escenario fallido con los dato usados. Pero sería un error usar los mismo datos para después asumir que el error fue corregido.

- Se buscan nuevos escenarios donde se utilicen valores relativos. Como Otras plataformas, otros sistemas operativos, otros exploradores, otros dispositivos

**Pruebas de regresión**

- La matrices de pruebas cuando se implementan otros dispositivos u otros exploradores nos ayuda a tenerlos en cuenta nuestros puntos de verificación para que no sufran un impacto.

- La matrix de prueba nos funciona para casos donde no solo vemos los defectos sino que todo lo que ya funciona siga funcionando.

- Nos ayuda a tener una claridad con los casos de prueba claves que pueden ser automatizados.

**Documentación**

Se procura actualizar la documentación: 

- Comentarios en el código

- Documentación técnica

- Pruebas unitarias

- Pruebas específicas

- Matrices de pruebas

- Plan de pruebas

## Clase 27 Automatización de pruebas

![assets/img62.png](assets/img62.png)

En esta unidad vamos a conocer las bases para la automatización de pruebas y podemos automatizar las siguientes tipos de pruebas.


- **Pruebas unitarias:** Tienen que ver con un pedazo de código que el desarrollador esta codificando, pero no tienen que ver con todo el flujo de negocio y proceso del software.

- **Pruebas de integración:** Cómo hacemos que el conjunto del equipo que libera pedacitos de software funcionen juntos y no hagan defectos adicionales.

- **Pruebas funcionales o de aceptación:** Estas pruebas no necesariamente forman parte de los requerimientos especificados por el cliente, una recomendación para automatizar estas pruebas es que deban cumplir con los requerimientos dados por el cliente.

- **Test Driven Development:** 

    ![assets/img63.png](assets/img63.png)

    El desarrollo va a estar enfocado haciendo primera las pruebas y después el código. Haciendo que el desarollo sea muy específico con la mayor cobertura y no pongamos líneas de código que no van a funcionar o no se usan.

    - Escribimos una prueba

    - Ejecutamos la prueba: Falla

    - Se escribe el código

    - Ejecutamos la prueba: Pasa

- **Behavior Driven Development:** 

    ![assets/img64.png](assets/img64.png)

    Si primero vamos a escribir las pruebas, debemos hacerlo bien y usando un lenguaje sencillo, simple para que la sirva al equipo para entender qué es lo que queremos hacer.

### Clase 28 Gherkin

Gherkin es un lenguaje de texto plano con estructura, usamos palabras que no son comandos pero permiten entender en un modo de pseudocódigo qué es lo que se tiene que hacer. Esta diseñado para ser fácil de aprender y ser entendido por todos.

**Ventajas**

- Simple

- Palabras claves o keywords

- Estandariza los casos de uso

- Reduce el tiempo de diseño

![assets/img65.png](assets/img65.png)

**Ejemplo de uso de Gherkin**

![assets/img66.png](assets/img66.png)

___

## ¿Quieres conocer mas proyectos?

Puedes visualizar mi portafolio en el siguiente enlace https://jeyfredc.github.io/Portafolio/

![assets/img-portafolio.png](assets/img-portafolio.png)
