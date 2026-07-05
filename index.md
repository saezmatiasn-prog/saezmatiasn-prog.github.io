---
title: "Cuando el equipo no se pone de acuerdo: elegir un proveedor de rutas de entrega"
date: 2026-07-01
tags: [logística, trabajo-en-equipo, feedback, post-mortem]
---

# Cuando el equipo no se pone de acuerdo: elegir un proveedor de rutas de entrega

## Contexto

Trabajo en el equipo técnico de una operación de logística, donde estábamos evaluando integrar un proveedor externo de optimización de rutas de entrega para reducir tiempos de despacho y costos de combustible. Teníamos dos candidatos sobre la mesa:

- **Proveedor A**: mejor documentación, soporte dedicado y una integración más simple, pero más costoso y con riesgo de dependencia (vendor lock-in).
- **Proveedor B**: más económico, con una API abierta y flexible, pero con una integración más compleja y menos casos de uso comprobados en nuestra escala.

## Problema

El equipo se dividió en dos posturas. Un grupo priorizaba velocidad de implementación y estabilidad, y defendía al Proveedor A. Otro grupo priorizaba costo y flexibilidad a largo plazo, y defendía al Proveedor B. No teníamos un proceso claro para tomar la decisión, y las conversaciones se volvieron repetitivas: cada bando presentaba argumentos a favor de su opción sin realmente escuchar los riesgos que el otro bando señalaba.

Esto generó dos problemas concretos:
1. La decisión se retrasó casi dos semanas, afectando el cronograma del proyecto.
2. Empezó a notarse fricción en las reuniones de equipo, con comentarios pasivo-agresivos en lugar de discusión técnica directa.

## Acciones

Decidimos frenar la discusión abierta y aplicar un proceso más estructurado:

1. **Feedback radicalmente sincero**: organizamos una reunión donde cada persona expuso su posición con datos concretos (costos proyectados a 12 meses, tiempos estimados de integración, riesgos técnicos), y donde se pidió explícitamente decir lo que se pensaba, incluso si era incómodo, pero siempre con la intención de ayudar a decidir mejor, no de "ganar" la discusión.
2. **Post-mortem constructivo del proceso de decisión**: analizamos por qué nos habíamos estancado, sin buscar culpables. Identificamos que faltaban criterios de decisión acordados desde el inicio.
3. **Definición de criterios objetivos**: en conjunto, definimos qué pesaba más (costo, tiempo de integración, riesgo, escalabilidad) y le dimos un puntaje a cada proveedor según esos criterios.
4. **Piloto acotado**: en lugar de comprometernos de inmediato, acordamos correr un piloto de dos semanas con el Proveedor B, con métricas claras de éxito, antes de tomar la decisión final.

## Aprendizajes

- **Definir criterios de decisión *antes* de evaluar opciones** evita que la discusión se convierta en una defensa de posturas personales.
- **El feedback directo y a tiempo previene la acumulación de tensión.** Esperar a que el desacuerdo "se resuelva solo" solo lo empeora.
- **Un post-mortem no es solo para incidentes técnicos.** También sirve para revisar procesos de decisión de equipo y mejorar cómo trabajamos juntos.
- **Un piloto acotado reduce el riesgo de decisiones irreversibles** cuando hay incertidumbre real entre opciones.

## Evidencia de control de versiones

- Repositorio: [saezmatiasn-prog.github.io](https://github.com/saezmatiasn-prog/saezmatiasn-prog.github.io)
- Commit inicial (creación del blog): [ver commit](https://github.com/saezmatiasn-prog/saezmatiasn-prog.github.io/commit/ce4eab498f68a5d59330322db3ea7c0e3621de24)
- Commit de mejora visual (tema oscuro): [ver commit](https://github.com/saezmatiasn-prog/saezmatiasn-prog.github.io/commit/030ac1a053ca3fc41cd8449c2b0ba1cc16d40362)

## Reflexión sobre feedback radicalmente sincero

Aplicar feedback radicalmente sincero en este proceso significó decir abiertamente "creo que estamos priorizando velocidad sobre lo correcto" o "creo que estamos subestimando el riesgo de este proveedor", sin suavizar el mensaje pero cuidando el tono y la intención. Lo más difícil no fue decir lo que pensaba, sino asegurarme de que la otra persona sintiera que mi objetivo era llegar a la mejor decisión para el equipo, no imponer mi punto de vista. Esa distinción cambió por completo cómo se recibió el feedback y qué tan rápido pudimos avanzar.
