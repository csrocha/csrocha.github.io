---
layout: post
title: "Sobre estrategias para articular mejor la tecnología en tu negocio"
date: 2026-04-30
author: csrocha
audience: "Dueños de empresa"
categories: [estrategia, tecnologia, negocios]
status: published
hilo: tecnologia-negocio
references:
  - christensen-innovators-dilemma
  - conway-committees
  - cunningham-technical-debt
  - vendor-lock-in
  - shadow-it
  - gartner-composable-business
  - kpmg-chatgpt-impact-2023
  - conway-committees
  - kim-phoenix-project
  - forrester-build-buy-partner
  - johnson-adjacent-possible
  - davenport-mission-critical
  - gartner-postmodern-erp
---

*La idea central de este artículo es simple: Confiar la tecnología a terceros equivale a entregar parte del negocio. ¿Estás seguro de lo que estás haciendo?*

---

Quisiera posicionarme en una estrategia de tecnología que considero fundamental para encontrar la mejor versión de un emprendimiento. Lo que voy a comentar no es novedad, sino que es una formalización de muchas prácticas que surgieron en los últimos años y que la literatura empezó a definir con nomenclaturas para poder articularla, pero como todo lo nuevo necesita revisión, una impronta personal y propuestas.

Voy a comenzar por dos estrategias bien definidas en un emprendimiento, empresa, sin importar el tamaño, la antigüedad, el sector o la facturación: **comprar** y **construir**.

En el mundo del software *comprar* implica varias formas de contratos: *licenciado* — un pago y adueñarse de una copia —, como *servicio* — pagos mensuales fijos y contratos de confidencialidad y uso -, o *código libre* — podés hacer lo que quieras con él, pero cero responsabilidad para el desarrollador —. 

Y la tendencia actual es clara en la industria, se deja de lado el único pago y se busca garantizar un flujo mensual. *(Forrester Research)* Esto no es un resultado únicamente económico, sino que es la evolución de años de versiones, actualizaciones, compromisos de calidad y mantenimientos difíciles de satisfacer. Las empresas de software ya no quieren arriesgar, y lo mismo ocurre con sus clientes.

Y *construir* no significa escapar de comprar; pero permite huir de una cárcel de funcionalidades predeterminadas *(Vendor Lock-in)* y acceder a capacidades y recursos que resultan inimaginables si no hay un *equipo de desarrollo* **in-house** capaz de orquestarlo. El software libre, las APIs y las soluciones serverless lo hacen posible y son parte de la "navaja suiza" de la nueva era. *(Christensen, 1997)*

## El reinicio de LEGO

Cada día se lanzan nuevas propuestas en el mercado orientadas a las necesidades del negocio, tomando como producto funcionalidades que podríamos llamar **atómicas**: envío de email, llamadas telefónicas, bases de datos, páginas web *(Gartner, 2020)*. Pero esas funciones atómicas no son atractivas sin una experiencia de usuario clara y amable, por lo que los proveedores integran servicios solapados:

Mailchimp gestiona listas de suscriptores junto a su servicio de envío masivo. Salesforce integra la bandeja de entrada con el seguimiento de clientes, pero no se especializa en campañas de email masivo.

Y así podemos listar miles de herramientas. Un ejemplo claro es OpenAI, que no logró convencer a nadie sobre el uso de sus modelos de lenguaje hasta que publicaron ChatGPT *(KPMG, 2023)*. Pero integrar todo eso depende de una parte del negocio que el proveedor no considera su fuerte. Si se quiere aprovechar al 100% sus virtudes, se necesita alguien capaz de entender esas tecnologías para integrarlas: un equipo que sepa construir la herramienta perfecta a partir de esas piezas de LEGO.

## Volviendo al futuro

Tener personal de tecnología puede ser un problema de recursos humanos, pero el mayor de los problemas es la confianza: ¿cómo es posible que un software creado por un equipo interno logre mejores resultados que uno cerrado? ¿Acaso el software enlatado no está preparado para tu industria? ¿Por qué elegir una tecnología sobre otra?

Hay decisiones que un zapatero, un albañil, o un administrador de empresas no tienen por qué tomar, al menos no fueron entrenados en eso: es un mundo que no les concierne bajo las expectativas de lo que es el negocio. Pero la realidad es clara, no hay sector donde la informática no deje su impronta.

Para entender adónde estamos debemos viajar al pasado, al menos unos 20 años. Es aquí donde muchos tuvieron pésimas experiencias implementando "enlatados" y buscaron "informáticos" en sobrinos, hijos o vecinos *(Shadow IT)* — soluciones a lo que no podían tener acceso, ya sea por el costo de su puesta a punto, o simplemente porque no abarcaba sus necesidades reales.

Usar una planilla de cálculo se transformó en una de las soluciones más adoptadas, y lo que cada empresa construía con ella era su diferencial ante la competencia. Pero no tardaron en quedar cortas; quedaron aisladas de todo el proceso productivo, ventas y contabilidad.

