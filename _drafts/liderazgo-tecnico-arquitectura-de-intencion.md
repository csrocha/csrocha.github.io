---
layout: post
title: "Liderazgo técnico: arquitectura de intención"
author: csrocha
audience: "Líderes de tecnología y CTOs de PyMEs"
status: draft
hilo: "El líder técnico que no programa pierde el pulso de la realidad. La arquitectura del software refleja la salud del equipo."
fuentes:
  - IDEA: Liderazgo como Arquitectura de Intención
  - IDEA: Pensar 5 pasos adelante (anécdota Borland/Microsoft)
  - IDEA: Qué delegar y qué no (autenticación, UX, datos federados)
  - NOTE: Ley de Conway
---

<!--
  HILO CONDUCTOR:
  El líder técnico que no programa pierde el pulso de la realidad.
  La arquitectura del software refleja la salud comunicacional del equipo.
  Este artículo es el más técnico de la serie — cambia de público.
  Acá le hablamos al líder de IT, no solo al dueño del negocio.
-->

## Introducción

<!--
  Abrir con la tensión clásica del líder técnico que asciende y deja de programar.
  Se convierte en coordinador, facilitador, gestor de reuniones.
  Y pierde el pulso de lo que realmente está pasando en el código.
  La pregunta central: ¿puede liderar bien quien no hace?
-->

## Desarrollo

### Liderazgo como arquitectura de intención

<!--
  IDEA: El liderazgo en tecnología no es una tarea administrativa.
  Es una labor de mentoría técnica y estratégica donde el involucramiento — 
  incluso el acto de programar — es vital para no perder el pulso de la realidad operativa.
  El líder debe construir junto al equipo, proveyendo herramientas técnicas, 
  estratégicas y emocionales que impactan directamente en la calidad del código.
  La arquitectura del software es un reflejo inevitable de la salud comunicacional del grupo.
  Cuando la patología es organizacional, no se debe "medicalizar" al equipo con reuniones infinitas
  que solo generan felicidad sin producción.
  Se debe intervenir desde la trinchera, asegurando que el equipo tenga claridad y pragmatismo
  para que cada línea de código responda a una intención del negocio.
-->

### La Ley de Conway: tu empresa se refleja en tu software

<!--
  NOTE - Conway (1968): "Las organizaciones que diseñan sistemas están condenadas a producir 
  diseños que son copias de las estructuras de comunicación de esas organizaciones."
  Si tu empresa es ágil, tu software debe ser construido ágilmente.
  Si comprás un software rígido, tu empresa se vuelve rígida.
  Si tu equipo no se comunica bien, tu arquitectura va a tener los mismos silos 
  que tienen tus departamentos.
  Desarrollar con ejemplos concretos de cómo la estructura organizacional aparece en el código.
-->

### Pensar cinco pasos adelante sin perder el rumbo

<!--
  IDEA personal: Al comienzo como desarrollador, encontrar en la documentación de Microsoft o Borland
  recomendaciones sobre cómo usar una u otra función para tal o cual funcionalidad.
  Eso dejó una huella: se puede pensar 5 pasos adelante sin perder el rumbo.
  El resultado fue ser lento pero preciso: preparar todo para lo que seguramente iba a venir.
  Y el resultado siempre fue ser más efectivo en el futuro.
  Desarrollar esto como filosofía de diseño, no como perfeccionismo:
  la diferencia entre anticipar y paralizarse.
-->

### Qué delegar y qué no: las reglas del negocio son tuyas

<!--
  IDEA: La charla sobre si integrar dos plataformas es programar o se puede delegar.
  Caso concreto: autenticación de usuario — validar correo y teléfono.
  Principio: si hay un servicio de validación de un dato federado del cual tenés responsabilidad,
  no deberías delegar esa acción. Esa integración la tenés que implementar vos.
  Eso no significa no usar servicios de terceros para enviar mail o SMS.
  El criterio: ¿la responsabilidad sobre ese dato es tuya? Entonces la implementación también.
  UX como argumento adicional: saltar de dominio en dominio para dar un servicio 
  es mala experiencia y genera desconfianza.
  Conectar con la idea del artículo 0: in-house elimina riesgos a la hora de delegar 
  reglas del negocio. Así lo entendió JPMorgan.
-->

### El software propio como activo: más allá del negocio original

<!--
  IDEA: El software que se desarrolla puede desacoplarse del negocio y compartirse con el mundo,
  ya sea vendiéndolo o entregándolo como software libre.
  Amazon no nació como empresa de tecnología — hoy AWS es su negocio más rentable.
  Mercado Libre hace lo mismo con Mercado Pago y Mercado Envíos.
  Ninguna de las dos es "una empresa de software" en su origen.
  Pero ambas desarrollan tecnología que exponen al mundo y explotan inteligentemente
  en nichos de negocios que antes no existían.
  Para el líder técnico: cada decisión de arquitectura es también una decisión estratégica
  sobre qué puede convertirse en activo futuro.
-->

## Conclusión

<!--
  El liderazgo técnico efectivo no es gestión — es presencia.
  Presencia en el código, en el diseño, en las decisiones pequeñas que definen 
  la arquitectura real del sistema.
  Un líder que no programa no lidera tecnología — administra tecnología.
  Y hay una diferencia enorme entre las dos cosas.
-->

## Acciones y recomendaciones

<!--
  1. Reservar tiempo semanal para programar, aunque sea poco — mantener el pulso técnico.
  2. Antes de cada decisión de arquitectura, preguntarse: ¿refleja cómo queremos trabajar 
     o refleja cómo estamos trabajando mal?
  3. Mapear qué integraciones involucran datos o responsabilidades propias — esas no se delegan.
  4. Identificar qué componentes del sistema actual podrían desacoplarse y tener vida propia.
  5. Revisar la Ley de Conway en tu equipo: ¿los silos del código coinciden con los silos del equipo?
-->
