---
title: Informe 10
description: Informe de salud de Internet y censura en Cuba - Tercer trimestre 2026
date: 2026-10-01 00:00:00+0000
image: Diktyon_inf10.png
categories:
    - Informes
    - Informe trimestral
tags:
    - OONI
    - DPI
    - Cuba
    - Derechos digitales
    - Monitoreo
weight: 1       # You can add weight to some posts to override the default sorting (date descending)
---

> [Descargar aquí el Informe 10 completo](https://github.com/diktyoncuba/public/blob/main/Informes/Informe-10_Jul-Sept-2026.pdf)

**Período**: *1 de julio de 2026 - 30 de septiembre de 2026*

## RESUMEN

Durante el tercer trimestre de 2026, Cuba registró cinco colapsos nacionales del Sistema Electroenergético Nacional (SEN) y una desconexión regional en el oriente del país, todos con caídas severas del tráfico de Internet. A mediados de septiembre se observó además un comportamiento inusual en el acceso a sitios históricamente bloqueados: dominios que durante años aparecían censurados pasaron a mostrarse accesibles de forma intermitente, con diferencias entre la red ADSL (Nauta Hogar) y la red de datos móviles. La evidencia disponible no permite determinar si se trata de un levantamiento deliberado de bloqueos, de cambios en las reglas de filtrado o de efectos de la degradación de la infraestructura. Los indicadores de calidad de la conectividad se mantuvieron en niveles bajos y Cuba continuó sin aparecer en el Speedtest Global Index de Ookla.

## INTRODUCCIÓN

El presente informe corresponde a la décima edición de Diktyon y analiza el estado de la censura, la conectividad y la calidad de Internet en Cuba durante el tercer trimestre de 2026 (julio-septiembre). Como en ediciones anteriores, el objetivo es documentar con evidencia técnica verificable lo que ocurre en la red cubana, de modo que periodistas, organizaciones de derechos humanos, investigadoras y la propia ciudadanía dispongan de información independiente.
El trimestre se lee mejor a la luz de los dos informes previos. El Informe 8 documentó los colapsos eléctricos de marzo, entre ellos el apagón de Internet de 30,4 horas del 16 de marzo. El Informe 9 describió después un período de estabilidad en la arquitectura de censura: no se detectaron nuevos dominios bloqueados ni cambios en las técnicas de filtrado, mientras la infraestructura de telecomunicaciones seguía deteriorándose por la crisis energética y se registraba un corte coincidente con protestas el 14 de mayo.
El tercer trimestre rompe en parte ese patrón. Por un lado, los colapsos del Sistema Eléctrico Nacional (SEN) se repitieron con una frecuencia inusual: tres nacionales en apenas nueve días en julio (6, 10 y 14), otro entre el 2 y el 4 de agosto y uno más el 18 de septiembre, además de una desconexión regional en el oriente el 27 de agosto. Estos eventos provocaron caídas del tráfico de Internet de entre el 58 % y el 84 %, y el 18 de septiembre la propia ETECSA reconoció que la mayor parte de sus radiobases había quedado fuera de servicio. Por otro lado, a mediados de septiembre aparecieron señales de que parte de los sitios históricamente bloqueados podían volver a ser accesibles desde redes cubanas, aunque de manera irregular y sin que los datos disponibles permitan hablar de un desbloqueo definitivo.
El informe se organiza en torno a esos dos ejes. Primero se documenta y analiza la accesibilidad irregular de sitios previamente censurados, con el cuidado necesario para no atribuir intenciones sin evidencia y con una comparación con el episodio de desbloqueo temporal de 2024 recogido en el Informe 6. Después se examinan los cortes de Internet del trimestre, con una cronología de eventos, su duración aproximada y el impacto sobre el tráfico. Se completa con las secciones habituales: tecnologías de censura observadas, estado de los 75 dominios monitoreados y calidad del servicio según Cloudflare Radar y Ookla.
Conviene advertir desde el inicio que algunas de las mediciones de este trimestre son más difíciles de interpretar que las de ediciones anteriores. El comportamiento irregular de los sitios, el bajo volumen de mediciones públicas y la lenta recuperación del tráfico tras cada apagón limitan la precisión con la que pueden fijarse fechas, duraciones y causas. Por ello, el informe distingue siempre entre lo que los datos muestran, lo que sugieren y lo que aún queda por comprobar. Las limitaciones metodológicas se detallan en la sección correspondiente.