Los **ERP** se suponían que venían a solucionar muchos de los problemas con una visión integral, pero terminaron centrándose, en la práctica, en soluciones contables, perdiendo la universalidad de su ER: *Enterprise Resources*. *(Davenport, 2000; Gartner, 2014)* Y es por ello que surgieron los **CRM**, y luego Websites o Carritos de Compras, Dashboards y más. No queda otro camino: lo que hay ahora en el mercado no son balas de plata, son parches que conforman **biomas aislados** en un ecosistema tecnológico cada vez más difícil de llevar. *(Cunningham, 1992)*

Y terminamos en un equipo de tecnología que en principio administra ese ecosistema. Pero surgen ideas, necesidades que ningún enlatado logra satisfacer al 100% porque se trata de una integración o un pequeño cambio de paradigma en la forma de trabajar.

La solución en esos casos es un desarrollo, y aquí viene el dilema que nos compete: ¿lo implementa el equipo que contratamos o tercerizamos? Mi respuesta es clara: hay que delegar la responsabilidad al equipo de tecnología. Las razones son varias, pero esto va a depender de si se está listo para dar un paso al frente en el desarrollo in-house, un camino lleno de crisis y aprendizajes que, desde mi punto de vista, vale la pena transitar.

No importa que seas una entidad sin fines de lucro, una cooperativa, una pequeña o mediana empresa: si se quiere dar un salto siempre te vas a encontrar con que la automatización de procesos, la comunicación interna y la exposición al público están condicionadas a la tecnología. El hecho de que los empleados trabajen menos, por el mismo sueldo, no implica ser menos productivos — es ser al menos igual de productivos y acceder a tiempos de rediseño y optimización que no puede conseguirse manteniendo los procesos tal como estaban hace varios años.

## Externalización vs ad-hoc vs in-house

Cuando algo no funciona en el negocio, el primer impulso es buscar a alguien que lo resuelva. Un recomendado, un consultor, alguien que "sabe de tecnología". Y ese alguien va a llegar con buena voluntad y conocimiento genuino — pero general. No porque sea incompetente, sino porque lo que ocurre adentro de cada empresa solo lo conocen los que están ahí día a día, metidos en el proceso.

El problema es que ni siquiera los que están adentro siempre pueden explicarlo. Saben qué pasa — lo sienten, lo viven — pero no necesariamente pueden articularlo de forma que otro lo pueda implementar. Hay una diferencia enorme entre tener el conocimiento incorporado en el cuerpo y poder transferirlo.

Y hay un tercer nivel, más profundo todavía: entender un problema no es lo mismo que conocerlo en profundidad. Para automatizar un proceso no alcanza con comprenderlo a grandes rasgos — hay que sumergirse hasta el fondo, hasta donde están las excepciones, los casos raros, las decisiones que se toman casi sin pensar porque "siempre se hizo así". Ese nivel de profundidad no se alcanza en una reunión de relevamiento. Se alcanza de dos formas: con una capacidad analítica excepcional, o a los golpes.

De ahí viene una ventaja que se subestima constantemente: una persona de tecnología dentro de la empresa — aunque sea una sola, aunque sea junior — que lleva seis meses trabajando codo a codo con los equipos, tiene más chances de encontrar la solución correcta que cualquier consultor externo. No porque sea más inteligente, sino porque acumuló algo que no se puede comprar: **contexto**. *(Kim et al., 2013)*

Sabe por qué se hace lo que se hace, conoce las excepciones que nunca están en ningún documento, y puede adaptar tanto la solución al negocio como el negocio a la solución. Esa doble capacidad de adaptación es el primer valor del equipo interno.

Aquellos que vean muy grande el riesgo apostarán primero por la **externalización**. Delegan las decisiones en un tercero y confían plenamente en la solución que este aporta. El concepto **"llave en mano"** es lo que se verá en la punta del iceberg. Pero debajo del límite de flotación empieza a aparecer la necesidad de adaptar el negocio con el software, los requisitos mal relevados, ya sea por no entender el negocio o por no ser exhaustivo.

Del otro lado están quienes se atreven a construir su propia planilla de cálculo. Diseñar y programar esa herramienta está del lado del in-house, incluso para un neófito. Y desde ahí se puede dar un salto tecnológico grande codificando el software de punta a punta.

De aquí surge un abanico de soluciones donde en el otro extremo aparecen las personalizaciones, ya sea porque el proveedor está dispuesto a modificar su herramienta, o porque hay un core diseñado para modificarse y así llegar a la personalización por medio de la consultoría.

También se puede ir en búsqueda de un punto intermedio, algo que no obligue a modificar los flujos y planes existentes. Si se terceriza la tecnología con una visión de negocio propia, se busca adaptar el software al negocio, y eso es un desarrollo **ad-hoc**. El proceso va a ser más largo que un desarrollo in-house. Y si lo que se quiere hacer es algo novedoso - lamento decir que muy pocas soluciones son novedosas, excepto que se esté en los límites de la tecnología *(Christensen, 1997; Johnson, 2010)* -, eso solo se puede hacer si el desarrollo es in-house. *(Forrester Research)*

