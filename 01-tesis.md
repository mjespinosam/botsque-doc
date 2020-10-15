# El lenguaje del botsque: pensar los prototipos para integrar las plantas como agentes no humanos en entornos colaborativos





Pero si Dios  es los árboles y las flores                                                                                                                            y los montes y la luz de la luna y el sol,                                                                                                                       ¿para qué le llamo Dios?                                                                                                                                          Le llamo flores y árboles y montes y luz de la luna;                              
porque si él se hizo, para que yo lo vea,                                                                                                                          sol y luz de la luna y flores y árboles y montes,                        
si se me aparece en figura de árboles y montes  
y luz de luna y sol y flores,                                                                                                                                       es que quiere que le conozca                                                                                                                                       como árboles y montes y flores y luz de luna y sol.

​                                                                                                           _El guardador de rebaños. Fernando Pessoa_






[TOC]

## Índice





##   Introducción

Técnicamente esta tesis se logró a un año de presentar este trabajo. Implementé una wiki semántica etnobotánica (relaciones seres humanos-plantas), por medio de formularios estructurados con estándares de metadatos (Dublin core, Foaf), en una interfaz amigable. La wiki alimentaba colaborativamente una base de datos relacional a la vez que respondía a los requerimientos del proyecto: eficiencia en la estructuración, recuperación, migración e inter-operabilidad de la información y principios democráticos a la hora de construir el conocimiento de un campo específico, etnobotánica, mediante una estrategia colaborativa con comunidades. Sin embargo, aparecieron problemas de carácter conceptual, legal, ético y de diseño que reformularon el proyecto y sobre todo nombrarme como humanista digital. 

Al menos son dos los propósitos de las humanidades digitales: 1) implementar y desarrollar herramientas digitales para la investigación y transferencia de conocimiento de las disciplinas y 2) dialogar con las herramientas para dar discusiones conceptuales y teóricas.[^1]. La primera perspectiva se desarrolla a partir de conocimientos de las ciencias de la información, bibliotecología, archivística, ingenierías de sistemas, informática, electrónica, desarrollo de software, etc. Estas disciplinas disponen de metodologías que permiten a los humanistas organizar corpus de datos, hacer análisis de los mismos, visualizarlos, crear y gestionar colecciones o desarrollar software específico para analizar, comprender o resolver sus problemas particulares. A este modelo de implementación o desarrollo de herramientas desde perspectivas y necesidades humanistas se suma la posibilidad de hacer investigación sobre el diálogo entre los diversos campos de las humanidades y las tecnologías o herramientas digitales[^2]. Aunque una perspectiva no excluye a la otra, es claro que la primera busca implementar o validar un prototipo para resolver un problema. La segunda perspectiva por su parte, busca mediante la implementación y el prototipado experimentar para dar cuenta de las tensiones y posibilidades entre herramientas y conocimientos disciplinares [^3].

En este sentido, esta tesis explora la segunda perspectiva, al discutir cómo la implementación de herramientas colaborativas, en particular una wiki semántica etnobotánica (relaciones seres humanos-plantas) [^4] , me permitió reconocer en el prototipo un dispositivo experimental para pensar tanto el problema de las herramientas colaborativas, como las relaciones seres humanos-plantas. Es decir, las tensiones y diálogos entre herramientas digitales y conocimiento etnobotánico. Durante la investigación el prototipado de las herramientas, en sus diferentes fases e iteraciones, pasaron de metodologías de diseño participativo o centrado en usuarios a una metodología de diseño centrado en conceptos problema. De ahí que en el proceso emergieron todos los actores humanos y no humanos involucrados en dar cuenta de las relaciones plantas-seres humanos. A esta altura de la experimentación se refinó el problema, se precisaron los actores involucrados y emergió la pregunta de qué condiciones son necesarias para que las herramientas colaborativas se configuren como un espacio en el que humanos y no humanos -en este caso plantas- se integren como actores del conocimiento colaborativo. Esta pregunta, que parte del reconocimiento de las plantas como partícipes en la construcción de conocimiento sobre ellas mismas y cuya relación con los seres humanos puede modelarse mediante herramientas digitales colaborativas, solo fue posible una vez recorrí la perspectiva de implementación de herramientas colaborativas para una necesidad de una comunidad y me encontré con una perspectiva crítica del diseño, que replanteó los dos elementos transversales a la tesis: las plantas, el software colaborativo e introdujo -sin saberlo- la experiencia como eje articulador. 

Abordar la agencia de la plantas como actores en la construcción del conocimiento colaborativo en herramientas digitales introduce en las humanidades digitales las discusiones sobre lo no humano que abordan las pos humanidades desde la filosofía, la antropología y estudios de la ciencia en diálogo a la biología, la teología y la etnografía [^5]. Si las indagaciones sobre las maneras como se comunican las plantas están en campos experimentales aún, ya se reconoce que tienen memoria y por lo tanto aprenden. La noción de una naturaleza que habla y un ser humano que escucha e interpreta lo aborda la ecosofía y en particular el pensamiento de Raimond Pannikar para quien el hablar es una cualidad del universo al comprenderlo teológicamente. Esta propuesta dialoga con la perspectiva semiótica de Peirce para quien nuestra realidad es semiótica y la capacidad de producción signica no recae en una mente humana. Estas posturas, que vinculo a referentes en el campo de proyectos digitales, serán abordadas en el apartado **Plantar** En este apartado, a mode de marco teórico, conceptual y de referentes, establezco los parámetros para la comprensión de las plantas como seres no humanos que siguiendo a Pannikar (**año** ) nos "hablan"  y a quienes "conocemos mientras nos conocen". Bajo este presupuesto el conocer ya no es el resultado de una experiencia de los sentidos y por lo tanto observable supeditado a leyes, si no, por el contrario, una experiencia interdependiente en la que no hay sujeto y objeto. Este modo de aproximarse al conocimiento y a la vida se contraponen al paradigma cinetífico heredado de Descartes que introdujo en la epistemología el uso del experimento controlado como la vía de conocimiento del universo. Para entender este cambio de punto de vista abordo en este capítulo la experiencia, concepto que nos permite trascender a la noción de experimento cómo vía de acceso al conocimiento. La experiencia por lo tanto, vincula en términos de Pánikkar tanto "lo divino, el logos, el pneuma". Es decir que pensamiento cuerpo y espíritu son vías de conocimiento dependientes y presentes en todo camino al conocer.  Estos modos de conocer han sido reportados por la Antropología, al indicar que hay modos no científicos de conocer la vida, las plantas -por ejemplo-. Ante las preguntas de ¿Cómo saben las comunidades que una planta es alimento, veneno, puede serles útil para una u otra cosa? Este saber es parte de una relación en la que las plantas, como indican las comunidades, dan información y el ser humano lo recibe de diversas maneras: por los sentidos, por la escucha, por los sueños (Terangpi et al., 2015). De ahí que dar esta discusión desde las humanidades digitales me permite construir un diálogo interdisciplinario de los retos que hay en la implementación o diseño de software que quiera integrar otras ontologías en las que las plantas son miembros y participes de las realidades, en las que las plantas hablan y los seres humanos escuchamos.  

En un segundo capítulo "Metodologías injertas"  recorro y propongo una ruta metodológica para documentar los presupuestos como los métodos utilizados en cada prototipo. Aquí se hace explícita la manera como se integran los saberes interdisciplinares como las prácticas en las Humanidades Digitales. Documentación indispensable para entender cómo llegué al problema. Por que para "plantar el problema" fue preciso recorrer un camino en el que la experiencia se vinculó al prototipado. ¿De qué manera llegué al problema de esta tesis luego de varios prototipos? Es decir, ¿cómo investigué en tanto humanista digital? ¿De qué manera conocí lo que conocí? ¿ De qué manera organicé el material y cómo decidí comunicarlo?  Preguntas de carácter ontológico, epistemológico y metodológico que abordan la discusión sobre la investigación como diseño, una discusión que desde los años ochentas valida el diseño como una vía de conocimiento. Discusión que me permite situar el prototipo en las humanidades digitales como una herramienta argumentativa. En este sentido, hago una propuesta de documentación utilizando Git, el sistema de control de versiones y Git hub como una plataforma en la cual acopiar datos textuales y visuales. En cuanto a la investigación misma realizo un recorrido por las metodologías de diseño abordadas -de manera más intuitiva que predefinida- en los diferentes momentos de la investigación junto a los referentes y prototipos que fui desarrollando. Un recorrido que implica un giro metodológico que coincide con la incongruencia del prototipo final de una wiki semántica, la oportunidad de hacer un laboratorio de electrónica y plantas y la apertura a las discusiones del diseño crítico y especulativo. Este recorrido me permite afirmar que las perspectivas críticas y especulativas del diseño involucran metodologías que permiten expandir las relaciones entre los artefactos, herramientas y humanidades. Desde allí es posible pensar los problemas que emergen de la vida y las disciplinas.

En el tercer capítulo: Mil país: Una wiki etnobotánica presento el prototipo realizado que detonó el problema subyacente. En la implementación de esta wiki emergieron al menos tres discusiones: el modelo extractivista que impera en la relación con la vida, con la naturaleza y por lo tanto los riesgos que implica la gestión de conocimientos etnobotánicos tanto por ausencia de legislación como por asuntos éticos; las implicaciones de las bases de datos relacionales en la organización de saberes interdependientes en tanto preestructuran el saber y finalmente, el marco conceptual y las posibilidades de desarrollar herramientas digitales que vinculen en el acto de conocimiento de la naturaleza la escucha de lo que "hablan" las plantas. 

**Como conclusión presento "El lenguaje del botsque", el esquema para una herramienta colaborativa que integre la agencia de las plantas con el uso de un agente virtual "botsque" en un entorno colaborativo. Este proyecto de prototipo y con el que concluyo este trabajo me permite "plantar el problema de las relaciones seres humanos- plantas", pensar " la siembra de datos antes que su extracción" e idear una herramienta desde un prospecto especulativo. Así, abordo el estatuto filosófico, telógico antropológico y biológico de la discusión de las plantas como un punto indispensable para pensar cualquier desarrollo de software o adecuación de uno ya existente. Aquí dialogo tanto con la ecosofía del filósofo y teólogo Reimond Pannikar, la Teoría Actor Red de Latour y la Semiótica de Peirce. Marcos teóricos que permiten abordar las plantas en tanto lo no humano que está en relación con los humano y que crea el conocimiento sobre sí mismas. Estas tres teorías tienen claras perspectivas metodológicas que fueron indispensables para abrir preguntas y pensar el prototipo**




[^1]: Las relaciones entre tecnologías digitales y humanidades han trasegado desde la computación humanista, la informática comunitaria, la informática educativa y las humanidades digitales. Si bien en ninguna de estos campos existen definiciones disciplinares con programas teóricos y metodológicos claros, todas emergen dentro de la cultura digital o cibercultura. Los abordajes para su definición presentan un campo múltiple de aproximaciones en las que prima lo heterogéneo, interdisciplinario. Ver: del Rio Riande, M. G., & González Garcí Blanco, B. (2015). Introducción a las Humanidades Digitales. Material Didáctico Sistematizado. 103. https://www.aacademica.org/gimena.delrio.riande/115 Cuartas-Restrepo, J. M. (2017). Humanidades digitales, dejarlas ser. Revista Colombiana de Educación, 72(1), 65-78. https://doi.org/10.17227/01203916.72rce65.78 Galina Russell, I. (s. f.). ¿Qué son las humanidades digitales? 1 Julio de 2012, 12(7). Recuperado 4 de diciembre de 2016, de http://132.248.9.34/hevila/Revistadigitaluniversitaria/2011/vol12/no7/5.pdf Rueda Ortiz, R. (Ed.). (2013). Ciberciudadanías, cultura política y creatividad social (Primera edición). Universidad Pedagógica Nacional. 

