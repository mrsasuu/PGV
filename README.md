**GAME DEFINITION DOCUMENT**

**Responsable de grupo:** Gregorio Carvajal Expósito

Antonio Javier Benítez Guijarro

Emilio Chica Jiménez

Hugo Maldonado Cózar

Jose Antonio Martinez Lopez

Javier Labrat Rodriguez

[]{#_fj8m9o6a9moh .anchor}*ÍNDICE*

DEFINICIÓN GENERAL DEL JUEGO
============================

OBJETIVO
--------

El objetivo principal de cada nivel es **defender** nuestra base de los
enemigos colocando torretas defensivas y conseguir sobrevivir a las
hordas.

Como objetivo secundario tenemos que conseguir todos los **logros**
(explicado más abajo) de cada nivel.

ESCENARIO
---------

-   Un mapa donde se muestran los distintos niveles. Sólo se muestra por
    > el que vamos y los anteriores (en caso de que haya)

<!-- -->

-   Un “tablero” con varios caminos hasta la base. Un entorno con
    > vegetación alrededor de los mismos que no será accesible,
    > simplemente por decoración.

-   Las torretas solo se pueden colocar en determinadas zonas. Dichas
    > zonas tienen un aspecto diferente al resto del suelo.

-   Los extractores de recursos solo se pueden colocar en las zonas en
    > las que hallan minas de recursos, que serán claramente
    > identificables en el nivel (parecen piedras azules que brillan)

ASPECTOS DEL JUEGO
------------------

-   Si el juego pasa a segundo plano se pausa automáticamente (si la
    > opción del HUD está seleccionada).

-   Cuando se completa un nivel, se guarda la partida.

-   Si adelantamos el comienzo de la siguiente oleada haciendo clic en
    > el botón de siguiente oleada, ganaremos más o menos recursos en
    > función del tiempo restante. Concretamente, ganaremos el doble de
    > recursos que el tiempo restante.

TIPOS DE TORRETAS
-----------------

-   Base (no posee acciones adicionales ni es posible colocarla/aparece
    > prefijada en el “tablero”).

<!-- -->

-   Torreta de disparo rápido - “Rapid-fire minigun”

-   Torreta de disparo fuerte (pero lento) - “Heavy Weapon”

-   Torreta de extracción de recursos - “Energy Unit”

-   Torreta lanzacohetes (daño alto, lento y en área)

TIPOS DE ACCIONES CON LAS TORRETAS
----------------------------------

-   Reparar (se necesita tiempo para realizar la reparación, durante
    > esta, la torreta no podrá atacar)

-   Vender (se recupera una parte del coste)

-   Mejorar (hasta 2 veces)

-   Escudo (dura un tiempo limitado)

ASPECTOS DE LAS TORRETAS
------------------------

-   Mientras se repara una torreta, no dispara a los enemigos

-   Las torretas no pueden disparar a traves de obstaculos ni de otras
    > torretas. Deberán hacer un disparo parabólico para ello

TIPOS DE ENEMIGOS
-----------------

-   Tipo 1: Rapido y poco ataque. Defensa baja. Matarlo proporciona 2 de
    > recursos.

-   Tipo 2: Lento y mucho ataque. Defensa alta. Matarlo proporciona 4 de
    > recursos.

-   Tipo 3: Lento, ataque eléctrico que inutiliza la torreta atacada.
    > Defensa alta. Matarlo proporciona 10 de recursos.

ASPECTO DE LOS ENEMIGOS
-----------------------

-   “Arañas” minúsculas azules (tipo 1)

-   “Arañas” negras (tipo 1)

-   “Cucarachas” pequeñas verdes (tipo 1)

-   “Bichos” grandes marrones (tipo 2)

-   Escorpiones grandes (tipo 2)

-   Bichos que paralizan torretas (tipo 3)

OBJETOS
-------

Los objetos nos ayudan en la batalla, pero no siempre estarán
disponibles. Al principio de cada nivel, estarán desactivados. Tendremos
que esperar un tiempo para poder usarlos y cada vez que los usemos,
tendremos que volver a esperar.

-   Bomba que destruye un radio de enemigos. Se selecciona con el ratón
    > el área donde se quiere lanzar la bomba. Tiempo de espera: 1:30
    > minutos (no aparece el tiempo restante como tal, en cambio, se
    > “aclara” el color del botón del objeto en el HUD en ascenso). -
    > “Air Support”

-   Bomba nuclear: Igual que la bomba anterior pero con más daño y un
    > rango mayor. El tiempo de espera es de 5:00 minutos

DIFICULTAD
----------

Para cada nivel, existen 3 modos de dificultad. La diferencia entre
ellos es la defensa de las torretas y la defensa de los enemigos.

-   Fácil - Torretas con mucha defensa, enemigos con poca defensa

-   Normal - Torretas con mucha defensa, enemigos con mucha también

-   Ultimate (bloqueado inicialmente; se desbloquea al conseguir los 3
    > logros normales del nivel) - Torretas con poca defensa, enemigos
    > con mucha defensa

LOGROS
------

En cada nivel podemos obtener hasta 3 logros diferentes.

-   Completar un nivel

-   Si los enemigos no destruyen más de 3 torretas

-   La base no sufre ningún daño

-   ESPECIAL: Completar el nivel en dificultad Ultimate

MEJORAS
-------

Las mejoras se compran con puntos de experiencia. Al conseguir un logro,
obtendremos 10XP. Si perdemos y nos destruyen nuestra base también
ganaremos algo de XP en función de las oleadas completadas.

Cada mejora se puede mejorar hasta 3 veces y cada una de esas mejoras
costará 20XP, 25XP y 30XP respectivamente.

-   Aumento del radio de ataque de las torretas

-   Aumento de la velocidad de reparación de las torretas

-   Defensa de las torretas

-   Cantidad de recursos obtenidos al vender una torreta colocada

-   Reducción en el tiempo de recarga de los objetos

-   Daño producido por los objetos

**POSICIONAMIENTO DE LOS ELEMENTOS EN EL “TABLERO”:** Existen espacios
hexagonales predefinidos en cada nivel del juego para poder posicionar
las distintas torretas de tipo disparo. También es posible colocar
*torretas de extracción de recursos* en los espacios hexagonales que
recubren *pozos de recursos* (“terreno azul”); dichas torretas ocupan
tres espacios hexagonales consecutivos. Todos estos espacios permanecen
invisibles hasta que se selecciona una torreta, momento en el que se
hacen visibles en función del tipo de torreta seleccionado en el HUD.

DEFINICIÓN DEL HUD
==================

En general cuando se sitúa el ratón sobre un botón hay una animación
sobre el botón, o el propio botón cambia de color a amarillo anaranjado.

-   **Precarga**

![](media/image33.png){width="2.6357305336832897in"
height="2.026042213473316in"}

Lo primero que hace el juego es mostrar una barra de carga.

![](media/image44.png){width="2.4089435695538057in"
height="1.859375546806649in"}

Después pregunta si se quiere sonido o no.

-   **Presentación inicial**

![](media/image42.png){width="2.585330271216098in"
height="1.9635422134733158in"}

> La presentación inicial del juego muestra dos pantallas de precarga
> que anuncian a los creadores del juego.

-   **Pantalla de inicio**

![](media/image41.png){width="3.9895833333333335in"
height="2.9895833333333335in"}

> La pantalla inicio del juego muestra un fondo animado, la animación
> consiste en una transición de brillo de las letras del título del
> juego y se muestra sobre este fondo varias opciones a elegir en forma
> de botones los cuales son:

-   **Play**: Esta opción muestra un nuevo menú **Slots** que se
    > superpone sobre el anterior y que superpone una sombra sobre de la
    > **Pantalla de inicio.**

-   **Options:** Muestra un menú que tiene elementos seleccionables:
    > Auto Pause, Sound y Music, es decir, permite activar estas
    > opciones o cerrar el menú.

-   **More Games:** Un enlace a una página web.

-   **Credits:** Muestra un menú que muestra la información del grupo de
    > creadores del juego y su logo y un botón para cerrarlo.

<!-- -->

-   **Slots**

![](media/image43.png){width="1.6666666666666667in"
height="2.4270833333333335in"}

> Este menú nos proporciona varias opciones: Si hemos jugado previamente
> y está guardada nuestra partida en las cookies del navegador nos
> permitirá *cargar* *la partida* desde el nivel por el que estábamos
> jugando, si no hemos jugado previamente nos da la opción de crear una
> **nueva partida** en tres Slots distintos. Por último tenemos un botón
> de salir que nos devuelve a la **Pantalla de inicio**.

-   **Nueva partida:** Comienza con una pantalla con el fondo con una
    > imagen y superponiendo texto de una historia que va contando
    > animando dicho texto. La animación consiste en que el texto va
    > apareciendo progresivamente en un tiempo determinado. En esta
    > pantalla muestra un botón de siguiente para continuar con el menú
    > **selector de niveles**.

-   **Cargar la partida:** El botón de cargar te muestra en el propio
    > botón, el nivel que tienes, los logros conseguidos hasta el
    > momento en esa partida que vas a cargar y los logros en modo
    > ultimate y un botón para eliminar la partida, que muestra en el
    > propio botón una pregunta de confirmación para eliminar la partida
    > o no. Cuando pulsamos dicho botón te lleva al menú **selector de
    > niveles**.

<!-- -->

-   **Selector de niveles (Mapa del juego)**

![](media/image15.png){width="3.3261876640419947in"
height="2.4843755468066493in"}

> Se muestra una imagen de fondo con un mapa de un terreno en 2D, sobre
> esta imagen se sitúa una malla en azul de hexágonos. Sobre esta malla
> se resalta una zona en **naranja** la cual tiene una animación de una
> diana que apunta al lugar donde se supone que se va a centrar el lugar
> del primer nivel. Esta malla reacciona con una animación cuando se
> sitúa el ratón encima de dicha zona y es clickable para poder acceder
> a dicha zona del mapa o nivel del juego. Si hemos ganado logros se
> muestran en la zona **anaranjada** del nivel, si hemos ganado el logro
> ultimate sólo se muestra dicho logro. Cuando se hace click sobre la
> zona **anaranjada** nos muestra el menú de **descripción del nivel**.
> Sobre el mapa se muestra en la parte superior la experiencia actual, y
> los logros normales y ultimate. Además se muestran tres botones uno
> que es **Main menu**, otro que es **More games** y por último uno que
> es **Research**. Main menu te devuelve a la **Pantalla de inicio,**
> **More games** es una enlace a una página web y **Research** muestra
> otro menú que tiene por cada tipo de mejora posible (Shooting radius,
> Speed of repair, Weapons armoring, Refund for selling weapons,Support
> recharge time, Support power) una serie de botones que serán
> desbloqueados dependiendo de la cantidad de experiencia que tengas y
> que puedas comprar. Si están bloqueados el botón se muestra con un
> fondo negro y letras blancas y si están desbloqueados se muestra en
> azul, si ha sido comprado se muestra sobre dicho botón el nivel en el
> que está dicha mejora. Para aceptar los posibles cambios en mejoras se
> tiene un botón de DONE que las hace efectivas, sino un botón de CANCEL
> para descartar los cambios.

-   **Descripción del nivel(Misión)**

![](media/image26.png){width="2.871350612423447in"
height="1.6666666666666667in"}

> Muestra una imagen del nivel completo, los posibles logros que hayas
> ganado en ese nivel tanto ultimate, como normal. El nombre de la
> misión en la parte superior, un botón de cerrar que vuelve al selector
> de nivel en la parte superior derecha. A la derecha de la imagen
> muestra un selector de dificultad el cual sólo tiene habilitados el
> nivel fácil y normal, el modo ultimate sólo se desbloquea cuando has
> obtenido los tres logros normales.

-   **Pantalla de juego**

![](media/image04.png){width="3.7224004811898515in"
height="2.8349398512685915in"}

> Comienza mostrando un pequeño **tip** avisando de que hay enemigos que
> se acercan a tu base, dicho tip es un pequeño cuadro de diálogo que
> sólo permite cerrarlo con un botón OK. Estos **tip** irá apareciendo
> conforme tengas que evolucionar en el juego, es decir, cuando tengas
> algo nuevo disponible que desbloquear o necesites instrucciones para
> realizar alguna acción.

![](media/image29.png){width="1.8661417322834646in"
height="1.7708333333333333in"}

> También se muestran **bocadillos** explicativos para cualquier acción
> que tengas que realizar sobre un botón si se posiciona el cursor
> encima de dicho botón.

![](media/image16.png){width="1.1145833333333333in"
height="0.8854166666666666in"}

Los **elementos del HUD**, empezando de izquierda a derecha y de arriba
a abajo, son los siguientes:

1.  **Esquina superior izquierda:** muestra los indicadores de estado
    > del juego, es decir, muestra la cantidad de recursos de los que
    > dispones actualmente y las oleadas que quedan por eliminar, se
    > muestra con un icono y un valor numérico.Justo debajo se muestra
    > el nombre de la empresa.

![](media/image21.png){width="1.1473917322834646in" height="0.375in"}

1.  **Esquina superior derecha:** muestra tres botones, el primero un
    > botón de avance rápido que te permite aumentar la velocidad del
    > juego, el segundo botón es un **pause** para pausar la partida y
    > el tercer botón es un botón de menú que te muestra el **menú de
    > juego**.

![](media/image36.png){width="0.53125in" height="0.20833333333333334in"}

1.  **Esquina inferior izquierda:** muestra los **botones de
    > construcción** de los cuales tres de ellos están bloqueados al
    > principio hasta que no avanzas en el juego y puedas construir ese
    > tipo de torre.

![](media/image23.png){width="1.4182250656167978in"
height="0.3541666666666667in"}

1.  **Esquina inferior derecha:** muestra los **botones de habilidades**
    > que al principio están bloqueadas hasta que avanzas en el juego.

![](media/image19.png){width="0.65625in" height="0.3854166666666667in"}

**Botones de construcción:**

1.  Torres con minigun

2.  Torres con heavy weapon

3.  Torres lanzacohetes

4.  Energy unit

> Si pulsamos cualquiera de ellos nos aparece en el mapa una silueta de
> la torre seleccionada que nos permite colocar dicha torre en los
> sitios permitidos que se mostrarán en el mapa con un hexágono señalado
> en azul y también nos mostrará esa silueta de la torre en rojo si no
> se puede colocar y en verde si se puede colocar y un círculo azul
> indicando el alcance dicha unidad.

**Botones de habilidades**

1.  **Ataque aéreo**: Muestra en el mapa un círculo que representa el
    > rango del ataque y donde quieres situarlo.

2.  **Ataque nuclear**: Igual que el anterior pero con un radio más
    > grande.

> **Botón para comenzar con la horda**

![](media/image30.png){width="0.5in" height="0.34375in"}
![](media/image25.png){width="0.3817661854768154in"
height="0.4270833333333333in"}

> Una vez hayas situado todo en el campo mediante las acciones que
> puedes hacer sobre los distintos menús, ya sea construyendo torretas o
> usando habilidades, aparece en el lugar de donde vaya a provenir la
> horda un **botón para comenzar con la horda**.Si nos situamos sobre
> dicho botón nos aparece un pequeño bocadillo con información sobre la
> horda, el tipo de enemigos con su icono y su número, y también cambia
> el texto del botón a NOW, en lugar de GO. Además dicho botón cuando
> terminas con una horda aparecerá de nuevo con un contador de tiempo
> estableciendo el tiempo que te queda para que la siguiente horda
> aparezca, puedes pulsar dicho botón sin que el tiempo se haya acabado
> y este desaparecerá y empezará la horda que te gratificará con
> recursos dependiendo del tiempo y se mostrará en la posición en la que
> estaba el botón que pulsaste un icono con el número de recursos
> ganados que desaparecerá al poco tiempo.
>
> **Barra de vida:** En el mapa también se muestra sobre nuestras torres
> y sobre los enemigos una **barra de vida** que nos indica cuanta vida
> le queda a la torre o enemigo.
>
> ![](media/image01.png){width="1.2447922134733158in"
> height="1.016580271216098in"}
> ![](media/image28.png){width="1.0677088801399826in"
> height="0.9553182414698163in"}
>
> **Menú de las torretas**

![](media/image39.png){width="1.9479166666666667in"
height="1.9166666666666667in"}

> Este menú sólo se activa cuando hacemos clic sobre una torreta y
> muestra el rango del alcance de esa torreta en el mapa y un menú de
> cuatro opciones en el HUD:

1.  **Reparar la torre**: Muestra el precio de repararla en recursos

2.  **Vender la torre**: Muestra el precio de venderla en recursos

3.  **Mejorar la torre**: Muestra el precio de mejorar el nivel de la
    > torre

4.  **Escudo**: Muestra el precio de colocar un escudo en la torre

> **Fin de partida**: Muestra un cuadro de diálogo el resultado que has
> obtenido, si es victoria o derrota, con una animación sobre el texto
> la misma que para el texto de la pantalla de inicio. Tiene cuatro
> ítems:

1.  **Logro Area Cleaned**: Con un texto que explica en qué consiste el
    > logro y con un icono de estrella si lo has conseguido o una
    > estrella vacía en el caso de que no.

2.  **Logro Weapon Stamina**: Lo mismo que el anterior.

3.  **Logro Invencible base**: Lo mismo que el anterior.

4.  Experiencia ganada que muestra en un cuadro la cantidad de
    > experiencia ganada.

5.  **Continue** que te lleva al menú de Selector de niveles (Mapa del
    > juego).

6.  **Restart** que reinicia el
    > nivel.![](media/image45.png){width="2.996350612423447in"
    > height="3.416220472440945in"}![](media/image34.png){width="2.4964741907261594in"
    > height="3.526042213473316in"}

DEFINICIÓN DE BICHOS
====================

Todos los bichos
----------------

**Atributos**

-   **ID:** Atributo estático. Valor numérico discreto que identifica el
    > tipo de bicho que es.

<!-- -->

-   **Vida:** Atributo estático. Valor numérico continuo de 0 a 100.
    > Decrece conforme recibe ataques.

-   **Tipo de ataque:** Atributo estático. valor numérico discreto.
    > Especifica distintos tipos de ataque que pueden ser “pegando”,
    > “disparando” o en ángulo a un área específica (que puede atacar
    > más de una torre a la vez) **OPTATIVO** SEGÚN EL TIEMPO QUE
    > TENGAMOS.

-   **Fuerza de ataque:** Atributo estático. Valor numérico discreto de
    > 0 a 100. Indica el daño que hará a las torres.

-   **Alcance de ataque:** Atributo estático. Valor numérico discreto
    > que indica el radio de la circunferencia en la que el bicho podrá
    > atacar. **OPTATIVO** SEGÚN TIPO DE ATAQUE

-   **Frecuencia de ataque:** Atributo estático. Valor numérico discreto
    > de 0 a 100. Indica el tiempo que pasa entre dos ataques
    > consecutivos.

-   **Velocidad movimiento:** Atributo estático. Valor numérico discreto
    > de 0 a 100. Especifica la distancia que recorre por unidad de
    > tiempo.

-   **Posición:** Atributo dinámico. Coordenadas x,z,y discretos que
    > indiquen la posición del bicho en el mapa.

-   **Esfera englobante:** Atributo estático. Esfera de radio mínimo que
    > engloba a todo el bicho.

-   **Recompensa de muerte:** Atributo estático. Recompensa de recursos
    > por matar al bicho.

**Estados**

-   **En espera** -&gt; Esperando al evento de salida de la horda.

<!-- -->

-   **En movimiento** -&gt; siguiendo la trayectoria hacia la base.

-   **Colisión con otro bicho** -&gt; modificación de trayectoria

-   **Llegada a alguna torre** -&gt; atacar torre

-   **Llegada a base** -&gt; atacar base

-   **Muerto** -&gt; Se queda sin vida -&gt; desaparece del juego

Bicho bajo
----------

-   **ID** -&gt; 1

-   **Vida** -&gt; 20

-   **Fuerza de ataque** -&gt; 10

-   **Frecuencia de ataque** -&gt; 10

-   **Velocidad movimiento** -&gt; 50

-   **Recompensa de muerte:** -&gt; 2

Bicho medio
-----------

-   **ID** -&gt; 2

-   **Vida** -&gt;40

-   **Fuerza de ataque** -&gt; 20

-   **Frecuencia de ataque** -&gt; 30

-   **Velocidad movimiento** -&gt;50

-   **Recompensa de muerte:** -&gt; 4

Bicho alto
----------

-   **ID** -&gt; 3

-   **Vida** -&gt;70

-   **Fuerza de ataque** -&gt; 40

-   **Frecuencia de ataque** -&gt; 50

-   **Velocidad movimiento** -&gt; 50

-   **Recompensa de muerte:** -&gt; 8

Super Bicho
-----------

-   **ID** -&gt; 4

-   **Vida** -&gt; 100

-   **Fuerza de ataque** -&gt; 60

-   **Frecuencia de ataque** -&gt; 50

-   **Velocidad movimiento** -&gt; 50

-   **Recompensa de muerte:** -&gt; 16

Diagrama de estados
-------------------

![](media/image37.png){width="6.267716535433071in"
height="2.6944444444444446in"}

[]{#_2ez94s1px2lu .anchor}

DEFINICIÓN DE TORRES
====================

Todos las torres
----------------

***Atributos***

-   **Vida**: Atributo dinámico cantidad de 0 a 100, decrece cuando
    > recibe ataques.(Aumenta con el nivel de la torreta con un factor
    > de 1.2 por nivel\*).

-   **Precio**: Atributo estático. El precio de la mejora dependerá del
    > precio base de la torreta + un incremento del nivel de la mejora.

-   **Precio de venta**: Atributo dinámico. Aumenta con el nivel de
    > mejora. Disminuye en función de la vida restante.

-   **Incremento del precio por nivel:** Atributo estático. Incremento
    > en el precio de cada mejora.

-   **Nivel**:Atributo dinámico. Indica cuantas mejoras se han aplicado
    > a la torre. Valores={1,2,3}.

-   **ID**: Atributo estático. Indica el tipo de torreta

-   **Posición**: Atributo estático. Coordenadas x, y, z discretos que
    > indiquen la posición de la torreta en el mapa.

-   **Escudo**: Objeto escudo asociado.

-   **Caja Englobante** -&gt; Cubo de tamaño mínimo que engloba a la
    > torre.

***Estados** *

-   **En espera** -&gt; Esperando al evento de salida de la horda.

-   **En reparación** -&gt; Reparando los daños producidos.

-   **Atacado** -&gt; Recibiendo daños de los bichos

<!-- -->

-   **Destruida** -&gt; Se queda sin vida -&gt; desaparece del juego.

Torres de ataque
----------------

-   **Alcance**: Atributo estático. Radio en el cual es capaz de atacar
    > a los enemigos. Aumenta con las mejoras.

-   **Daño**: Atributo estático. Vida que le quita a los enemigos en
    > cada disparo. Podría aumentar dependiendo del nivel de
    > mejora.(Aumenta con el nivel de la torreta con un factor por nivel
    > que podrá ser reajustado para ajustar la dinámica del juego).

-   **Ratio de disparo**: Atributo estático. Tiempo que pasa entre dos
    > disparos consecutivos. Aumentar con las mejora.

-   **Radio de explosión**: Atributo estático. Indica el rango de efecto
    > del proyectil (para cohetes).

-   **Bicho objetivo**

***Estados*** (además de los anteriores)

-   **Apuntando** -&gt; Cuando un bicho entra en el radio de ataque.

<!-- -->

-   **Atacando** -&gt; Disparando a los bichos.

Torre recolectora:
------------------

-   **Ratio de recolección**: Atributo estático. Podría aumentar
    > dependiendo del nivel de mejora.

-   **Cantidad de la recolección**: Atributo estático. Podría aumentar
    > dependiendo del nivel de mejora.

-   **Incremento del precio de mejora:** Atributo estático. Indica
    > cuánto aumenta el precio de cada mejora. +100 en el precio de cada
    > mejora.

***Estados*** (además de los anteriores)

-   **Recolectando**-&gt; Obteniendo recursos.

Escudo
------

-   **Duración**: Atributo estático. Tiempo que tarda en desaparecer.
    > Aumenta con mejoras.

-   **Precio**: Atributo estático. Cantidad de recursos que perdemos al
    > construirla

***Estados***

-   **En espera** -&gt; No se ha colocado ningún escudo en la torre.

-   **Protegiendo** -&gt; Defendiendo a la torre de ser atacada

-   **Fin del tiempo** -&gt; Pasa el tiempo de duración y desaparece del
    > mapa. ¿Sería más bien un desencadenante?

-   **Destruido** -&gt; Los bichos han destrozado el escudo y desaparece
    > del mapa

Base
----

-   **Vida**: 50

Torreta ametralladora
---------------------

-   **Vida**: 30

-   **Precio**: 100

-   **Nivel**: 1

-   **ID**: 1

-   **Alcance**: 20

-   **Daño**: 5

-   **Ratio de disparo**: 4 balas/segundo

-   **Radio de explosión**: -

-   **Incremento de precio de mejora**: +20

Torreta cañón
-------------

-   **Vida**: 30

-   **Precio**: 150

-   **Nivel**: 1

-   **ID**: 2

-   **Alcance**: 20

-   **Daño**: 20

-   **Ratio de disparo**: 1 bala cada 3 segundos

-   **Radio de explosión**: -

-   **Incremento de precio de mejora**: +30

Torreta de misiles
------------------

-   **Vida**: 20

-   **Precio**: 250

-   **Nivel**: 1

-   **ID**: 3

-   **Alcance**: 25

-   **Daño**: 50

-   **Ratio de disparo**: 1 misil cada 5 segundos

-   **Radio de explosión**: 5

-   **Incremento de precio de mejora**: +0, +20

Diagrama de estados
-------------------

![](media/image17.png){width="6.267716535433071in"
height="3.236111111111111in"}

DEFINICIÓN DE MEJORAS
=====================

**Descripción**

Las mejoras se adquieren con puntos de experiencia (*XP*). Éstos se
consiguen en las siguientes situaciones y cantidad:

-   Por cada logro conseguido obtenemos 10 XP

-   Si perdemos y destruyen nuestra base ganamos XP en función del
    > progreso de la misión.

Cada mejora se puede actualizar hasta 3 niveles y cada una de estas
actualizaciones costará 20 XP, 25 XP y 30 XP respectivamente.

**Atributos:**

Atributos **comunes a todas las mejoras**:

Atributo dinámico: **Nivel**; valores = {0,1,2,3}.

Atributo dinámico: **Coste de actualización**; valores = {20,25,30}.

Atributos de ***Shooting radius***:

Atributo estático: **Factor de incremento de radio de alcance**

Atributos de ***Speed of repair***:

Atributo estático: **Factor de incremento de velocidad de reparación**

Atributos de ***Weapons armoring***:

Atributo estático: **Factor de incremento de salud**

Atributos de ***Refund for selling weapons***:

Atributo estático: **Factor de incremento de valor de venta**

Atributos de ***Support recharge time***:

Atributo estático: **Factor de decremento de tiempo de recarga de
objetos especiales**

Atributos de ***Support power***:

Atributo estático: **Factor de incremento de potencia de objetos
especiales**

*Para todas las mejoras, se multiplicaría el nivel actual de cada una
por su factor de incremento/decremento correspondiente con el fin de
obtener su capacidad total de mejora.*

DEFINICIÓN DEL MAPA
===================

Todos los mapas
---------------

**Atributos**

-   **Recursos iniciales**: Atributo estático. Indica la cantidad de
    > recursos iniciales para ese nivel.

-   **Número de oleadas**: Atributo estático. Indica el número de rondas
    > que deberá resistir el jugador para ganar el nivel.

-   **Oleada actual:** Atributo dinámico. Indica el número de oleada en
    > la que se encuentra el jugador.

-   **Dificultad**: Atributo estático. Indica la dificultad del nivel.
    > Valores={Fácil,Normal,Ultimate}. Cada nivel de dificultad
    > aumentará el número de enemigos que aparezcan por oleada.

-   **ID**: Atributo estático.

-   **Tipo de terreno:** Atributo estático. Una lista de posiciones del
    > mapa que indica que tipo de terreno es cada posición. Valores:

    -   Pared no ocupable: Posición del mapa no ocupable por ningún
        > objeto jugable.

    -   Suelo válido: Posición por la que los enemigos podrán moverse.

    -   Posición de torreta libre: Posición que indica donde puede
        > construirse una torreta de ataque.

    -   Posición de torreta ocupada: Posición que indica donde está
        > construida una torreta de ataque.

    -   Posición de extracción de recursos libre: Posición que indica
        > donde puede colocarse una torreta de recursos.

    -   Posición de extracción de recursos ocupada: Posición que indica
        > donde se ha colocado una torreta de recursos.

-   **Cantidad de recompensa por oleada**: Atributo estático. Indica los
    > recursos de recompensa que se obtienen al terminar una oleada. En
    > función de la velocidad a la que el jugador termine la ronda y de
    > paso a la siguiente mediante un click en siguiente oleada, se
    > ganarán más o menos recursos.

-   **Tipos de torretas permitidas en el nivel**: Atributo estático.
    > Indica las torretas que podrán usarse en el nivel. Valores =
    > {Torreta ametralladora, Torreta cañón, Torreta lanzacohetes,
    > Torreta recolectora}.

-   **Tipos de acciones de torretas permitidas en el nivel**: Atributo
    > estático. Indica las acciones disponibles al hacer clic en una
    > torreta colocada. Valores={Vender, Mejorar, Reparar, Escudo}.

-   **Tipos de habilidades permitidas en el nivel:** Atributo estático.
    > Indica las habilidades que puede usar el jugador en el nivel.
    > Valores = {Bombardeo, Misil nuclear}.

-   **Oleadas:** Atributo estático. Colección de tipos de enemigos que
    > indicarán los enemigos que aparecerán en dicha oleada.

-   **Experiencia final:** Atributo estático. Indica la cantidad de
    > experiencia que obtiene el jugador por ganar el nivel. Esta
    > experiencia dependerá de la calidad de cómo haya resuelto el
    > nivel.

Oleada
------

-   **Tipos de enemigos**: Atributo estático. Valores = {Tipos de
    > enemigos}. Un array de tipos de enemigos que se irán lanzando en
    > la oleada. Cada posición del array identificará a un tipo de
    > enemigo y el valor de la posición indicará la cantidad de enemigos
    > de ese tipo.

DEFINICIÓN DE LOS NIVELES
=========================

Nivel 1
-------

**Atributos**

-   **Recursos iniciales**: 600.

-   **Número de oleadas**: 5.

-   **Dificultad**: Valores={Fácil 0.8,Normal 1,Ultimate 1.2}.

-   **ID**: 0.

-   **Cantidad de recompensa por oleada**: 8 de recursos por cada
    > segundo restante hasta que se lance automáticamente la oleada.

-   **Tipos de torretas permitidas en el nivel**: Valores = {Torreta
    > ametralladora, Torreta cañón, X, X}.

-   **Tipos de acciones de torretas permitidas en el nivel**:
    > Valores={Vender, Mejorar, Reparar, X}.

-   **Tipos de habilidades permitidas en el nivel:**Valores =
    > {Bombardeo, X}.

-   **Oleadas:** Valores = {

    -   {Oleada0(20,0s,T1),(5,10sT2)}

    -   {Oleada1(15,0s),(12,3s)},

    -   {Oleada2(20,0s,T1),(5,10s,T2),(10,20s,T1)},

    -   {Oleada3(20,0s,T1),(9,10s,T2),(15,20s,T1),(15,20s,T2)},

    -   {Oleada4(30,0s,T1),(9,10s,T2),(15,20s,T1),(17,20s,T2)},

-   }

-   **Experiencia final:** 10xp por logro completado.

Nivel 2
-------

**Atributos**

-   **Recursos iniciales**: 400.

-   **Número de oleadas**: 7.

-   **Dificultad**: Valores={Fácil 0.8,Normal 1,Ultimate 1.2}.

-   **ID**: 0.

-   **Cantidad de recompensa por oleada**: 8 de recursos por cada
    > segundo restante hasta que se lance automáticamente la oleada.

-   **Tipos de torretas permitidas en el nivel**: Valores = {Torreta
    > ametralladora, Torreta cañón, Torreta lanzacohetes, Torreta
    > recolectora}.

-   **Tipos de acciones de torretas permitidas en el nivel**:
    > Valores={Vender, Mejorar, Reparar, Escudo}.

-   **Tipos de habilidades permitidas en el nivel:**Valores =
    > {Bombardeo, X}.

-   **Oleadas:** Valores = {

    -   {Oleada0(20,0s,T1),(5,10sT2)}

    -   {Oleada1(15,0s),(12,3s)},

    -   {Oleada2(20,0s,T1),(5,10s,T2),(10,20s,T1)},

    -   {Oleada3(20,0s,T1),(9,10s,T2),(15,20s,T1),(15,20s,T2)},

    -   {Oleada4(30,0s,T1),(9,10s,T2),(15,20s,T1),(17,20s,T2)},

-   }

-   **Experiencia final:** 10xp por logro completado.

Nivel 3
-------

**Atributos**

-   **Recursos iniciales**: 400.

-   **Número de oleadas**: 8.

-   **Dificultad**: Valores={Fácil 0.8,Normal 1,Ultimate 1.2}.

-   **ID**: 0.

-   **Cantidad de recompensa por oleada**: 8 de recursos por cada
    > segundo restante hasta que se lance automáticamente la oleada.

-   **Tipos de torretas permitidas en el nivel**: Valores = {Torreta
    > ametralladora, Torreta cañón, Torreta lanzacohetes, Torreta
    > recolectora}.

-   **Tipos de acciones de torretas permitidas en el nivel**:
    > Valores={Vender, Mejorar, Reparar, Escudo}.

-   **Tipos de habilidades permitidas en el nivel:**Valores =
    > {Bombardeo, Misil nuclear}.

-   **Oleadas:** Valores = {

    -   {Oleada0(20,0s,T1),(5,10sT2)}

    -   {Oleada1(15,0s),(12,3s)},

    -   {Oleada2(20,0s,T1),(5,10s,T2),(10,20s,T1)},

    -   {Oleada3(20,0s,T1),(9,10s,T2),(15,20s,T1),(15,20s,T2)},

    -   {Oleada4(30,0s,T1),(9,10s,T2),(15,20s,T1),(17,20s,T2)},

-   }

-   **Experiencia final:** 10xp por logro completado.

REGLAS
======

TORRES
------

  -------------------------------------------------------------------------------------------
  **Apuntar a bicho**
  -------------------------------------------------------------------------------------------
  -   Para fijar objetivo, debe haber un bicho dentro del rango.
  
  -   Solo se puede fijar un único objetivo.
  
  -   No se puede cambiar de objetivo fijado hasta que el bicho muera o salga del alcance.
  
  -   Si varios bichos detectados, se fija como objetivo el enemigo más cercano a la torre.
  
  -   No se puede fijar un objetivo que esté detrás de una pared del mapa.
  
  -------------------------------------------------------------------------------------------

  -------------------------------------------------------------------------------------------------------------------------------------------
  **Atacar a bicho**
  -------------------------------------------------------------------------------------------------------------------------------------------
  -   La torre atacará al objetivo.
  
  -   Solo se puede disparar a un bicho mientras sea el objetivo.
  
  -   Mientras disparando objetivo, objetivo.vida -= torre.daño
  
  -   El daño realizado se ajustará al valor proporcionado por el **algoritmo de cálculo de daño** especificado al final de este documento.
  
  -------------------------------------------------------------------------------------------------------------------------------------------

  -----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  **Reparar torre**
  -----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  -   La reparación será voluntaria y manual.
  
  -   Solo se podrá reparar si hay recursos suficientes.
  
  -   Solo se podrá reparar si la vida de la torreta está por debajo del 100%.
  
  -   El coste de la reparación se cobrará justo al ordenarla.
  
  -   El coste de la reparación dependerá de la vida que le falte a la torre en el momento de la reparación. coste = maxHealth - currentHealth
  
  -   Una torre podrá recibir daño mientras se está reparando.
  
  -   Solo se reparará la cantidad de vida pagada en el momento de ordenar la reparación.
  
  -   No puede cancelarse la reparación.
  
  -   Mientras se está reparando la torre no puede disparar ni apuntar.
  
  -   Si click en reparar y currentHealth &lt; maxHealth, guardamos maxHealth - currentHealth y cada X tiempo incrementamos currentHealth y decrementamos el Health guardado y repetimos hasta que Health guardado == 0
  
  -----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

  --------------------------------------------------------------------------------------------------------------------------
  **Colocar escudo**
  --------------------------------------------------------------------------------------------------------------------------
  -   Solo se puede utilizar si se tienen recursos suficientes.
  
  -   Absorberá todo el daño recibido de la torre hasta que se acabe la duración del escudo o baje la vida del escudo a 0.
  
  -   El escudo tendrá una duración determinada.
  
  -   El coste de colocar el escudo es el mismo para todas las torretas.
  
  --------------------------------------------------------------------------------------------------------------------------

  ---------------------------------------------------------------------------------------------------------------------------------------
  **Mejorar torre**
  ---------------------------------------------------------------------------------------------------------------------------------------
  -   Acción voluntaria y manual.
  
  -   Sólo se puede mejorar si se tienen recursos suficientes.
  
  -   Sólo podrá mejorarse una torre hasta nivel 3 como máximo.
  
  -   Al mejorar una torre se incrementará el precio de venta de una torre.
  
  -   Al mejorar una torre se incrementará el daño de esta, la cadencia de disparo y el radio de explosión (solo para el lanzacohetes).
  
  -   El coste es el mismo para todas las torretas.
  
  ---------------------------------------------------------------------------------------------------------------------------------------

  -------------------------------------------------------------------------------------------------------------------------------------------
  **Vender torre**
  -------------------------------------------------------------------------------------------------------------------------------------------
  -   Acción voluntaria y manual.
  
  -   Solo se puede vender una torre viva.
  
  -   Los recursos obtenidos al vender dependerá del tipo de torreta y nivel de mejora. recursos obtenidos = (costeBase / 2) \* nivelMejora
  
  -   Al vender la torre el espacio ocupado por la torre volverá a estar disponible para colocar una nueva torre.
  
  -------------------------------------------------------------------------------------------------------------------------------------------

  ----------------------------------------------------------------------------------------------------
  **Colocar torre**
  ----------------------------------------------------------------------------------------------------
  -   Acción voluntaria y manual.
  
  -   Solo podrá colocarse una torre en las posiciones del mapa habilitadas para ello.
  
  -   No podrá colocarse ninguna torre en una posición donde ya haya otra torre construida.
  
  -   Solo podrá colocarse una torre si se dispone de los recursos suficientes para la construcción.
  
  -   Las torretas colocadas aparecerán a nivel de mejora 1.
  
  ----------------------------------------------------------------------------------------------------

  --------------------------------------------------------------------------------------------------------------
  **Destruirse**
  --------------------------------------------------------------------------------------------------------------
  -   Acción automática.
  
  -   Una torre será destruida cuando la vida de dicha torre llegue a 0.
  
  -   Al destruirse, desaparecerá de la posición que ocupase y se podrá colocar una torreta en dicha posición.
  
  --------------------------------------------------------------------------------------------------------------

BICHOS
------

  ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  **Moverse**
  ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  -   Un bicho sólo podrá moverse por su línea de trayectoria.
  
  -   Un bicho se moverá a una velocidad preestablecida según el tipo de bicho.
  
  -   Cuando un bicho se mueva irá actualizando su posición interna.
  
  -   Un bicho no puede avanzar en su trayectoria si hay otro bicho de su misma trayectoria que le impida el paso, se tiene que detener.
  
  -   Un bicho no puede avanzar en su trayectoria si hay otro bicho de distinta trayectoria que le impida el paso, debe saltar el bicho bloqueante o ser saltado y en caso de ser saltado seguirá con su movimiento normal.
  
  ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

  ----------------------------------------------------------------------------------------
  **Morirse**
  ----------------------------------------------------------------------------------------
  -   Cuando un bicho se queda sin vida, desaparece del mapa.
  
  -   Cuando un bicho muere y desaparece del mapa no puede realizar ninguna otra acción.
  
  ----------------------------------------------------------------------------------------

  ----------------------------------------------------------------------------------------------------------------------------------------------
  **Atacar a torre**
  ----------------------------------------------------------------------------------------------------------------------------------------------
  -   No puede atacar a una torre que esté fuera de su alcance de ataque.
  
  -   Un bicho sólo puede atacar a una torre a la vez (esta regla podrá desaparecer si finalmente incluimos el radio de ataque de los bichos).
  
  -   Un bicho estará atacando a la misma torre hasta que ésta sea destruida o el bicho se muera.
  
  -   Mientras atacando objetivo, objetivo.vida -= bicho.daño
  
  -   El daño realizado se ajustará al valor proporcionado por el **algoritmo de cálculo de daño** especificado al final de este documento.
  
  ----------------------------------------------------------------------------------------------------------------------------------------------

  **Apuntar a torre**
  ------------------------------------------------------------
  -   El bicho se orientará hasta tener a la torre enfrente.
  

  --------------------------------------------------------------
  **Saltar**
  --------------------------------------------------------------
  -   Sólo se podrá saltar un bicho de una única vez.
  
  -   El bicho después del salto continuará con su movimiento.
  
  --------------------------------------------------------------

  **Detenerse**
  --------------------------------------------------------------------------------------------------
  -   El bicho comenzará a moverse de nuevo cuando no haya ningún bicho bloqueando su trayectoria.
  

OBJETOS ESPECIALES
------------------

  **Seleccionar tipo de acción especial**
  -----------------------------------------------------------------------------------------
  -   No se puede seleccionar una bomba si está bloqueada o si está en estado de recarga.
  

  -------------------------------------------------------------------------------------------------
  **Apuntar**
  -------------------------------------------------------------------------------------------------
  -   No se puede utilizar la acción especial sino se ha seleccionado un tipo de bomba en el HUD.
  
  -   Para apuntar necesitas situar el ratón encima de una zona cualquiera del mapa
  
  -   Se puede cancelar el apuntado con el botón derecho del ratón.
  
  -------------------------------------------------------------------------------------------------

  ------------------------------------------------------------------------------------------
  **Disparar**
  ------------------------------------------------------------------------------------------
  -   Sólo se puede disparar si se ha apuntado previamente.
  
  -   Si se intenta disparar fuera de la zona de disparo, no se provoca acción alguna.
  
  -   Al disparar se establece en el HUD el objeto que se haya usado al estado de recarga.
  
  ------------------------------------------------------------------------------------------

MAPA
----

  ----------------------------------------------------------------------------------------------------------------------------------------------------------------------
  **Aumentar recursos**
  ----------------------------------------------------------------------------------------------------------------------------------------------------------------------
  -   Cada nivel tiene asociada una cantidad inicial de recursos.
  
  -   Al morir un bicho se aumenta una cantidad determinada los recursos en función del tipo de bicho.
  
  -   Al vender una torre se aumenta una cantidad determinada los recursos en función del tipo de torre, las mejoras compradas de la misma y el nivel de investigación
  
  -   Cuando una base recolectora finaliza un ciclo de recolección se suman los recursos obtenidos al total.
  
  ----------------------------------------------------------------------------------------------------------------------------------------------------------------------

  -------------------------------------------------------------------------------------------------------------------------------------------
  **Lanzar oleada**
  -------------------------------------------------------------------------------------------------------------------------------------------
  -   Se incrementa el número de la oleada con cada oleada completada.
  
  -   Solo se podrán lanzar oleadas mientras no se alcance el límite del nivel.
  
  -   Entre oleada y oleada hay un tiempo máximo de espera, este se puede reducir si todos los bichos de la oleada anterior son eliminados.
  
  -   Cada oleada contiene un número de bichos determinado para cada tipo de bicho.
  
  -   Lanzar la oleada antes de tiempo otorga recursos: recursos obtenidos = tiempo restante \* 2
  
  -------------------------------------------------------------------------------------------------------------------------------------------

  ------------------------------------------------------------------------------------------------------------------------------------------------------------
  **Otras reglas**
  ------------------------------------------------------------------------------------------------------------------------------------------------------------
  -   Cada nivel de partida tiene asociado tipos de torretas, mejoras y objetos especiales desbloqueados.
  
  -   El mapa tiene un número limitado de posiciones para colocar torres, este depende del nivel.
  
  -   Para superar un nivel se deben eliminar todos los bichos de todas las oleadas sin que la base sea destruida.
  
  -   El nivel se termina como incompleto si la base pierde todos sus puntos de vida. En ese caso, se otorgan 10XP si se han completado la mitad de oleadas.
  
  ------------------------------------------------------------------------------------------------------------------------------------------------------------

ALGORITMO DE CÁLCULO DE DAÑO
----------------------------

  --------------------------------------------------
  > **cont\_alto = 0;**
  >
  > **cont\_bajo = 0;**
  >
  > **aleatorio\_general = 0;**
  >
  > **factor\_daño\_aleatorio = 0;**
  >
  > **Si cont\_alto &gt; 5**
  >
  > **factor\_daño\_aleatorio = Random(0.2,0.7);**
  >
  > **cont\_alto = 0;**
  >
  > **Sino Si cont\_bajo &gt; 5**
  >
  > **factor\_daño\_aleatorio = Random(0.8,1);**
  >
  > **cont\_bajo = 0;**
  >
  > **Sino**
  >
  > **aleatorio\_general = Random(0,1);**
  >
  > **Si aleatorio\_general == 0**
  >
  > **factor\_daño\_aleatorio = Random(0.2,0.7);**
  >
  > **cont\_bajo++;**
  >
  > **Sino si aleatorio\_general == 1**
  >
  > **factor\_daño\_aleatorio = Random(0.8,1);**
  >
  > **cont\_alto++;**
  --------------------------------------------------

TABLA DE MAPPINGS
=================

  **1. Physical Input → World**
  ------------------------------- -------------- --------------------------- ----------------------
  **ID**                          **Elemento**   **Acción**                  **Efecto**
  1.1                             Torre          Click izquierdo del ratón   Selecciona una torre

  **2. World → Physical Output**
  -------------------------------- -------------- --------------------------------------------------------- -------------------------
  **ID**                           **Elemento**   **Acción**                                                **Efecto**
  2.1                              Cámara Mapa    Click en cualquier sitio cuando otra cámara está activa   Cambia la cámara activa
  2.2                              Cámara Torre   Click botón derecho en una torre                          Cambia la cámara activa
  2.3                              Cámara Bicho   Click en un bicho                                         Cambia la cámara activa

  **3. Physical Input → Virtual Interface**
  ------------------------------------------- ------------------------- --------------------------- ------------------------------------------------------------------------------------------
  **ID**                                      **Elemento**              **Acción**                  **Efecto**
  3.1                                         Botón “With Sound”        Click izquierdo del ratón   Carga el juego con sonido
  3.2                                         Botón “Muted”             “                           Carga el juego sin sonido
  3.3                                         Botón “Credits”           “                           Muestra en pantalla los créditos
  3.4                                         Botón “More Games”        “                           Abre una nueva pestaña/ventana con juegos independientes a este
  3.5                                         Botón “Options”           “                           Abre un menú de opciones con 3 botones: Autopause, Sound y Music
  3.6                                         Botón “Play”              “                           Abre el menú de *slots* de partidas
  3.7                                         Botón “Nueva Partida”     “                           Se carga el selector de niveles
  3.8                                         Botón “Cargar Partida”    “                           Se carga el selector de niveles
  3.9                                         Botón “Main menu”         “                           Se carga la pantalla de inicio
  3.10                                        Botón “Research”          “                           Se accede al menú de mejoras
  3.11                                        Nivel disponible          “                           Se selecciona un el nivel para jugar
  3.12                                        Botón “Fight”             “                           Comenzar el nivel seleccionado
  3.13                                        Botón “Avance rápido”     “                           Se entra en modo avance rápido
  3.14                                        Botón “Pause”             “                           Se pausa la partida
  3.15                                        Botón “Menú del juego”    “                           Se despliega el menú del juego
  3.16                                        Botones de construcción   “                           Se selecciona el tipo de torreta a construir, se pasa a estado “Construir torreta”
  3.17                                        Botones de habilidades    “                           Se selecciona el tipo de ataque especial a utilizar, se pasa a estado “Lanzar habilidad”
  3.18                                        Botón comenzar horda      “                           Comienza el ataque de una nueva horda de bichos
  3.19                                        Botón “Reparar torre”     “                           Torre seleccionada pasa a estado “Reparando”
  3.20                                        Botón “Vender Torre”      “                           Se vende la torre seleccionada
  3.21                                        Botón “Mejorar Torre”     “                           La torre seleccionada sube de nivel
  3.22                                        Botón “Escudo”            “                           Activa un escudo protector en la torre seleccionada
  3.23                                        Botón “Cerrar”            “                           Cierra el pop-up o el modal seleccionado

  **4. Virtual Interface → World**
  ---------------------------------- -------------------------------- ------------ --------------------------------------------
  **ID**                             **Elemento**                     **Acción**   **Efecto**
  4.1                                Comenzar el nivel seleccionado   3.12         Se inicia el nivel
  4.2                                Modo avance rápido               3.13         Se aumenta el doble la velocidad del mundo
  4.3                                Se pausa la partida              3.14         Se pausa el mundo

  **5. World → Virtual Interface**
  ---------------------------------- -------------------- ------------------------------- ----------------------------------------
  **ID**                             **Elemento**         **Acción**                      **Efecto**
  5.1                                Torre seleccionada   1.1                             Mostrar HUD de la torre seleccionada
  5.2                                Torre                Recibe daño                     Reducir vida
  5.3                                Bicho                Recibe daño                     Reducir vida
  5.4                                Habilidad especial   Finaliza el tiempo de recarga   Habilidad especial disponible
  5.5                                Bicho                El bicho muere                  Se incrementan los recursos
  5.6                                Nueva horda          3.18 o finaliza el tiempo       Se inicia el ataque de una nueva horda

  **6. Virtual Interface → Physical Output**
  -------------------------------------------- ---------------------------------------- ------------ ------------------------------------------------------
  **ID**                                       **Elemento**                             **Acción**   **Efecto**
  6.1                                          Mostrar HUD de una Torre                 5.1          Muestra por pantalla el menú desplegable de la torre
  6.2                                          Reducir vida                             5.2 y 5.3    Se actualiza la barra de vida
  6.3                                          Habilidad especial disponible            5.4          Se ilumina el icono de la habilidad
  6.4                                          Se incrementan los recursos              5.5          Se actualiza el indicador
  6.5                                          Se inicia el ataque de una nueva horda   5.6          Se actualiza el indicador


