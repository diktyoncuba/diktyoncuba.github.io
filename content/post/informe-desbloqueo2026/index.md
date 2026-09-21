---
title: Informe sobre el desbloqueo de sitios web en Cuba
description: Informe sobre los desbloqueos de censura de sitios web - Septiembre 2026
date: 2026-09-21 00:00:00+0000
image: broken-chains.png
categories:
    - Informes
tags:
    - OONI 
    - DPI
    - Cuba
    - Monitoreo
weight: 1       # You can add weight to some posts to override the default sorting (date descending)
---

> [Descargar aquí este informe](https://github.com/diktyoncuba/public/blob/main/Extras/20260921-Desbloqueos_sept_2026.pdf)

## Lo que está ocurriendo

Desde el 16 de septiembre de 2026, múltiples sitios web de noticias y organizaciones críticas con el gobierno cubano se han vuelto accesibles desde la isla sin necesidad de VPN. Este hecho sugiere un desbloqueo masivo de páginas previamente censuradas, lo que representa un cambio significativo en la política de control de información en Cuba.

## Listado de sitios desbloqueados

Entre los portales que ahora se pueden visitar libremente se encuentran:

- 14ymedio
- CiberCuba
- Cubanet
- Diario de Cuba
- Cubaencuentro
- ADN Cuba
- Martí Noticias
- Rialta
- El Toque
- Revista El Estornudo
- Delta Chat y Support Delta Chat
- Además de otros medios internacionales como Univisión, VOA News, Libertad Digital, América TeVe, Freedom House, OAS, entre otros.
*(Se adjunta listado completo en anexo)*

## Evidencia técnica (OONI)

Las mediciones de OONI Explorer realizadas entre el 17 y 19 de septiembre de 2026 confirman que estos sitios son accesibles desde redes cubanas. Ejemplos de pruebas:

- [Medición 1](https://explorer.ooni.org/m/20260919144222.458323_CU_webconnectivity_a22b97e7d51d7759?webview=true&language=en-US) 
- [Medición 2](https://explorer.ooni.org/m/20260919144204.686413_CU_webconnectivity_01b7c6dc2637c44e?webview=true&language=en-US)
- [Medición 3](https://explorer.ooni.org/m/20260919144212.440180_CU_webconnectivity_4cc4ab753a74e5c6?webview=true&language=en-US)

Los resultados muestran conectividad normal y ausencia de bloqueos por DNS, TCP/IP o HTTP, lo que respalda la hipótesis de un levantamiento de la censura.

## Cronología

1. 16 de septiembre de 2026: Usuarios reportan acceso libre a sitios previamente bloqueados.

2. 17 de septiembre de 2026: OONI registra las primeras mediciones confirmando el desbloqueo.

3. 19 de septiembre de 2026: Se amplía la lista de sitios accesibles, incluyendo medios internacionales y organizaciones de derechos humanos.

## Coincidencia regional

Este fenómeno coincide con un proceso similar en Venezuela, donde en las mismas fechas se reportó el desbloqueo de portales informativos que llevaban años censurados. La simultaneidad sugiere una estrategia regional coordinada o un cambio de política en materia de control de información.

> [Ver enlace a publicación de VeSinFiltro](https://x.com/vesinfiltro/status/2100703544118849557)

## Conclusiones

- El desbloqueo masivo de sitios críticos en Cuba representa un cambio sin precedentes en la política de censura digital.
- Las pruebas de OONI confirman la accesibilidad real desde redes locales.
- La coincidencia con Venezuela refuerza la hipótesis de un ajuste regional en las prácticas de control informativo.
- Se recomienda monitorear continuamente la situación para verificar si el desbloqueo es permanente o temporal.

## ANEXO

### Listado de sitios a los que se les ha retirado la censura en Cuba


*Leyenda*
| Código | Descripción |
|---------|-------------|
| NEWS | Sitios de noticias |
| HUMR | Sitios de derechos humanos |
| POLR | Sitios críticos con el gobierno |
| REL | Sitios relacionados con la religión |
| ANON | Herramientas de elusión y anonimización |
| COMT | Herramientas de comunicación |
| ACT | Sitios relacionados con el activismo |
| TUR | Sitios relacionados con el turismo |
| CULTR | Sitios relacionados con la cultura |
| ALDR | Alcohol y drogas |
| SRCH | Motores de búsqueda |
| 11S | Temática 11S |

*Sitios. Fuente: Diktyon (2026).*
| # | Dominio | Categoría | Mediciones |
|---:|---|---|---|
| 1 | gatopardo.com | NEWS | https://explorer.ooni.org/m/20260919144041.998243_CU_webconnectivity_dfe3c035e20b2e72?webview=true&language=en-US |
| 2 | 14ymedio.com | NEWS | https://explorer.ooni.org/m/20260919144204.686413_CU_webconnectivity_01b7c6dc2637c44e?webview=true&language=en-US |
| 3 | cibercuba.com | NEWS | https://explorer.ooni.org/m/20260919144212.440180_CU_webconnectivity_4cc4ab753a74e5c6?webview=true&language=en-US |
| 4 | cubanet.org | NEWS | https://explorer.ooni.org/m/20260919144222.458323_CU_webconnectivity_a22b97e7d51d7759?webview=true&language=en-US |
| 5 | diariodecuba.com | NEWS | https://explorer.ooni.org/m/20260919145827.586893_CU_webconnectivity_c072f2419cab2039?webview=true&language=en-US |
| 6 | cubaencuentro.com | NEWS | |
| 7 | periodicocubano.com | NEWS | https://explorer.ooni.org/m/20260919150509.587116_CU_webconnectivity_697453e1c4e33e94?webview=true&language=en-US |
| 8 | univision.com | NEWS | |
| 9 | asere.com | NEWS | |
| 10 | cubanosporelmundo.com | NEWS | |
| 11 | rialta.org | NEWS | |
| 12 | adncuba.com | NEWS | https://explorer.ooni.org/m/20260919150931.458616_CU_webconnectivity_6a3116d6d6f51869?webview=true&language=en-US |
| 13 | martinoticias.com | NEWS | |
| 14 | libertaddigital.com | NEWS | |
| 15 | cafefuerte.com | NEWS | |
| 16 | voanews.com | NEWS | |
| 17 | cubaenmiami.com | NEWS | |
| 18 | cubanology.com | NEWS | |
| 19 | americateve.com | NEWS | |
| 20 | somosmascuba.com | NEWS | |
| 21 | cubasindical.org | HUMR | |
| 22 | damasdeblanco.com | HUMR | |
| 23 | freedomhouse.org | HUMR | |
| 24 | cadal.org | HUMR | |
| 25 | cubalex.org | HUMR | |
| 26 | observacuba.org | HUMR | |
| 27 | icj.org | HUMR | |
| 28 | represorescubanos.com | HUMR | |
| 29 | oas.org | HUMR | |
| 30 | directorio.org | POLR | |
| 31 | cubadata.com | POLR | |
| 32 | cubademocraciayvida.org | POLR | |
| 33 | cubadecide.org | POLR | |
| 34 | proyectoinventario.org | POLR | https://explorer.ooni.org/m/20260919161820.918827_CU_webconnectivity_896843fa0dfa4080?webview=true&language=en-US |
| 35 | change.org | ACT | |
| 36 | revistaelestornudo.com | CULTR | |
| 37 | delta.chat | COMT | |
| 38 | support.delta.chat | COMT | |
| 39 | eltoque.com | NEWS | |