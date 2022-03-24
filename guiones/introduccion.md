# Organización de lecciones

## ¿Qué es programar?

Muchos cursos de programación empiezan enseñándote a hacer un hola mundo, nosotros también, pero
creo que es importante que primero sepamos qué coño estamos haciendo, y por eso hago este mini vídeo
sobre qué es programar y cómo funciona un ordenador.

Porque probablemente ya sepas cómo funciona la interfaz de un ordenador, sabrás instalar un programa,
gestionar ficheros e incluso puede que trastear con configuraciones del sistema. Y si alguna vez has
montado un PC también sabrás los componentes básicos que tiene: la CPU, la RAM, placa base, disco duro
y tarjeta gráfica. E incluso puede que tengas una ligera idea sobre qué hace cada uno. A saber:
- Placa base: Comunica el resto de componentes
- CPU: Ejecuta instrucciones
- RAM: Almacena datos de programas en ejecución y es volátil, es decir, los datos sólo están ahí mientras
el programa esté en ejecución.
- Disco duro: Almacena datos de manera persistente.
- Tarjeta gráfica: Realiza cálculos gráficos
Pero ¿cómo se contectan estos dos niveles? ¿Magia negra? En eso es en lo que consiste la programación.

## CPU y RAM

Los componentes principales de un ordenador son la CPU y la RAM. El resto son añadidos que le dan
funcionalidades útiles, pero se puede hacer un ordenador que funcione sin ellos. No se puede hacer sin
CPU o sin RAM. ¿Cómo funcionan? No vamos a explicar cómo funciona un PC moderno si un hipotético ordenador
que me acabo de inventar que es el más simple posible.

Empecemos por la RAM. En realidad es muy simple: es una serie de celdas de memoria a las cuales se puede
acceder mediante una dirección, tanto para leer datos como para escribirlos. Es decir, tiene 3 puertos. Si,
en el primero pones la dirección 7, en el segundo pones modo escritura y en el tercero el número 42 (todo
esto en binario, claro), en la celda 7 se guardará un número 42 al que después podrás acceder escribiendo
la dirección y poniendo la memoria en modo lectura. No tiene más.

La CPU, como he dicho, ejecuta instrucciones. Cuando los ingenieros la diseñan incluye un set de instrucciones
básicas que puede ejecutar y una pequeña memoria interna. Se conecta a la RAM y en su memoria guarda una
referencia a la dirección de la RAM de la próxima instrucción (llamado contador de programa). Date cuenta que
la RAM contiene código binario, y éste puede ser interpretado como instrucciones, como números o como lo
que nos de la gana.

Bueno, digamos que en la RAM hay una serie de instrucciones y datos que han llegado ahí por arte de magia,
la CPU cargará la instrucción indicada por el contador de programa, la realizará y pasará a la siguiente
instrucción, y así en bucle hasta que llegue al final del programa. Estas instrucciones son del estilo "suma
estos números", "compara estos valores", "continúa desde este punto en lugar de desde la siguiente instrucción".

## Programación de bajo y de alto nivel

¿Y cómo se programa este ordenador? No podemos escribir binario, así que la manera más sencilla es con lenguaje
ensamblador. Este lenguaje sencillamente hace una transformación 1 a 1 de instrucciones escritas como texto y
su código máquina, que por cierto, así es como se llaman las instrucciones que el procesador puede interpretar
directamente.

Y este es un buen momento para introducir el concepto de capas de abstracción. En los 80 sí que se programaba
en ensamblador, pero hoy en día, salvo casos muy concretos, ya no se usa, se usan lenguajes de alto nivel,
es decir, lenguajes que tienen estructuras más complejas las cuales te abstraen de las complejidades de la
circuitería. En este sistema de capas, cuanto cuando el código interactúa directamente con los circuitos, se
dice que es de bajo nivel. Cuando no interactúa con la circuitería si no con otro pedazo de código (el cual
podría a su vez interactuar con una o varias capas más antes de llegar los circuitos), se dice que es de alto
nivel.

Los ordenadores actuales tienen muchas más funcionalidades, notablemente la entrada/salida, con distintos
métodos para que el programa pueda recibir datos de teclado, ratón, mando, red o periférico y también para que 
pueda enviarlos a la pantalla, por red o a periféricos. Sin embargo el funcionamiento básico sigue siendo el
mismo, siguen siendo instrucciones que se ejecutan en un orden determinado para realizar una serie de modificaciones
sobre unos datos. Como por ejemplo transformar unos datos recibidos por red e integrarlos con una interfaz, o
cargar un fichero que contiene un vídeo y mostrarlo por pantalla.

En el siguiente capítulo empezaremos a hablar de los fundamentos de la programación con Python. ¿Por qué Python?
Pues sencillamente porque es un lenguaje de sintaxis sencilla y que no introduce complejidad innecesaria si no
se desea, así que para aprender es una herramienta muy buena.
