---
title: Informe 3
description: Informe de salud de Internet y censura en Cuba - Septiembre a noviembre de 2023
date: 2023-12-01 00:00:00+0000
image: Diktyon_inf3.png
categories:
    - Informes
    - Informe trimestral
tags:
    - OONI 
    - Tor
    - DPI
    - Cuba
    - Derechos digitales
    - Monitoreo
---

> [Descargar aquí el Informe 3 completo](https://github.com/diktyoncuba/public/blob/main/Informes/Informe-3_Sep-Nov-2023.pdf)

**Período**: *1 de septiembre de 2023 - 31 de noviembre de 2023*

## HALLAZGOS CLAVE

Durante nuestro monitoreo en los meses de septiembre, octubre y noviembre de 2023, se encontró que **67** de los 240 dominios examinados, principalmente sitios de noticias y derechos humanos, estaban bloqueados en Cuba. Utilizamos 217 sitios de la lista de CitizenLab para Cuba y agregamos otros 23 con alta probabilidad de bloqueo en la isla para este estudio.

- En Cuba, se bloquearon 49 sitios web utilizando tecnología de **inspección profunda de paquetes (DPI)**, manipulando la transmisión de paquetes.

- En el informe anterior descubrimos que al solicitar la versión **HTTPS** de 12 de los 60 dominios bloqueados, OONI los catalogaba como mediciones fallidas y que en realidad estaban siendo censurados mediante tecnología DPI. Este mes, **hemos agregado 20 dominios** más a esta lista, lo que suma un total de 32 dominios con mediciones fallidas en múltiples ocasiones que en realidad se trata de censura.

Para este informe, utilizamos las herramientas del Observatorio Abierto de Interferencias de la Red (OONI, por sus siglas en inglés): **OONI Probe** para obtener muestras, OONI Explorer para analizarlas y OONI MAT para crear gráficas.

También realizamos capturas de paquetes de tráfico con la herramienta **WireShark** para poder examinar los protocolos en detalle.

> [Descargar aquí el Informe 3 completo](https://github.com/diktyoncuba/public/blob/main/Informes/Informe-3_Sep-Nov-2023.pdf)