[^2]: Los estudios de las tecnologías tiene por objeto de estudio la tecnología y si bien da cuenta de las relaciones de los actores humanos y no humanos su objetivo no es pensar el problema mismo desde el uso o experimentación con la tecnología. Esta manera de investigar por medio del hacer con una tecnología está más cerca de las metodologías del diseño. 
[^3]: Como elaboraré en la metodología esta perspectiva coincide con lo que los diseñadores han llamado "Investigación como diseño" (Simon, 2015).
[^5]: En el 
[^6]:La etnobotánica es la disciplina en la que confluyen la botánica y la antropología para aboradar las perspctivas de uso y aprovechamiento del entorno vegetal por parte de comunidades indígenas. Como disciplina nación en el siglo XIX y ha estado vinculada desde un inicio con la etnofarmacología. El interés como disciplina se ha enfocado en la capitalización de los saberes tradicionales por parte de farmacéuticas e industrias quienes la mayor parte se benefician de estos saberes para emprender investigaciones, crear fármacos. Una perspectiva más humanista de estas disciplinas busca descentran la nocion de la naturaleza como un objeto suceptible de explotación para pensarlo como una participante de la vida de las comunidades. Ver Zuluaga 2008 **Verificar definiciones y buscar la bibliografía
[^7]:  Lo no humano en las humanidades se desarrollará en el apartado II. La filosofía permite un marco para el reconocimiento ontológico a lo vegetal (Ver: Michael Marder),  la antropología un abordaje de la construcción de realidad, sentido y comunicación con lo no humano (Ver :Latour (2014), Kohn (2013)) y la biología una expansión de sus preguntas sobre inteligencia y comunicación vegetal (Ver Gagliano (2017), Mancuso (2015) ↩



## I. Plantar



> _Debes preguntar de otro modo, debes sentirlo y quererlo, debes contemplarlo con un espíritu tan grande como aquél por que existe, antes de poder conocer la ley.  Emerson (1836)_

Ante la pregunta de qué manera dar cuenta de las relaciones plantas seres humanos de tal modo que las plantas sean consideradas actores de ese conocimiento y por lo tanto partícipes del conocimiento que se hace sobre sí mismas, en una plataforma colaborativa, es preciso establecer un marco teórico y conceptual que nos permita partir de una perspectiva de la realidad no objetivamente, que supere las nociones sujeto objeto y que integre lo no humano en la constitución del conocimiento. Esto implica reconocer y hacer participe de la experiencia del conocimiento a todo lo que no sea humano pero sobre todo, implica conocer la manera como otros entienden y conocen lo no humano, en este caso las plantas, para comprender e integrar esas otras epistemologías. Pero, ¿cómo abordar la participación de lo no humano en la construcción de conocimiento colaborativo en un entorno digital? En lo que sigue, me gustaría recoger tres reflexiones que superan el paradigma científico dominante que desconoce lo no humano: la Ecosofía desde la perspectiva de Raimon Pannikar y la Semiótica de Pierce. El primero, Panikkar, como marco teórico y los  Peirce, como marcos metodológico. A partir de estos dos autores construyo el principio de realidad desde el cual abordo esta investigación, que cuestiona el antropocentrismo  para indagar en una experiencia de la realidad de manera tripartita o como desarrolla Panikkar, intuición cosmoteándrica. Realidad que responde a esta intuición, relación entre lo inefable, divino, Theos;  lo terrenal, el cuerpo, la materia, kosmos y, el logos, el pensamiento, la razón.[1^].  Estos autores se entretejen con la pregunta de cómo comprender la planta como ser, su agencia y comunicación. Propuestan que permiten el diálogo con las discusiones que se establecen en la filosofía sobre las plantas sobre todo lo referente a Michael Marder y  respuesta a cómo piensan las Plantas, el manifiesto Cybor de Haraway y la aproximación de la bióloga Gagliano sobre el pensamiento de las plantas. Estos autores permiten pensar los desafios que tienen las herramientas colaborativas digitales cuyos objetivo sean integrar las plantas en relación a lo humano y por lo tanto a una pluralidad de modos de conocerse y relacionarse con ellas. 



##### Plantar el problema

¿Es posible integrar lo inefable, lo divino, como principio vinculado a lo terreno, a nuestra referencia material y al pensamiento o razón?[2^].  Partir de que esta integración es necesaria y deseable, así no se sepa exactamente cómo, marca un primer alejamiento del aparato teórico conceptual heredado de la modernidad de occidente para conocer lo no humano. Habituados a concebir la realidad como la expresión aprehendida por los sentidos, que opera bajo leyes universales determinadas por la razón y verificables a través de la experimentación, nuestra epistemología de entrada erradica toda posibilidad de conocer que no sea a través de la razón ( Pannikar, 1999, Sheldrake, 2020). No por ello la misma ciencia, sobre todo las humanidades, han venido desmontando esta historia del pensamiento y a la vez trayendo a la escena otras epistemologías. Pensemos por ejemplo, en la revisión de la naturaleza en occidente. La ecología crítica como la ecocrítica, señala la escritora e investigadora Gisella Heffer (2014), han llegado por varias rutas a dar cuenta de la constante representación de la naturaleza en la modernidad desde una relación dualista que la opone a la cultura y la cual está expuesta a relaciones de explotación en situaciones por ejemplo de colonización. Bajo las categorías de raza, género, clase y lugar, ya sea el ecofeminismo, la ecología social, la ecología profunda o el ecomarxismo, todas dicen en una sola voz lo mismo: el antropocentrismos y el androcentrismo son causa de la crisis ambiental. Por su parte, perspectivas latinoamericanas reivindican modelos de comprensión que instalan visiones plurales que pueden ser o no indígenas, que coinciden en una particularidad: hay formas de vida, de conocer y ser,  presentes y pasadas que invierten las crisis al reconocer lo no humano como coparticipes de la vida y que se oponen a esas perspectivas extractivistas (Simposio tierras raras, 2020). Reivindicación que parte en principio por el reconocimiento de lo humano y no humano como parte de la vida en todas sus dimensiones y de la vida como un misterio no explicable racionalmente. Pero ¿es posible vincular perspectivas no occidentales para investigar desde una academia cuyo punto de partida es precisamente que la realidad se conoce a través de la razón y los sentidos? Pero ¿por qué hacerme esta pregunta en esta investigación? 

Para poder abordar lo no humano en el marco de las relaciones plantas seres humanos se requiere un desplazamiento epistemológico de las propias maneras como se piensa, se siente y se vive la naturaleza. Cada sistema, cuyos esquemas conceptuales son implícitos, establece unos límites de lo que es posible preguntar y solo dentro de ese sistema se puede dar la verificación, la justificación, la búsqueda de evidencia. Este marco de referencia es el mythos que elabora Panikkar (1999), un mito englobante que direcciona nuestro pensar y nuestra acción según el lugar cultural en el que nos situemos: 

> Aquello en que creemos de tal manera a pie juntillas que ni siquiera nos damos cuenta de que creemos en ello (…) El horizonte de inteligibilidad en el que tenemos necesidad de colocar no importa cuál idea, convicción o acto de conciencia para que pueda ser captado por nuestro espíritu (…) Aquello que hace plausible, esto es, creíble el mundo en el que vivimos o estamos (…) Una galaxia que segrega su autocomprensión y, con ella, los criterios de verdad, bondad, y belleza de todas las acciones humanas (p.14)

El pensamiento de Raimond Pannikar (1918-2010) con su propuesta de la hermeneútica intercultural permite introducir el desplazamiento hacia otras epistemologías en función no solo de la comprensión sino del esclarecimiento de los presupuestos de realidad. Comprensión que se da mediante un acto de reconocimiento del "tu" en una conversión a su mythos. En la revisión de la hermenéuticas interculturales el filósofo de las religiones Carlos Miguel Gómez (2015) revisa las nociones de hermeneútica de la escuela alemana en la que se postula que toda tradición se rediseña a medida que una  comunidad de sentido " cuestiona sus prejucios, valida e incorpora otros nuevos". Pero, se pregunta Gómez (2015)

> ¿Qué ocurre cuando la interpretación no se orienta hacia la reconstrucción del sentido de aquello que habla ya en la propia tradición, sino hacia la comprensión de otro con el cual no compartimos una comunidad de sentido garantizada por la pertenencia a un horizonte de inteligibilidad común? ¿Es posible comprender una obra, entendida en el sentido amplio del término, a la que no estamos vinculados mediante la historia efectual, y que no nos interpela desde la intemporalidad, a la vez lejana y familiar, de lo clásico? ( p.25)

La respuesta viene con Panikkar quien elabora el pluralismo radical. Este reconoce que hay sistemas racionales que son ininteligibles porque no comparten la tradición de una comunidad de sentido mas esto no implica que no puedan comunicarse. Primero porque cada sistema no está cerrado y segundo por que en el encuentro, dice Pannikar, se da un intercambio en el que  además de generar sentido  vuelven símbolos a la vida pero también emergen nuevos símbolos» (Pannikar, xxxx p.20). Este proceso señala Gomez ocurre en tres momentos. La hermeneútica morfológica que implica iniciarse en el segnificado de una tradición particular por medio de la lectura comentada textos clásicos. Aquí todo ocurre mediante el análisis, comparación y argumentación. La hermeneútica diacrónica que implica conocer la visión de mundo desde la cual una obra es generada y finalmente la hermeneútica diatópica. Esta hermeneútica no busca superar una distancia ni de que exista un horizonte de inteligibilidad común sino un movimiento constante entre dos universos de inteligibilidad heterogéneos. Esto solo es posible si se hacen visibles los presupuestos desde los que hablamos. Estos principios se contrastan con los principios fundamentales de otra visión del mundo no para establecer algo como "más verdadero" sino al descubrimiento " en el encuentro con el otro, de ciertos elementos que se hallan en una relación de equivalencia homeomórfica en las dos tradiciones" (Gómez, p. x). Equivalencia que no es conceptual sino la reconstrucción contextual que da el significado una aproximación a la tradicción que, " requiere  transplantar el contexto que les da significado y que les confiere el horozonte en el cual puede ser comprendidos" (Panikkar, xxxx,p.x)

Para que esto pueda ocurrir se precisa una actitud imperativa, dice Panikkar,  un principio fundamental de la hermeneútica intercultural desde la cual ocurre una " suerte de conversión". Pannikar lo denomina "comprensión por convencimiento: no podemos comprender las convicciones de alguien a menos que de algún modo las compartamos"(Pannikar citado en Gómez, ) . Para Gómez esta es una suerte de comunidad de sentido en términos de Gadamer si bien no es un saber presupuesto si no un mode de convertirse a la verdad que se comprende. Es aprender otra manera en clave dialógica y transformadora. Una comunicación que ocurre dice, por fuera de "un logos común", se da entre personas, con un tu. "El otro es fuente autónoma de autocomprensión que no puedo asimilar desde mi perspectiva". Debe ocurrir una comunión transformadora a partir de un diálogo dialógico que llama Panikkar. Un diálogo que " tiene profundo significado religioso"

En este escenario ya la realidad del tu o del yo no es objetivable en tanto " soy parte de ella, soy en ella y no puedo separarme de ella"

> El diálogo dialógico asume un radical dinamismo de la realidad, esto es, que la realidad no es dada de una vez para siempre, sino es real justamente por el hecho de que está continuamente creándose a sí
> misma y no simplemente desarrollándose a partir de premisas y puntos de partida preexistentes (Panikkar xxxx, p.38)

Ante la pregunta por la comprensión y el diálogo con la naturaleza, las plantas, la imposibilidad es que los aparatos teóricos y conceptuales llegan a develar pero aún no revelan lo que implican esas experiencias de escucha, una experiencia que en el marco amplio de la experiencia representa una comunión con la planta, con la naturaleza. Pero ¿cómo relacionarse con ellas? ¿Es posible desde la hermeneútica de Panikkar, aproximarse a una hermeneútica vegetal en tanto la naturaleza es un tu, cuyo contexto es ininteligible pero posible de ser escuchado, como lo citan yerbateras, campesinos, indígenas y personas que se relacionan con ellas? 

Además de su propuesta hermeneútica intercultural en el pensamiento de Pannikar hay una aproximación a la ecosofía. Este neologísmo que está enmarcado en lo que se denomina ecología profunda, suele estar señalado por su apartamiento de un modelo racional y una postura política.  Lo que no menciona la autora es la vinculación a perspectivas teológicas e interculturales cuyos objetivos políticos son epistemológicos y hermeúticos y entre ellos autores como Pannikar, Arne Naes (1973) y Josef Estermann (2013) se adelantan a lo que no resuelven nuestros modelos de comprensión. Perspectivas que según lo afirmado más arriba integran lo sagrado como parte de la experiencia de conocimiento. En Panikkar no hay lugar para los dualismos si no que hay continuos por ejemplo entre lo que una cultura presupone el mythos y lo que piensa, la razón. Así la ecosofía no considera la naturaleza ajena al ser humano sino que está en relación con lo humano y lo divino, es, en relación. El cosmos, en el que está la naturaleza, aunque tiene aspectos regido por leyes, también es autónomo y crea con libertad. Y su conocimiento se puede dar tanto por métodos lógicos y científicos como por medios intuitivos y directos de quienes escuchan. Al entender acá la escucha como un acto de contemplación que integra el silencio.

La ecosofía es la sabiduría de y sobre la tierra que integra la relación entre el ser humano, el mundo y lo inefable. La tierra es vida, “descubrir la vida de la Tierra significa que podemos entrar en una relación personal con ella" (Pannikar citado en Meza, p.8). Perspectiva que comparten las comunidades indígenas americanas y desde la cual se integra sus prácticas políticas y culturales en comunidad con lo viviente. Así, la ecosofía marca una diferencia con la ecología que dice Panikkar:  "no dará sus frutos, como se está viendo, mientras se reduzca a una ciencia pragmática de una mejor explotación de las riquezas naturales. El mismo lenguaje corriente nos indica que no hemos cambiado de mentalidad: la Tierra como un simple objeto de ‘explotación de recursos’ –que hay que procurar que duren lo más posible” (p.90)

> La palabra Ecosofía, para empezar, no denota principalmente un genitivo objetivo: nuestra sofía, conocimiento, o más bien sabiduría sobre la Tierra o hábitat. No es una doctrina sobre el mundo (y sus ‘recursos’). Denota sobre todo un genitivo subjetivo, es decir, la sabiduría de la Tierra misma, de nuestro hábitat, de nuestra morada, que se descubre a nosotros una vez estamos abiertos a entenderla, a rendirnos ante el hechizo de lo que nos está revelando. Es la sabiduría de la Tierra, no la pericia humana.

En este punto el mundo vegetal integra un "tu" que comparte con el ser humano la vida y a quien podemos escuchar, por que a su modo "habla", se revela ante nosotros. Pero ¿Cómo es que las plantas piensan y qué es lo que de ellas escuchamos? 

##### Lo que las plantas piensan y pensar como las plantas

> "Por regla general, los creyentes de hoy creen que el hombre lo "sabe" casi todo sobre los lirios, sobre su reproducción, por supuesto, sobre la química de sus colores, sobre la función del polen, sobre sus tipos y variedades, su valor de mercado, sus utilizaciones simbólicas, su metamorfosis con la tierra y mucho más. [...] Observar los lirios no quiere decir clavar la mirada en ellos aquí o allá, ahora, antes o después. Conocer los lirios es más que situarlos en el espacio y el tiempo o analizar sus partes y funciones. Conocer es más que clasificar y poder predecir comportamientos." ([Panikkar 1998:6](zotero://open-pdf/library/items/IG9M8LUL?page=2))

¿Si el mundo se nos revela con su sabiduría en tanto ser viviente cuáles son nuestros modos para poder excuchar, para poder establecer el diálogo y la comprensión de lo no humano? Con la hermeneútica intercultural de Panikkar podemos pensar en los mythos de las comunidades que viven en comunidad con las plantas, pero ¿como comprender a las plantas mismas en tanto comunidad? ¿Podriamos tener entre nuestros dispositivos teórico conceptuales algunos que nos permitan establecer ese diálogo para la comprensión? 

 Michael Marder aborda el pensamiento de las plantas desde la filosofía. ¿Qué es el pensamiento de las plantas se pregunta Marder? ¿Cuáles sus maneras de ser? Para Marder el pensamiento de las plantas se refiere a cuatro ideas. El pensamiento propio de las plantas que no es cognitivo, ideacional o imaginativo que también llama "pensar sin la cabeza", lo que nosotros pensamos sobre las plantas, cómo el pensamiento humano es deshumanizado y convertido en vegetal al encontrarse con el mundo vegetal y finalmente la relación simbiótica en curso entre este pensamiento transfigurado y la existencia de las plantas. 

El primer punto para comprender ese pensamiento vegtal es la intencionalidad no consciente. De acuerdo a sus indagaciones en la biología del comportamiento de las plantas (Marder, 2013),  las plantas develan una conciencia prereflexiva que pertenece a la vitalidad misma a lo que llamaban los griegos el alma vegetal. Parte de esa intencionalidad reune el pensamiento vegetal en el que se da fe de la existencia de un recuerdo involuntario en las plantas, que no es consciente. Esta memoria denota la existencia de un pasado que puede ser recuperado en cualquier momento y además comunitarios: informan a sus congéneres de los peligros y cambios.  Es decir, son seres temporale y gregarios. Pero ¿de qué manera se recupera la información por parte de las plantas? Marder mencional dos casos emblemáticos. "Las hojas de cebada se desarrollan si se exponen a la luz roja siempre que tengan calcio. Su memoria les permite que si no tienen calcio y se les agrega 4 horas depués de la exposición a la luz roja, sus hojas se desarrollan. Por otra parte las pálntulas de nilo responden a los estímulos estresantes disminuyendo el calcio de su células. Tanto las hojas de cebada como el nilo o la mimosa señalan que los seres veetales retienen rastros en el recuerdo más que una proyección idealizado de lo sucedido en el pasado. Dice Marder " Concebida cada una de manera no antropocéntrica como una cualidad primordial, la memoria inherente a las plantas en los niveles celular y molecular, llega a describir cualquier red de rastros, de los cuales la conciencia es una instancia muy circunscrita. Es el mismo hecho o facticidad de la impresión, de una impronta, o mejor, un ex-print, lo que forma el registro de lo que un ser vivo ha sufrido durante su vida" (Marder, 2013 a, p.127)

Así, la memoria no consciente es solo un componente de la inteligencia de las plantas que dice Marder,  siguiendo a Shelling,  no es "la inteligencia viva, si no la inteligencia de la vida, en el continuo siempre cambiante de sensibilidad-irritabilidad" (p.127). Este contínuo entre sensibilidad e irritabilidad que marca un registro en la memoria se une a el no pensar de la planta, el pensar antes del pensar que en lo humano, dice Marder, es aquel actuar sin nuestras cabezas. Un pensar y una memoria desvinculadas de un sistema nervioso y cerebral que nos permite integrar la inteligencia como una cualidad no solo humana. Este pensamiento vegetal de conciencia no reflexiva es una noción cercana a cualidad primera de Peirce y al conocer de Pannikar, quienes señalan que hay una experiencia en la que no interviene el logos -pensamiento- pero en la que hay una revelación del universo. La intencionalidad no conciente de la planta dice Marder, no se dirige a sí misma, de ahí su no-identidad, su ser conceptual, en el que proliferan los significados sin necesidad de las representaciones conscientes. 

De este modo, para entrar en lo que podemos denominar hermeneuticas vegetal,  el humano que piensa como la planta -primer acuerdo de Pannikar: la conversión a su mythos-

> " se convierte literalmente en planta, ya que la destrucción del logos clásico aniquila aquello que nos distingue de los demás seres vivos [...]. Para ser justos, una persona vegetal no es la que ya no piensa sino, en una formulación más matizada, la que piensa sin seguir las prescripciones de la lógica formal y, por tanto, en cierto sentido, sin pensar. Intentemos entonces acostumbrarnos a la idea de que el pensar no es prerrogativa exclusiva del sujeto, ni del ser humano, y que, además de alterar la forma del pensamiento (que se vuelve inseparable de su opuesto, el no pensamiento) y cambiando su contenido (que incluye contradicciones), "pensamiento no idéntico" indica libertad de la identidad sustantiva y encerrada en sí misma de los propios pensadores." (p.134 )

La postulación de un pensamiento vegetal coincide con la teoría semiótica de Peirce en la cual el pensamiento no ocurre necesariamente en una mente humana si no que es una cualidad del universo. Al respecto dice el matemático Fernando Zalamea, estudioso de Peirce:

> Una de las fortalezas de la semiótica peirceana, y uno de sus mayores atractivos, es dejar la noción de "cuasi-mente" o contexto de interpretación, donde se efectúa la semiosis. Al liberar los contextos de interpretación [cuasi-mentes] de los matices sicologicistas de la mente humana,  y al permitir "cuasi mentes" arbitrarias, la semiótica peirceana adquiere un rango muy amplio de universalidad. Ya que la "cuasi-mente" puede ser medio protoplasmático ene le que la seimiosis  se constituye  en un proceso de crecimiento y asimilación de materiela en un vaivén entre licuefacción y cohesión 

Para Peirce igual que para Panikkar la realidad es tripartita. Y el signo es la relación entre un representamen un objeto y un interpretan. El representamente es algo que está por algo [un objeto que puede ser una idea, artefacto, suceso] para alguien el interpretante. Este interpretante como cuasi-mente no es necesariamente una mente humana y desde allí pueden producirse nuevos signos pues todo signo es antecedido por un signo. En palabras de Pierce "la relación triádica es genuina, esto es, sus tres miembros están vinculados por ella de una forma que no consiste en ningún complejo de relaciones diádicas" Tres son los signos segú Peirce:  íconos, índices y símbolos que serán desarrollados más adelante. 

Retomando la idea de las plantas como pensante Marder retoma a Husserl y su elaboración de la intención  como marca de existencia. Esta idea lo lleva a proponer que tanto humanos como plantas comparten esa intencionalidad prereflexiva y que por lo tanto, otorga a lo no humano existencia y agencia: "las existencias no humanas también tienen sus correspondientes intencionalidades, en algunos casos intersectando o subyaciendo al comportamiento inconsciente de otros cuerpos vivos".Y eso, ya lo he anotado,  es objeto de las investigaciones controladas en laboratorio y también en espacions abiertos, sobre pensamiento y comunicación en las plantas. Sabemos ya que entre plantas hay comunicación que se da tanto por vía del a emisión de compuestos orgánicos volátiles (COV) mediante las cuales advierten a otras plantas de peligros inminentes para que se preparen pese a que la distancia es limitada. Los COV son utlizados para atraer polinizadores, asegurar la reproducción y dar mensales de emergencia como solidaridad con las de su misma especie. Una acción de alerta que también ocurre cuando aparecen herbíboros y a quienes según la literatura científica las plantas escuchan a escondidas: "Para preparar una defensa contra los generalista las plantas escuchan al herbívoro" (Ueda et al., 2012, p.224). 

A esta capacidad de comunicar y la de su memoria se inscribe la del aprendizaje. Las plantas nos cuenta Gagliano, una bióloga especializada en el pensamiento de las plantas que hasta hace muy poco la ciencia se  ocupó del aprendizaje asociativo vegetal. Es decir el aprendizaje que ocurre a partir de un experiencia repetida de un mismo estímulo o suceso. Las plantas aprenden asociativamente con fines ecológicos que van desde buscar comida hasta cuidarse de los peligros que por el suelo o por el aire las acechan: "un estudio de 2014 demostró que las plantas pueden detectar el sonido de las orugas que se alimanetas y las causadas por viento o por insectos cantores" (Gagliano, 2017, p.2). Señales acústicas que refuerzan la eficacia de otros sistemas de señalización de las plantas como las de los COV. Esto llevó a la investigadora a insinuar que las planas tienen conciencia y subjetividad. Todo el proceso de evaluación que realiza la planta la lleva a utilizar "sus propias experiencias y y sentimientos como estados funcionales que motivan sus elecciones". En cuanto a la conciencia la investigadora aboga por una conciencia básica que se logró a través del aprendizaje asociativo y de los sistemas de valores. Marder no aborda la conciencia en los términos de Gagliano sino que habla es de la intención  y trata de la no -indentidad de la planta, que plantea más la intersubjetividad que la subjetividad en las plantas. Sin embargo, tanto la filosofía como la biología y la semiótica coinciden en que el pensamiento no se da en una mente humana y que el aprendizaje y la comunicación también se puede dar en las plantas. 


 ##### ¿Hablan las plantas? ¿Escuchamos a las plantas? Apuntes para pensar la comunicación interespecie

“_La sabiduría de las plantas: incluso cuando tienen raíces, siempre hay un exterior donde forman un rizoma con algo más, con el viento, un animal, los seres humanos_." _Michael Marder_

En Panikkar encontramos la alusión a la escucha como parte del encuentro con el conocimiento en la triada ser, hablar, pensar. El logos es la palabra escuchada antes que hablada. Antes de pensar se escucha. En su trabajo sobre la relación del ser humano y la naturaleza: una experiencia integral de vida Jéssica Sepúlveda elabora esta idea de Panikkar:

> "si la naturaleza habla, no quiere indicar que ella tenga lenguaje propiamente como el ser humano, y que se produzca un diálogo entre ambos. La relación es de otro nivel: la naturaleza habla, es símbolo de la realidad cosmoteándrica; donde el hombre participa de su habla, escuchándola, y siendo su intérprete, si sabe escucharla. Esta afirmación requiere desentenderse de la visión causal entre hablar y escuchar. (138)

Por lo tanto, la experiencia de la escucha es la puerta para el conocimiento de las plantas y para poder tener una relación con ellas:  “[...]el que habla es el hombre y la naturaleza a través del hombre cuando el hombre no se desentiende de ella y sabe ser su voz en vez de querer ser el dominador” (Pánikkar 2011 citado por Sepúlveda, p.143). Y ¿Cómo escucharla?

Al respecto propongo las siguientes acciones desde la hermeneútica intercultural o hermenúetica vergetal como la denomino, para activar la escucha como acto previo al habla y espacio de conocimiento entre los universos:

1. Comprensión del  mythos de las plantas en tanto  los signos que ellas hacen sobre sí según sus contextos 
2. Comprensión de mi mythos en tanto maneras como las pienso
3. Creación de analogías homeomórficas que permitan establecer estados del ser entre la sensibilidad y la irratibilidad
4. La traducción de los signos mutuos en señales acústicas
5. La contemplación mediante la escucha profunda y compartida

##### Referentes

https://www.bbg.org/visit/event/sonic_succulents_plant_sounds_and_vibrations_at_brooklyn_botanic_garden_by_adrienne_adar



https://www.instagram.com/p/CGT4hn9HlNj/?igshid=18bjt9h5fqemn



https://www.musicoftheplants.com/es/#eluid0e42bc3a

### Metodología para plantar el problema

#### Diseño crítico y especulativo para las Humanidades Digitales 

Desde los años noventas los diseñadores Dunne y Raby retomaron discusiones del diseño radical de los setentas para formular su manifiesto por un diseño crítico el cual  desvincula al diseño de la actividad centrada en la producción para un mercado para pasar a un diseño que piensa problemas sociales.  Pero sobre todo para cuestionar las ideas de aque la tecnología era buena y capaz de resolver problemas en todos los casos “critical design uses speculative design proposals to challenge narrow assumptions,preconceptions, and givens about the role products play in everyday life.” (Dunne y Raby,2013, pág.)En el manifiestode diseño crítico establecen que este diseño permite encontrar problemas, para hacer preguntas, debatir, imaginar el cómo podría ser el mundo, sopesar las implicaciones, provocar reacciones, diseñar conceptos, sitiuarnos desde lo ético Dunne y Raby (2013). Pensar el diseño más allá de la resolución de problemas sobre todo los estéticos implica el usar el diseño para establecer otro tipo de relaciones con la realidad. Esta actitud frente al diseño carecía entonces de una metodología que tomó forma con la definición del diseño especulativo y sus modos de indagar la ficción para comprender el presente. 

El diseño especulativo como lo exponen extensamente Dunne y Raby,  son idea posibles, futuros como herramientas para comprender mejor el presente. Estos futuros desde el diseño toman forma de escenarios que fundan preguntas como ¿qué pasaría si? Todo ello como vía para abrir debates. Es decir que se establece un vínculo con un mundo que podría ser más allá de un unívoco y moralista "debería ser". Para ello el diseño especulativo hace uso de varias herramientas o métodos por así decirlo: mundos ficticios, utopías y distopías, ideas como historias, experimentos de pensamientos, contrafacticos, escenarios de ¿que pasaría si? Estas herramientas vincualdas estrechamente a procesos creativos de la literatura, el cine y la arquitectura entre otras artes no se utilizan para predecir el futuro sino para pensar "los futuros". Así, todo este programa de investigación hace explícito un propósoto. político  y es hacer consciente a la ciudadanía de las consecuencias de sus consumos. 

_By acting on peoples’ imaginations rather than the material world, critical design aims to challenge how people think about everyday life. In doing this, it strives to keep alive other possibilities by providing a
counterpoint to the world around us and encouraging us to see that everyday life could be different_ (Dunne y Raby, 2013, pagers, x)

De este modo el diseño se encamina al diseño conceptual o de ideas. Este diseño es diferente al diseño desde las humanidades o el designe thinking en tanto no opera dentro de un marco de realidad, no experimenta con cosas para hacerlas mejores sino para pensar otras posibilidades. Es decir que la carga de la funcionalidad y pertinencia social no son principios transversales. Pensar desde el diseño conceptual es pensar desde lo no real, desde las ideas como dicen Dunne y Raby los ideales (pág. x). Estos futuros ficcionales, abordados desde diversas escuelas del diseño, dicen los autores, están estrechamene realcionados con la exploración de posibles futuros tecnológicos. En alguna medida esta exploración conceptual a través del modelo ya lo venía haciendo el arte, el arte conceptual. Exploración que en campos como el diseño de modas nos ha permitido observar la exploración de conceptos a través de materiales y formas. Pero también a través de biofuros, diseños que tienen una relación directa con la ciencia del laboratorio, con lo que sucede allí cuando se piensa la vida, la tecnología y la innovación. 

En este breve recorrido de la apuesta del diseño crítico y especulativo la pregunta es cuál es el diálogo con las Humanidades Digitales, por qué pensarlo como un referente metodológica, y cómo integrarlo. Ahora bien, investigar con diseño las humanidades digitales permite traer a la escena las tecnologías, herramientas e instrumentos existentes o por existir e indagarlas. Cuando Latour habla de la cajanegrización enfatiza en la manera como las tecnologías se obscurecen tras su inserción dentro de las realidades. El diseño crítico y especulativo indaga por principio esas redes inmersas en las tecnologías y por lo tanto abre preguntas sobre las implicaciones éticas. Si bien una buena parte de las propuestas en HD pueden ser abordadas desde el Design Thinkin, o el diseño con comunidades y desde perspectivas como la informática comunitaria (Gurstein, 2000), el diseño participativo con enfoque etnometodológico (Srinivasan, 2007), el diseño para la antropología o la antropología para el diseño (Escobar, 2016), todos ellos diseñan desde el presente. El aporte del diseño especulativo es que permite abordar escenarios futuros  y por ello aprovecha todas las herramientas para abordar el presente pero proyectarlo desde la imaginación, pero sobre todo desde el debate. En este sentido, todo diseño se convierte en un dispositivo para pensar-nos, para debatir y así nuevamente, el prototipo nos permite pensar el problema, indagar sus implicaciones y retos. Aquí ya las humanidades digitales dejan de posicionarse desde metodologías de la implementación de soluciones sino desde metodologías apra pensar soluciones y sopesarlas éticamente. Que se desarrollen herramientas digitales no es el propósito si bien desde el diseño especulativo si pueden surgir modelos y prototipos que no oscurescan sus intenciones y por lo tanto las redes que las producen y crean. 

No queda más que concluir con la importancia que tuvo conocer este diseño. Si bien dos de los prototipos de este proyecto están en el marco de este diseño, La mesa Huerta y El lenguaje del Botsque, el primer prototipo no estuvo dirigido conceptualmente desde este diseño. Es decir el modo de proceder nació espontáneamente en el marco del laboratorio de micro huertas en Plataforma Bogotá, dirigido por Mangle Rojo. Allí desarrollamos junto otros colegas proyecciones y posibilidades de pensar la vida vegetal y los modos de comunicación con ella. Unos meses después encontré en la oferta de la Universidad un curso de diseño especulativo que sin duda concretó y direccionó lo que habría de venir y es la reflexión misma de el diseño como investigación y la investigació como diseño en las Humaniades Digitales. 

![Esquema de iteración](https://github.com/mjespinosam/botsque-doc/blob/master/Esquemas/esqu-metodologia-003.jpeg)


##### Las raíces del problema

Pero, ¿cómo llegué a formular este problema? Como podré mostrar en el siguiente capítulo, llegar al problema que acabo de formular y al marco teórico que lo acompaña, fue el resultado de una serie de prototipos desde los que emergieron preguntas y se refinó el problema. Este trayecto, que da cuenta de un proceso de documentación de construcción de pensamiento interdisciplinario, me permite debatir las limitaciones del prototipo Milpaís. Este prototipo que cumplió con los objetivos del problema con el que empecé el proceso de tesis fue el detonante para cuestionar todos los presupuestos bajo los cuales daba cuenta de las relaciones plantas-seres humanos. En este sentido el problema pese a que en esta estructura aparece la pregunta, el problema y los referentes asociados al inicio, estos son resultados del proceso y no los antencedentes del proyecto en sí. 



























 

**Notas al pie**

[1^]: Intuición que es preciso aclarar, supera la la dialéctica pues descrubre la relación trinitaria, visión que ya enunciaba Peirce en su teoría semiótic que es tripartita y en la que al igual que Panikkar, descubre la acción creativa del universo, su libertad.  

[2^]: Ante el señalamiento de que esta es un discurso filosófico teologizante dice Jose Meza Rueda (2010) " no habría que olvidar su anclaje a la antropología teológica que lo salva de ser una simple cosmología antropológica en una ontología cósmica. De hecho, si por la religión el hombre se vincula con la realidad, por este mismo “religare” rompe los límites de un grupo humano particulardentro de la tensión no-dual inmanencia-trascendencia" (p.7)

**Referencias**



2 PANIKKAR, RAIMON. La intuición cosmoteándrica. Las tres dimensiones de la realidad, Trotta, Madrid 1999, 82.

PANIKKAR, Ecosofía, o. c., 114.

###  Metodologías injertas: perspectivas del diseño para las humanidades digitales

¿Qué hacer cuando una vez logrado el objetivo inicial de una investigación emergen aspectos problémicos? ¿Es posible que una tesis refute la tesis que la originó? ¿De qué manera relato, construyo, discuto y comparto las vicisitudes y los hallazgos de un proyecto? Pero sobre todo, ¿cómo llegué a saber más cosas sobre el problema de las relaciones seres humanos-plantas mediante la obervación, experimentación, análisis y reflexión de los prototipos logrados en el tiempo? 

La pregunta de cómo investigué lo que investigué y sobre todo cómo llegué a refinar el problema me llevó a observar un modo particular en el hacer: investigar como diseño, investigar con diseño. La investigación como diseño es una propuesta que tiene sus orígenes en los años ochentas con las reflexiones que hizo en su momento Zeisel. El autor aborda los puntos en común entre diseñadores e investigadores a la hora de afrontar una situación a indagar o investigar. Allí, dice Zeisel (1984), ambos crean conceptos o imágenes, formulan hipótesis o presentan los conceptos y luegos los ponen a prueba. La investigación como diseño es en todo caso más que un paralelismo en los pasos o procesos para investigar de las ciencias. Es una ruta para pensar los problemas desde la creación de artefactos, prototipos (Dunne y Raby 2013). Es una manera de resolver los problemas (Gray y Malins 2004) o, una ruta para encontrarlos. Una ruta que involucra el pensamiento visual y práctico al pensamiento conceptual, del modo que lo hace la ingeniería, por ejemplo (Grand & Wiedmer, 2010). Los prototipos por lo tanto son una representación de las hipótesis que permiten desde sí mismos, comprender o -simular- las maneras como se comportan los problemas en una materialización. Es decir, pensamos con los prototipos y por ello, podemos hablar de sus funciones epistémicas.

Posicionar a los prototipos como instrumentos con funciones epistémicas y que por ello nos ayuda a pensar y desarrollar el pensamiento, nos lleva a la pregunta de cómo ocurre ello. Si bien esta pregunta tendría que ser respondida desde las ciencias cognitivas o los estudios de la creatividad, la etnografía de los procesos creativos en la ciencia también nos permite precisar algunas vías para comprender este asunto.  Latour en sus etnografías de laboratorio y la constitución de la teoría actor red (TAR), discute el principio de simetría como horizonte para integrar tanto a lo humano como lo no humano en la producción del conocimiento. Por ejemplo las tecnologías de inscripción, por ejemplo la escritura,  el experimento, etc., son participes y protagonistas de procesos del pensamiento. 

> Cada vez más analistas conciben la tecnología de inscripción (procedimientos para escribir, enseñar, imprimir y registrar) como la causa principal de lo que en tiempos pasados se atribuía a fenómenos "cognitivos" o "vagamente culturales". Los libros de Jack Goody (1977) y, sobre todo, de Elizabeth Eisenstein (1979) muestran muy bien la extraordinaria fecundidad de centrarse en este nivel material que ha escapado a la atención tanto de epistemólogos, historiadores, sociólogos y antropólogos, porque la tecnología de inscripción les parecía demasiado obvia y demasiado simple. (Latour, 1983)
>
> 

 Así, además de la acción humana sobre el hecho a investigar, los dispositivos, artefactos y experimentos son actores que propician en sus interacciones, el conocimiento mismo. Latour habla de actantes y no de agentes entendidos estos como "cualquier entidad que produzca una relación o adquiera valor de significación [...], y éste podrá ser humano o no humano. El actante se definirá por su capacidad de producir una acción dentro de una trama" ( Tirado y Doménech, 2005 citado por Moreira,2012, p.64). Si bien esa tesis es objeto de múltiples controversias, como se tratará la segunda parte en el apartado _plantar la discusión_,  la teoría actor red nos permite indagar sobre el lugar del prototipo como "actante" en la construcción de conocimientos en humanidades digitales, una discusión que ya se viene dando.

En el artículo  Developing Things: Notes toward an Epistemology of Building in the Digital Humanities Stephen Ramsay and Geoffrey Rockwell (2012) postulan las herramientas digitales como "telescopios para la mente", instrumentos hermeneúticos a través de los cuales  -y con los cuales- interpretamos fenómenos. Esta analogía, utilizada originalmente por la lingüista computacional Margaret Masterman, no solo es provocativa sino polémica. ¿Pueden las herramientas ser en el ejercicio investigativo parte de la discusión y de la explicación por que en sí mismas tienen elementos que discuten, problematizan, explican lo que se está  investigando?  Aunque su integración como argumento esté mediado por un discurso -pensemos en la mediación del curador de arte y la obra de arte- las herramientas, artefactos, modelos y obras cuentan con argumentoss que pueden ser leídos  por quienes dominan su lenguaje. De ahí que se requieran procesos de traducción. Pero, ¿cómo contar estas historias, como traducirlas? ¿Cuál el esquema narrativo de una tesis que quiere dar cuenta de estos procesos? 

La traducción en la TAR proviene de la conceptulización de Callón. Para este autor la traducción se basa en "describir las acciones de los humanos y no humanos que intervienen en la fabricación de un hecho científico"(García Díaz, 2008, pág. 59). Estas acciones emergen para la comprensión y experimentación de un problema. Allí, en el encuentro con otros actores humanos o no, el problema toma nuevas formas. Por lo anterior, en esta tesis emprendí una búsqueda -podría decir que fui a las raíces- para dar cuenta de las tecnologías de inscripción mediante las cualés refiné, comprendí y expliqué las preguntas y los problemas para llegar a una formulación del problema final. 

##### Las raíces del problema: refinar preguntas y problemas

¿Qué es de la planta lo que una base de datos dice que es la planta? ¿Cuál es la participación de la planta en lo que sobre ella se dice en una plataforma colaborativa? ¿Puede ella colaborar en lo que de sí se dice y se construye en una plataforma que quiere poner de manifiesto las relaciones que tiene ella con los seres humanos? ¿Las plataformas colaborativas pueden dar cuenta de las relaciones plantas-seres humanos? La aparición de cada una de estas preguntas en esta tesis no fue un asunto a priori, si no el resultado de un proceso de investigación a partir de la consulta y estudio de referentes y el prototipado de plataformas colaborativas. Así, las preguntas fueron develando el problema subyacente al problema inicial. Pero, ¿es posible hacer una investigación sin un problema acotado? 

En las humanidades es usual que nuevas categorías aparezcan en el curso del desarrollo de la investigación. Generalmente se parte con unas categorías predeterminadas y aparecen nuevas categorías metodológicas o conceptuales en la medida que se expande el corpus teórico y se analizan datos (Rico de Alonso, 2005). Sin embargo, no es usual, ni metodológicamente deseable, que el problema cambie en el transcurso de la investigación. El problema responde a la identificación de vacios del conocimiento y su investigación tiene por objeto comprender, explicar y ampliar los conocimientos. Sin embargo, en esta investigación desde las Humanidades Digitales (HD) el problema fue un problema. Las rutas metodológicas de diseño de investigación de las humanidades, excepto los estudios culturales o la etnohistoria [^5] , no piensan en la confluencia de disciplinas para el abordaje de los problemas si bien en muchas investigaciones confluyen varias disciplinas. Por ello es usual que las investigadoras encontremos tensiones metodológicas antes los vacios del saber y el saber hacer en diversas disciplinas. Así, en esta investigación, como suele suceder en el diseño y en las artes, el problema tomó diversas materialidades -prototipos- y la investigación misma se encaminó a construir el problema interdisciplinariamente [6^]. Por lo tanto, el acotamiento del problema y su matertialización en un prototipo es el resultado de la investigación misma. Un recorrido que aporta a las discusiones de la investigación como diseño (Grand, 2010; Jonas, 2010), una metodología que fue determinante para todo el proceso (ver gráfico 4). Pero, ¿qué es investigar como diseño?

![Esquema problema de investigación](https://github.com/mjespinosam/botsque-doc/blob/master/Esquemas/esqu_problema_21.png)

Gráfico 4. Los prototipos en la investigación en Humanidades Digitales 

[5^]: La emergencia de las interdisciplinas en las humanidades ha permitido explorar metodologías y métodos mixtos para poder observar y dar cuenta de problemas desde diversas ópticas. La etnohistoria por ejemplo, ha recurrido tanto a la historia como la antropología y la arqueología para establecer diálogos transtemporales. Por su cuenta los estudios culturales son la intersección de prácticas investigativas de la economía, los mass media y disciplinas como la antropología, la sociología, el psicoanálisis. 

[6^]:  En las Humanidades Digitales confluyen discusiones, metodologías y métodos de las ciencias de la información, la bibliotecología, el diseño, las artes, la comunicación, las ingenierías de desarrollo de software y las humanidades, entre otros campos. 

##### La investigación como diseño

En las reflexiones sobre las metodologías de investigación en las artes y el diseño se  marca la diferencia entre la investigación en diseño y el diseño como investigación. La investigación en diseño hace uso de métodos mixtos para responder una pregunta problema comunmente relacionada con el desarrrollo de un producto [^7]. La investigación como diseño, a su vez, piensa en las maneras como se investiga en diseño y las conexiones con la investigación científica. Ambas improvisan, experimentan, crean artefactos e imágenes y finalmente llegan a conclusiones. En este punto es donde se discute la función epistémica de los prototipos pues a través de ellos, desde su diseño, se piensa el problema en sí. En el artículo *Design Fiction: A Method Toolbox for Design Research in a Complex World*  los autores Simon Grand y Martin Wiedmer (2010) presentan la discusión de las prácticas de la investigación científica como diseño y a su vez el diseño como práctica de investigación que desarrolla conocimiento.

> "Otra observación interesante es que las controversias en los estudios científicos sobre la investigación científica en general enfatizan cada vez más la naturaleza inherentemente constructivista e imaginativa de la práctica científica (Galison, 1997; Knorr Cetina, 1999; 2002), la importancia de la improvisación (Knorr Cetina, 2002) y experimentación (Rheinberger, 2001) para el proceso de investigación en general, o el papel principal de los artefactos (Knorr Cetina, 1999), las imágenes (Jones & Galison, 1998) o la materialidad (Galison, 1997) y su diseño en la práctica investigadora" (Grand y Wiedmer, 2010, pág.2 ).

 Al respecto, la observación del proceso de experiementación de esta tesis me permitió reconocer una manera de abordar un problema de conocimiento en el cual la investigación como diseño me permitió refinar el problema y generar al menos dos situaciones:

> Mientras el tema general se mantuvo (construcción de conocimiento colaborativo-relaciones seres humanos-plantas-plataforma digital) el problema y por consecuencia la pregunta de investigación y los objetivos empezaron a iterar, alimentados por abordajes conceptuales y experimentos técnicos nuevos.
>
> Los prototipos en tanto objetos observables se presentaron como medios  observar y refinar el   problema.  

Por refinar me refiero al esclarecimiento o descubirmiento de los problemas subyacentes a la formulación inicial(Ver: gráfico:6).  De ahí que en la investigación como diseño el refinamiento implicó procesos de resolución de problemas de al menos cuatro tipos:

1. Resolución por pensamiento lateral. Es decir el despliegue de todas las opciones posibles para resolver el problema sin apelar a la  lógica ni a la linealidad. Y esto como procesos de ideación. 
2. Resolución heurística de problemas es decir la utilización de reglas empíricas para llegar a una solución. Según Polya intervienen cuatro operaciones 1- entender el problema, 2- trazar el plan, 3- ejecutar el plan (resolver) 4- revisar. Este proceso, anota Juan Carlos López García  en su texto *Algoritmos y programaicón. Guía para docentes.* (2009 no es un proceso lineal sino dinámico y cíclico (Ver: gráfico 5)

![](https://github.com/mjespinosam/botsque-doc/blob/master/Esquemas/esqu-resolucionheuristica-v1.png)

Gráfico 5: Interpretacion dinámica y cíclica de las etapas propuesta por Polya.

3. Ensayo y error: como estrategia para el aprendizaje de la implementación de las herramientas: omeka, wiki semántica, git, etc.

4. Algorítmica: aplicación de pasos detallados para resolver un problema. Por ejemplo en el diseño de los experimentos y en la implementación de formularios en la wiki semántica.  

Cabe anotar que estos modos de resolución de problemas estuvieron muy relacionados con las metodologías de Soft System las cuales se derivan de los sistemas de información sobre todo basados en computadoras. Estos sistemas buscan mejorar una situación problémica aprendiendo del procesos de resolución del problema mismo desde una visión sistémica. Esta visión holística del problema permite ver el problema como un todo. Para ello se usan técnicas visuales de mapeo como gráficos, diagramas, ilustraciones, animaciones, etc. ([Gray and Malins 2004:92](zotero://open-pdf/library/items/GL9D93DZ?page=92)). 

![](https://github.com/mjespinosam/botsque-doc/blob/master/Esquemas/esqu-resolucionprobl-v3.png)

Gráfico 6: Esquema del proceso de resolución de problemas.

Finalmente estos modelos de resolución de problemas también se traducen en la creación de instrumentos de recolección de información. Ese es el caso del [protocolo para los laboratorios de prototipado](https://github.com/mjespinosam/botsque-doc/blob/master/05-protocolo_prototipo.md).  El protocolo integra un modelo de informe de laboratorio con un modelo de resolución de problemas heurístico el cual busca que se comprenda el problema, se cree un plan, se ejecute y se analice. El asunto es poder dar cuenta del proceso dinámico, iterativo y cíclico sin perder detalles, procedimientos y aprendizajes. Pero, ¿qué es documentar?

[^7]: usualmente el diseño se concentra en el desarrollo de productos más no es el único interés del diseño. Como se aborda más adelante hay diseño centrado en creación de productos pero también diseño centrado en conceptos.  Como trabajaré en el apartado de diseño crítico y especulativo poara las humanidades digitales y siguiendo a Dunne y Raby (2013) el diseño conceptual trasgrede la idea de utilidad y mercado desde la creación de artefactos especulativos para pensar el presente. 

##### La experiencia en la investigación

 "En este sentido, Hegel no pretendió nunca plantear la losofía como una doctrina abstracta, extraña a la vida, sino que buscó involucrarla siempre en el amplio mundo de la experiencia humana corriente." ([Gama :26](zotero://open-pdf/library/items/RFPVEIC5?page=3))

"La describe, en Fenomenología efecto, el tránsito de la experiencia humana a través de diversas conguraciones de sentido o acepciones de mundo, que no son meros constructos teóricos, sino que tienen un correlato real en formas sociales de vida histórico-concretas, pero al mismo tiempo muestra que este camino de la experiencia sigue una estructura racional determinada por el absoluto, con lo que se hace posible conceptualizar la experiencia real de la conciencia en los términos especulativos del sistema." ([Gama :28](zotero://open-pdf/library/items/RFPVEIC5?page=5))

El propósito de poner en consonancia una razón universal absoluta con las formas concretas de la experiencia humana encuentra muy pronto serios obstáculos para su cumplimiento. En primera instancia, una interrelación tal parece ir en contravía con la experiencia más inmediata del sentido común, para la que no hay una única dimensión de la experiencia, sino múltiples ámbitos de realización de la misma, y para la que dichos ámbitos parecen" ([Gama :28](zotero://open-pdf/library/items/RFPVEIC5?page=5))

"Así, espontáneamente tendemos a considerar como cualitativamente distintos los tipos de experiencia que hacemos frente al arte del tipo de experiencia cientíca, religiosa o de la experiencia intersubjetiva. Si esto es así, ¿cómo, entonces, defender que es una y la misma razón la que en todos estos campos se hace presente?" ([Gama :29](zotero://open-pdf/library/items/RFPVEIC5?page=6))

"Además, esta variedad de las formas de experiencia se complica aún más si se introduce la dimensión de la historia, pues resulta evidente que, aun en el interior de un mismo ámbito de la realidad, la experiencia humana ha asumido conguraciones diferentes en distintas épocas." ([Gama :29](zotero://open-pdf/library/items/RFPVEIC5?page=6))

"Pero el absoluto hegeliano no es solo sustancia en este sentido, sino que es sustancia viva o sujeto, es decir, no un fundamento estático ya acabado, sino un principio en desarrollo que va determinándose progresivamente en un movimiento de mediaciones internas, similar al que realiza un sujeto -el sujeto individual o el yo trascendental de Fichteen su proceso de autoapropiación. La" ([Gama :30](zotero://open-pdf/library/items/RFPVEIC5?page=7))

"De modo que cuando Hegel arma que «el absoluto ya está en nosotros», no se trata de algo así como una armación mística según la cual podemos buscar en nuestra interioridad, mediante alguna suerte de intuición mágica, el contacto con una esfera trascendente. Todo lo que arma es que en nuestras experiencias de mundo, aun en las más elementales, se hace presente una forma de racionalidad, que no debe ser vista en oposición a otras formas histórico-culturales distintas con las que ella sería irreconciliable ni tampoco como la racionalidad ya denitiva y suprema, sino, al contrario, como un estadio más en el desarrollo progresivo del absoluto" ([Gama :30](zotero://open-pdf/library/items/RFPVEIC5?page=7))

"El absoluto se presenta, pues, en cada conguración histórica de la experiencia humana encarnado en la racionalidad que es inherente a cada una de ellas y que determina sus particulares criterios de conocimiento y de acción." ([Gama :31](zotero://open-pdf/library/items/RFPVEIC5?page=8))

Quienes arman que la verdad se descubre a través del método cientíco no están en mejor posición, ya que, como hoy bien sabemos, todo el instruy los procedimientos de la ciencia no dejan inalterado mentarium el objeto, sino que buscan más bien ajustarlo a modelos explicativos preconcebidos." ([Gama :38](zotero://open-pdf/library/items/RFPVEIC5?page=15))

"Se verá ya claro cómo esta idea de experiencia dista mucho de las concepciones empiristas o cientícas que equiparan la experiencia con la percepción sensible o la normativizan en procedimientos metódicos." ([Gama :40](zotero://open-pdf/library/items/RFPVEIC5?page=17))

Lo que sucede es que en el lenguaje corriente solemos llamar experiencia tanto a la posesión de un saber como al proceso por el cual se ganó ese saber." ([Gama :41](zotero://open-pdf/library/items/RFPVEIC5?page=18))

"Hegel quiere llamar la atención sobre el proceso de la realización de la experiencia" ([Gama :41](zotero://open-pdf/library/items/RFPVEIC5?page=18))

"El verdadero hombre con experiencia no es aquel que por haber vivido mucho sabe de todo, sino justamente aquel que por haber vivido mucho sabe que su saber siempre es falible y susceptible de derrumbarse, del mismo modo que el hombre que tiene experiencia con las mujeres es quizás también aquel que ha sufrido más decepciones con ellas." ([Gama :41](zotero://open-pdf/library/items/RFPVEIC5?page=18))

"Frente al esquema instrumentalista, la estructura hegeliana del movimiento de la experiencia, o, lo que es igual, del proceso del conocimiento (esto es, la experiencia como inversión de la conciencia o negación determinada), no resulta una invención arti- ciosa, sino que, si bien solemos olvidarlo, se encuentra a la base de nuestras vivencias cotidianas, porque el conocimiento es metódico o instrumental solo en situaciones y ante objetos muy especícos, pero las experiencias corrientes, donde advertimos que ganamos en conocimiento, no funcionan aplicando un procedimiento externo, sino que surgen del convencimiento interior de que ahora vemos con claridad donde antes solo veíamos a medias." ([Gama :44](zotero://open-pdf/library/items/RFPVEIC5?page=21))

"El verdadero conocimiento de otro ser humano, para poner otro ejemplo, no se da al modo como uno acumula informaciones sobre un extraño, sino en tanto que, partiendo de los prejuicios que sobre él tengo, voy reformulando y precisando mi imagen de él a medida que hacemos experiencias comunes." ([Gama :45](zotero://open-pdf/library/items/RFPVEIC5?page=22)

##### Documentar los procesos de pensamiento

Tanto la retrospección como la prospección son acciones involucradas en la documentación, un ejercicio de desandar para seguir andando, un método como es el caso de la etnohistoria, que permite viajar en el tiempo para detallar descripciones, encontrar rutas, comprender decisiones y cuestionar la presencia de actores como pueden ser narrativas e incluso artefactos. Así, documentar entendido como un arte (Lafuente et al., 2018) se inscribe como ejercicio para hacer visible procesos de aprendizaje, confluencia de experiencias y procesos creativos. 

¿Cómo se llegó a un aprendizaje? ¿Cómo ese nuevo conocimiento emerge durante el proceso y de que maneras apoya o cuestiona otros conocimientos previos? Las respuestas por parte de cualquier persona inmersa en un proceso de investigación o de creación puede ser sucinta, vaga, difusa. “Se nos ocurrió así no más”, “ estaba en un salón de té y vi un objeto que me pareció que podía ser perfecto para desarrollar la idea”, “no se, simplemente sucedió después de muchas horas de estar trabajando allí”. Si bien se construye una suerte de milagro en el aprendizaje que también denominan resolución de problemas por "iluminación" (López García, 2009), es claro que un análisis retrospectivo de múltiples elementos presentes en el proceso puede dar cuenta de cuáles fueron las asociaciones, conversaciones, rutas, rupturas, artefactos, etc., que permitieron llegar a ese “no se, simplemente sucedió”.

Como ejercicio documental revisé todos los apuntes, diagramas, esquemas e informes para dar cuenta del proceso. Este proceso descriptivo de las prácticas que realicé en las diferentes fases del proyecto lo abordo desde el enfoque “tecno-etnográfico” que resulta de la lectura de Latour y perspectiva de la Antropología de la ciencia. El abordaje “técno—auto-etnográfico” implicó ejercicios de revisión y tamizase de información. Al respecto, opté por esquematizar los momentos de manera gráfica y análoga ( Imagen 1), como ejercicio de síntesis de los diferentes momentos, actores e insumos con los que fui desarrollando cada momento de la investigación. Un ejercicio para reconocer lo que Latour denomina las masas perdidas o inviables que más adelante sería apoyada por Git el sistema de control de cambios. 

![](https://github.com/mjespinosam/botsque-doc/blob/master/imagenes/esque-proceso-analogo.png)


Imágen 1: Esquema análogo de momentos de la investigación. 

> Latour, en cambio, sólo parece preocupado por estudiar el conjunto de actores
> humanos y no-humanos que co-participan en todos los procesos por los que atraviesa la
> fabricación y estabilización de un hecho científico o un dispositivo técnico. Este
> conjunto de actantes, lo que se corresponde con el criterio acumulativo tratado
> anteriormente, se denomina “las masas perdidas” o invisibles (the missing masses).  _Latour, Mixing Humans and Nonhumans Together: The Sociology of a Door Closer._(García Díaz, 2008)



##### Git: software de control de versiones

 Apoyada en la herramienta de control de versiones Git creada por Linus Torvals (2005), y ampliamente utilizada en el mundo del desarrollo del software, ideé una estrategia para organizar, categorizar y narrar los cambios que ocurrieron entre la creación de los prototipos y la revisión de los referentes. Esta narrativa permite hacer seguimiento a la persistencia del tema investigado -relaciones plantas-seres humanos- y la emergencia de preguntas, problemas e ideas así como, la integración de conceptos y referentes. Basada en el esquema annálogo (Imagen 1), desarrollé un experimento que emandó sistematizar todos mis archivos de versiones del proyecto y las notas de cuadernos, esquemas, etc. Ver: [Informe de laboratorio: Experimento Git](https://github.com/mjespinosam/ruta-metodologia/wiki/Experimento-GIT)

Ver grafico 7.

![](https://github.com/mjespinosam/botsque-doc/blob/master/Esquemas/esqu_git_v1.png)




Gráfico 7: Esquema control de versiones. Proceso investigativo y de prototipado. María Juana Espinosa.

El control de versiones Git permite registrar momentos en el tiempo de un proceso. Cada momento referenciado se registra a partir de un commit que es un comentario textual que resumen el avance, cambio, edición, adición etc., sobre el proyecto. Esto permit a quien desarrolla un software regresar a momentos del desarrollo anteriores al presente, apoyado por estas frases clave y visualizando los cambios sobre los archivos. Otro elemento que se destaca son las ramas. Desarrollos paralelos que se desprenden del desarrollo principal pero que no interfieren y que pueden volver a la rama princial una vez se resuelvan los problemas o desarrollen las funciones. Esta acción de unión de una rama se denomina merge. Si bien todo el flujo de trabajo en git está pensado para desarrollo de software, para el caso del control de cambios de un proyecto de investigación académica estimé necesario definir:

>1. La rama principal o Master / Tema transversal del proyecto.
>2. Los temas para hacer el seguimiento / Pregunta, Problema, conceptos integrados, ideas Integradas, prototipos, esquemas.
>3. Las ramas que se desprenden / Cada tema de seguimiento es una rama que se une a la rama principal en un prototipo del que a su vez se desprenden los nuevos temas de seguimiento.
>4. Los puntos de cambio en la rama principal / Cada prototipo es un punto de control de versiones donde se unen - o se hace merge en términos de git- los temas a los que se les hace seguimiento. 
>5. Merge final / una vez el problema está refinado y la pregunta del proyecto se desarrolla en un prototipo se realiza el merge. 
>
>

Como se puede observar en el gráfico 8,  cuatro fueron los prototipos del proyecto: wiki semántica, app cofechas, mesa huerta y finalmente el lenguaje del botsque. En los primeros dos prototipos las plantas no fueron asumidas como actores o actantes en la contrucción del conocimiento sobre sí mismas, pese a intuir su protagonismo. El giro metodológico se concretó en un artefacto "La mesa huerta", que implicó la discusión de las infraestructuras, herramientas y postulados ontológicos de los dos prototipos anteriores. ¿Que son las plantas? ¿Como se representan en sistemas informáticos? ¿Cómo se dan y cuáles son las relaciones plantas-seres humanos? ¿De qué manera ellas contribuyen al conocimiento que de sí mismas se registra en un entorno colaborativo? Estas preguntas me permitieron problematizar las herramientas y metodologías así como los presupuestos que subyacen a ellas.


![](https://github.com/mjespinosam/botsque-doc/blob/master/Esquemas/esqu-rutainvestiva-v2.png)

Gráfico 8: Esquema ruta investigativa.

El seguimiento en Git se realiza desde la terminal, con el uso de comandos específicos que permiten además conectarse remotamente con una copia de respaldo en Github. Github es un repositorio remoto que visualiza los procesos de control de versiones y permite trabajar colaborativamente en un proyecto de software o en este caso, para la discusión y refinamiento de ideas y problemas de un proyecto de investigación. Desde Github entonces, se completa la documentación de los prototipos y la escritura de la tesis. En el repositorio [Botsque-documento](https://github.com/mjespinosam/botsque-doc) está el control de versiones de la escritura de la tesis y como un submódulo anidado está el repositorio [ruta-metodológica](https://github.com/mjespinosam/ruta-metodologia). Los submódulos es una función de Git para tener en un repositorio otro repositorio de referencia conservando control de versiones separados. En el repositorio principal se pueden consultar los "issues" un espacio en el que trabajamos las discusiones del proceso concpetual, técnico y de escritura de la tesis. En el submódulo se encuentra la [Wiki](https://github.com/mjespinosam/ruta-metodologia/wiki), espacio en el que quedan detallados cada uno de los referentes del proyecto según unas categorías de análisis y los protocolos de los prototipos (ver: gráfico 9). Finalmente en el [readme.md](https://github.com/mjespinosam/botsque-doc/blob/master/readme.md)se presenta el proyecto y en la pestaña insights/networks se registran las rutas de los commits. Todo esto permite simular en la plataforma un trabajo de desarrollo de código pero con un desarrollo de la tesis. 

![](https://github.com/mjespinosam/botsque-doc/blob/master/Esquemas/esqu-marcoreferentes-v1.png)

Gráfico 9. Marco analítico de referentes para los prototipos de la investigación. María 

Ahora bien, el uso de Git como experimento narrativo, es un correlato del esquema análogo. Su uso no responde solo a una necesidad de control de versiones de un documento sino también al registro de un proceso de construcción de pensamiento, de documentación. El que durante más de dos años las preguntas hayan detonado nuevos experimentos y que además,  el problema después de todo ese tiempo se hubiese refinado al punto de llegar a intuiciones para un sistema comunicativo seres humanos-plantas es resultado del proceso en el que participaron actores humanos y no humanos. Con el uso de git se puede identificar los momentos del proyecto y los cambios en las formulaciones de las preguntas, el problema, la aparición de referentes. Este contro por lo tanto, desvirtua la idea de que todo proyecto es el desarrollo de una idea ya clara que tiende a reafirmar lo que allí se establece como hipótesis. Cuando lo que sucede es que dicha hipótesis es el resultado de la refinación del problema en  múltiples discusiones y hallazgos. En campos como las Humanidades Digitales en particular, documentar estas versiones nos permite identificar cómo las hipotesis tienen una serie de problemas conexos. Y es que al ser un área multi e interdisciplinaria, los aspectos a tener en cuenta emergen en el proceso mismo e inciden en los prototipos así como los prototipos inciden en los problemas. Pasemos ahora a ver este recorrido para entender cómo se refinó el problema y cómo llegué a el. 

### Metodologías de investigación exploradas  

En la búsqueda de dar respuesta disciplinar de cómo conocemos desde las HD la intersección entre las artes, el diseño, las tecnologías, las humanidades e incluso las ciencias  nos dan una primera respuesta: desde la mixtura. Es usual que en contextos investigativos de áreas interdisciplinarias o en el arte se de una apropiación y adpatación de metodologías y métodos de otras disciplinas (Gray & Malins, 2004). De ahí que el diseño dialogue con la etnografía, la investigación acción participativa, por ejemplo. En todo caso y como he venido mostrando la investigación diseño nos permite rastrear el cómo conocemos y diseñar caminos para conocer. Al respecto hago una diferencia entre metodologías mixtas que desarrollan herramientas para la investigación en HD (gráfico 10), metodologías centradas en comunidades e infraestructuras digitales  (gráfico 11)  y las metodologías centradas en pensar el problema en HD desde el prototipado (gráfico 12). 

Las dos primeras se dan en diálogo con las ciencias y las humanidades y fueron desarrolladas en dos de los prototipos, Milpaís y Cofechas, mientras que la tercera es una metodología propia de las artes y el diseño que implementé intuitiva y luego sistemáticamente en los dos siguientes prototipos: Mesa Huerta y Lenguaje del Botsque. 

#### Herramientas para las Humanidades Digitales (HD)

Los proyectos en HD suelen desarrollar o implementar herramientas digitales para poder explorar campos difícilmente abordables a través de la estructuración y análisis manuales de la información. Arqueología, lingüística (computacional) estudios literarios, sociología, entre otras áreas, han impulsado el desarrollo o la implementación de herramientas digitales que permiten trabajar con un corpus considerable y así, reconocer hipótesis de trabajo, hacer hallazgos. Bases de datos, exposiciones virtuales, visualización, geo-referenciación, mapeo, corpus lingüísticos, ocurrencia de palabras y contextos de uso, referencias textuales, análisis figurativos-semióticos de pictogramas, jeroglíficos, etc, son algunas de los resultados de estas implementaciones o desarrollos que son en alguna manera herramientas de recolección, organización y análisis de datos. Desde allí es claro emergen hipótesis y es posible hacer lecturas que difícilmente se podrían hacer por metodologías fenomenológicas. Esta perspectiva tiende más al racionalismo y dialoga con los métodos de las ciencias duras, metodologías cuantitativas. Trabajo de laboratorio, prueba de hipótesis y experimentaciones a partir de diseño de protocolos. 

![](https://github.com/mjespinosam/botsque-doc/blob/master/Esquemas/esqu-metodologia-007.jpeg)

￼
Grafíco 10. Creación  propia.

###### Los primeros experimentos con OMEKA

En esta investigación este modelo ha sido utilizado en diversos momentos. Sobre todo para empezar a identificar los requerimientos y las posibilidades para su prototipado en herramientas digitales disponibles. Para entenderlo, volvamos al inicio de los tiempos. El hilo conductor de todo el proceso han sido las relaciones seres humanos plantas. Inicialmente la investigación tuvo por objetivo la implementación de un software colaborativo etnobotánico - tipo wiki- . En ese primer momento el interés estaba dirigido a construir un referente para la adecuación de la [Base de Datos del Centro de Estudios de Medicina intercultural](https://github.com/mjespinosam/ruta-metodologia/wiki/CEMI). Un proyecto etnobotánico centrado en la construccion colaborativa de usos y aprovechamiento de las plantas. El preproyecto titulado "Savias wiki, una wiki etnobotánica" (2017)  estaba formulado desde el trabajo realizados con anterioridad en el colectivo Savias Sabias y desde una perspectiva bibliotecológica, ámbito en el que había trabajado por varios años.  El proyecto primigenio tenía por objetivos secundarios: 

>* Estructurar  semántica de la información para una recuperación efectiva. 
>
>* Catalogar  los saberes etnobotánicos a partir de vocabularios controlados.
>
>* Incluir el lenguaje común -folksonomías- para aumentar o precisar vocabularios controlados.
>
>* Construir de manera colaborativa y democrática el conocimiento sobre las plantas y su aprovechamiento. 
>
>*  Georefereniciar conocimientos y plantas.

Estos requerimientos implicaban que debía aprender de la estructuración de información, el conocimiento de las bases de datos y las posibilidad de las plataformas wiki. En su momento este saber era rudimentario así que desde el Laboratorio de HD empecé por pequeños experimentos en Omeka, guiados por Camilo Martínez. [Omeka](https://omeka.org/about/project/) es un software libre creado por  el Centro de Historia y Nueva Media Roy Rosenzweig para la admnistración y y gestión de colecciones de objetos digitales[^8]  para museos, archivos y bibliotecas. En este software, propuesto por la maestría como herramienta para experimientos, fue la primera vez que noté las dificultades para definir las plantas en un entorno digital. En ese entonces estaba frente al dilema de cómo crear una "planta" en Omeka:  ¿Podía capturar o crear digitalmente una planta como se hace en un proceso de digitalización desde un soporte análogo o en la creación de un libro, imagen, sonido digital? Para poder hacer un proceso análogo debía en principio crear la planta como un item en Omeka. Los items types en este software se corresponden a las entidades en las bases de datos. Es decir "cualquier objeto (real o abstracto) sobre el cual queremos tener información en la base de datos" (Conabio, s.f). En esta plataforma las entidades estan pensadas por tipos -types- que se corresponden a tipos de documentos digitales (textos, sonidos, imágenes, representaciones visuales) o digitalizados (libros, fotografías, música, etc.), recursos (páginas web, historia oral, eventos), individuos (personas), entre otras entidades. Fue así que creé "Planta" como un item que además decribí como "individuo". (Ver: imagen 2)

<img src=" https://github.com/mjespinosam/botsque-doc/blob/master/imagenes/img-item-planta.png" style="zoom:150%;"/>

![](https://github.com/mjespinosam/botsque-doc/blob/master/imagenes/img-item-planta.png)

Imagen 2: creación de la entidad "planta" en Omeka.

Si bien esto era un proceso que pasaba por una acción técnica, al crear una entidad es preciso establecer los atributos y es un acto de nombramiento y descripción de la realidad de la manera como yo, o un comunidad, concibe que es. Una decisión ontológica. ¿Cuáles los atributos de una planta? ¿Nombre? ¿Forma? ¿Partes? ¿Componentes? En este software los atributos de todo objeto digital están estandarizados por un conjunto de metadados denominados Dublin Core. Este estandar de metadatos "datos que estructuran un dato" [^9] están pensados para objetos digitales más que para individuos: personas o plantas. Es decir que allí existía una segunda dificultad. Al tomar una fotografía de una planta y subirla a la plataforma el interés descriptivo no estaba sobre el "objeto digital imagen" sino sobre el objeto retratado "la planta". ¿Cómo adecuarme a esos metadatos o encontrar metadatos alternos? Pero más allá del uso de uno y otro metadato ¿Qué son de la planta los metadados? ¿Son los metadatos universales? 

En el [experimento desarrollado](https://github.com/mjespinosam/ruta-metodologia/wiki/Omeka) creé entradas para plantas, las describí con los  campos de Dublin Core, utilicé vocabularios para la descripción y establecí una georeferenciación para cada item. Entre los problemas que surgieron apareció la dificultad para poder hacer el relacionamiento entre entidades de muchos a muchos. El nombre de una planta corrresponde a muchas plantas diferentes y una planta puede tener muchos nombres comunes e incluso científicos. En este punto aunque el nombre científico se establece como un identificador único o clave primaria, no es necesariamente la manera como se busca una planta ni su uso es generalizado entre las comunidades que se relacionan con las plantas. Como refernte estudié la base de datos de [Nombres comunes de plantas de Colombia](http://www.biovirtual.unal.edu.co/nombrescomunes/es/). Esta base de datos relacional se modeló para dar cuenta de las particularidades del nombramiento de las plantas: los nombres corresponden a una sola especie (nombre unívocos), los nombres se aplican a dos o más especies ( nombres equívocos) o en muy poca frecuencia los nombres se aplican a una sola especie y para esa especie es el único nombre reportado (biunivocos) (Nombres Comunes Plantas de Colombia, s. f.). Construída a partir de una amplia bibliografía, documentos de herbarios y trabajo de campo, esta base de datos no se organizó a partir del nombre científico sino a partir de un _nombre común referente_ asociado a todos los otros nombres comunes o científicos reportados. En todo caso se puede hacer la búsqueda por ambos nombres: común científico. Esta base de datos no cuenta con un API (Application Programming Interface), sistema de comunicación de aplicaciones que permite compartir información para otros desarrollos. Además, no es una base de datos abiertos reutilizables, ni tiene especificaciones de su documentación. A eso se sua que su creación y crecimiento no es colaborativo. Por todo lo anterior, pese a ser un exelente referente, el proyecto ya tenía una tarea pendiente: modelar lo que podría ser una base de datos relacional de muchos a muchos que permitiera los nombres unívocos, equívocos y biunívocos georeferenciados al modo de plantas comundes de colombia. Aprendizajes y experimentos que fueron realizándose con los prototipos que vinieron desde una perspectiva de implementación de infraestructuras digitales para comunidades. 



[8^]: Se entiende por objeto digital (Digital like Objetct- DLO) el producto intelectual cuya materialidad digital-codificación numérica de la información- permite que sea publicado y accedido en tecnologías informáticas. "Frente a los DLOs están los no-DLOs, entendiendo como tales, por ejemplo, experiencias virtuales, bases de datos que generan "documentos como resultados" (Document-Like Outputs), o aplicaciones interactivas que pueden tener un contenido diferente según qué usuarios las utilicen". (96) Este concepto permite establecer sistemas de recuperación de información a partir de metadatos asignados a los DLO no-DLO o Documents-like Outputs.

[9^]:  Los metadatos son informaciones que hacen útiles los datos. Están destinados a ordenar y describir la información contenida en un documento entendido como objeto (DLO), de tal forma que se erigen como reveladores tanto de la descripción formal, como del análisis de contenido, en aras a mejorar el acceso a los objetos de información de la Red. (Rodríguez Méndez, 2001, pág. 100)



#### Comunidades e infraestructuras digitales 

El segundo modelo de metodología responde más a proyectos que trabajan factual o hipotéticamente con una comunidad de usuarios que pueden necesitar o serles útil una herramienta digital. Al reconocer una comunidad usuaria eso implica un abordaje en el cual el problema a resolver debe necesariamente dialogar e incluir claridades legales, éticas y de gestión (sobre todo sostenibilidad) del proyecto. Redes sociales temáticas, diseño de video juegos, proyectos transmedia, páginas interactivas, wikis, son algunos de los proyectos que resultan de estas metodologías. En este modelo tanto la informática comunitaria como la informática educativa tienen un papel importante pues están enfocadas en resolver problemas mediante la tecnología como puede ser el aprendizaje. Es por así decirlo una solución técnica a un problema social. La falencia de este modelo es su determinismo tecnológico y la ausencia crítica de las tecnologías en sí. Está estrechamente relacionado con el diseño centrado en el usuario y metodologías participativas de diseño, investigación acción y métodos etnográficos. Así como la informática comunitaria, computación social e  informática educativa.  



![](https://github.com/mjespinosam/botsque-doc/blob/master/Esquemas/esqu-metodologia-001.jpeg)￼

Gráfico 11. Creación propia.

 Poner la atención en tecnologías o sistemas informáticas al servicio o para la resolución de un problema de índole social es una tendencia que desde los años 80´s congrega a aficionados y profesionales de la computación, u otras áreas. Cuando Grunstein publicó *Community Informatics: Enabling Communities with Information and Communications Technologies* (Idea Group, 2000) ya existían al menos 20 años de experiencias localizadas de informática comunitaria (IC). Este campo que no cuenta con metodologías propias para ser definido como disciplina, "se preocupa por mejorar la sociedad civil y fortalecer comunidades para la autogestión y para el medio ambiente y el sostenimiento económico,poder, desarrollo, asegurando que muchos. que de otro modo quedarían excluidos, puedan aprovechar las enormes oportunidades que presentan las nuevas tecnologías" (Gurstein, 2000, pág.2). Por lo tanto, allí discurren los conceptos de comunidad e implementación y diseño de tecnologías y aplicaciones. 

Si bien el acceso a las tecnologías y las herramientas implican que las sociedades salgan de lo que se denomina brecha digital, su implementación no necesariamente implica la apropiación y la comprensión de lo que implica la tecnología misma. La informática comunitaria siguiendo a Gurstein (2000),  incluye el acceso al hardware, el software, la conectividad y la información en contextos donde la tecnología sea aplicada a comunidades "físicas".  Esto implica que los usuarios como las comunidades deben ser parte del proceso de diseño de las implementaciones que se van a realizar. Pero, ¿incluye el diseño la dicusión de las implicaciones de las tecnologías en las comunidades? No necesariamente y por ello el tercer modelo metodológico que exploraremos más adelante.

En todo caso este segundo modelo fue el utilizado en dos prototipos Milpaís y Cofechas. La implementación de la herramienta colaborativa dialogó con un paradigma fenomenológico -naturalista-  dede el cual se fundamentaron las metodologías investigación acción, provenientes de las humanidades que luego se fundamentó con discusiones del diseño participativo de corte etnometodológico (Srinivasan, 2007). Ambos prototipos estaban pensados para trabajar con ARAC, una comunidad de productores agroecológicos de Subachoque, Colombia. 



##### Savia wiki: una wiki de saberes sobre las plantas

A partir de los experimentos en Omeka la necesidad de trabajar con una plataforma colaborativa era apremiente. Si bien el proyecto quería aportar a la dinamización de la Base de Datos del Centro de Estudios en Medicina Intercultura CEMI, era claro que no podía trabajar desde la BD misma. Debía crear un prototipo que dialogara con los requerimientos de partida y los que citaba CEMI. Para ellos era indispensable 

> 1) Recopilar y documentar la información disponible sobre plantas medicinales, en especial los conocimientos tradicionales que existen sobre ellas y las consideraciones sobre su aplicación para el cuidado de la salud. 2) Permitir el acopio incremental de información, su alimentación colaborativa y el fácil acceso de personas interesadas a través de Internet y 3) Integrar a las personas interesadas en las plantas medicinales a través de una red de colaboración.



Si bien esos eran sus propósitos era clato que aún no tenía una comunidad que la alimentara y no contaban con un sistema de curaduría que permitiera verificar la calidad y pertinencia de la información dispuesta allí. Dos de los problemas que tienen por lo general todos los sistemas colaborativos pues responsabilidad generalmente recae sobre unos cuantos. En conversaciones con quien en su momento era el gerente de proyectos de CEMI, Iván Sarmiento, establecí algunos compromisos frente al proyecto que en principio declaraban que mis intereses no eran económicos, que toda la información y  la Base de Datos era propiedad de la organización y que mi aporte estaría en el marco de una recomendación. El análisis de esta BD requirió de la lectura de los términos y condiciones y la conversación con la abogada experta en propiedad intelectual y conocimientos tradicionales Cristina Matiz Mejía. A partir de las conversaciones que tuve con ellos empecé a conocer las discusiones sobre propiedad intelectual y conocimientos tradicionales y de paso empecé a conocer  las bibliotecas digitales que trabajaban temas etnobotánicos, las aplicaciones que en colombia abordaban este tema y otros sistemas colaborativos. (Ver: gráfico 13)

![](https://github.com/mjespinosam/botsque-doc/blob/master/Esquemas/esqu-referentes-2017/esqu-referentes-2017.001.jpeg)

Gráfico 13. Primeros referentes y fuentes indagadas para el proyecto. Marzo de 2017.

 El primer y más importante referente para crear el prototipo  fue [Inaturalist]( https://www.inaturalist.org/pages/what+is+it). Este software libre creado en el marco de una maestría de ciencias de la información de la universIdad de Berkley es actualmente una plataforma tipo red social que integra a la ciudadanía en la captura de datos sobre la biodiversidad. De este modo, información sobre especies animales, vegetales u hongos son reportados mediante imágenes o sonidos, y debidamente georeferenciados en la plataforma. Allí, una comunidad de expertos hace la verificación del nombramiento de tal modo que, se asegure la estructuración debida de los datos. Esta curaduría junto a una opción de oscurecimiento de información son dos de los elementos a destacar. La curaduría permite que la comunidad de expertos verifique la información y lo ajuste a los estándares científicos y estructuración de datos. Todos los datos están estructuradas bajos las categorías del estandar de metadatos Darwin Core. Este estandar  permite estructurar la información por  elementos de registro -¿qué se observa o escucha?-, registro biológico -¿cuáles son sus atributos?-, evento -¿a qué horas se realizó el registro?-, ubicación -¿dónde se realizó el registro?- y taxón -¿cuál es la especificación taxonómica?-,  excepto identificación que es una categoría que organiza los ID de la base de datos internamente y el contexto geológico.  En cuanto al oscurecimiento de la información esto permite que especies en peligro de extinción puedan reportarse pero mantenerse ocultos para protegerlas de traficantes, por ejemplo. Esta decisión es tomada tanto por quienes hacen las observaciones como por los curadores. El rol de los curadores es asignado por los administrados a partir de su participación o experiencia demostrada. Los curadores trabajan sobre la taxonomías, que pueden modificar una vez se establezca el debate. Los curadores tienen potestad sobre lo que se obscurece a partir de criterios de riesgo y toda la información sobre cómo ser curadores está en la [guía  para curadores](https://www.inaturalist.org/pages/curator+guide). 

Ver [Observación inaturalist](https://www.inaturalist.org/observations/20189776)

![](https://github.com/mjespinosam/botsque-doc/blob/master/Esquemas/esqu-referentes-v1.png)



La posibilidad de ocultar informacion y el sistema curatorial de la información, respondían a dos problemas emergentes en el proceso de la investigación de Milpaís:  los riesgos para la salud de información de plantas medicinales sin verificación famaceútica, médica, etc. y la necesidad de resguardar cierta información etnobotánica dentro de plataformas digitales para protegerlas de apropiación indebida de conocimiento tradicionales. En cuanto a la curaduría inaturalist me permitió identificar un esquema de relacionamiento entre expertos y aficionados para la estabilización de la información. Sus criterios de evaluación de calidad de datos, los procedimientos colaborativos para rectificar o asignar nombramientos son dos estrategias que funcionarian perfectamente en una paltaforma etobotánica para verificar correspondencia con literatura científica. Ello aseguraría la democratización en la construcción del conocimiento y la fiabilidad de los datos. De tal modo se controlarían los riesgos de toxicidad, interacciones entre componentes y tratamientos, entre otras cosas. En cuanto a la posibilidad de obscurecimiento de información es claro que ante la inexistencia de legislación respecto a la protección de saberes tradicionales, los saberes etnobotánicos son propensos a la apropiación indebida o la biopiratería. ¿Qué quiere decir esto? ¿Cómo prevenirlo?

La información etnobotánica, según reporta la Organización Mundial de la Propiedad Intelectual (OMPI), está en riesgo de apropiación indebida(Organización Mundial de la Propiedad Intelectual, 2015). El riesgo yace en las falencias para el establecimiento de legislaciones nacionales sobre derechos tradicionales de propiedad colectiva y la posibilidad de la usurpación de saberes tradicionales mediante patentes y por parte de particulares con intereses económicos. En este contexto la [Biblioteca digital de medicinas tradicionales de la India](http://www.tkdl.res.in/tkdl/langdefault/common/Home.asp) (TDK) fundamentó en el proyecto de Milpais la necesidad de establecer una discusión con la situación legal de dicho conocimiento en entronos digitales. La TDK es además un  modelo de estructuración de información para la protección y prevención de biopiratería [^10] Tras descubrir que varias de las plantas y prácticas medicinales tradicionales estaban siendo patentadas -la cúrcuma por ejemplo- el gobierno Indio decidió crear esta biblioteca. Allí se recopila el saber de varias tradiciones de medicina hindúes en sus lenguas originales y traducidas em 5 idiomas. El propósito es que las oficinas de patentes de todo el mundo verifiquen antes de conceder una patente. Como se puede revisar en la [wiki de referentes en github](https://github.com/mjespinosam/ruta-metodologia/wiki) la TDK estructura la información siguiendo el modelo de clasificación internacional de patentes(CIP) pero añadiento campos de descripción. En la CIP

> "hasta 2005, solo había un subgrupo –el A61K35/78– correspondiente a plantas medicinales, lo que significaba que los examinadores de patentes no disponían de los recursos óptimos para revisar solicitudes de patentes basadas en medicinas tradicionales" (La protección de los conocimientos tradicionales de la India, s. f.) 

Por lo que con el trabajo de la TDK se establecieron 207 subgrupos nuevos además de los 27 mil subgrupos presentados por la TDK en lo que denominaron: Clasificación de recursos de conocimientos tradicionales en sus siglas en inglés TKRC. Este modelo de clasificación "sistémica de diseminación y recuperación del conocimiento tradicional en un entorno digital" es un referente mundial. Países como china consideran oportuno crear un sistema armónico con el CIP pese a que la clasificación TKRC no responde a las particularidades de sus medicinas. En todo caso el TKRC constituye un esfuerzo por dar cuenta del dominio etnobotánico. Si es o no una clasificación aplicable a todo los saberes etnobotánicos es una discusión que daré más adelante. Lo que si es cierto es que gracias a esta plataforma un sistema de conocimiento milenario vivo es catalogado, divulgado y protegido a través del  acceso restringido de ciertas informaciones 

Hasta aquí  Inaturalis se presentaba como el software que podría incluir aspectos culturales a la taxonomía vegetal y presentar así una mixtura entre enciclopedia y red social. Allí se podría integrar los saberes etnobotánicos a partir de la estructuración de los datos al modo de la TDK que pudiesen servir para la protección preventiva del conocimiento. Para ello procedimos con Camilo Martínez [^11] a la instalación de este software y prototipar desde allí el entorno colaborativo. Dos aspectos se interpusieron para poder llevarlo a cabo: el software, según comunicó via email el desarrollador del software Ken-*ichi* Ueda, no estaba documentado en sus últimas versiones y según reportaba Karen Socha, encargada de ciencia ciudadana y referente de inaturalist desde el Instituto Humbold en su momento, implementar esta plataforma era demandante y costoso. Al respecto la investigadora comentó sobre la experiencia de España en donde decidieron hacer un Fork  -bifurcación- de inaturalist llamada [Natusfera](https://natusfera.gbif.es/pages/about), que integra además la wikipedia. Este proyecto -reiteró- ha sobrepasado las capacidades humanas y los recursos del equipo. Lo mejor en todos los casos dijo la investigadora - es trabajar desde la que ya existe implementada- . Pero esto era inviable: inaturalist no contempla información etnobotánica,  ni los sistemas de información sobre biodiversidad integran campos culturales como parte de la biodiversidad, por ejemplo nombres comunes, usos, preparaciones, etc. Por ello, cualquir reporte de caracter cultural que se suba a la plataforma como pueden ser imágenes de plantas en códices, cuadros, canciones, etc, son datos que se notifican para dar de baja pues interfiere en la estructuración conceptual de la Base de Datos. En cierta medida es posible hacerlo a riesgo de ser censurado. Esta imposibilidad curatorial sumada a la imposibilidad técnica de poder hacer un prototipo con este software, nació Milpaís, una wiki semántica etnobotánica. 



##  Milpaís: una wiki semántica para recuperar, compartir y construir colaborativamente las relaciones entre plantas, seres humanos, comunidades y entornos


![](https://github.com/mjespinosam/botsque-doc/blob/master/imagenes/poster-mipais-v2.png)

Milpaís [^12]

##### Lecturas







Una intención que ya estaba clara en la pregunta del proyecto de la wiki etnobotánica "Mil país"

> ¿De qué manera se puede articular ciencia y conciencia ciudana bajo principios éticos, en comunidades que usan, ivestigan, producen y defienden saberes etnobotánicos mediante la implementación de una wiki semántica pensada para diversas comunidades que permita la apropiación de la tecnología, el acceso recuperación del conocimiento y verificación de la información?

Y así ocurrió en el primer año [5^]. La investigación acción como una metodología de investigación centrada en las relaciones de las personas con el problema,  me permitió mediante el diseño de instrumentos y consulta a comunidades y expertos construir un prototipo inicial. La realización de entrevistas a tres expertos en etnobotánica, propiedad intelectual y ciencia ciudadana, la participación en las reuniones de la comunidad ARAC (productores agroecológicos de Subachoque), la realización de un grupos focal con ellos, la observación participante, las conversaciones, más las matrices de análisis de referentes y exploración conceptual permitieron consolidar un prototipo bajo incipientes metodologías ágiles. Pero ¿Cuáles habían sido los referentes (software) para consolidar este prototipo?

 Al respecto en Milpas pude notar dos aspectos:

1. En ningún momento había pensado en la manera como se estructuraba el conocimiento para el modelado de una base de datos
2. Tenía la plena convicción de que las wikis al ser colaborativas ya eran herramientas suficientes para democratizar la construcción y recuperación del conocimiento además de mapear las relaciones seres humanos plantas. 

En cuanto a los aspectos legales emergió la vulnerabilidad de los conocimientos tradicionales sobre plantas ante el riesgo de ser patentados. Esta cuestión que parece impensable es el motivo por el que paises como la  India. Como se puede consultar en el referentes Biblioteca Digital de Medicinas tradicionales de la India por sus siglas en inglés TKDL (Ver: wiki en GitHub), existen escazos pero importantes rmodelos de bibliotecas digitales que previenen la bioperiatería o apropiación indebida de conocimientos tradicionales vinculados a recursos biológicos. Este asunto que no es menor cuestiona la procedencia ética de una plataforma etnobotánica. En tanto no exista una legislación nacional, toda informacion que circule en internet está en riesgo de ser apropiada indebidamente. Y esto implica un riesgo para la existencia de las plantas como para las comunidades donde habitan y comparten sus beneficios. Para aclarar el tema: quien patente un  

Frente al asunto de las relaciones de las plantas con los seres humanos, mi perspectiva, como los preceptos ontológicos de los modelos subyacentes a los prototipos: modelado de bases de datos e infraestructuras, no consideraban ni integraban a las plantas como agentes en el sistema mismo. Sin embargo, la oportunidad de desarrollar un laboratorio de micro huertas [x^] me permitió explorar la intuición de dichas relaciones. Intuiciones que más adelante identificaría como metodologías del diseño crítico y  especulativo. Desde allí, como desarrollaré más adelante, me pregunté sobre la agencia de las plantas, su relación -de amistad- con los seres humanos, su estatuto ontológico y la experiencia que teníamos los participantes con ellas. Aquí, el diseño crítico es el detonante del giro de esta investigación pues me permitió reconocer perspectivas multidisciplinarias para abordar un problema de investigación desde las Humanidades Digitales y ver en el prototipo un artefacto para pensar [2]. 

En este punto el problema emergió en la necesidad de hacer el modelado de datos como prerequisito para poder hacer prototipos en diferentes software. Pero este problema que era en apariencia un asunto técnico devino en una exploración sobre los tipos de bases de datos, la creación de las mismas y los conceptos subyacentes. De ahí que la pregunta de cómo dar cuenta de las relaciones seres humanos plantas en una plataforma colaborativo tipo wiki, desecandenó en una serie de preguntas sobre la naturaleza de diferentes software, los presupuestos sobre las relaciones seres humanos plantas, los aspectos éticos y jurídicos a tener en cuenta y las discusiones conceptuales sobre las plantas. ¿Qué es al final de cuentas una planta y cuáles las relaciones que ella tiene con nosotros? Si la entidad planta se describía como un individuo ¿Q
ué implica definirla como individuo? ¿Cómo se puede evidenciar la agencia que tiene la planta en la construcción de conocimiento que sobre ella se trasnfiere a un entorno digital? 





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

El *prototipo* *se* *desarrolla* *a* *partir* *de* *una* *wiki* *semántica* *del* *software* *libre* *Media* *Wiki* (*semantic*-*mediawiki*.*org*, 2018) para la gestión del conocimiento etnobotánico de comunidades que usan, defienden y comparten saberes sobre las plantas. Diseñada a partir de una reflexión ética y legal de lo que implica documentar, catalogar y difundir conocimientos tradicionales y locales, el prototipo parte de una estrategia para visibilizar las relaciones plantas-personas-comunidades con cuidado de no exponer contenidos susceptibles de expropiación indebida (componentes, fórmulas, técnicas, rituales). Es así que en este prototipo me interesa conectar qué lugares, qué personas (comunidades) y de qué maneras se construyen las relaciones con las plantas, entendidas estas como uno de los bienes comunes que sostienen y equilibran entornos como el cuerpo y el medio ambiente (Lafuente, 2007).

En términos técnicos, la SMW permite estructurar una Base de Datos Relacional (BDR) mediante el uso de plantillas que integran notación semántica y vocabularios controlados. Para esta wiki utilizamos el estándar de metadatos FOAF(*The* *FOAF* *Project*, 2018) y un conjunto de metadatos propios y vocabularios controlados alimentados de diversas fuentes de catalogación etnobotánica (Royal Museum From Central Africa, 2017; *BRIT* - *Native* *American* *Ethnobotany* *Database*, 2003). Igualmente, se ha tenido y se tendrá en cuenta la información que colaboradores y posibles usuarios han reportado necesaria. Para recuperar la información y que se integre la notación semántica, el prototipo implementa los formularios de Semantic Media Wiki (*Page* *Forms* - *MediaWiki*, 2018). Estos formularios permiten a los colaboradores/creadores de la wiki ingresar la información mediante una interfaz amable sin necesidad de hacer notación semántica manual. Una vez se ingresa la información la SMW permite recuperar información relacional (qué personas son amigos de una planta, qué plantas sirven a las personas para hacer artesanía, qué comunidades resguardan una semilla en particular, quiénes y dónde hay médicos tradicionales, yerbateras, investigadores, médicos alópatas que trabajan con plantas, etc.) así como visualizar datos tales como los geográficos.



##### La Wiki semántica: la caja negra de la clasificación de las plantas y sus relaciones

La organización mundial de la propiedad intelectual (OMPI) desde hace más de dos décadas discute y prepara documentos que permitan incorporar en su paradigma del derecho y la propiedad intelectual (PI) y los conocimientos tradicionales (CCTT). La OMPI los define como, **“**conocimiento como tal, en particular el conocimiento que produce la actividad intelectual en un contexto tradicional, e incluye la experiencia, práctica y aptitudes así como las innovaciones” (OMPI, n.d.) A la fecha existe una guía de la organización para la catalogación de los CCTT no sin advertir que deben ser las propias comunidades quienes cataloguen y preferiblemente administren dicho conocimiento (Organización Mundial de la Propiedad Intelectual (OMPI 2017) Señalan también que no es suficiente con proteger las Bases de Datos (BD) pues los conocimientos allí incluidos, si no están protegidos por una legislación nacional pertinente, no están protegidos en sí. Su gran discusión es si es posible que los Derechos Colectivos puedan ser reconocidos en su modelo de Derechos. Autoras como Andressa Caldas discute las distancias epistemológicas del modelo del derecho occidental y la imposibilidad de que lo común, lo colectivo, lo tradicional, puedan ser incorporados en el paradigma de la PI (Caldas 2004) y por lo tanto, la vulnerabilidad a la que están expuestos al no ser respetados sus propios modos de circular. Detrás de todo este debate avanza por el mundo entero la biopiratería, la apropiación indebida de conocimientos y los intereses privados sobre bienes comunes a la vez que se presentan iniciativas para crear bases de datos con este tipo de conocimientos (Lafuente 2007) (Biopirateria – Iniciativa Andino Amazónica Para La Prevención de La Biopiratería n.d.) (CEMI n.d.) Es preciso entonces, abordar desde las Humanidades Digitales las implicaciones legales y sociales de la conservación de dichos conocimientos a través de BD y el software. Este abordaje debe partir de las maneras como las propias comunidades, en las que circula como conocimiento y práctica dichos CCTT, consideran que deben integrarse estrategias digitales que permitan administrar, catalogar o no, compartir o resguardar estos saberes. 

Una aproximacion desde  la antropología me permite discutir la necesidad de contemplar la arquitectura de la información, las Bases de Datos de conocimientos tradicionales, locales y comunitarios y el uso/desarrollo del software como iniciativas que si no parten de un ejercicio reflexivo y ético pueden desconocer la pluralidad de ontologías de las comunidades, el sentido en sí del conocimiento y de paso convertirse en prácticas colonialistas enmarcadas en el extractivismo de información o la vulneración de los derechos colectivos (Vargas 2010).

En las humanidades las discusiones sobre la relación entre lenguaje y realidad-cultura así como los sistemas de clasificación han sido recurrentes. Levy Strauss en el Pensamiento Salvaje (Lévi-Strauss and González Aramburo 2014) aborda la clasificación como práctica humana que puede darse de manera “mítica” o “científica”. El pensamiento mítico, señala, no utiliza modelos estructurados para clasificar el mundo, mientras el pensamiento científico parte de sus hipótesis y teorías. Si bien Levy Strauss no nos está hablando de pluralidad sino de una diferencia en dos modelos, es claro que existen en los “pensamientos míticos” muchos modos de clasificar el mundo relacionados con el lenguaje mismo, con las palabras. Siguiendo la hipótesis de Sapir- Whorf (Carr 2018) el lenguaje construye las realidades particulares que coincide con lo que en la última década, y para hablar de las pluralidades, la antropología empezó a trabajar con las ontologías “mundos desde los que se habla” y que se denomina el “giro ontológico” (Varela 2015). Así, las ontologías están estrechamente relacionadas con las palabras y los conceptos de cada comunidad pues son constituyentes de mundos desde los que se habla, se determina su realidad y que son enclave para pensar su conocimiento e información. Estos permite prever la importancia de explorar, investigar, pensar-negociar y definir con las comunidades los modos de clasificar, la creación de metadatos y en sí mismo los principios ontológicos. Al respecto Christies y sus colegas (2008) , hablan de la co creación con y para las comunidades, de la relación entre palabras y ontologías y de la necesidad de interrogarlas, para hacer la mejor construcción o uso.  Preguntas como ¿Comparten las comunidades las mismas taxonomías que los investigadores? Y si no ¿Cuáles consideran las comunidades que son pertinentes? ¿Los metadatos a utilizar dan cuenta de las necesidades de información de un grupo? ¿Tiene en cuenta el diseño del software la experiencia de las personas, la necesidad de la comunidad? ¿Están los investigadores informados y sensibilizados sobre las maneras de estructurar el conocimiento de su comunidad? 

En Australia el grupo investigador de la universidad Charles Darwin ha trabajado por años con la comunidad indígena Yolngu en proyectos que van de la lingüística a la etnobotánica y a partir de los resultados de investigación, e implementación de diversas soluciones digitales, no solo han reconocido que la “arquitectura de la información refleja y representa políticas del conocimiento” si no que es una práctica colonialista que puede ser desmontada desde la negociación y diseño del software (Christie 2006). La manera como un grupo de académicos, una agencia de cooperación o una institución (por ejemplo la OMPI) pueden llegar a determinar las buenas prácticas para catalogar, archivar, crear interfaces sin incluir a las comunidades, puede en muchos casos imponer –con la mejor de las intenciones- modelos que no le sirven a la comunidad, no revitalizan sus relaciones, su memoria y no ayudan –por ejemplo- a la apropiación del patrimonio  (Srinivasan 2007) (Christie 2006). En este sentido la formulación de los proyectos con comunidades y sobre todo con CCTT requieran de una reflexión ética y política-legal sobre la pertinencia o no de las estrategias digitales a usar.  

Los metadatos en particular, como instrumentos de captura de información, de estructuración de los mismos, privilegian la interoperabilidad sobre el uso real, contextual y cultural de los datos que pueden no necesitar dichos modelos. ¿Para qué comunidad/usuarios se quiere garantizar la interoperabilidad? ¿Qué metadatos son más pertinentes según las comunidades? Como señala Srinivasan:

> “What is clear when one begins to analyze these metadata models is that they are built around a system of logic that follows traditional notions of rationality. These are systems that do not seem to be concerned primarily with the community or specific cultural group’s authorship, epistemology or ontology”(Srinivasan 2006)

El punto aquí no es su negación o llamar al desuso, si no la posibilidad de que confluyan estándares con metadatos propios y que esto posibilite la negociación entre diferentes ontologías (Verran et al. 2007) o espacios de reinvidicaión de lugares de la no existencia (Santos 2006), eso que no es lo culto, ni lo estándar, ni lo aprobado por un sector, en este caso los sistemas de información. Es decir, un espacio digital en el que puedan convivir diferentes modelos de metadatos estandarizados con otros que no lo son pero que son pertinentes localmente. Igualmente se puede recurrir a entornos que no condicionen el conocimiento ni la experiencia de los usuarios, con su conocimiento y con la experiencia de la interfaz a formularios, etiquetas predefinidas. Este es el caso de TAMI (Texto Audio, Video e Imagen), sistema de administración de archivos para una comunidad indígena, que se pensó por investigadores bajo la premisa de ontologías fluidas en la que cada usuario decide qué metadatos definir, como agrupar y qué compartir o no (IKRMNA - Making Collective Memory with Computers n.d.) (Ver: imagen 3)

![](https://github.com/mjespinosam/botsque-doc/blob/master/imagenes/TAMI-gestor.png)



Iamgen 3: [TAMI](https://www.cdu.edu.au/centres/ik/db_TAMI.html#). Administrador de conocimiento etnobotánico. 

Ahora bien, si las palabras-conceptos de un estándar de metadatos u ontologías están allí modelando y delimitando no solo un conocimiento si no un grupo humano y su experiencia con los conocimientos, estos se aplican a entornos que son el resultado de un diseño y desarrollo de Software. Para Chrities ( 2005) el software “is not ontologically neutral, it is invested by the expectations of the programmers about both the nature of the world and the nature of work to be done upon it.” (Pág.6). Esta aparente neutralidad la cuestiona también Lev Manovich (Manovich 2017) para quien estudiar el software es una deuda de las Humanidades Digitales en tanto el software como el habla “hacen cosas”: modelan pensamientos, crean experiencias sociales, culturales, etc. A esto le llama el autor “actos de software” haciendo un paralelo lingüístico. Esos “actos de software” pueden entonces abordarse desde nuestro campo en dos vías: una, haciendo una lectura (próxima o lejana) del código para analizar sus modos de crear experiencias y modelar o dos, creando software –comunitario- que permita modelar colaborativamente para dar respuesta a las inquietudes y necesidades de las mismas comunidades. 

Este tipo de creación colaborativa del software es nombrada por Ramesh Srinivasan informática comunitaria (Srinivasan 2007) y es la apuesta a que la misma comunidad esté implicada en el diseño y sea  “information architects and ontology creators of their own systems. (Pág. 3). Esta inclusión permite una nueva comprensión del rol profesional de los Humanistas Digitales como “Facilitadores del conocimiento orientados al proceso. En lugar de ingenieros de información orientados al producto. (Albrechtsen y Jacob, 1995, p. 30, citado en Srinivasan). 

Este tipo de iniciativas cabe aclarar, son el resultado de trabajos interdisciplinarios en los que por ejemplo, el diseño dialoga con las humanidades y sus métodos: etnografía, etnometodología. La etnografía permite la observación directa y la interacción con la comunidad mientras la etnometodología “entendida como, la investigación empírica (logía) de los métodos (método) que utiliza la gente (etno) para dar sentido y producir, al mismo tiempo, la actividad social cotidiana, es decir, el estudio de los procedimientos constitutivos de la inteligibilidad social”. (Diccionario Crítico de Ciencias Sociales | Etnometodología n.d.) En este sentido, estas metodologías aplicadas al trabajo de ideación, prototipado y versiones beta, permite según Srinivisan, crear puentes para que las comunidades creen sus contenidos, sus propios sistemas de información, diseñen las arquitecturas de sus bases de datos en integren los sistemas en sus comunidades. 

Finalmente y volviendo al tema de los conocimientos tradicionales, hay que reparar que dada su vulnerabilidad, el estado de pérdida en el que muchos se encuentran y la urgencia institucional por conservarlos, es preciso replantear los modos y los medios como se establecen los puentes para que el trabajo con los mismos esté al servicio de las comunidades y que permita la apropiación, revitalización, cuidado y defensa de dichos saberes. Igualmente, esto implica que se debe tener aclarar el lugar ético e investigativo frente a la elección e implementación de los modelos de gestión del conocimiento en la era digital (Van der Velden 2005). Rescato la importancia de métodos etnográficos y la etnometodológicos como puntos de partida para poder idear y diseñar con los otros, propuestas digitales, rutas metodológicas. La apropiación depende en gran medida de los niveles de involucramiento y decisión que tienen las comunidades sobre lo que se diseña y prototipa. 



Nota de Camilo:  Relacionado a lo CCTT y lo de Australia <!-- Aquí hay un a discusión importante que también hace referencia a la estandarización como una forma de normalización.  Estandarizar implica normalizar, describir y usar categorías comunes, pero cuando las categorías han sido formuladas desde una parte con poder, para una comunidad estandarizar y normalizar su conocimiento implica eliminar lo particular de ese conocimiento, por ejemplo eliminar la agencia espiritual o mágica de una planta en ese proceso de estandarización/normalizacón.  Interoperabilidad es un término que evoca una relación bidireccional horizontal, por lo tanto oculta las relaciones de poder implícitas en el término



<!--En este párrafo se despliega una idea interesante, yo creo que también es posible reconocer estos procesos de informática comunitaria como procesos bidireccionales de tranferencia de conocimiento, una comunidad aprende a modelas, por lo tanto tiene que etender conceptos de las ciencias de la computación (colonialistas y hegemónicas, como ya lo has planteado) pero también implica que las ciencias de la computación y las humanidades son transformadas por estas formas de conocimiento. El humanista digital debería ser capaz de actual en estos dos procesos o direcciones -->

##### Diseño para las comunidades: Cofechas

 

[Cofechas](https://github.com/mjespinosam/botsque-doc/blob/master/Cofechas/index.html)





![](https://github.com/mjespinosam/botsque-doc/blob/master/imagenes/cofechas-logo-v1.png)

<img src="https://github.com/mjespinosam/botsque-doc/blob/master/Esquemas/esque-cofechas-v1.png" style="zoom:150%;" />

![](https://github.com/mjespinosam/botsque-doc/blob/master/Esquemas/esque-cofechas-v1.png)





[^10]: La biopiratería es entendida como la apropiación indebida de saberes tradicionales relacionados con recursos naturales. La TDK alerta sobre el riesgo de que intrusos aprovechen saberes ancestrales para registrarlos en oficinas de patentes que al no tener vías de verificación de la existencia de estos saberes proceden a otorgar patentes. Un litigio en defensa de un saber tradicional es costoso y lleva años. Casos como el de la cúrcuma, nema, arroz basmati, quinoa, ayahuasca, hoodia son emblemáticos por haber sido ganados a favor de las comunidades o por haber sido patentados. 
[^11]: Esta tesis es el resultado del trabajo con Camilo Martinez quien además de ser el director de este proyecto fue el profesor encargado del laboratorio de Humanidades Digitales. Es claro que las Huamanidades Digitales son el resultado de trabajos colaborativos y que de las relaciones entre campos de conocimientos y personas estos proyectos suelen abrir nuevas discusiones y propuestas.
[^12]: El proyecto recibió una financiación de la Facultad de Artes y Humanidades de los Andes a partir de la cual se desarrolló el trabajo de campo en la comunidad de ARAC 



[x^] Tanto las aplicaciones de la IC como los modelos de servicios, tienen una clara vinculación con los procesos que se han adelantado o se pueden adelantar en las Bibliotecas Públicas. Y es claro que en este marco las tecnologias son las mediadoras de procesos para las comunidades. Pero ¿cuál es la incidencia de las tecnologías en las mismas comunidades?





#### Prototipar para pensar los problemas en HD

![img](https://github.com/mjespinosam/botsque-doc/blob/master/Esquemas/esqu-metodologia-002.jpeg)

Gráfico 12

El tercer modelo permite salir de la lista de requerimientos a cuestionar las instancias fundacionales de las herramientas desde la experimentación con ellas mismas. Probar las diferentes plataforma e indagar críticamente las maneras como han sido diseñadas y las maneras como presentan el problema del o la investigadora. Latour llama la atención sobre estos casos de mediación que nombra como cajanegrización. En referencia a las cajas negras de los aviones, el autor señala la opacidad de ciertos actantes como pueden ser las herramientas o tecnologías digitales. Tras la implementación de una herramienta se oscurecen todas las redes que la constituyeron lo que no permite ver la complejidad interna.  Este modelo por lo tanto puede ser usado para traer a la luz las redes de una tecnología diseñada o implementada para un problema o una comunidad. Así, se parte del posible diseño, uso y apropiación de una herramienta pero se cuestiona el cómo, para qué, entre quienes se va a diseñar o diseñó esta herramienta. Es preciso señalar que aquí el prototipo no es solo el resultado sino un elemento que permite mediante la iteración, refinar el proceso, evidenciarlo de manera crítica (Ver: gráfico 8). Este modelo dialoga directamente con la investigación en diseño crítico y el especulativo. Desde allí se propone el diseño de dispositivos de reflexión sobre conceptos sociales problémicos en un mundo neoliberal que se apoya muchas veces en tecnologías. 

￼
Figura 8. Creación propia



###### La mesa huerta: un prototipo especulativo

![](https://github.com/mjespinosam/botsque-doc/blob/master/imagenes/mesa-huerta-6.jpg)



[APARTADO EN PROCESO DE ESCRITURA]

Como parte del resultado del primer laboratorio de creación colectiva de Microhuertas “Crear/criar espacios vivos en casa” realizado en Bogotá (2018) un grupo interdisciplinario de creadores de la ciencia el arte y la tecnología prototipamos una “ Mesa-microhuerta” en la que se integramos sensores electrónicos con el fin de activar la comunicación entre seres humanos-plantas-agente virtual (bot). A partir de un ejercicio especulativo cuestionamos la integración de los sensores como dispositivos de control a los espacios vivos si bien reconocemos la huerta como espacio semiótico en el que se da la interacción entre sensores personas y plantas. Esta interacción construye y devela signos a partir de una experiencia corporal y emocional. Por lo tanto, la integración de los sensores más que sustituir labores de cuidado de la huerta se integran en la mediación comunicativa para la conexión con lo vivo. Bajo la pregunta ¿Cuál es el bienestar de la microhuerta y de qué manera los sensores dan cuenta de ello? Trabajamos con 4 sensores: el cuerpo como sensor primario que desde la observación determina condiciones para las plantas, y los sensores de humedad de tierra, humedad relativa y luz. Estos sensores están dispuestos de tal modo que se relaciones con la mesa a través de canales de bienestar contruídos inicialmente con tinta conductora y luego con cinta de cobre. Sobre cada canal habitan un conjunto de insectos benéficos para el entorno y elaborados de materiales electrónicos que se encienden si cada canal: agua, luz, humedad, son los propicios para el bienestar. Los datos a su vez son entregados vía wi fi a telegram desde donde se archivan mediante un bot que comunica a la comunidad de microhuertas el estado de bienestar de las huertas. 







## II Parte

## El lenguaje del botsque : prototipo para pensar la agencia de lo no humano en entornos colaborativos



"R.W.Emerson (2008a): "Debes preguntar de otro modo, debes sentirlo y quererlo" p.163)." ([Sepúlveda Pizarro 2015:20](zotero://open-pdf/library/items/FD4XPIM8?page=20))

 

### Marco conceptual: Plantar la discusión: Las plantas como agentes, (abordajes interdisciplinarios perspectivas teóricas)

Bajo la premisa de una naturaleza que comunica y es parte de la creación de conocimiento sobre ella misma ¿Qué es la naturaleza? ¿De qué manera conocemos la naturaleza? ¿Es posible conocerla? Es más, ¿Qué somos nosotros con relación a  ella? 

"la naturaleza como símbolo, desde el paradigma ser-hablar-pensar, se explicó que si la naturaleza habla, no quiere decir que posea lenguaje, sino que el hombre participa de su habla, escuchándola y siendo su intérprete, si sabe escuchar. Como señala Panikkar (2011a) la relación entre escuchar y hablar es de tipo a-dual: “No hablaríamos si primero no hubiéramos escuchado, y no escucharíamos si nuestro ser no participara del Ser que habla”202 

La historia de la naturaleza desde la configuración de la ciencia excluye las preguntas sobre la divinidad y de paso, sobre la participación de ella en la trascendencia. Una naturaleza regida por leyes, observable y predecible abrió las puertas a una ciencia determinista. Una ciencia que con sus métodos nos entrega una realidad que se conoce a través de acciones controladas, observables, repetibles. En muchos casos a tavés de la disección y el escudriñamiento de las partes ínfimas. Una visión atomista, que si bien retrata la naturaleza, es un retrato limitado. De ahí que la pregunta sea un asunto que nos conduce a preguntas sobre su propia divinidad.

Así, abordar la naturaleza desde una perspectiva teológica y como una pregunta filosófica, sin ser este el objeto de esta investigación, es la declaración de principios sobre realidad de las que parto al hacerme las preguntas sobre ella. Declaración que se transfiere a cada una de las acciones que he realizado para acercarme, para pensarla, para recrearla. En este caso,



##### La experiencia mística

¿Es posible conocer más allá del conocimiento conceptual? 

"El mythos sólo es real en la intersubjetividad, es comunitario." ([Sepúlveda Pizarro 2015:69](zotero://open-pdf/library/items/FD4XPIM8?page=69))

 El mismo ejercicio filosófico de nuestro autor sugiere este triple don de la vida: aceptar el logos (lo pensado, lo dicho), desenterrar el mythos (lo no pensado) y acoger el pneuma (lo impensable)." ([Sepúlveda Pizarro 2015:70](zotero://open-pdf/library/items/FD4XPIM8?page=70))

"No quisiera terminar este tema, sin hacer una alusión al logos, por temor a que sólo se le reduzca al aspecto reflexivo conceptual. El logos tiene una mayor riqueza que la simple inteligibilidad, de ahí su complicidad y participación con el mythos y pneuma: si el logos es palabra escuchada es porque no existe sin el pneuma. Para Panikkar, (2007a) nos recuerda que logos es "vāc sonido, contenido; pero también icono, εἳδος, gesto, expresión, forma" (p.359).

"Mi experiencia con la naturaleza hizo que surgiera una idea algo difusa pero de gran complejidad en términos filosóficos: La experiencia con la naturaleza es una experiencia mística." ([Sepúlveda Pizarro 2015:14](zotero://open-pdf/library/items/FD4XPIM8?page=14))

De esta manera, a la filosofía no sólo le compite aceptar el logos, sino también recuperar el mythos, lo no dicho, lo no pensado." ([Sepúlveda Pizarro 2015:63](zotero://open-pdf/library/items/FD4XPIM8?page=63))

"Con el término experiencia, la presente investigación se apoya más en un discurso antropológico que en un discurso cosmológico, e incluso ecológico de la realidad." ([Sepúlveda Pizarro 2015:14](zotero://open-pdf/library/items/FD4XPIM8?page=14)) "Por otra parte, la concepción de la experiencia en Panikkar hace referencia a un dato inmediato sin reflexión." ([Sepúlveda Pizarro 2015:54](zotero://open-pdf/library/items/FD4XPIM8?page=54))

"El lenguaje del mythos es la narrativa que apunta al sentido de las cosas en relación al todo sin estar constreñido a un lenguaje conceptual. El sentido - a diferencia de la categoría epistemológica de significado - siempre se refiere a la totalidad de la experiencia, y por lo tanto no se deja dividir ni analizar, tan solo conocer en relación al contexto." ([Sepúlveda Pizarro 2015:64](zotero://open-pdf/library/items/FD4XPIM8?page=64))

**"La consciencia es el lugar donde algo se nos rinde presente, pero ¿qué es esta presencialidad?. Lo más corriente es llamar evidencia a esta presencialidad, la que además asociamos con inteligibilidad y a ésta con racionalidad. El rasgo común de toda inteligibilidad es la presencia inmediata (de lo inteligible) en nuestra consciencia y que excluye toda duda de esta presencia. Pero si el Ser habla, para Panikkar (2007b) existe una evidencia acústica de una presencia no directamente inteligible:" ([Sepúlveda Pizarro 2015:65](zotero://open-pdf/library/items/FD4XPIM8?page=65))**

**"Somos conscientes de que algo esté presente en nuestro espíritu y que no nos exige interpretación; no nos es inteligible; lo aceptamos como un dato; no lo cuestionamos; ni su resistencia a la interpretación se nos hace problema a no ser que alguien nos lo cuestione. (p.107)" ([Sepúlveda Pizarro 2015:66](zotero://open-pdf/library/items/FD4XPIM8?page=66))**

**"Esta consciencia de una presencia en cuanto presencia y no en cuanto inteligible, sería la presencia de "algo" sin saber lo que es. Esta presencia es el mythos. Pero no debemos confundir esta presencia como un objeto, el mythos es la aparición misma, no lo que aparece, es el horizonte de presencialidad que se nos hace consciente. Es por esta razón, que es el primer peldaño de la consciencia, nos apoyamos en él para los demás pasos. El mythos como el horizonte de presencialidad nos deja quietos, lo vemos presente, entero, aún no escindido por la razón:" ([Sepúlveda Pizarro 2015:66](zotero://open-pdf/library/items/FD4XPIM8?page=66))**

**"El movimiento del espíritu por el cual aceptamos el mythos no es la pura racionalidad, sino algo mucho más profundo que nos convence de que ello es así, con visos de una verdad que no es lógica sino precisamente mítica. (Panikkar, 2007b, p.109)" ([Sepúlveda Pizarro 2015:66](zotero://open-pdf/library/items/FD4XPIM8?page=66))**

""Junto al conocimiento conceptual, para el cual el amor no es absolutamente necesario, se da, sin embargo, el conocimiento simbólico, que exige la salida del cognoscente ( y por tanto amor) para participar en el símbolo - esto es, amarlo" (Ibid)." ([Sepúlveda Pizarro 2015:69](zotero://open-pdf/library/items/FD4XPIM8?page=69))

"Es por esta razón que para nuestro autor afirmar que la realidad se nos manifiesta en forma de mythos, quiere explicitar que la experiencia integral ve lo concreto encarnando lo universal, como una epifanía real del Todo." ([Sepúlveda Pizarro 2015:64](zotero://open-pdf/library/items/FD4XPIM8?page=64))

 "En este sentido, cabe hacerse la pregunta por una "experiencia consciente" y no una "consciencia reflexiva". Al respecto, Panikkar se plantea las siguientes preguntas: "¿Es posible una experiencia que excluya esta autoconsciencia destructiva? ¿Puede existir una experiencia en la cual el sí-mismo que experimenta sea el mismo que la experiencia misma?" (Panikkar, 2007a, p. 320)." ([Sepúlveda Pizarro 2015:54](zotero://open-pdf/library/items/FD4XPIM8?page=54))

La mística es más cauta: ni afirma ni niega. Por eso no dice que la flor sea una parte de la realidad ni que sea toda la realidad. Diría más bien que la flor es símbolo del Todo, que en la flor "está" toda la realidad. No es, evidentemente, un conocimiento (conceptual) absoluto, sino una experiencia (integral) concreta. (Ibid, p.76)" ([Sepúlveda Pizarro 2015:55](zotero://open-pdf/library/items/FD4XPIM8?page=55))

"81 Considerando los desafíos que plantea su pensamiento no objetivante, Panikkar desarrollará la hermeneútica diatópica, la que define: "en cuanto la distancia a superar no es meramente temporal, dentro de una única y amplia tradición, sino que la distancia que existe entre dos topoi humanos, "lugares" de comprensión y autocomprensión, entre dos (o más) culturas que no han elaborado sus modelos de inteligibilidad o sus premisas fundamentales a partir de una tradición histórica común o mediante una influencia recíproca" (Panikkar, 2007a, p.33). La hermenéutica diatópica no es objetivable en cuanto que considera al otro como una fuente de conocimiento igualmente original." ([Sepúlveda Pizarro 2015:62](zotero://open-pdf/library/items/FD4XPIM8?page=62))

"La misma experiencia indica más que simple inmediatez; indica com-penetración, haber penetrado en el mismo interior de la cosa "experienciada". Procede del griego περάω, peraô, pasar a través; entrar, penetrar, y del sánscrito pi-piparmi, conducir (cf. perito, peligro, experto, puerta y, naturalmente, experimento, etcétera). La experiencia se reconoce en aquel "interior intimo meo" ("más interior que lo mío más íntimo") de san Augustín. (Panikkar, 1007b, p.82)" ([Sepúlveda Pizarro 2015:54](zotero://open-pdf/library/items/FD4XPIM8?page=54))

"El último recurso en el hombre está en su experiencia. Por eso para nuestro autor comprender el dato, la cosa, la Vida como lo dado exige una actitud más receptiva." ([Sepúlveda Pizarro 2015:54](zotero://open-pdf/library/items/FD4XPIM8?page=54))

"Como veremos más adelante, la metáfora índica de la śruti (audición) es más cercana a la experiencia de la Vida que la metáfora griega del ve" ([Sepúlveda Pizarro 2015:54](zotero://open-pdf/library/items/FD4XPIM8?page=54))

""La experiencia es don - el don de la Vida (...) Hay algo que se nos da - y que por tanto se recibe" (Ibid, p.83)." ([Sepúlveda Pizarro 2015:54](zotero://open-pdf/library/items/FD4XPIM8?page=54))

"Panikkar hace referencia a la experiencia de la plenitud, del "toque" consciente con toda la realidad desde un ángulo concreto. Es la intuición totum in parte. Es decir, le da un fundamento antropológico a la experiencia del Todo en la unicidad de cada ser. Por eso, nuestro autor define a la experiencia como el "toque consciente con la realidad" (Ibid, p.82)," ([Sepúlveda Pizarro 2015:54](zotero://open-pdf/library/items/FD4XPIM8?page=54)) donde toda experiencia es corporal, consciente y divina. Esta concepción implica superar la visión tradicional de experiencia como consciencia reflexiva." ([Sepúlveda Pizarro 2015:54](zotero://open-pdf/library/items/FD4XPIM8?page=54)

"La delimitación conceptual del tema de estudio implica una nueva forma de comprender las nociones de lo divino, naturaleza y hombre; y además superar aquellas visiones dualistas que concibe las relaciones de estas dimensiones como zonas ontológicas diferenciadas." ([Sepúlveda Pizarro 2015:15](zotero://open-pdf/library/items/FD4XPIM8?page=15))

"experiencia humana; experiencia que el hombre moderno ha perdido" ([Sepúlveda Pizarro 2015:19](zotero://open-pdf/library/items/FD4XPIM8?page=19))

"Diferenciándose de este paradigma, Panikkar en su pensamiento místico, destacará el criterio de libertad de la realidad, situándose en el paradigma índico ser, hablar, pensar; postura que para la investigadora es fecunda para el tema de estudio, puesto que nos asienta en la realidad simbólica" ([Sepúlveda Pizarro 2015:15](zotero://open-pdf/library/items/FD4XPIM8?page=15))

Tal como se indicó al principio, esta investigación se sitúa conceptualmente desde el término experiencia, y es desde ahí donde las lecturas de los trascendentalistas, R.W.Emerson, H.D. Thoreau, el naturalista Aldo Leopold y el conocimiento ancestral de los pueblos indígenas de América ayudan a afirmar ciertas tesis que la investigadora va desarrollando, específicamente en el capítulo seis referido a la naturaleza como símbolo y al capítulo siete sobre la sabiduría de la Tierra." ([Sepúlveda Pizarro 2015:16](zotero://open-pdf/library/items/FD4XPIM8?page=16))

"la relación del hombre y la naturaleza, una experiencia integral de Vida, se quiere argumentar tal como se indicó, que la experiencia con la naturaleza es una experiencia mística." ([Sepúlveda Pizarro 2015:16](zotero://open-pdf/library/items/FD4XPIM8?page=16))

"la experiencia mística no es exclusiva de algunas personas privilegiadas, sino que constituye una dimensión esencial del hombre, aunque hoy se encuentra atrofiada por nuestra actual sociedad tecno-científica." ([Sepúlveda Pizarro 2015:16](zotero://open-pdf/library/items/FD4XPIM8?page=16))

"Esta experiencia se desplaza de una antropología dualista (cuerpo y alma) a una antropología trinitaria: cuerpo, intelecto y espíritu, y cuyo órgano de conocimiento se funda en los tres "ojos" de apertura a la realidad: sentido, intelecto y espíritu." ([Sepúlveda Pizarro 2015:16](zotero://open-pdf/library/items/FD4XPIM8?page=16))

"Panikkar denominará a la experiencia mística, "experiencia integral de la realidad" (Panikkar, 2007" ([Sepúlveda Pizarro 2015:16](zotero://open-pdf/library/items/FD4XPIM8?page=16))

"Con la palabra "experiencia", Panikkar también quiere destacar la estructura trinitaria del ser humano y de la realidad. La experiencia para nuestro autor, es el "toque consciente con la realidad" (Panikkar, 2007, p.82), donde la palabra "toque" manifiesta el carácter concreto, encarnado y finito de cada ser de la realidad; la palabra "consciencia" su dimensión humana; y la palabra "realidad" la dimensión divina, puesto que en "este toque nos identificamos con toda la realidad" (Panikkar, 2007, p.88). Desde esta perspectiva, si la experiencia es un "toque consciente con la realidad" significa que es una experiencia "integral", es decir, "es aquélla no tocada por ninguna interpretación ni intermediario: es pura experiencia, íntegra, 'intocada'" (Panikkar, 2007, p.69). La experiencia "integral" es la intuición totum in parte y se funda en una consciencia simbólica:" ([Sepúlveda Pizarro 2015:17](zotero://open-pdf/library/items/FD4XPIM8?page=17))

"La mística es más cauta: ni afirma ni niega. Por eso no dice que la flor sea una parte de la realidad ni que sea toda la realidad. Diría más bien que la flor es símbolo del Todo, que en la flor "está" toda la realidad. No es, evidentemente, un conocimiento (conceptual) absoluto, sino una experiencia (integral) concreta. (Panikkar, 2007, p.76)" ([Sepúlveda Pizarro 2015:17](zotero://open-pdf/library/items/FD4XPIM8?page=17))

"Para Panikkar el ser humano posee tres "ojos" que le abren a la experiencia de la Vida. Estos tres ojos hace mención a los tres "órganos" que prácticamente todas las culturas identifican como mediadores en el contacto del hombre con la realidad: sentidos, razón y fe." ([Sepúlveda Pizarro 2015:56](zotero://open-pdf/library/items/FD4XPIM8?page=56)) "Esta tríada se corresponde tanto con la antropología trinitaria (cuerpo, alma y espíritu) como con la tripartición cosmoteándrica: divino, humano y kosmos." ([Sepúlveda Pizarro 2015:56](zotero://open-pdf/library/items/FD4XPIM8?page=56))

"No podemos sentir, 68 pensar y experimentar sin materia, logos y espíritu" (" ([Sepúlveda Pizarro 2015:56](zotero://open-pdf/library/items/FD4XPIM8?page=56))

 : "No podemos conocer la realidad en cuanto tal, puesto que ella no es ningún objeto (de conocimiento) y es la que nos permite ser conscientes de lo que el logos presenta precisamente a nuestra consciencia" (Panikkar, 2007b, p.95)." ([Sepúlveda Pizarro 2015:61](zotero://open-pdf/library/items/FD4XPIM8?page=61))



"Al afirmar que la realidad es nuestro mythos se quiere indicar con ello que el mythos es nuestra presuposición fundamental que le da sentido a la pregunta por la realidad, por eso a la realidad no la podemos definir pues es el mismo mythos quien delimita los límites de la pregunta. Pero cabe señalar, que esta presuposición no es un "algo", sino más bien un horizonte de plausibilidad. Es por esta razón, que el discurso del mythos es un discurso último; a la pregunta ¿qué se entiende por el mythos?, podemos señalar que es una pregunta epistemológicamente no válida dado que es el mismo mythos quien confiere inteligibilidad a la cuestión sobre lo que es entender: entendemos algo cuando lo inscribimos en un mythos, es decir, es éste quien nos permite ver en forma "clara" sin seguir preguntando" ([Sepúlveda Pizarro 2015:61](zotero://open-pdf/library/items/FD4XPIM8?page=61))

"el mythos es literalmente lo que se da por descontado, no pertenece al ámbito de la reflexión." ([Sepúlveda Pizarro 2015:61](zotero://open-pdf/library/items/FD4XPIM8?page=61))

"No lo tenemos adelante, no se coloca ante nosotros, por eso que estudiarlo requiere una actitud particular: "No se puede mirar directamente a la fuente de la" ([Sepúlveda Pizarro 2015:61](zotero://open-pdf/library/items/FD4XPIM8?page=61))

"luz; hay que darle la espalda, para poder ver no la luz, sino los objetos iluminados. La luz es invisible. Y lo mismo el mito (...)" (Panikkar, 2007 a, p.29)." ([Sepúlveda Pizarro 2015:62](zotero://open-pdf/library/items/FD4XPIM8?page=62))

"Dentro del pensamiento trinitario de Panikkar, el mythos es símbolo del misterio de la realidad. Recordemos que el Ser para nuestro autor es una ser que habla y se le escucha antes de ser pensado: El Ser no se piensa (comprende, concibe, aprehende), sino que se es consciente de él; no se "ve", pero se "escucha", jugando con una metáfora griega y otra índica. La palabra habla, pero no es palabra si no es escuchada. "La fe viene de la audición" (Rom X, 17). (Panikkar, 2006, p.51)" ([Sepúlveda Pizarro 2015:62](zotero://open-pdf/library/items/FD4XPIM8?page=62))

"Sin entrar en este momento a la especificidad del pneuma, quiero desatacar la idea de que la realidad no es sólo logos, es también espíritu, y éste no se reduce al logos." ([Sepúlveda Pizarro 2015:62](zotero://open-pdf/library/items/FD4XPIM8?page=62))

"El mythos, como símbolo del misterio de la realidad, es aquella dimensión en que la filosofía deja emerger a lo no dicho, a lo no pensado, por eso para Panikkar (2007a), mythos y sabiduría van juntos:" ([Sepúlveda Pizarro 2015:62](zotero://open-pdf/library/items/FD4XPIM8?page=62))

###### Conocimiento

"Pese a este entusiasmo, la madurez científica no ha desembocado en un determinismo lógico causal de mente-naturaleza, puesto que también ha descubierto que la naturaleza posee grados de libertad y que por lo tanto no es esclava de la mente lógica del hombre." ([Sepúlveda Pizarro 2015:99](zotero://open-pdf/library/items/FD4XPIM8?page=99))

 Con esta idea quiero destacar que Panikkar en su antropología quiere recuperar la dimensión "divina" excluida en la epistemología moderna y contemporánea" ([Sepúlveda Pizarro 2015:103](zotero://open-pdf/library/items/FD4XPIM8?page=103))

"Esta investigación requiere preguntarse primero sobre una nueva antropología trinitaria que pueda responder a esta triple relación entre lo divino, lo humano y lo cósmico. Con fines heurístico, el objetivo del siguiente capítulo enfatizará la relación del hombre con lo divino para desarrollar posteriormente la relación entre el hombre el kosmos." ([Sepúlveda Pizarro 2015:99](zotero://open-pdf/library/items/FD4XPIM8?page=99))

"Me interesa detenerme en la primera objeción a fin de esclarecer más la argumentación de la intuición cosmoteándrica en el orden epistemológico, principalmente al modo de conocer la identidad-en-la diferencia "" ([Sepúlveda Pizarro 2015:77](zotero://open-pdf/library/items/FD4XPIM8?page=77))

"En el capítulo anterior, hemos visto la argumentación de Panikkar sobre el conocimiento trinitario y advaita en referencia al planteamiento metafísico de lo Uno y lo Múltiple. Aquí su argumento responde al problema epistemológico de identidad y diferencia: la realidad no es ni una (identidad) ni dos (diferencia), ni monismo ni dualismo. Veamos el siguiente ejemplo: "Un elefante no es un hombre, pero ambos son, aunque de forma diferentes. El elefante es y el hombre es, pero uno no es-el-otro" (Panikkar, 1999, p.90)." ([Sepúlveda Pizarro 2015:77](zotero://open-pdf/library/items/FD4XPIM8?page=77))

"Ambos son distintos; sin embargo, participan en el ser, aunque éste no ha de ser entendido como substrato metafísico de cada cosa, sino como "relación". Esto quiere decir, que si el hombre es y el elefante es, no podemos decir que "el elefante no-es hombre", puesto que en esta afirmación vemos al elefante como una mónada aislada y excomulgada de la comunión de los seres. Desde este pensar regido por el principio de no contradicción, la cosas son "en sí mismas" y por ende, tienen en sí mismas su fundamento sin relacionalidad con la realidad. Distinto es decir, "el elefante es no-hombre", pues si bien le negamos humanidad al elefante (el elefante es diferente al hombre), no le negamos su identidad: el elefante es." ([Sepúlveda Pizarro 2015:78](zotero://open-pdf/library/items/FD4XPIM8?page=78))

Lo que se quiere destacar es diferenciamos88, que en el "no es" no nos sino que por el contrario, es en el "es", donde nos distinguimos y a la vez nos identificamos. Es la identidad-en-la-diferencia:  ** "El es los distingue tanto como los une" (Panikkar, 1999, p.90)."**  ([Sepúlveda Pizarro 2015:78](zotero://open-pdf/library/items/FD4XPIM8?page=78))

"El "es" distingue, puesto que existe una diferencia infinita entre cada ser, pero a la vez los identifica, puesto que son una relación. La radicalidad de esta afirmación quiere expresar que son "precisamente los vínculos que relacionan cada cosa con todo lo demás los que constituyen estas mismas cosas" (Panikkar, 1999, p.90). Y este vínculo el cosmoteándrica89 es, el ser como relación, es la realidad (Panikkar, 1990)." ([Sepúlveda Pizarro 2015:78](zotero://open-pdf/library/items/FD4XPIM8?page=78))

###### Naturaleza habla

El kosmos como símbolo; más concretamente, haciendo su respectiva aclaración conceptual, la naturaleza como símbolo. Creo que asumir esta concepción dentro del pensamiento de Raimon Panikkar nos abre a explorar esta relación de una manera muy distinta a la interpretación materialista y dualista como comúnmente se la entiende. Así podemos anticipar una primera idea de este capítulo: desde la perspectiva simbólica, la naturaleza habla." ([Sepúlveda Pizarro 2015:123](zotero://open-pdf/library/items/FD4XPIM8?page=123))

"Indagar la naturaleza como símbolo significa profundizar en la relación de la consciencia humana con la naturaleza" ([Sepúlveda Pizarro 2015:123](zotero://open-pdf/library/items/FD4XPIM8?page=123))çEn la edad ecuménica, el hombre primordial (distinción que hace Panikkar del hombre "primitivo"), es el período del el hombre de la naturaleza: "Aquí naturaleza es oikos, la casa, el hábitat del hombre. Aquí lo divino está incluido en la naturaleza, que no es meramente 'natural' sino sagrada, y en última instancia una con lo divino" (Panikkar, 1999a, p.44)." ([Sepúlveda Pizarro 2015:123](zotero://open-pdf/library/items/FD4XPIM8?page=123))

"En el momento económico," ([Sepúlveda Pizarro 2015:124](zotero://open-pdf/library/items/FD4XPIM8?page=124))

"En este período, el oikos real del hombre es así su nomos; su hogar no es ya la tierra, a la que ahora ya explota para sus propios objetivos, sino el mundo ideal (de su mente, de un espíritudesencarnado -, o de un futuro que debe ser modelado según sus proyecciones ideales). El hombre es el señor incondicional y soberano del universo. Es superior a la naturaleza. (Panikkar, 1999a, p.56)" ([Sepúlveda Pizarro 2015:124](zotero://open-pdf/library/items/FD4XPIM8?page=124))

##### Naturaleza como símbolo

El viento sopla donde quiere, y oyes su sonido; pero no sabes de dónde viene ni a dónde va" (Juan 3:8)." ([Sepúlveda Pizarro 2015:97](zotero://open-pdf/library/items/FD4XPIM8?page=97))

La realidad en tanto vida. Vida entendida como Zoe, no slo como bios, vida individual. 

Panikkar nos abre a la experiencia del símbolo como realidad ontomítica y que constituye un postulado importante para una de las tesis de la presente investigación que concibe a la naturaleza como símbolo. Este planteamiento integra la realidad del mythos, logos y pneuma en inhabitación recíproca." ([Sepúlveda Pizarro 2015:17](zotero://open-pdf/library/items/FD4XPIM8?page=17))

"la centralidad del pensamiento de Raimon Panikkar está en su concepción de la relación15 realidad como" ([Sepúlveda Pizarro 2015:18](zotero://open-pdf/library/items/FD4XPIM8?page=18))

"pasar de un pensar sustancial a un pensar relacional, donde la relación tiene un status ontológico primario." ([Sepúlveda Pizarro 2015:18](zotero://open-pdf/library/items/FD4XPIM8?page=18))

la centralidad del pensamiento de Raimon Panikkar está en su concepción de la relación15 realidad como" ([Sepúlveda Pizarro 2015:18](zotero://open-pdf/library/items/FD4XPIM8?page=18))

"pasar de un pensar sustancial a un pensar relacional, donde la relación tiene un status ontológico primario." ([Sepúlveda Pizarro 2015:18](zotero://open-pdf/library/items/FD4XPIM8?page=18))

"Cuarto, Panikkar propone un nuevo neologismo, Ecosofía, la sabiduría de la Tierra. Con kosmos16 este término, al igual que el de intuición cosmoteándrica, intenta recuperar el en la" ([Sepúlveda Pizarro 2015:18](zotero://open-pdf/library/items/FD4XPIM8?page=18))

El desafío se plantea en superar aquellas visiones dominantes del conocimiento científico que disecciona y objetiviza a la naturaleza. Panikkar le otorgará un fundamento antropológico al dinamismo extático (amor) y entático (conocimiento), que hace del amor cognoscente la forma de conocer a la naturaleza." ([Sepúlveda Pizarro 2015:19](zotero://open-pdf/library/items/FD4XPIM8?page=19))

"El capítulo seis, trata la relación del hombre con el kosmos (naturaleza), asumiendo que el conocimiento simbólico propuesto por nuestro autor nos lleva a comprender una relación constitutiva entre consciencia y naturaleza, muy diferente a la relación epistemológica moderna entre sujeto y objeto." ([Sepúlveda Pizarro 2015:20](zotero://open-pdf/library/items/FD4XPIM8?page=20))

"Para Raimon Panikkar, el objeto del pensar filosófico en occidente ha sido la realidad, que muy a menudo se le ha identificado con el ser. En esta identificación está implícita la unidad pensar y ser, donde el pensar nos dice que es el ser y la realidad (hay una dirección del pensar al ser). No obstante, para Panikkar a la realidad se le escapa al logos." ([Sepúlveda Pizarro 2015:22](zotero://open-pdf/library/items/FD4XPIM8?page=22))

"Para nuestro autor, occidente se ha acostumbrado de tal manera a la objetivación de la realidad que la pregunta siempre es formulada en tercera persona ¿qué es la realidad?, ¿qué es el ser?; a diferencia de algunas tradiciones orientales donde la pregunta se formula en primera persona ¿qué o quién soy?. La Upaniṣhad (Panikkar, 2012) pregunta: "Qué 18 es lo que, conociéndolo, permite conocerlo todo" (p.123), la respuesta es el quién conoce y no el conocedor conocido (que sería un conocedor objetivado)." ([Sepúlveda Pizarro 2015:22](zotero://open-pdf/library/items/FD4XPIM8?page=22))



"En este sentido nuestra experiencia corporal nos hace ser consciente de que tocamos la realidad en un solo punto: "es la tangente de nuestra 'contingencia' (cum tangere)" (Ibid, p.89); y es "integral" si por esta palabra la entendemos en su origen etimológico: "integral proviene de in y de tangere (de la raíz teg), no tocado, intacto, no manipulado ni siquiera por la mente" (Ibid, p.40). Esto quiere decir, que en este toque nos identificamos con toda la realidad: "Por eso dijimos también 'experiencia integral', porque no la toca (in-tangere) ni por tanto necesita ningún órgano particular. No toca la realidad; somos ella, aunque en un punto tangencial sin dimensiones" (Ibid, p.88-89). Es por esta razón que no existe ni tocante ni tocado." ([Sepúlveda Pizarro 2015:55](zotero://open-pdf/library/items/FD4XPIM8?page=55))

###### Ecosofía

El pensamiento ecológico ha dado un avance significativo en su concepción de la realidad, dando inicio a un nuevo paradigma de la interdependencia, tal como lo describe Boff (1997): La ecología, al nivel de paradigma, implica una actitud básica: pensar siempre holísticamente, es decir, ver continuamente la totalidad, que no es la resultante de la suma de las partes, sino de la interdependencia orgánica de todos los elementos; con ello se supera el pensamiento meramente analítico, atomizado y no religado, propio de la modernidad. (p.60)" ([Sepúlveda Pizarro 2015:22](zotero://open-pdf/library/items/FD4XPIM8?page=22))

Sin embargo, la dificultad del pensar la interdependencia radica en concebir la realidad como relación y no como sustancia, es decir, la relación como consciencia originaria y no como una "entidad" subsidiaria a todo ser individual." ([Sepúlveda Pizarro 2015:22](zotero://open-pdf/library/items/FD4XPIM8?page=22))

"indagar en la concepción de la realidad como relación en Raimon Panikkar. Como veremos en nuestro autor, la pregunta por la realidad no sigue los caminos de investigación epistemológica de occidente. Una breve alusión a su forma de preguntar, nos ayuda a introducirnos en su pensamiento." ([Sepúlveda Pizarro 2015:22](zotero://open-pdf/library/items/FD4XPIM8?page=22))

### Estado del Arte

### Metodologías

### Sistema de comunicación plantas sere humanos -Prototipo-

"Si "Al principio existía la Palabra", el Principio es el Silencio, de donde nace la Palabra. La palabra re-vela cubriendo con su sonido al Silencio. En este sentido, el Silencio es ausencia de Palabra y desde un punto de vista lógico es "anterior", porque es lo que la hace posible" ([Sepúlveda Pizarro 2015:49](zotero://open-pdf/library/items/FD4XPIM8?page=49))

"el ser verdadero es cuando deja de ser paramdarse a los demás." ([Sepúlveda Pizarro 2015:50](zotero://open-pdf/library/items/FD4XPIM8?page=50)) "Es decir, los seres son en su relación de inter-in-dependencia con los demás." ([Sepúlveda Pizarro 2015:50](zotero://open-pdf/library/items/FD4XPIM8?page=50))

###  De la extracción a la siembra de datos 

 

 ## Conclusiones

[PROCESO DE ESCRITURA]

Explorar las maneras como los seres humanos resolvemos problemas de manera algoritmica, heurística, etc.  es fundamental para abordar los problemas en las humanidades digitales donde confluyen disciplinas y metodologías. Hay aspectos de los problemas que se resuelven algoritmicamente pero hay otros que requieren de pensamiento paralelo o enfoques heurísticos. En esta tesis en particular el pensamiento paralelo entendido como la confluencia de múltiples soluciones a un problema me permitieron explorar el problema e identificar todos los aspectos relacionados. Sin embargo, hice uso del pensamiento algoritmico para solucionar problemas de las herramientas y diseñar experimentos. 

## Referencias

Dunne, A., & Raby, F. (2013). *Speculative everything: Design, fiction, and social dreaming*. The MIT Press.

García Díaz, P. (2008). *Bruno Latour y los límites de la descripción en el estudio de la ciencia* [Http://purl.org/dc/dcmitype/Text, Universidad de Granada]. https://dialnet.unirioja.es/servlet/tesis?codigo=71660

Gray, C., & Malins, J. (s. f.). *Procedimientos/Metodologías de investigación para artistas y diseñadores*. Recuperado 16 de agosto de 2020, de [http://carolegray.net/Papers%20PDFs/EPGAD%20Spanish%20translation.pdf](http://carolegray.net/Papers PDFs/EPGAD Spanish translation.pdf)

Gray, C., & Malins, J. (2004). *Visualizing research: A guide to the research process in art and design*. Ashgate.

Grand, S., & Wiedmer, M. (2010). *Design Fiction: A Method Toolbox for Design Research in a Complex World*. 16.

Gurstein, M. (2000). *Community Informatics: Enabling Community Uses of Information and Communications Technology*. https://pdfs.semanticscholar.org/4c5a/6b7c0885415791e12ac0c000132358461582.pdf

Jonas, W. (2007). Design Research and its Meaning to the Methodological Development of the Discipline. En R. Michel (Ed.), *Design Research Now* (pp. 187-206). Birkhäuser Basel. https://doi.org/10.1007/978-3-7643-8472-2_11

Latour, B. (1983). Dadme un laboratorio y moveré el mundo. En M. I. González García. (Trad.), *Science Observed: Perspectives on the Social Study of Science* (Ciencia, Tecnología y Sociedad CTS-OEI). https://www.oei.es/historico/salactsi/latour.htm

Lafuente, A., Gómez, D., & Freire, J. (2018). *El Arte De Documentar*. https://doi.org/10.5281/ZENODO.1195211

Lafuente, A. (2007). Los cuatro entornos del procomún. *Archipiélago: Cuadernos de crítica de la cultura*, *77*, 15-22.

Moreira, G. M. C. (2012). *El concepto de mediación técnica en Bruno Latour*. 26.

Organización Mundial de la Propiedad Intelectual. (2015, noviembre 19). *¿Qué significa proteger los conocimientos tradicionales y las expresiones culturales tradicionales desde la perspectiva de la propiedad intelectual?* http://www.wipo.int/edocs/mdocs/tk/es/ompi_iptk_pan_15/ompi_iptk_pan_15_presentation.pdf

Rodríguez Méndez, M. E. (2001). *Metadatos y recuperación de información: Estándares, problemas y aplicabilidad en bibliotecas digitales*. https://e-archivo.uc3m.es/handle/10016/26863

Ramsey, S., & Rockwell, G. (2012). Developing Things: Notes toward an Epistemology of Building in the Digital Humanities | Stephen Ramsay and Geoffrey Rockwell” in “Debates in the Digital Humanities” on Manifold. En *Debates in the Digital Humanities*. https://dhdebates.gc.cuny.edu/read/untitled-88c11800-9446-469b-a3be-3fdb36bfbd1e/section/c733786e-5787-454e-8f12-e1b7a85cac72#ch05

Rico de Alonso, A. (2005). Las categorías de investigación. En *La investigación social: Diseños, componentes y experiencias*. Pontificia Universidad Javeriana. [https://www.javeriana.edu.co/blogs/mlgutierrez/files/Rico-de-Alonso-Et-al-CAP%C3%8DTULO-4-Categor%C3%ADas1.pdf](https://www.javeriana.edu.co/blogs/mlgutierrez/files/Rico-de-Alonso-Et-al-CAPÍTULO-4-Categorías1.pdf)

Srinivasan, R. (2007). Ethnomethodological architectures: Information systems driven by cultural and community visions. *Journal of the American Society for Information Science and Technology*, *58*(5), 723-733. https://doi.org/10.1002/asi.20544

Zeisel, J. (1984). *Inquiry by Design. Tools for enviromente-behavior research.* (Harvard University). http://staff.washington.edu/villegas/BerlinSyllabus2008/zeisel_inquirybydesign.pdf



## Anexos
