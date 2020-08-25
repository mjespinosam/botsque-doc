
# El lenguaje del botsque: pensar los prototipos para integrar las plantas como agentes no humanos en entornos colaborativos

### Índice

[TOC]

I

Introducción

Metodologías injertas: prespectivas del diseño para las humanidades

¿De que manera podemos abordar este problema desde las humanidades digitales? 

Plantar la discusión: Las plantas como agentes (abordajes interdisciplinarios perspectivas teóricas)

¿Cómo pensamos las plantas?

Las raíces del problema: ¿Qué es de la planta la planta digital?

¿Qué ocurre cuando pensamos las plantas en infraestructuras digitales ? 

De la Extracción a la siembra de datos colaborativa: rutas y prototipos

¿Cuál fue el recorrido, cuáles los modos y cuáles los hallazgos?


El lenguaje del botsque : prototipo para pensar la agencia de lo no humano en entornos colaborativos

¿De qué manera podemos diseñar un entorno colaborativo en la que las plantas sean agentes? 

Conclusiones

Referencias

Anexos


##   Introducción

Al menos son dos los objetos de las humanidades digitales: 1) implementar y desarrollar herramientas digitales para la investigación y transferencia de conocimiento de las disciplinas y 2) dialogar con las herramientas para dar discusiones conceptuales y teóricas.[^1]. La primera perspectiva se desarrolla a partir de conocimientos de las ciencias de la información, bibliotecología, archivística, ingenierías de sistemas, informática, electrónica, desarrollo de software, etc. Estas disciplinas disponen de metodologías que permiten a los humanistas organizar corpus de datos, hacer análisis de los mismos, visualizarlos, crear y gestionar colecciones o desarrollar software específico para analizar, comprender o resolver sus problemas particulares. A este modelo de implementación o desarrollo de herramientas desde perspectivas y necesidades humanistas se suma la posibilidad de hacer investigación sobre el diálogo entre los diversos campos de las humanidades y las tecnologías y herramientas digitales[^2]. Aunque una perspectiva no excluye a la otra, es claro que la primera busca implementar o validar un prototipo para resolver un problema. La segunda perspectiva por su parte, busca mediante la implementación y el prototipo experimentar para dar cuenta de las tensiones y posibilidades que se dan entre herramientas y conocimientos disciplinares [^3].

En este sentido, esta tesis explora la segunda perspectiva, al discutir cómo la implementación de herramientas colaborativas, en particular una wiki semántica etnobotánica (relaciones seres humanos-plantas), me permitió reconocer en el prototipo un dispositivo experimental para pensar tanto el problema de las herramientas colaborativas como las relaciones seres humanos-plantas. Es decir, las tensiones y diálogos entre herramientas digitales y conocimiento etnobotánico. Durante la investigación el prototipado de las herramientas, en sus diferentes fases e iteraciones, pasaron de metodologías de diseño participativo o centrado en usuarios a una metodología de diseño centrado en conceptos problema. De ahí que en el proceso emergieron todos los actores humanos y no humanos involucrados en dar cuenta de las relaciones plantas-seres humanos. A esta altura de la experimentación se refinó el problema, se precisaron los actantes y emergió la pregunta de qué condiciones son necesarias para que las herramientas colaborativas se configuren como un espacio en el que humanos y no humanos -en este caso plantas- se integren como actores del conocimiento colaborativo. Esta pregunta, que parte del reconocimiento de las plantas como actantes en la construcción de conocimiento sobre ellas y cuya relación con los seres humanos puede modelarse mediante herramientas digitales colaborativas, solo fue posible una vez recorrí la perspectiva de implementación de herramientas colaborativas para una necesidad de una comunidad y me encontré con una perspectiva crítica del diseño para analizar categorías como "planta" y el software mismo. Un problema que emergió al poner a prueba el problema inicial mediante diversos prototipos. 

Abordar la agencia de la plantas como actores en la construcción del conocimiento colaborativo en herramientas digitales introduce en las humanidades digitales las discusiones sobre lo no humano que abordan las pos humanidades desde la filosofía, la antropología y estudios de la ciencia en diálogo a la biología y la etnografía [^3]. Si bien la manera como las plantas se pueden comunicar está en campos experimentales aún, ya se reconoce que tienen memoria y por lo tanto aprenden. Igualmente es claro que producen signos que comunican a los humanos, a los entornos y que, a través de sistemas más complejos, les permiten comunicarse entre sí. En diferentes latitudes del planeta las comunidades no solo reconocen la agencia de las plantas como parte de sus culturas sino que, describen las maneras como seres humanos y plantas entran en comunicación para reportar sus usos, por ejemplo a tavés de los sueños (Terangpi et al., 2015). De ahí que dar esta discusión desde las humanidades digitales me permite construir un diálogo interdisciplinario para hacer una aproximación crítica tanto a una software existente que es modelo de los entornos colaborativos, el Media wiki, como una modesta proposición de un modelo posible para una herramienta colaborativa hipotética, en la que se reconozca y active la agencia de las plantas con la mediación de agentes virtuales. 

Ya que la tesis quiere hacer explícitas las rutas metodológicas y por lo tanto los presupuestos como los métodos utilizados en relación al saber y el hacer en las Humanidades Digitales, la ruta argumentativa arranca por allí. ¿De qué manera llegué al problema de esta tesis luego de varios prototipos? Es decir ¿Cómo investigué en tanto humansita digital? ¿De qué manera conocí lo que conocí? ¿ De qué manera organicé el material y cómo decidí comunicarlo?  Preguntas de carácter ontológico, epistemológico y metodológico que abordo en el capítulo 1: "Metodologías injertas". Allí presento la discusión sobre la investigación como diseño, una discusión que desde los años ochentas valida el diseño cómo una vía de conocimiento. Discusión que me permite el prototipo en las humanidades digitales como una herramienta argumentativa. En este sentido hago una propuesta de documentación utilizando Git, el sistema de control de versiones y Git hub como una plataforma en la cual acopiar datos textuales y visuales. En cuanto a la investigación misma realizo un recorrido por las metodologías de diseño abordadas -de manera más intuitiva que predefinida- en los diferentes momentos de la investigación. Un recorrido que implica un giro metodológico que coincide con la incongruencia del prototipo final de una wiki semántica, la oportunidad de hacer un laboratorio de electrónica y plantas y la apertura a las discusiones del diseño crítico y especulativo. Este recorrido me permite afirmar que las perspectivas críticas y especulativas del diseño involucran metodologías de diseño que permiten expandir las relaciones entre los artefactosm, herramientas y humanidades. Desde allí es posible pensar los problemas que emergen de la vida y las disciplinas. 



En el capítulo 2: "Plantar la discusión" abordo el estatuto filosófico, antropológico y biológico de las plantas como un punto indispensable para pensar cualquier desarrollo de software o adecuación de un ya existente. Aquí dialogo con la Teoría Actor Red de Latour y la Semiótica de Peirce como marcos teóricos que permiten abordar lo no humano como agentes productores de signos y por lo tanto de información y conocimiento en diversos  contextos. Estas dos teorías tienen claras perspectivas metodológicas que fueron indispensables para abrir preguntas y pensar en los prototipos. 