Otra dimensión a tener en cuenta es dónde se aplica este enfoque, porque puede ocurrir que en diferentes departamentos los directivos tengan visiones distintas y adopten modelos diferentes. Esa convivencia de visiones dentro de una misma empresa tiene un resultado que merece su propio análisis: genera ecosistemas tecnológicos fragmentados, con biomas que crecen sin comunicarse *(Conway, 1968)*. Eso es materia del próximo artículo.

## Caer en un rio lleno de rocas

La industria del software arrastra prejuicios que tienen nombre propio: gente difícil de tratar, tiempos que se estiran, costos difíciles de justificar. Nacieron de malas experiencias reales — muchas de hace 20 años — y todavía pesan en cada conversación comercial.

El consultor externo llega sin contexto y necesita vender antes de entender. La única forma de cerrar es simplificar el problema. El conflicto con el cliente llega después, cuando la realidad del negocio aplasta lo que se prometió. Y si hay un equipo de ventas de por medio, la disputa se vuelve también interna: lo que se comprometió contra lo que es posible entregar.

De mis experiencias, que puedo contar con los dedos de una mano, solo dos fueron aceptadas con plena convicción, y solo una se puso en producción y todavía se sigue usando con todo orgullo. El resto, mejor olvidar. Con respecto a mi integración a empresas de diversos rubros, donde puse mi grano de arena, puedo decir que todos mis aportes están en producción o lo estuvieron un largo tiempo.

---

## Conclusión

No hay una respuesta universal entre comprar y construir. Hay una que es correcta para cada empresa en cada momento. Lo que sí es universal: no tomar esa decisión conscientemente es la peor decisión posible. El dueño que cede la tecnología sin entender qué entrega, pierde también parte del control de su negocio. La tecnología no es el departamento de sistemas — es el sistema nervioso de la empresa. *(Kim et al., 2013)*

---

## Acciones y recomendaciones

La primera acción no es técnica. Es sentarse con el equipo de IT — sin agenda, sin resultados esperados — y hablar. De la situación actual, de cómo ven el futuro de la compañía, de qué les preocupa y qué ven posible. Sin prejuicios de ningún lado. Con la única intención de que emerja una dirección donde la automatización libere tiempo para la innovación.

Es la primera acción porque todo lo demás depende de ella. Sin esa conversación, cualquier decisión tecnológica — comprar, construir, tercerizar — se toma a ciegas. El equipo de IT tiene información que no aparece en ningún reporte.

En esa misma conversación, o en una siguiente, empezar a identificar qué parte de lo que surgió se puede resolver in-house y qué hay que buscar afuera. No hace falta que sea exhaustivo ni preciso — va a marear, y está bien. La clave es anotarlo todo. Ese registro, aunque parezca caótico, va a ser el insumo más valioso para los próximos pasos.

El objetivo no es llegar a conclusiones todavía. Es iniciar una dinámica donde el equipo de IT salga de su rol de ejecutor de tickets y empiece a buscar problemas y proponer soluciones. Que se integre con el resto de la empresa no como soporte, sino como parte de la comunidad que construye el negocio.

Este es un momento de flotar en miles de ideas. La priorización viene después. Lo que nunca se hace es descartar — una idea que hoy parece imposible puede ser la más importante en seis meses, cuando el contexto cambie o aparezca la herramienta correcta para llevarla adelante.

---

Lo que pase después depende de ellos — del equipo de IT, de su disposición, de sus ideas. Y depende de uno, de la capacidad de escuchar y de aceptar propuestas que quizás no se entendía que eran posibles.

No es tiempo perdido. Es pensar un poco más lejos, pero actuando ya.

---

## Referencias y lecturas recomendadas

- Christensen, C. M. (1997). *The Innovator's Dilemma*. Harvard Business School Press.
- Johnson, S. (2010). *Where Good Ideas Come From: The Natural History of Innovation*. Riverhead Books.
- Conway, M. E. (1968). How Do Committees Invent? *Datamation*, 14(4), 28–31.
- Kim, G., Behr, K., & Spafford, G. (2013). *The Phoenix Project*. IT Revolution Press.
- Forrester Research. *The Build-Buy-Partner Spectrum*.
- Cunningham, W. (1992). The WyCash Portfolio Management System. *OOPSLA '92 Experience Report*.
- Davenport, T. H. (2000). *Mission Critical: Realizing the Promise of Enterprise Systems*. Harvard Business Press.
- Gartner. (2014). *Postmodern ERP*.
- Gartner. (2020). *The Future of Business is Composable*.
- KPMG. (2023). *The potential impact of ChatGPT and the new AI on business*.
- **Vendor Lock-in**: Situación en que el costo de cambiar de proveedor es tan alto que el cliente queda atrapado, independientemente de la calidad del servicio.
- **Shadow IT**: Uso de sistemas sin aprobación explícita del departamento de TI — síntoma de que el equipo necesita herramientas ágiles que la empresa no provee de forma oficial.
