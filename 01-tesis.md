# El lenguaje del botsque: pensar las relaciones plantas seres humanos en entornos digitales de aprendizaje colaborativo interespecies 



```
Cualquiera que sea el objeto, su perfección es un defecto. Dejad las cosas inacabadas, tal como son, sin refinarlas, me interesaré por ellas y me sentiré contento. Se me ha dicho: Cuando se construye una morada imperial, es costumbre dejar un lugar inacabado. En los textos religioso, búdicos u otros, escritos por los sabios de antaño, ¿no es cierto que se encuentran ejemplos de capítulos que faltan?  El libro del Ocio. Urake Kenko
```




[TOC]

##   Introducción

Técnicamente esta tesis se logró a un año de presentar este trabajo. Implementé una wiki semántica etnobotánica (relaciones seres humanos-plantas), por medio de formularios estructurados con estándares de metadatos (Dublin Core, Foaf) que, al convertirse en plantillas en la wiki permitían construir colaborativamente una base de datos relacional. Todas estas características de la wiki semántica cumplían con los requerimientos del proyecto: eficiencia en la estructuración, recuperación, migración e interoperabilidad de la información y acceso y construcción colaborativa del conocimiento. Sin embargo, aparecieron problemas de carácter conceptual,legal, ético y de diseño que reformularon el proyecto así como mi lugar en tanto humanista digital. En este sentido, este documento da cuenta de dos cosas: el problema al que llegué y una exploración de sus posibilidades y la ruta mediante la cual descubrí, prototipé y documenté, los problemas que emergieron en el camino hasta encontrar el problema. 

El primer asunto lo abordo en el _Lenguaje del botsque_, una propuesta que sitúa los sistemas conversacionales con agente virtuales, _bots_ [^1], como asistentes en sistemas de aprendizaje colaborativo que en este caso, permiten dar cuenta de las relaciones plantas-seres humanos. Estas relaciones las entiendo desde una perspectiva en la que las plantas son agentes y no objetos en el proceso del aprendizaje. Para desarrollar dicha propuesta utilicé el diseño especulativo como metodología, el cual me permite construir un escenario utópico para activar dos asuntos: ¿Es posible llegar al conocimiento directo de las plantas a través de la escucha y la contemplación? y ¿cuáles son los entornos en los que podemos construir un diálogo interespecie e intercultural con y sobre las plantas? La razón por la cual este prototipo toma la forma que expondré se debe a que el problema al que llegué, después de haber realizado la wiki semántica y darme cuenta, en la validación del prototipo, que allí "no se veían las relaciones plantas-personas". 

Abordar la agencia de la plantas como actores en la construcción del conocimiento colaborativo en entornos digitales introduce en las humanidades digitales las discusiones sobre lo no humano que abordan las pos-humanidades desde la filosofía, la antropología y estudios de la ciencia en diálogo con la biología, la teología y la etnografía. Las indagaciones sobre las maneras cómo se comunican las plantas están en campos experimentales aún, Biólogas como Mónica Gagliano (2017) vienen  observando cómo las plantas tienen memoria y aprenden de manera asociativa y, por lo tanto, las asumen como seres con pensamiento y consciencia. Pero, si las plantas aprenden ¿qué nos pueden enseñar y cómo aprender de ellas? Para Raimond Panikkar el conocimiento se da por medio de la escucha de la naturaleza, "el que habla es el hombre y la naturaleza a través del hombre cuando el hombre no se desentiende de ella y sabe ser su voz en vez de querer ser el dominador”(Panikkar, 2011, p.338 citado en Sepúlveda,2015,p.138).Esta perspectiva dialoga con la semiótica de Peirce (1986) para quien nuestra realidad se manifiesta a través de signos, que emergen y se crean por mentes humanas o no. 

> El pensamiento no necesariamente debe estar conectado con un cerebro. Aparece en el trabajo de las abejas, de los cristales, y a través de todo el mundo físico;[...] No solamente se puede decir que el pensamiento está en el mundo orgánico. sino también que se desarrolla allí. Pero, como no puede haber un General sin Instancias que lo encarnen, igualmente no puede haber pensamiento sin Signos. Acá debemos dar a "Signo" el sentido más amplio, sin lugar a dudas, pero ese sentido no debe ser tan amplio como para exceder nuestra definición. Admitiendo que los Signos conectados entre sí deben tener una Cuasi-Mente, puede declararse en consecuencia que no puede haber ningún signo aislado (p.81).

Por lo anterior, se afirma que reconocer lo no humano como parte de los procesos sígnicos o semiosis como lo llama Peirce, implica que allí también hay pensamiento. Pero, ¿qué significa el pensamiento de las plantas? Más allá de si las plantas producen signos y son parte de una mente en la que se producen, ¿cómo piensan las plantas? Michael Marder indaga sobre ese pensar de las plantas y su lugar en la filosofía vegetal. Este marco teórico me permite indagar sobre la hermenéutica intercultural como principio para poder entender las relaciones con las plantas desde una perspectiva antropológica y así problematizar las perspectivas epistemológicas desde las cuales pensé las relaciones plantas-personas. Así, en este apartado incluyo una aproximación al _Lenguaje del botsque_ sistema desarrollado desde el diseño especulativo. El prototipo que me fue posible idear tras haber realizado una ruta de investigación preliminar en el que el problema se me reveló. Por ello es preciso responder cómo llegué al problema.