En el capítulo 3 "Las raíces del problema" presento el recorrido en el refinamiento de la pregunta y el problema durante la investigación. Este proceso es documentado a través de el control de versiones Git. Este software me permite ver como el tema de las relaciones seres humanos y plantas requirió de un refinamiento de las preguntas y los problemas mediante procesos de prototipado y como se desprendieron ramas de discusiones que daban paso a nuevas investigaciones o desarrollos. Así, en este trayecto hago el seguimiento a las preguntas iniciales, emergentes, el refinamiento del problema, los prototipos realizados, los referentes encontrados, los conceptos integrados y las ideas emergentes. 

 En el capítulo 4 "De la extracción a la siembra de datos" presento cada uno de los prototipos bajo un modelo de informe de laboratorio para determinar las cuestiones emergentes que me llevaron a nuevas itereaciones en las que se refinaba el problema a partir de los hallazgos, hasta un punto final en el que se planea un prototipo acorde a un estado de la cuestión desde una perspectiva crítica de las herramientas y la construcción de los sujetos-objetos de estudio-investigación-croeación. 

 En el 5 capítulo: "El lenguaje del botsque", elaboro un esquema para una herramienta colaborativa que integre la agencia de las plantas con el uso de un agente virtual "botsque" en un entorno colaborativo. Prootipo con el que concluyo este trabajo y que me permite recomendar elementos para el desarrollo de herramientas ágiles, incluyentes, biocéntricas que impliquen un diseño centrado en lo vegetal para aboradar las relaciones plantas-seres humanos.

#### Hoja de Ruta

Para la comprensión argumentativa de este trabajo hay que  tener claros los siguientes momentos

1. Determinación de requerimientos. Enfoque bibliotecológico y comunitario
2. Exploracion de herramientas 1 -Omeka / Wiki / Inaturalist
3. Definición de un proyecto de wiki semántica
4. Prototipo de la wiki semántica "Mil país" para gestión de conocimiento
5. Replanteamiento de la wiki como prototipo y emergencia de tensiones éticas y concpetuales
6. Giro metodológico metodologías participativas tecnocentristas/ metodologías críticas especulativas biocentristas
7. Prototipo de una mesa huerta como sistema comunicativo 
8. Refinamiento del problea  con perspectivas críticas y éticas de las tecnologías
9. Diseño de un sistema de comunicación con agentes virtuales. Prototipo final. 






[^1]: Las relaciones entre tecnologías digitales y humanidades han trasegado desde la computación humanista, la informática comunitaria, la informática educativa y las humanidades digitales. Si bien en ninguna de estos campos existen definiciones disciplinares con programas teóricos y metodológicos claros, todas emergen dentro de la cultura digital o cibercultura. Los abordajes para su definición presentan un campo múltiple de aproximaciones en las que prima lo heterogéneo, interdisciplinario. Ver: del Rio Riande, M. G., & González Garcí Blanco, B. (2015). Introducción a las Humanidades Digitales. Material Didáctico Sistematizado. 103. https://www.aacademica.org/gimena.delrio.riande/115 Cuartas-Restrepo, J. M. (2017). Humanidades digitales, dejarlas ser. Revista Colombiana de Educación, 72(1), 65-78. https://doi.org/10.17227/01203916.72rce65.78 Galina Russell, I. (s. f.). ¿Qué son las humanidades digitales? 1 Julio de 2012, 12(7). Recuperado 4 de diciembre de 2016, de http://132.248.9.34/hevila/Revistadigitaluniversitaria/2011/vol12/no7/5.pdf Rueda Ortiz, R. (Ed.). (2013). Ciberciudadanías, cultura política y creatividad social (Primera edición). Universidad Pedagógica Nacional. 

