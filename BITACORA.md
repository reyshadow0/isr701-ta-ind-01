# Bitácora — TA-IND-01

Una entrada por cada día trabajado, con la fecha y lo que coincide con los commits de ese día.

<!--
Formato de cada entrada (copiar y llenar):

## AAAA-MM-DD

- **Qué hice:**
- **Problema:**
- **Solución:**
- **Tiempo:**
-->

## 2026-11-11

- **Qué hice:** Leí la guía de la tarea. Comparé algunas opciones de sistema para contrastar con Discord y elegí Matrix, porque también es una plataforma de mensajería, pero con arquitectura federada, mientras que Discord es centralizado. Subí la carátula al SGA, armé la estructura del informe e hice el primer commit.
- **Problema:** No encontré ningun dato donde diga que Discord fuera mi sistema. Además, la tarea aparecía como grupal.
- **Solución:** Dejé un mensaje para el día siguiente hablar con el docente para consultarle las dos cosas.
- **Tiempo:** 2 h (aprox.)

## 2026-11-12

- **Qué hice:** Volví a subir la carátula porque la tarea pasó a ser individual. Hice a mano el esquema de Discord.
- **Problema:** El cierre de la tarea se adelantó al sábado. También el esquema tenía datos que no tenia en mis fuentes.
- **Solución:** Reorganicé los días que me quedan para entregar el sábado. En el esquema en papel marqué con «?» lo que no tenía fuente.
- **Tiempo:** 2 h 20 min (aprox.)

## 2026-11-13

- **Qué hice:** Tomé las capturas de Discord web: la conexión WebSocket con la gateway y el envío de un mensaje por la API. Levanté en Docker un clúster de 3 nodos de ScyllaDB, creé la tabla de mensajes e hice el experimento de ONE contra QUORUM: latencia, un nodo caído, dos nodos caídos y recuperación. También busque y agregue referencias de Matrix.
- **Problema:** En el experimento repetí un comando con la flecha ↑ y el estado con dos nodos caídos se guardó en el archivo 04, que era el de un nodo caído. Además, la latencia no quedó clara: con 3 corridas el promedio dice que ONE es más rápido y la mediana dice lo contrario.
- **Solución:** Dejé en el archivo 04 el bloque porque es la salida real. Con la latencia vi que, con solo 3 corridas en la misma PC, la diferencia es tan pequeña que se pierde en el ruido.
- **Tiempo:** 1 h 30 min (aprox.)
