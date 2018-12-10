---
title: "UNRC, ¿accesible para todos?"
categories:
  - Accesibilidad
tags:
  - accesibilidad
  - accesibilidad web
  - discapacidad
  - inclusión
image:
---

"La UNRC se caracteriza por ser pública  y  gratuita (...) para  asegurar  la  igualdad  y  libertad de  acceso y  permanencia  para  todas  las
personas (...)", anuncia en el preámbulo, el [estatuto de la UNRC](https://www.unrc.edu.ar/descargar/EstatutoUNRC.pdf), pero esto incluye a las **personas con discapacidad** para quienes, en diferentes medidas según sus dificultades cognitivas y/o motrices, resulta imperceptible, inoperable e incomprensible **cualquiera de los sitios web de la UNRC** en el que deseen navegar, y ello cesa en un mero deseo.

¿Es la UNRC una institución **accesible** para *todos*? ¿inclusive para personas con discapacidad visual? Para intentar responder estas preguntas se necesita algo de **empatía**.

Pensando en una acción cotidiana como lo es ingresar al sitio web de la UNRC, a la página de nuestra facultad, de una secretaría o entidad para realizar algún trámite, nos encontramos con la [página de inicio](https://www.unrc.edu.ar/):

![Captura de página de inicio del sitio web de la UNRC](/images/2018-12-10/captura_sitio_unrc.png)

Pero una persona con disminución visual se encuentra con algo así:

![Captura del sitio web de la UNRC con efecto para mostrar disminución visual](/images/2018-12-10/captura_sitio_unrc_blur.png)

Dos simples funciones le permitirían acceder, percibir, entender y operar el sitio web de la uni: *aumentar el tamaño de la fuente de texto*, ( sólo se aplica en el texto del cuerpo de los artículos, no aplica para el resto de los recursos a navegar), y *una mejor combinación entre los colores del fondo y de la fuente*, ninguno funcional en el [sitio oficial de la UNRC](https://www.unrc.edu.ar/)

Alguien que necesite usar un sintetizador de voz en su celular o computadora no puede escuchar las noticias, ni las leyendas de los links como **Becas 2019**, ya que están en formato de imagen y no todas cuentan con la correspondiente descripción en el campo *Alt* del código HTML. `<img src="/img/becas2019.png" alt="" width="339" height="64">`, que es el texto que **le describe la imagen** a la persona con discapacidad, quien  simplemente se pierde toda esta información.

Y si quisiera enviar un mensaje a la administración del sitio web, manifestando estas y muchas otras dificultades que la **excluyen** de acceder al mismo, se encuentra con que debe completar un captcha sin la opción de escuchar el código a ingresar, es decir un formulario no apto para quien use un sintetizador.

[![Captcha no apto para ciegos](/images/2018-12-10/captcha_unrc.png)](https://web.archive.org/web/20181210225751/https://sisinfo.unrc.edu.ar/entrada2/contacto-ext.php)

Este mismo y obsoleto sistema de verificación con captcha se usaba hasta hace apenas algunos meses en el [Sistema de información](https://sisinfo.unrc.edu.ar/), y casualmente se reemplazó por un [*"re-captcha"*](https://www.google.com/recaptcha/intro/v3.html), pero sólo en este sitio. El que muchas veces *"desconoce"* a los *humanos* que deseamos entrar al SIAL en hora pico para sacar menú.

Estos impedimentos no sólo contradicen el propio estatuto de la universidad, no sólo son obstáculos para las personas con discapacidad y pueden ser descriptos como discriminatorios, sino que **violan la Ley Nacional de Accesibilidad de la Información en las Páginas Web**.

Se agranda la lista de *incumplimientos a leyes nacionales* en la UNRC, en cuanto a [transparencia](https://unileaks.github.io/presupuesto/sueldos-unrc-hay-un-problema-real/), también en [investigación](https://unileaks.github.io/repositorios%20digitales/de-la-sociedad-para-los-academicos-y-nunca-al-reves/), en esta ocasión sobre **accesibilidad**.

En  2010 se sancionó en Argentina la [ley de Accesibilidad de la Información (26.653)](http://servicios.infoleg.gob.ar/infolegInternet/anexos/175000-179999/175694/norma.htm), cuyo **Art 1°** enuncia:

> "El Estado nacional, (...) los entes públicos no estatales, las empresas del Estado y las empresas privadas concesionarias de servicios públicos, (...)  deberán respetar en los diseños de sus páginas Web las normas y requisitos sobre accesibilidad de la información que faciliten el acceso a sus contenidos, **a todas las personas con discapacidad** con el objeto de garantizarles la igualdad real de oportunidades y trato, evitando así todo tipo de **discriminación**."

Y en su **Art 5°** que las normas y requisitos están determinados por la Oficina Nacional de Tecnologías de la Información (ONTI) a través de la [disposición N° 2/14](http://servicios.infoleg.gob.ar/infolegInternet/anexos/230000-234999/233667/norma.htm), que asigna una determinada cantidad de puntos a cada criterio y establece **como nivel mínimo de cumplimiento el nivel A**, a través de dos etapas con **50 Y 80** puntos correspondientemente, existiendo los niveles AA y AAA.

En 2016, 6 años después de la sanción de la ley, en el Simposio de Informática del estado, se realizó un [Análisis de Accesibilidad de los Sitios Web de las Universidades Argentinas](http://www.clei2017-46jaiio.sadio.org.ar/sites/default/files/Mem/SIE/SIE-11.pdf), en el que el sitio web de la UNRC (las páginas de inicio, oferta académica y contacto), sólo superaba la primera etapa (de dos, con 64 de 100 puntos) del nivel A (de tres niveles).

Pasados dos años desde esta primer *alerta* de accesibilidad, realizando el [test de accesibilidad online](https://www.tawdis.net) y aplicando el criterio del artículo a la página de inicio, de oferta académica y formulario de contacto), Puntaje = (cantidad de SI + Cantidad de NA)*4, con:

* Cantidad de SI = 1
* Cantidad de NO = 5
* Cantidad de NA (no aplica) = 4

**Puntaje = 20**

| Año 	| SI | NO | NA | Puntaje | Etapa 1 | Etapa 2 |
| --- 	| -  | -  | -  | ---	 | --- 	   |  ---    |
| 2016 	|12  |9	  | 4  | 64	 | Si      | No	     |
| 2018 	| 1  |5  | 4 | 20      | No      | No	     |

En 2018, el sitio de la UNRC aún **no cumple con la primera de dos etapas, para el nivel "A" mínimo exigido por la ley sancionada hace 8 años**.

Para asignar un puntaje a cada página web de la UNRC, de todas las facultades, dependencias, secretarías, desarrollamos dos herramientas de análisis automático, especilamente para el estudio de esta problemática:

* **[Un scraper de Taw (Test de accesibilidad web online)](https://github.com/lbellomo/taw_scraper)**, hecho por [Lucas Bellomo](https://twitter.com/ucaomo)
* **[Análisis de accesibilidad web en la UNRC](https://github.com/brivadeneira/analisis-accesibilidad-web-UNRC)**

Ambas escritas en Python y según los [criterios de análisis de accesibilidad](https://github.com/brivadeneira/analisis-accesibilidad-web-UNRC/blob/master/criterios-analisis.md) y de [asignación de puntaje](https://github.com/brivadeneira/analisis-accesibilidad-web-UNRC/blob/master/README.md) del artículo *"[Análisis de Accesibilidad de los Sitios Web de las Universidades Argentinas](http://www.clei2017-46jaiio.sadio.org.ar/sites/default/files/Mem/SIE/SIE-11.pdf)"*, del Simposio de Informática del Estado.

Los problemas con el diseño web de las páginas de la uni proliferan de principio a fin del análisis. Al buscar los **títulos** de las páginas, con el tag *title* del código HTML *(mismo recurso con el que un sitentizador de voz le indica a una persona con discapacidad visual en qué sitio se encuentra navegando)*, aparece *"de todo un poco"*, páginas con título no descriptivo, páginas cuyo diseñador web dejó vacío el campo donde debía ir el título, y hasta páginas sin el tag *title*, presente en toda estructura básica de un sitio web, varias páginas no disponibles y algunas otras a las que se llega por dos links diferentes.

| Sitio web                 | Título                                                    |                    |
|---------------------------|-----------------------------------------------------------|--------------------|
| www.siat.unrc.edu.ar      | Campus Virtual SIAT - Universidad Nacional de ...         |                    |
| www.coro.unrc.edu.ar      | Coro - UNRC                                               |                    |
| dbm.exa.unrc.edu.ar       | Departamento de Biología Molecular                        |                    |
| dcn.exa.unrc.edu.ar       | Departamento de Ciencias Naturales                        |                    |
| geo.exa.unrc.edu.ar       | Departamento de Geología                                  |                    |
| dmat.exa.unrc.edu.ar      | Departamento de Matemática                                | FCEFQyN - UNRC     |
| dmi.exa.unrc.edu.ar       | Departamento de Microbiología e Inmunología               |                    |
| dq.exa.unrc.edu.ar        | Departamento de Química                                   | FCEFQyN - UNRC     |
| app2.eco.unrc.edu.ar      | Encuesta Docente                                          |                    |
| www.eco.unrc.edu.ar       | **FCE** (?)                                               |                    |
| www.fce.unrc.edu.ar       | Facultad de Ciencias Economicas – Servicios In...         |                    |
| www.hum.unrc.edu.ar       | Facultad de Ciencias Humanas                              | UNIVERSIDAD NAC... |
| www.ing.unrc.edu.ar       | Facultad de Ingeniería - UNRC                             |                    |
| webmail.unrc.edu.ar       | Horde :: WEBMAIL de la UNRC                               |                    |
| www.ayv.unrc.edu.ar       | **Inicio** (?)                                            |                    |
| www.irc.unrc.edu.ar       | Secretaría de Extensión y Desarrollo UNRC – Ce...         |                    |
| neutron.exa.unrc.edu.ar   | **Site** (?) de la Facultad de Ciencias Exactas, Físic... |                    |
| cepeiper.unrc.edu.ar      | Tecnología Educativa - Universidad Nacional de...         |                    |
| www.edutec.unrc.edu.ar    | Tecnología Educativa - Universidad Nacional de...         |                    |
| www.unrc.edu.ar           | Universidad Nacional de Río Cuarto                        |                    |
| sisinfo.unrc.edu.ar       | Universidad Nacional de Río Cuarto                        |                    |
| www.extension.unrc.edu.ar | **Untitled Document** (?)                                 |                    |
| gma.ing.unrc.edu.ar       | **página no disponible** ¯\_(ツ)_/¯                                  |                    |
| cursos.ing.unrc.edu.ar    | **página no disponible** ¯\_(ツ)_/¯                                  |                    |
| revista.eco.unrc.edu.ar   | **página no disponible** ¯\_(ツ)_/¯                                  |                    |
| dc.exa.unrc.edu.ar        | **página sin tag título** ¯\_(ツ)_/¯                               |                    |
| www.exa.unrc.edu.ar       | **página sin título** ¯\_(ツ)_/¯                                     |                    |

Para cada sitio de la lista, se busca y analiza *la página de inicio*, *la página de oferta académica (si la hubiere)*, y *la página de contacto* u otra que *contenga un formulario*.

Se asignan los resultados y se confecciona un ranking:

![Ranking de accesibilidad web en la UNRC](/images/2018-12-10/ranking_accesibilidad_web.svg)

**No existe un sitio web en la UNRC que alcance los requerimientos mínimos de accesibilidad del primer nivel exigidos por ley**.

El **peor puntaje** se atribuye al [Sistema de información](https://sisinfo.unrc.edu.ar/), en el que se realizan de manera excluyente consultas, administración y gestión de *inscripciones a las carreras, a las materias, a los exámenes finales, consulta del aula virtual, solicitud de certificados, de becas, compra de menú diario, etc*.

Pero tal puntaje se encuentra compartido con la [Facultad de Ingeniería](https://www.ing.unrc.edu.ar) y el [Departamento de Matemática](dmat.exa.unrc.edu.ar).

El sitio de la [Biblioteca Juan Filloy](http://juanfilloy.bib.unrc.edu.ar/) *(biblioteca pública y la más grande de Río Cuarto)*, apenas alcanza **un cuarto** del puntaje mínimo exigido por ley.

Irónicamente el sitio del [Departamento de computación](http://dc.exa.unrc.edu.ar/), omite el tag *title* en su código, y al momento del análisis de accesibilidad, no se encontraba disponible.

A la hora de *sumar* puntos, la mayoría de las páginas lo hizo gracias al resultado *"no aplica a este criterio"* y no con un *"si, cumple"*.

![Cantidad de resultados positivos, negativos y no aplica](/images/2018-12-10/cantidad_resultados.svg)

Dado que en la lista no hay, por lejos, ningún *ganador*, sino perdedores en malas y pésimas condiciones, se puede mencionar que la [Facultad de Cs Económicas](www.fce.unrc.edu.ar) reporta la *menor cantidad* de **problemas de accesibilidad**.

El pésimo estado de los sitios web de la UNRC en lo que a accesibilidad respecta, suceden a pesar de que la ley de accesibilidad se sancionó *hace 8 años*, a pesar de que desarrollos e implementaciones web de la UNRC se llevan a cabo bajo la supervisión y aprobación de la [Unidad Tecnológica de la Información (UTI)](https://www.unrc.edu.ar/unrc/general/uti.php), encargada de *proveer los servicios de tecnología de la información a la universidad*, donde se supone que se manejen estándares tecnológicos, y entre ellos el de accesibilidad web *([WCAG](https://www.w3.org/TR/WCAG20/))*.

Y más aún, a pesar de que la UNRC cuenta con una [Comisión de Atención a las Personas con Discapacidad](https://www.unrc.edu.ar/unrc/bienestar/com-atencion-pers-disc.php) perteneciente a la [Secretaría de Bienestar](https://www.unrc.edu.ar/unrc/bienestar/) desde 2005, conformada por *representantes de las cinco Facultades, por  miembros de la Secretaría de Bienestar, de la Secretaria Académica, por estudiantes y graduados*.

> Sitio web que irónicamente alcanza 24 de 80 puntos de accesibilidad.

¿Se preocupan en esta *comisión* de los **derechos** y **problemáticas reales** de las personas con discapacidad?, ¿entienden sobre el tema?

¿Se realizan desde esta *comisión* actividades ligadas a garantizar los derechos de las personas con discapacidad en materia de acceso a la información y a la educación? ¿Conocen acaso las leyes vigentes en nuestro país al respecto?

Los resultados muestran que, respecto a la accesibilidad web, la respuesta es no. Este es apenas uno de muchos aspectos de acceso igualitario a la información y a la educación, como infraestructura de la universidad, libros, apuntes y presentaciones de las cátedras, dictado de de las clases, todos ellos con sus problemáticas.

La universidad debe brindar recursos tanto web como de toda índole, a todas las personas de la comunidad sin **discriminación**, así como formar profesionales conscientes de estas problemáticas.

Agradecimientos especiales a [Lucas Bellomo](https://twitter.com/ucaomo) por el desarrollo de [taw_scraper](https://github.com/lbellomo/taw_scraper) y a Viviana Chappeto y Bibiana Rossi por la asesoría en el tema.

*Si vivís/viviste en las residencias o conocés a alguien que si, por favor, respondé/difundí esta encuesta:  [Residencias UNRC](https://goo.gl/forms/G3Y8mTFw69BtO7Mw2)*