[^2]: Los estudios de las tecnologías o la antropología de la ciencia tienen por objeto de estudio la tecnología y si bien dan cuenta de las relaciones de los actores humano y no humano su objetivo no es pensar el problema mismo desde el uso o experimentación con la tecnología. Esta manera de investigar por medio del hacer con una tecnología está más cerca de las metodoogías del diseño. 
[^3]: Como elaboraré en la metodología esta perspectiva coincide con lo que los diseñadores han llamado "Investigación como diseño" (Simon, 2015).
[^4]: Lo no humano en las humanidades se desarrollará en el III capítulo. La filosofía permite un marco para el reconocimiento ontológico a lo vegetal (Ver: Michael Marder),  la antropología un abordaje de la construcción de realidad, sentido y comunicación con lo no humano (Ver :Latour (2014), Kohn (2013)) y la biología una expansión de sus preguntas sobre inteligencia y comunicación vegetal (Ver Gagliano (2017), Mancuso (2015)



## I  Metodologías injertas: prespectivas del diseño para las humanidades



Técnicamente esta tesis se logró a un año de presentar este trabajo. Implementé una wiki semántica etnobotánica (relaciones seres humanos -plantas) por medio de formularios estructurados con estándares de metadatos (Dublin core, Foaf), en una interfaz amigable. La wiki alimentaba colabortivamente una base de datos relacional a la vez que respondía a los requerimientos del proyecto:  eficiencia en la estructuración, recuperación, migración e inter-operabilidad de la información y principios democráticos a la hora de construir el conocimiento de un campo específico (etnobotánica), mediante una estrategia colaborativa con comunidades. Sin embargo, aparecieron problemas de carácter conceptual, legal, ético y de diseño que reformularon el proyecto y sobre todo mi rol como humanista digital en formación. ¿Qué hacer cuando una vez logrado el objetivo inicial de una investigación emergen aspectos problémicos? ¿Es posible que una tesis refute la tesis que la originó? ¿De qué manera se relata, construye, discute y se comparte las vicisitudes de un proyecto? Pero sobre todo, ¿cómo llegué a saber más cosas sobre el problema de las relaciones seres humanos-plantas mediante la obervación, análisis y reflexión del prototipo logrado en ese momento? 

La pregunta de cómo investigué lo que investigué y sobre todo cómo llegué a refinar el problema me llevó a observar un modo particular en el hacer: investigar como diseño, investigar con diseño. La investigación como diseño es una propuesta que tiene sus orígenes en los años ochentas con las reflexiones que hizo en su momento Zeisel. El autor aborda  los puntos en común entre diseñadores e investigadores a la hora de afrontar una situación a indagar o investigar. Allí, dice Zeisel (1984), ambos crean conceptos o imágenes, formulan hipótesis o presentan los conceptos y luegos los ponen a prueba. La investigación como diseño es en todo caso más que un paralelismo en los pasos o procesos para investigar. Es una ruta para pensar los problemas desde la creación de artefactos, prototipos (Dunne y Raby 2013). Es una manera de resolver los problemas (Gray y Malins 2004) o, una ruta para encontrarlos. Es una manera de involucrar el pensamiento visual y práctico al pensamiento conceptual, del modo que lo hace la ingeniería, por ejemplo. (Grand & Wiedmer, s. f.). Los prototipos por lo tanto, vendrían a ser la representación de las hipótesis que permiten desde sí mismos, comprender o -simular- las maneras como se comportan los problemas en un entorno. Es decir, pensamos con los prototipos y por ello, podemos hablar de las funciones epistémicas del prototipo.

Posicionar a los prototipos como instrumentos con funciones epistémicas y que por ello nos ayuda a pensar y desarrollar el pensamiento, nos lleva a la pregunta de cómo ocurre ello. Si bien esta pregunta tendría que ser respondida desde las ciencias cognitivas, o los estudios de la creatividad, la etnografía de los procesos creativos también nos permite precisar algunas vías para comprender este asunto.  **Latour en sus célebres etnografías de laboratorio introdujo varios elementos a tener en cuenta en la configuración de la ciencia y el conocimiento científico** en la que los objetos implícitos en los diseños experimentales no eran ajenos a lo hallado. Por ellos y a través de ellos el científico observa y comprende su objeto de estudio. Así, además de la acción humana sobre el hecho a investigar, los dispositivos, artefactos y experimentos son actores que determinan el conocimiento mismo. Identificarlos como actores implica entender que los objetos inanimados tienen agencia en las relaciones que establecen con los seres humanos, por ejemplo. Si bien esa tesis es objeto de múltiples controversias, como se tratará en el capítulo teórico, tanto la discusión de Latour como la perspectivas semiótica de Peirce nos permite indagar sobre dicha agencia. En el artículo  Developing Things: Notes toward an Epistemology of Building in the Digital Humanities Stephen Ramsay and Geoffrey Rockwell postulan las herramientas digitales como "telescopios para la mente" instrumentos hermeneúticos  a través de los cuales  -y con los cuales- interpretamos fenómenos. Esta analogía, utilizada originalmente por la linguista computacional Margaret Masterman, no solo es provocativa sino polémica. ¿Pueden las herramientas ser en el ejercicio investigativo parte de la discusión y de la explicación por que en sí mismas tienen elementos que discuten, problematizan, explican lo que se está  investigando?  Aunque su integración como argumento esté mediado por un discurso -pensemos en la mediación del curador de arte y la obra de arte- las herramientas, artefactos y obras cuentan con los elementos que pueden ser leídos solo por quienes dominan su lenguaje. De ahí que se requieran procesos de traducción. Pero, ¿cómo contar estas historias, traducirlas? ¿Cuál el esquema de una tesis que quiere dar cuenta de estos procesos? 

##### Git: software de control de cambios

 Apoyada en una herramienta digital de control de cambios denominada Git, ampliamente utilizada en el mundo del desarrollo del software, ideé una estrategia para organizar, categorizar y narrar los cambios que ocurriendo entre la creación de un prototipo y la revisión de los referentes. Esta narrativa grafica la persistencia de un tema y la emergencia de preguntas, problemas, ideas así como la integración de conceptos y referentes. Como se muestra en la gráfica 1,  cuatro fueron los prototipos: wiki semántica, app cofechas, mesa huerta y finalmente el lenguaje del botsque. En los primeros dos prototipos como se discutirá ampliamente en el capítulo "plantar el problema",  las plantas no fueron asumidas como actores  en la contrucción del conocimiento sobre sí mismas pese a intuir su agencia. El giro metodológico se concretó en un artefacto "La mesa huerta" que implicó la discusión de las infraestructuras, herramientas y postulador del proyecto. ¿Que son las plantas? ¿Como se representan en sistemas informáticos? ¿Cómo se dan y cuáles son las relaciones plantas-seres humanos?  Esto me permitió problematizar las herramientas y metodologías mismas los presupuestos que subyacen a ellas. 

<img src="/Users/juanaespinosa/tesis/001-tesis- git/esquemas/esqu-rutainvestiva-v2.png" style="zoom:300%;" />

El sistema git funciona a partir de 



#### Preguntas, problemas y referentes 

¿Qué es de la planta lo que una base de datos dice que es la planta? ¿Cuál es la participación de la planta en lo que sobre ella se dice en una plataforma colaborativa? ¿Puede ella colaborar en lo que de sí se dice y se construye en una plataforma que quiere poner de manifiesto las relaciones que tiene ella con los seres humanos? ¿Las plataformas colaborativas pueden dar cuenta de las relaciones plantas-seres humanos? La aparición de cada una de estas preguntas en esta tesis no fue un asunto a priori, si no el resultado de un proceso de investigación a partir de la consulta y estudio de referentes y el prototipado de plataformas colaborativas. Así, las preguntas fueron develando el problema subyacente al problema inicial. Pero, ¿es posible hacer una investigación sin un problema acotado? 

En las humanidades es usual que nuevas categorías metodológicas o conceptuales aparezcan en el curso del desarrollo de la investigación. Generalmente se parte con unas categorías predeterminadas y aparecen nuevas categorías metodológicas o conceptuales en la medida que se expande el corpus teórico y se analizan datos (Rico de Alonso, 2005). Sin embargo, no es usual, ni metodológicamente deseable, que el problema cambie en el transcurso de la investigación. El problema responde a la identificación de un vacios del conocimiento y su investigación tiene por objeto comprender, explicar y ampliar los conocimientos que allí se discuten. Sin embargo, en esta investigación desde las Humanidades Digitales  el problema fue un problema. Las rutas metodológicas de diseño de investigación de las humanidades, excepto los estudios culturales o la etnohistoria [5^], no piensan en la confluencia de disciplinas para el abordaje de los problemas si bien en muchas investigaciones confluyen varias disciplinas. Por ello es usual que las investigadoras encontremos tensiones metodológicas antes los vacios del saber y el saber hacer en diversas disciplinas. Así, en esta investigación, como suele suceder en el diseño como en las artes, el problema tomó diversas materialidades -prototipos- y la investigación misma se encaminó a construir el problema interdisciplinariamente [6^]. Por lo tanto, el acotamiento del problema es el resultado de la investigación misma. Un recorrido que de paso posiciona la investigación como diseño (Grand, 2010; Jonas, 2010).

![Esquema problema de investigación](/Users/juanaespinosa/Tesis/001-tesis- git/esquemas/esqu_problema_21.png)

 



Para dar cuenta de cómo pensé mediante el diseño de prototipos, o cómo estos fueron  "telescopios para mi mente" este capitulo se organiza en tres partes. 

En la primera narro - en lo que puede denominarse una acción auto etnográfica- lo que llamo el giro metodológico. Allí se concentra la discusión de las perspectivas disciplinares y metodológicas que definieron el lugar de las herramientas e infraestructuras en  la investigación. ¿Son las herramientas e infraestructuras un fin o un medio? Las perspectivas detalladas son la informática comunitaria, la informática educativa, el diseño participativo y finalmente el diseño crítico. 

En la segunda parte presento la discusión sobre lo que implicó investigar como diseño y desde el diseño en las Humanidades Digitales. Finalmente, en la tercera parte integro la reflexión sobre la documentación como parte de la resolución de problemas en Humanidades Digitales.  

En particular situo el uso de Git, un software de control de versiones para mapear la trayectoria del proyecto en relación a las preguntas e ideas emergentes, la refinación del problema, la integración de conceptos y su relación en el tiempo con los prototipos. Igualmente presento el uso de la visualización mediante diagramas y el diseño de dos instrumentos en particular: los marcos analíticos para abordar los referentes y el protocolo -análogo al de un laboratorio- para sistematizar los prototipos. 

## 

## Las raíces del problema: ¿Qué es de la planta la planta digital?  



A la pregunta de cuáles fueron las herramientas utilizadas para trabajar el presupuesto de las relaciones "seres humanos plantas" es preciso dar cuenta de un giro metodológico. Un giro que se comprende a partir de la revisión de los presupuestos inciales -algunos de ellos implícitos- y los elementos emergentes durante la investigación: el análisis de referentes, los problemas e ideas emergentes y los conceptos integrados.

 

El hilo conductor de todo este proceso ha sido las relaciones seres humanos plantas o mejor plantas seres humanos. Inicialmente la investigación tuvo por objetivo la implementación de un software colaborativo - tipo wiki- de las relaciones "seres humanos-plantas". En ese primer momento el interés estaba dirigido a construir un referente para la adecuación de la [Base de Datos del Centro de Estudios de Medicina intercultural](https://github.com/mjespinosam/ruta-metodologia/wiki/CEMI). Un proyecto etnobotánico centrado en la construccion colaborativa de usos y aprovechamiento de las plantas. Así, desde un paradigma fenomenológico -naturalista- con metodologías investigación acción, provenientes de las humanidades, la investigación avanzó en ese primer momento con la intención de darle forma a una herramienta - la wiki semántica- bajo unos requerimientos. A saber:

>* Estructuración semántica de la información para una recuperación efectiva. 
>
>* Catalogación de los saberes etnobotánicos a partir de vocabularios controlados.
>
>* Inclusión de lenguaje común -folksonomías- para aumentar o precisar vocabularios controlados.
>
>* Construcción colaborativa y democrática del conocimiento sobre las plantas y su aprovechamiento. 
>
>* Manifestación de las relaciones de las plantas con individuos y comunidades así como su pertencia a territorios.

 El primer y más importante referente para crear el prototipo de Milpaís fue [Inaturalist]( https://www.inaturalist.org/pages/what+is+it). Este software libre creado en el marco de una maestría de ciencias de la información de la universIdad de Berkley es actualmente una plataforma tipo red social que integra a la ciudadanía en la captura de datos sobre la biodiversidad. De este modo, información sobre especies animales, vegetales u hongos son reportados mediante imágenes o sonidos, y debidamente georeferenciados en la plataforma. Allí, una comunidad de expertos hace la verificación del nombramiento de tal modo que, se asegure la estructuración debida de los datos. Esta curaduría junto a una opción de oscurecimiento de información son dos de los elementos a destacar. La curaduría permite que la comunidad de expertos verifique la información y lo ajuste a los estándares científicos y estructuración de datos. Todos los datos están estructuradas bajos las categorías del estandar de metadatos Darwin Core. Este estandar  permite estructurar la información por  elementos de registro -¿qué se observa o escucha?-, registro biológico -¿cuáles son sus atributos?-, evento -¿a qué horas se realizó el registro?-, ubicación -¿dónde se realizó el registro?- y taxón -¿cuál es la especificación taxonómica?-,  excepto identificación que es una categoría que organiza los ID de la base de datos internamente y el contexto geológico.  En cuanto al oscurecimiento de la información esto permite que especies en peligro de extinción puedan reportarse pero mantenerse ocultos para protegerlas de traficantes, por ejemplo. Esta decisión es tomada tanto por quienes hacen las observaciones como por los curadores. El rol de los curadores es asignado por los administrados a partir de su participación o experiencia demostrada. Los curadores trabajan sobre la taxonomías, mediante modificaciones. Los curadores tienen potestad sobre lo que se obscurece a partir de criterios de riesgo. Toda la información está en su [guía  para curadores](https://www.inaturalist.org/pages/curator+guide). 



Ver [Observación inaturalist](https://www.inaturalist.org/observations/20189776)

![](/Users/juanaespinosa/Tesis/001-tesis- git/esquemas/esqu-referentes-v1.png)



La posibilidad de obscurecer informacion y el sistema curatorial de la información, respondían a dos problemas emergentes en el proceso de la investigación de Milpaís:  los peligros de información de plantas medicinales sin verificación famaceútica, médica, etc. y la necesidad de resguardar cierta información etnobotánica dentro de plataformas digitales. En cuanto a la curaduría inaturalist me permitió identificar un esquema de relacionamiento entre expertos y aficionados para la estabilización de la información. Sus criterios de evaluación de calidad de datos, los procedimientos colaborativos para rectificar o asignar nombramientos son dos estrategias que funcionarian perfectamente en una paltaforma etobotánica. Ello aseguraría la democratización en la construcción del conocimiento y la fiabilidad de los datos. De tal modo se controlarían los riesgos de toxicidad, interacciones entre componente y tratamientos, entre otras cosas. En cuanto a la posibilidad de obscurecimiento de información es claro que ante la inexistencia de legislación respecto a la protección de saberes tradicionales, los saberes etnobotánicos son propensos a la apropiación indebida o la biopiratería. ¿Qué quiere decir esto? ¿Cómo prevenirlo?

La información etnobotánica, según reporta la Organización Mundial de la Propiedad Intelectual (OMPI), está en riesgo de apropiación indebida. El riesgo yace en las falencias para el establecimiento de legislaciones nacionales sobre derechos tradicionales de propiedad colectiva y la posibilidad de la usurpación de saberes tradicionales mediante patentes y por parte de particulares con intereses económicos. En este contexto la [Biblioteca digital de medicinas tradicionales de la India](http://www.tkdl.res.in/tkdl/langdefault/common/Home.asp) (TDK) fundamentó en el proyecto de Milpais la necesidad de establecer una discusión con la situación legal de dicho conocimiento en entronos digitales. La TDK es además un  modelo de estructuración de información para la protección y prevención de biopiratería [^6] Tras descubrir que varias de las plantas y prácticas medicinales tradicionales estaban siendo patentadas -la cúrcuma por ejemplo- el gobierno Indio decidió crear esta biblioteca. Allí se recopila el saber de varias tradiciones de medicina hindúes en sus lenguas originales y traducidas em 5 idiomas. El propósito es que las oficinas de patentes de todo el mundo verifiquen antes de conceder una patente. Como se puede revisar en la [wiki de referentes en github](https://github.com/mjespinosam/ruta-metodologia/wiki) la TDK estructura la información siguiendo el modelo de clasificación internacional de patentes(CIP) pero añadiento campos de descripción. En la CIP "hasta 2005, solo había un subgrupo –el A61K35/78– correspondiente a plantas medicinales, lo que significaba que los examinadores de patentes no disponían de los recursos óptimos para revisar solicitudes de patentes basadas en medicinas tradicionales" (La protección de los conocimientos tradicionales de la India, s. f.) Por lo que con el trabajo de la TDK se establecieron 207 subgrupos nuevos además de los 27 mil subgrupos presentados por la TDK en lo que denominaron: Clasificación de recursos de conocimientos tradicionales en sus siglas en inglés TKRC. Este modelo de clasificación "sistémica de diseminación y recuperación del conocimiento tradicional en un entorno digital" es un referente mundial. Paises como china consideran oportuno crear un sistema armónico con el CIP pese a que la clasificación TKRC no responde a las particularidades de sus medicinas. En todo caso el TKRC  constituye un esfuerzo por dar cuenta del dominio etnobotánico. Si es o no una ontología aplicable a todo los saberes etnobotánicos es una discusión que daré más adelante. Lo que si es cierto es que gracias a esta plataforma un sistema de conocimiento milenario vivo es catalogado y oscurecido para protegerlo. 

Hasta aquí  Inaturalis se presentaba como el software que podría estructurar una nueva taxonomía -en este caso etnobotánica- y presentar así una mixtura entre enciclopedia y red social que podría ¿por qué no? integrar los saberes etnobotánicos a partir de la estructuración de los datos al modo de la TDK que pudiesen servir para la protección preventiva del conocimiento. Para ello procedimos (10^) a la instalación de este software y prototipar desde allí el entorno colaborativo. Dos aspectos se interpusieron para poder llevarlo a cabo: el software, según comunicó via email el desarrollador del software Ken-*ichi* Ueda, no estaba documentado en sus últimas versiones y según reportaba Karen Socha, encargada de ciencia ciudadana y referente de inaturalist desde el Instituto Humbold en su momento, implementar esta plataforma era demandante y costoso. Al respecto la investigadora comentó sobre la experiencia de España en donde decidieron hacer un Fork  -bifurcación- de inaturalist llamada [Natusfera](https://natusfera.gbif.es/pages/about), que integra además la wikipedia. Este proyecto -reiteró- ha sobrepasado las capacidades humanas y los recursos del equipo. Lo mejor en todos los casos dijo la investigadora - es trabajar desde la que ya existe implementada- . Pero esto era inviable: inaturalist no contempla información etnobotánica, ni a la información sobre biodiversidad le interesa los cruces con lo cultural. Al estar conectada con sistemas de data de biodiversidad, incluir reportes como imágenes de plantas en códices, cuadros, canciones, etc, pasaría ser notificado pues interfiere en la estructuración conceptual de la Base de Datos. En cierta mediad es posible hacerlo a riesgo de ser censurado como ha ocurrido en otras ocasiones.

La Wiki semántica 



Estas rutas me llevaron darle forma a un wiki semántica llamada "Mil País"  y a la aparición de una posible app "Cofechas". Pese a que ambos respondían  o a los requerimientos propuestos en el preproyecto, o a los requerimientos emergentes de una comunidad de productores agroecológicos, los prototipos no evidenciaban la "construcción de conocimiento colaborativo seres humanos plantas", ni resolvían los asuntos éticos y legales del conocimiento etnobotánico en entornos digitales. Estos dos aspectos reformularon la coherencia del proyecto. 

Y así ocurrió en el primer año [5^]. La investigación acción como una metodología de investigación centrada en las relaciones de las personas con el problema,  me permitió mediante el diseño de instrumentos y consulta a comunidades y expertos construir un prototipo inicial. La realización de entrevistas a tres expertos en etnobotánica, propiedad intelectual y ciencia ciudadana, la participación en las reuniones de la comunidad ARAC (productores agroecológicos de Subachoque), la realización de un grupos focal con ellos, la observación participante, las conversaciones, más las matrices de análisis de referentes y exploración conceptual permitieron consolidar un prototipo bajo incipientes metodologías ágiles. Pero ¿Cuáles habían sido los referentes (software) para consolidar este prototipo?





En cuanto a los aspectos legales emergió la vulnerabilidad de los conocimientos tradicionales sobre plantas ante el riesgo de ser patentados. Esta cuestión que parece impensable es el motivo por el que paises como la  India. Como se puede consultar en el referentes Biblioteca Digital de Medicinas tradicionales de la India por sus siglas en inglés TKDL (Ver: wiki en GitHub), existen escazos pero importantes rmodelos de bibliotecas digitales que previenen la bioperiatería o apropiación indebida de conocimientos tradicionales vinculados a recursos biológicos. Este asunto que no es menor cuestiona la procedencia ética de una plataforma etnobotánica. En tanto no exista una legislación nacional, toda informacion que circule en internet está en riesgo de ser apropiada indebidamente. Y esto implica un riesgo para la existencia de las plantas como para las comunidades donde habitan y comparten sus beneficios. Para aclarar el tema: quien patente un  

Frente al asunto de las relaciones de las plantas con los seres humanos, mi perspectiva, como los preceptos ontológicos de los modelos subyacentes a los prototipos: modelado de bases de datos e infraestructuras, no consideraban ni integraban a las plantas como agentes en el sistema mismo. Sin embargo, la oportunidad de desarrollar un laboratorio de micro huertas [x^] me permitió explorar la intuición de dichas relaciones. Intuiciones que más adelante identificaría como metodologías del diseño crítico y  especulativo. Desde allí, como desarrollaré más adelante, me pregunté sobre la agencia de las plantas, su relación -de amistad- con los seres humanos, su estatuto ontológico y la experiencia que teníamos los participantes con ellas. Aquí, el diseño crítico es el detonante del giro de esta investigación pues me permitió reconocer perspectivas multidisciplinarias para abordar un problema de investigación desde las Humanidades Digitales y ver en el prototipo un artefacto para pensar [2]. 



![](/Users/juanaespinosa/Tesis/001_Tesis Git_esquema/Esquemas/esqu_Giro_metodol_V2.png)

¿Pero qué decían estos cambios metodológicos del lugar de las herramientas, las tecnologías y las infraestructuras? Poner la atención en tecnologías o sistemas informáticas al servicio o para la resolución de un problema de índole social es una tendencia que desde los años 80´s congrega a aficionados y profesionales de la computación, u otras áreas. Cuando Grunstein publica *Community Informatics: Enabling Communities with Information and Communications Technologies* (Idea Group, 2000) ya existían al menos 20 años de experiencias localizadas de informática comunitaria (IC). Este campo que no cuenta con unas metodologías propias para ser definido como disciplina, "se preocupa por mejorar la sociedad civil y fortalecer comunidades para la autogestión y para el medio ambiente y el sostenimiento económico
poder, desarrollo, asegurando que muchos que de otro modo quedarían excluidos puedan 
aprovechar las enormes oportunidades que presentan las nuevas tecnologías" (Gurstein, 2000, pág.2). Por lo tanto allí discurren los conceptos de comunidad e implementación y diseño de tecnologías y aplicaciones. Una intención que ya estaba clara en la pregunta del proyecto de la wiki etnobotánica "Mil país"

> ¿De qué manera se puede articular ciencia y conciencia ciudana bajo principios éticos, en comunidades que usan, ivestigan, producen y defienden saberes etnobotánicos mediante la implementación de una wiki semántica pensada para diversas comunidades que permita la apropiación de la tecnología, el acceso recuperación del conocimiento y verificación de la información?

Si bien el acceso a las tecnologías y las herramientas implican que las sociedades salgan de lo que se denomina brecha digital, su implementación no necesariamente implica la apropiación y la comprensión de lo que implica la tecnología misma. La informática comunitaria siguiendo a Gurstein (2000)  incluye el acceso al hardware, el software, la conectividad y la información en contextos dondela tecnología sea aplicada a comunidades "físicas" [x^].  Esto implica que los usuarios como las comunidades deben ser parte del proceso de diseño de las implementaciones que se van a realizar. Pero ¿Incluye el diseño la dicusión de las implicaciones de las tecnologías en las comunidades? Al respecto en Milpas pude notar dos aspectos:

1. En ningún momento había pensado en la manera como se estructuraba el conocimiento para el modelado de una base de datos
2. Tenía la plena convicción de que las wikis al ser colaborativas ya eran herramientas suficientes para democratizar la construcción y recuperación del conocimiento además de mapear las relaciones seres humanos plantas. 





Esta perspectiva pone en escena las tensiones entre las realidades comunitarias y el acceso. Además de condiciones técnicas específicas para poder tener por ejemplo tele llamadas hay demandas educativas que deben acompañar ese acceso



Si bien desde esta perspectiva se aboga por la inclusión y superación de lo que ahora reconocemos 

Informática comunitaria

Informática educativa

Diseño participativo 

Presupuesto

1. Trasnferir la existencia de un ser vivo a una base de datos es un ejercicio de descripción que no acarrea problemas concpetuales. Muchas plataformas tienen información útil y conveniente sobre las plantas. Ya hay preexistencias de estos modelos.
2. Las herramientas no modelan el conocimiento sino que a través de las herramientas modelamos los conocimientos.
3. Existen relaciones entre los seres humanos y las plantas.

Por lo tanto pensar las representaciones de las plantas u otros elementos de los entornos vivos en las herramientas nos permite identificar sus limites y los retos en el desarrollo de software. Pero no solamente en clave de desarollo sino de pertinencia. ¿Para qué queremos un otro software? ¿Cómo el software media con las representaciones que tenemos de la realidad y en este caso de las plantas? 





[5^]: El proyecto recibió una financiación de la Facultad de Artes y Humanidades de los Andes a partir de la cual se desarrolló el trabajo de campo en la comunidad de ARAC 

[6^]: La biopiratería es entendida como la apropiación indebida de saberes tradicionales relacionados con recursos naturales. La TDK alerta sobre el riesgo de que intrusos aprovechen saberes ancestrales para registrarlos en oficinas de patentes que al no tener vías de verificación de la existencia de estos saberes proceden a otorgar patentes. Un litigio en defensa de un saber tradicional es costoso y lleva años. Casos como el de la cúrcuma, nema, arroz basmati, quinoa, ayahuasca, hoodia son emblemáticos por haber sido ganados a favor de las comunidades o por haber sido patentados. 

[10^]: Esta tesis es el resultado del trabajo con Camilo Martinez gracias a quien se pudieron adelantar ensayos y pruebas. Pero no solamente como ejercicio técnico sino como ejercicio reflexivo. Las discusiones aquí presentadas son el resultado de todo el proceso de su tutoría como director de la tesis. 

[2] La perspectiva metodológica aquí expuesta debería ser parte de los hallazgos, sin embargo, la metodología misma requiere de una ruta narrativa que de cuenta de cómo mediante el hacer fui pensando.

[x^] Tanto las aplicaciones de la IC como los modelos de servicios, tienen una clara vinculación con los procesos que se han adelantado o se pueden adelantar en las Bibliotecas Públicas. Y es claro que en este marco las tecnologias son las mediadoras de procesos para las comunidades. Pero ¿cuál es la incidencia de las tecnologías en las mismas comunidades?

*****



#### La investigación como diseño

**Resolver problemas**

###### Pensar visualmente

###### Pensar con prototipos

Cuando el prototipo no es el resultado sino el detonante

Pensar desde los prototipos retoma dos ideas: el diseño como investigación y la función epistémica de los prototipos. El diseño como investigación se ha abordado desde la antropología de las ciencias ampliamente desarrollada por Latour pero también por las investigaciones propias del diseño como disciplina. Simon (2017) marca la diferencia entre la investigación en diseño y el diseño como investigación. La investigación como diseño hace uso de métodos mixtos para responder una pregunta problema comunmente relacionada con un producto. La investigación como diseño, por el contrario, piensa es las maneras como se investiga y las conexiones con el pensamiento en diseño relacionado con el representar gráficamente y el hacer. En este punto es donde se presenta la función epistémica de los prototipos pues a través de ellos, desde el diseño, se piensa el problema en si. 

Quisiera señalar que si bien es posible hablar de fracaso, la observación del proceso me permitió reconocer una manera de abordar un problema de conocimiento en el cual la investigación como diseño (Grand, 2017) permite refinar el problema y generar al menos dos situaciones: 1) mientras el tema general se mantiene ( construcción de conocimiento colaborativo-relaciones seres humanos-plantas-plataforma digital) el problema y por consecuencia la pregunta de investigación y los objetivos empiezan a iterar alimentados de abordajes conceptuales y experimentos técnicos nuevos y 2) los prototipos en tanto objetos observables se presentan como medios para refinar el mismo problema.  Este modo de proceder me permitió hacer procesos exploratorios para la definición de un problema en un campo como las humanidades digitales el cual al ser interdisciplinario implica en muchos casos la observación e inclusión de aspectos emergentes. Al respecto hago una diferencia entre un modelo que desarrolla infraestructuras para la investigación en humanidades digitales (figura 1), un modelo que integra en un objetivo diferentes áreas de conocimiento para el desarrollo integro de un prototipo digital (figura 2)  y un modelo que hace del prototipo una ruta para pensar el problema  de las relaciones humanidades-infraestructuras digitales 





(figura 3). 


￼
Figura 1. Creación propia


￼
Figura 2. Creación  propia.

￼


Figura 3. Creación propia.

Los tres modelos responden a proyectos de diferente naturaleza. EL primero nos remite a los proyectos que desarrollan o implementan tecnologías digitales para poder explorar campos difícilmente abordables por las y los investigadores. Arqueología, lingüística (computacional) estudios literarios entre otras áreas, han impulsado el desarrollo o la implementación de herramientas digitales que permiten trabajar con un corpus considerable y así, reconocer hipótesis de trabajo, hacer hallazgos. Bases de datos, exposiciones virtuales, visualización, geo-referenciación, mapeo, corpus lingüísticos, ocurrencia de palabras y contextos de uso, referencias textuales, análisis figurativos-semióticos de pictogramas, jeroglíficos, etc, son algunas de los resultados de estos modelos que son en alguna manera herramientas de recolección, organización y análisis de datos. 

El segundo modelo responde más a proyectos que trabajan factual o hipotéticamente con una comunidad de usuarios que pueden necesitar o serles útil una herramienta en particular.  Al reconocer una comunidad usuaria eso implica un abordaje en el cual el problema a resolver debe necesariamente dialogar e incluir claridades legales, éticas y de gestión (sobre todo sostenibilidad) del proyecto. Redes sociales temáticas, diseño de video juegos, proyectos transmedia, páginas interactivas, wikis, blogs, son algunos de los proyectos que resultan. En este modelo tanto la informática comunitaria como la informática social han tenido un papel importante pues están enfocadas en resolver problemas mediante la tecnología. Es por así decirlo una solución técnica a un problema social. La falencia de este modelo es su determinismo tecnológico y la ausencia crítica de las tecnologías en sí. Está estrechamente relacionado con el diseño centrado en el usuario.

El tercer modelo permite salir de la lista de requerimientos a cuestionar las instancias fundacionales de las herramientas desde la experimentación con ellas mismas. Probar las diferentes plataforma e indagar críticamente las maneras como han sido diseñadas y las maneras como presentan el problema del o la investigadora. Este modelo permite relacionar tanto el diseño de una herramienta ( modelo 1) con la implementación del mismo ( modelo 2 ) en un marco de observación más amplio que el simple determinismo. Se parte del posible diseño, uso y apropiación de una herramienta pero se cuestiona el cómo, para qué, entre quienes se va a diseñar esta herramienta. Es preciso señalar que aquí el prototipo no es solo el resultado sino un elemento que permite refinar el proceso de manera crítica ( figura 4) Este modelo es muy cercano a las vertientes del diseño crítico y el especulativo los cuales se proponen ser dispositivos de reflexión sobre las “posibilidades de ser” en nuestro planeta y mediados muchas veces por tecnologías. 


￼
Figura 4. Creación propia

Prototipos para pensar las relaciones humanidades infraestructuras digitales


En muchos sentidos queda la sensación que el problema y el proyecto aparece delimitado y claro después de varios experimentos y debería ser este el punto de partida y el caso a narrar en la tesis. Pero como Latour ha insistido ( xxxx), es poco o nulo el conocimiento que desde la ciencia misma se produce sobre cómo se llega al conocimiento y en este caso al problema. 

En este sentido quisiera solicitarles la posibilidad de “prototipar” un modelo de informe de tesis que me permita mediante el ensayo y apoyada en esquemas, dar cuenta de este proceso. Es decir narrar las rutas en las que el problema fue iterando, los experimentos y los hitos que permitieron refinar el problema y finalmente la manera como las infraestructuras fueron abordadas desde la antropología para cuestionar su “objetividad” y “adecuación” a la hora de dar cuenta de una relación como las de seres humanos plantas cuya ocurrencia cultural desborda la relación “ descriptiva” “utilitarista” y “extractiva” que predomina en los modelos de archivo y enciclopedismo occidental. Igualmente es de mi interés el poder establecer las rutas desde las cuales me posicioné como investigadora. Si bien fue posterior a muchos de los ejercicios y fue mediante la lectura de diversa literatura, quisiera dejar huella de la manera como se transformó mi rol y lo que ello significa profesionalmente. 





###### Documetar

* Git 

* Marcos analíticos para los referentes

* Marcos analíticos para los prototipos

 



## Pensar las herramientas  ¿Cómo vemos y qué vemos a través de ellas? 











************





#### En el principio

El problema inicial se formuló como la necesidad de implementar una herramienta colaborativa -tipo wiki-  que mejorara la recuperación de conocimiento sobre las relaciones seres humanos-plantas a la vez que democratizara el acceso y producción de dicho conocimiento[7^]. Todo ese esfuerzo recaía en elegir una herramienta, adaptarla a un sistema curatorial, implementarla para un ejercicio de ciencia ciudadana. Sin embargo, a medida que se desplegaron los elementos a tener en cuenta en una implementación de esta naturaleza: aspectos legales, éticos, filosóficos y hasta económicos, el problema descubrió aspectos subyacentes a todo proceso de implemetación: la aparente objetividad de las herramientas y la ingenuidad frente a su incidencia -interferencia- en modos de pensar y organizar el significado y la experiencia. De ahí que me preguntara ¿Cómo se captura y da forma al conocimiento sobre la naturaleza en las herramientas informáticas? ¿Cómo damos forma a las plantas, personas, etc., cuando queremos representarlas digitalmente? ¿Pueden las herramientas colaborativas tipo wiki dar cuenta de las relaciones seres humanos plantas? y además, ¿pueden dar cuenta de múltiples maneras de relacionamiento?  

La primera vez que noté las dificultades para definir las plantas en un entorno digital estaba frente al dilema de cómo crear una "planta" en Omeka, un software libre creado para hacer colecciones de objetos digitales [6^]. ¿Podía capturar o crear digitalmente una planta como se hace en un proceso de digitalización desde un soporte análogo o en la creación de un libro, imagen, sonido digital? Para poder hacer un proceso análogo debía en principio crear la planta como un item en Omeka. Los items types en este software se corresponden a las entidades en las bases de datos. Es decir "cualquier objeto (real o abstracto) sobre el cual queremos tener información en la base de datos" (Conabio, s.f). En esta plataforma las entidades estan pensadas por tipos -types- que se corresponden a tipos de documentos digitales (textos, sonidos, imágenes, representaciones visuales) o digitalizados (libros, fotografías, música, etc.), recursos (páginas web, historia oral, eventos), individuos (personas), entre otras entidades. Fue así que creé "Planta" como un item que además decribí como "individuo" [Ver: Tesis_item_planta.jpg] Si bien esto era un proceso que pasaba por una acción técnica, al crear una entidad es preciso establecer los atributos ¿Cuáles los atributos de una planta? ¿Nombre? ¿Forma? ¿Componentes?. En este software los atributos de todo objeto digital están estandarizados por un conjunto de metadados denominados dublin core. Este estandar de metadatos "datos que estructuran un dato" [7^]. están pensados para objetos digitales más que para individuos: personas o plantas. Es decir que allí existía una segunda dificultad. Al tomar una fotografía de una planta y subirla a la plataforma no era el "objeto digital imagen" lo que sería descrito sino el objeto retratado. ¿Cómo adecuarme a esos metadatos o encontrar algunos alternos? Pero más allá del uso de uno y otro metadato ¿Qué son de la planta los metadados? 

En este punto el problema era cómo hacer el modelado de datos como prerequisito para poder hacer prototipos en diferentes software. Pero este problema que era en apariencia un asunto técnico devino en una exploración sobre los tipos de bases de datos, la creación de las mismas y los conceptos subyacentes. De ahí que la pregunta de cómo dar cuenta de las relaciones seres humanos plantas en una plataforma colaborativo tipo wiki, desecandenó en una serie de preguntas sobre la naturaleza de diferentes software, los presupuestos sobre las relaciones seres humanos plantas, los aspectos éticos y jurídicos a tener en cuenta y las discusiones conceptuales sobre las plantas. ¿Qué es al final de cuentas una planta y cuáles las relaciones que ella tiene con nosotros? Si la entidad planta se describía como un individuo ¿Q
ué implica definirla como individuo? ¿Cómo se puede evidenciar la agencia que tiene la planta en la construcción de conocimiento que sobre ella se trasnfiere a un entorno digital? 

Pero no solo en el hacer con las herramientas surgieron las preguntas. La revisión de los referentes y un estudio por menorizado de ellas me llevó a establecer requerimientos antes no tenidos en cuenta. Inicialmente el proyecto quería aportar a la estructuración e implementación en las comunidades de la Base de Datos del Centro de Estudios en Medicina Intercultura CEMI, organización que viene adelantando con la Universidad del Rosario un trabajo exhaustivo y riguroso en los sistemas de medicina tradicional en Cota Cundinamarca y en el Vaupés. Esta base de datos tenía la infraestructura para ser colaborativa pero tenía al menos dos problemas: no tenía quien la alimentara y no contaban con un sistema de curaduría que permitiera verificar la calidad y pertinencia de la información dispuesta allí.   En conversaciones con quien en su momento era el gerente de proyectos establecí algunos compromisos frente al proyecto que en principio establecían claramente que mis intereses no eran económicos, que toda la información e incluso la base de datos era propiedad de la organización y que mi aporte estaría en el marco de una recomendación. El análisis de esta Base de Datos requirió de la lectura de los términos y condiciones y a la conversación con la abogada experta en propiedad intelectual y conocimientos tradicionales. A partir de allí empecé a reconocer las bibliotecas digitales que trabajaban temas etnobotánicos, las aplicaciones que en colombia abordaban este tema, desarrollos tipo wiki y otros sistemas colaborativos.  Inicialmente buscaba responder los siguientes temas:

1. Plataformas etnobotánicas
2. Plataformas colaborativas
3. Sistemas de estructuración y recuperación de la información
4. Tipo de vinculación de las personas y las comunidades en las plataformas
5. Vocbularios controlados sobre etnobotánica
6. Catalogación de conocimientos etnobotánicos



![](/Users/juanaespinosa/Tesis/001_Tesis Git_esquema/Esquemas/esqu_Referentes_V4.png)



Plataformas etnobotánicas como tal encontré tan solo 1 año y medio después de empezar la investigación tras muchas búsquedas. El desarrollo llamado TAMI es un proyecto liderado por investigadores de la Universidad Charles Darwin de Australia. Este desarrollo es el resultado de una reflexión sonbre el desarrollo colaborativo de software con comunidades y la discusión del desarrollo mismo. El resultado es un software adminsitrador de archivos digitales que no preestablece un sistema de captura del conocimiento mediante formularios sino que es estructurado por la comunidad misma. Est o introduce en la investigación el concepto de ontologías planas. Una discusión que cuestionó todos los procesos de catalogación del conocimientos tradicionales recomendados por la OMPI y la configuración misma de los formularios de la wiki semántica. 

Cada una de los referentes fue descrito a partir de los siguientes categorías



* Nombre
* Descripción
* Objeto
* Antecedentes
* Catalogación
* Búsqueda
* Términos y condiciones*
* Protección saberes tradicionales
* Búsqueda
* Usabilidad
* Documentación
* Autores
* Aportes al proyecto  

En github pueden revisar la Wiki donde está cada una de las descripciones.

**¿Qué aportaron cada una de estos referentes?**

ESQUEMA 



CEMI: discusión sobre los terminos y condiciones e inclusión de la necesidad de un protocolo curatorial.

Biblitoecas digitales: estructuración de la información y necesidad de trabajar con 





 En Colombia tuve noticia de un desarrollo tipo wiki que había desarrollado el Humbold llamado Yoscua que por asuntos legales no continuó. Ya desde el inicio del proyecto tenía algunas alertas sobre las dificultades de las plataforma







Como grafico en el esquema siguiente los referentes consultados para ver modelos de sistemas colaborativos o no de conocimiento etnobotánico me permitieron ir pensando el problema. Que inicialmente se formuló como una la identificación, adecuación e implementación de un software colaborativo a pensar el problema mediante los prototipos y pensar un softawre que problematizara los problemas encontrados. 



Los prototipos 

Las pruebas empezaron con sistemas de relaciones entre metadatos, esa información que describe un objeto digital bajo aspectos comunes y generales a todos los de su mismo tipo. De base, ese software, permite activar el Dublin Core Extended, un estandarización de metadatos que permite construir colecciones estructuradas para que la máquina recupere mejor la información, intercambie con otras plataformas y en resumidas haga de la web una sola cosa, interdependiente. Los item relations, la red posible de relaciones entre items que son fragmentos, derivados o parte de un mismo objeto, me permitían decir que **amaranto** is version of/ is part of/ _Amaranthus hibridus_ . Así era posible vincular uno y todos los nombres comunes con ese identificador único de una planta. La plataforma lo podría hacer no sin un trabajo desmedido. Tocaba para cada nombre común hacer una entrada única y vincularla a esa planta "maestra". El trabajo no era colaborativo. Una tarea que además ya había adelantado la Universidad Nacional con su paltaforma de [Nombres comunes de plantas de Colombia] (http://www.biovirtual.unal.edu.co/nombrescomunes/es/). Si ya existía, abría que buscar interoperabilidad. Pero más allá de que existiera el "nombre científico" asignado al metadato "título" ¿era este metadato de la planta, su identificador?. Por más que vinculara nombres comunes a un nombre científico ¿Cuál era la autoridad para decir que ese nombre es la planta? Esta es entonces la historia del trasegar de la reflexión  materializacion de la representación digital de las plantas y sus relaciones con los seres humanos. De cómo las plantas entraron a esta tesis vistas como objetos y se volcaron a ser sujetos, actantes que están en relación con los seres humanos para dar cuenta de sus beneficios, preferencias y dinámicas. Recorramos el diagrama





![](/Users/juanaespinosa/Tesis/001_Tesis Git_esquema/Esquemas/esqu_Referentes_V4.png)



**Prototipos**



Empecemos por su identidad. Toda planta al construirse como una entidad en una base de datos debe ser identificada de manera única (llave primaria) para poder establecer relaciones con otras entidades (Lugar, usos, etc). Principio universal de las Bases de Datos: cada entidad debe tener una llave única. Pero ¿cuál era ese identificador único de una planta? El nombre, pensé. El nombre científico. Aún así, conozco muchas plantas de los jardines que he habitado y de ninguna se su nombre si bien se que a unas llegan abejas, a otras mosquitos blancos, que otras nunca florecen en el encierro y que las ventanas es el lugar preferidas de esas otras que mi amiga llama Anturios. Pero además, sabía en ese entonces que existían cientos de nombres comunes para referierse a una planta ¿Qué había de la alegría, el amaranto, los quelites en ese _Amaranthus hybridus_? El desarrollador nuevamente me miró con sospecha. Estaba la pantalla y el cuaderno garabateado: Ese amaranto del que hablo tiene muchas maneras de ser nombrado -Camilo- y, cómo hacer para que todas esas maneras ¿sean la misma planta, de semillas milagrosas y penachos fuccias, un poco rastreras, salvajes y malezas ellas? La identidad de la planta tiene un código de identificación: el o los nombres científicos. Pero esta es una asignación que se establece desde la biologia. ¿Podría existir una llave primaria más cercana a la planta como planta? ¿Su imagen? 

#### Documentar

![](/Users/juanaespinosa/Tesis/001_Tesis Git_esquema/Esquemas/esqu_git_v1.png)



Tanto la retrospección como la prospección son acciones involucradas en la
documentación, un ejercicio de desandar para seguir andando, un método
como es el caso de la etnohistoria, que permite viajar en el tiempo para detallar descripciones, encontrar rutas, comprender decisiones y cuestionar la
presencia de actores como pueden ser narrativas e incluso artefactos. Así,
documentar entendido como un arte (Lafuente, Gómez, Freire s.f) se inscribe
como un ejercicio para hacer visible procesos de aprendizaje.

¿Cómo se llegó a un aprendizaje? ¿Cómo ese nuevo conocimiento emerge
durante el proceso y de que maneras apoya o cuestiona otros conocimientos
previos? Las respuestas por parte de cualquier persona inmersa en un proceso
de investigación o de creación puede ser sucinta, vaga, difusa. “Se nos ocurrió
así no más”, “ Estaba en un salón de té y vi un objeto que me pareció que podía
ser perfecto para desarrollar la idea”, “No se, simplemente sucedió después de
muchas horas de estar trabajando allí”. Si bien se construye una suerte de
milagro en el aprendizaje o la consecución de un nuevo conocimiento, es claro
que un análisis retrospectivo de múltiples elementos presentes en el proceso
puede dar cuenta de cuáles fueron las asociaciones, conversaciones, rutas,
rupturas, artefactos, etc., que permitieron llegar a ese “no se, simplemente
sucedió”.
En este capítulo desando las hojas de los cuadernos, los esquemas e informes
para dar cuenta del proceso. Ester proceso descriptivo de las prácticas que
realicé en las diferentes fases del proyecto de investigación sobre plataformas
de aprendizaje colaborativo y las relaciones seres humanos -plantas, lo abordo
desde el enfoque “tecno-etnográfico” que resulta de la lectura de Latour y su
perspectiva de la Antropología de la ciencia.
El abordaje “técno—auto-etnográfico” implicó ejercicios de revisión y tamizase
de información. Al respecto, opté por esquematizar los momentos de manera
gráfica y análoga, como ejercicio de síntesis de los diferentes soportes con los
que fui desarrollando cada momento de la investigación. En este esquema doy
cuenta de la manera como la pregunta de investigación iteró, pues considero
que al converger varias áreas en un objeto de estudio la formulación de la
pregunta no es a priori. Existe si un interés, una inquietud, pero es en el
“andante” que la pregunta empieza a definirse, a perfilarse una vez las
inquietudes toman escena en los vínculos entre los actores/actantes.
Considero que las personas interesadas en la creación o ideación de
tecnologías digitales situados desde la humanidades, tienen la posibilidad de
emprender ese arte de la documentación desde el ejercicio del registro de lo
que llama Latour “masas perdidas”. Es decir, registrar los vínculos de los
actores humanos y no humanos, la experiencia, el fracaso y los hallazgos
imprevistos como elementos imprescindibles del resultado, cual sea que fuese.
Como desarrollaré en las conclusiones el proceso del prototipado es en sí
mismo un resultado y un instrumento de recolección de información, de
cuestionamiento. El prototipo, pensando en latour, tiene agencia en la
definición misma del problema. Lo limita, lo expande, lo aprisiona. El vinculo
con la investigadora permite observar lo que allí sucede y seguir alguno de los
caminos dispuestos.

[5^]: La emergencia de las interdisciplians en las humanidades ha permitido explorar metodologías y métodos mixtos para poder encarar problemas. La etnohistoria por ejemplo ha recurrido tanto a la historia como la antropología y la arqueología para establecer diálogos transtemporales. Por su cuenta los estudios culturales son la intersección de prácticas investigativas de la economía, los mass media y disciplinas como la antropología, sociología. Por lo tanto un objeto de investigación es observado y construido por métodos mixtos. 

[6^]:  En las Humanidades digitales confluyen discusiones, metodologías y métodos de las ciencias de la información, la bibliotecología, el diseño, las artes, la comunicación, las ingenierías de desarrollo de software y las humanidades, entre otros campos. 



[7^]: La etnobotánica es la disciplina en la que confluyen la botánica y la antropología para aboradar las perspctivas de uso y aprovechamiento del entorno vegetal por parte de comunidades indígenas. Como disciplina nación en el siglo XIX y ha estado vinculada desde un inicio con la etnofarmacología. El interés como disciplina se ha enfocado en la capitalización de los saberes tradicionales por parte de farmacéuticas e industrias quienes la mayor parte se benefician de estos saberes para emprender investigaciones, crear fármacos. Una perspectiva más humanista de estas disciplinas busca descentran la nocion de la naturaleza como un objeto suceptible de explotación para pensarlo como una participante de la vida de las comunidades. Ver Zuluaga 2008 **Verificar definiciones y buscar la bibliografía**

[8^]: Se entiende por objeto digital el producto intelectual cuya materialidad digital-codificación numérica de la información- permite que sea publicado y acedido en tecnologías informáticas. "Frente a los DLOs están los no-DLOs, entendiendo como tales, por ejemplo, experiencias virtuales, bases de datos que generan "documentos como resultados" (Document-Like Outputs), o aplicaciones interactivas que pueden tener un contenido diferente según qué usuarios las utilicen". (96) Este concepto permite establecer sistemas de recuperación de información a partir de metadtos

[9^]: Metadatos Informaciones que hacen útiles los datos. Están destinados a ordenar y describir la información contenida en un documento entendido como objeto (DLO), de tal forma que se erigen como reveladores tanto de la descripción formal, como del análisis de contenido, en aras a mejorar el acceso a los objetos de información de la Red

## III Plantar la discusión: Las plantas como agentes, (abordajes interdisciplinarios perspectivas teóricas)

 

## V  De la Extracción a la siembra de datos colaborativa: rutas y prototipos

## VI  El lenguaje del botsque : prototipo para pensar la agencia de lo no humano en entornos colaborativos

## VII  Conclusiones

## VIII  Referencias

## IX  Anexos