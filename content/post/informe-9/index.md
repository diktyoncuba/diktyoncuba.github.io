---
title: Informe 9
description: Informe de salud de Internet y censura en Cuba - Segundo trimestre 2026
date: 2026-07-01 00:00:00+0000
image: Diktyon_inf9.png
categories:
    - Informes
    - Informe trimestral
tags:
    - OONI 
    - Zoque Labs
    - DPI
    - Cuba
    - Derechos digitales
    - Monitoreo
---

> [Descargar aquí el Informe 9 completo](https://github.com/diktyoncuba/public/blob/main/Informes/Informe-9_Abr-Jun-2026.pdf)

**Período**: *1 de abril de 2026 - 30 de junio de 2026*

## RESUMEN

Durante el segundo trimestre de 2026, la censura en Internet en Cuba mantuvo un comportamiento estable, sin detectarse nuevos dominios bloqueados ni cambios en los mecanismos técnicos de filtrado. Persistieron las limitaciones estructurales de la conectividad, marcadas por el deterioro de la infraestructura de telecomunicaciones, la exclusión de Cuba del Speedtest Global Index y una reducción del tráfico HTTP durante mayo. El período también estuvo caracterizado por interrupciones de conectividad coincidentes con protestas sociales y por nuevos indicios sobre riesgos para la seguridad de las comunicaciones, ampliando el análisis de Diktyon hacia la vigilancia del ecosistema digital.

## NOSOTROS

Diktyon es un grupo independiente dedicado al monitoreo de la censura digital, la salud de Internet y el estado de la conectividad en Cuba. A través de mediciones técnicas y análisis de datos abiertos, el grupo documenta las restricciones al acceso a la información y las interrupciones en la conectividad que afectan a las personas usuarias dentro de la isla.

El trabajo de Diktyon se basa en el uso de herramientas de medición de red, el análisis de tráfico de Internet y la recopilación de evidencias públicas sobre el comportamiento de la infraestructura digital cubana. Los resultados de estas investigaciones se presentan en informes periódicos cuyo objetivo es ofrecer una visión técnica y documentada sobre el estado de Internet en el país.

Estos informes constituyen una fuente de referencia sobre la evolución de la censura en línea y la estabilidad de la infraestructura de conectividad en Cuba.

En redes sociales: @DiktyonCuba

## INTRODUCCIÓN

El presente informe corresponde a la novena edición de Diktyon y analiza el estado de la censura, la conectividad y la seguridad de las comunicaciones en Cuba durante el segundo trimestre de 2026 (abril-junio). Su objetivo es documentar, mediante evidencia técnica y el análisis de fuentes abiertas, la evolución de los mecanismos de control aplicados sobre la infraestructura nacional de Internet y evaluar su impacto sobre el acceso a la información y el ejercicio de los derechos digitales.

El período analizado estuvo marcado por la persistencia de la crisis energética, el deterioro progresivo de la infraestructura de telecomunicaciones y un contexto de creciente tensión social. Estos factores incidieron tanto en el funcionamiento de la red como en la disponibilidad de los servicios de Internet, dificultando el acceso a las comunicaciones digitales para una parte importante de la población.

Las mediciones realizadas por Diktyon muestran que la arquitectura técnica de censura implementada por el proveedor nacional de acceso a Internet se mantuvo estable durante el trimestre, sin evidencias de cambios significativos en los mecanismos de filtrado ni de incorporación de nuevos dominios al conjunto de sitios bloqueados. No obstante, el análisis permitió obtener nueva evidencia sobre el funcionamiento de la infraestructura de censura, aportando una caracterización más precisa de algunos de los dispositivos y técnicas empleados para restringir el acceso a contenidos en línea.

Además de la censura de contenidos, el informe examina la evolución de indicadores de calidad de la conectividad, la ocurrencia de interrupciones de Internet coincidentes con episodios de protesta social y nuevos elementos relacionados con la seguridad de las comunicaciones. En conjunto, estos hallazgos ofrecen una visión integral del ecosistema digital cubano, donde las limitaciones estructurales de la infraestructura, las restricciones económicas al acceso y los mecanismos de control sobre la red continúan configurando un entorno adverso para el ejercicio de los derechos digitales.

Como en ediciones anteriores, Diktyon combina mediciones técnicas propias con información procedente de plataformas de monitoreo de Internet y de investigaciones independientes. Este enfoque permite documentar de forma sistemática la evolución del ecosistema digital cubano y contribuir a una comprensión más precisa de las dinámicas de censura, conectividad y vigilancia que afectan al país.

## METODOLOGÍA

El presente informe se elaboró a partir del análisis de múltiples fuentes de datos obtenidas entre abril y junio de 2026. La metodología combina mediciones activas de conectividad, análisis de tráfico de red, monitoreo de indicadores públicos sobre el estado de Internet y revisión de información procedente de organizaciones especializadas en medición y seguridad digital.

Las mediciones de censura se realizaron mediante OONI Probe, ejecutando pruebas periódicas desde redes de acceso de ETECSA. Los resultados fueron analizados para identificar evidencias de interferencia en la resolución DNS, bloqueo de conexiones TCP, manipulación del protocolo HTTP y anomalías durante el establecimiento de conexiones TLS, incluyendo filtrado basado en el campo Server Name Indication (SNI). Cuando fue posible, los resultados fueron complementados mediante capturas de tráfico y análisis de paquetes para caracterizar con mayor precisión los mecanismos técnicos de filtrado observados.

La evaluación del rendimiento de Internet se basó en los indicadores publicados por Cloudflare Radar, incluyendo velocidad estimada de descarga, latencia, tiempo de resolución DNS y volumen agregado de tráfico HTTP. Asimismo, se revisó la disponibilidad de datos del Speedtest Global Index de Ookla para contextualizar el comportamiento de las mediciones de desempeño.

El análisis de posibles interrupciones de Internet combinó información procedente de IODA, Cloudflare Radar, reportes públicos de usuarios y medios de comunicación, así como anuncios oficiales relacionados con la infraestructura de telecomunicaciones y el sistema eléctrico nacional. La atribución de un evento como corte deliberado solo se realiza cuando existe evidencia técnica suficiente; en ausencia de esta, los incidentes se describen como interrupciones de conectividad coincidentes con eventos de interés.

La sección dedicada a seguridad y vigilancia incorpora información publicada por organizaciones especializadas, como Zoque Labs, únicamente cuando resulta relevante para comprender la evolución del ecosistema digital cubano. En estos casos, Diktyon distingue claramente entre los resultados derivados de sus propias mediciones y aquellos sustentados en investigaciones de terceros.

Las mediciones reflejan el comportamiento observado desde las redes analizadas durante el período de estudio y no permiten descartar que existan mecanismos de censura o vigilancia adicionales que no hayan sido detectados mediante las pruebas realizadas.

> LIMITACIONES METODOLÓGICAS:

> La ausencia de evidencia de bloqueo no debe interpretarse como evidencia de ausencia de censura. Algunas técnicas de filtrado pueden activarse únicamente bajo determinadas condiciones, ubicaciones geográficas, horarios o perfiles de usuario. Asimismo, ciertos incidentes de conectividad no pueden atribuirse de forma concluyente a acciones deliberadas sin disponer de mediciones activas obtenidas durante el evento.

## HALLAZGOS CLAVE

Durante el segundo trimestre de 2026 se identificaron varios eventos relevantes relacionados con el estado de la seguridad, la censura y la conectividad en Cuba:

1. No se detectaron nuevos dominios censurados durante el segundo trimestre de 2026. Las mediciones confirman la persistencia del mismo conjunto de sitios bloqueados identificado en informes anteriores, sin evidencia de expansión de la lista de censura..

2. La arquitectura técnica de censura permaneció sin cambios, manteniendo mecanismos de filtrado multinivel que incluyen interferencia DNS, inspección del campo SNI en conexiones TLS, técnicas compatibles con Deep Packet Inspection (DPI) y bloqueo selectivo a nivel TCP/IP.

3. Se obtuvo nueva evidencia técnica sobre el funcionamiento del sistema de filtrado, documentándose respuestas HTTP 503 generadas por un dispositivo de filtrado Huawei (V2R2C00-IAE/1.0) que intercepta conexiones HTTPS tras inspeccionar el campo SNI, proporcionando una caracterización más precisa de la infraestructura de censura.

4. La calidad del servicio de Internet continuó siendo deficiente. Cuba volvió a quedar excluida del Speedtest Global Index por insuficiencia de mediciones representativas, mientras Cloudflare Radar registró una velocidad media de descarga de 3,9 Mbps, una latencia de 142 ms y un tiempo medio de resolución DNS de 222 ms.

5. Durante mayo se observó una reducción sostenida del tráfico HTTP nacional, acompañada de una disminución del volumen de búsquedas en Internet, lo que sugiere una menor actividad del ecosistema digital durante ese mes respecto al trimestre anterior.

6. Se registró una interrupción significativa de la conectividad el 14 de mayo, coincidiendo con protestas por los apagones en La Habana. Aunque la evidencia disponible no permite atribuir de forma concluyente el evento a una acción deliberada de censura, su sincronía con las manifestaciones reproduce patrones observados en episodios anteriores y justifica su seguimiento.

7. El trimestre aportó nuevos indicios sobre riesgos para la seguridad de las comunicaciones. La investigación de Zoque Labs documentó un mecanismo de secuestro de cuentas de WhatsApp basado en la interceptación de códigos SMS, lo que amplía el análisis de Diktyon desde la censura hacia posibles capacidades de vigilancia apoyadas en el control centralizado de la infraestructura de telecomunicaciones.

> [Descargar aquí el Informe 9 completo](https://github.com/diktyoncuba/public/blob/main/Informes/Informe-9_Abr-Jun-2026.pdf)

## TECNOLOGÍAS DE CENSURA OBSERVADAS

Las mediciones realizadas durante el periodo analizado no muestran cambios significativos en las técnicas de censura previamente documentadas. Los resultados continúan evidenciando el empleo de múltiples mecanismos de interferencia de red dentro de la infraestructura de telecomunicaciones cubana, lo que indica la persistencia de una arquitectura de filtrado en múltiples capas.

Al igual que en el trimestre anterior, las evidencias recopiladas muestran que el bloqueo de contenidos no depende de un único mecanismo técnico, sino de la combinación de distintas técnicas, entre ellas la interferencia en la resolución de nombres de dominio (DNS), el filtrado basado en la extensión Server Name Indication (SNI) del protocolo TLS, la inspección profunda de paquetes (DPI) y la manipulación selectiva de conexiones TCP.

Durante el periodo no se identificaron nuevas técnicas de censura ni cambios apreciables en el comportamiento de los mecanismos previamente observados. Las técnicas descritas a continuación continúan siendo consistentes con los resultados obtenidos por las mediciones de OONI Probe y el análisis de capturas de tráfico realizadas por Diktyon.

### Filtrado basado en DNS

Las mediciones de OONI Probe muestran anomalías compatibles con interferencia en el proceso de resolución de nombres de dominio (DNS).

En condiciones normales, cuando un usuario intenta acceder a un dominio, su dispositivo consulta un servidor DNS para obtener la dirección IP correspondiente. Sin embargo, en varios de los dominios analizados se detectaron respuestas DNS anómalas que sugieren la existencia de filtrado a este nivel.

Los patrones observados incluyen:
-   respuestas NXDOMAIN para dominios que existen y resuelven correctamente desde redes de control
-   ausencia total de respuesta DNS
-   resoluciones inconsistentes entre distintos resolvers
    
Este tipo de comportamiento puede indicar:
-   manipulación de respuestas DNS por parte del proveedor de acceso  
-   filtrado implementado en resolvers controlados por el operador  
-   redirección hacia servidores DNS interceptores.
    
El filtrado DNS constituye uno de los métodos de censura más simples de implementar, aunque puede ser evadido mediante el uso de resolvers alternativos o servicios DNS cifrados.

### Filtrado basado en SNI (Server Name Indication)

Una de las técnicas de censura más consistentemente observadas en las mediciones corresponde al filtrado basado en la extensión SNI del protocolo TLS.

Durante el establecimiento de una conexión HTTPS, el cliente envía en texto claro el nombre del dominio al que desea conectarse mediante el campo Server Name Indication (SNI) dentro del handshake TLS.

Este campo permite a sistemas de inspección de red identificar el dominio solicitado antes de que se establezca la sesión cifrada.

Las mediciones muestran que en varios dominios censurados:
-   la conexión TCP se establece correctamente
-   el handshake TLS se inicia 
-   pero la conexión se interrumpe inmediatamente después del envío del campo SNI.
    
En muchos casos la interrupción ocurre mediante:
-   paquetes TCP RST
-   cierres abruptos de la sesión
-   timeouts durante el handshake TLS.
    
Este comportamiento es consistente con mecanismos de filtrado basados en inspección de metadatos TLS.

El uso de filtrado SNI es ampliamente documentado en diversos sistemas de censura a nivel mundial, ya que permite bloquear dominios HTTPS sin necesidad de descifrar el contenido del tráfico.

Las capturas de tráfico obtenidas durante las pruebas continúan mostrando un patrón consistente de filtrado basado en SNI. En particular, el análisis de las conexiones hacia [proyectoinventario.org](http://proyectoinventario.org/) confirma que un dispositivo de filtrado identificado como Huawei V2R2C00-IAE/1.0 inspecciona el campo SNI del mensaje TLS Client Hello y, cuando el dominio coincide con una política de bloqueo, responde con una página HTTP 503 en texto plano a través del puerto 443, sin completar el intercambio TLS. Este comportamiento constituye una evidencia directa de interferencia activa a nivel de red y es consistente con el funcionamiento de dispositivos comerciales de inspección y filtrado de tráfico.

El cliente envió un TLS Client Hello legítimo (frame 4) con SNI: proyectoinventario.org. El dispositivo de filtrado lee el SNI, identifica el dominio en su lista de bloqueo, y responde con una página HTTP 503 en texto plano — sin completar ningún handshake TLS, sin Server Hello, sin certificado.

El cliente detectó que la respuesta recibida en el puerto 443 no es TLS válida y emitió un TCP RST (frame 7) para cerrar la conexión abruptamente.

En el caso de las capturas por HTTP queda en evidencia al analizar las cabeceras HTTP de la respuesta de bloqueo:

Cabeceras HTTP de la respuesta de bloqueo (visibles en texto claro):
> HTTP/1.1 503 Service Unavailable
Connection: close
Server: V2R2C00-IAE/1.0
Cache-Control: no-cache, no-store
Content-Type: text/html
Content-Length: 1032

Contenido HTML de la página de bloqueo:
...

Para tráfico HTTP (puerto 80), el sistema de filtrado inspecciona el header Host de la petición HTTP (en texto claro). Si el valor del header Host coincide con una URL en la lista de bloqueo, intercepta la conexión TCP. Devuelve la página 503 con Content-Length: 1032 bytes y cierra la conexión con FIN.

Para tráfico HTTPS (puerto 443), el sistema de filtrado deja pasar el handshake TCP (SYN/SYN-ACK/ACK) normalmente. Espera al TLS Client Hello del cliente, que contiene el SNI en texto claro. Si el SNI coincide con la lista de bloqueo, ignora completamente el protocolo TLS. Devuelve directamente una respuesta HTTP 503 en texto plano a través del puerto 443 — sin certificado, sin Server Hello, sin cifrado. Envía FIN para cerrar la conexión.

...

> [Descargar aquí el Informe 9 completo](https://github.com/diktyoncuba/public/blob/main/Informes/Informe-9_Abr-Jun-2026.pdf)