En la metodología de investigación cualitativa y cuantitativa el planteamiento del problema suele ser el punto de partida, pero en este proyecto de investigación fue el punto de llegada. ¿Por qué llegué y no partí del problema? Como desarrollo en el apartado "Saberes adventicios", saberes que se dan en lugares insospechados, de manera accidental, en las humanidades digitales la integración de varias disciplinas implica trabajar en zonas de frontera y los problemas se refinan en la medida en que se vinculan los saberes disciplicares. En mi caso, las perspectivas de la bibliotecología y antropología, fueron precedentes para la formulación del problema inicial del proyecto: democratización del saber etnobotánico en plataformas colaborativas. Sin embargo, no fueron suficientes para darle forma. El diálogo que establecí con la gestión de sistemas de información, el derecho de autor y la propiedad intelectual, la teología y, en especial con el diseño reveló aspectos y metodologías que no había tenido en cuenta y que difícilmente los hubiese podido tener en cuenta en una exploracion teórica inicial. Así, en esta segunda parte presento las aproximaciones metodológicas que vinculé a las humanidades digitales en relación con los prototipos realizados y discuto la función epistémica de los prototipos en el proceso de refinamiento del problema. La propuesta se fundamenta en las perspectivas de la investigación como diseño y de la teoría actor-red. Allí propongo vincular metodologías de control de versiones para hacer el seguimiento a las preguntas, conceptos, ideas y problemas emergentes y prototipos. Esta metodología está basada en el uso de software para control de versiones, entre los cuales está Git, y que utilizan ampliamente desarrolladores para documentar y trabajar colaborativamente. Seleccioné este sistema de versiones debido al soporte que encontré en comunidad virtuales en español que me han acompañado en el proceso de aprendizaje a través de canales de Telegram (MIAU)[https://t.me/miau2018] y (Git en español)[https://t.me/git_en_espanol]

Cabe resaltar que la metodología en este proyecto tuvo un giro determinante. Inicialmente, las relaciones entre los presupuestos teórico y conceptuales me permitieron abordar metodologías participativas de las Humanidades o centradas en el usuario provenientes del diseño. Sin embargo, a medida que realicé prototipos, empecé a utilizar metodologías centradas en los conceptos, lo cual me ayudó a pensar el problema. En específico, el diseño crítico como el diseño especulativo me permitieron pensar mis presupuestos, abrir la posibilidad de investigar y diseñar sin tener como objetivo la implementación efectiva del prototipo, pues no estaba relacionado con la resolución de un problema de diseño centrado en el usuario. En cambio, al tratar el diseño de conceptos tuve la posibilidad de especular sobre uno que denomino diseño centrado en el ecosistema. Esta propuesta emergente se formula como la posibilidad de abordar especulativamente una hermenéutica para establecer la escucha y el diálogo con las plantas. Para comprender a un otro, en este caso no humano, se deben desplegar modos para entablar un diálogo. La manera en la que se puede dar con lo no humano y el alcance de lo que comprendemos como diálogo, lo desarrollo desde la hermenéutica intercultural de Panikkar. Este marco teórico me permite especular sobre la tecnología para la comprensión interespecies. Todo esto lo desarrollaré en el marco teórico titulado "Plantar".

Toda la documentación de esta tesis está disponible en [Github] (https://github.com/mjespinosam/botsque-doc) y todos los esquemas, ideas, bocetos están bajo licencia creative commons, atribuir, derivar, sin fines económicos. Para quienes quieran comentar la tesis a través de hypothe.is [^2], herramienta de lectura colaborativa, pueden realizar comentarios públicos.

[^1]: Los programas orientados a crear sistemas conversacionales o _chatbots_, se remontan a Eliza, el primer bot conversacional que apareció en los años sesentas. Creada po Joseph Wizembau, del Instituto de Massachusetts (MIT), Eliza parodiaba las terapia psicológica. La conversación no robótica se daba mediante la recuperación de palabras claves y preguntas sobre ellas. Además contaba con frases hechas, palabras empáticas y de continuidad.Los chatbots trabajan con el procesamiento de lenguaje natural y se entrena a partir de la interacción con los usuarios.Actualmente se desarrollan con algoritmos de inteligencia artificial y evolutivos. Su uso más común es para la búsqueda y recuperación de información. Este tema se desarrollará más en el prototipo. 
[^2]: Para acceder a hypothe.is (https://web.hypothes.is/start/) es preciso crear un usuario en su página, instalar la extensión y unirse al grupo. 

## I. Las Raíces del problema

_¿Buscabas la causa en la naturaleza? Esto se refiere a eso, y eso a aquello, y aquello a lo otro, y todo se refiere a algo. Debes preguntar de otro modo, debes sentirlo y quererlo, debes contemplarlo con un espíritu tan grande como aquél por que existe, antes de poder conocer la ley. Emerson (2008 [1896], p.101)_

Ante la pregunta, ¿de qué manera dar cuenta de las relaciones entre plantas y seres humanos en una plataforma colaborativa, de tal modo que las plantas sean consideradas actores y partícipes del conocimiento que se genera en esa interacción?, es preciso establecer un marco teórico y conceptual que nos permita partir de una perspectiva de la realidad no objetivamente. Es preciso, además, superar las nociones de sujeto y objeto para la integración de lo no humano en la constitución del conocimiento. Esto implica reconocer y hacer partícipe de la experiencia del conocimiento a todo lo que no sea humano, pero, sobre todo, implica conocer la manera como otros entienden y conocen lo no humano, en este caso las plantas, para comprender, dialogar y vincularse con otras epistemologías. Pero, ¿cómo abordar esas epistemologías que reconocen lo no humano como actor en la construcción de conocimiento colaborativo en un entorno digital? En lo que sigue, me gustaría recoger tres reflexiones que superan el paradigma científico dominante que desconoce lo no humano y que pueden dar pistas sobre el debate en las humanidades digitales: la hermenéutica intercultural y la ecosofía de Raimon Panikkar,la Semiótica de Pierce y el pensamiento de las plantas de Michael Marder. A partir de estos tres autores, construyo el principio de realidad, más allá del antropocentrismo, para indagar en una experiencia de la realidad de manera tripartita. Panikkar (1985) denomina intuición cosmoteándrica a una perspectiva de la realidad como experiencia que consta de tres dimensiones: "la material (espacio-temporal), la intelectual (consciente) y la mistérica (infinita)" sin subordinación entre ellass (Citado en Meza, 2009,p.15) Como anotaré más adelante para estos tres autores el pensamiento no es una cualidad humana sino que ocurre en el universo. Por ello, es posible comprender la planta como ser pensante, agente y comunicador. Estas tres cualidades han sido investigadas por Mónica Gagliano desde la biología de plantas (2017). Sus proximaciones permiten ver los desafíos que tienen las herramientas colaborativas digitales al querer integrar las plantas en relación con lo humano. Para inscribir la pluralidad de modos de conocerse y relacionarse con ellas hay que explorar otras epistemologías tanto a la hora de diseñar como de implementar software colaborativo. 

### El problema

Es claro que desde la perspectiva de la ciencia occidental la pregunta por lo sagrado se desvincula del cuerpo, la naturaleza y la materia. Esta perspectiva desacralizada, inerte y mecanicista de la realidad física devino en el conocimiento de la naturaleza a partir de la taxonomía y la disección. El biólogo y botánico Rupert Sheldrake, al reflexionar, desde un diálogo intercultural sobre el mito de fundación científica, se cuestionó por otras maneras de conocer las plantas, por comprenderlas por vía directa, desde la atención a la vida de ellas (Sheldrake,1994). Aunque la pregunta por la restitución de lo sagrado en la vida no es el tema de esta tesis, sí es claro que, para integrar lo no humano como partícipe del conocimiento sobre nosotros mismos es preciso alejarnos del aparato teórico conceptual objetivizante. Habituados a concebir la realidad como la expresión aprehendida por los sentidos, que opera bajo leyes universales determinadas por la razón y verificables a través de la experimentación, nuestra epistemología de entrada erradica toda posibilidad de autonomía y libertad de la naturaleza (Pannikar, 1999, Sheldrake, 2020). Es por ello que la misma ciencia, sobre todo las humanidades, ha venido criticando esta historia del pensamiento y, a la vez, trayendo a la escena epistemologías en las que puede haber otros modos de pensar y conocer. Así, de acuerdo con Boaventura de Sousa Santos (2011), las epistemologías del sur se levantan sobre occidente para validar las múltiples visiones de la naturaleza como parte de lo social, lo cultural y lo sagrado. Estas perspectivas no extractivistas instalan visiones plurales, indígenas o no, que coinciden en al menos dos cosas: **se puede conocer más allá de la razón y la naturaleza también siente y piensa (Simposio tierras raras, 2020)**. Como señala la escritora e investigadora Gisella Heffer (2014), la representación de la naturaleza en oposicion a la cultura permite la explotación y apropiación de la naturaleza con fines individuales y privativos dualismo que pertenece a nuestra tradición moderna y que no comparten otras visiones de mundo. Estos avances analíticos bajo las categorías de raza, género, clase y lugar, ya sea el ecofeminismo, la ecología social, la ecología profunda o el ecomarxismo coinciden en que el antropocentrismos y el androcentrismo son causa de la crisis ambiental. Sin embargo, más allá de las agendas políticas y de los activismos que nacen de estas miradas, es claro que el modelo epistémico no se desestabiliza lo suficiente. De ahí que surja la pregunta de si es posible vincular perspectivas no occidentales para investigar dentro una academia cuyo punto de partida es precisamente que la realidad se conoce a través de la razón y los sentidos. ¿Es posible posicionar modos intuitivos, no racionales de aproximación al conocimiento? Pero, ¿por qué hacerme esta pregunta en esta investigación? 

Para poder abordar lo no humano en el marco de las relaciones plantas seres humanos se requiere un desplazamiento epistemológico de las propias maneras como se piensa, se siente y se vive la naturaleza. Cada sistema, cuyos esquemas conceptuales son implícitos, establece unos límites de lo que es posible preguntar y solo dentro de ese sistema se puede dar la verificación, la justificación, la búsqueda de evidencia. En este sentido, la pregunta de esta tesis no tiene lugar bajo una postura científica si bien dialoga con ella. Necesito, es claro, otro marco de referencia de realidad. Como marcos de referencia me refiero al _mythos_ que elabora Panikkar (1999), un mito englobante que direcciona nuestro pensar y nuestra acción según el lugar cultural en el que nos situamos: 

> Aquello en que creemos de tal manera a pie juntillas que ni siquiera nos damos cuenta de que creemos en ello (…) El horizonte de inteligibilidad en el que tenemos necesidad de colocar no importa cuál idea, convicción o acto de conciencia para que pueda ser captado por nuestro espíritu (…) Aquello que hace plausible, esto es, creíble el mundo en el que vivimos o estamos (…) Una galaxia que segrega su autocomprensión y, con ella, los criterios de verdad, bondad, y belleza de todas las acciones humanas (p.14)

Ese desplazamiento de epistemologías se elabora en el pensamiento de Raimond Panikkar (1918-2010) con su propuesta de la hermenéutica intercultural o hermenéutica diatópica. Esta hermenéutica está en función no solo de la comprensión, sino del esclarecimiento de los presupuestos de realidad, comprensión que se da mediante un acto de reconocimiento del "tú", en una conversión a su _mythos_. Como se pregunta el filósofo de las religiones Carlos Miguel Gómez (2015), al revisar esta hermenéutica en relación con la tradición hermenéutica alemana:

> ¿Qué ocurre cuando la interpretación no se orienta hacia la reconstrucción del sentido de aquello que habla ya en la propia tradición, sino hacia la comprensión de otro con el cual no compartimos una comunidad de sentido garantizada por la pertenencia a un horizonte de inteligibilidad común? ¿Es posible comprender una obra, entendida en el sentido amplio del término, a la que no estamos vinculados mediante la historia efectual, y que no nos interpela desde la intemporalidad, a la vez lejana y familiar, de lo clásico? (2015, p.25)

Para Panikkar hay sistemas racionales que son ininteligibles porque no comparten la tradición de una comunidad de sentido mas esto no implica que no puedan comunicarse. Primero porque cada sistema no está cerrado y segundo porque en el encuentro, dice Pannikar, se da un intercambio ya que " la hermenéutica es el arte y la ciencia de la interpretación, de generar un sentido, de hacer significativo, de devolver los símbolos a la vida y finalmente dejar emerger nuevos símbolos" (2007, p.32). Este proceso señala Gomez, ocurre en tres momentos. El primero es la hermeneútica morfológica que implica iniciarse en el significado de una tradición particular por medio de la lectura comentada textos clásicos. Aquí todo ocurre mediante el análisis, comparación y argumentación. El segundo momento es la hermenéutica diacrónica que implica conocer la visión de mundo desde la cual una obra es generada. Y finalmente, la hermenéutica diatópica, que no busca superar una distancia ni 
parte de un horizonte de inteligibilidad común sino que es un movimiento constante entre dos universos de inteligibilidad. Esto solo es posible si se hacen visibles los presupuestos desde los que hablamos, el _mythos_. Estos principios que se contrastan con otras visiones del mundo no para establecer algo como "más verdadero", sino para permitir el descubrimiento "en el encuentro con el otro, de ciertos elementos que se hallan en una relación de equivalencia homeomórfica en las dos tradiciones" (Gómez, 2015, p.30). Esta equivalencia no es conceptual sino que es la reconstrucción digamos, del pretexto, el texto y el contexto. 

Para que esto pueda ocurrir se precisa una actitud imperativa, dice Panikkar, un principio fundamental de la hermenéutica diatópica desde la cual ocurre una "suerte de conversión". Dice Pannikar que la "comprensión por convencimiento:[implica que] no podemos comprender las convicciones de alguien a menos que de algún modo las compartamos"(Pannikar citado en Gómez, 2015. p.32 ). Para Gómez esta es una suerte de comunidad de sentido en términos de Gadamer, no es un saber presupuesto si no un modo de convertirse a la verdad que se comprende. Es aprender otra verdad, entrando en ella a través del diálogo y transformándose mediante su conocimiento. Es una comunicación que ocurre dice, por fuera de "un logos común", se da entre personas, con un tú. "El otro es fuente autónoma de autocomprensión que no puedo asimilar desde mi perspectiva". Debe ocurrir una comunión transformadora a partir de un diálogo dialógico como lo llama Panikkar. Un diálogo que " tiene profundo significado religioso" (p.36):

> El diálogo dialógico asume un radical dinamismo de la realidad, esto es, que la realidad no es dada de una vez para siempre, sino es real justamente por el hecho de que está continuamente creándose a sí  misma y no simplemente desarrollándose a partir de premisas y puntos de partida preexistentes (Panikkar, 1999, p.38)

Durante el encuentro con la otra cultura y en la búsqueda de la comprensión y conversión operan, dice Panikkar, las relaciones de equivalencia homeomórficas. Esta equivalencia, no es la traducción, sino la identificación de contextos en los cuales se comprende su significado. Las traducciones directas son posibles pero esto no se establece a priori sino que es parte del encuentro durante el cual se establecen e incluso se descubren las equivalencias y los roles homólogos en la narrativa de los _mythos_. El descubrimiento de estos equivalentes ocurre a través del aprendizaje del lenguaje del otro, de su cosmovisión. 


> En este sentido, más que una analogía simple, que indicaría que los términos son en parte iguales y en parte diferentes, el homeomorfismo establece una analogía de tercer grado: no afirma que dos términos cumplen la misma función en dos sistemas heterogéneos, sino que busca determinar lo que sería la función equivalente en cada cosmovisión (Gómez, 2015, p.31). 

Ahora bien, ante la pregunta por la comprensión y el diálogo con la naturaleza, con las plantas, la dificultad es que los aparatos teóricos y conceptuales llegan a develar pero aún no revelan lo que implican esas experiencias de comprensión, de escucha, que en un marco amplio representan una comunión con la planta, con la naturaleza. Por ejemplo, la Teoría Actor-Red identifica en un sistema de relaciones a los seres humanos y a las plantas como actantes, es decir como actores, que realizan acciones que dan cuenta de su asociación. "La acción es un apropiedad de las entidades asociadas (...) La acción no es simplemente una propiedad atribuible a los humanos sino a una asociación de actantes" (Latour,1999b,217 citado por García Díaz, 2007). Así la tar nos permite entender las relaciones en términos de acciones no de  vinculaciones entre seres. ¿Es posible desde la hermeneútica diatópica de Panikkar aproximarse a una hermeneútica vegetal en tanto la naturaleza es un tu, cuyo _mythos_ es ininteligible pero posible de ser escuchado, comprendido, desde posibles equivalencias homeomórficas, como lo han experimentado y narrado yerbateras, campesinos, indígenas y otras personas que se relacionan con ellas? 

Además de la propuesta hermenéutica intercultural, en el pensamiento de Pannikar hay una aproximación a la ecosofía. Este neologísmo está enmarcado en lo que se denomina ecologías profundas (Heffer, 2014), ecologías que, pese a sus señaladas de apolíticas e irracionales,  proponen otros modos de conocer. Además de Pannikar, pensadores como Arne Naes (1973) y Josef Estermann (2013) se adelantan a lo que no resuelven nuestros modelos de comprensión de la naturaleza, pues sus perspectivas integran lo sagrado como parte de la experiencia de conocimiento. En Panikkar, como en Mircea Eliade, menciona Javier Melloni (2020), lo sagrado está permanentemente en el acto de conocer y es una experiencia antropológica vinculada a la vida. No hay lugar para los dualismos, si no que hay continuos, por ejemplo, entre lo que una cultura presupone (_mythos_) lo que piensa (_logos_) y la materia (_cosmos_). La naturaleza no es un reflejo de la divinidad, es la divinidad. Así, la ecosofía no considera la naturaleza ajena al ser humano, ni a lo divino, sino que los entiende en relación permanente. El cosmos, que es naturaleza, aunque tiene aspectos regido por leyes, también es autónomo y crea con libertad. Y su conocimiento se puede dar tanto por métodos científicos como por medios intuitivos y directos de quienes escuchan. Esta escucha  ocurre como un acto de contemplación, integra el silencio y precede al habla.

La ecosofía es la sabiduría de y sobre la tierra, es vida. “Descubrir la vida de la Tierra significa que podemos entrar en una relación personal con ella" (Panikkar citado en Meza, p.8). Esta perspectiva la comparten las comunidades indígenas y poblaciones americanas e incide en las prácticas políticas y culturales donde lo no humano tiene demandas frente a los actos que el ser humano quiere emprender. Así, la ecosofía marca una diferencia con la ecología, la cual, dice Panikkar:  "no dará sus frutos, como se está viendo, mientras se reduzca a una ciencia pragmática de una mejor explotación de las riquezas naturales. El mismo lenguaje corriente nos indica que no hemos cambiado de mentalidad: la Tierra como un simple objeto de ‘explotación de recursos’ –que hay que procurar que duren lo más posible” (Panikkar citado por Meza Rueda, 2010. p.138)

En este punto el mundo vegetal integra un "tu" que comparte con el ser humano la vida y a quien podemos escuchar, por que a su modo "habla", se revela ante nosotros. Pero ¿Cómo es que las plantas piensan y qué es lo que de ellas escuchamos? 



### Marco teórico y conceptual                                                                           

###  Lo que las plantas piensan y pensar como las plantas



> "Por regla general, los creyentes de hoy creen que el hombre lo "sabe" casi todo sobre los lirios, sobre su reproducción, por supuesto, sobre la química de sus colores, sobre la función del polen, sobre sus tipos y variedades, su valor de mercado, sus utilizaciones simbólicas, su metamorfosis con la tierra y mucho más. [...] Observar los lirios no quiere decir clavar la mirada en ellos aquí o allá, ahora, antes o después. Conocer los lirios es más que situarlos en el espacio y el tiempo o analizar sus partes y funciones. Conocer es más que clasificar y poder predecir comportamientos." ([Panikkar ,1998 p. 6](zotero://open-pdf/library/items/IG9M8LUL?page=2))

Si el mundo se nos revela con su sabiduría en tanto ser viviente, ¿cuáles son nuestros modos para poder escuchar, para poder establecer el diálogo y la comprensión de lo no humano? Con la hermeneútica intercultural de Panikkar podemos identificar los _mythos_ de la propia cultura y de otras que viven en comunidad con las plantas pero, ¿cómo comprender a las plantas mismas en tanto comunidad?, ¿podriamos tener entre nuestros dispositivos teórico-conceptuales algunos que nos permitan establecer ese diálogo para la comprensión? En este apartado la discusión del pensamiento de las plantas de Marder, las analogías homeomóficas de Panikkar y el signo de Peirce dan respuesta a lo que denomino hermeneútica vegetal.

Michael Marder (2013a) aborda el pensamiento de las plantas desde la filosofía. ¿Qué es el pensamiento de las plantas?, ¿cuáles son sus maneras de ser? se pregunta Marder. Para este autor el pensamiento de las plantas se refiere a cuatro ideas: el pensamiento propio de las plantas el cual no es cognitivo, ideacional o imaginativo y también "pensar sin la cabeza", lo que nosotros pensamos sobre las plantas, cómo el pensamiento humano es deshumanizado y convertido en vegetal al encontrarse con el mundo vegetal, y, finalmente, la relación simbiótica en curso entre este pensamiento transfigurado y la existencia de las plantas. 

El primer punto para comprender ese pensamiento vegetal es la intencionalidad no consciente. De acuerdo con sus indagaciones en la biología del comportamiento de las plantas (Marder, 2013), estas revelan una conciencia prereflexiva que pertenece a su vitalidad misma, lo que llamaban los griegos el alma vegetal (p.125). Parte de esa intencionalidad reune el pensamiento vegetal en el que se da fe de la existencia de un recuerdo involuntario en las plantas, que no es consciente. Esta memoria denota la existencia de un pasado que puede ser recuperado en cualquier momento y que además se usa con fines comunitarios: informan a sus congéneres de los peligros y cambios contextuales. Es decir, las plantas son seres temporales y gregarios. Pero, ¿de qué manera se recupera la información por parte de las plantas? Marder menciona dos casos emblemáticos. Por una parte, señala el de las hojas de cebada que se desarrollan si se exponen a la luz roja, siempre que tengan calcio. En caso de no tenerlo, su memoria a las hojas crecer si reciben calcio hasta cuatro horas después de haber estado expuestas. Por otra parte, están las plántulas de nilo que responden a los estímulos estresantes disminuyendo el calcio de su células. Tanto las hojas de cebada como el nilo o la mimosa permiten evidenciar que los seres vegetales retienen rastros en el recuerdo y que estos son más que una proyección idealizada de lo sucedido en el pasado. Dice Marder, "concebida cada una de manera no antropocéntrica como una cualidad primordial, la memoria inherente a las plantas en los niveles celular y molecular, llega a describir cualquier red de rastros, de los cuales la conciencia es una instancia muy circunscrita. Es el mismo hecho o facticidad de la impresión, de una impronta, o mejor, un _ex-print_, lo que forma el registro de lo que un ser vivo ha sufrido durante su vida" (Marder, 2013 a, p.127)

Así, la memoria no consciente es solo un componente de la inteligencia de las plantas que dice Marder, siguiendo a Schelling, no es "la inteligencia viva, sino la inteligencia de la vida, en el continuo siempre cambiante de sensibilidad-irritabilidad" (p.127). Este continuo entre sensibilidad e irritabilidad que marca un registro en la memoria se une al no pensar de la planta, el pensar antes del pensar, que en lo humano, dice Marder, es aquel actuar sin nuestras cabezas. Un pensar y una memoria desvinculadas de un sistema nervioso y cerebral que nos permite integrar la inteligencia como una cualidad no solo humana. Este pensamiento vegetal de conciencia no reflexiva es una noción cercana a cualidad primera de Peirce y a la revelación del símbolo de Pannikar, quienes señalan que hay una experiencia en la que no interviene el logos pero en la que hay una revelación del universo. Dice Peirce:

> La idea de lo absolutamente primero debe ser por completo separada de toda concepción -o referencia- a cualquier otra cosa; pues lo que implica un segundo es segundo él mismo para eso segundo. Lo primero debe, por lo tanto, estar/ser presente de inmediato, de modo que no sea segundo para una representación. Debe ser/estar fresco y nuevo pues, si es antiguo, es segundo para su estado primero. Debe ser iniciativo, original, espontáneo y libre; de otro modo no es segundo para una causa determinada. Es también algo vívido y consciente; así, solamente confiesa ser el objeto de alguna sensación. Precede toda síntesis y diferenciación; no tiene unidad ni partes. No puede ser pensamiento articulado: si afirma, ya casi ha perdido toda su inocencia característica; pues la aserción siempre implica la negación de alguna otra cosa. Deja de pensar en él y ¡ya ha volado!. Lo que el mundo fue para Adán el día en que abrió los ojos, antes de que hubiera esbozado cualquier distinción, o se hubiera hecho consciencia de su propia existencia -eso es lo primero, presente, inmediato, fresco, nuevo, lleno de iniciativa, original, espontáneo, fresco, vívido, consciente y evanescente. Sólo recordemos que cualquier descripción de él tiene que falsearlo. (*C. S. Peirce: «Una conjetura para el acertijo»*, s. f.) [1887-88; CP 1357]

La intencionalidad no conciente de la planta es un conocer desde la prioridad, desde la cual no se dirige la atención a sí misma y, afirma Marder, de ahí su no-identidad, su ser conceptual, en el que proliferan los significados sin necesidad de las representaciones conscientes. 

De este modo, a propósito de lo que denominé hermeneutica vegetal para la comprensión de las relaciones plantas-seres humanos se podría decir que el humano que piensa como la planta se entrega a la experiencia de la primeridad como señala Peirce y así a la conversión de su _mythos_ que como propone Marder, para conocerlo hay que estar por fuera de la lógica formal. La persona que piensa como planta:

> "[...]se convierte literalmente en planta, ya que la destrucción del logos clásico aniquila aquello que nos distingue de los demás seres vivos [...]. Para ser justos, una persona vegetal no es la que ya no piensa sino, en una formulación más matizada, la que piensa sin seguir las prescripciones de la lógica formal y, por tanto, en cierto sentido, sin pensar. Intentemos entonces acostumbrarnos a la idea de que el pensar no es prerrogativa exclusiva del sujeto, ni del ser humano, y que, además de alterar la forma del pensamiento (que se vuelve inseparable de su opuesto, el no pensamiento) y cambiando su contenido (que incluye contradicciones), "pensamiento no idéntico" indica libertad de la identidad sustantiva y encerrada en sí misma de los propios pensadores" (Marder, 2013, p.134 )

La postulación de un pensamiento vegetal coincide con la teoría semiótica de Peirce, teoría general de las representaciones, en la cual el pensamiento no ocurre necesariamente en una mente humana si no que es una cualidad del universo. Al respecto dice el matemático Fernando Zalamea, estudioso de Peirce:

> Una de las fortalezas de la semiótica peirceana, y uno de sus mayores atractivos, es dejar la noción de "cuasi-mente" o contexto de interpretación, donde se efectúa la semiosis. Al liberar los contextos de interpretación [cuasi-mentes] de los matices sicologicistas de la mente humana,  y al permitir "cuasi mentes" arbitrarias, la semiótica peirceana adquiere un rango muy amplio de universalidad. Ya que la "cuasi-mente" puede ser medio protoplasmático en el que la seimiosis  se constituye  en un proceso de crecimiento y asimilación de material en un vaivén entre licuefacción y cohesión (Zalamea, 2001)

Para Peirce, igual que para Panikkar, la realidad es tripartita. Así el signo es la relación entre un representamen un objeto y un interpretante. El representamente es algo [1] que está por algo [2],un objeto que puede ser una idea, artefacto, suceso, para alguien [3] el interpretante, la mente. Este interpretante como cuasi-mente no es necesariamente una mente humana y desde allí pueden producirse nuevos signos pues todo signo es antecedido por otro signo (p. 27).

> Un signo o representamen es un Primero que está en una relación triádica genuina tal con un Segundo, llamado su Objeto, que es capaz de hacer que un Tercero, llamado su Interpretante, asuma la misma relación triádica con su Objeto que aquella en la que está él mismo respecto al mismo Objeto. La relación triádica es genuina, esto es, sus tres miembros están vinculados por ella de una forma que no consiste en ningún complejo de relaciones diádicas. Esa es la razón por la que el Interpretante, o Tercero, no puede estar en una mera relación diádica con el Objeto, sino que debe estar con él en la misma relación que aquella en la que está el Representamen mismo (*Charles S. Peirce: «El icono, el índice y el símbolo»*, s. f.) [1903; CP 2.274]

La importancia tanto de la mente como del signo es porque son las maneras como se declara lo no humano como pensante y su modo a través de la constitución de signos. Si bien a través de los signos el universo aprende, replica, comunica, estos no son necesariamente intencionales. Para entender esta función del signo es preciso aproximarse a las relaciones que se dan entre el objeto y el representamen. Para Peirce esta relación resulta en un segundo nivel de triadicidad. El signo puede ser un ícono, un índice y un símbolo:

> un ícono es un signo que sustituye un objeto dado: señala una marca sintáctica. un índice es un ícono que, además, detecta algunas variaciones del objeto: indica un cambio semántico. Un símbolo es un índice que, además, integra las variaciones a lo largo de un contexto de interpretación: incorpora un aporte pragmático

Esto nos permitirá más adelante identificar cómo la comunicación entre las plantas y nuestra relación  crea conocimiento a través del ícono, por ejemplo la analogía, el índice como marcado que determina una causa y el símbolo como la construcción del significado contextual en la que está la planta: espacio, asociaciones, interacciones. Esto nos lleva a comprender la agencia de la planta en la construcción de las posibilidades de existencia según los recursos y las condiciones, su adaptación y creatividad, todo desde su intencionalidad no consciente.Y eso, el pensamiento y la acción de las plantas, como ya lo dijo Marder, es objeto de las investigaciones controladas en laboratorio y también en espacios abiertos. Al respecto, sabemos ya que entre plantas hay comunicación que se da tanto por vía de la emisión de compuestos orgánicos volátiles (COV), mediante los cuales advierten a otras plantas de peligros inminentes para que se preparen pese a que la distancia es limitada. Los COV son utilizados para atraer polinizadores, asegurar la reproducción y enviar mensajes tanto de emergencia como de solidaridad con las de su misma especie. Esta acción de alerta también ocurre cuando aparecen hervíboros, quienes, según la literatura científica, las plantas escuchan a escondidas: "Para preparar una defensa contra los generalista las plantas escuchan al herbívoro" (Ueda et al., 2012, p.224). 

A esta capacidad de comunicar y a la impronta de su memoria se le suma la del aprendizaje.  Nos cuenta Gagliano, bióloga especializada en el pensamiento de las plantas, que desde hasta hace muy poco la ciencia comenzó a ocuparse del aprendizaje asociativo vegetal. Es decir, el aprendizaje que ocurre a partir de un experiencia repetida de un mismo estímulo o suceso. Las plantas aprenden asociativamente con fines ecológicos que van desde buscar comida hasta cuidarse de los peligros que por el suelo o por el aire las acechan: "un estudio de 2014 demostró que las plantas pueden detectar el sonido de las orugas que se alimentan y las causadas por viento o por insectos cantores" (Gagliano, 2017, p.2), señales acústicas que refuerzan la eficacia de otros sistemas de señalización de las plantas como las de los COV. Esto llevó a la investigadora a insinuar que las plantas tienen conciencia y subjetividad. Todo el proceso de evaluación que realiza la planta la lleva a utilizar "sus propias experiencias y sentimientos como estados funcionales que motivan sus elecciones"(p.3). En cuanto a la conciencia la investigadora aboga por una conciencia básica que se logró a través del aprendizaje asociativo y de los sistemas de valores. Marder no aborda la conciencia en los términos de Gagliano, sino que habla de la intención y la no -identidad de la planta, lo cual se inclina más a la intersubjetividad que la subjetividad en las plantas. Sin embargo, tanto la filosofía como la biología y la semiótica coinciden en que el pensamiento no solo se da en una mente humana y que el aprendizaje y la comunicación también se puede dar en lo no humano, en este caso en las plantas. 

### Metodología                                                                                           

###  Diseño crítico y especulativo para pensar las plantas desde las Humanidades Digitales

Formulada la discusión de las plantas como seres pensantes que son protagonistas de su propio aprendizaje, queda la pregunta sobre cómo dar cuenta de ello en una plataforma digital. En tanto las infraestructuras exploradas en esta investigación contribuyeron a revelar los problemas de los presupuestos epistemológicos subyacentes tanto en el diseño del software como a su implementación propongo vincular el diseño especulativo como una metodología para las humanidades digitales. ( Ver apartado _Saberes adventicios: metodologías del diseño para las Humanidades Digitales_). El diseño especulativo es una herramienta que permite desligarse de la utilidad y viabilidad de los prototipos, para idear posibles respuestas tecnológicas en escenarios distópicos, utópicos o paralelos. Esto no se hace con el fin de continuar procesos de diseño para el desarrollo sino para activar discusiones. En este caso puntual esta metodología me permite idear un escenario de comunicación interespecies basado en la escucha, la hermeneútica diatópica/vegetal, la equivalencia homeomórfica y el habla en entornos colaborativos mediados por un agente virtual. Todo esto será desarrollado en el prototipo. Por ahora me permito contestar ¿qué es y por qué el diseño especulativo es una metodología apropiada?  

Desde los años noventa los diseñadores Dunne y Raby retomaron discusiones del diseño radical de los setentas para formular su manifiesto en favor de un diseño crítico el cual desvincula al diseño de la actividad centrada en la producción para un mercado para pasar a un diseño que piensa problemas sociales.  Pero, sobre todo, tuvieron como propósito cuestionar las ideas de que la tecnología era buena y capaz de resolver problemas en todos los casos “critical design uses speculative design proposals to challenge narrow assumptions, preconceptions, and givens about the role products play in everyday life.” (Dunne y Raby,2013,p.34). En el manifiesto de diseño crítico, establecen que este diseño permite encontrar problemas, para hacer preguntas, debatir, e imaginar cómo podría ser el mundo; sopesar las implicaciones; provocar reacciones; diseñar conceptos y situarnos desde lo ético. Pensar el diseño más allá de la resolución de problemas sobre todo los estéticos,  lo activa en otro tipo de relaciones con la realidad. Esta actitud permitió dar cuenta de una metodología desde el diseño especulativo y sus modos de indagar la ficción para comprender el presente. 

El diseño especulativo como lo exponen extensamente Dunne y Raby,  consiste  en ideas posibles o, futuros como herramientas para comprender mejor el presente. Estos futuros, desde el diseño, toman forma de escenarios que fundan preguntas como, ¿qué pasaría si? Todo ello como vía para abrir debates. Es decir, se establece un vínculo con un mundo que podría ser más allá de un unívoco y moralista "debería ser". Para ello, el diseño especulativo hace uso de varias herramientas: mundos ficticios, utopías y distopías, ideas como historias, experimentos de pensamientos, contrafácticos, escenarios de ¿que pasaría si? (What if). Estas herramientas vinculadas estrechamente a procesos creativos de la literatura, el cine y la arquitectura entre otras artes, no se utilizan para predecir el futuro, sino para pensar "los futuros". Así, todo este programa de investigación hace explícito un propósito político y es hacer consciente a la ciudadanía de las consecuencias de sus consumos. 

> By acting on peoples’ imaginations rather than the material world, critical design aims to challenge how people think about everyday life. In doing this, it strives to keep alive other possibilities by providing a counterpoint to the world around us and encouraging us to see that everyday life could be different. (Dunne y Raby, 2013, p.45)

De este modo, aparece el diseño conceptual o de ideas. Este diseño es diferente al Diseño desde las humanidades o el Design Thinking en tanto no opera dentro de un marco de realidad, no experimenta con cosas para hacerlas mejores, sino para pensar otras posibilidades. Es decir, la carga de la funcionalidad y pertinencia social no son principios transversales. Pensar desde el diseño conceptual es pensar desde lo no real, desde las ideas, como dicen Dunne y Raby los ideales (p.49). De acuerdo con los autores, estos futuros ficcionales, abordados abordados a partir de diversas escuelas del diseño, están estrechamente relacionados con la exploración de posibles futuros tecnológicos. En alguna medida, esta exploración conceptual a través del modelo ya lo venía haciendo el arte, el arte conceptual (Veciana Schultheiss, 2004). En campos como el diseño de modas, ha sido posible observar la exploración de conceptos a través de materiales y formas. Pero también a través de biofuturos, diseños que tienen una relación directa con la ciencia del laboratorio, con lo que sucede allí cuando se piensa la vida, la tecnología y la innovación **(CITA)** 

A partir de este breve recorrido por la apuesta del diseño crítico y especulativo, las preguntas que surgen son ¿cuál es el diálogo que dicho diseño establece con las Humanidades Digitales?, ¿por qué pensarlo como un referente metodológico y cómo integrarlo? Ahora bien, investigar desde las humanidades digitales con diseño permite traer a la escena las tecnologías, herramientas e instrumentos existentes o por existir e indagar sobre ellos, de lo que subyace a su creación. Cuando Latour habla de la cajanegrización enfatiza en la manera como las tecnologías se obscurecen tras su éxito "así, paradójicamente, sucede que la ciencia y la tecnología cuanto más éxito obtienen más opacas se vuelven". Para develar lo que conceptualmente detrás decada herramienta, como si fuese una decodificación inversa, el diseño crítico y especulativo funcionan metodologicamente para indagar las implicaciones éticas, sociales y culturales de las herramientas. Si bien una buena parte de las propuestas en HD pueden ser abordadas desde el Design Thinking, o el diseño con comunidades y desde perspectivas como la informática comunitaria (Gurstein, 2000), el diseño participativo con enfoque etnometodológico (Srinivasan, 2007), el diseño para la antropología o la antropología para el diseño (Escobar, 2016), todos ellos diseñan desde el presente. El aporte del diseño especulativo es que permite idear escenarios futuros y para ello parte de indagaciones interdisciplinarias que permitan a las investigadoras abordar el presente pero proyectándolo desde la imaginación, a escenarios utópicos o distópicos, para detonar el debate. En este sentido, todo diseño se convierte en un dispositivo para pensar-nos, para debatir y, así, el prototipo nos permite "pensar" el problema, indagar sobre sus implicaciones y retos. Aquí, las humanidades digitales dejan de posicionarse desde metodologías de la implementación de soluciones, para pasar a analizar las ideas que podrían convertirse en soluciones y sopesarlas éticamente. Si bien desde el diseño especulativo pueden surgir modelos y prototipos que revelen las intenciones y las redes para producir y crear tecnologías, su propósito no es desarrollar tecnologías o herramienta.  

En términos metodológicos, en el diseño especulativo se construye el problema interdisciplinariamente. Se levantan todos los insumos necesarios para entender un tema que se proyecto al futuro utópico, distópico, o realidad alterna y a partir de ahí, formular preguntas que vayan acotando la problemática. Los resultados de investigación en cada momento se presentan como prototipos exploratorios de la problemática acompañados de textos argumentativos. Artefactos, historias, intervenciones son algunos de los productos que emergen y que exploran tanto la posibilidad como el presente. ¿Cómo ese artefacto, sistema o experiencia detona una conversación? ¿Ese futuro imaginado que puede hablarnos del presente? ¿Qué conceptos, ideas o prácticas entrar en crisis? 

Ahora bien, ¿cuál es el escenario especulativo que me permite pensar como piensan las plantas para establecer un sistema de relaciones con ellas basados en la escucha y el habla? Dos de los prototipos de esta tesis se crearon bajo esa metodología. _La mesa huerta_ y _El lenguaje del Bosque_ . El primero que fue parte del laboratorio de co-creación de Plataforma Bogotá, Mangle Rojo y Savias Sabias, es antecendente del segundo. Sin embargo, ambos son resultado y parte de procesos anteriores que me permitieron refinar el problema. Este proceso lo enmarco en lo que se llama investigación como diseño y será abordado en el segundo aparte: _Saberes adventicios _

#### ¿Hablan las plantas? ¿Escuchamos a las plantas?                                    

#### Apuntes metodológicos para pensar la comunicación interespecie

“_La sabiduría de las plantas: incluso cuando tienen raíces, siempre hay un exterior donde forman un rizoma con algo más, con el viento, un animal, los seres humanos_." _Michael Marder_

En Panikkar encontramos la alusión a la escucha como parte del encuentro con el conocimiento en la triada ser, hablar, pensar. El logos es la palabra escuchada antes que hablada. Antes de pensar se escucha. En su trabajo sobre la relación del ser humano y la naturaleza: una experiencia integral de vida Jéssica Sepúlveda elabora esta idea de Panikkar:

> "Si la naturaleza habla, no quiere indicar que ella tenga lenguaje propiamente como el ser humano, y que se produzca un diálogo entre ambos. La relación es de otro nivel: la naturaleza habla, es símbolo de la realidad cosmoteándrica; donde el hombre participa de su habla, escuchándola, y siendo su intérprete, si sabe escucharla. Esta afirmación requiere desentenderse de la visión causal entre hablar y escuchar. (138)

Por lo tanto, la experiencia de la escucha es la puerta para el conocimiento de las plantas y para poder tener una relación con ellas:  “[...]el que habla es el hombre y la naturaleza a través del hombre cuando el hombre no se desentiende de ella y sabe ser su voz en vez de querer ser el dominador” (Panikkar citado por Sepúlveda,2015, p.143).  Y ¿Cómo escucharla?

Al respecto propongo las siguientes acciones desde el diseño especulativo como metodología para activar la hermenéutica intercultural/diatópica o hermenéutica vergetal como la denomino. Para activar la escucha como acto previo al habla y espacio de conocimiento entre los universos:

1. Comprensión del  _mythos_ de las plantas en tanto  los signos que ellas hacen sobre sí según sus contextos.
2. Comprensión de mi _mythos_ en tanto maneras cómo las pienso.
3. Creación de analogías homeomórficas que permitan establecer estados del ser entre la sensibilidad y la irratibilidad.
4. La traducción de los signos mutuos en señales acústicas.
5. La contemplación mediante la escucha profunda y compartida.

#### Las analogías homeomórficas seres humanos -plantas

La comprensión no consiste en encontrar lo que compartimos con las plantas y traducirlo a nuestro lenguaje. No es una equivalencia conceptual. Es la comprensión contextual es trasplantar "el contexto que les da significado y que les confiere el horizonte de ese contexto en el cual pueden ser comprendidos" (Panikkar citado en Gómez, 2015, p.30). El conocimiento del contexto permite que no haya deformación en la comprensión. 

El homeomorfismo vincula términos intraducibles en dos o más visiones de mundo mediante la equivalencia: "El homeomorfismo establece una analogía de tercer grado: no afirma que dos términos cumplen la misma función en dos sistemas heterogéneos, sino que buscan determinar lo que sería la función equivalente en cada cosmovisión"(Panikkar citado en Gómez, 2015, p.31). Esto no ocurre mediante un trabajo comparativo sino mediante lo que llamó Panikkar actitud imperativa. Según Gómez, la comprensión es solo posible mediante el aprendizaje de la lengua de la otra cultura para poder desde allí entrar a su visión del mundo. Es decir, convertirse a esa cultura. Para ello se necesita dice, Panikkar, la "comprensión por convencimiento: no podemos comprender las convicciones últimas de alguien a menos que de algún modo las compartamos". La comunión es el resultado del encuentro, una acción creativa desde el diálogo. (Gómez, 2015,p.32)

Una hermenéutica interespecies seres humanos-plantas puede estar impedida por la ausencia de una lengua para el diálogo. Sin embargo, siguiendo a Marder, la vida y lenguaje de las plantas se nos revela como un modo de ser y estar en el mundo y a cuya experiencia y no-pensar podemos acceder. Esta tesis postula dicho acceso como una acción de contemplación, más que de observación, y de quietud-inquietud. Como se elaborará en el prototipo, esto implica reconocer y configurar las analogías homeomórficas para que, mediante un sistema que vincule tecnologías de cosecha de datos, se pueda traducir esta información en un lenguaje que habite los espacios de contemplación y de escucha recíproca. 

Esta simulación de escucha y habla busca dar cuenta de una relación seres humanos plantas no extractivista sino de amistad.  En esta relación el ser humano tras escuchar a las plantas reconoce sus necesidades y aprende con ella, contemplándola. En el sistema los datos se transcodifican de señales eléctricas o de luz -datos conceptuales- a sonidos, que son emitidos a una comunidad de conversación. En esta comunidad de conversación en un grupo de Telegram está botsque, un bot que escucha las conversaciones de plantas y personas. Bostque da cuenta de las relaciones a través de la localización, organización, recuperación y notificacion de personas-plantas nuevas o activas en dos escenarios: siembra de datos obtenidos desde la escucha y transcodificados a sonidos que son emitidos en una emisora y, espacios conversacionales sobre las plantas y sus humanos amigos. 

#### Referentes

[**Pulsum Plantae**](http://interspecifics.cc/work/pulsum-plantae-2012/) (2011-2014)

Proyecto de Leslie García (México)

Este proyecto analiza los mecanismos que utilizan las plantas para comunicarse y cómo sus propios proceso biológicos se manifiestan pasando desapercibidos para nuestros sentidos. El proyecto crea una "prótesis de sonudo" basado en el biofeedback el cual conciste en recopilar información sobre las funciones fisiológicas de un cuerpo, utilizando instrumentos. A través de un proceso de transducción, es decir pasar una tipo de energía en señal eléctrica, que le da "voz a las plantas". Los patrones obtenidos, señala la artista, podrían ser la base para un diseño de comunicación codificada basada en el sonido.

[Muestras de sonidos de las plantas](https://soundcloud.com/lessnullvoid/sets/pulsu-m-plantae_muestras)

**[Pulsum] hardware (https://github.com/Lessnullvoid/Pulsum-Plantae)

El proyecto de Leslie García permite identificar una infraestructura electróncia que permite la transducción. Replicar su sistema para poder hacer el análisis de código comunicacional de las plantas en contexto es prometedor pues permitiría cosechar los sonidos particulares de cada planta. En todo caso el sistema botsque prima la escucha sobre el habla y el habla es el resultado de interacciones contextuales: humedad, luz, etc. Interacciones que se dan con un otro ser (humano) quien también se dispone a compartir sus datos pulso y respiración como parte de la relación para el establecimiento de analogía homeomórficas. 

**El autor de la semilla de acacia**

Ursula L Guin

Acacia Seeds esta compuesta por tres breves extractos de la futura revista Therolinguistics, el campo que estudia los lenguajes no humanos. El primer fragmento, titulado *MS. Encontrado en un hormiguero*, trata sobre los intentos de descifrar los mensajes dejados por las hormigas en las semillas de acacia. Un terolingüista está convencido de que una de esas declaraciones, traducida aproximadamente como "¡Arriba la reina!", es en realidad un llamado de un trabajador a la rebelión, porque en el mundo de una hormiga y la mente "arriba" representa la muerte y el exilio. La segunda parte es sobre una exploración al país de los pingüinos para entender su lenguaje " silencioso y ciego". La última parte  es una editorial escrita por el presidente de la asociación que hace un llamado a que se exploren los lenguajes de las plantas cuyo descuido da cuenta de la falta de imaginación. La exploración del lenguaje dice, debe expandirse a las artes pasivas por que no puede restringirse al movimiento y al tiempo sino que debe incluir nociones de recepción y respuesta. Mirar retrospectiva y prospectivamente cuando no se entendían los lenguajes de los animales pero también cuando en el futuro se burlen de quienes no comprende " la letra delicada y pasajera del liquen", la "poesía totalmente atemporal, fría y volcánica de la roca", incluso las palabras de la tierra " en su inmensa soledad, dentro de la comunidad más inmensa del espacio" (*El autor de las semillas de acacia y otros extractos del diario de la Sociedad de Zoolingüístas - La Púrpura de Tiro*, s. f.)

**Eunoia**

https://www.thelisapark.com/work/eunoia

performace que utiliza in sensor de actividad cerebral comercial para manifestar los estados de la artista en sonidos. Eunoia significa pensamiento bello en griego. El software desarrollado permite musicalizar la actividad cerebral de la artista en relación a sus estador. El código calibra el volumen, tono del sonido asociado con la variación de la atención y meditación  detectados por el sensor. El sonido produce vibraciones en el agua que está correlacionado con la intensidad d ela actividad mental. La motivación de la artista es lograr la calma para que no se produzca ningún sonido. 

**La mesa huerta**

María Juana Espinosa David Ariza

<img src="/Users/juanaespinosa/Tesis/001-tesis- git/imagenes/mesa-huerta-6.jpg" style="zoom:40%;" />

Como parte del resultado del primer laboratorio de creación colectiva de Microhuertas [“Crear/criar espacios vivos en casa”](https://vimeo.com/299020396) realizado en Bogotá (2018) un grupo interdisciplinario de creadores de la ciencia el arte y la tecnología prototipamos una “ Mesa-microhuerta” en la que se integramos sensores electrónicos con el fin de activar la comunicación entre seres humanos-plantas-agente virtual (bot). A partir de un ejercicio especulativo cuestionamos la integración de los sensores como dispositivos de control a los espacios vivos si bien reconocemos la huerta como espacio semiótico en el que se da la interacción entre sensores personas y plantas. Esta interacción construye y devela signos a partir de una experiencia corporal y emocional. Por lo tanto, la integración de los sensores más que sustituir labores de cuidado de la huerta se integran en la mediación comunicativa para la conexión con lo vivo. Bajo la pregunta ¿Cuál es el bienestar de la microhuerta y de qué manera los sensores dan cuenta de ello? Trabajamos con 4 sensores: el cuerpo como sensor primario que desde la observación determina condiciones para las plantas, y los sensores de humedad de tierra, humedad relativa y luz. Estos sensores están dispuestos de tal modo que se relaciones con la mesa a través de canales de bienestar contruídos inicialmente con tinta conductora y luego con cinta de cobre. Sobre cada canal habitan un conjunto de insectos benéficos para el entorno y elaborados de materiales electrónicos que se encienden si las condiciones son óptimas. Cada canal representa un sensor: agua, luz, humedad. Los datos son entregados vía wifi a telegram desde donde se archivan mediante un bot que comunica a la comunidad de microhuertas el estado de bienestar de las huertas. 

## II. Prototipo                                                                                           

### El lenguaje del botsque, un entorno colaborativo de aprendizaje plantas-humanos-bot.

 

El prototipo del Lenguaje del botsque es un sistema para las relaciones plantas-seres humanos que permite desarrollar la idea especulativa de una hermeneútica interespecies. El sistema está basado en procesos de escucha de datos e información que aportan plantas y seres humanos así como, la siembra de los mismos en un sistema colaborativo de aprendizaje. Las plantas aportan al sistema datos contextuales como humedad y luz relativa; los seres humanos pulso y frecuencia de respiración.  Los datos son de origen análogo y pasan a digitales para ser trans-codificados en sonidos o en silencio. La asignacion de características sonoras se establecen a partir de analogías homeomórficas que operan mediante la comprensión de equivalencias de conceptos como bienestar y desequilibrio tanto en las plantas como el ser humano. ¿Qué es estar bien para las plantas o el ser humano? ¿Qué es estar en desequilibrio? Todos los datos son agregados a una base de datos que permite hacer consultas sobre los estados de bienestar y desequilibrio de plantas y personas en la comunidad. Una transmisión sonora que implica la escucha y que se integra al sistema de aprendizaje colaborativo mediante lo que se denomina siembra de datos. Allí, la comunidad de cuenta de lo que escucha de las plantas así como, el aprendizaje a través de la lectura o conversación con sabedores e investigadores. La siembra de datos e información para el conocimiento de las relaciones seres humanos-plantas está mediado por un bosque_bot quien apoya a la comunidad en la trasnmisión del estado de las plantas y la organización, localización, recuperación y notificación de temas actuales o de interés para cada miembro. La interaccion con el bot ocurre en un sistema de mensajería Telegram, desde el cual se trasnmite, escucha y dialoga.  Existen dos canales: uno en el que la interacción es persona- bot- planta y otro que es el canal grupal de interaccion  personas-personas, plantas-personas.

**Palabras clave**: hermeneútica interespecies, analogías homeomórficas, visualización sonora, chatbots, diseño especulativo

**Problema**:  ¿De qué manera un lenguaje sonoro, resultado de la transcodificación de datos contextuales y propios de seres humanos y plantas, permite a un bot y una comunidad aprender sobre las relaciones seres humanos-plantas?

Parto de la idea de la naturaleza como signo que comunica a un ser humano que la escucha y quien, a través del habla u otros medios, revela eso que escuchó. La naturaleza comunica al ser humano cuando este se dispone a la contemplación y escucha profunda, estados relacionados con la meditación que pueden darse desde la quietud o desde la atención mientras se ejecuta una acción como las caminatas por la naturaleza, la siembra o la jardinería. El estado contemplativo es similar al pensamiento de las plantas: un pensar antes del pensar, una intención sin conciencia reflexiva que elabora Marder en su discusión sobre la filosofías de las plantas (2013). A su vez, según reportan investigaciones (Gagliano, 2015), las plantas escuchan, aprenden, recuerdan. Por lo anterior imagino un sistema que permita "escuchar" información contextual de la planta y del ser humano. La escucha de los datos de datos la construyo en tanto acción no extractivista como si lo es la minería de datos. En cuanto a la siembra de datos es una acción colaborativa para el aprendizaje que permite cultivar un conocimiento. La razón al por qué los datos son contextuales se debe a dos motivos: los sensores para escuchar a las plantas no están a mi alcance o no exiten aún y porque todo lenguaje es contextual y para comprender la planta es preciso conocerla en relación con la tierra, la microbiota, la luz, etc. Esta información, como señala Marder, es uno de los principios del modo como las plantas piensan. Ellas piensan con otros: tierra, luz, humedad, microorganismos. Finalmente, los datos de los seres humanos son la frencuencia respiratoria y la cardiaca que al igual que los datos de las plantas, son trans-codificados en el sistema para componer un lenguaje común sonorizado que configura una comunidad de lenguaje.Como señala Panikkar (2011a) la relación entre escuchar y hablar es de tipo a-dual: “No hablaríamos si primero no hubiéramos escuchado, y no escucharíamos si nuestro ser no participara del Ser que habla”(p.202) 

En los sistemas de información la transcodificación es entendida como el cambio de formato de un objeto digital. Este concepto no da cuenta de las "traducciones" que se dan en los procesos de codificación de información, analoga a digital y de digital variaciones digitales, por ejemplo, de imagen a sonido. La platicidad de los objetos digitales me permiten pensar  la trans-codificación como el proceso en el que cambian las materialidades de la información: corriente a números enteros, números enteros a sonidos o a imagénes digitales. La raíz trans que significa "que 'atraviesa', 'sobrepasa', 'de un lado a otro', 'del otro lado', 'más allá' [..] nos permitiría pensar en este cambio (*www.deChile.net*, s. f.), que desintegra un límite y rematerializa una información común: los ceros y los unos. Así, una trans-codificación es una equivalencia de un objeto en otro lenguaje. Pero, qué es el sonido del dato recibido ¿es versión, es parte, es formato, es una referencia del objeto del cual se recuperan los datos? El sonido trans-codificado de las plantas y los seres humanos es una traducción que posibilita una equivalencia para la creacion de una comunidad de lenguaje donde los seres humanos y no se escuchan y comunican. 

Ahora bien, en este prototipo considero que todos los datos de las plantas son signos en términos de Peirce y que en el sistema de _El lenguaje del Botsque_ pueden llegar a constituirse como signos del tipo íconos, índices o símbolos. Según las definiciones de Peirce (1986 [1897]), los iconos son referencias a un objeto que "son como esa cosa y son usados como signo de ella" ; [Los índices son] un signo que se refiere al Objeto que denota en virtud de ser realmente afectado por aquel Objeto" [y un símblo es] un signo que se refiere al Objeto que denota en virtud de una ley, usualmente una asociación de ideas generales" (p.30). En nuestra tradición cultural buena parte de los iconos de las plantas se asocian a olores o imágenes. En cuanto al sonido este no es protagónico en el mundo vegetal en tanto no son audibles para nosotros o porque no reparamos en el. Si se constituye una comunidad de lenguaje de sonidos de las plantas en tanto emisiones o trasncodificaciones es posible constituir un sistema en el que podamos comprenderlos como íconos de las plantas. Un sonido puede relacionarse con una familia de plantas y por lo tanto ser, como la imagen, una versión sonora de la planta. Como índices, los sonidos se vinculan a la  planta en cuanto reportan una afectación vinculada a su bienestar, sequedad, florecimientos, etc. y como símbolos, es la constitución de la comunidad del lenguage donde las personas y plantas ( no nos olvidemos que las plantas escuchan y aprender) hacen uso del sistema al apropiar unas codificaciones que permiten relacionarse y comunicar sus estados. 

Volviendo a la idea de bienestar y desequilibrio ¿qué es estar bien o no para un ser humano y para una planta? Experiencias como la calma y la ecuanimidad se relacionan con ese bienestar así como, el incremento de hormonas como el cortisol, el exceso de agua o la presencia de hongos puede producir desequilibrios. Pero, ¿qué es estar bien desde las plantas? Si bien funciono como interprete al respecto, parto de una serie de signos sobre todo "índices" que me permiten en relación con las plantas dar cuenta del bienestar o desequilibrio. Una semiótica de la planta revela un estado general de bienestar a través de su color y su entereza. La despigmentación, la falta de fuerza en sus tallo o sus hojas caídas, manchas, comunidades de insectos, etc., manifietan que algo no está en orden. El bienestar según mi relación con ellas también está vinculado al crecimiento de otras plantas amigas cercanas, como tréboles, su florecimiento estacional, el aspecto de la tierra. Así, el bienestar de planta y humanos se establece como dos estados análogos que responden a situaciones contextuales de la planta y mias en las que hay calma y condiciones para la vida. Variables asignadas desde mi concepción personal de bienestar y desde la relación con mis plantas y su bienestar. Las variables de bienestar para mi y las plantas con que habito no son transferibles necesarimente a la relación de otra persona con sus plantas si bine los rangos de muestreo son los mismos. En el sistema se toman datos periodicamente pero para constiruir la comunidad de lenguaje deben calibrarse los datos y estados de tal modo que permitan comprender cómo está la relación de una o unas plantas con las personas con quienes viven 

El sistema cosecha datos a través de arduino y los trans-codifica a través de código que visualiza o sonoriza datos. En virtud de esta trans-codificación se establecen las analogías homeomórficas que se agregan a una base de datos. El bot y la comunidad disponen de todos los datos abiertos. Quien desee purede consultar y visualizar las analogías homeomórficas de la comunidad de al menos dos estados:  bienestar y desequilibrio. El sistema permite la escucha en tiempo real o diferido de la trans-codificación de una planta y la persona amiga y sus analogías.  

**Hardaware y software**

- Arduino 
- Sensor humedad
- Sensor Luz
- Raspberry
- Phyton 
- BD SQL
- Telegram



**Procedimientos**

Descripción del sistema 

Esquema del sistema

Caso de uso 

Escenarios de uso del bot en seudocódigo 

Modelado de datos 

Variables de transcodificación

Desarrollo del bot con phyton

Vínculo al bot en telegram: @Botsque_bot

#### Descripción del sistema

**Principios**

El lenguaje del botsque no impone ontologías para el conocimiento de las plantas. Las entidades a partir de las cuales se estructura la información: persona, planta, lugar, nombre común y nombre científico, solo son entidades para el relacionamiento entre seres humanos y no humanos y conocimientos. Prima la relación de pertenencia y amistad. 

En el lenguaje del botsque se desconoce la minería de datos y en cambio se propone la siembra y cosechamiento de datos y conocimiento. 

La trans-codificación es una estrategia para crear una comunidad de lenguaje entre seres humanos plantas. La asignación de rangos para codificar la escucha y comunicación con las plantas es una decisión individual. El bienestar o desequilibrio en relación con los datos las asignan las personas que se vinculan a la comunidad. 

El lenguaje del botsque reconoce el saber de las plantas y sobre las plantas como bien común de todos los seres humanos y no humanos. No es un saber apropiable de manera privativa y el acceso al mismo se debe hacer de manera respetuosa y ética. 

La relación de los humanos con las plantas se constituye como una puerta para el conocimiento de la vida y otras formas de pensamiento y aprendizaje aún poco exploradas y comprendidas por los modelos de conocimiento occidentales y las lenguas y lenguajes en uso. El lenguaje es entonces una posibilidad para constituir un 



**Usuarios**  

Personas que tienen acceso a la tecnología, personas que viven con plantas, personas que trabajan en el campo, personas que se relacionan con las plantas desde la salud y la medicina, personas que estudian las plantas, personas que siembran en sus casas.

**Característica usuario**

Tienen relaciones o quieren tener relaciones con las plantas con las que conviven en su casa o en su territorio.

**Tipos de usuarios**

Integrado: se conecta a todo el sistema

Explorador: interactúa con la comunidad, siembra datos pero no los cosecha. 

Observador/Escucha: solo escucha o lee. 

#### Esquema del sistema



![](/Users/juanaespinosa/Tesis/001-tesis- git/imagenes/esquema-lenguaje-1.png)

#### Video del sistema



![]()

#### Caso de uso



Ver anexo: [Caso de uso](https://github.com/mjespinosam/botsque-doc/blob/master/04-caso-de-uso.md)  

#### Escenarios de uso en seudocódigo

**Escenario 1 / Conexión**

Inicio

Usuaria **conecta** al sistema la transmisión de datos de la planta y de si misma

Sistema **recopila** datos

El sistema **"trans-codifica"** datos en sonidos

El sistema **transmite** los sonidos

Usuaria y plantas escuchan sonidos. Si hay sonidos rápidos es que hay algun desequilibrio en si misma o en las plantas. 

Usuaria no escucha sonidos. Si los sonidos se dilatan y tienden al silencio es indicador de bienestar. 

Fin

Escenario 2 / Escuchar plantas y personas en vivo 

Inicio

El bot **identifica** que una persona y su amiga planta están transmitiendo

El bot **notifica** en el chat grupal que hay transmisión

El bot **comparte** los datos de la transmisión: lugar, persona, planta

Las personas que desean **escuchan** a la transmisión

Fin

**Escenario 3 / Notificaciones del dí**

Inicio

El sistema **conoce** las plantas amigas de cada persona 

El sistema **identifica** las plantas sobre las que se conversa en el chat durante las últimas 24 horas

El sistema **notifica** a la comunidad en horas de la noche los temas generales de las últimas 24 horas 

Fin 

**Escenario 4 / Notificaciones personalizadas**

Inicio

El sistema **localiza** la planta amiga de cada persona 

El sistema **localiza** otras plantas de interés de una persona

El sistema **identifica** plantas sobre las que se conversa en el chat

El sistema **envía** notificaciones personalizadas, mientras se conversa sobre una planta, a las personas interesadas en ella.

**Escenario 5 / Vincular personas y plantas para la conversación**

Inicio

La usuaria **consulta** sobre una planta 

El sistema **identifica** las personas que son amigas y viven con esas plantas

El sistema **notifica** en el chat grupal a las personas y plantas amigas que hay alguien interesado en conversar sobre esa planta

La usuaria **realiza** preguntas en el chat grupal

Fin

**Escenario 6 / Contemplar plantas y personas**

Inicio

La usuaria  **solicita**escuchar plantas 

El sistema le **da la opción** de escuchar plantas de su misma familia, de otra familia, o aleatoriamente. 

El sistema le **da la opción** de escuchar de manera individual o combinada las plantas elegidas

El sistema **transmite** la elección solicitada

La usuaria **escucha**

Fin

**Escenario 7 / Conocer sobre plantas**

Inicio

La usuaria quiere saber sobre una planta en específico y consulta al sistema

El sistema verifica en el historial de las conversaciones 

El sistema recupera las conversaciones

El sistema entrega las conversaciones

El sistema da la opción de descargar las conversaciones en PDF

Fin

#### Modelado de datos 



![](/Users/juanaespinosa/Tesis/001-tesis- git/imagenes/bd_botsque.png)

#### Variables de transcodificación

Las varibales para la vidualización sonora del  prototipo inicial se crean a partir de las variables: humedad en la planta y respiración en el ser humano. Se establecen dos estados de equivalencia: Desequilibrio y Bienestar. Los rangos pertenecen al estado de una planta que llamo camándula de arvejitas, cuyo nombre científico es Senecio rowleyanus. Los rangos de respiración en seres humanos están basados en la literatura (*Signos vitales*, s. f.). 





|        | **Estado**                      |                   | **Rango** | **Frecuencia** | **Color** | **Sonido eléctrico**       |
| ------ | ------------------------------- | ----------------- | --------- | -------------- | --------- | -------------------------- |
| **1**  | **Seco/Desequilibrio**          | **1023-700 / 50** | 1023-1000 |                | #000000   | Clumk Mid_bip.wav          |
| **2**  | **Seco/Desequilibrio**          |                   | 999-975   |                | #151515   | Buzz 1_bip.wav             |
| **3**  | **Seco/Desequilibrio**          |                   | 974-950   |                | #1C1C1C   | Cosmic Clay 2_bip.wav      |
| **4**  | **Seco/Desequilibrio**          |                   | 949-925   |                | #2E2E2E   | Cosmic Clay 3_bip.wav      |
| **5**  | **Seco/Desequilibrio**          |                   | 899-875   |                | #42424    | Cosmic Clay 4_bip.wav      |
| **6**  | **Seco/Desequilibrio**          |                   | 874-850   |                | #585858   | Cosmic Clay_bip.wav        |
| **7**  | **Seco/Desequilibrio**          |                   | 849-825   |                | #6E6E6E   | Clave Hard_bip.wav         |
| **8**  | **Seco/Desequilibrio**          |                   | 824-799   |                | #848484   | Conga Big_bip.wav          |
| **9**  | **Seco/Desequilibrio**          |                   | 798-775   |                | #A4A4A4   | Floor Tom_bip.wav          |
| **10** | **Seco/Desequilibrio**          |                   | 774-750   |                | #BDBDBD   | High Tom_bip.wav           |
| **11** | **Seco/Desequilibrio**          |                   | 749-725   |                | #D8D8D8   | Kick 1_bip.wav             |
| **12** | **Seco/Desequilibrio**          |                   | 724-700   |                | #E6E6E6   | Kick 2_bip.wav             |
| **13** | **Bienestar**                   | **700-300 /45**   | 699-654   |                | #DBA901   | Mid Tom _bip.wav           |
| **14** | **Bienestar**                   |                   | 653-608   |                | #868A08   | Tabla 1_bip.wav            |
| **15** | **Bienestar**                   |                   | 607-563   |                | #0B4C5F   | Tabla 5_bip.wav            |
| **16** | **Bienestar**                   |                   | 562-518   |                | #610B5E   | Tabla 6_bip.wav            |
| **17** | **Bienestar**                   |                   | 517-472   |                | #DF7401   | Tabla 7_bip.wav            |
| **18** | **Bienestar**                   |                   | 471-426   |                | #380B61   | Tabla 9_bip.wav            |
| **19** | **Bienestar**                   |                   | 425-380   |                | #088A85   | Tabla 10_bip.wav           |
| **20** | **Muy húmedo/Desequilibrio**    | **379-0 /31**     | 379-348   |                | #E6E6E6   | Tabla 11_bip.wav           |
| **21** | **Muy húmedo/Desequilibrio**    |                   | 347-316   |                | #D8D8D8   | Click Buzz_bip.wav         |
| **22** | **Muy húmedo/Desequilibrio**    |                   | 315-284   |                | #BDBDBD   | Alien Zip_bip.wav          |
| **23** | **Muy húmedo/Desequilibrio**    |                   | 283-252   |                | #A4A4A4   | Electronic Tabla a_bip.wav |
| **24** | **Muy húmedo/Desequilibrio**    |                   | 251-220   |                | #848484   | Glong_bip.wav              |
| **25** | **Muy húmedo /Desequilibrio**** |                   | 219-188   |                | #6E6E6E   | Mall Drum_bip.wav          |
| **26** | **Muy húmedo/Desequilibrio****  |                   | 187-156   |                | #585858   | Tabla 2_bip.wav            |
| **27** | **Muy húmedo/Desequilibrio****  |                   | 155-124   |                | #42424    | Tabla 3_bip.wav            |
| **28** | **Muy húmedo/Desequilibrio****  |                   | 123-92    |                | #2E2E2E   | Tabla 4_bip.wav            |
| **29** | **Muy húmedo/Desequilibrio****  |                   | 91-60     |                | #1C1C1C   | Tabla 8_bip.wav            |
| **30** | **Muy húmedo/Desequilibrio****  |                   | 59-28     |                | #151515   | Wood Block_bip.wav         |
| **31** | **Muy húmedo/Desequilibrio****  |                   | 28-0      |                | #000000   | Woodblock 2_bip.wav        |





| **Frecuencia de respiración** | **Numero de respiraciones por minuto** | **Sonido**                 | **Frecuencia sonido** |
| ----------------------------- | :------------------------------------- | -------------------------- | --------------------- |
| **Calma extrema/ Bienestar**  | 1                                      | Mid Tom _bip.wav           | 1 x min               |
| **Calma extrema/ Bienestar**  | 2                                      | Tabla 1_bip.wav            | 2 x min               |
| **Calma extrema/ Bienestar**  | 3                                      | Tabla 5_bip.wav            | 3 x min               |
| **Calma extrema/ Bienestar**  | 4                                      | Tabla 6_bip.wav            | 4 x min               |
| **Calma extrema/ Bienestar**  | 5                                      | Tabla 7_bip.wav            | 5 x min               |
| **Calma extrema/ Bienestar**  | 6                                      | Tabla 9_bip.wav            | 6 x min               |
| **Calma extrema/ Bienestar**  | 7                                      | Tabla 10_bip.wav           | 7 x min               |
| **Calma extrema/ Bienestar**  | 8                                      | Mid Tom _bip.wav           | 8 x min               |
| **Calma extrema/ Bienestar**  | 9                                      | Tabla 1_bip.wav            | 9 x min               |
| **Calma extrema/ Bienestar**  | 10                                     | Tabla 5_bip.wav            | 10 x min              |
| **Calma extrema/ Bienestar**  | 11                                     | Tabla 6_bip.wav            | 11 x min              |
| **Normal/Bienestar**          | 12                                     | Tabla 7_bip.wav            | 12 x min              |
| **Normal/Bienestar**          | 13                                     | Tabla 9_bip.wav            | 13 x min              |
| **Normal/Bienestar**          | 14                                     | Tabla 10_bip.wav           | 14 x min              |
| **Normal/Bienestar**          | 15                                     | Mid Tom _bip.wav           | 15 x min              |
| **Agitación/Desequilibrio**   | 16                                     | Tabla 1_bip.wav            | 16 x min              |
| **Agitación/Desequilibrio**   | 17                                     | Tabla 5_bip.wav            | 17 x min              |
| **Agitación/Desequilibrio**   | 18                                     | Tabla 6_bip.wav            | 18 x min              |
| **Agitación/Desequilibrio**   | 19                                     | Tabla 11_bip.wav           | 19 x min              |
| **Agitación/Desequilibrio**   | 20                                     | Click Buzz_bip.wav         | 20 x min              |
| **Agitación/Desequilibrio**   | 21                                     | Alien Zip_bip.wav          | 21 x min              |
| **Agitación/Desequilibrio**   | 22                                     | Electronic Tabla a_bip.wav | 22 x min              |
| **Agitación/Desequilibrio**   | 23                                     | Glong_bip.wav              | 23 x min              |
| **Agitación/Desequilibrio**   | 24                                     | Mall Drum_bip.wav          | 24x min               |

#### Desarrollo del bot con phyton

Vínculo al bot en telegram: @Botsque_bot

Ver documentación del Bot en el repositorio [Botsque_bot]()

## III. Plantar el problema : saberes adventicios

## IV. Conclusiones

Al menos son dos los propósitos de las humanidades digitales: 1) implementar y desarrollar herramientas digitales para la investigación y transferencia de conocimiento de las disciplinas y 2) dialogar con las herramientas para dar discusiones conceptuales y teóricas.[^1]. La primera perspectiva se desarrolla a partir de conocimientos de las ciencias de la información, bibliotecología, archivística, ingenierías de sistemas, informática, electrónica, desarrollo de software, etc. Estas disciplinas disponen de metodologías que permiten a los humanistas organizar corpus de datos, hacer análisis de los mismos, visualizarlos, crear y gestionar colecciones o desarrollar software específico para analizar, comprender o resolver sus problemas particulares. A este modelo de implementación o desarrollo de herramientas desde perspectivas y necesidades humanistas se suma la posibilidad de hacer investigación sobre el diálogo entre los diversos campos de las humanidades y las tecnologías o herramientas digitales[^2]. Aunque una perspectiva no excluye a la otra, es claro que la primera busca implementar o validar un prototipo para resolver un problema. La segunda perspectiva por su parte, busca mediante la implementación y el prototipado experimentar para dar cuenta de las tensiones y posibilidades entre herramientas y conocimientos disciplinares [^3].

En este sentido, esta tesis explora la segunda perspectiva, al discutir cómo la implementación de herramientas colaborativas, en particular una wiki semántica etnobotánica (relaciones seres humanos-plantas) [^4] , me permitió reconocer en el prototipo un dispositivo experimental para pensar tanto el problema de las herramientas colaborativas, como las relaciones seres humanos-plantas. Es decir, las tensiones y diálogos entre herramientas digitales y conocimiento etnobotánico. Durante la investigación el prototipado de las herramientas, en sus diferentes fases e iteraciones, pasaron de metodologías de diseño participativo o centrado en usuarios a una metodología de diseño centrado en conceptos problema. De ahí que en el proceso emergieron todos los actores humanos y no humanos involucrados en dar cuenta de las relaciones plantas-seres humanos. A esta altura de la experimentación se refinó el problema, se precisaron los actores involucrados y emergió la pregunta de qué condiciones son necesarias para que las herramientas colaborativas se configuren como un espacio en el que humanos y no humanos -en este caso plantas- se integren como actores del conocimiento colaborativo. Esta pregunta, que parte del reconocimiento de las plantas como partícipes en la construcción de conocimiento sobre ellas mismas y cuya relación con los seres humanos puede modelarse mediante herramientas digitales colaborativas, solo fue posible una vez recorrí la perspectiva de implementación de herramientas colaborativas para una necesidad de una comunidad y me encontré con una perspectiva crítica del diseño, que replanteó los dos elementos transversales a la tesis: las plantas, el software colaborativo e introdujo -sin saberlo- la experiencia como eje articulador. 

Así, _El Lenguaje del Botsque_ me permite pensar las relaciones plantas-seres humanos de manera especultaiva para indagar las maneras como podemos construir lenguajes de escucha para pensar como ellas y pensar sobre ellas. La recopilación de datos en este sistema busca superar la noción de extracción de datos, cosecha de datos, para dar cuenta de la siembra de datos. Un acto colaborativo para el aprendizaje interespecies en el que el ser humano también entrega a las plantas información sobre su estado y recibe información suceptible de ser trans-codificada. Lo que puede llegar a ser un corpus de data abierta para la compresión de las relaciones con las plantas se configura, además, como materia de exploración que puede trans-codificarse en imagen, acción, objeto, cuerpo. Este lenguaje también me permite orientar un proceso de indagación acerca de la hermeneútica interespecie y un diseño centrado en el ecosistema. Cuestiones que reparan en cómo ir más allá de las teorías críticas sobre el antropocentrismo a la construcción de escenarios que vinculen el ser, el cosmos y lo inefable. Esta línea de investigación dialoga directamente con el pensamiento de Pannikar y con las epistemologías del sur en especial con las propuestas de las hermeneúticas diatópicas. 

Por otra parte, esta tesis  reconoce el diseño como referente disciplinar que aporta metodológicamente a la investigación en las Humanidades Digitales. Tanto en la definición de la investigación como diseño y por lo tanto como proceso que vincula la experiencia, la interación y la validación, como el diseño en la investigación. Es decir, las metodologías centradas en el usuario o en los conceptos, como rutas para vincular las prácticas con los presupuestos epistémicos. En particular el diseño participativo de Ramesh Srinivasan basado en la etnometodología y el diseño especulativo propuesto por Raby y Dune que expande el diseño a esferas conceptuales, introducen la reflexivadad respecto a los presupuestos e implicaciones de las tecnologías en la cultura así como el lugar de quien diseña, investiga en relación con los otros, con los problemas. Hacer transparente los presupuestos propios, así como los presupuestos del diseño del software, el hardware permite abordar crítica y éticamente el rol de los humanistas digitales en sus vinculaciones con las comunidades usuarias. Sobre todo cuando la creación de las tecnologías desvirtúa la pluralidad de epistemologías y se impone desde criterios universalistas. ¿Es posible pensar tecnologías incluyentes de otras perspectivas epistemológicas que integren por ejemplo lo no humano? Ese fue el objetivo final de esta investigación y es a todas luces el camino que apenas empieza.  

[^1]: Las relaciones entre tecnologías digitales y humanidades han trasegado desde la computación humanista, la informática comunitaria, la informática educativa y las humanidades digitales. Si bien en ninguna de estos campos existen definiciones disciplinares con programas teóricos y metodológicos claros, todas emergen dentro de la cultura digital o cibercultura. Los abordajes para su definición presentan un campo múltiple de aproximaciones en las que prima lo heterogéneo, interdisciplinario. Ver: del Rio Riande, M. G., & González Garcí Blanco, B. (2015). Introducción a las Humanidades Digitales. Material Didáctico Sistematizado. 103. https://www.aacademica.org/gimena.delrio.riande/115 Cuartas-Restrepo, J. M. (2017). Humanidades digitales, dejarlas ser. Revista Colombiana de Educación, 72(1), 65-78. https://doi.org/10.17227/01203916.72rce65.78 Galina Russell, I. (s. f.). ¿Qué son las humanidades digitales? 1 Julio de 2012, 12(7). Recuperado 4 de diciembre de 2016, de http://132.248.9.34/hevila/Revistadigitaluniversitaria/2011/vol12/no7/5.pdf Rueda Ortiz, R. (Ed.). (2013). Ciberciudadanías, cultura política y creatividad social (Primera edición). Universidad Pedagógica Nacional. 

[^2]: Los estudios de las tecnologías tiene por objeto de estudio la tecnología y si bien da cuenta de las relaciones de los actores humanos y no humanos su objetivo no es pensar el problema mismo desde el uso o experimentación con la tecnología. Esta manera de investigar por medio del hacer con una tecnología está más cerca de las metodologías del diseño. 
[^3]: Como elaboraré en la metodología esta perspectiva coincide con lo que los diseñadores han llamado "Investigación como diseño" (Simon, 2015).



## Referencias







 

