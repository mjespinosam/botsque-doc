
# Protocolo de prototipos

Omeka

La documentación de los prototipos está basado en los sistemas de resolución de problemas de pensamiento lateral y el heurístico. 


### Definir el problema

La construcción de una herramienta colaborativa del conocimiento plantas seres humanos een una wiki tiene al menos tres retos

1. Defenir la planta como entidad en una Bases de Datos

2. Determinar sus atributos

3. Establecer las realciones de uno a muchos y de muchos a muchos. 

Como software de prueba para crear la entidad y sus relaciones se opta por OMEKA. Este software aparece como una infraestructura que permite empezar a dar cuenta de cuáles son los atributos y las relaciones de la planta. <Sin embargo hay otra serie de relaciones que son de muchos a muchos. Las relaciones de muchos a muchos no son fácilmente recupeables en software como la Media Wiki. De qué manera se debe modelar las relaciones de muchos a muchos. 

Los prototipos 

Las pruebas empezaron con sistemas de relaciones entre metadatos, esa información que describe un objeto digital bajo aspectos comunes y generales a todos los de su mismo tipo. De base, ese software, permite activar el Dublin Core Extended, un estandarización de metadatos que permite construir colecciones estructuradas para que la máquina recupere mejor la información, intercambie con otras plataformas y en resumidas haga de la web una sola cosa, interdependiente. Los item relations, la red posible de relaciones entre items que son fragmentos, derivados o parte de un mismo objeto, me permitían decir que **amaranto** is version of/ is part of/ _Amaranthus hibridus_ . Así era posible vincular uno y todos los nombres comunes con ese identificador único de una planta. La plataforma lo podría hacer no sin un trabajo desmedido. Tocaba para cada nombre común hacer una entrada única y vincularla a esa planta "maestra". El trabajo no era colaborativo. Una tarea que además ya había adelantado la Universidad Nacional con su paltaforma de [Nombres comunes de plantas de Colombia] (http://www.biovirtual.unal.edu.co/nombrescomunes/es/). Si ya existía, abría que buscar interoperabilidad. Pero más allá de que existiera el "nombre científico" asignado al metadato "título" ¿era este metadato de la planta, su identificador?. Por más que vinculara nombres comunes a un nombre científico ¿Cuál era la autoridad para decir que ese nombre es la planta? Esta es entonces la historia del trasegar de la reflexión  materializacion de la representación digital de las plantas y sus relaciones con los seres humanos. De cómo las plantas entraron a esta tesis vistas como objetos y se volcaron a ser sujetos, actantes que están en relación con los seres humanos para dar cuenta de sus beneficios, preferencias y dinámicas. Recorramos el diagrama



**Prototipos**



Empecemos por su identidad. Toda planta al construirse como una entidad en una base de datos debe ser identificada de manera única (llave primaria) para poder establecer relaciones con otras entidades (Lugar, usos, etc). Principio universal de las Bases de Datos: cada entidad debe tener una llave única. Pero ¿cuál era ese identificador único de una planta? El nombre, pensé. El nombre científico. Aún así, conozco muchas plantas de los jardines que he habitado y de ninguna se su nombre si bien se que a unas llegan abejas, a otras mosquitos blancos, que otras nunca florecen en el encierro y que las ventanas es el lugar preferidas de esas otras que mi amiga llama Anturios. Pero además, sabía en ese entonces que existían cientos de nombres comunes para referierse a una planta ¿Qué había de la alegría, el amaranto, los quelites en ese _Amaranthus hybridus_? El desarrollador nuevamente me miró con sospecha. Estaba la pantalla y el cuaderno garabateado: Ese amaranto del que hablo tiene muchas maneras de ser nombrado -Camilo- y, cómo hacer para que todas esas maneras ¿sean la misma planta, de semillas milagrosas y penachos fuccias, un poco rastreras, salvajes y malezas ellas? La identidad de la planta tiene un código de identificación: el o los nombres científicos. Pero esta es una asignación que se establece desde la biologia. ¿Podría existir una llave primaria más cercana a la planta como planta? ¿Su imagen? 


### Resultado que espera obtener

### Información disposnible

¿Qué información es relevante? ¿Cuál no?
¿Qué información es importante?
¿Qué conozco del problema?

### Restricciones 



### Procesos necesarios para convertir los datos disponible en la inforamción requerida

### Resultados

### Esquemas


### Discusión. Problemas o ideas emergentes


